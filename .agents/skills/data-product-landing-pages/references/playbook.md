# Landing pages playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Organize the page around workload, source-to-destination flow, supported semantics, reconciliation evidence, permissions, cost, and evaluation. Separate credential-free sample access from approved real-data setup instead of promising instant production access.

## Task-specific method

Show data flow, supported inputs and outputs, permissions, validation behavior, deployment choices, and a realistic evaluation path. Keep enterprise approvals accessible without overwhelming a simple sample workflow.

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

## Application brief

Deliver: An annotated page outline or implementation, section-level proof requirements, CTA behavior, and a measurement plan connecting the page to evaluation quality.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not promise conversion lifts from a wireframe. A demo request, documentation visit, and successful evaluation are different events.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
