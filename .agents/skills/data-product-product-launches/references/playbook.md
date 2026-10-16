# Product launches playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Verify connector behavior, approved evaluation data, reconciliation, access scope, cost limits, operating ownership, and recovery before choosing launch scope. A sample-only test can support a scoped beta claim, not unqualified production availability.

## Task-specific method

Verify connector behavior, data access scope, evaluation dataset, reconciliation, cost, limits, deployment, and the path from beta testing to approved production use.

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

For this scenario, apply the task-specific method above and deliver: A readiness decision, launch brief, owned checklist and schedule, announcement drafts, support and recovery plan, and downstream measurement.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not declare general availability from a marketing deadline. Do not fabricate launch traction or assume every release deserves every channel.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
