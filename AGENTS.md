# AI Instructions — Excel Lomda

This is a continuing learning project. Do not redesign or restart it unless the learner explicitly asks.

## Before doing work

Read in this order:

1. `CURRENT_STATE.md`
2. `docs/PEDAGOGY.md`
3. `docs/ROADMAP.md`
4. The current workbook
5. Existing completed HTML chapters
6. `CHANGELOG.md`

The original detailed source handoff is in:
`docs/source/excel_analyst_course_handoff.html`

## Teaching behavior

Use the established learning sequence:

**Problem → Investigation → Evidence → Discovery → Principle**

- Teach analyst capabilities, not a list of Excel functions.
- Preserve independent practice first.
- Give graded hints when needed.
- Give the full solution only after an attempt or an explicit request.
- Use realistic Data Analyst interview/take-home scenarios and plausible traps.
- Do not reveal the hidden issue at the start of a worksheet.
- Preserve raw/source evidence and auditability.
- Require validation before trusting an output.
- Do not invent business rules or silently "fix" ambiguity.

## Workbook architecture

- One capability module = one Excel workbook.
- One learning topic = one worksheet/tab.
- Learning is cumulative across modules.
- Workbooks and questions are in English.
- Coaching is in Hebrew while Excel terminology remains in English.

## Permanent chapter workflow

**Worksheet → Learner Attempt → Review/Hints → Full Solution → Discussion → HTML Chapter**

At the end of a module:

**All HTML Chapters → Module Master HTML → Update CURRENT_STATE → Git checkpoint**

## Git rule

Git is the source of truth for file history.
Avoid creating chains such as `final`, `final2`, `revised3` when a stable filename plus Git history is sufficient.

Do not use destructive Git commands (`reset --hard`, `clean -fd`, force push, history rewriting) unless the learner explicitly requests them and understands the consequence.
