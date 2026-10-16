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

## Worked application

For this scenario, apply the task-specific method above and deliver: A runnable guide, expected outputs and success checks, failure recovery, cleanup, and a precise tested-versus-untested record.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Never claim a command was tested because it looks plausible. A sample working once does not prove production reliability, security, or scale.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
