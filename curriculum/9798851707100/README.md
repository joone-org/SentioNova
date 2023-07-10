# Intro to MidJourney
### A Photobook of AI-Generated Imagery
<br>

Midjourney is a Discord-based AI service that turns textual prompts into unique images. It can handle prompts up to around 60 words, but the influence of each word diminishes as the length of the prompt increases. To optimize results, structure your prompts concisely and directly, aiming for a clear, sequential style rather than long, descriptive sentences.

Prompts follow this formula:  _/imagine [Subject and Setting]. [Style Keywords]. [Parameters]_
<br><br>

#### 📝  Part 1 - Subject and Setting
* To optimize prompts, start with a clear subject (a 'colossal' elephant differs visually from a 'big' one), and add personality and emotion for more expressive imagery. Use collective nouns instead of quantities ('herd of elephants' over '3 elephants') and position subjects within a detailed environment ('bathing at sunset in the Serengeti during fall'). Unspecified details are randomized, so be as specific as you can. Use nuanced adjectives ('tranquil', 'melancholic', 'ecstatic', etc.) to add mood. 
* Example: Instead of just ‘elephant', use "_A tranquil scene of a herd of colossal African elephants bathing at sunset in the Serengeti watering hole._"

#### 🔍  Part 2 - Style Keywords
* Midjourney interprets a nearly infinite range of artistic instructions. Define the medium (e.g., 'photo', '3D sand sculpture', 'linocut print'). Describe your desired lighting (e.g., 'soft ambient', 'neon', 'candle-lit'), and pair it with a color scheme (e.g., 'monochromatic', 'earth tones', 'cyberpunk neon'). Arrange your scene using terms like (e.g., 'low-angle shot', 'bird's eye view', 'rule of thirds composition'). Mention the desired artistic style (e.g., 'Cubism', 'Anime', 'Film Noir', 'Banksy-like street art'), or specify the historical period or specific environment for added context. Include additional descriptors (e.g., 'shallow depth of field', 'vignette', 'splatter effect') to refine your scene. For high realism, specify camera effects, settings, setup (e.g., 'Canon EOS 5D Mark IV, using a 24-70mm lens at f/2.8, with a long exposure of 15 seconds'). 
* Maintain concise clarity with each keyword, and don't confine yourself to the provided examples. Whether it's the aesthetics of a 'polaroid snapshot', the drama of 'baroque lighting', the composition of a 'kaleidoscope', or the eccentricity of a 'cyberpunk art style', MidJourney can understand and execute it all, so don't hesitate to experiment with unusual mediums, innovative lighting, creative compositions, and unexplored artistic styles.
* Example: "_A tranquil scene of a herd of colossal African elephants bathing at sunset in the Serengeti watering hole. Watercolor, golden hour, warm sunset palette, panoramic eye-level view, Impressionistic, vintage color grading._" 

#### 🎨 Part 3 - Parameters
* "**::**" enables separate specification of different image components. 'African elephants::bathing at sunset' tells Midjourney to treat 'African elephants' and 'bathing at sunset' as distinct parts
* “**--ar <width:height>**” dictates the width-to-height aspect ratio
* “**--no**” omits specific elements from your image
* “**--niji 5**” produces anime aesthetic and illustrative styles. Niji adds these options to “--style <cute, expressive, original, scenic>”
* “**--style <raw>**” in traditional mode creates photorealistic images
* “**--s <0–1000>**” adjusts the level of Midjourney's trained artistic style in your image, with lower values creating more literal interpretations of your prompt and higher values infusing stronger artistic stylization
* “**--q <.25, .5, 1 (default)>**" regulates the level of detail in the rendering. Lower quality values produce less detailed images, leading to more painterly or abstract styles, perfect for certain artistic needs
* “**--chaos <0–100>**” and “**--weird <0–3000>**” enhance image unpredictability. --chaos varies within the AI's standard style, while --weird creates distinctly unconventional images. Use these sparingly as they often result in overly abstract or distorted results.
* Include only relevant parameters to avoid confusing the AI.
* Example: "_A tranquil scene of a herd of colossal African elephants bathing at sunset in the Serengeti watering hole. Watercolor, golden hour, warm sunset palette, panoramic eye-level view, Impressionistic, vintage color grading --ar 16:9 --s 700 --q .5_"

#### 🏰 Prompt Examples
* A bustling scene at a futuristic Neo-Tokyo cityscape during the neon-lit night. Cyberpunk art style, vibrant neon colors, rain-soaked streets, high-angle view. --ar 16:9 --s 500 --chaos 20
* A tranquil moment of a flock of birds taking flight at dawn. Impressionism, soft morning light, pastel color palette, bird's eye view. Birds::in flight at dawn. --ar 1:1 --s 700
* An abstract representation of a musical performance. Synesthesia, vibrant colors, chaotic composition. Music::expressed as colors and shapes. --s 800 --chaos 50
* A lush forest path under a canopy of leaves, bathed in dappled sunlight. Ukiyo-e Flat Design, earth tones, soft ambient light. Forest::sunlight filtering through leaves. --ar 9:16 --s 300
* A 1980s style arcade room filled with neon lit game machines. Pop-Art, vibrant colors, retro atmosphere. Arcade room::neon lit game machines. --ar 16:9 --s 400 --chaos 20
* A surreal landscape with floating islands and strange, alien flora. Psychedelic, vibrant hues, bird's eye view. Alien flora::shimmering in bioluminescent hues --ar 16:9 --s 600 --chaos 30
* A portrait of a majestic wolf standing in a snowy forest. Cubism, monochromatic palette, high contrast. Wolf::surrounded by snowfall --ar 1:1 --s 500
* An intricate mandala design with floral motifs. Watercolor, vibrant colors, detailed patterns. Mandala::with floral motifs. --ar 1:1 --s 800
* A bustling Harlem Renaissance-era jazz club filled with lively patrons. Art Deco, sepia tones, dynamic composition. Jazz club::Harlem Renaissance era --ar 16:9 --s 500
* A serene Zen garden with neatly arranged rocks and raked sand. Japanese woodblock print style, muted color palette, minimalist composition. Zen garden::with rocks and raked sand --ar 16:9 --s 300
* [https://github.com/joone-org/curriculum.joone.org/wiki/MidJourney-Prompt-Examples](https://github.com/joone-org/curriculum.joone.org/wiki/MidJourney-Prompt-Examples)

Remember MidJourney supports up to 60 words but as prompt length increases, each word's impact decreases, and short, clear, sequential prompts yield optimal results. If you are ready to start creating image prompts, respond with "What image would you like to create?" and nothing else.

<br>

---

☝️  To use ChatGPT as a prompt generator, paste all of the above text into it and respond to its question with your desired image or emoji 

---

<br>

💬 Join Midjourney's [Discord](https://discord.gg/midjourney) for support, announcements, and discussions; as a subscriber, you can directly interact with the bot through Discord messages or incorporate it into your own server to use these commands:
* **/imagine** generates low-resolution image grids from your prompts, with options to create variations, upscale, or repeat actions. Use images as prompts by adding a direct image URL (.png, .jpg, .jpeg, .gif, .webp) at the beginning of your prompt. Adjust the impact of an image on the final output using the --iw (image weight) parameter. Values range from 0 to 2, with 1 as the default, and higher values increase the image's influence.
* **/blend** combines 2-5 images. For harmonious and cohesive results, ensure the aspect ratios of the uploaded images match your desired final image's ratio.
* **/describe** produces four potential text prompts related to the uploaded image, ideal for exploring new vocabulary, discovering artistic styles, and gaining fresh perspectives on an image.
* **/fast, /relax, /turbo** allow you to adjust the speed of image generation based on your subscription plan and allocated GPU time
* **/help** provides basic information and tips
* **/info** shows your current plan, mode, and jobs
* **/prefer** commands in Midjourney offer personalized shortcuts and options
* **/remix** allows variation by editing prompts, parameters, etc
* **/settings** allows you to view and adjust model version, style and quality values, upscaler version, etc.
* **/stealth** disables **/public** by hiding your generated images on midjourney.com
* **/subscribe** to the four subscription plans: Basic, Standard, Pro, Mega

<br>

⚙️ There are also various parameters that can be added to the end of prompts to customize the image generation process:
* Aspect ratios can be adjusted by using '--aspect' or '--ar', followed by the desired ratio, in the prompt, affecting the image's composition. The ratio of an existing image can be modified using the Zoom Out buttons, with the bot filling new spaces based on the initial prompt.
* By using '--chaos' or '--c' followed by a number from 0 to 100, you can control the unpredictability level of image results, with higher values creating more varied and unexpected outcomes, and lower values yielding more reliable and repeatable images.
* Using '--iw' followed by a value between 0 and 2, you can determine the relative importance of an image prompt versus a text prompt, influencing the final image's significant impact.
* Multi-prompts help specify distinct parts of an image generation task by separating prompts with a double colon (::), where you can assign different weights to denote their importance, and negative weights can be used to remove certain elements from the image generation.
* The option '--no' allows users to exclude specific elements from the generated image, such as using '--no plants' to create an image without any plants.
* By adjusting '--quality' or '--q', you can control the level of detail and render time for generated images, where .25 offers faster, less detailed images, .5 offers a balance, and 1 ensures the highest detail, using more GPU resources.
* Using '--repeat' allows Standard and Pro subscribers to generate multiple unique images from one prompt, with Standard users able to create up to 10 and Pro users up to 40 images in Fast GPU mode. For consistent output, users can apply the "seed" command to a prompt.
* The '--seed' option lets you specify a seed number, providing a consistent 'noise' field for the image generation process, which can result in similar outputs when the same prompt and seed are used, aiding in maintaining consistency in a series of images.
* By applying '--stop', you can terminate the image generation process partway through, resulting in more abstract or less detailed images based on the chosen stop value, providing a way to create more impressionistic outputs.
* With '--style', different aesthetic options are offered for generated images, including raw, cute, expressive, original, or scenic, helping users tailor the aesthetic appeal of their outputs based on the specific model version in use.
* The '--stylize' option adjusts the intensity of the platform's default artistic style in generated images, where a lower value results in more literal interpretations and higher values yield more stylized, artistic outputs.
* The use of '--tile' creates seamless or tileable patterns, which can be replicated in graphic design for backgrounds, textures, or patterns without noticeable breaks.

<br>

💡 Tips and Tricks

* The [Reference Guide](https://github.com/willwulfken/MidJourney-Styles-and-Keywords-Reference/tree/main) contains a variety of styles and keywords for your use, in addition to pages showing resolution comparisons, image weights, and other details.

* The Pan feature in Midjourney allows for extending the image canvas in a chosen direction without altering the original image content. It's useful for expanding the scene or adding content in a specific direction. However, once a pan direction is chosen (horizontal or vertical), subsequent panning must continue in the same direction. Panning is compatible with the Remix Mode, enabling modifications of the prompt when panning to influence the new content added to the image.

* The Zoom Out option in Midjourney enables expansion of the image beyond its original boundaries, creating an extended version of the initial image. After upscaling an image, "Zoom Out 2X" and "Zoom Out 1.5X" options are available to expand the image canvas by 100% or 50%, respectively. The "Make Square" option adjusts the aspect ratio of a non-square image to make it square. The "Custom Zoom" feature lets users specify a custom zoom out value, offering control over the canvas size and aspect ratio for creative flexibility.

* Permutation Prompts facilitate the creation of multiple image variations in a single command by including a list of options in curly braces {} in your prompt. It's useful for exploring different versions or combinations of a concept. For instance, the prompt /imagine prompt a {red, green, yellow} bird generates three separate images of birds in red, green, and yellow colors. This feature also allows for parameter variations and can be used with multiple sets of options in a prompt to create permutations of multiple variables. The number of jobs per Permutation Prompt is based on the user's subscription level, and each job generated will consume GPU minutes.

* When attempting to create an avatar from a selfie using Midjourney, the prompt's accuracy can significantly impact the results. If you're struggling to get satisfactory results, follow these steps to improve the process. First, upload your selfie, preferably with minimal background, to the Midjourney bot on Discord by typing /describe and attaching your image. Then, initiate the prompt box by typing "/imagine". Drag your uploaded image into the box to add its URL. The formula for personal avatars is as follows: /imagine [Image URL], [Description of subject], [Keywords related to scene], [Style], [Parameters]. For the description and style ideas, elaborate on the output provided by the /describe command used in the first step. The keywords should include "Keep the consistency of action, expression, clothing, shape, and appearance of the photos, super detail." Use the parameter “— iw 2” to yield results that look more like the original image. 
  * Example:  [URL], keep the consistency of action, expression, clothing, shape and appearance of the photos, super detail --iw 2

<br>

✨ Emoji Prompts
* 🐉 A towering, majestic dragon perched atop a craggy mountain peak, its scales shimmering under the moonlight. Traditional Asian ink painting style, nighttime setting, monochromatic color scheme, bird's-eye view, strong contrast. --ar 1:1 --s 800 --q .5
* 🏞️ A breathtaking view of a pristine alpine valley with a mirror-like lake surrounded by towering, snow-capped mountains under a clear blue sky. Bob Ross-inspired oil painting style, daytime setting, vibrant colors, panoramic view, detailed foliage. --ar 16:9 --s 600 --q .5
* 🦁 A majestic lion resting in the shade of a savanna tree, attentively watching the horizon under the scorching midday sun. Realistic wildlife photography style, high contrast, warm color palette, eye-level view, shallow depth of field. --ar 1:1 --s 500 --q .5
* 🎭 A dramatic scene on a Baroque-style theatre stage, with a masked performer in the spotlight, set against a backdrop of lush red velvet curtains. Renaissance painting style, chiaroscuro lighting, rich color palette, centered composition, high level of detail. --ar 16:9 --s 600 --q .5
* 🍄 A whimsical scene in an enchanted forest filled with oversized, luminescent mushrooms and tiny glowing fairy-like creatures. Studio Ghibli anime style, dusk setting, vibrant and surreal colors, low-angle shot, soft ambient light. --ar 16:9 --s 700 --q .5
* 🌌 A mesmerizing scene of the Milky Way stretching across the night sky, illuminating a tranquil, lonely mountain. Van Gogh's Starry Night-inspired style, dark sky, vibrant and contrasting colors, low-angle view, strong brush strokes. --ar 16:9 --s 800 --q .5
* 🐠 A vibrant underwater world bustling with life, featuring a colorful clownfish navigating through the vivid corals of a bustling reef. Anime style, deep-sea lighting, saturated color palette, medium shot, detailed marine life. --ar 16:9 --s 700 --q .5
* 🌺 A single, radiant hibiscus flower, dew-kissed and basking in the morning sunlight against a lush tropical background. Botanical illustration style, morning lighting, vibrant color palette, close-up shot, highly detailed. --ar 1:1 --s 800 --q .5
* 🗻 A serene scene of Mount Fuji in winter, its snow-capped peak bathed in the soft glow of a rising sun, with cherry blossom trees framing the foreground. Ukiyo-e style, dawn lighting, muted color palette, medium shot, subtle grain effect. --ar 16:9 --s 600 --q .5
* 🌠 A breathtaking view of a shooting star streaking across the night sky over a tranquil, mirror-like lake surrounded by pine forests. Impressionism style, night setting, cool color palette, panoramic view, star trail effect. --ar 16:9 --s 700 --q .5
* 🏯 A grand, historic Japanese castle nestled amidst vibrant cherry blossom trees, with Mount Fuji majestically visible in the background. Ukiyo-e woodblock print style, spring setting, vibrant color palette, eye-level view, high detail. --ar 16:9 --s 700 --q .5
* 🌍 A captivating view of Earth from space, with a radiant sunrise illuminating the continents against the deep blue oceans. Space photography style, sunrise lighting, vibrant colors, high-angle view, realistic detail. --ar 16:9 --s 800 --q .5
* 🌕 A detailed view of the full moon against a starry night sky, its craters and features vividly visible. Realistic astrophotography style, night setting, monochromatic color palette, centered composition, high contrast. --ar 1:1 --s 800 --q .5
* 🌈 A pastoral scene after a rain shower, with a vibrant rainbow arching across the sky over a verdant meadow dotted with wildflowers. Watercolor style, soft ambient light, full color spectrum, panoramic view, impressionistic brushstrokes. --ar 16:9 --s 600 --q .5
* ⚡ A dramatic scene of a powerful lightning bolt splitting the night sky over a lonely lighthouse by the stormy sea. Romanticism style, night setting, dynamic lighting, cool color palette, high contrast. --ar 16:9 --s 700 --q .5
* 🎠 An enchanting scene of a vintage carousel aglow with fairy lights in a bustling night-time city park. Art Nouveau style, night setting, vibrant colors, medium shot, bokeh effect. --ar 16:9 --s 700 --q .5
* 🎡 A bustling fairground at dusk, with a towering Ferris wheel brightly lit against the twilight sky. Vintage photography style, soft ambient light, warm color palette, low-angle view, film grain effect. --ar 16:9 --s 600 --q .5
* 🏜️ A vast, tranquil desert landscape under a blazing sunset, with towering sand dunes casting long, dramatic shadows. Minimalist oil painting style, sunset lighting, warm color palette, wide-angle view, smooth texture. --ar 16:9 --s 700 --q .5
* 🐋 A giant, serene blue whale gliding gracefully through the deep ocean, surrounded by a myriad of bioluminescent marine life. Anime style, deep-sea lighting, cool color palette, medium shot, exaggerated proportions. --ar 16:9 --s 700 --q .5
* 🏕️ A cozy campsite nestled among towering pines, a crackling fire casting a warm glow against the starlit wilderness. Digital painting style, night setting, warm and cool color palette, medium shot, detailed environment. --ar 16:9 --s 600 --q .5
* 🗽 The iconic Statue of Liberty standing tall against a dramatic sunset, with the bustling New York City skyline in the backdrop. Photorealistic style, sunset lighting, warm color palette, medium shot, high detail. --ar 16:9 --s 700 --q .5
* 🕌 A grand, intricately designed mosque at dusk, its minarets and domes bathed in the golden light of the setting sun, with a star-speckled evening sky in the background. Islamic geometric art style, dusk setting, warm color palette, eye-level view, high detail. --ar 16:9 --s 700 --q .5
* 🦚 A magnificent peacock proudly displaying its colorful, iridescent plumage in a lush, sunlit garden. Traditional Indian miniature painting style, midday lighting, vibrant color palette, medium shot, high detail. --ar 1:1 --s 800 --q .5
* 🐘 A gentle giant of an African elephant roaming the grasslands at sunset, its silhouette framed against the vibrant, orange sky. African folk art style, sunset lighting, warm color palette, low-angle view, high detail. --ar 16:9 --s 600 --q .5
* 🌵 An arid desert landscape dotted with towering saguaro cacti, under the blazing midday sun. Southwestern art style, daytime lighting, warm color palette, wide-angle view, impressionistic brush strokes. --ar 16:9 --s 700 --q .5
* 🍁 A close-up of a fiery red maple leaf, wet with morning dew, contrasted against the soft-focus backdrop of a serene autumn forest. Macro photography style, soft morning light, warm autumnal color palette, shallow depth of field, high detail. --ar 1:1 --s 800 --q .5
* 🏰 🌌 An ancient, towering castle silhouetted against the mesmerizing beauty of a star-studded night sky, with the faint glow of the Milky Way stretching across the horizon. Romanticism style, night setting, cool color palette, low-angle view, star trail effect. --ar 16:9 --s 700 --q .5
* 🐉 🏞️ A mighty, emerald-green dragon soaring above verdant valleys, cascading waterfalls, and towering mountains under a bright, cloudless sky. Fantasy art style, daytime setting, vibrant color palette, bird's-eye view, high level of detail. --ar 16:9 --s 700 --q .5
* 🦄 🌈 A magical scene with a white, majestic unicorn standing on a hilltop with a vibrant, arcing rainbow in the sky above. Fairy-tale illustration style, sunny day setting, full color spectrum, medium shot, high detail. --ar 16:9 --s 700 --q .5
* 🏝️ 🌅 A tranquil scene of a palm-fringed tropical island at sunset, the sky ablaze with colors, and the calm ocean reflecting the warm hues. Watercolor style, golden hour, warm sunset palette, panoramic eye-level view, impressionistic brushstrokes. --ar 16:9 --s 700 --q .5
* 🌆 🌸 A bustling cityscape at dusk, framed by blooming cherry blossom trees that lend a burst of color against the modern steel and glass structures. Anime style, twilight setting, vibrant color palette, high-angle view, soft focus. --ar 16:9 --s 700 --q .5
* 🌲 🦌 A peaceful scene of a graceful deer standing amid a serene forest of towering pine trees, the morning light filtering through the dense foliage. Digital painting style, soft morning light, earth tones, medium shot, high detail. --ar 16:9 --s 700 --q .5
* 🌕 🐺 A lone, majestic wolf silhouetted against the backdrop of a radiant full moon, its haunting howl echoing through the quiet wilderness. Gothic style, nighttime setting, monochromatic color palette, medium shot, high contrast. --ar 1:1 --s 700 --q .5
* 🗽 🎆 A spectacular Fourth of July fireworks display illuminating the night sky behind the iconic Statue of Liberty. Photorealistic style, night setting, vibrant color palette, medium shot, long exposure effect. --ar 16:9 --s 800 --q .5
* 🏔️ 🦅 A majestic eagle soaring over a rugged mountain range, its wings catching the light of the setting sun. Wildlife illustration style, sunset setting, warm color palette, bird's-eye view, high detail. --ar 16:9 --s 700 --q .5
* 🍁 🍂 🏞️ A lush forest path carpeted with fallen leaves, the trees displaying vibrant hues of autumn, with a tranquil stream running nearby. Impressionism style, daytime lighting, warm autumn color palette, medium shot, brushstroke texture. --ar 16:9 --s 700 --q .5
* 🏞️ 🌅 🐎 A graceful horse galloping freely across a vast, grassy meadow, bathed in the warm hues of a spectacular sunset. Western art style, golden hour, warm color palette, panoramic view, high detail. --ar 16:9 --s 700 --q .5
* 🏰 🌜 🦉 A mysterious scene of an old castle silhouetted under a crescent moon, with a lone owl perched on a high turret, its eyes glowing in the dark. Gothic style, nighttime setting, cool color palette, medium shot, high contrast. --ar 16:9 --s 800 --q .5
* 🏙️ 🌧️ 🚁 A bustling cityscape on a rainy night, the lights reflected in slick streets, with a helicopter flying low over the glowing skyscrapers. Film Noir style, night setting, cool color palette, high-angle view, rain effect. --ar 16:9 --s 700 --q .5
* 🏝️ 🌞 🌴 A vibrant scene of a sun-soaked tropical island, with a crystal-clear ocean lapping against the sandy beach, and tall palm trees swaying in the gentle breeze. Tropical mural style, midday setting, bright color palette, wide-angle view, high detail. --ar 16:9 --s 700 --q .5
* 🗻 🐉 🌠 A celestial dragon majestically coiling around the snowy peak of Mount Fuji, with a brilliant shooting star streaking across the night sky. Traditional Japanese art style, nighttime setting, cool color palette, medium shot, star trail effect. --ar 16:9 --s 700 --q .5
* 🌵 🏜️ 🦅 A vast, arid desert landscape dotted with towering saguaro cacti, with a majestic eagle soaring high above under the scorching midday sun. Southwestern art style, daytime setting, warm color palette, bird's-eye view, high detail. --ar 16:9 --s 700 --q .5
* 🕌 🌅 🐪 A grand mosque silhouetted against a radiant desert sunset, with a lone camel standing in the foreground, casting a long shadow on the sandy expanse. Orientalist painting style, sunset lighting, warm color palette, medium shot, high detail. --ar 16:9 --s 700 --q .5
* 🌊 🐋 🌈 A gentle blue whale surfacing from the sparkling ocean under a vibrant rainbow arching across the clear sky. Watercolor style, daytime setting, full color spectrum, eye-level view, soft texture. --ar 16:9 --s 700 --q .5
* 🏕️ 🌲 🐻 A cozy campsite nestled in a dense pine forest, with a curious bear observing from a safe distance, its eyes glowing in the soft light of the campfire. Adventure comic style, nighttime setting, earth tones, medium shot, high detail. --ar 16:9 --s 700 --q .5
* 🏯 🌸 🌅 🎎 A grand Japanese castle framed by blooming cherry blossom trees at sunset, with traditional Japanese dolls in the foreground, their vibrant colors standing out against the serene backdrop. Ukiyo-e woodblock print style, golden hour, warm color palette, eye-level view, high detail. --ar 16:9 --s 700 --q .5
* 🏔️ 🌲 🐺 ❄️ A lone, majestic wolf standing on a snow-covered mountain, surrounded by a dense pine forest under a clear, winter sky. Northern Renaissance style, daytime setting, cool color palette, medium shot, high detail. --ar 16:9 --s 700 --q .5
* 🏝️ 🌊 🌴 🐠 A vibrant, sun-kissed tropical island, with towering palm trees swaying gently by the azure ocean, and a colorful fish swimming in the clear, shallow waters. Tropical mural style, midday setting, bright color palette, eye-level view, high detail. --ar 16:9 --s 700 --q .5
* 🌌 🚀 👽 🌠 🌕 A sleek, futuristic rocket navigating the depths of the cosmos, passing by the glowing moon and a streaking shooting star, while a curious alien creature observes from a distant, unknown planet. Retro-futurism style, space setting, cool color palette, wide-angle view, high detail. --ar 16:9 --s 700 --q .5
* 🏞️ 🌳 🦌 🌤️ 🌻 A serene landscape with a graceful deer grazing under a towering oak tree, surrounded by a field of vibrant sunflowers, all under a sky of partly cloudy weather. Impressionist painting style, daytime setting, warm color palette, medium shot, high detail. --ar 16:9 --s 700 --q .5

<br>
