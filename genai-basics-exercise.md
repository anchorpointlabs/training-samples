# GenAI basics: sample exercise: rewriting a client update

## The task

A learner takes a real, slightly messy client update email they wrote (or one provided for practice) and turns it into a clean, factual client update, checking every claim before sending.

## The exercise (30 min)

1. Pick the draft. Use a real draft email about an ongoing project, with names and numbers intact only if the training is internal and the tool is approved.
2. Write the prompt:

> You are my drafting assistant. Below is a draft client update. Rewrite it so it is clear, factual, and no longer than 150 words. Keep every number and date exactly as written. Where the draft says something that is not supported by the facts given, mark it [CHECK]. Do not add anything that is not in the draft.
>
> Draft:
> [paste the draft]

3. Run the prompt. Then check the output with the check list:
   - Every number and date matches the draft.
   - Every [CHECK] is a real unsupported claim. Discuss each with the trainer.
   - Nothing new was invented.
4. Fix the output by hand, not by re-prompting. The learner decides the final wording.

## What this proves

- A structured prompt produces a better first draft than free-form asking.
- The AI's output is input, not the answer. The check list is the skill.
