# Beyond the Wronskian: Linear Independence of ODE Solutions

## Overview
A mathematical investigation into necessary vs. sufficient conditions 
for linear independence of ODE solutions using the Wronskian determinant.
Course project for Mathematics IV, BSDS-II, Indian Statistical Institute 
Bangalore (May 2026). Instructor: Prof. Ramij Rahaman.

## The Question
If W(x) = 0 everywhere on an interval, must the functions be linearly 
dependent? The answer is surprisingly **no** — and understanding why 
doesn't break ODE theory is the core of this project.

## What's in this repo
- `Beyond_The_Wronskian_Report.pdf` — full written report
- `Beyond_The_Wronskian_Presentation.pdf` — slide deck (27 slides)

## Key Results
- Proved the sufficient condition: W ≠ 0 at some point ⟹ independent
- Constructed a counterexample: f₁(x) = x² and f₂(x) = x|x| on [-1,1]
  are linearly independent yet have W ≡ 0 everywhere
- Showed the resolution via Abel's Identity — for ODE solutions with
  continuous coefficients, W ≡ 0 and W ≠ 0 everywhere are the only
  possibilities (all-or-nothing property)

## Tools
R (figures), LaTeX (typesetting)

## References
- Kreyszig, *Advanced Engineering Mathematics*, 10th ed., §2.8
- Ross, *Differential Equations*, 3rd ed., §4.1
