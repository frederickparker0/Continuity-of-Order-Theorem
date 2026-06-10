# Reproducibility Guide

This public package does not include raw datasets or private/local artifacts. It records the state needed for a reviewer to reproduce or challenge the work.

## General Rules

- Use only observed or source-admitted data.
- Do not replace missing data with simulation unless the run is explicitly labeled diagnostic-only.
- Do not score before data, provenance, uncertainty, baselines, and mutation controls are frozen.
- Keep failed variants in the failure log.
- Do not rewrite failure as promotion.

## Turbulence Reproduction Route

Dataset family:

- Johns Hopkins Turbulence Database, `transition_bl`

Frozen target side:

- 20 future-material point-path payloads from the C304 route

Missing source side:

- 76 C204/C207 source payloads require explicit-token reexport/hash admission or an exact official archived bundle.

Minimal next reproducible step:

1. Obtain valid JHTDB credential or exact official archived bundle.
2. Reexport/admit the 76 source payloads unchanged.
3. Confirm the 20 target payload hashes.
4. Emit a no-scoring source-target review.
5. Only after that, prepare scoring with baselines and mutations.

## Transition Front Reproduction Route

Protocol:

- `COT_TRANSITION_FRONT_TURBULENCE_SINGLE_DOMAIN_PROTOCOL_v0_1`

Minimal next reproducible step:

1. Preserve the sparse-front residual-class adapter boundary.
2. Admit the unchanged 76-source hash lane against C337.
3. Do not upgrade point anchors into true `Gamma_D` front geometry.
4. Score only after source admission and only under the frozen baselines/controls.

## Fracture / Crack Propagation Reproduction Route

Minimal next reproducible step:

1. Obtain a valid access/grant/denial artifact for Zenodo `11669624`, or acquire the complete official-md5 `H01.zip`.
2. Verify bytes before schema extraction.
3. Extract rows only from admitted payloads.
4. Run frozen reader and baselines only after admission.

## Plasma Reconnection Reproduction Route

Minimal next reproducible step:

1. Use the C92/C93 MMS intake/protocol.
2. Build an externally labeled event/control register.
3. Use event-heldout splits.
4. Run raw-channel baselines and null controls.

## Protein Folding Reproduction Route

Minimal next reproducible step:

1. Use the C184/C193 external-reproduction handoff/validator.
2. Reproduce Domainome diagnostics independently.
3. Test generalization beyond the narrow Domainome local signal.
4. Treat ProteinGym packets as baseline/control scaffolding until COT-specific scoring is locked.

## Planck / Action-Phase Reproduction Route

Minimal next reproducible step:

1. Preserve the action-phase mapping `kappa_A = hbar`.
2. Reproduce photoelectric and Davisson-Germer recovery checks.
3. Preserve Compton strict row-level failure until repaired by source-grade evidence.
4. Do not claim derivation.

## DESI / Vacuum Energy Reproduction Route

Minimal next reproducible step:

1. Import DESI DR2 chain/posterior summaries where required.
2. Preserve the frozen theta_V definition.
3. Select exactly one candidate packet in advance.
4. Compare against `compressed_cmb_no_sn_reference`.
5. Require strict improvement on all frozen metrics.
6. Treat ties as failure.

