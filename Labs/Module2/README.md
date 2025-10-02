# Lab: Iteratively Engineering a Prompt for lesson planning

**Objective:** Iterate the prompt refinement workflow to achieve a high-quality prompt for effective lesson planning.

## Step 1: Baseline Prompt (naive)
**Prompt v1:**
```text
Create 6th grade earth science lessons.
```

**Issue:** Missing scope (which concepts), number of lessons, structure, standards, engagement.

## Step 2: Define Scope + Lesson Sequencing
Prompt v2:
```text
Create 3 sequential 45-minute 6th grade earth science lesson ideas on plate tectonics, earthquakes, volcanoes, tsunamis, floods, landslides, and topography.
Improvement: Specifies count, duration, thematic set, progression requirement.
Gap: No standards, structure, assessment.
```

## Step 3: Add Standards + Required Components
**Prompt v3:**

```text
Create 3 sequential 45-minute 6th grade earth science lessons (topics above) each with NGSS alignment, learning objectives, key vocabulary, outline (direct instruction, activity, closure), and an assessment.
```

**Improvement**: Adds alignment and core pedagogical skeleton.

**Gap:** Still vague on quality of objectives, engagement, coherence.

## Step 4: Elevate Quality + Clarity
Prompt v4: 
```text
... Ensure objectives are measurable (student can + action + concept), vocabulary defined student-friendly, activity is hands-on or simulation-based, closure synthesizes learning, assessment checks objectives, and lessons explicitly build (Foundations → Processes → Impacts/Mitigation).
```

**Improvement:** Ensures rigor, progression, engagement.

**Gap:** Tone + final cohesive framing still needed.

## Step 5: Final Aggregated Prompt (copy/paste)
**Final Prompt:**

```text
You are an expert 6th grade science teacher, proficient in creating engaging, well-developed, and effective lesson plans. Your task: Propose 3 sequential lesson plans (45 minutes each) in a unit on Earth Science. The sequence must build logically (Lesson 1 foundational plate tectonics and topography; Lesson 2 dynamic events: earthquakes, volcanoes; Lesson 3 hazard effects and related phenomena: tsunamis, floods, landslides, mitigation). Each lesson must be appropriate for 6th grade and aligned to relevant NGSS performance expectations (cite codes). For each lesson provide: Title; NGSS Alignment (codes + brief rationale); Learning Objectives (3–4 measurable, student-focused); Key Vocabulary (term + concise student-friendly definition); Lesson Outline with time stamps (Direct Instruction, Engaging Activity, Closure with synthesis); Assessment of Learning (format + answer expectations); Materials/Resources. Use concise, teacher-facing imperative sentences. Ensure activities are interactive (models, mapping, simple simulation, data interpretation) and closures prompt evidence-based explanation. Show how each lesson connects to the next in a brief “Progression Note.” Output in markdown with H2 for each Lesson (Lesson 1, Lesson 2, Lesson 3) and bullet lists under subheadings. Avoid extraneous commentary. End with a short summary recommending which components could be reused for review.
```

End of lab.
