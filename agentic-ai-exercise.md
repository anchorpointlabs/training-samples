# Agentic AI — sample exercise: brief an agent on a bounded task

## The task

Write a brief that an agent can execute without further questions, for a real, bounded task: producing a weekly status report from a folder of inputs.

## The exercise (60 min)

1. Pick the task. It must be real, repetitive, and checkable — a weekly report is ideal.
2. Write the brief using this structure (the same structure the training teaches):

> You are my reporting agent. Your job: produce the weekly status report from the inputs below.
>
> GOAL: One markdown file, "status-report-YYYYMMDD.md", summarising this week's work.
>
> INPUTS: [folder path]. Read every file in it. Ignore files older than 7 days.
>
> FORMAT: Sections: Done / In progress / Blocked / Next week. Under each: one bullet per item, with the source file named in brackets. No opinions, no suggestions.
>
> STOP CONDITIONS: If a file mentions a client name, do not include it in the report — list it under Blocked as "client-confidential item, see [file]". If the folder is empty, write "no inputs" and stop. Do not create or edit any file other than the report.
>
> OUTPUT: Write the report next to the inputs. Then reply with the report and the count of files you read.

3. Run the brief twice: once on the real folder, once on an empty folder. Check both outputs against every clause of the brief.
4. Write down what the agent got wrong that the brief did not forbid. Tighten the brief. Run once more.

## What this proves

- A good brief is the whole skill: goal, inputs, format, stop conditions, output.
- The second run exists because the first brief is never complete. Iteration is the work.
