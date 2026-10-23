# VCE Applied Computing (Data Analytics; Software Development) and Algorithmics (HESS)

Sources: VCAA exam specifications, 2025 and 2024 external assessment reports for each study. My own summary.

## Exam formats
- **Data Analytics / Software Development:** 15 min reading + 2 hours writing. Section A: 20 MC (20). Section B: short answer (20). Section C: case-study questions with a detachable insert (60). 100 marks.
- **Algorithmics (HESS):** 15 min reading + 2 hours writing. Section A: 20 MC (20). Section B: short and extended answer (80). 100 marks.
- Applied Computing terminology is marked against the study design's "Terms used in this study" and the outcome-specific requirements documents. **Use those exact terms.**

## Applied Computing – marking habits to replicate
- **Apply to the case study** in Section C. Generic answers ("makes the customer feel good") score nothing. Two synonymous advantages earn only one mark.
- **Justify** = compare all options, pick one, explain why it's best *and* why the others aren't. For in-house vs external development: an advantage of one *paired with* a disadvantage of the other, tied to the case.
- **Explain how it's used, not what it is** (e.g. how a Gantt chart monitors progress, not a definition of a Gantt chart).
- **Exact study design terms**: non-functional requirements = usability, reliability, portability, robustness, maintainability, as the documents list them (in 2025 only certain terms were accepted for the context). "Easy to read" alone isn't a term.
- **Goal vs objective**: an objective is measurable and quantifiable.
- **Backups**: full vs incremental vs differential, *comparing* storage space and backup and restore times (many answers had them backwards).
- **Gantt charts**: milestones on the line, dependency lines precisely placed.
- **SQL**: name the function asked (e.g. INNER JOIN) and explain it across both tables. Output tables use **only** the specified columns (an extra ID column = 0).
- **Data types**: choose precisely (character for a single symbol, integer for whole numbers, Boolean for yes/no). Follow the given naming convention (camelCase) and type names exactly as in the object description.
- **Validation**: existence, type and range checks tied to the specific variable and why it would fail.
- **DFDs**: external entities can't flow directly to a data store, so explain the error.
- **OOP**: inheritance explained with the case's classes.
- **Security**: identity and access management, version control (rollback), secure development training. Answer the specific risk asked, not a different one.
- **Testing**: beta testing user groups chosen from the data flows. Know what participants actually test (usability, not functional output checks).
- **Research and ethics** (Data Analytics): features of a good research question, ethical data collection methods, referencing quotations correctly.

## Algorithmics – marking habits to replicate
- Give **time complexities** whenever options are compared, including hidden costs (string comparison, creating sub-lists).
- Use the **required design pattern** (dynamic programming, backtracking). Another approach scores little even if it works.
- **Annotate pseudocode.**
- ADT answers must show *how all required information* is stored. Give the advantage of any alternative data structure. Make the top of a stack explicit.
- Graph questions: include all required edges. Consider all starting points.
- **Proofs** (e.g. by contradiction): cover every case. State assumptions.
- Explain what a signature *means*, not what the operation does.
- Neural networks: apply the activation function at every node. Training vs test sets (no resampling claim needed).
- **Theory**: P ⊆ NP (P sits inside NP, not merely intersecting it). Don't confuse the Entscheidungsproblem with Church–Turing equivalence. Explain *why* a diagram is wrong rather than listing facts.
- Recognise reductions (e.g. a seating problem as graph colouring).
