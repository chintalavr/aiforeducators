# Lab: Iteratively Engineering a Prompt for lesson planning

**Objective:** Iterate the prompt refinement workflow to achieve a high-quality prompt for effective lesson planning.
Let's practice using prompts
Each version builds in complexity and clarity, with a focus on lesson design, NGSS alignment, and instructional strategy appropriate for 9th grade Earth science.

🔹 Prompt 1: Idea Generation (Open-Ended)

Prompt: You are an expert 9th grade science teacher. Come up with 3 lesson ideas for a unit on Earth science. The lessons should build on each other and focus on topics like plate tectonics, earthquakes, volcanoes, cyclones, tsunamis, floods, landslides, and topography. Each lesson should be 40 minutes long and appropriate for 9th grade students.

💡 Purpose of Prompt 1: Establish a creative baseline. This prompt is intentionally broad, encouraging general idea generation without requiring a detailed structure.

🔹 Prompt 2: Add Instructional Components

Prompt: You are an expert 9th grade science teacher. Create 3 connected lesson plans for a 9th grade Earth science unit. Each lesson should be 40 minutes long and focus on one or more of the following: plate tectonics, earthquakes, volcanoes, cyclones, tsunamis, floods, landslides, and topography. Each lesson plan should include:

A specific topic focus

Learning objectives

A list of key vocabulary

A short outline that includes direct instruction, an engaging activity, and a closure or summary of learning

💡 Purpose of Prompt 2: Adds essential structure for lesson planning. Still flexible, but pushes the AI to think in terms of lesson flow and learning targets.

🔹 Prompt 3: Include NGSS Standards & Assessment

Prompt: You are an expert 9th grade science teacher. Develop 3 sequential, 40-minute Earth science lesson plans that align with NGSS high school standards. Topics should include plate tectonics, earthquakes, volcanoes, cyclones, tsunamis, floods, landslides, and topography. Each lesson must include:

NGSS performance expectations or standard codes

Clear learning objectives

Key vocabulary

A lesson outline with:

Brief direct instruction

A hands-on or inquiry-based activity

A closure that summarizes student learning

A method for assessing student understanding (formative or summative)

💡 Purpose of Prompt 3: Introduces rigor and accountability by requiring standards alignment and assessment, moving the AI closer to producing instructionally sound materials.

🔹 Prompt 4: Emphasize Cohesion, Purpose, and Reflection

Prompt: You are an expert 9th grade science teacher. Design 3 sequential Earth science lesson plans, each 40 minutes long, for a unit focused on topics such as plate tectonics, earthquakes, volcanoes, cyclones, tsunamis, floods, landslides, and topography. Lessons must build upon one another to develop a comprehensive understanding of Earth’s dynamic systems. Each lesson should:

Align to specific NGSS high school standards (e.g., HS-ESS2-1, HS-ESS3-1)

Include clear and measurable learning objectives

Target essential academic vocabulary

Provide a lesson structure with:

Brief direct instruction (max 10 minutes)

A student-centered, engaging activity (hands-on, simulation, data analysis, etc.)

A closure that includes reflection, synthesis, or real-world application

Include a formative or summative assessment Also explain how each lesson connects to the previous one and contributes to the overall goals of the unit.

💡 Purpose of Prompt 4: This is the final, fully enhanced prompt—clear, rigorous, and instructionally rich. It asks for cohesion across lessons, depth of student engagement, and real-world relevance while staying aligned to standards.

🧪 How to Use These Prompts in a Lab Exercise: Round Prompt Focus Activity 1 Prompt 1 Creative Idea Generation Compare the variety of topics suggested. Identify missing structure. 2 Prompt 2 Structured Lesson Components Evaluate the presence of objectives, vocabulary, flow. What’s still missing? 3 Prompt 3 Standards & Assessment Discuss the role of standards and assessment. Are the lessons now usable? 4 Prompt 4 Cohesion & Purpose Examine how lessons build on each other. Discuss how clarity improves with each iteration.


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
