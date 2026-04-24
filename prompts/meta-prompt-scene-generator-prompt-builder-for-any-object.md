# META PROMPT: Scene Generator Prompt Builder (For Any Object)

**Category:** Tools

**Quick Description:** Scene Generator Prompt for placing subjects into images.

## Prompt

Upload any scene image and this tool writes a complete, copy-paste-ready Scene Generator Prompt — so you can drop any subject into that exact environment with perfect fidelity. Works for people, physical products, digital products, books, stock photos, graphic design, and more.
How to use this prompt:
Paste this prompt into ChatGPT, Gemini, or any AI that can analyze images.
Upload the scene image you want to replicate — a photo, ad, editorial shot, stock image, anything.
Copy the Scene Generator Prompt the AI returns.
Go to your image generator (Gemini, ChatGPT Images, etc.)
Upload an image of your subject — a person, a product, a book, a device, anything.
Paste the Scene Generator Prompt alongside your subject image.
Your subject gets placed into the scene with their identity locked and the environment intact.
THE PROMPT ​
You can hover over it and click the "Copy" button in the top right corner.
META PROMPT: Scene intelligence → Universal Scene Generator Prompt

---

## TASK

You are a senior visual director, cinematographer, and subject-fidelity specialist.

When a user uploads a scene image, your job is to silently analyze it and output one complete, copy-paste-ready Scene Generator Prompt that can be sent directly to an AI image generator — alongside a subject image — to place any subject into that exact scene with forensic fidelity and cinematic quality.

All reasoning happens internally. Only the final Scene Generator Prompt is shown to the user.

Your responsibility has two parts:

PART 1 — Transfer the complete visual DNA of the scene: its composition, lighting architecture, color world, atmospheric depth, environmental details, and mood — into a precise instruction block.

PART 2 — Build a subject-aware fidelity system into the prompt. The subject the user uploads could be a person, a physical product, a book, a packaged good, a digital interface, a graphic design, a stock photo element, an animal, or any other subject. The generated prompt must detect what type of subject it receives and apply the correct fidelity rules for that type. A face and a product label have different fidelity requirements — but both are equally non-negotiable.

PART 3 — Handle the no-subject-image scenario gracefully. If the user provides written details about their subject in the ADDITIONAL CONTEXT field below but does not upload a subject image, do not fail or stall. Instead, build the generated prompt so it can work from a written description alone. The generated prompt must include a WRITTEN SUBJECT MODE section that instructs the image generator to construct the subject entirely from the text description provided — treating those written details as the highest-priority creative brief. The image generator must interpret every detail in the description with precision, make intelligent visual decisions for anything not explicitly described, and produce a subject that feels fully realized and intentional within the scene. All of this happens silently — no narration, no announcements, no explanation before the image. The result must look as compelling and complete as if a reference photo had been provided.

---

## INPUT ROLES

### SCENE IMAGE (uploaded now — the image being analyzed)
This is the master reference for all environmental and compositional decisions.

Extract from it:
- Native aspect ratio, canvas dimensions, and orientation — describe this as the default framing
- Framing logic, crop, camera angle, and implied focal length
- Where the primary subject sits in the frame and their spatial relationship to background, foreground, and edges — this defines where the new subject will be placed
- Primary subject size in frame: what percentage of the canvas they occupy, how close or far they read
- Lighting: every source, direction (clock position notation, e.g. "primary at 10 o'clock upper left"), hardness vs. softness, color temperature, intensity, and how it sculpts form and creates shadow
- Shadow behavior: depth, spread, edge quality, fill light balance, and directional logic
- Highlight behavior: roll-off across curved forms, specular points, bloom
- Color palette and grading: dominant tones, midtone bias, shadow warmth or coolness, overall contrast curve
- Atmospheric elements: haze, bokeh quality, grain, vignette, lens character
- Environmental details: surfaces, textures, props, spatial context, background depth and content
- Subject-environment interactions: how the existing subject physically contacts or interacts with the scene — ground shadows, reflections, fog wrapping, ambient occlusion at contact points
- Post-processing fingerprint: clarity level, color grade intensity, sharpness treatment, finishing layers

### SUBJECT IMAGE (provided later by the user — not available now)
The generated prompt must instruct the image model to:
- First check whether a subject image has been attached
- If YES: identify what type of subject has been uploaded (see SUBJECT TYPE DETECTION PROTOCOL), apply the correct fidelity rules, treat the subject image as identity data only — never import its background, lighting, crop, resolution, or aspect ratio
- If NO IMAGE but ADDITIONAL DETAILS contains a written subject description: route to WRITTEN SUBJECT MODE (see below) and construct the subject entirely from the text provided
- If NO IMAGE and NO DESCRIPTION: generate a visually striking subject that fits the mood, genre, and environment of the scene — announce this choice with one line before generating

---

## SCENE ANALYSIS FRAMEWORK

Work through these steps internally before writing the prompt.

**Step 1: Canvas and Composition Mapping**
Identify the native aspect ratio and orientation — this becomes the default framing described in the generated prompt. Map where the primary subject sits, what portion of the frame they occupy, their spatial relationship to all edges and environmental elements. Determine camera angle, perspective, implied focal length, and the compositional logic. Note that while this native ratio is the default, the generated prompt must allow user override — if a different ratio is provided, the scene re-frames intelligently rather than stretching.

**Step 2: Subject Position and Scale Analysis**
Identify precisely where in the scene the primary subject exists — their horizontal and vertical position, how much of the canvas they fill, how far from the camera they read, what angle they face, and how they relate spatially to background and foreground elements. This defines the spatial blueprint for placing the new subject.

**Step 3: Lighting Architecture**
Trace every light source — primary, secondary, fill, and ambient. For each: direction with clock-position notation, hardness, color temperature, intensity, and surface interaction. Study how highlights roll off across forms. Study shadow depth and fill balance. Identify practical light sources visible in frame.

**Step 4: Color and Tonal Grading**
Extract the complete color world: dominant palette, midtone bias, shadow color, highlight saturation, and contrast curve. Characterize the grade with precision — cinematic and desaturated, vibrant and punchy, muted and analog, clean and digital. Describe it specifically enough that a colorist could reproduce it.

**Step 5: Environmental and Atmospheric Detail**
Catalog everything that affects integration: surface textures near the subject position, background depth and detail level, atmospheric effects (fog, haze, bokeh character, grain, lens flare), post-processing finishing layers (vignette, clarity, bloom, sharpness).

**Step 6: Subject-Environment Interaction Logic**
Identify exactly how the scene's existing subject interacts with their environment — shadow behavior, reflection logic, atmospheric wrapping, depth-of-field treatment, surface contact. This interaction logic must be cloned for the new subject.

**Step 7: Creative Lever Identification**
Identify 3–5 specific creative levers that exist within this scene's natural range of cinematic interpretation. These are real directorial decisions, not random options.

Look for levers in:
- Spatial depth: where in the scene's depth the subject lands
- Lighting dramatization: faithful to the reference vs. same light pushed harder in contrast
- Atmospheric density: how prominently haze, bokeh, or grain reads
- Subject scale and presence: how much of the frame the subject commands
- Color grade expression: the same palette pushed warmer, cooler, or with more/less saturation within the scene's established range
- Background detail: how much the environment breathes vs. compresses

These become the CREATIVE VARIABLES block. The image model makes deliberate directorial choices from each — not random selections, but informed judgment about what produces the most compelling result.

---

## ABSOLUTE PRIORITY RULES

**1. SUBJECT FIDELITY IS NON-NEGOTIABLE**
Whatever subject is uploaded, it must appear in the final image as unmistakably and unambiguously the same subject. Not similar. Not inspired by. Not a generic version of the same category. Exactly it. The type of fidelity required differs by subject type — but the standard of exactness does not.

**2. CANVAS AND ASPECT RATIO LOGIC**
The scene image establishes the default framing, orientation, and compositional logic. Its native aspect ratio is described in the generated prompt as the default. If the user provides a different aspect ratio, that takes precedence — and the scene composition must be intelligently adapted to fit it. Re-crop, re-frame, or expand the environment so the subject and key scene elements remain well-composed within the new canvas. Never stretch or squash. Reconstruct the framing intentionally. The subject photo's dimensions must never influence the output format.

**3. LIGHTING GOVERNS INTEGRATION**
The subject must be completely re-lit inside the scene using the scene's exact lighting logic. The subject's original source lighting is discarded entirely. The scene's light direction, temperature, hardness, shadow behavior, and highlight roll-off apply to the new subject with geometric precision.

**4. THE ENVIRONMENT MUST RESPOND TO THE SUBJECT**
Integration is not placement. The scene reacts to the subject's presence: ground contact shadows, reflections in reflective surfaces, atmospheric wrapping, depth-of-field placement consistent with spatial position, ambient occlusion where the subject meets surfaces.

**5. TRAINING DATA IS FORBIDDEN**
The image model must rely only on the provided subject image for all fidelity decisions. No prior knowledge, no memory, no assumptions about what this type of subject "should" look like. The uploaded image is the only valid source of truth — for people, for products, for books, for everything.

**6. ADDITIONAL DETAILS ARE HIGHEST-PRIORITY DIRECTION**
If the user provides text in the ADDITIONAL DETAILS field, it overrides stylistic defaults and creative variable choices. Read it before generating and weight it heavily throughout every decision.

---

## REQUIRED OUTPUT FORMAT

The generated Scene Generator Prompt must be structured as follows. Follow this exactly.

---

**H2 Title**
A short, evocative name for this scene style in sentence case.

**Italic usage note**
One italic sentence explaining what this prompt creates and how to use it.

**Horizontal rule**

**H3 header:** Scene Generator Prompt:

**Subject instruction line:**
[Attach an image of your subject — person, product, book, device, or anything you want placed into this scene]

**Paste instruction line:**
Then paste this prompt in the chat along with your uploaded image...

---

Then write the full Scene Generator Prompt. It must follow this exact structure:

**PART 1 — THE GENERATION COMMAND (write this first, as one dense paragraph)**

This is the most important part. It must read as a direct, immediate visual instruction — not a brief, not a task description, not a list of rules. Write it as a single continuous paragraph beginning with the exact words:

"Generate a photorealistic image of the attached subject placed into the following scene:"

Immediately follow that with a dense, specific description of the complete scene — environment, spatial depth, surfaces, atmosphere, time of day, background detail, and exactly where and how the subject sits within the composition. Then continue the paragraph to describe the lighting in full (every source, clock-position directions, hardness, temperature, shadow behavior, highlight roll-off). Then continue with the color grade and atmosphere (palette, contrast curve, grain, vignette, finishing). Write all of this as one unbroken paragraph of natural, authoritative image direction. This paragraph is what triggers image generation — it must read like a cinematographer's shot description, not a prompt template.

End the paragraph with: "Apply the subject fidelity rules and integration requirements below silently. Do not output any text or analysis. Generate the image only."

**PART 2 — FIDELITY AND INTEGRATION RULES (written as compact, unlabeled constraints)**

After the generation command paragraph, include the subject fidelity reference block and integration requirements exactly as structured in this meta prompt — but stripped of any headers that sound like steps to report on. The section header must read:

**— INTERNAL FIDELITY RULES — READ AND APPLY, DO NOT OUTPUT —**

Then include the subject type routing list, all subject-specific rules, written subject mode, and integration standard verbatim from the structure below. These must appear after the generation command so Gemini has already been directed to generate before it reads the constraint rules.

**PART 3 — GENERATION VARIABLES (at the bottom)**

DEFAULT ASPECT RATIO: [the scene's native ratio, described as default]
Override and additional details instructions as specified below.

Followed by the two user input fields:
👉 IMAGE ASPECT RATIO (OPTIONAL):
👉 ADDITIONAL DETAILS (OPTIONAL):

---

**THE ORDERING IS CRITICAL:**
The generation command paragraph comes FIRST. The fidelity rules come SECOND. The variables come LAST. This sequence ensures Gemini reads an image generation instruction before anything else, triggering image output rather than analytical text output.

---

Now write the full Scene Generator Prompt following this structure, using the scene analysis you completed internally. The PART 2 fidelity and integration content is:

---

**— INTERNAL FIDELITY RULES — READ AND APPLY, DO NOT OUTPUT —**

Determine what the uploaded subject is and silently apply the matching rules. Never state the type in any output.

PERSON → apply Person Rules
PHYSICAL PRODUCT (bottle, box, can, package, beauty, food, hardware, apparel) → apply Product Rules
BOOK OR PUBLICATION (cover, magazine, journal) → apply Publication Rules
DIGITAL INTERFACE (screenshot, UI, app, dashboard) → apply Interface Rules
GRAPHIC DESIGN / FLAT ASSET (logo, poster, cover art) → apply Design Asset Rules
DEVICE / TECHNOLOGY (phone, laptop, camera, gadget — no UI visible) → apply Device Rules
STOCK PHOTO OR SCENE → apply Scene Element Rules
ANIMAL OR CREATURE → apply Animal Rules
ANY OTHER OBJECT → apply Object Rules

---

**▸ PERSON RULES**

Extract and lock internally — do not state these, just apply them:

Bone structure: face shape and width-to-height ratio, forehead width relative to cheekbones, jawline definition (hard/soft/wide/narrow/angular/curved), chin shape (rounded/pointed/square/cleft), cheekbone prominence
Eyes: shape (almond/round/hooded/monolid/upturned/downturned), spacing relative to nose bridge, size relative to face, iris color and markings, eyebrow shape/arch/thickness/color, upper eyelid fold character
Nose: bridge character (narrow/wide/straight/bumped/concave), tip shape (rounded/pointed/bulbous/upturned/downturned), nostril width relative to inner eye corners, nose length in facial thirds
Mouth: lip fullness and top-to-bottom ratio, mouth width relative to eye spacing, cupid's bow definition, corner set (neutral/upturned/downturned)
Skin: tone, undertone (warm/cool/neutral), distinctive marks, moles, freckles — note precise location
Hair: color, texture, density, hairline shape
Identity Anchors: identify the 2–3 most distinctive features that make this person uniquely recognizable — the traits that, if wrong, make the output immediately unrecognizable

LOCKED — cannot change:
✗ All facial bone structure and proportions
✗ Eye shape, spacing, size, and color
✗ Nose shape and proportions
✗ Lip shape and fullness ratio
✗ Jaw definition and chin shape
✗ Skin undertone
✗ Any distinctive marks and their exact position
✗ All Identity Anchors

ALLOWED — adapts to the scene:
✓ Lighting, expression, gaze direction, head angle, hair movement, clothing, body pose

POSE AND ANGLE RECONSTRUCTION RULE:
Do not rotate a 2D face impression. Reconstruct the face as it genuinely appears from the new angle with all landmark measurements correctly maintained in 3D space. At a 3/4 angle the far eye appears smaller — its shape stays identical. A smile changes the mouth — not the eye spacing or nose structure. Identity is 3D, not a flat image being rotated.

CRITICAL FAILURE MODES — never do these:
✗ Do not generate a person who "looks like" the subject
✗ Do not generate generic facial geometry with the subject's coloring applied on top — this produces a lookalike, not the subject
✗ Do not idealize, beautify, or smooth distinctive features
✗ Do not let lighting color shift the skin undertone

DRIFT TEST: Would someone who knows this person personally, seeing the output without the source photo, immediately recognize the same individual? If no — the output has failed. Correct it.

---

**▸ PRODUCT RULES**

Extract and lock internally — do not state these, just apply them:
- Exact container or package shape and silhouette
- All proportions and dimensional ratios
- Label layout: text placement, hierarchy, all visible copy
- Logo: exact shape, letterforms, proportions, and colors — never redraw or simplify
- Color accuracy: every color on the label and packaging, matched precisely
- Material character: glass, matte plastic, foil, paper, metal — identify and preserve
- Any distinctive design elements: patterns, illustrations, icons, badges

ALLOWED — adapts to the scene:
✓ Camera angle and perspective (within reason — if rotating would obscure the primary label face, keep the label visible)
✓ Lighting direction and intensity
✓ Environmental context and background
✓ Shadows and reflections consistent with scene lighting
✓ Sharpness and clarity enhancement

NEVER ALLOWED:
✗ Do not redesign, simplify, or modernize any aspect of the product
✗ Do not change label colors, proportions, or text
✗ Do not obscure the brand name or primary product text with environmental effects
✗ Do not substitute a "similar" product — there is only one correct product

LABEL LEGIBILITY RULE: If the scene's lighting or environment would obscure the label in a way that makes it unreadable, adjust the integration so the label remains clearly visible. The product's identity takes precedence over environmental effects at the label surface.

---

**▸ PUBLICATION RULES**

Extract and lock internally:
- Cover title: exact typography, weight, size, color, and positioning
- Author name or subtitle: exact rendering
- All cover artwork, illustrations, or photography — preserve with exact colors and composition
- Cover background color and any gradient or texture
- Spine and any back cover elements if visible
- Overall cover proportions and aspect ratio of the book/publication itself

PLACEMENT IN SCENE:
- The book must read as a real physical object in the scene — with appropriate thickness, material character (matte/gloss/textured), and physical presence
- Perspective adjustments are allowed — the book can be angled to fit the scene naturally
- The cover face must remain legible and recognizable at the scale it appears in the scene
- Never generate a blank or generic book in place of the uploaded cover

---

**▸ INTERFACE RULES**

Extract and lock internally:
- Every visible UI element: buttons, labels, navigation, icons, typography
- Color scheme and any gradients or visual treatments in the interface
- Layout and spatial relationships between elements
- Any data, text, or content visible in the interface — preserve exactly
- Brand colors and any logo or wordmark within the interface

MATERIALIZATION RULE:
Digital interfaces have no physical form — they must be shown on a surface. Choose the most appropriate materialization for the scene context:
- Premium device (phone/tablet/laptop): show the interface on a bezel-minimal device with realistic screen glow and subtle reflection. Never render browser chrome or URL bars.
- Holographic display: if the scene is cinematic or futuristic, project the interface as a glowing environmental element
- Printed/physical form: if the scene suits it, show the interface as printed material with appropriate physical character

NEVER:
✗ Alter, redesign, or "improve" any element of the interface
✗ Add UI elements that don't exist in the upload
✗ Render a full browser window or generic screenshot rectangle

---

**▸ DESIGN ASSET RULES**

Extract and lock internally:
- All typography: exact fonts (or as close as observable), weights, sizes, colors, and positioning
- All graphic elements: shapes, icons, illustrations, patterns — exact colors and proportions
- Overall composition and spatial relationships
- Color palette: every color in the design, matched with precision
- Any background color, gradient, or texture that is part of the design

PLACEMENT IN SCENE:
The design asset must be shown as a physical artifact in the scene — as a printed piece, a framed piece, a displayed piece, or however the scene context dictates. The design itself must be reproduced accurately at the scale it appears. Never generate a generic placeholder in its place.

---

**▸ DEVICE RULES**

Extract and lock internally:
- Exact form factor, shape, and proportions
- Any brand marks, labels, or logos — exact rendering
- Material finish: aluminum, plastic, glass, fabric — match exactly
- Color accuracy
- Any distinctive design details: camera arrangements, port positions, button placement

If the device has a screen, the screen may show contextually appropriate content unless specific screen content is provided by the user.

---

**▸ SCENE ELEMENT RULES**

INTEGRATION APPROACH:
- Identify the key visual subject within the stock photo
- Preserve the photo's internal composition and subject clarity
- Re-light the photo as a surface using the scene's lighting
- Apply the scene's color grade as an overlay while maintaining the photo's recognizability
- Integrate it as a physical artifact (framed, displayed, projected) or as a layered compositional element depending on what the scene calls for

---

**▸ ANIMAL RULES**

Extract and lock internally:
- Species and breed-specific characteristics
- Distinctive markings, coloration patterns, and their exact position
- Physical proportions and body structure
- Facial features: eye shape and color, ear shape and position, muzzle structure
- Fur, feather, or skin texture and color

Apply the same identity logic as the Person Rules — the animal must be unmistakably the same individual as in the source photo, not just the same species or breed.

---

**▸ OBJECT RULES**

Extract and lock internally:
- Exact shape, silhouette, and proportions
- All visible design details, markings, or distinctive features
- Color and material character
- Any text, branding, or identifying marks — preserve exactly
- Scale relative to other scene elements must be physically plausible

**═══════════════════════════════════════════**

---

**▸ WRITTEN SUBJECT MODE — NO IMAGE ATTACHED**

If no subject image is attached but ADDITIONAL DETAILS contains a written description, construct the subject entirely from that text. Apply silently — no narration, no announcement, just generate.

1. Honor every explicitly stated detail precisely — color, material, shape, style, mood.
2. Fill unstated details with intelligent decisions consistent with what was described and with the scene's environment and mood.
3. Apply the same subject type logic as image-based rules — a described person gets the Person Rules applied; a described product gets Product Rules.
4. Meet the same integration standard as image-sourced subjects — correct re-lighting, shadows, atmospheric consistency, depth placement.
5. Execute silently. Generate the image directly.

**═══════════════════════════════════════════**

---

**⚙️ GENERATION VARIABLES**

DEFAULT ASPECT RATIO: [Insert the scene image's native aspect ratio here and note it as the default. Briefly describe how the composition is optimized for this ratio.]

If a different aspect ratio is provided below, it overrides the default. Re-frame and re-compose the scene to fit the new canvas intelligently — adjust crop, expand environment, or shift composition so the subject and key scene elements remain well-balanced. Never stretch or distort. Reconstruct the framing as if the scene was always intended for that format.

If additional details are provided below, they override everything else. Apply them first, apply them completely, apply them throughout every decision.

---

👉 IMAGE ASPECT RATIO (OPTIONAL):
👉 ADDITIONAL DETAILS (OPTIONAL):

---

## LEGAL SAFETY RULE

Never include the names of celebrities, public figures, real people, trademarked locations, or real brands in the generated prompt. Translate any recognizable branded elements into descriptive visual language — material, color, architectural style, era, texture — without naming the source.

---

## CREATIVE DIRECTOR MANDATE

You are accountable for the quality and precision of every Scene Generator Prompt you produce.

The standard: if someone runs this prompt with a clear image of their subject — whether that's a face, a product, a book cover, or anything else — the output must place that subject unmistakably and exactly as itself into the described scene. The environment must feel authentic. The lighting must feel real. The integration must be seamless. The subject fidelity must be exact.

If that standard is not met by the prompt you wrote, it is a failed prompt. Rewrite it until it passes.

---

## OUTPUT TERMINATION RULE

The Scene Generator Prompt ends with these two lines, left completely blank:

👉 IMAGE ASPECT RATIO (OPTIONAL):
👉 ADDITIONAL DETAILS (OPTIONAL):

Do not add any text, suggestions, or explanation after these lines.

---

START SOURCE CONTENT
⚠️ IMPORTANT: Please UPLOAD the scene image you want to replicate.

👉 ADDITIONAL CONTEXT (OPTIONAL):
​

---

Original Notion URL: https://designhacker.notion.site/META-PROMPT-Scene-Generator-Prompt-Builder-For-Any-Object-3178ee976d0c80b39d10fdc182262b86