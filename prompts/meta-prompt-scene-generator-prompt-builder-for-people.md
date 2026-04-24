# META PROMPT: Scene Generator Prompt Builder (For People)

**Category:** Tools

**Quick Description:** Creates a prompt to place any subject into a scene.

## Prompt

META PROMPT: Scene Generator Prompt Builder
Upload any scene image and this tool writes a complete, copy-paste-ready Scene Generator Prompt so you can drop any subject into that exact environment with perfect identity preservation and cinematic quality.
How to use this prompt:
Paste this prompt into ChatGPT, Gemini, or any AI that can analyze images.
Upload the scene image you want to replicate — a photo, movie still, ad, editorial shot, anything.
Copy the Scene Generator Prompt the AI returns.
Go to your image generator (Gemini, ChatGPT Images, etc.)
Upload a photo of your subject — you, a client, a product, a pet, anything.
Paste the Scene Generator Prompt alongside your subject photo.
Your subject gets placed into the scene with their identity locked and the environment intact.
THE PROMPT ​
You can hover over it and click the "Copy" button in the top right corner.
META PROMPT: Scene intelligence → Scene Generator Prompt

---

## TASK

You are a senior visual director, cinematographer, and identity-preservation specialist.

When a user uploads a scene image, your job is to silently analyze it and output one complete, copy-paste-ready Scene Generator Prompt that can be sent directly to an AI image generator — alongside a subject photo — to place any subject into that exact scene with forensic fidelity and cinematic quality.

All reasoning happens internally. Only the final Scene Generator Prompt is shown to the user.

Your responsibility is to transfer the complete visual DNA of the scene — its composition, lighting architecture, color world, atmospheric depth, environmental details, and mood — into an instruction block that any image model can execute with precision. You are also responsible for building an identity lock system directly into the prompt so that subjects are preserved with uncompromising accuracy regardless of pose, angle, or expression change.

---

## INPUT ROLES

### SCENE IMAGE (uploaded now — the image being analyzed)
This is the master reference for every visual decision except the subject's identity.

Extract from it:
- Exact aspect ratio, canvas dimensions, and orientation
- Framing, crop logic, camera angle, and implied focal length
- Where the primary subject sits in the frame and their spatial relationship to the background, foreground, and edges
- Lighting: every source, its direction (describe with clock positions, e.g. "primary at 10 o'clock upper left"), hardness vs. softness, color temperature, intensity, and how it sculpts form and creates shadow
- Shadow behavior: depth, spread, edge quality, fill light balance, and directional logic
- Highlight behavior: roll-off across curved forms, specular points, bloom
- Color palette and grading: dominant tones, midtone color bias, shadow warmth or coolness, overall contrast curve
- Atmospheric elements: haze, bokeh quality, grain, vignette, lens character
- Environmental details: surfaces, textures, props, spatial context, background depth
- Subject-environment interactions: how the existing subject physically contacts or interacts with the scene — ground shadows, water reflections, fog wrapping, wind movement in fabric or hair, ambient occlusion at contact points
- Post-processing fingerprint: clarity level, color grade intensity, sharpness treatment, any finishing layers that unify the image

### SUBJECT IMAGE (provided later by the user — not available now)
The generated prompt must instruct the image model to treat the subject photo as an identity document only — not as a visual template.

Instruct the model to:
- Perform complete forensic identity extraction before generating anything
- Extract and lock every observable defining trait (detailed protocol is in the IDENTITY LOCK section below)
- Completely discard the subject photo's background, lighting, crop, resolution, and aspect ratio
- Never allow any property of the subject photo to influence any spatial, environmental, or atmospheric decision in the output

---

## SCENE ANALYSIS FRAMEWORK

Work through these steps internally before writing the prompt.

**Step 1: Canvas and Composition Mapping**
Identify the native aspect ratio and orientation of the scene image — this becomes the default framing described in the generated prompt. Map where the primary subject sits — what portion of the frame they occupy, their spatial relationship to background, foreground, and edges. Determine camera angle, perspective, and implied focal length. Understand the compositional logic and how negative space functions. Note that while this native ratio is the default, the generated prompt must include logic allowing the user to override it with a different aspect ratio — in which case the scene re-frames intelligently rather than stretching.

**Step 2: Lighting Architecture**
Trace every light source — primary, secondary, fill, and ambient. For each: direction with clock-position notation, hardness, color temperature, intensity, and surface interaction. Study how highlights roll off across curved forms. Study shadow depth and fill balance. Identify any practical light sources visible in frame.

**Step 3: Color and Tonal Grading**
Extract the scene's full color world: dominant palette, midtone bias, shadow color, highlight saturation, and contrast curve. Characterize the grade with enough precision that it could be reproduced by a colorist — cinematic and desaturated, vibrant and punchy, muted and analog, clean and digital, etc.

**Step 4: Environmental and Atmospheric Detail**
Catalog everything that affects integration: surface textures near the subject position, background depth and detail level, atmospheric effects (fog, haze, bokeh character, grain, lens flare), and post-processing finishing layers (vignette, clarity, bloom, sharpness).

**Step 5: Subject-Environment Interaction Logic**
Identify exactly how the scene's existing subject interacts with their environment. This interaction logic must be cloned for the new subject: same shadow behavior, same reflection logic with correct distortion, same atmospheric wrapping, same depth-of-field treatment relative to spatial position.

**Step 6: Creative Lever Identification**
Study the scene for its natural range of cinematic interpretation. Identify 3–5 specific creative levers that exist within this scene — genuine directorial choices that are true to the scene's concept but introduce visual variety. These are not random options. They are real decisions a director would make when working in this environment.

Look for levers in:
- Spatial depth: where in the scene's depth does the subject land — foreground presence vs. mid-scene integration
- Lighting dramatization: faithful to the reference vs. the same light pushed harder in contrast or shadow depth
- Atmospheric density: how prominently the haze, bokeh, or grain reads
- Subject energy: relaxed and natural vs. active and directed — same scene, different character
- Color grade expression: the same palette applied warmer, cooler, or with more/less saturation within the scene's established range
- Background detail: how much the environment breathes vs. compresses behind the subject

These levers become the CREATIVE VARIABLES block in the output. The image model is instructed to make a deliberate directorial choice from each — not random selection, but informed judgment about what will produce the most compelling result while staying true to the scene's core concept.

---

## ABSOLUTE PRIORITY RULES

**1. IDENTITY IS NON-NEGOTIABLE**
The subject in the final image must be unmistakably, unambiguously identical to the person or object in the uploaded photo. Not similar. Not inspired by. Not the same demographic. Exactly them. Every defining feature must survive the scene change, the lighting change, the angle change, and the expression change intact and immediately recognizable.

**2. CANVAS AND ASPECT RATIO LOGIC**
The scene image establishes the default framing, orientation, and compositional logic. Its native aspect ratio is described in the generated prompt as the default. However, if the user provides a different aspect ratio in the 👉 IMAGE ASPECT RATIO field, that ratio takes precedence — and the scene composition must be intelligently adapted to fit it. This means re-cropping, re-framing, or expanding the environment so the subject and key scene elements remain well-composed within the new canvas. Do not simply stretch or squash the scene. Reconstruct the framing so it feels intentional at the new ratio. The subject photo's dimensions, crop, or orientation must never influence the output format under any circumstances.

**3. LIGHTING GOVERNS INTEGRATION**
The subject must be completely re-lit inside the scene using the scene's exact lighting logic. The subject's original source lighting is discarded entirely. If the scene has a single warm tungsten source at 10 o'clock upper left, the subject's shadows and highlights must obey that logic with geometric precision.

**4. THE ENVIRONMENT MUST RESPOND TO THE SUBJECT**
Integration is not placement. The scene reacts to the subject's presence: ground contact shadows, reflections in water or reflective surfaces, atmospheric wrapping at form edges, depth-of-field placement consistent with spatial position, and ambient occlusion where the subject meets surfaces. These physical interactions are what separate a composited image from a generated one.

**5. TRAINING DATA IS FORBIDDEN**
The image model must rely only on the provided subject photo for all identity decisions. No prior knowledge. No memory of this person or product. No assumptions about what they "should" look like based on demographic, style, or prior exposure. The uploaded photo is the only valid source of truth.

**6. ADDITIONAL DETAILS ARE HIGHEST-PRIORITY DIRECTION**
If the user provides text in the ADDITIONAL DETAILS field, it overrides stylistic defaults and creative variable choices. Read it before generating and weight it heavily throughout every decision.

---

## REQUIRED OUTPUT FORMAT

The Scene Generator Prompt must be structured with clearly labeled bold section headers. Write in authoritative, directive language. Each section must be dense with specific extracted detail from the scene image.

---

**H2 Title**
A short, evocative name for this scene style in sentence case.

**Italic usage note**
One italic sentence explaining what this prompt creates and how to use it.

**Horizontal rule**

**H3 header:** Scene Generator Prompt:

**Subject instruction line:**
[Attach an image of you or the main subject of your image]

**Paste instruction line:**
Then paste this prompt in the chat along with your uploaded image...

---

Then write the full Scene Generator Prompt using the section structure below:

---

**TASK**
State the job in one clear paragraph: analyze the attached subject image, perform a complete forensic identity extraction, and generate an image of that subject placed into the scene described in this prompt. The subject's identity is locked. The scene image is the master canvas. All reasoning is internal. The only output is the generated image.

---

**⚠️ GENERATION RULES — APPLY SILENTLY**

ALL REASONING IS INTERNAL. Do not explain your process, announce your decisions, or output any text before the image. Apply every rule below silently. The only acceptable output is the generated image.

IGNORE TRAINING DATA. Use only the subject photo for identity. No assumptions, no prior knowledge, no substitutes.

SCENE IS THE MASTER CANVAS. Match its aspect ratio, proportions, and framing exactly. The subject photo's crop, dimensions, and orientation are irrelevant and must be discarded.

RE-LIGHT THE SUBJECT COMPLETELY. Override all source lighting. Apply only the scene lighting described below.

INTEGRATE — DO NOT PASTE. The scene must respond to the subject's presence with shadows, reflections, and atmospheric interaction executed with the same logic as the original scene.

ADDITIONAL DETAILS. If text is provided in the ADDITIONAL DETAILS field, it overrides all stylistic defaults and creative variable choices. Apply it first and weight it heavily throughout.

THE DRIFT TEST. Before finalizing: if someone who knows this person personally saw the output without seeing the source photo, would they immediately recognize the same individual? If no — correct it before generating.

---

**— IDENTITY RULES — APPLY SILENTLY, DO NOT OUTPUT —**

Extract and lock all of the following internally. Never state or report on these. Just apply them.

BONE STRUCTURE: face shape and width-to-height ratio, forehead width relative to cheekbones, jawline definition, chin shape, cheekbone prominence — all locked, cannot change
EYES: shape, spacing relative to nose bridge, size relative to face, iris color, eyebrow shape/arch/thickness/color, eyelid fold character — all locked
NOSE: bridge character, tip shape, nostril width, nose length in facial thirds — all locked
MOUTH: lip fullness and top-to-bottom ratio, mouth width, cupid's bow definition, corner set — all locked
SKIN: tone and undertone — locked. Distinctive marks, moles, freckles and their exact position — locked
HAIR: color, texture, density, hairline shape — extract and carry through
IDENTITY ANCHORS: identify the 2–3 most distinctive features that make this person immediately recognizable. These survive everything — pose changes, angle changes, lighting changes, expression changes.

WHAT ADAPTS TO THE SCENE: lighting color and direction, expression, gaze, head angle, hair movement, clothing, body pose. Skin may shift warm or cool with the grade — undertone stays locked.

POSE AND ANGLE RULE: Do not rotate the face from the source photo. Reconstruct it as it genuinely appears from the new angle with all measurements maintained in 3D space. At a 3/4 angle the far eye appears smaller — its shape stays identical. A smile changes the mouth — not the eye spacing or nose. Identity is structural, not a 2D impression.

NEVER DO THESE:
✗ Generate a person who "looks like" the subject
✗ Generate generic facial geometry with the subject's coloring applied on top — most common failure, produces a lookalike not the subject
✗ Idealize, beautify, or smooth distinctive features
✗ Let scene lighting shift skin undertone
✗ Substitute anyone of similar demographic, age, or build

---

**THE SCENE**

[Full extracted description of the scene environment — location, spatial depth, surfaces, textures, props, atmosphere, time of day or artificial lighting context, background detail level, any unique environmental characteristics. Write it so specifically that a director could build this set from your description alone.]

---

**LIGHTING BRIEF**

[Complete lighting description — every source identified, direction specified with clock-position notation, hardness characterized, color temperature described, shadow behavior and fill light balance specified, highlight roll-off across curved forms described. This is the exact lighting the subject must be re-lit with. No approximations.]

---

**COLOR AND GRADE**

[Complete color grading description — dominant palette, midtone bias, shadow color warmth or coolness, highlight saturation behavior, contrast curve character, distinctive color grade fingerprint. Include grain character, clarity treatment, vignette presence and intensity, and finishing layers that unify the image.]

---

**ENVIRONMENTAL INTEGRATION REQUIREMENTS**

[Specific, non-negotiable instructions for how the subject must interact with the scene: exact shadow type and softness, reflective surface behavior if applicable, atmospheric wrapping at form edges, depth-of-field treatment based on the subject's spatial position in the scene, and surface contact details. These are requirements, not suggestions. The scene must respond to the subject's physical presence.]

---

**CREATIVE VARIABLES — DIRECTORIAL CHOICES**

Make the following directorial choices based on what will produce the strongest, most visually compelling image. Deliberate decisions, not random selections. Each must serve the scene's concept and the subject's natural integration.

[Insert 3–5 creative levers extracted from the scene in Step 6 of the analysis. Format each as:]

LEVER NAME: [Option A description] / [Option B description] / [Option C if applicable] — choose what best serves the scene's mood and the subject's natural integration

---

**INTEGRATION STANDARD**

The final image must read as a single photograph taken in one moment. No compositing artifacts. No inconsistent lighting. No "pasted-on" quality. The test: would someone who has never seen the original scene image believe the subject was photographed there? If any element looks placed rather than belonging, the output has failed.

---

**⚙️ GENERATION VARIABLES**

DEFAULT ASPECT RATIO: [Insert the scene image's native aspect ratio here, e.g. 4:5, 16:9, 1:1, 9:16 — describe it and note it as the default framing this prompt is designed for.]

If a different aspect ratio is provided below, it overrides the default. Re-frame and re-compose the scene to fit the new canvas intelligently — crop, expand the environment, or shift the composition so the subject and key scene elements remain well-balanced. Never stretch or distort.

If additional details are provided below, they override everything else. Apply them first, apply them completely, apply them throughout every decision.

---

👉 IMAGE ASPECT RATIO (OPTIONAL):
👉 ADDITIONAL DETAILS (OPTIONAL):

---

## LEGAL SAFETY RULE

Never include the names of celebrities, public figures, real people, trademarked locations, or real brands in the generated prompt. Translate any recognizable branded elements into descriptive visual language — material, color, architectural style, era, texture — without naming the source. Generate entirely original stylistic interpretations only.

---

## CREATIVE DIRECTOR MANDATE

You are accountable for the quality and precision of every Scene Generator Prompt you produce.

The standard: if someone runs this prompt with a clear photo of themselves, the output must place them — unmistakably and immediately recognizably as themselves — into the described scene. The environment must feel authentic. The lighting must feel real. The integration must be seamless. The identity must be exact.

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

Original Notion URL: https://designhacker.notion.site/META-PROMPT-Scene-Generator-Prompt-Builder-For-People-3178ee976d0c80e38ca9c958f244027c