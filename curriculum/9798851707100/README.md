<div align="center">

![image](https://github.com/joone-org/curriculum.joone.org/blob/main/curriculum/9798851707100/Images/cover.jpg)

This guide introduces MidJourney and doubles as a ChatGPT prompt. As experience is the teacher of all things, we invite you to scroll down and explore the example prompts and the images generated from their respective emoji inputs. Shared under an open license by [Joone](https://joone.org/), you're free to use and share it while giving appropriate credit.

[Amazon Kindle](https://kdp.amazon.com/amazon-dp-action/us/dualbookshelf.marketplacelink/B0CBRK83LC)<br>
[Amazon Paperback](https://www.amazon.com/dp/B0C9SC73JC?ref_=pe_3052080_397514860)<br>
[Microsoft Word](https://github.com/joone-org/curriculum.joone.org/blob/main/curriculum/9798851707100/MidJourney.docx)<br>
[Markdown](https://github.com/joone-org/curriculum.joone.org/blob/main/curriculum/9798851707100/README.md)<br>
[PDF](https://github.com/joone-org/curriculum.joone.org/blob/main/curriculum/9798851707100/MidJourney.pdf)<br>

</div>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>
<br><p>To use ChatGPT as a prompt generator, copy all of the following text and paste it into ChatGPT's input.<br>When it responds with the question, provide a description of the image you want it to generate, or simply insert some emoji.</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<br>

[**Midjourney**](https://www.midjourney.com/) is a [generative AI](https://en.wikipedia.org/wiki/Generative_artificial_intelligence) bot on [Discord](https://discord.com/) that generates images from natural language "prompts".

<br>
  
As prompt length increases, each word's impact decreases, so remain concise while following this format: 
> "*/imagine [**subject**] in the style of [**style**], [**specifications**]*"

<br>

Though none of the following are mandatory, elements should be ordered as follows: 
> [**Subject**]:  *Quantity of → Subject → Characteristics → Action → Setting → "in the style of" →*

> [**Style**]:  *Genre → Medium → Techniques → Influences → Hues → Lighting → Heritage → Technology → Mood → Theme →*

> [**Specifications**]:  *Hashtags, Negative Spaces, Series, Purpose, Jargon, Subthemes, etc. → Resolution → --Parameters*

<br>

#### Subject and Setting
Start with a subject positioned within a specific environment, use collective nouns if needed ("herd" instead of "3"), and be specific ('sunset' differs from 'dusk'). 
> *Example: "/imagine Elephant herd at sunset in the Serengeti"*

<br>

#### Style Keywords
For the most expressive imagery infuse your prompts with personality and emotion. MidJourney's capabilities span infinite artistic possibilities, from 'pointillism' to 'brutalist architecture', 'vaporwave aesthetic' to 'Chiaroscuro', and even specific concepts like 'double exposure', 'neon lights', and 'steampunk elements': 
  - Define the medium (photo, sand sculpture, linocut print).
  - Describe your desired lighting (soft ambient, neon, candle-lit)
  - Pair it with a color scheme (monochromatic, earth tones, cyberpunk neon)
  - Arrange your scene using terms like (low-angle shot, bird's eye view, rule of thirds composition)
  - Mention the desired artistic style (Cubism, Anime, Film Noir, Banksy graffiti), or specify the historical period or specific environment for added context
  - Include additional descriptors (shallow depth of field, vignette, splatter effect) to refine your scene
  - For high realism, specify camera effects, settings, setup (Canon EOS 5D Mark IV, 24-70mm lens, f/2.8)
  - Leverage nuanced adjectives (tranquil, breathtaking, etc.) to add mood
> *Example: "/imagine Elephant herd at sunset in the Serengeti, in the style of Impressionist art, grandiose landscapes, under a sky richly colored in hues of orange and gold."*

<br>

#### Parameters
- "*::*" allows for distinction of image components and their weighting. In the example *"/imagine A herd of colossal African elephants::2 under a breathtaking sunset in the Serengeti::1"*, *'elephants'* are twice as emphasized as the *'sunset'*. Using --no will exclude defined elements
- "*--s*" (values can range from 0 through 1000) adjusts Midjourney's artistic style, with lower values for more literal imagery and higher for stronger stylization
- "*--niji 5*" produces anime aesthetic, and illustrative styles can be added with "*--niji 5 --style (cute, expressive, original, scenic)*"
- “*--style raw*" in traditional mode creates photorealistic images
- “*--ar width:height" dictates the width-to-height aspect ratio
- “*--q*" (options are: .25, .5, and the default of 1) regulates the level of detail in the rendering with lower values producing less detailed, painterly, abstract images
- "*--chaos*" (0 – 100) and "*--weird*" (0 – 3000) create unpredictabile, abstract, distorted results. "*--chaos*" varies within Midjourney's standard style, while "*--weird*" creates distinctly unconventional images. 
> *Example: "/imagine A herd of colossal African elephants::2 under a breathtaking sunset::1 in the Serengeti. Pointillist style, golden hour lighting, earth tone color scheme, low-angle shot composition. --s 700 --ar 16:9 --no people"*

#### Prompt Examples
- 

Remember MidJourney supports up to 60 words but as prompt length increases, each word's impact decreases, and short, clear, sequential prompts yield optimal results. If you are ready to start creating image prompts, respond with "What image would you like to create?" and nothing else.

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

![ele1](https://github.com/joone-org/curriculum.joone.org/assets/137654670/c34ebea0-ffc9-4d67-a61c-117afaeaadec)
> *A tranquil scene of a herd of colossal African elephants bathing at sunset in the Serengeti watering hole. Watercolor, golden hour, warm sunset palette, panoramic eye-level view, Impressionistic, vintage color grading --ar 16:9 --s 700*

<br>

---

<br>Join [MidJourney’s Discord](https://discord.gg/midjourney) to get started. As a subscriber, you can directly interact with the bot through Discord messages or incorporate it into your own server to use these commands:

- */imagine* generates low-resolution image grids from your prompts, with options to create variations, upscale, or repeat actions. Use images as prompts by adding a direct image URL *(.png, .jpg, .jpeg, .gif, .webp*) at the beginning of your prompt. Adjust the impact of an image on the final output using the *--iw (image weight)* parameter. Values range from 0 to 2, with 1 as the default, and higher values increase the image's influence.

- */blend* combines 2-5 images. For harmonious and cohesive results, ensure the aspect ratios of the uploaded images match your desired final image's ratio.

- */describe* produces four potential text prompts related to the uploaded image, ideal for exploring new vocabulary, discovering artistic styles, and gaining fresh perspectives on an image.

- */fast, /relax, /turbo* allow you to adjust the speed of image generation based on your subscription plan and allocated GPU time

- */help* provides basic information and tips

- */info* shows your current plan, mode, and jobs

- */prefer* commands in Midjourney offer personalized shortcuts and options

- */remix* allows variation by editing prompts, parameters, etc

- */settings* allows you to view and adjust model version, style and quality values, upscaler version, etc.

- */stealth* disables /public by hiding your generated images on midjourney.com

- */subscribe* to the four subscription plans: Basic, Standard, Pro, Mega

<br>

**Parameters** can be added to the end of prompts to customize the image generation process. For a comprehensive guide on how to fully leverage these parameters, please refer to the [MidJourney Documentation](https://docs.midjourney.com/docs).

- Aspect ratios can be adjusted by using *'--ar'*, followed by the desired ratio, in the prompt, affecting the image's composition. The ratio of an existing image can be modified using the Zoom Out buttons, with the bot filling new spaces based on the initial prompt.

- By using *'--c'* followed by a number from 0 to 100, you can control the unpredictability level of image results, with higher values creating more varied and unexpected outcomes, and lower values yielding more reliable and repeatable images.

- Using *'--iw'* followed by a value between 0 and 2, you can determine the relative importance of an image prompt versus a text prompt, influencing the final image's significant impact.

- Multi-prompts help specify distinct parts of an image generation task by separating prompts with a double colon *(::)*, where you can assign different weights to denote their importance, and negative weights can be used to remove certain elements from the image generation.

- The option *'--no'* allows users to exclude specific elements from the generated image, such as using '--no plants' to create an image without any plants.

- By adjusting *'--q'*, you can control the level of detail and render time for generated images, where .25 offers faster, less detailed images, .5 offers a balance, and 1 ensures the highest detail, using more GPU resources.

- Using *'--repeat'* allows Standard and Pro subscribers to generate multiple unique images from one prompt, with Standard users able to create up to 10 and Pro users up to 40 images in Fast GPU mode. For consistent output, users can apply the "seed" command to a prompt.

- The *'--seed'* option lets you specify a seed number, providing a consistent 'noise' field for the image generation process, which can result in similar outputs when the same prompt and seed are used, aiding in maintaining consistency in a series of images.

- By applying *'--stop'*, you can terminate the image generation process partway through, resulting in more abstract or less detailed images based on the chosen stop value, providing a way to create more impressionistic outputs.

- With *'--style'*, different aesthetic options are offered for generated images, including raw, cute, expressive, original, or scenic, helping users tailor the aesthetic appeal of their outputs based on the specific model version in use.

- The *'--stylize'* option adjusts the intensity of the platform's default artistic style in generated images, where a lower value results in more literal interpretations and higher values yield more stylized, artistic outputs.

- The use of *'--tile'* creates seamless or tileable patterns, which can be replicated in graphic design for backgrounds, textures, or patterns without noticeable breaks.

<br>

**TIPS AND TRICKS**

- [Midlibrary](https://www.midlibrary.io/) and this [Reference Guide](https://github.com/willwulfken/MidJourney-Styles-and-Keywords-Reference/tree/main) contain a variety of styles and keywords for your use, in addition to pages showing resolution comparisons, image weights, and other details.

- The Pan feature in Midjourney allows for extending the image canvas in a chosen direction without altering the original image content. It's useful for expanding the scene or adding content in a specific direction. However, once a pan direction is chosen (horizontal or
  vertical), subsequent panning must continue in the same direction. Panning is compatible with the Remix Mode, enabling modifications of the prompt when panning to influence the new content added to the image.

- The Zoom Out option in Midjourney enables expansion of the image beyond its original boundaries, creating an extended version of the initial image. After upscaling an image, "Zoom Out 2X" and "Zoom Out 1.5X" options are available to expand the image canvas by 100% or 50%, respectively. The "Make Square" option adjusts the aspect ratio of a non-square image to make it square. The "Custom Zoom" feature lets users specify a custom zoom out value, offering control over the canvas size and aspect ratio for creative flexibility.

- Permutation Prompts facilitate the creation of multiple image variations in a single command by including a list of options in curly braces {} in your prompt. It's useful for exploring different versions or combinations of a concept. For instance, the prompt /imagine prompt a {red, green, yellow} bird generates three separate images of birds in red, green, and yellow colors. This feature also allows for parameter variations and can be used with multiple sets of options in a prompt to create permutations of multiple variables. The number of jobs per Permutation Prompt is based on the user's subscription level, and each job generated will consume GPU minutes.

- When attempting to create an avatar from a selfie using Midjourney, the prompt's accuracy can significantly impact the results. If you're struggling to get satisfactory results, follow these steps to improve the process. First, upload your selfie, preferably with minimal background, to the Midjourney bot on Discord by typing /describe and attaching your image. Drag your uploaded image into the box to add its URL. For the description and style ideas, elaborate on the output provided by the /describe command used in the first step. The keywords should include "*Keep the consistency of action, expression, clothing, shape, and appearance of the photos, super detail.*" Use the parameter *“-- iw 2”* to yield results that look more like the original image.

> *Example: \[URL\], keep the consistency of action, expression, clothing, shape and appearance of the photos, super detail --iw 2*

<br>

---

This introductory guide to Midjourney is designed for newcomers, and below we present a series of images generated from emoji prompts used with the ChatGPT generator this guide began with. Each emoji triggers a unique narrative, which Midjourney then converts into visual representation. Bear in mind that AI imaging is more art than science, and results might not align perfectly with initial intentions. To observe Midjourney's accuracy, compare these images with their original prompts. For further improvement in accuracy and prompt structure, consider referencing the article [here](https://artificialcorner.com/youre-using-midjourney-wrong-here-s-how-to-create-better-images-than-99-of-midjourney-users-c876fbe7915e), or the comprehensive source of prompt creation tips at [UX Collective](https://medium.com/design-bootcamp/search?q=midjourney).

![image](https://github.com/joone-org/curriculum.joone.org/blob/main/curriculum/9798851707100/Images/lion.jpg)
🦁 A majestic lion resting in the shade of a savanna tree, attentively watching the horizon under the scorching midday sun.<br>Realistic wildlife photography style, high contrast, warm color palette, eye-level view, shallow depth of field. 🦁

<!-- 

![image](URL)
prompt<br>
<br><br>


* 🐉 A towering, majestic dragon perched atop a craggy mountain peak, its scales shimmering under the moonlight. Traditional Asian ink painting style, nighttime setting, monochromatic color scheme, bird's-eye view, strong contrast. --ar 1:1 --s 800 --q .5<br><br>
* 🏞️ A breathtaking view of a pristine alpine valley with a mirror-like lake surrounded by towering, snow-capped mountains under a clear blue sky. Bob Ross-inspired oil painting style, daytime setting, vibrant colors, panoramic view, detailed foliage. --ar 16:9 --s 600 --q .5<br><br>
* 🎭 A dramatic scene on a Baroque-style theatre stage, with a masked performer in the spotlight, set against a backdrop of lush red velvet curtains. Renaissance painting style, chiaroscuro lighting, rich color palette, centered composition, high level of detail. --ar 16:9 --s 600 --q .5<br><br>
* 🍄 A whimsical scene in an enchanted forest filled with oversized, luminescent mushrooms and tiny glowing fairy-like creatures. Studio Ghibli anime style, dusk setting, vibrant and surreal colors, low-angle shot, soft ambient light. --ar 16:9 --s 700 --q .5<br><br>
* 🌌 A mesmerizing scene of the Milky Way stretching across the night sky, illuminating a tranquil, lonely mountain. Van Gogh's Starry Night-inspired style, dark sky, vibrant and contrasting colors, low-angle view, strong brush strokes. --ar 16:9 --s 800 --q .5<br><br>
* 🐠 A vibrant underwater world bustling with life, featuring a colorful clownfish navigating through the vivid corals of a bustling reef. Anime style, deep-sea lighting, saturated color palette, medium shot, detailed marine life. --ar 16:9 --s 700 --q .5<br><br>
* 🌺 A single, radiant hibiscus flower, dew-kissed and basking in the morning sunlight against a lush tropical background. Botanical illustration style, morning lighting, vibrant color palette, close-up shot, highly detailed. --ar 1:1 --s 800 --q .5<br><br>
* 🗻 A serene scene of Mount Fuji in winter, its snow-capped peak bathed in the soft glow of a rising sun, with cherry blossom trees framing the foreground. Ukiyo-e style, dawn lighting, muted color palette, medium shot, subtle grain effect. --ar 16:9 --s 600 --q .5<br><br>
* 🌠 A breathtaking view of a shooting star streaking across the night sky over a tranquil, mirror-like lake surrounded by pine forests. Impressionism style, night setting, cool color palette, panoramic view, star trail effect. --ar 16:9 --s 700 --q .5<br><br>
* 🏯 A grand, historic Japanese castle nestled amidst vibrant cherry blossom trees, with Mount Fuji majestically visible in the background. Ukiyo-e woodblock print style, spring setting, vibrant color palette, eye-level view, high detail. --ar 16:9 --s 700 --q .5<br><br>
* 🌍 A captivating view of Earth from space, with a radiant sunrise illuminating the continents against the deep blue oceans. Space photography style, sunrise lighting, vibrant colors, high-angle view, realistic detail. --ar 16:9 --s 800 --q .5<br><br>
* 🌕 A detailed view of the full moon against a starry night sky, its craters and features vividly visible. Realistic astrophotography style, night setting, monochromatic color palette, centered composition, high contrast. --ar 1:1 --s 800 --q .5<br><br>
* 🌈 A pastoral scene after a rain shower, with a vibrant rainbow arching across the sky over a verdant meadow dotted with wildflowers. Watercolor style, soft ambient light, full color spectrum, panoramic view, impressionistic brushstrokes. --ar 16:9 --s 600 --q .5<br><br>
* ⚡ A dramatic scene of a powerful lightning bolt splitting the night sky over a lonely lighthouse by the stormy sea. Romanticism style, night setting, dynamic lighting, cool color palette, high contrast. --ar 16:9 --s 700 --q .5<br><br>
* 🎠 An enchanting scene of a vintage carousel aglow with fairy lights in a bustling night-time city park. Art Nouveau style, night setting, vibrant colors, medium shot, bokeh effect. --ar 16:9 --s 700 --q .5<br><br>
* 🎡 A bustling fairground at dusk, with a towering Ferris wheel brightly lit against the twilight sky. Vintage photography style, soft ambient light, warm color palette, low-angle view, film grain effect. --ar 16:9 --s 600 --q .5<br><br>
* 🏜️ A vast, tranquil desert landscape under a blazing sunset, with towering sand dunes casting long, dramatic shadows. Minimalist oil painting style, sunset lighting, warm color palette, wide-angle view, smooth texture. --ar 16:9 --s 700 --q .5<br><br>
* 🐋 A giant, serene blue whale gliding gracefully through the deep ocean, surrounded by a myriad of bioluminescent marine life. Anime style, deep-sea lighting, cool color palette, medium shot, exaggerated proportions. --ar 16:9 --s 700 --q .5<br><br>
* 🏕️ A cozy campsite nestled among towering pines, a crackling fire casting a warm glow against the starlit wilderness. Digital painting style, night setting, warm and cool color palette, medium shot, detailed environment. --ar 16:9 --s 600 --q .5<br><br>

-->

---

This text is independently published and unaffiliated with MidJourney or OpenAI

Text and Illustration Copyright © 2023 by Joone 501(c)(3)

Published and Imprinted by Joone 501(c)(3)

ISBN: 9798851707100

This work is shared with you under the Creative Commons Attribution -NonCommercial - NoDerivatives (CC BY-NC-ND) License. This means we invite you to share, copy, and use this material in any medium or format. However, we ask that you give appropriate credit to Joone
501(c)(3) (Attribution), refrain from using the material for commercial purposes (Non-Commercial), and avoid distributing modified versions of the material (No-Derivatives). 

Our material is intended to be used by a wide range of individuals. If you're an educator, feel free to incorporate it into your curriculum to introduce students to the concept of AI in digital arts. Novice tech enthusiasts can use it as a guide to comprehend and navigate the world of AI-generated imagery. Parents can use it to educate their children about the creative applications of AI. Individuals with no prior experience in artificial intelligence can use it to understand how AI intersects with art and creativity. Community leaders or organizers can distribute it to promote digital literacy and understanding about AI in their communities. Our goal with this text is to demystify the role of artificial intelligence in creative fields and make it accessible to everyone, by teaching people how to interact with and use MidJourney and ChatGPT-4 effectively.

Joone 501(c)(3) is a non-profit organization committed to democratizing K-12 education. We create and distribute high-quality, openly licensed educational resources to address the curriculum crisis and ensure every child, regardless of their circumstances, has access to personalized, cutting-edge education. Our innovative curricula are designed to engage students and promote interactive learning, breaking the cycle of outdated educational materials. Through our efforts, we aim to foster educational consistency and quality worldwide, envisioning a future where every child has the resources they need to succeed.

Your support through contributing your expertise, monetary donations, or simply volunteering your time, plays a critical role in creating and distributing these essential educational resources. You're an integral part of a global effort to enhance children's lives through education. We appreciate your consideration to contribute in any way, making this mission possible.

For more information, please visit <https://joone.org>.
