# Integration marketing playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Verify source, transformation, destination, schema/update semantics, credentials, reconciliation, freshness, partial failures, and recovery. Connectivity alone does not prove correct operation; distinguish a tested supported connector from a custom example.

## Task-specific method

Show source, transformations, destination, credentials, reconciliation, freshness, and recovery behavior. Supported connectivity alone does not prove equivalent semantics or production readiness.

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

For this scenario, apply the task-specific method above and deliver: A verified workflow brief, integration page or listing, example and evidence notes, support boundary, distribution drafts, and maintenance plan.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not generate a directory of unsupported product pairs, use restricted brand assets, or imply endorsement because an API is public.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
