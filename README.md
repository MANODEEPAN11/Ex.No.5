# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

## AI Tool Used

- **ChatGPT**
- Generative AI / Large Language Model (LLM)

## Prompting Method: Chain of Prompt

This experiment follows:

**Prompt 1 → Output 1 → Prompt 2 using the previous output → Output 2 → Comparison**

The second prompt does not start from zero. It uses the previous response as context and asks the AI to improve, expand, restructure, or refine it.

---

# Scenario 1: Creative Story

### Prompt 1
> Write a story about a robot.

### Output 1

<img width="1200" height="500" alt="01_creative_story_prompt1_output (1)" src="https://github.com/user-attachments/assets/08e7347f-6221-473b-8fd9-922128735105" />


### Prompt 2 — Chain/Refinement
> Using the previous response, improve the story into a 200-word story for college students. Add a clear engineering problem, conflict, solution, and positive ending. Use simple English.

### Output 2

<img width="1200" height="641" alt="01_creative_story_prompt2_output" src="https://github.com/user-attachments/assets/e814ffd2-5bd8-4c00-b868-a816f0eb442d" />


**Observation:** The second output is more focused because the previous response is refined with specific requirements.

---

# Scenario 2: Factual Explanation

### Prompt 1
> Explain Artificial Intelligence.

### Output 1

<img width="1200" height="500" alt="02_ai_explanation_prompt1_output" src="https://github.com/user-attachments/assets/c42398dc-3846-4be8-83b9-b7f2e9b6e3ee" />


### Prompt 2 — Chain/Refinement
> Using the previous response, rewrite it for a beginner. Include a definition, five applications, three advantages, three limitations, and two real-world examples. Use headings and bullet points.

### Output 2

<img width="1200" height="1145" alt="02_ai_explanation_prompt2_output" src="https://github.com/user-attachments/assets/cf24bc4c-82f5-4b32-bc9e-4cd76da7f3f6" />


**Observation:** The second output is more complete, structured, and beginner-friendly.

---

# Scenario 3: Summarization

### Prompt 1
> Summarize cloud computing.

### Output 1

<img width="1200" height="500" alt="03_summarization_prompt1_output" src="https://github.com/user-attachments/assets/5721bec1-e328-4022-b550-22c97811448f" />


### Prompt 2 — Chain/Refinement
> Using the previous response, create a concise summary for an engineering student. Include service models, deployment models, advantages, disadvantages, and one real-world example. Keep it around 150 words.

### Output 2

<img width="1200" height="1073" alt="03_summarization_prompt2_output" src="https://github.com/user-attachments/assets/1b7b9cc7-a49f-4944-98cd-cc3089e89256" />


**Observation:** The chain prompt adds specific topics, audience, and length, producing a more useful summary.

---

# Scenario 4: Interview Preparation

### Prompt 1
> How should I prepare for an interview?

### Output 1

<img width="1200" height="500" alt="04_interview_plan_prompt1_output" src="https://github.com/user-attachments/assets/e0914323-d9d0-4d1e-a21d-8b05e03e1504" />


### Prompt 2 — Chain/Refinement
> Using the previous response, create a practical 7-day interview preparation plan for a final-year ECE student applying for a technical job. Include core electronics, programming, aptitude, communication, resume preparation, HR questions, and mock interviews.

### Output 2

<img width="1200" height="679" alt="04_interview_plan_prompt2_output" src="https://github.com/user-attachments/assets/bae72dad-2872-435a-9343-ecddeec03f01" />


**Observation:** The second output converts general advice into a specific and actionable plan.

---

# Scenario 5: Technical Explanation

### Prompt 1
> Explain MOSFET.

### Output 1

<img width="1200" height="500" alt="05_technical_explanation_prompt1_output" src="https://github.com/user-attachments/assets/40f25099-9ffe-4a5c-8f36-7d52ce36d86d" />


### Prompt 2 — Chain/Refinement
> Using the previous response, explain MOSFET for a beginner ECE student. Include construction, terminals, working principle, threshold voltage, cutoff, triode and saturation regions, advantages, and applications. Use simple English.

### Output 2

<img width="1200" height="1145" alt="05_technical_explanation_prompt2_output" src="https://github.com/user-attachments/assets/2172f1c1-0c87-48fb-a4e2-a71983daf0a1" />


**Observation:** The second output provides a deeper and more systematic technical explanation.

---

# Comparative Analysis

| Scenario | Initial Prompt | Chain/Refinement Prompt | Improvement |
|---|---|---|---|
| Creative Story | General story | Added structure, audience, length | High |
| AI Explanation | General explanation | Added topics, examples, format | High |
| Summarization | General summary | Added audience, length, topics | High |
| Interview Preparation | General advice | Added user profile and 7-day structure | High |
| MOSFET | General explanation | Added technical concepts and audience | High |

---

# Evaluation

| Parameter | Initial Prompt | Chain/Refined Prompt |
|---|---:|---:|
| Quality | 3/5 | 5/5 |
| Relevance | 3/5 | 5/5 |
| Clarity | 3/5 | 5/5 |
| Completeness | 3/5 | 5/5 |
| Depth | 3/5 | 5/5 |

---
## Summary of Findings:

Initial prompts gave general responses. 

Chain/refinement prompts produced more relevant and detailed outputs.

Adding context, requirements, and format improved response quality.

Simple prompts worked well for simple tasks.

Overall, prompt chaining improved clarity, completeness, and depth.


---

# Result

**The experiment was successfully executed using ChatGPT. The chain-of-prompt method demonstrated that an initial AI response can be progressively improved by using subsequent prompts that add context, requirements, constraints, and output instructions. The refined outputs were generally more relevant, structured, complete, and detailed than the initial outputs.**
