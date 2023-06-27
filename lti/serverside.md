The basic purpose of an LTI tool is to provide a way for content hosted outside of an LMS to be embedded within the LMS interface.

At its simplest, an LTI tool you'd create for this purpose would need to:

Handle LTI Launch Requests: When a user clicks on the link for your tool in their LMS, the LMS will send an LTI launch request to your tool. This request includes information about the user, the course, and the context of the launch. Your tool needs to be able to receive and process this launch request.

Authenticate the Launch Request: The LTI launch request will be signed with a shared secret to verify its authenticity. Your tool needs to be able to authenticate the request using this shared secret.

Display the Content: Once the launch request has been authenticated, your tool needs to display the relevant content to the user. This is where your HTML page that imports and displays the markdown comes in. You could have your tool fetch the markdown content based on information in the launch request, convert it to HTML using something like marked.js, and then display it to the user.

Here's a simplified structure of what the server-side code of your tool might look like:

javascript
Copy code
const express = require('express');
const lti = require('ltijs').Provider;

const app = express();

// Set up LTI provider
const ltiProvider = new lti.Provider('LTIKEY', 
  {
    "iss": "LTIURL",
    "client_id": "LTI_CLIENT_ID"
  }, 
  { 
    staticPath: './public', // Path to static files
    cookies: {
      secure: false, // Set secure to true if the platform is in a secure domain
      sameSite: 'None' // Set sameSite to None if the platform is in a secure domain
    }
  }
);

// On connect success
ltiProvider.onConnect((token, req, res) => {
  const filePath = req.body.path; // This would be sent in the LTI launch request
  res.sendFile(filePath); // Serve the HTML file
});

// Setup provider
ltiProvider.setup().then(() => app.listen(3000, () => console.log('LTI tool is running')));
In this example, I've used the ltijs library, which is a helper library for creating LTI tools in Node.js. The server listens for LTI launch requests, and when it receives one, it sends the corresponding HTML file in response.

This is a very simplified version of what your tool could look like, and in a real-world situation there would be many more considerations to take into account, like security, error handling, and scalability. But hopefully, this gives you a basic idea of what's involved in creating an LTI tool.

Also, please note that the code is for illustrative purposes only and may not work if copied and pasted directly.