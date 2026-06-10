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

## Protein Folding Reproduction Route

Minimal next reproducible step:

1. Use the C184/C193 external-reproduction handoff/validator.
2. Reproduce Domainome diagnostics independently.
3. Test generalization beyond the narrow Domainome local signal.
4. Treat ProteinGym packets as baseline/control scaffolding until COT-specific scoring is locked.

## Vacuum Energy Reproduction Route

Minimal next reproducible step:

1. Preserve the frozen theta_V definition.
2. Select exactly one candidate packet in advance.
3. Compare against `compressed_cmb_no_sn_reference`.
4. Require strict improvement on all frozen metrics.
5. Treat ties as failure.

