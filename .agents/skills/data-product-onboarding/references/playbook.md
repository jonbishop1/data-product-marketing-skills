# Onboarding playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Map approved access, source connection, initial output, reconciliation, incremental changes, recurring runs, and production approval. Keep sample success and real-data success separate; show the next useful step while an administrator reviews access.

## Task-specific method

Include approved access, representative data, connector setup, first valid output, reconciliation, recurring runs, and production approval. An imported sample or green connector alone may not prove value.

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

For this scenario, apply the task-specific method above and deliver: A journey map, first-value and durable-adoption definitions, prioritized interventions, failure recovery, lifecycle copy if relevant, and an event plan.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not remove access controls to improve conversion. Do not treat trial expiry, usage limits, or a required credit card as universal best practices.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
