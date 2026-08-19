# Pedagogical Constitution

This summary is derived from the original project handoff preserved in `docs/source/excel_analyst_course_handoff.html`.

## Core model

**Problem → Investigation → Evidence → Discovery → Principle**

The learner should encounter the analyst problem before being told which function or concept solves it.

## Question progression

A worksheet should usually move through:

1. Observation — What do you see?
2. Verification — How can you test it?
3. Evidence — What proves the conclusion?
4. Impact — Why does it matter analytically?
5. Professional behavior — What should be checked before trusting/changing the data?

## Practice design

- Use real `.xlsx` practice workbooks when hands-on work is useful.
- Do not include solutions or obvious hints in the exercise workbook unless explicitly requested.
- Use realistic analyst domains and manageable but meaningful datasets.
- Preserve a clear row grain and intentional relationships.
- Every irregularity should teach something; avoid random "bad data" noise.
- Traps must be plausible in interview/take-home conditions.
- Do not design a worksheet around an Excel function. Design it around an analyst problem.

## Cumulative learning

Later modules reuse earlier mental models instead of restarting from zero.

Example:
- Data Discovery: Which field appears to be the identifier?
- Data Cleaning: Does that identifier actually behave as a unique key?
- Lookup / Join: Is that key safe to use in a relationship?

## HTML chapter protocol

Create a permanent HTML chapter only after the exercise is completed:

**Attempt → Review/Hints → Full Solution → Discussion → HTML Chapter**

A substantial chapter should preserve the problem, questions, answers, evidence, Excel method, validation, common traps and transferable principle.
