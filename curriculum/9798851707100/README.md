# Beginning Midjourney

* [Amazon Kindle](https://kdp.amazon.com/amazon-dp-action/us/dualbookshelf.marketplacelink/B0CBRK83LC)
* Amazon Paperback (in review with AKDP)
* [PDF](https://github.com/joone-org/curriculum.joone.org/blob/main/curriculum/9798851707100/MidJourney.pdf)
* [Microsoft Word](https://github.com/joone-org/curriculum.joone.org/blob/main/curriculum/9798851707100/MidJourney.docx)
* [Markdown](https://github.com/joone-org/curriculum.joone.org/blob/main/curriculum/9798851707100/midjourney.md)
* Canvas (in production)<br><br>

This guide offers an insightful peek into the mesmerizing world of AI-driven creativity. Within its compact format, you'll find a straightforward tutorial on maximizing the capabilities of the Midjourney AI service on Discord and creating compelling prompts with ChatGPT. Alongside this guide, there's an array of vibrant, AI-generated visuals created from simple emoji prompts, demonstrating the convergence of technology and imagination in a tangible and inspiring manner.

This guide is shared under the Creative Commons Attribution - NonCommercial - NoDerivatives (CC BY-NC-ND) License by Joone 501(c)(3), a non-profit aimed at democratizing K-12 education. As such, you're free to share and use it while giving appropriate credit. Ideal for educators, tech enthusiasts, parents, or anyone interested in the intersection of AI and art, it's part of a broader effort to make AI accessible to all.<br><br>

![steam_ship](https://github.com/joone-org/curriculum.joone.org/assets/137654670/aa2d91df-bf2a-476e-b9fa-4f5d33ec6ed4)
<div align="center">
  
[Full resolution 8K image here](https://github.com/joone-org/curriculum.joone.org/blob/main/curriculum/9798851707100/steam_ship_8k.png)

</div>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>
<p>To use ChatGPT as a prompt generator, copy all of the following text and paste it into ChatGPT's input.<br>When it responds with the question, provide a description of the image you want it to generate, or simply insert some emoji.</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

[Midjourney](https://www.midjourney.com/) is a
[Discord](https://discord.com/)-based AI service that turns textual prompts into unique images. It can handle prompts up to around 60 words, but the influence of each word diminishes as the length of the prompt increases. To optimize results, structure your prompts concisely and directly, aiming for a clear, sequential style rather than long, descriptive sentences.

> Prompts follow this formula: */imagine \[Subject and Setting\]. \[Style Keywords\]. \[Parameters\]*

<br>

**Subject and Setting**:

- To optimize prompts, start with a clear subject (a *'colossal'* elephant differs visually from a *'big'* one), and add personality and emotion for more expressive imagery. Use collective nouns instead of quantities (*'herd of elephants*' over *'3 elephants*') and position subjects within a detailed environment (*'bathing at sunset in the Serengeti during fall'*). Unspecified details are randomized, so be as specific as you can. Use nuanced adjectives (*'tranquil', 'melancholic', 'ecstatic', etc.*) to add mood.

> Example: Instead of just ‘*elephant'*, use "*A tranquil scene of a herd of colossal African elephants bathing at sunset in the Serengeti watering hole.*"

<br>

**Style Keywords**:

- Midjourney interprets a nearly infinite range of artistic instructions. Define the medium (*e.g., 'photo', '3D sand sculpture', 'linocut print'*). Describe your desired lighting (*e.g., 'soft ambient', 'neon', 'candle-lit'*), and pair it with a color scheme (*e.g., 'monochromatic', 'earth tones', 'cyberpunk neon'*). Arrange your scene using terms like (*e.g., 'low-angle shot', 'bird's eye view', 'rule of thirds composition'*). Mention the desired artistic style (*e.g., 'Cubism', 'Anime', 'Film Noir', 'Banksy-like street art'*), or specify the historical period or specific environment for added context. Include additional descriptors (*e.g., 'shallow depth of field', 'vignette', 'splatter effect'*) to refine your scene. For high realism, specify camera effects, settings, setup (*e.g., 'Canon EOS 5D Mark IV, using a 24-70mm lens at f/2.8, with a long exposure of 15 seconds'*).

- Maintain concise clarity with each keyword, and don't confine yourself to the provided examples. Whether it's the aesthetics of a *'polaroid snapshot'*, the drama of *'baroque lighting'*, the composition of a '*kaleidoscope*', or the eccentricity of a *'cyberpunk art style'*, MidJourney can understand and execute it all, so don't hesitate to experiment with unusual mediums, innovative lighting, creative compositions, and unexplored artistic styles.

> Example: "*A tranquil scene of a herd of colossal African elephants bathing at sunset in the Serengeti watering hole. Watercolor, golden hour, warm sunset palette, panoramic eye-level view, Impressionistic, vintage color grading.*"

<br>

**Parameters**:

- "*::*" enables separate specification of different image components.
  *'African elephants::bathing at sunset'* tells Midjourney to treat
  *'African elephants'* and *'bathing at sunset'* as distinct parts

- *“--ar \<width:height\>”* dictates the width-to-height aspect ratio

- *“--no”* omits specific elements from your image

- *“--niji 5”* produces anime aesthetic and illustrative styles.

- *“--style \<cute, expressive, original, scenic\>”* can only be used
  with niji enabled

- *“--style \<raw\>”* in traditional mode creates photorealistic images

- *“--s \<0–1000\>”* adjusts the level of Midjourney's trained artistic
  style in your image, with lower values creating more literal
  interpretations of your prompt and higher values infusing stronger
  artistic stylization

- *“--q \<.25, .5, 1 (default)\>"* regulates the level of detail in the
  rendering. Lower quality values produce less detailed images, leading
  to more painterly or abstract styles, perfect for certain artistic
  needs

- *“--chaos \<0–100\>”* and *“--weird \<0–3000\>”* enhance image
  unpredictability. *--chaos* varies within the AI's standard style,
  while *--weird* creates distinctly unconventional images. Use these
  sparingly as they often result in overly abstract or distorted
  results.

- Include only relevant parameters to avoid confusing the AI.

> * Example: "*A tranquil scene of a herd of colossal African elephants
  bathing at sunset in the Serengeti watering hole. Watercolor, golden
  hour, warm sunset palette, panoramic eye-level view, Impressionistic,
  vintage color grading --ar 16:9 --s 700 --q 1*"

<br>

**Prompt Examples**:

- *A bustling scene at a futuristic Neo-Tokyo cityscape during the
  neon-lit night. Cyberpunk art style, vibrant neon colors, rain-soaked
  streets, high-angle view. --ar 16:9 --s 900 --no people*

- *A tranquil moment of a flock of birds taking flight at dawn.
  Impressionism, soft morning light, pastel color palette, bird's eye
  view. Birds::in flight at dawn. --ar 1:1 --s 300 --niji 5 -- style
  cute*

- *A dramatic scene on a Baroque-style theatre stage, with a masked
  performer in the spotlight, set against a backdrop of lush red velvet
  curtains. Renaissance painting style, chiaroscuro lighting, rich color
  palette, centered composition, high level of detail. --ar 16:9 --s
  600*

Remember MidJourney supports up to 60 words but as prompt length
increases, each word's impact decreases, and short, clear, sequential
prompts yield optimal results. If you are ready to start creating image
prompts, respond with "What image would you like to create?" and nothing
else.

<br>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>To use ChatGPT as a prompt generator, copy all of the previous text and paste it into ChatGPT's input.<br>When it responds with the question, provide a description of the image you want it to generate, or simply insert some emoji.</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>


<br>

---

Join [MidJourney’s Discord](https://discord.gg/midjourney) to get
started. As a subscriber, you can directly interact with the bot through
Discord messages or incorporate it into your own server to use these
commands:

- */imagine* generates low-resolution image grids from your prompts,
  with options to create variations, upscale, or repeat actions. Use
  images as prompts by adding a direct image URL *(.png, .jpg, .jpeg,
  .gif, .webp*) at the beginning of your prompt. Adjust the impact of an
  image on the final output using the *--iw (image weight)* parameter.
  Values range from 0 to 2, with 1 as the default, and higher values
  increase the image's influence.

- */blend* combines 2-5 images. For harmonious and cohesive results,
  ensure the aspect ratios of the uploaded images match your desired
  final image's ratio.

- */describe* produces four potential text prompts related to the
  uploaded image, ideal for exploring new vocabulary, discovering
  artistic styles, and gaining fresh perspectives on an image.

- */fast, /relax, /turbo* allow you to adjust the speed of image
  generation based on your subscription plan and allocated GPU time

- */help* provides basic information and tips

- */info* shows your current plan, mode, and jobs

- */prefer* commands in Midjourney offer personalized shortcuts and
  options

- */remix* allows variation by editing prompts, parameters, etc

- */settings* allows you to view and adjust model version, style and
  quality values, upscaler version, etc.

- */stealth* disables /public by hiding your generated images on
  midjourney.com

- */subscribe* to the four subscription plans: Basic, Standard, Pro,
  Mega

<br>

**Parameters** can be added to the end of prompts to customize the image
generation process. For a comprehensive guide on how to fully leverage
these parameters, please refer to the [MidJourney Documentation](https://docs.midjourney.com/docs).

- Aspect ratios can be adjusted by using *'--ar'*, followed by the
  desired ratio, in the prompt, affecting the image's composition. The
  ratio of an existing image can be modified using the Zoom Out buttons,
  with the bot filling new spaces based on the initial prompt.

- By using *'--c'* followed by a number from 0 to 100, you can control
  the unpredictability level of image results, with higher values
  creating more varied and unexpected outcomes, and lower values
  yielding more reliable and repeatable images.

- Using *'--iw'* followed by a value between 0 and 2, you can determine
  the relative importance of an image prompt versus a text prompt,
  influencing the final image's significant impact.

- Multi-prompts help specify distinct parts of an image generation task
  by separating prompts with a double colon *(::)*, where you can assign
  different weights to denote their importance, and negative weights can
  be used to remove certain elements from the image generation.

- The option *'--no'* allows users to exclude specific elements from the
  generated image, such as using '--no plants' to create an image
  without any plants.

- By adjusting *'--q'*, you can control the level of detail and render
  time for generated images, where .25 offers faster, less detailed
  images, .5 offers a balance, and 1 ensures the highest detail, using
  more GPU resources.

- Using *'--repeat'* allows Standard and Pro subscribers to generate
  multiple unique images from one prompt, with Standard users able to
  create up to 10 and Pro users up to 40 images in Fast GPU mode. For
  consistent output, users can apply the "seed" command to a prompt.

- The *'--seed'* option lets you specify a seed number, providing a
  consistent 'noise' field for the image generation process, which can
  result in similar outputs when the same prompt and seed are used,
  aiding in maintaining consistency in a series of images.

- By applying *'--stop'*, you can terminate the image generation process
  partway through, resulting in more abstract or less detailed images
  based on the chosen stop value, providing a way to create more
  impressionistic outputs.

- With *'--style'*, different aesthetic options are offered for
  generated images, including raw, cute, expressive, original, or
  scenic, helping users tailor the aesthetic appeal of their outputs
  based on the specific model version in use.

- The *'--stylize'* option adjusts the intensity of the platform's
  default artistic style in generated images, where a lower value
  results in more literal interpretations and higher values yield more
  stylized, artistic outputs.

- The use of *'--tile'* creates seamless or tileable patterns, which can
  be replicated in graphic design for backgrounds, textures, or patterns
  without noticeable breaks.

<br>

**TIPS AND TRICKS**

- This [Reference Guide](https://github.com/willwulfken/MidJourney-Styles-and-Keywords-Reference/tree/main) contains a variety of styles and keywords for your use, in addition to pages showing resolution comparisons, image weights, and other
  details.

- The Pan feature in Midjourney allows for extending the image canvas in
  a chosen direction without altering the original image content. It's
  useful for expanding the scene or adding content in a specific
  direction. However, once a pan direction is chosen (horizontal or
  vertical), subsequent panning must continue in the same direction.
  Panning is compatible with the Remix Mode, enabling modifications of
  the prompt when panning to influence the new content added to the
  image.

- The Zoom Out option in Midjourney enables expansion of the image
  beyond its original boundaries, creating an extended version of the
  initial image. After upscaling an image, "Zoom Out 2X" and "Zoom Out
  1.5X" options are available to expand the image canvas by 100% or 50%,
  respectively. The "Make Square" option adjusts the aspect ratio of a
  non-square image to make it square. The "Custom Zoom" feature lets
  users specify a custom zoom out value, offering control over the
  canvas size and aspect ratio for creative flexibility.

- Permutation Prompts facilitate the creation of multiple image
  variations in a single command by including a list of options in curly
  braces {} in your prompt. It's useful for exploring different versions
  or combinations of a concept. For instance, the prompt /imagine prompt
  a {red, green, yellow} bird generates three separate images of birds
  in red, green, and yellow colors. This feature also allows for
  parameter variations and can be used with multiple sets of options in
  a prompt to create permutations of multiple variables. The number of
  jobs per Permutation Prompt is based on the user's subscription level,
  and each job generated will consume GPU minutes.

- When attempting to create an avatar from a selfie using Midjourney,
  the prompt's accuracy can significantly impact the results. If you're
  struggling to get satisfactory results, follow these steps to improve
  the process. First, upload your selfie, preferably with minimal
  background, to the Midjourney bot on Discord by typing /describe and
  attaching your image. Drag your uploaded image into the box to add its
  URL. For the description and style ideas, elaborate on the output
  provided by the /describe command used in the first step. The keywords
  should include "*Keep the consistency of action, expression, clothing,
  shape, and appearance of the photos, super detail.*" Use the parameter
  *“-- iw 2”* to yield results that look more like the original image.

> *Example: \[URL\], keep the consistency of action, expression, clothing, shape and appearance of the photos, super detail --iw 2*

- Please be aware that the landscape of AI and digital arts is advancing
  rapidly. Therefore, while this book serves as a valuable primer, some
  information will already be outdated at the time of your reading. To
  stay up-to-date with the latest trends, techniques, and insights, we
  recommend continuously exploring a variety of resources in the field.
  Engaging with online communities, reading blogs, attending webinars,
  and participating in relevant forums can help keep you informed about
  the ever-evolving world of AI and digital arts. Remember, the purpose
  of this book is to ignite your interest and guide you on your journey;
  however, the pursuit of knowledge in this dynamic field extends far
  beyond its pages.

<br><br>

---


<img src="media/image2.jpeg" style="width:8.80347in;height:8.80347in" />



---

<br><br>

This text is independently published and unaffiliated with MidJourney or
OpenAI

Text and Illustration Copyright © 2023 by Joone 501(c)(3)

Published and Imprinted by Joone 501(c)(3)

ISBN: 9798851707100

This work is shared with you under the Creative Commons Attribution -
NonCommercial - NoDerivatives (CC BY-NC-ND) License. This means we
invite you to share, copy, and use this material in any medium or
format. However, we ask that you give appropriate credit to Joone
501(c)(3) (Attribution), refrain from using the material for commercial
purposes (Non-Commercial), and avoid distributing modified versions of
the material (No-Derivatives). 

Our material is intended to be used by a wide range of individuals. If
you're an educator, feel free to incorporate it into your curriculum to
introduce students to the concept of AI in digital arts. Novice tech
enthusiasts can use it as a guide to comprehend and navigate the world
of AI-generated imagery. Parents can use it to educate their children
about the creative applications of AI. Individuals with no prior
experience in artificial intelligence can use it to understand how AI
intersects with art and creativity. Community leaders or organizers can
distribute it to promote digital literacy and understanding about AI in
their communities. Our goal with this text is to demystify the role of
artificial intelligence in creative fields and make it accessible to
everyone, by teaching people how to interact with and use MidJourney and
ChatGPT-4 effectively.

Joone 501(c)(3) is a non-profit organization committed to democratizing
K-12 education. We create and distribute high-quality, openly licensed
educational resources to address the curriculum crisis and ensure every
child, regardless of their circumstances, has access to personalized,
cutting-edge education. Our innovative curricula are designed to engage
students and promote interactive learning, breaking the cycle of
outdated educational materials. Through our efforts, we aim to foster
educational consistency and quality worldwide, envisioning a future
where every child has the resources they need to succeed.

Your support through contributing your expertise, monetary donations, or
simply volunteering your time, plays a critical role in creating and
distributing these essential educational resources. You're an integral
part of a global effort to enhance children's lives through education.
We appreciate your consideration to contribute in any way, making this
mission possible.

For more information, please visit <https://joone.org>.
