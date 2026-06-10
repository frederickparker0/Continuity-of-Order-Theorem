# Route to a Mathematics Candidate

Research originator and project steward: **Frederick M. Parker**.

This document states how the Continuity-of-Order work can move from research program toward a mathematical candidate without pretending it has already arrived.

## Current Object

COT is currently best described as a path-history theorem candidate:

> Ordered histories of observed systems may contain transition or failure information that is lost in pointwise, static, or aggregate summaries.

This is not yet a theorem. It becomes a serious mathematics candidate only if the objects, maps, assumptions, and falsification conditions are made precise.

## Minimal Formal Objects

A branch must define the following before claiming theorem-grade progress.

### State Space

Define a state space `X`.

Each state `x_i in X` must be observed, source-admitted, or reproducibly derived from observed/source-admitted data.

### Path

Define an ordered path:

`P = (x_0, x_1, ..., x_n)`.

The ordering must be physically or empirically meaningful. Time order, material-path order, sequence order, or acquisition order may qualify if justified.

### Summary Comparator

Define a non-path summary:

`S(P)`.

Examples include pointwise state features, static snapshots, aggregate statistics, or baseline model outputs.

### COT Functional

Define a path-history functional:

`F_COT(P)`.

This functional must be frozen before heldout testing. Coefficients, residuals, thresholds, and interpretation rules must be locked from theory, calibration data, or independent measurement.

### Transition or Failure Boundary

Define a target boundary:

`B`.

The boundary may be a transition, fracture, regime shift, folding/stability event, or other observable event. It must have a declared measurement source and uncertainty/tolerance rule.

## Candidate Claim Form

A narrow candidate claim should look like this:

> For paths `P` drawn from domain `D`, under admissibility conditions `A`, the frozen functional `F_COT(P)` recovers, ranks, detects, or constrains boundary `B` at least as well as comparator `S(P)` under metric `M`, tolerance `T`, and baseline set `K`.

This form is intentionally narrow. Broad claims should be built only after narrow claims survive.

## Proof and Validation Obligations

A branch may advance only when it answers:

1. What exactly is the path?
2. What exactly is the order?
3. What exactly is the candidate functional?
4. Which data locked the candidate?
5. Which data were held out?
6. Which baselines were tested?
7. Which wrong variants failed?
8. What uncertainty or tolerance makes the result meaningful?
9. What would falsify the claim?

## Promotion Labels

- `L5 Recovery`: recovers known results across multiple benchmarks.
- `L6 Heldout Recovery - Baseline Equivalent`: recovers heldout results without new tuning, but does not beat established theory.
- `L6 Diagnostic Recovery`: recovers heldout results and adds failure detection, clarity, or protocol utility.
- `L7 Distinct Prediction`: predicts or constrains something not forced by the baseline and passes.
- `Quarantined`: blocked by leakage, missing data, missing uncertainty, hidden tuning, or unsupported interpretation.

## What Would Make COT Mathematical

COT becomes mathematics-grade when a branch supplies a frozen object and a falsifiable theorem-shaped claim:

- exact domain,
- exact path definition,
- exact functional,
- exact comparator,
- exact admissibility rules,
- exact result type,
- exact proof or empirical-validation contract,
- exact failure condition.

Until then, it remains a structured research program. That is acceptable. The purpose of this repository is to make the transition visible and testable.
