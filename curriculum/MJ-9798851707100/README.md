<div align="center">

![cover](https://github.com/joone-org/curriculum.joone.org/assets/137654670/ed652ec8-dde4-41cd-b528-148c19c783eb)

This guide introduces MidJourney and doubles as a ChatGPT prompt. As experience is the teacher of all things, we invite you to scroll down and explore the example prompts and the images generated. Shared under an open license by [Joone](https://joone.org), you're free to use and distribute.

[Amazon Kindle](https://kdp.amazon.com/amazon-dp-action/us/dualbookshelf.marketplacelink/B0CBRK83LC)<br>
[Amazon Paperback](https://www.amazon.com/dp/B0C9SC73JC?ref_=pe_3052080_397514860)<br>
[Microsoft Word](https://github.com/joone-org/curriculum.joone.org/blob/main/curriculum/MJ-9798851707100/Text/MidJourney.docx)<br>
[Markdown](https://github.com/joone-org/curriculum.joone.org/blob/main/curriculum/MJ-9798851707100/README.md)<br>
[PDF](https://github.com/joone-org/curriculum.joone.org/blob/main/curriculum/MJ-9798851707100/Text/MidJourney.pdf)<br>

</div>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>
<br><p>To use ChatGPT as a prompt generator, continue the conversation from <a href="https://chat.openai.com/share/112d7feb-fe02-4d47-b1e2-174a1aa2690a">this link</a>, or copy all of the following text and paste it into ChatGPT's input. When it responds with the question, provide emoji or a description of the image you want it to generate.</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<br>

[**Midjourney**](https://www.midjourney.com/) is a [generative AI](https://en.wikipedia.org/wiki/Generative_artificial_intelligence) bot on [Discord](https://discord.com/) that generates images from natural language "prompts".

<br>
  
As prompt length increases, each word's impact decreases, so remain concise while following this format: 
> */imagine [**subject**] in the style of [**style**], [**specifications**], [**--Parameters**]*

<br>

Though none of the following are mandatory, elements should be ordered as follows: 
> [**Subject**]:  *Quantity of > Subject > Characteristics > Action > Setting*

> [**Style**]:  *"in the style of" > Influences/Genre > Techniques > Color > Lighting > Medium > Tone*

> [**Specifications**]:  *Tags > Visual Elements > Series > Purpose > Equipment > Quality*

> [**--Parameters**]

<br>

#### [Subject]
Begin by describing the main focus of your image. Include specifics ('*flying*' differs from '*soaring*') about any actions or settings associated with your subject, and use collective nouns if needed ("*flock*" instead of "*3*").
> *The order of this section should follow:  Quantity of > Subject > Characteristics > Action > Setting*
 
> Example: _**a flock of macaws flying over a rainforest**_

<br>

#### [Style]
Next, describe any specific artistic styles or influences you want the image to reflect.  To create expressive imagery, infuse your prompts with personality and emotion, leveraging infinite artistic possibilities.  These should only be added when necessary, and are individually optional:
* Note **influential artists or periods**:
  * *Monet, Frida Kahlo, Banksy, Yayoi Kusama, Hokusai, Art Nouveau, Byzantine, Harlem Renaissance, Postmodernism, etc.*
* Define **genre**:
  * *Impressionist, Surrealism, Anime, Cubism, Vaporwave, Gothic, Photorealism, Abstract, Steampunk, Futurism, etc.*
* Include **techniques**:
  * *Bird's eye view, Chiaroscuro, Pointillism, Double Exposure, Rule of Thirds, Forced Perspective, Long Exposure, Vignette, etc.*
* Describe **color**:
  * *Hues of green and blue, Monochromatic, Earth tones, Vibrant neon, Primary colors, Warm or Cool, Black and White, Sepia, etc.*
* Indicate **lighting**:
  * *Morning, Golden Hour, Nighttime, Candle-lit, Backlit, Silhouette, Neon lights, Harsh shadows, Soft diffused, Underwater, etc.*
* Specify **medium**:
  * *Watercolor, Oil Paint, Digital, Pencil, Photography, Mosaic, Graffiti, CGI, Glassblowing, Etching, Sculpture, etc.*
* Set the **tone** (Mood/Theme):
  * *Tranquility, Joy, Melancholy, Mystery, Adventure, Discovery, Conflict, Transformation, Journey, Nature, Urban, Dreams, etc.*

> *The order of this section should follow:  "in the style of" > Influences/Genre > Techniques > Color > Lighting > Medium > Tone*

> Example: _**in the style of Impressionism**_

<br>

#### [Specifications]
These should only be added when necessary, and are individually optional:
* Include **Tags**:
  * Use specific keywords, jargon, or hashtags to refine the vision: *#wildlife, #fantasy, #noir, #steampunk, #scifi, #retro, etc.*
* Define **Visual Elements**:
  * Detail visual characteristics to enhance the precision and relevance: *depth of field, negative space, symmetry, etc.*
* Mention **Series**:
  * Indicate if the image belongs to a collection like: '*bird series*', '*seasons collection*', '*abstract emotions project*', *etc*.
* State **Purpose**:
  * Specify the image's intent, such as: '*beauty of nature*', '*demonstrating innovation*', '*provoking a sense of nostalgia*', *etc*.
* Chose **Equipment**:
  * Specify equipment or software to emulate: '*Illustrator*', '*Nikon D850*', '*Hasselblad X1D II*', '*Drone camera*', '*Macro lens*', *etc*.
* Determine **Quality**:
  * Designate the desired resolution to influence the level of detail and clarity: *QVGA, HD, 2K, UHD, 16K, IMAX, Cinemascope, etc*.

> *The order of this section should follow:  Tags > Visual Elements > Series > Purpose > Equipment > Quality*

> Example: _**#wildlife**_

#### [--Parameters]
  * "**::**" allows for the distinction of image components and their weighting. For instance, in the prompt *"/imagine a flock of macaws::2, bright feathers::1 flying over the rainforest"*, *'macaws'* are twice as emphasized as the *'bright feathers'*. The "**--no**" parameter can be used to exclude defined elements.
  * "**--stylize**" (values can range from 0 through 1000) adjusts Midjourney's artistic style, with lower values for more literal imagery and higher for stronger stylization
  * "**--niji 5**" produces anime aesthetics, with additional styles available using "**--niji 5 --style (cute, expressive, original, scenic)**"
  * “**--style raw**" in traditional mode creates photorealistic images
  * “**--aspect width:height**" dictates the width-to-height aspect ratio
  * “**--quality**" (options are: .25, .5, 1) regulates the level of detail in the rendering with lower values producing less detailed, painterly, abstract images
  * "**--chaos**" (0 – 100) creates unpredictable, abstract, distorted results within Midjourney's standard style
  * "**--weird**" (0 – 3000) creates distinctly unconventional images

> Example: _**--ar 2:1**_

> _**Parameters always come at the end of the prompt**_

> Completed Example:  **_/imagine a flock of macaws flying over a rainforest, in the style of Impressionism, #wildlife --aspect 2:1_**

<br>

#### [Examples]
> *Quantity of > Subject > Characteristics > Action > Setting > "in the style of" > Influences/Genre > Techniques > Color > Lighting > Medium > Tone > Tags > Visual Elements > Series > Purpose > Equipment > Quality > --Parameters*

* _/imagine an ancient city, in the style of Baroque, dramatic contrasts of light and shadow, detailed oil textures, glow of twilight, melancholy --stylize 1000_
* _imagine Uncle Sam in a tug of war with citizens, in the style of Banksy's street art, vivid colors under harsh streetlights, tone of conflict_
* _/imagine an alien face, in the style of Chiaroscuro, half-illuminated and half-enshrouded in shadow, monochromatic palette, Sony A7R V --style raw --aspect 1:2_
* _/imagine a rusty robot in a mechanic's workshop, in the style of Steampunk with rich metallic hues, stark contrasts, tone of transformation_
* _/imagine a dense forest of bioluminescent plants, in the style of surrealism, radiating a sense of wonder and mystery --chaos 50 --weird 1500_
* _/imagine a small fluffy kitten playing in a garden filled with vibrant flowers, in the style of anime, embodying a sense of joy and playfulness --niji 5 --style cute_
* _/imagine a sunken cityscape with walls adorned in vibrant graffiti, in the style of Photorealism infused with Graffiti art, soft and dappled sunlight filtering through the water_
* _/imagine an expansive valley dotted with wildflowers, in the style of bird's-eye view, capturing the grandeur of nature, drone photograph --aspect 16:9_
* _/imagine a group of dancers in a whirl of vibrant colors and fluid forms, in the style of Abstract Expressionism, energy and rhythm of dance --quality .25_
* _/imagine a lone tree standing against a stark and snowy landscape under the icy blue winter sky, in the style of Minimalism, UHD --stylize 50_

<!--

* _"/imagine the Aurora Borealis, colorful lights, dancing across a star-studded polar sky, in the style of Expressionism, fluid lines, cool hues, night sky, digital painting, ethereal spectacle, #aurora #northernlights, emphasis on light movements, Natural Phenomena series, beauty of the universe, Adobe Photoshop, IMAX --s 400 --ar 16:9"_
* _"/imagine Elton John, flamboyant glasses, playing a grand piano on a glittering stage, in the style of Glam Rock Art, fantastical elements, vibrant hues, spotlight, digital painting, extravagant showmanship, #EltonJohn #pop, emphasis on costume, modern music icons series, flamboyance and authenticity, Adobe Illustrator, IMAX --s 400 --ar 16:9"_
* _"/imagine a bustling marketplace in Marrakech, filled with vibrant fabrics and exotic spices, in the style of Fauvism, exaggerated colors, bold patterns, afternoon, oil painting, vibrant diversity, #market #Marrakech, focus on color contrasts, World Cultures series, richness and variety, Fauvist oil paints, 4K --s 300 --ar 2:1"_
* _"/imagine the fierce face of a warrior, adorned in traditional Maori tattoos, in the style of Tribal Art, bold lines, earthy colors, intense gaze, wood sculpture, pride and strength, #Maori #warrior, emphasis on patterns and symbolism, World Cultures series, courage and heritage, wood chisel and mallet, UHD --s 200 --ar 1:1"_
* _"/imagine a bedroom, cozy and personal, being swept by an ocean wave, with a larger wave arching over the entire scene, in the style of Surrealism, warped perspective, shades of blue and muted interior colors, eerie underwater lighting, digital painting, dreamlike inversion, #bedroom #ocean #surreal, emphasis on fluidity and displacement, dream spaces series, subconscious exploration, Adobe Photoshop, 4K --s 600 --ar 16:9"_
* _"/imagine a labyrinth, high stone walls, stretching out into infinity under a twilight sky, in the style of M.C. Escher, intricate patterns, twilight hues, mysterious shadows, pencil sketch, journey into the unknown, #labyrinth #infinity, emphasis on illusion and perspective, Architectural Wonders series, exploration and puzzle, graphite pencils, 4K --s 400 --ar 16:9"_
* _"/imagine Elizabeth Bennet and Mr. Darcy, period attire, engaged in a tense conversation in a Victorian drawing room, in the style of Romanticism, delicate detailing, muted palette, soft candlelight, oil painting, restrained passion, #PrideAndPrejudice #romance, focus on facial expressions and body language, classic literature series, complexity of relationships, traditional oil paints, 4K --s 300 --ar 4:3"_
* _"/imagine a large montage of a bustling city, diverse architecture, with colorful hot air balloons floating across the skyline, in the style of Cubism, fragmented perspective, vibrant colors, sunset, digital painting, celebration of urban life, #city #hotairballoons, juxtaposition of urban and whimsical, cityscape series, freedom and exploration, Adobe Illustrator, 8K --s 400 --ar 21:9"_
* _"/imagine the first moon landing, illustrated as a collage of newspaper clippings and photographs, in the style of Dadaism, eclectic mix, sepia tones, layered composition, mixed media collage, triumph of human spirit, #MoonLanding #history, emphasis on juxtaposition, Milestones in History series, exploration and discovery, scissors and glue, 4K --s 300 --ar 16:9"_
* _"/imagine a dense forest, trees reaching skyward, carved intricately from a single block of wood, in the style of Realism, attention to texture, natural wood tones, subtle lighting, wood sculpture, serenity in nature, #forest #sculpture, focus on detail and form, Art in Nature series, life's resilience, Hand chisel and mallet, QHD --s 200 --ar 1:2"_
* _"/imagine a samurai standing under a cherry blossom tree, in the style of Anime, bold lines, pastel hues, soft morning light, digital art, honour and tranquility, #samurai #cherryblossom, focus on the samurai's pose and cherry blossom's petals, Samurai Tales series, courage and tranquility, Adobe Animate, 4K --s 200 --ar 1:1 --niji 5 --style expressive"_
* _"/imagine a lighthouse, tall and solitary, as a red sun rises over a serene shore, in the style of Impressionism, loose brushwork, warm hues of red and orange, morning light, watercolor, hopeful dawn, #lighthouse #sunrise, emphasis on the play of light on water, maritime series, navigation and new beginnings, traditional watercolors, 4K --s 250 --ar 2:1"_
* _"/imagine a tranquil zen garden, raked sand, rocks and bonsai, reflecting in a still pond, in the style of Japanese Ink Wash Painting, simplicity, earth tones, soft light, ink wash, peace and harmony, #zengarden #Japan, emphasis on balance and minimalism, Tranquil Spaces series, mindfulness and calm, traditional ink, 4K --s 300 --niji 5 --style scenic --ar 4:3"_
* _"/imagine the complex structure of a neuron, intricate dendrites and axons, against a black background, in the style of Scientific Illustration, high level of detail, cool tones, stark contrast, charcoal drawing, mystery of the mind, #neuron #science, focus on texture and pattern, Science in Art series, intricacy and complexity of life, charcoal pencils, 4K --s 300 --ar 1:1"_

-->
<br>

Midjourney allows up to 60 words per prompt, but effectiveness diminishes with length. Be selective with styles, specifications, and parameters for better results. Aim for clarity and specificity in your prompts for optimal image generation. Can you guide me through creating an effective prompt with suitable examples?  If you are please reply with, "What image would you like to create?"

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

![png11](https://github.com/joone-org/curriculum.joone.org/assets/137515679/734bbd62-8e44-4758-aa00-f04fc8dc2ea1)

---

Join [MidJourney’s Discord](https://discord.gg/midjourney) to get started. As a subscriber, you can directly interact with the bot through Discord messages or incorporate it into your own server to use these commands:

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

![png23](https://github.com/joone-org/curriculum.joone.org/assets/137515679/4bd81a24-ba43-4543-a400-a2f92d2d6393)

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

![png28](https://github.com/joone-org/curriculum.joone.org/assets/137515679/d42c6732-4f3e-4c2b-a705-b8cd6bb6b154)

<br>

**TIPS AND TRICKS**

- [Midlibrary](https://www.midlibrary.io/) and this [Reference Guide](https://github.com/willwulfken/MidJourney-Styles-and-Keywords-Reference/tree/main) contain a variety of styles and keywords for your use, in addition to pages showing resolution comparisons, image weights, and other details.  We keep an extensive list of prompt examples for model training and review [here](https://github.com/joone-org/curriculum.joone.org/wiki/MidJourney-Prompt-Examples).

- The Pan feature in Midjourney allows for extending the image canvas in a chosen direction without altering the original image content. It's useful for expanding the scene or adding content in a specific direction. However, once a pan direction is chosen (horizontal or
  vertical), subsequent panning must continue in the same direction. Panning is compatible with the Remix Mode, enabling modifications of the prompt when panning to influence the new content added to the image.

- The Zoom Out option in Midjourney enables expansion of the image beyond its original boundaries, creating an extended version of the initial image. After upscaling an image, "Zoom Out 2X" and "Zoom Out 1.5X" options are available to expand the image canvas by 100% or 50%, respectively. The "Make Square" option adjusts the aspect ratio of a non-square image to make it square. The "Custom Zoom" feature lets users specify a custom zoom out value, offering control over the canvas size and aspect ratio for creative flexibility.

- Permutation Prompts facilitate the creation of multiple image variations in a single command by including a list of options in curly braces {} in your prompt. It's useful for exploring different versions or combinations of a concept. For instance, the prompt /imagine prompt a {red, green, yellow} bird generates three separate images of birds in red, green, and yellow colors. This feature also allows for parameter variations and can be used with multiple sets of options in a prompt to create permutations of multiple variables. The number of jobs per Permutation Prompt is based on the user's subscription level, and each job generated will consume GPU minutes.

- When attempting to create an avatar from a selfie using Midjourney, the prompt's accuracy can significantly impact the results. If you're struggling to get satisfactory results, follow these steps to improve the process. First, upload your selfie, preferably with minimal background, to the Midjourney bot on Discord by typing /describe and attaching your image. Drag your uploaded image into the box to add its URL. For the description and style ideas, elaborate on the output provided by the /describe command used in the first step. The keywords should include "*Keep the consistency of action, expression, clothing, shape, and appearance of the photos, super detail.*" Use the parameter *“-- iw 2”* to yield results that look more like the original image.

> *Example: \[URL\], keep the consistency of action, expression, clothing, shape and appearance of the photos, super detail --iw 2*

<br>

---

![waves](https://github.com/joone-org/curriculum.joone.org/assets/137654670/77ff2190-9d35-4bf3-b62b-e7da1d803734)
> "*/imagine waves spraying off the sandy shore, in the style of photorealistic accuracy, vibrant coloration, light turquoise and light white, saturated pigment pools, Mediterranean landscapes --ar 2:1 --no people*"

<br><br>

![traveler](https://github.com/joone-org/curriculum.joone.org/assets/137654670/1a076be4-5dcd-4920-8e60-a51a7ec9702a)
> "*/imagine a lone traveler, weathered cloak, standing at the crossroads in an endless desert, in the style of Romanticism, oil paint, chiaroscuro technique, influenced by Caspar David Friedrich, hues of warm sunset, twilight lighting, embodying a mood of introspection and hope --s 100 --ar 16:9*"

<br><br>

![hogwarts](https://github.com/joone-org/curriculum.joone.org/assets/137654670/cb1281bb-b230-4668-ac58-7405e3ef3a5a)
> "*/imagine Hogwarts Castle, towering, surrounded by the Black Lake, in the style of Romanticism, watercolor, hues of twilight blues and purples, under a starry sky, evoking a mood of magic and wonder --s 100 --ar 16:9*"

<br><br>

![bedroom](https://github.com/joone-org/curriculum.joone.org/assets/137654670/01001fb6-8aeb-4e02-a212-2aff2ac66b0b)
> "*/imagine a bedroom with ocean waves and an ocean wave over it, in the style of surrealistic dreamlike scenes, solarization effect, matte painting, forced perspective, I can't believe how beautiful this is, dreamlike whimsy, tonalist genius --ar 1:1*"

<br><br>

![throne](https://github.com/joone-org/curriculum.joone.org/assets/137654670/e5093799-387b-48a6-873c-85fbed5f8cee)
> "*/imagine The Iron Throne, menacing, under the shadowy light of torches, in the style of Gothic, digital art, influenced by H. R. Giger, hues of cold steel and dark shadows, evoking a mood of power and danger --s 200 --ar 1:1*"

![elizabeth](https://github.com/joone-org/curriculum.joone.org/assets/137654670/b0a39c62-2add-4084-8749-0ec04d18b6fd)
> "*/imagine Elizabeth Bennet and Mr. Darcy, standing in the rain, sharing a tender moment, in the style of Realism, watercolor, influenced by John Constable, hues of cool blues and greens, under an English sky, evoking a mood of love and tension --s 100 --niji 5 --style cute --ar 1:1*"

<br><br>

![daisy](https://github.com/joone-org/curriculum.joone.org/assets/137654670/0145efc6-77a7-4987-bdd6-ac655cf7fab3)
> "*/imagine Daisy Fay Buchanan, standing alone, looking across the bay at the green light, in the style of Art Deco, digital, influenced by Tamara de Lempicka, hues of dark blues and vibrant green, at night, evoking a mood of longing and opulence --ar 1:1*"

<br><br>

![balloons](https://github.com/joone-org/curriculum.joone.org/assets/137654670/8126bbf4-7657-4700-8557-5597c15b3b01)
> "*/imagine a large montage of a city with hot air balloons flying, in the style of vray tracing, Mexican folk art influence, photorealistic details, light red and cyan, rococo - inspired art, rendered in Cinema4D, detailed crowd scenes --ar 16:9*"

<br><br>

![inception](https://github.com/joone-org/curriculum.joone.org/assets/137654670/9d0a0102-7c43-4a88-89e5-2b0fa388f2d3)
> "*/imagine a city folding onto itself, surreal and disorienting, under a gloomy sky, in the style of Surrealism, digital medium, influenced by Escher, monochromatic hues, under diffused light, evoking a mood of mystery and confusion --s 800 --weird 1500 --ar 1:1*"

<br><br>

![bubble](https://github.com/joone-org/curriculum.joone.org/assets/137654670/43e32c8a-3f62-462b-a727-e79e02575b14)
> "*/imagine a painting with a big blue bubble hanging over water, in the style of classical balance, modernist landscapes, hard edge painter, Terragen, jarring juxtapositions, high detail, punctured canvases --ar 2:1 --no people*"

<br><br>

![tower](https://github.com/joone-org/curriculum.joone.org/assets/137654670/55003ef7-8baa-4c9e-800c-592d2103c1d0)
> "*/imagine The Dark Tower, looming and mysterious, surrounded by a field of roses, under a dusky, ominous sky, in the style of Gothic, digital medium, influenced by H. R. Giger, hues of monochromatic blacks, grays, and reds, with harsh shadowy lighting, evoking a mood of foreboding and adventure --s 200 --ar 16:9*"

<br><br>

![red](https://github.com/joone-org/curriculum.joone.org/assets/137654670/93ed2ff3-a1c2-4f69-8c03-c6c9b380c408)
> "*/imagine there is a white building above the dune, in the style of color field minimalism, light indigo and red, surreal portraiture, depiction of rural life, Zeiss Batis 18mm f/ 2. 8, German Expressionism, Italian landscapes --ar 2:1*"

<br><br>

![books](https://github.com/joone-org/curriculum.joone.org/assets/137654670/c256f85c-852f-42f1-9a56-6c600a4cba15)
> "*/imagine a pile of books with colorful titles, in the style of moody tonalism, heavily textured, vivid and saturated colors, aerial view, old timey, monumental scale, iconic --ar 1:1*"

<br><br>

![lighthouse](https://github.com/joone-org/curriculum.joone.org/assets/137654670/43d5908e-e21f-4886-a2ba-1527fc23d7e4)
> "*/imagine the red sun rises over a lighthouse on the shore, in the style of psychedelic artwork, cyan, 2D game art, hyper - detailed illustrations, bold palette, trillwave, moody color schemes --niji 5 --ar 1:1*"

<br><br>

![shipwreck](https://github.com/joone-org/curriculum.joone.org/assets/137654670/2d10f90e-5c5a-4d9d-8ce4-40ffc2c46ab5)
> "*/imagine a picture of an old wrecked ship in the desert, in the style of photorealist painter, Martin Ansin, realistic impressionism, Konica Auto S3, Peter Mitchev, multilayered realism, UE5 --ar 1:1*"

<br><br>

![hobbiton](https://github.com/joone-org/curriculum.joone.org/assets/137654670/92d0eb65-3858-4a2d-a98e-0efee4427c4c)
> "*/imagine a small cartoon fantasy house on a green meadow, in the style of graffiti - inspired illustrations, inventive character designs, rusticcore, rounded, comic/ cartoon, wandering eye, detailed character illustrations --ar 1:1*"

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

<!-- 

![image](URL)
prompt<br>
<br><br>

![image](https://github.com/joone-org/curriculum.joone.org/blob/main/curriculum/9798851707100/Images/lion.jpg)
🦁 A majestic lion resting in the shade of a savanna tree, attentively watching the horizon under the scorching midday sun.<br>Realistic wildlife photography style, high contrast, warm color palette, eye-level view, shallow depth of field. 🦁

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

![png41](https://github.com/joone-org/curriculum.joone.org/assets/137515679/9b338229-7008-4c6a-bc29-5501e6ebaa6b)
![png40](https://github.com/joone-org/curriculum.joone.org/assets/137515679/92ee7cbf-8e88-417c-b030-0bdacde54faa)
![png39](https://github.com/joone-org/curriculum.joone.org/assets/137515679/be6320d0-1100-4910-8718-ba55dc895769)
![png38](https://github.com/joone-org/curriculum.joone.org/assets/137515679/c14aa4d5-0baf-40bd-a6cb-4c83e0417d12)
![png37](https://github.com/joone-org/curriculum.joone.org/assets/137515679/04cfdaa8-e248-48ee-a26c-6bb109c3aeba)
![png36](https://github.com/joone-org/curriculum.joone.org/assets/137515679/e28a5d68-b5e2-4c5d-ab0c-9d434d17ea92)
![png35](https://github.com/joone-org/curriculum.joone.org/assets/137515679/dc6915b0-041f-4f28-8688-996f7c4e462f)
![png34](https://github.com/joone-org/curriculum.joone.org/assets/137515679/9a743127-901d-4f53-8a6c-c2760fcf5326)
![png33](https://github.com/joone-org/curriculum.joone.org/assets/137515679/56785b42-d0af-4b7c-92e9-86df52d209e2)
![png32](https://github.com/joone-org/curriculum.joone.org/assets/137515679/e53cf144-d3ea-444e-b921-ff2f69b3f697)
![png31](https://github.com/joone-org/curriculum.joone.org/assets/137515679/91fc22be-bbdd-4884-9d89-49e6f447f528)
![png30](https://github.com/joone-org/curriculum.joone.org/assets/137515679/d0f7720f-9cdd-48be-a31a-4d11e2448daa)
![png29](https://github.com/joone-org/curriculum.joone.org/assets/137515679/35eb45e5-04e7-4c69-a249-83810c214bf8)
![png27](https://github.com/joone-org/curriculum.joone.org/assets/137515679/b5a574f2-acb4-44d8-b33a-76924d419edf)
![png26](https://github.com/joone-org/curriculum.joone.org/assets/137515679/95133444-e6c4-41e3-baa6-5706aaf9155e)
![png25](https://github.com/joone-org/curriculum.joone.org/assets/137515679/51140a29-ec8c-47a6-8868-67a6b922705d)
![png24](https://github.com/joone-org/curriculum.joone.org/assets/137515679/5d235bac-98ed-4167-9e45-49bc39519b70)
![png22](https://github.com/joone-org/curriculum.joone.org/assets/137515679/a53e5f23-8fdf-4594-acb3-281122de81bf)
![png21](https://github.com/joone-org/curriculum.joone.org/assets/137515679/0022579e-f48c-4db5-8af5-978be13652f8)
![png20](https://github.com/joone-org/curriculum.joone.org/assets/137515679/b5a03b9b-95c7-4eff-a99a-acecd654e491)
![png19](https://github.com/joone-org/curriculum.joone.org/assets/137515679/cdd4713e-ac15-4af8-80b8-bb7fec80eaa9)
![png18](https://github.com/joone-org/curriculum.joone.org/assets/137515679/277f941d-038a-462e-b7a2-cf1d85c67378)
![png17](https://github.com/joone-org/curriculum.joone.org/assets/137515679/41776e67-ccd9-4505-94d6-f4f02cbb0453)
![png16](https://github.com/joone-org/curriculum.joone.org/assets/137515679/b2019be2-01ab-4123-aea7-b15d5df0b52c)
![png15](https://github.com/joone-org/curriculum.joone.org/assets/137515679/c624907c-37a6-4a6c-8713-f978204cecb3)
![png14](https://github.com/joone-org/curriculum.joone.org/assets/137515679/54675b2e-e4e3-4b10-86bd-b2e0848f9f93)
![png13](https://github.com/joone-org/curriculum.joone.org/assets/137515679/dbcad470-d4fb-430c-b8dc-817e8bbee594)
![png12](https://github.com/joone-org/curriculum.joone.org/assets/137515679/2419ea3d-e9de-4599-a2cb-5c977f4f377e)
![png10](https://github.com/joone-org/curriculum.joone.org/assets/137515679/d4f6b31f-c0db-41cc-9e6a-6fa5d92653e1)
