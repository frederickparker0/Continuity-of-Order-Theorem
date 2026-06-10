# Contributing to the Continuity-of-Order Research Program

Thank you for taking the work seriously enough to test it.

This repository is not asking contributors to believe COT. It is asking them to help determine what COT is:

- a useful theorem candidate,
- a recovery protocol,
- a diagnostic framework,
- a bridge notation between domains,
- or a failed/redundant formalism.

All of those outcomes are useful if they are shown honestly.

## Ground Rules

1. Use observed, source-admitted, or reproducibly derived data.
2. Label simulations as simulations. They cannot replace missing real data for promotion.
3. Do not tune on the same evidence used for heldout testing.
4. Do not add residuals, coefficients, or interpretation repairs after a heldout failure.
5. Compare against strong baselines on the same target.
6. Include uncertainty or tolerance criteria before claiming a pass.
7. Keep failure reports. A clean failure is a contribution.
8. Do not claim COT solves turbulence, protein folding, vacuum energy, or any other branch.

## Good First Contributions

The most useful contributions right now are not broad speculation. They are specific, checkable repairs.

### Turbulence

- Help admit the missing 76 source payloads for the `transition_bl` JHTDB route.
- Provide an exact archived source bundle if one exists.
- Reproduce the 96-payload source-plus-target contract.
- Build baseline and wrong-form mutation tests after source provenance is admitted.

### Protein Folding

- Independently run the C184/C193 reproduction validator.
- Test whether the local Domainome signal generalizes outside the original route.
- Add strong baseline comparisons with identical train/test boundaries.

### Vacuum Energy / theta_V

- Propose exactly one predeclared candidate packet.
- Preserve the frozen definition: `theta_V = atan2(wa, w0 + 1)` in degrees.
- Test against `compressed_cmb_no_sn_reference`.
- Treat ties as failure.

### Mathematics Candidate

- Sharpen the definitions of path, state, order, transition, boundary, and functional.
- Identify whether the candidate is a theorem, conjecture, diagnostic protocol, or equivalent reformulation.
- Prove narrow claims before proposing broad ones.
- State what would falsify the candidate.

## Evidence Labels

Every contribution should identify the evidence type:

- `calibration`: used to build, tune, choose, or lock the candidate.
- `recovery`: known benchmark used to show the candidate can recover established behavior.
- `heldout`: not used to build, tune, select, or justify the candidate.
- `diagnostic`: useful for debugging but not promotion-grade evidence.
- `rejected`: failed provenance, leakage, insufficient uncertainty, or unsupported claim.

## Pull Request Checklist

Before opening a pull request, confirm:

- [ ] The claim is bounded and does not overstate promotion.
- [ ] The evidence label is explicit.
- [ ] Dataset source and provenance are documented.
- [ ] Calibration and heldout data are separated.
- [ ] Baseline comparison is included or the absence is declared.
- [ ] Mutation/wrong-form controls are included or listed as a blocker.
- [ ] Failure modes are logged, not hidden.
- [ ] Large raw datasets are not committed to the repository.

## What Counts as Progress

Progress can be any of the following:

- a reproduced result,
- a corrected claim boundary,
- a stronger baseline,
- a failed mutation control,
- a clean data-wall report,
- a formal definition that removes ambiguity,
- a narrowed theorem statement,
- or a falsification that saves everyone time.

This project advances by becoming harder to fool.

