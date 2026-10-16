# Quickstart playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Use synthetic or authorized records with explicit schema, expected keys/values, reconciliation checks, connector permissions, resource caps, and cleanup. A green connection or sample dashboard alone is not the success assertion.

## Task-specific method

Use synthetic or authorized data, state schema and expected rows or invariants, verify reconciliation, and disclose created resources and possible charges.

## Output worksheet

| Field | Record |
| --- | --- |
| Requested decision and task | |
| User, evaluator, buyer, and owner | |
| Supported behavior and environment | |
| Evidence, source, and limits | |
| Proposed action or finished artifact | |
| Meaningful result and verification | |
| Unknowns, failure, and stop condition | |

## Completed example

Proposed synthetic test: five rows, keys 1–5, status="new". Reconcile exact keys, values and multiplicities at destination. Update source key 3 to status="ready"; after a documented sync/checkpoint condition, expect exactly five rows and only key 3 changed. This is an unexecuted invariant, not verified propagation. Missing connector syntax stays a labelled command placeholder. On interruption inspect documented checkpoint/retry behavior; do not reload into the same target until duplicate/idempotency and cost effects are known. Use a disposable destination for an authorized recovery experiment.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Never claim a command was tested because it looks plausible. A sample working once does not prove production reliability, security, or scale.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
