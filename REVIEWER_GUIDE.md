# Reviewer guide — how to review this portfolio in 15 minutes

**English** | [Русский](ru/REVIEWER_GUIDE.md)

This portfolio shows methodology, not code. Here is how to check it fast — and what to look at to
tell a working method from a write-up.

## Reading order

| # | What | Time | What it proves |
|---|---|---|---|
| 1 | [README](README.md) | 2 min | the experience map and the scope of the folder |
| 2 | [Case 1: shared services](cases/01-shared-services/case.md) | 5 min | the end-to-end path: concept → financial case → service model → operating model → rollout |
| 3 | [Case 2: business architecture](cases/02-business-architecture/case.md) | 3 min | a repeatable decomposition method with decision views |
| 4 | [Case 3: requirements engineering](cases/03-requirements-engineering/case.md) | 3 min | standards turned into a sign-off gate |
| 5 | any one [method](methodology) + one [checklist](checklists) | 2 min | the working granularity: steps, tables, severity levels |

## What to check (the fast test for a working method)

1. **Can you run it?** Pick any method and ask: could a competent analyst execute the steps without
   me explaining? Every method here is written as a procedure: numbered steps, tables, rules.
2. **Do decisions have owners?** Gap tables carry a "owner" and "deadline" column; checklists carry
   severity levels that decide *who must act before release*.
3. **Are numbers sourced?** Illustrative examples say "fictional data" explicitly; the rule
   "every figure carries a source, date and unit" runs through methods, checklists and cases.
4. **Is there a gate?** The requirements case shows a 29-check gate before sign-off; the deck
   checklist shows hard geometry numbers (contrast ≥ 4.5:1, min font size) — verifiable, not vibes.
5. **Anonymization is honest** — scale indicators remain (a group of 100+ companies, 1,500+
   functions), but employer names, document titles and operational figures are absent by design.

## Questions worth asking

- How would this method change for a smaller organization? (Answer: the attribute set shrinks to
  decision-critical fields — see case 2, principle 4.)
- What breaks first when data quality drops? (Answer: measurement-driven methods — case 1 and the
  SLA method fall back to "estimate" labeling and a baseline-removal rule.)
- What does AI change here? (See [forja-concept](https://github.com/khsergey-afk/forja-concept) and
  [omniscope-concept](https://github.com/khsergey-afk/omniscope-concept): the same checklists now
  gate AI-generated drafts.)
