# Template Review

Use this file when you want to create the same spaced repetition review format for future days.

## Reusable Prompt

Copy this prompt and replace the bracketed parts:

```text
Create a spaced repetition review Markdown file for [DAY NUMBER] based on [TOPIC / NOTEBOOK / LESSON CONTENT].

Use the same format as my existing review files:

- Add a Review Schedule near the top.
- Add a Scoring Guide using 0 = forgot, 1 = partial, 2 = correct with effort, 3 = easy.
- Add a short Summary in my own learning style.
- Add Core Concepts with concept, why it matters, and example.
- Add a Confidence Checklist with measurable confidence.
- Add one Question To Evaluate Learning with a hidden answer toggle.
- Add Brain Test Questions split into:
  - Recall Questions for facts and definitions.
  - Explain Questions for why/how understanding.
  - Apply With Code for small Python prediction or writing tasks.
- Put every answer inside a Markdown <details><summary>Answer</summary> toggle.
- Under every scored question, add:
  Score: 0/1/2/3
  Last reviewed: YYYY-MM-DD
  Next review: YYYY-MM-DD
  Mistake note:
- Add an Error Log table.
- Add an Interleaving From Older Days section with 3-5 questions from previous days.
- Keep Markdown only. Do not use an external spaced repetition app.
- Use this default review interval: same day, next day, 3 days, 7 days, 14 days, 30 days.

Make the questions practical for testing real understanding, not only memorizing definitions.
```

## File Template

````md
# Day X Review

## Review Schedule

| Field | Value |
|---|---|
| First review | YYYY-MM-DD |
| Last review | YYYY-MM-DD |
| Next review | YYYY-MM-DD |
| Last score | Not scored yet (/TOTAL) |
| Weak topics | Fill after scoring |
| Status | New / Learning / Stable |

Default review intervals: same day, next day, 3 days, 7 days, 14 days, 30 days.

## Scoring Guide

| Score | Meaning |
|---|---|
| 0 | Forgot |
| 1 | Partial |
| 2 | Correct with effort |
| 3 | Easy |

## Summary

Write a short explanation of what this day covered and what you should be able to do after reviewing it.

## Core Concepts

| Concept | Why it matters | Example |
|---|---|---|
| Concept name | Why this concept is useful | Example code or value |

## Confidence Checklist

| Skill | Confidence 0/1/2/3 | Evidence |
|---|---:|---|
| I can explain the main idea. |  |  |
| I can use the idea in code. |  |  |
| I can avoid the common mistake. |  |  |

## Question To Evaluate Learning

Write one bigger question that checks whether you really understand the topic.

<details><summary>Answer</summary>

Write the hidden answer here.

</details>

Score: 0/1/2/3  
Last reviewed: YYYY-MM-DD  
Next review: YYYY-MM-DD  
Mistake note:

## Brain Test Questions

Use these questions without looking at the notebook first.

### Recall Questions

1. Write a fact-based question.
   <details><summary>Answer</summary>

   Write the hidden answer here.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

### Explain Questions

1. Write a why/how question.
   <details><summary>Answer</summary>

   Write the hidden answer here.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

## Apply With Code

1. Predict the output or write a small Python example.

   ```python
   # code here
   ```

   <details><summary>Answer</summary>

   ```python
   # answer here
   ```

   Explain why this is the answer.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

## Error Log

| Date | Question | Mistake | Correct idea |
|---|---|---|---|
| YYYY-MM-DD |  |  |  |

## Interleaving From Older Days

- Day 1:
- Day 2:
- Day 3:
````

## Review Workflow

1. Answer every question before opening the hidden answer.
2. Score each question honestly from 0 to 3.
3. Add weak topics to the Review Schedule.
4. Add mistakes to the Error Log.
5. Set the next review date using the default intervals.
6. Bring old questions into the Interleaving section of future review files.
