# Failure and Data Walls

This project treats failure records as first-class evidence. A failure row should state what failed, why it failed, what evidence proves the failure, and what exact next test would resolve it.

## Active Turbulence Data Wall

Current request:

- Branch: turbulence
- Gate: provenance before scoring
- Need: JHTDB `transition_bl` exact source-plus-target bundle frozen by the C337 96-payload contract
- Source side: 76 payloads across heldout blocks `t520`, `t620`, `t720`, `t820`
- Target side: 20 C304 target payloads already local and hash-frozen
- Preferred route: run unchanged C207 with `JHTDB_AUTH_TOKEN` or `TURBULENCE_JHTDB_TOKEN`
- Acceptable alternate: official archived bundle matching every required payload and hash
- Forbidden substitutes:
  - public-testing-token exports for source provenance,
  - 16-target stale bundles,
  - changed anchors, offsets, variables, row order, or support,
  - same-anchor Eulerian targets relabeled as material-path evidence,
  - simulated or inferred payloads,
  - scoring before source hash admission.

Promotion effect:

- blocked

## Active Protein Folding Failure Boundary

Current blocker:

- Local Domainome signal is not enough for public promotion.
- External reproduction is not yet present.
- Observed kinetic robustness failed.
- ProteinGym support remains baseline/control scaffolding until a COT reader is scored under locked rules.

Promotion effect:

- public promotion blocked

## Active Vacuum Energy Failure Boundary

Current blocker:

- The reference-beat contract is ready, but no exact one-candidate packet has beaten `compressed_cmb_no_sn_reference`.
- Existing candidate inventory is not fill-ready under the frozen support, delta, and calibration-overlap fields.

Promotion effect:

- stayed blocked

## Cross-Branch Pattern

The same failure pattern appears across branches:

1. local signal or diagnostic recovery appears;
2. stronger baseline, independent-source, or mutation gate absorbs it;
3. honest progress requires a sharper contract, not looser claims.

This is a useful pattern, not a reason to force promotion.

