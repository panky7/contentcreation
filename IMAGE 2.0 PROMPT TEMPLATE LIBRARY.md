# **IMAGE 2.0 PROMPT TEMPLATE LIBRARY**

Copy-Paste Prompt Templates for Creators, Marketers, Agencies & Business Teams

A practical, audience-ready library of detailed prompts for product mockups, model photography, outfit shots, ad creatives, carousel covers, brand visuals, packaging concepts, and business marketing assets.

**How to use this document: replace anything in [square brackets], keep the structure, and add the output size/platform at the end of every prompt.**

---

# What This Library Includes

- Prompt format guide: when to use natural language vs. JSON
- Universal prompt formula for any image idea
- 40 ready-to-copy templates across creator, brand, product, fashion, agency and business use cases
- Add-on lines to improve realism, luxury, ad performance, text rendering and identity consistency

# Natural Language Prompt vs. JSON Prompt

Both formats work well. The right choice depends on how much control you need. Natural language is best for organic, photographic, and creative outputs. JSON is better when the image has many controlled parts such as layout, text, brand rules, product details, platform ratio, or repeated campaign variations.

| **Use Case** | **Best Format** | **Why** |
| --- | --- | --- |
| Instagram photos, fashion shots, UGC-style images | Natural language | More fluid, creative and photographic. |
| Product mockups, ad creatives, brand campaigns | JSON | Better control over layout, copy, colors, props and ratios. |
| Model photography with pose/outfit/location | Natural language or JSON | Natural for realism; JSON for repeatable shot lists. |
| Agency creative testing | JSON | Easier to create controlled variations. |
| Posters, flyers and infographics with text | JSON | Helps preserve hierarchy, text blocks and layout. |
| Image editing, face consistency, outfit changes | Natural language | Clear edit instructions usually work better. |
| E-commerce catalog shots | JSON | Consistency across angles, lighting and background. |

# Universal Prompt Formula

Create a [TYPE OF IMAGE] for [BRAND / PERSON / PRODUCT / USE CASE].

Subject:

[Describe the main person/product/object clearly.]

Scene:

[Describe location, background, props, time of day, environment.]

Style:

[Photorealistic / editorial / luxury / UGC / cinematic / minimal / futuristic / magazine / DTC ad style.]

Composition:

[Close-up / full body / flat lay / 3/4 angle / top-down / hero shot / centered / rule of thirds.]

Lighting:

[Soft natural light / studio lighting / golden hour / flash photography / high contrast / diffused daylight.]

Mood:

[Premium / playful / trustworthy / aspirational / bold / calm / high-energy.]

Details:

[Clothing, colors, textures, objects, packaging, facial expression, hand position, product placement.]

Output:

[Aspect ratio, platform, no extra text unless specified, high-resolution, realistic proportions.]

---

# Prompt Template Library

## 1. Creator Portrait / Personal Brand Shot

**Best format:** Natural language

For creator profiles, AI educator pages, founder-led content and personal branding.

Create a realistic editorial portrait of a female creator standing in a modern creative studio. She is dressed in a polished smart-casual outfit: tailored blazer, clean top, minimal jewelry, soft makeup, and styled hair. The background has a premium creator workspace aesthetic with a laptop, moodboard, camera, soft warm lighting, and subtle AI/design elements on a screen.

The mood should feel confident, intelligent, modern, and aspirational. Use shallow depth of field, natural skin texture, realistic facial features, soft studio lighting, and a high-end magazine photography style. Composition should be vertical 9:16, waist-up framing, subject slightly off-center, looking directly at the camera.

---

## 2. Founder / CEO LinkedIn Profile Image

**Best format:** Natural language

For founders, consultants, speakers, CXOs and business profiles.

Create a professional LinkedIn-style portrait of a startup founder in a modern office environment. The person should look confident, approachable, and credible. Outfit: sharp business-casual blazer, neutral colors, clean grooming, subtle expression.

Background: blurred modern office with glass walls, laptop screens, plants, and warm daylight. Lighting should be soft, professional, and flattering. The image should look like a premium personal branding photoshoot, not a stock photo. Square 1:1 aspect ratio, high-resolution, realistic skin texture, natural posture, no text.

---

## 3. Instagram Reel Cover for AI Tool Content

**Best format:** JSON

Use when text hierarchy and a scroll-stopping thumbnail matter.

{

"image_type": "Instagram reel cover",

"aspect_ratio": "9:16",

"topic": "AI tools for creators",

"main_visual": "A stylish creator sitting at a desk with laptop, phone, and floating AI interface cards around her",

"style": "premium tech editorial, bold, modern, high contrast",

"background": "dark gradient studio background with subtle glow and digital UI elements",

"text_overlay": {

"headline": "5 AI Tools I Use Daily",

"subheadline": "for content, ads & design",

"text_style": "large bold sans-serif, clean, high contrast, easy to read on mobile"

},

"composition": "subject on lower third, headline on upper half, strong empty space for text",

"lighting": "cinematic softbox lighting with subtle rim light",

"mood": "smart, futuristic, premium, creator-led",

"negative_prompt": "no messy text, no extra words, no distorted hands, no cluttered background"

}

---

## 4. Viral Carousel Cover

**Best format:** JSON

For Instagram or LinkedIn educational posts where the hook must be instantly readable.

{

"image_type": "Instagram carousel cover",

"aspect_ratio": "4:5",

"theme": "AI productivity for everyday work",

"headline": "7 Things AI Can Do in 5 Minutes",

"visual_concept": "A split-screen visual showing chaotic manual work on one side and clean AI-powered workflow on the other",

"style": "bold editorial social media design, premium but relatable",

"color_palette": "black, white, electric blue, soft gray",

"layout": {

"headline_position": "center top",

"supporting_visual": "middle and bottom area",

"spacing": "clean, minimal, scroll-stopping"

},

"typography": "large bold sans-serif headline, high contrast, mobile-readable",

"details": "include subtle icons for email, spreadsheet, design, research, calendar, ads, and writing",

"negative_prompt": "no tiny unreadable text, no random logos, no clutter"

}

---

## 5. UGC-Style Product Ad Image

**Best format:** Natural language

For creator-style ads, testimonial visuals and casual product content.

Create a realistic UGC-style photo of a young woman holding [PRODUCT NAME] in her hand while sitting near a window in a cozy bedroom. The image should look like an authentic phone-shot creator post, not a polished studio ad.

Product should be clearly visible in the foreground. The creator is smiling naturally, wearing casual but aesthetic loungewear. Background includes soft bedding, a coffee cup, sunlight through curtains, and a relaxed lifestyle feel.

Lighting: natural morning light. Mood: honest, relatable, warm, trustworthy. Composition: vertical 9:16, slightly candid angle, realistic skin texture, natural hand position, no text.

---

## 6. Luxury DTC Product Hero Shot

**Best format:** JSON

For premium product ads, launch assets and DTC brand visuals.

{

"image_type": "luxury product hero shot",

"aspect_ratio": "4:5",

"product": "[PRODUCT NAME]",

"category": "[skincare / perfume / supplement / fashion accessory / beverage]",

"scene": "minimal studio setup with premium props",

"background": "warm beige stone surface with soft shadows",

"product_position": "center foreground, slightly elevated on a pedestal",

"props": ["soft fabric folds", "natural ingredient references", "glass reflection", "subtle brand-colored accent"],

"lighting": "soft diffused studio light with gentle highlights",

"style": "luxury DTC campaign, clean, premium, editorial",

"mood": "elegant, expensive, trustworthy",

"composition": "balanced, plenty of negative space for future ad copy",

"negative_prompt": "no fake unreadable label text, no distorted packaging, no extra products"

}

---

## 7. Skincare Before/After Concept Ad

**Best format:** JSON

For beauty concepts where credibility and claim control matter.

{

"image_type": "skincare campaign visual",

"aspect_ratio": "1:1",

"concept": "before and after transformation without exaggeration",

"main_visual": "A clean split-frame portrait of the same woman, left side dull tired skin, right side fresh hydrated glowing skin",

"style": "premium dermatology-inspired beauty photography",

"lighting": "soft clinical studio lighting",

"background": "clean off-white background",

"text_overlay": {

"headline": "From Dull to Dewy",

"subheadline": "Hydration you can see",

"disclaimer": "Results may vary"

},

"tone": "credible, refined, not overdramatic",

"negative_prompt": "no unrealistic glass skin, no medical claims, no acne shaming, no exaggerated transformation"

}

---

## 8. Fashion Outfit Photography

**Best format:** Natural language

For outfit pages, fashion creators, lookbooks and editorial visuals.

Create a high-fashion full-body outfit photograph of a female model wearing [OUTFIT DETAILS]. The model is standing confidently on a clean urban street with elegant architecture in the background.

Style should feel like a premium fashion editorial: sharp composition, natural pose, refined styling, expensive-looking textures, and realistic fabric movement. The model should have polished makeup, styled hair, and minimal accessories that complement the outfit.

Lighting: soft golden-hour daylight. Composition: vertical 9:16 full-body shot, slightly low camera angle, model centered, background softly blurred. Mood: confident, modern, aspirational. No text.

---

## 9. Outfit of the Day Creator Shot

**Best format:** Natural language

For relatable OOTD, fashion reels, mirror selfie aesthetics and creator content.

Create a realistic mirror selfie-style outfit photo of a fashion creator wearing [OUTFIT DETAILS]. The image should look like a stylish Instagram OOTD post taken in a clean apartment mirror.

The room should have a minimal aesthetic: neutral walls, soft rug, plant, full-length mirror, natural daylight. The phone partially covers the face in a natural way. Outfit should be clearly visible from head to toe. Keep proportions realistic, fabric details sharp, and lighting flattering.

Aspect ratio: 9:16. Mood: effortless, stylish, relatable, premium.

---

## 10. Model Photography for Clothing Brand

**Best format:** JSON

For clothing catalogues and consistent fashion campaign outputs.

{

"image_type": "fashion e-commerce campaign photo",

"aspect_ratio": "4:5",

"model": {

"description": "female model, confident posture, natural expression",

"pose": "standing with one hand in pocket, slight turn toward camera"

},

"outfit": {

"main_item": "[CLOTHING ITEM]",

"details": "[fabric, color, fit, silhouette]",

"styling": "minimal accessories, clean footwear"

},

"location": "minimal studio with soft neutral background",

"lighting": "large softbox lighting, gentle shadows",

"style": "premium fashion catalog meets editorial campaign",

"composition": "full-body shot with clear view of garment shape and fit",

"mood": "modern, polished, commercially usable",

"negative_prompt": "no distorted limbs, no unrealistic fabric, no excessive posing, no clutter"

}

---

## 11. Product Mockup on Desk

**Best format:** JSON

For SaaS, websites, apps and portfolio mockups.

{

"image_type": "product mockup",

"aspect_ratio": "16:9",

"product": "[APP / WEBSITE / SAAS DASHBOARD]",

"device": "MacBook laptop with optional iPhone beside it",

"screen_content": "clean dashboard interface showing analytics, charts, and campaign metrics",

"environment": "modern desk setup with notebook, coffee, plant, and soft lighting",

"style": "premium SaaS landing page mockup",

"composition": "laptop angled at 3/4 view, screen clearly visible, shallow depth of field",

"lighting": "soft daylight from side window",

"mood": "productive, modern, credible",

"negative_prompt": "no unreadable messy UI, no random text, no warped device"

}

---

## 12. Mobile App Store Screenshots

**Best format:** JSON

For app launch graphics, app store previews and feature screens.

{

"image_type": "mobile app promotional screenshot",

"aspect_ratio": "9:16",

"app_category": "[fitness / recipe / finance / beauty / productivity]",

"device": "modern smartphone mockup",

"screen_design": {

"style": "clean modern UI",

"main_screen": "[describe screen: dashboard, recipe result, workout tracker, booking page]",

"colors": "[brand colors]",

"ui_elements": ["cards", "buttons", "icons", "progress indicators"]

},

"background": "soft gradient with subtle abstract shapes",

"text_overlay": {

"headline": "[MAIN BENEFIT]",

"subheadline": "[SUPPORTING BENEFIT]"

},

"composition": "phone centered, headline above, supporting elements around phone",

"mood": "polished, app-store-ready, premium",

"negative_prompt": "no unreadable tiny text, no fake app store badges, no distorted phone frame"

}

---

## 13. Agency Ad Creative Concept

**Best format:** JSON

For paid social creatives and service marketing assets.

{

"image_type": "paid social ad creative",

"aspect_ratio": "4:5",

"brand_category": "[DTC beauty / wellness / SaaS / coaching / real estate]",

"campaign_goal": "[awareness / lead generation / conversion / retargeting]",

"target_audience": "[describe audience]",

"main_message": "[primary value proposition]",

"visual_concept": "A bold problem-solution ad visual with product/service as the hero",

"layout": {

"headline": "[AD HEADLINE]",

"subheadline": "[SUPPORTING LINE]",

"cta": "[CTA TEXT]",

"visual_hierarchy": "headline first, product second, CTA third"

},

"style": "high-converting Meta ad, clean, premium, scroll-stopping",

"colors": "[brand colors]",

"mood": "direct, credible, persuasive",

"negative_prompt": "no clutter, no extra text, no unreadable typography, no fake logos"

}

---

## 14. Ad Creative Variation Generator

**Best format:** JSON

Use this to produce multiple controlled ad concepts for one product.

{

"task": "Create 4 different ad creative concepts for the same product",

"product": "[PRODUCT NAME]",

"audience": "[TARGET AUDIENCE]",

"platform": "Meta ads",

"aspect_ratio": "4:5",

"variations": [

{"angle": "Problem-aware", "headline": "[PAIN POINT HEADLINE]", "visual": "show the frustrating before-state clearly"},

{"angle": "Benefit-led", "headline": "[MAIN BENEFIT HEADLINE]", "visual": "show the desired after-state"},

{"angle": "Social proof", "headline": "[REVIEW / RESULT BASED HEADLINE]", "visual": "show testimonial-style layout"},

{"angle": "Offer-led", "headline": "[OFFER HEADLINE]", "visual": "show product bundle, bonus, or limited-time offer"}

],

"style": "premium DTC performance creative",

"design_rules": "high contrast, clean hierarchy, mobile-readable text, realistic product rendering",

"negative_prompt": "no unrealistic claims, no tiny text, no messy collage"

}

---

## 15. Real Estate Website Hero Image

**Best format:** Natural language

For landing pages, property ads and real-estate websites.

Create a premium hero image for a real estate landing page. Show a luxury modern home exterior at golden hour with warm interior lights glowing through large glass windows. The architecture should feel high-end, clean, and aspirational.

Composition should have enough negative space on the left side for website headline text. Include a subtle driveway, landscaped garden, and cinematic lighting. Style: realistic architectural photography, premium real estate campaign, elegant, trustworthy, high-converting. Aspect ratio 16:9, no text.

---

## 16. Cafe / Restaurant Brand Visual

**Best format:** Natural language

For cafe websites, restaurant social media and food brand campaigns.

Create a premium cafe brand campaign image showing a beautifully styled table with iced matcha, coffee, croissants, ceramic cups, flowers, and a softly blurred cafe interior in the background.

The visual should feel warm, aesthetic, Instagrammable, and high-end. Use natural window light, soft shadows, creamy neutral tones, and editorial food photography composition. Camera angle: slightly top-down 45-degree angle. Aspect ratio 4:5. No text.

---

## 17. Product Packaging Concept

**Best format:** JSON

For packaging explorations and brand concept presentations.

{

"image_type": "product packaging concept",

"aspect_ratio": "1:1",

"product_category": "[coffee / skincare / supplement / perfume / snack / wellness drink]",

"brand_name": "[BRAND NAME]",

"packaging_type": "[box / pouch / bottle / jar / tube]",

"design_style": "minimal premium packaging with strong shelf presence",

"color_palette": "[primary, secondary, accent colors]",

"label_details": {

"front_text": "[PRODUCT NAME]",

"supporting_text": "[SHORT BENEFIT LINE]",

"visual_motif": "[ingredient / pattern / symbol / abstract graphic]"

},

"scene": "packaging standing on a clean studio surface with subtle props",

"lighting": "soft studio lighting with realistic shadows",

"mood": "premium, modern, brand-ready",

"negative_prompt": "no misspelled brand name, no cluttered label, no fake certification logos"

}

---

## 18. Beauty Product Flat Lay

**Best format:** Natural language

For skincare, makeup and beauty campaign visuals.

Create a premium beauty product flat lay for [PRODUCT NAME]. Place the product on a smooth marble surface with soft fabric, water droplets, flowers, and subtle ingredient props around it.

The composition should be elegant and balanced, with the product clearly visible as the hero. Lighting should be soft, diffused, and luxurious. Style: high-end skincare campaign, clean editorial product photography, realistic textures. Aspect ratio 4:5, no extra text.

---

## 19. Tech SaaS LinkedIn Ad

**Best format:** JSON

For B2B campaigns, lead gen ads and SaaS launches.

{

"image_type": "LinkedIn ad creative",

"aspect_ratio": "1.91:1",

"industry": "B2B SaaS",

"target_audience": "[founders / marketers / HR teams / finance teams / sales leaders]",

"main_message": "[VALUE PROPOSITION]",

"visual": "a clean SaaS dashboard floating over a modern office background",

"layout": {

"headline": "[HEADLINE]",

"subheadline": "[SUPPORTING LINE]",

"cta": "[CTA]"

},

"style": "clean enterprise design, premium, trustworthy, minimal",

"colors": "[brand colors]",

"composition": "dashboard on right, text on left, strong whitespace",

"negative_prompt": "no random charts, no unreadable UI text, no cluttered corporate stock-photo look"

}

---

## 20. AI Tool Tutorial Thumbnail

**Best format:** JSON

For YouTube thumbnails, reel covers and tutorial hero graphics.

{

"image_type": "YouTube thumbnail",

"aspect_ratio": "16:9",

"topic": "[AI TOOL / WORKFLOW]",

"main_visual": "creator reacting to a futuristic AI interface on a laptop screen",

"headline": "[SHORT HOOK, MAX 5 WORDS]",

"style": "high-retention YouTube thumbnail, bold, clean, dramatic",

"composition": "face on one side, large text on the other, AI interface in background",

"lighting": "cinematic contrast with bright screen glow",

"colors": "black, white, neon accent color",

"mood": "curious, exciting, urgent",

"negative_prompt": "no tiny text, no overcluttered background, no distorted facial expression"

}

---

## 21. E-Commerce Catalog Product Shot

**Best format:** JSON

For marketplace-ready clean product shots.

{

"image_type": "e-commerce catalog image",

"aspect_ratio": "1:1",

"product": "[PRODUCT NAME]",

"background": "pure white or soft light gray",

"angle": "front-facing product shot",

"lighting": "even studio lighting with soft shadow under product",

"style": "clean marketplace-ready product photography",

"requirements": ["product centered", "sharp edges", "accurate proportions", "no props", "no extra text"],

"negative_prompt": "no lifestyle background, no distorted packaging, no reflections covering label"

}

---

## 22. Premium Lifestyle Product Shot

**Best format:** Natural language

For aspirational but believable brand content.

Create a premium lifestyle product photograph for [PRODUCT NAME]. Show the product being used naturally by [TARGET CUSTOMER] in [LOCATION].

The scene should feel aspirational but believable. Include subtle props that support the product use case. Lighting should be natural and flattering. The product must be clearly visible and look realistic.

Style: modern DTC lifestyle campaign, editorial photography, soft depth of field, premium composition. Aspect ratio 4:5, no text.

---

## 23. Fitness Brand Campaign Image

**Best format:** Natural language

For activewear, fitness apps, gyms and wellness brands.

Create a powerful fitness brand campaign image showing an athletic woman wearing [OUTFIT / ACTIVEWEAR] in a modern gym. She is mid-workout, holding a confident strong pose, with realistic sweat, natural muscle tone, and focused expression.

The background should include premium gym equipment, dramatic side lighting, and a slightly cinematic atmosphere. Mood: disciplined, strong, high-performance, aspirational. Composition: vertical 9:16, full-body or three-quarter shot, no text.

---

## 24. Jewellery Product Photography

**Best format:** Natural language

For luxury accessories, jewellery launches and product pages.

Create a luxury jewellery product photograph of [JEWELLERY ITEM] placed on soft silk fabric with subtle warm highlights. The jewellery should look premium, detailed, reflective, and elegant.

Use macro photography style with shallow depth of field, realistic metal reflections, gemstone sparkle, and soft shadows. Background should be minimal and luxurious. Mood: timeless, expensive, refined. Aspect ratio 1:1, no text.

---

## 25. Restaurant Food Delivery Ad

**Best format:** JSON

For food campaigns where offer, CTA and dish visibility matter.

{

"image_type": "food delivery ad creative",

"aspect_ratio": "4:5",

"restaurant_type": "[pizza / burger / Indian / cafe / sushi / healthy bowls]",

"main_dish": "[DISH NAME]",

"visual": "delicious close-up of the dish with steam, texture, and fresh ingredients visible",

"background": "warm restaurant table setup",

"text_overlay": {

"headline": "[CRAVING-BASED HEADLINE]",

"offer": "[OFFER, OPTIONAL]",

"cta": "Order Now"

},

"style": "high-converting food ad, rich colors, appetizing, realistic",

"lighting": "warm directional lighting",

"negative_prompt": "no fake-looking food, no messy plate, no unreadable text"

}

---

## 26. Hotel / Travel Campaign Visual

**Best format:** Natural language

For boutique hotels, travel brands, resorts and destination pages.

Create a premium travel campaign image for a boutique hotel in [LOCATION]. Show a beautiful room with large windows opening to [VIEW: mountains/ocean/city/forest], soft bedding, warm lamps, elegant furniture, and a calm luxury atmosphere.

The image should feel like a high-end hospitality campaign: inviting, peaceful, aspirational, and realistic. Use natural morning light, cinematic composition, and subtle editorial styling. Aspect ratio 16:9, no text.

---

## 27. Corporate Team Photo

**Best format:** Natural language

For about pages, company websites and team announcements.

Create a realistic corporate team photo of a modern marketing agency team standing together in a bright office. The group should look diverse, professional, friendly, and confident. Outfits should be smart-casual and polished.

Background: modern workspace with glass walls, plants, laptops, creative boards, and natural daylight. Style: premium company website photography, realistic, warm, credible. Aspect ratio 16:9, no text.

---

## 28. Pitch Deck Cover Visual

**Best format:** JSON

For investor decks, proposals and strategic presentations.

{

"image_type": "pitch deck cover visual",

"aspect_ratio": "16:9",

"company": "[COMPANY NAME]",

"industry": "[INDUSTRY]",

"theme": "[AI automation / healthcare / real estate / fintech / education]",

"visual_metaphor": "[AI brain / connected city / growth engine / digital command center]",

"style": "premium investor deck cover, clean, sophisticated, minimal",

"text_overlay": {

"title": "[DECK TITLE]",

"subtitle": "[SHORT POSITIONING LINE]"

},

"composition": "large visual metaphor in center, title in top left or bottom left",

"colors": "[brand colors]",

"negative_prompt": "no clutter, no stock-photo cliche, no tiny text"

}

---

## 29. Poster / Event Creative

**Best format:** JSON

For webinars, workshops, retreats, launches and conferences.

{

"image_type": "event poster",

"aspect_ratio": "4:5",

"event_name": "[EVENT NAME]",

"event_type": "[webinar / workshop / launch / retreat / conference]",

"theme": "[THEME]",

"main_visual": "[speaker portrait / abstract concept / location / product]",

"text_overlay": {

"headline": "[EVENT TITLE]",

"date": "[DATE]",

"time": "[TIME]",

"location": "[LOCATION OR ONLINE]",

"cta": "[REGISTER NOW / BOOK YOUR SEAT]"

},

"style": "premium modern event poster, high contrast, clean hierarchy",

"colors": "[brand colors]",

"composition": "headline clear at top, visual center, details bottom",

"negative_prompt": "no misspelled text, no extra fake details, no clutter"

}

---

## 30. Website Hero Section Background

**Best format:** Natural language

For SaaS, service websites, creator pages and landing pages.

Create a website hero background image for [BRAND / INDUSTRY]. The image should support the headline but not overpower it.

Visual concept: [describe the product/service/customer/environment]. Keep the left side or center area clean with negative space for website text. Style should be modern, premium, conversion-focused, and realistic.

Use soft gradients, subtle depth, professional lighting, and a polished digital brand aesthetic. Aspect ratio 16:9. No text, no logos.

---

## 31. Founder at Work Candid Shot

**Best format:** Natural language

For founder-led storytelling, LinkedIn posts and about pages.

Create a realistic candid photo of a founder working late in a modern office. The person is sitting at a desk with a laptop, notebook, coffee, and soft screen glow. The mood should feel focused, ambitious, and calm.

Style: documentary editorial photography, cinematic but realistic. Lighting: warm desk lamp mixed with cool laptop glow. Composition: side angle, medium shot, shallow depth of field. Aspect ratio 4:5, no text.

---

## 32. Luxury Perfume Campaign

**Best format:** JSON

For fragrance campaigns and premium product storytelling.

{

"image_type": "luxury perfume campaign",

"aspect_ratio": "4:5",

"product": "[PERFUME NAME]",

"bottle_design": "[describe bottle shape, color, cap, label]",

"scene": "perfume bottle placed on reflective black glass with soft smoke and flowers around it",

"lighting": "dramatic studio lighting with elegant highlights",

"style": "luxury fragrance editorial, cinematic, sensual, premium",

"mood": "mysterious, elegant, expensive",

"composition": "bottle centered, strong shadows, negative space for ad copy",

"negative_prompt": "no unreadable label, no distorted bottle, no clutter"

}

---

## 33. Educational Infographic

**Best format:** JSON

For educational carousel slides, explainers and audience handouts.

{

"image_type": "educational infographic",

"aspect_ratio": "4:5",

"topic": "[TOPIC]",

"audience": "[beginners / marketers / business owners / students]",

"title": "[INFOGRAPHIC TITLE]",

"sections": [

{"heading": "Step 1", "text": "[SHORT POINT]"},

{"heading": "Step 2", "text": "[SHORT POINT]"},

{"heading": "Step 3", "text": "[SHORT POINT]"}

],

"style": "clean educational carousel design, premium, mobile-readable",

"visual_elements": "icons, arrows, simple diagrams, cards",

"colors": "[brand colors]",

"negative_prompt": "no long paragraphs, no tiny text, no random icons, no spelling errors"

}

---

## 34. AI-Generated Ad Creative Audit Visual

**Best format:** JSON

For performance marketing analysis posts and campaign reports.

{

"image_type": "marketing analysis visual",

"aspect_ratio": "4:5",

"concept": "ad creative audit dashboard",

"main_visual": "three ad creatives displayed side by side with performance labels like Hook Rate, CTR, CPA, and Winner",

"style": "premium performance marketing dashboard aesthetic",

"background": "dark clean interface with subtle grid",

"text_overlay": {

"headline": "Which Creative Won?",

"subheadline": "Hook rate changed everything"

},

"mood": "analytical, sharp, performance-driven",

"composition": "clear hierarchy, ad previews in center, metrics underneath",

"negative_prompt": "no unreadable tiny numbers, no random platform logos, no clutter"

}

---

## 35. Model Face + Outfit Reference Prompt

**Best format:** Natural language

For uploaded reference images where identity consistency matters.

Using the uploaded person as the face and identity reference, create a realistic fashion photoshoot image. Keep the facial features, face shape, skin tone, and overall identity consistent.

Change only the styling, outfit, setting, pose, and lighting.

Outfit: [DESCRIBE OUTFIT].

Location: [DESCRIBE LOCATION].

Pose: [DESCRIBE POSE].

Style: premium editorial fashion photography.

Lighting: [DESCRIBE LIGHTING].

Composition: [close-up / waist-up / full-body], [aspect ratio].

Do not change the person's facial identity. Keep the result natural, realistic, and well-blended.

---

## 36. Product Held by Model

**Best format:** Natural language

For UGC, creator ads and product close-up storytelling.

Create a realistic product lifestyle photo of a model holding [PRODUCT NAME] close to the camera. The product should be sharp, clear, and readable, while the model and background are softly blurred.

The model should look natural, friendly, and aspirational. Setting: [bathroom / kitchen / gym / office / outdoor cafe]. Lighting: soft natural daylight. Style: premium UGC meets DTC ad photography. Aspect ratio 4:5, no extra text.

---

## 37. Agency Portfolio Mockup

**Best format:** JSON

For agency websites, case study pages and pitch decks.

{

"image_type": "agency portfolio case study mockup",

"aspect_ratio": "16:9",

"agency_type": "creative performance marketing agency",

"main_visual": "a clean spread of ad creatives, landing page mockups, social posts, and analytics dashboard",

"style": "premium case study presentation, modern, polished",

"layout": "collage grid with depth, shadows, and device mockups",

"background": "soft off-white or dark premium gradient",

"text_overlay": {

"headline": "Creative Testing System",

"subheadline": "From angles to winning ads"

},

"mood": "strategic, high-value, agency-grade",

"negative_prompt": "no messy layout, no unreadable text, no random logos"

}

---

## 38. Brand Moodboard

**Best format:** JSON

For creative direction, client presentations and brand strategy.

{

"image_type": "brand moodboard",

"aspect_ratio": "16:9",

"brand_category": "[beauty / tech / wellness / fashion / cafe / real estate]",

"brand_personality": "[premium / playful / minimal / bold / earthy / futuristic]",

"elements": ["color palette swatches", "typography samples", "product photography style", "texture references", "lifestyle imagery", "logo placeholder", "social media mockups"],

"style": "clean creative direction board, premium agency presentation",

"composition": "organized grid with elegant spacing",

"colors": "[brand colors]",

"negative_prompt": "no clutter, no illegible tiny text, no unrelated images"

}

---

## 39. Brand Mascot / Character

**Best format:** JSON

For app onboarding, brand stickers, websites and playful campaigns.

{

"image_type": "brand mascot concept",

"aspect_ratio": "1:1",

"brand": "[BRAND NAME]",

"mascot_type": "[animal / robot / object / human-like character]",

"personality": "[friendly / smart / playful / premium / quirky]",

"visual_style": "clean modern 3D character or flat vector illustration",

"pose": "welcoming pose, slight smile, expressive but not childish",

"colors": "[brand colors]",

"background": "simple clean background",

"usage": "website, social media, stickers, onboarding screens",

"negative_prompt": "no scary expression, no overly complex details, no copyrighted character resemblance"

}

---

## 40. Print-Ready Flyer

**Best format:** JSON

For local businesses, events, lead generation and offline promotions.

{

"image_type": "print flyer",

"aspect_ratio": "A4 vertical",

"business": "[BUSINESS NAME]",

"offer": "[MAIN OFFER]",

"audience": "[TARGET AUDIENCE]",

"text_overlay": {

"headline": "[MAIN HEADLINE]",

"subheadline": "[SUPPORTING LINE]",

"bullets": ["[BENEFIT 1]", "[BENEFIT 2]", "[BENEFIT 3]"],

"cta": "[CALL TO ACTION]",

"contact": "[PHONE / WEBSITE / QR PLACEHOLDER]"

},

"style": "premium clean flyer design, professional, high-converting",

"colors": "[brand colors]",

"layout": "clear hierarchy, large headline, visual hero, benefits, CTA at bottom",

"negative_prompt": "no spelling errors, no clutter, no tiny unreadable text"

}

---

# Best Add-On Lines to Improve Almost Any Prompt

## For realism

Make it look like a real photograph, with natural skin texture, realistic proportions, believable lighting, and no AI-generated plastic effect.

---

## For luxury

The final image should feel premium, refined, editorial, and expensive, with careful attention to texture, lighting, negative space, and composition.

---

## For ads

Design it like a high-performing paid social creative with clear visual hierarchy, mobile readability, strong contrast, and immediate message clarity.

---

## For product accuracy

Keep the product shape, label placement, proportions, material, and packaging structure consistent and realistic.

---

## For model identity consistency

Preserve the person’s facial identity, face shape, skin tone, and natural expression. Do not change their core facial features.

---

## For text-heavy visuals

Use clean, large, correctly spelled text. Avoid extra words. Keep the typography mobile-readable with strong spacing and hierarchy.

---

# Final Recommendation

Use natural prompts for creator photos, model shots, outfit photography, UGC images, lifestyle visuals and face-consistent edits.

Use JSON prompts for ad creatives, product mockups, posters, carousel covers, pitch deck covers, app screenshots, brand moodboards, packaging and agency portfolio visuals.

The strongest outputs usually come from clear creative direction, specific composition, controlled lighting, platform size and negative constraints - not from overly poetic prompts.
