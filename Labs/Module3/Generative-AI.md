# Module 3 Lab: Generative AI

## Objective
Learn to iteratively refine an image generation prompt to produce a clear, age‑appropriate book cover illustration.

## Story Summary (Original Content)
Title: Luna and the Lost Star Map  
Summary: Luna, a curious fourth-grade girl who loves stargazing, finds a faded star map in her grandma’s attic. With her friendly robot firefly, Spark, she follows glowing clues through a meadow, a whispering forest, and a hilltop telescope dome to help a dim star return to the sky. She learns persistence and teamwork.

Key Visual Elements
- Main character: Luna (8–10 yrs, curly hair in a ponytail, purple hoodie, denim jeans, bright sneakers, curious expression)
- Companion: Tiny robot firefly (metallic body, soft teal glow)
- Setting: Twilight meadow + faint Milky Way + old brass telescope + one dim star brightening
- Mood: Wonder, adventure, hopeful
- Style: Whimsical, vibrant, clean, suitable for children’s book cover

## Lab Steps

### Step 1: Use Baseline Prompt
Purpose: Quick concept without detail.  
Prompt 1: A girl and a glowing firefly in a field at twilight.

Observe: Likely generic, missing story identity.

### Step 2: Add Core Subjects + Setting
Prompt 2: Curious fourth-grade girl with a small glowing robot firefly companion standing in a twilight meadow under a starry sky.

Improvement: Age context + companion + environment.

### Step 3: Add Action + Focal Object
Prompt 3: Curious fourth-grade girl examining an old rolled star map beside a small glowing robot firefly in a twilight meadow under a starry sky.

Now story object (map) introduced.

### Step 4: Add Composition + Lighting + Mood
Prompt 4: Whimsical children’s book cover illustration, centered girl kneeling and unrolling a faded star map that glows faintly, small teal-glowing robot firefly hovering at her shoulder, twilight meadow with soft firefly lights, emerging stars, gentle rim light, hopeful mood.

Adds mood and layout.

### Step 5: Add Character Styling + Color Palette
Prompt 5: Whimsical children’s book cover illustration, Luna (brown curly ponytail, purple hoodie, denim jeans, bright sneakers) kneeling, unrolling a faded glowing star map; small teal-glowing metallic robot firefly Spark hovering; twilight meadow with tall soft grasses; early stars and faint Milky Way; warm-purple to deep-indigo sky gradient; hopeful adventurous mood.

Adds specific look.

### Step 6: Add Secondary Prop + Depth + Telescope
Prompt 6: Whimsical vibrant children’s book cover illustration, Luna (brown curly ponytail, purple hoodie, denim jeans, bright sneakers) unrolling a softly glowing faded star map; tiny teal-glowing metallic robot firefly Spark hovering; old brass telescope on tripod in background near a low hill; twilight meadow, soft depth of field, faint Milky Way and one dim star starting to brighten; warm inviting lighting, sense of wonder.

Adds telescope and depth.

### Step 7: Refine for Clean Output + Negative Guidance
Prompt 7 (Refined): Whimsical vibrant children’s book cover illustration, clean linework, Luna (8–10 year-old girl, brown curly ponytail, purple hoodie, denim jeans, bright sneakers) kneeling in a twilight meadow unrolling a softly glowing faded star map; tiny teal-glowing metallic robot firefly Spark hovering near her shoulder; old brass telescope on tripod behind her; faint Milky Way arc and a single dim star beginning to brighten; warm rim light, soft luminous firefly particles, hopeful adventurous mood, centered composition, space above for title.  
Negative (if model supports): no text, no watermark, no extra characters, no distortion, no realism, no dark horror tone.

### Step 8: Style Variant Experiments (Choose One)
Variant A (Painterly): soft painterly gouache texture, gentle brush strokes.  
Variant B (Flat vector): crisp flat vector shapes, bold simple color blocks.  
Variant C (Watercolor): light watercolor wash, subtle gradients, paper texture.  

Add to prompt 7 as desired.

### Step 9: Aspect Ratio + Output Parameters (Example)
- Aspect: 3:4 (portrait) or 2:3 (book cover mock)
- Guidance/CFG: moderate (e.g., 7–9) for balance
- Steps: standard (e.g., 25–35) depending on model
- Seed: Save seed for reproducibility

Example Full Prompt (Consolidated):
Whimsical vibrant children’s book cover illustration, clean linework, soft painterly gouache texture, Luna (8–10 year-old girl, brown curly ponytail, purple hoodie, denim jeans, bright sneakers) kneeling in a twilight meadow unrolling a softly glowing faded star map; tiny teal-glowing metallic robot firefly Spark hovering near her shoulder; old brass telescope on tripod behind her; faint Milky Way arc and a single dim star beginning to brighten; warm rim light, soft luminous firefly particles, hopeful adventurous mood, centered composition, space above for title.  
Negative: no text, no watermark, no extra characters, no distortion, no realism, no dark horror tone.  
Aspect ratio: 3:4.

### Step 10: Evaluate Outputs
Checklist:
- Luna clearly child, friendly and age-appropriate
- Map glows subtly (not overpowering)
- Firefly robot readable (not generic insect)
- Telescope present but not dominant
- Space for title free of clutter
- Mood = hopeful wonder (not dark)

If issues appear:
- Character too old: add youthful round face, child proportions.
- Map too bright: reduce glow, soft subtle light.
- Missing telescope: specify "visible old brass telescope on tripod to the left/right".
- Sky too busy: specify sparse stars.

### Step 11: Iterative Tweaks Examples
Problem: Firefly looks like real insect.  
Add: tiny metallic robot firefly with segmented chrome body and soft teal LED glow.  
Problem: Colors dull.  
Add: vibrant harmonious color palette, gentle complementary purples and teals.  
Problem: Cluttered foreground.  
Add: minimal foreground, clear open space around main subjects.

### Step 12: (Optional) Add Safe Variation Seeds
Generate 3–5 seeds, record: seed, prompt version, any changes.

Seed Log Template:
- Seed 10342 / Prompt 7A / Notes: Firefly shape unclear.
- Seed 10343 / Prompt 7A + metallic detail / Notes: Accept.
- Seed 10344 / Prompt 7C (watercolor) / Notes: Colors soft, keep.

## Student Tasks
1. Run Prompt 1 and save output.  
2. Progress through prompts 2–7; compare differences.  
3. Choose a style variant (A/B/C).  
4. Produce final cover image with consolidated prompt.  
5. Complete evaluation checklist and log adjustments.  
6. Submit: final prompt, final image, iteration log (3+ versions), short reflection (3 sentences max).

## Reflection Guide (Answer Briefly)
- Which refinement step made the biggest quality jump?  
- What single descriptor most improved clarity?  
- How did negative prompting help?

## Deliverables
- Final prompt text
- Image file(s)
- Iteration log (table or list)
- Reflection answers

End of lab.
