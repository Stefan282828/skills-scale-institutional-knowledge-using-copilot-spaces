# Roles & Personas — Responsibilities Matrix

This matrix provides a quick RACI-like view (Responsible, Accountable, Consulted, Informed) for common project activities. Use it to clarify handoffs and who is expected to act.

Legend:
- R = Responsible (does the work)
- A = Accountable (owns the outcome)
- C = Consulted (provide input)
- I = Informed (kept updated)

| Activity / Role                         | PdM | PM | Dev | QA Lead | Solution Architect | Scrum Master | BA | UX/UI |
|-----------------------------------------|-----|----|-----|---------|--------------------|--------------|----|-------|
| Define product outcomes / success metrics| A   | I  | I   | I       | C                  | I            | C  | C     |
| Write user stories & acceptance criteria | C   | I  | C   | C       | C                  | I            | A  | C     |
| Architecture & technical design         | C   | I  | R   | I       | A                  | I            | C  | I     |
| Implementation (deliver code)           | I   | I  | A/R | C       | C                  | I            | I  | C     |
| QA testing & verification               | I   | I  | C   | A/R     | I                  | I            | C  | C     |
| Release plan & deployment               | C   | A  | C   | R       | C                  | I            | I  | I     |
| Sprint ceremonies & cadence             | C   | C  | R   | C       | I                  | A/R          | C  | I     |
| Stakeholder communications              | A   | R  | I   | I       | I                  | I            | I  | I     |

Notes:
- One person may hold multiple roles in smaller teams. When that is the case, still record both personas to show intended responsibilities.
- Use this matrix as a starting point — adapt per project or org needs, and keep it in the project README or One-pager for visibility.
