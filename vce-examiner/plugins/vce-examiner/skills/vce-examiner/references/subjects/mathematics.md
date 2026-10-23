# VCE Mathematics (Study Design from 2023)
Covers Mathematical Methods, Specialist Mathematics, General Mathematics, Foundation Mathematics.

Sources: VCAA exam specifications (2025 versions) and the 2025 external assessment reports for each study. Summarised in my own words.

## Exam formats
| Study | Exam 1 | Exam 2 |
|---|---|---|
| **Methods** | 1 hr writing, **no technology, no notes**, short and extended answer, 40 marks, 20% of study score | 2 hr, CAS + one bound reference, Section A 20 MC (20 marks) + Section B extended (60), 80 marks, 40% |
| **Specialist** | Same structure as Methods Exam 1: tech-free, 40 marks, 20% | Same as Methods Exam 2: 20 MC + 60 marks extended, 40% |
| **General** | 1.5 hr, CAS allowed, **40 MC** (16 data analysis, 8 recursion & financial modelling, 8 matrices, 8 networks), 30% | 1.5 hr, short/extended answer, 60 marks (24 / 12 / 12 / 12 across the same areas), 30% |
| **Foundation** | One exam: Section A 20 MC + Section B 60 marks short/extended answer, 80 marks, 40% | — |
All have 15 minutes reading time and a formula sheet.

## Universal marking rules (apply hard)
- **Working must be shown for any question worth more than 1 mark.** A bare correct answer typically gets only the answer mark. A bare wrong answer gets 0, whereas shown method can earn a method mark.
- **"Show that"**: every line must follow logically, with the given result *emerging* from the working. Verifying by substitution, working backwards, skipping steps or "chains" of run-on equals signs lose marks. CAS-only steps don't count as showing.
- **"Hence"**: must use the previous result. **"Use calculus"**: must show calculus steps (e.g. antiderivative + initial condition), not just a CAS answer.
- **Exact vs rounded**: give exact answers unless told otherwise. A decimal when exact is asked for loses the mark. Round **only at the final step** and to the precision asked (decimal places vs significant figures). Rounding early compounds error.
- **Multiple or conflicting answers** = no full marks. Extra wrong solutions (e.g. outside the domain) cost the mark. Extra information must also be correct.
- **Answer the actual question**: giving a gradient when the equation of the tangent was asked, x-values when coordinates were asked, variance when standard deviation was asked, the turning point when the max *value* was asked, "the equation" when a coordinate was asked. All lost marks repeatedly.
- **Notation**: name functions as given (f′(x), not y′ or "dy/dx" if f was named). Include dx and +c. Brackets in product/quotient rules and interval notation (square vs round brackets matter). Coordinates in round brackets. Write equations of asymptotes, not just values. Define variables before using them.
- **Read ahead**: later parts often reuse earlier results.
- **Legibility**: papers are scanned, so use pen or 2B+ pencil. Faint dashed asymptotes may not show up. Write answers inside the space and make the final answer obvious.

## Graphs and sketches
- Label intercepts, turning points and endpoints (open/closed circles, including points of discontinuity) as coordinates, and asymptotes as equations.
- Correct shape: smooth curves, asymptotic behaviour (don't curve away), symmetry (e.g. cosine about its axis), correct domain and range. Use the grid and scale. Set CAS window to the given scale to check.
- Use a ruler for straight lines, asymptotes and tangent lines (tangent lines must not cut the curve where they shouldn't).

## Methods – recurring traps
- Chain rule missing the inner derivative. Log antiderivative missed when integrating 1/(ax+b), or the 1/a factor dropped.
- Trig equations: wrong quadrant or base angle, missing solutions from the period, a general solution given when particular solutions in a domain were required. **Exact trig values are expected knowledge.**
- Probability: forgetting total probability = 1. Factoring a constant out of an integral invalidly. Binomial sums: computing one term instead of the cumulative sum.
- Exponential equations: recognise the quadratic form, check the domain (e.g. reject impossible values such as negative exponentials, but don't wrongly discard valid ones).
- Transformations: correct wording and **order**, correct dilation factor (reciprocal errors).
- Average *value* vs average *rate of change* confused.
- CAS transcription errors: entering the right integral but writing down a wrong answer.

## Specialist – recurring traps
- Lines in parametric form: **different parameters for each line** when finding an intersection.
- Proof by induction: misstating the assumption, or a weak inductive step.
- Complex numbers: label points on the Argand plane. Conjugate root theorem. Principal arguments.
- Vectors: constant vector of integration. Parallel planes = normals that are scalar multiples. Dot product = 0 for perpendicular.
- Differential equations: apply the initial condition for c. Euler's method must be shown (a table is fine).
- Implicit differentiation arithmetic. Expected value of a continuous random variable may need partial fractions.
- Statistics: standard deviation vs variance. Type I/II errors.

## General – recurring traps
- Use **study design terminology exactly** (e.g. named features of time series: trend, seasonality, irregular fluctuations, which are always present, and structural change).
- Interpolation vs extrapolation is judged on the **explanatory** variable.
- Read calculator output in exponent notation (1.05E6). Significant figures are a persistent weakness.
- Use the values in the table when instructed, not a finance solver giving a different cent value. Sign conventions in finance solvers (payments are negative, but state the answer sensibly).
- Distinguish a recurrence relation from a rule. Matrices: row vs column sums. The identity matrix's effect.
- Networks: don't add edges that aren't there. Give only what's asked (e.g. a single activity).

## Foundation – recurring traps
- Check answers are **realistic** in context (a biscuit can't weigh kilograms).
- Units and conversions (mm → m, ha, GL). State units in "show that" money answers.
- Percentage change/difference: correct denominator (it's on the formula sheet). 0.5% ≠ 0.05.
- Weighted averages done properly. Simplify ratios fully.
- Interpreting percentiles (the 50th percentile is not "most"). Graph comparisons must actually compare and reference the data.
- Tax brackets, superannuation rates and GST applied to the right amounts.
- Many students left questions blank. Always attempt, since method marks are available.

## How to mark maths in this skill
- Break each question into **M (method) and A (answer) marks** and award them line by line. Note consequential marks where an earlier error carries through correctly.
- For MC, give the correct option and say why each distractor is tempting but wrong.
- In the model answer, set the working out like an exam solution: one logical step per line, no equals-chaining.
