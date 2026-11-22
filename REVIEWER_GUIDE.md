# Reviewer guide — how to review this portfolio in 20 minutes

**English** | [Русский](ru/REVIEWER_GUIDE.md)

This portfolio shows methodology, not code. Here is how to check it fast — and what to look at to
tell a working method from a write-up.

## Reading order

| # | What | Time | What it proves |
|---|---|---|---|
| 1 | [README](README.md) | 2 min | the experience map and the scope of the folder |
| 2 | [Case 1: concept design](cases/01-concept-design/case.md) | 4 min | one design that answers scope, model, money and decisions for 120 organizations |
| 3 | [Case 2: business architecture](cases/02-business-architecture/case.md) | 3 min | a repeatable decomposition method with decision views |
| 4 | [Case 3: the financial case](cases/03-financial-case/case.md) | 3 min | numbers built to survive a budget committee |
| 5 | [Case 4: change management](cases/04-change-management/case.md) | 3 min | the human side run as a method, not as announcements |
| 6 | [Case 5: the end-to-end operating model](cases/05-operating-model/case.md) | 3 min | who answers to whom: explicit responsibility boundaries along the client path |

## What to check (the fast test for a working method)

1. **Can you run it?** Every case is written as a procedure: stage gates, registers, tables with
   owners and columns. Could a competent analyst execute it without the author explaining?
2. **Do decisions have owners?** Zoning gives every function one decision with a priority and a
   wave; the decision memo format fixes one recommendation, the conditions that change it, and
   risk owners; change-register entries name a support channel and an adoption KPI.
3. **Are numbers sourced?** Illustrative examples say "fictional data" explicitly; the rule
   "every figure carries a source, date and unit" runs through all five cases.
4. **Is there a gate?** A management-committee gate between concept and detailed design (case 1),
   a budget-committee gate with a three-artifact package (case 3), transition-period completion
   criteria signed per wave (case 4) — verifiable gates, not vibes.
5. **Anonymization is honest** — scale indicators remain (120 organizations, 1,500+ functions),
   but employer names, document titles and operational figures are absent by design.

## Questions worth asking

- How would this method change for a smaller organization? (Answer: the section set of the
  concept design and the attribute set of the function registry shrink to decision-critical
  fields — case 2, principle 4.)
- What breaks first when data quality drops? (Answer: the measurement-driven parts — the
  financial case labels unverified inputs "assumption" and pushes them into the scenario fork;
  case 2 marks interview figures as estimates.)
- What does AI change here? (See [forja-concept](https://github.com/khsergey-afk/forja-concept)
  and [omniscope-concept](https://github.com/khsergey-afk/omniscope-concept): the same registers
  and gates now govern AI-generated drafts.)
