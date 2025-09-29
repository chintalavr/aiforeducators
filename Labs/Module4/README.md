# Lab: Crafting Effective AI Prompts for 7th Grade STEM Assessment Assets

## Goal
Create a single effective prompt that asks an AI model to generate:
- Student-facing project directions
- An aligned analytic rubric (e.g., 4 performance levels)
- Optional extension or differentiation ideas

## Steps

1. Define Learning Targets  
    - List 2–4 standards-aligned objectives (e.g., investigate forces, model energy transfer, explain design choices).  
    - Phrase in student-friendly language (I can…).

2. Specify Assessment Scenario  
    - Describe the real-world STEM task (e.g., design a prototype to solve a classroom problem).  
    - Include required outputs (report, model sketch, data table).

3. List Required Content + Skills  
    - Concepts: variables, fair test, measurement units.  
    - Practices: hypothesis, data collection, iteration, explanation with evidence.

4. Set Constraints and Resources  
    - Time (3 class periods), materials (cardboard, tape, rubber bands), safety notes, collaboration rules.

5. Define Structure of Student Directions  
    - Request: numbered steps, clear verbs, checkpoints, success criteria callout, optional challenge.

6. Design Rubric Dimensions  
    - Choose 4–5 criteria (Understanding of Concept, Planning & Design, Data Quality, Explanation & Evidence, Collaboration).  
    - Performance levels (Exceeds / Meets / Developing / Beginning) with observable descriptors.

7. Specify Prompt Formatting for the AI  
    - Instruct: return Markdown with sections: Overview, Materials, Student Directions, Tips, Rubric (table), Extensions.  
    - Require age-appropriate reading level (Grade 7), concise sentences, no jargon without definition.

8. Assemble the Final Prompt  
    - Combine: objectives, scenario, constraints, criteria, formatting instructions.  
    - Include an explicit instruction: Do not invent unsafe materials; keep reading level ~7th grade.

## Template Prompt (Fill Brackets)

You are an assistant helping a 7th grade STEM teacher create an assessment.  
Learning Targets: [list]  
Scenario: [description]  
Required Student Outputs: [list]  
Materials Available: [list]  
Time: [e.g., 3 class periods]  
Safety / Constraints: [list]  
Rubric Criteria: [list 4–5] with 4 performance levels (Exceeds, Meets, Developing, Beginning).  
Instructions:  
1. Produce Markdown sections: Overview, Materials, Student Directions (numbered), Checkpoints, Rubric (table), Extensions, Differentiation.  
2. Student Directions: 6–10 clear steps; include planning, testing, data recording, reflection.  
3. Rubric: each level has specific, observable descriptors; no vague words like good/bad.  
4. Reading level: Grade 7; define any technical term in parentheses.  
5. Tone: encouraging, clear, actionable.  
6. Do not add materials not listed.  
Return only the Markdown content.

## Quality Check Before Use
- Does each rubric descriptor distinguish levels clearly?  
- Are directions actionable (each starts with a verb)?  
- Are success criteria visible to students?  
- Any ambiguity in materials or time? Revise before sending to AI.

## Optional Extension
After generation, prompt AI to simplify language or translate for multilingual learners.

## Next Action
Fill the template, run the prompt, review output, iterate if criteria lack clarity.
