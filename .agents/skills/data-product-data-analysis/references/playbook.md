# Data analysis playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Choose workload/workspace/account identities deliberately. Separate sample runs, valid real-data output, reconciliation, recurring approved operation, and paid adoption. Include empty/failed runs, freshness, operating cost, and complete observation windows.

## Task-specific method

Measure valid workload completion, freshness and reconciliation where relevant, recurring approved data use, workload cost, and account progression. Distinguish empty, failed, test, and successful runs.

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

For this scenario, apply the task-specific method above and deliver: Metric definitions, reproducible analysis or query, concise findings, uncertainty and data-quality notes, and a recommended decision or next measurement.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not publish customer-level records or deanonymizable small cells. Do not use arbitrary universal activation benchmarks or claim an experiment effect without appropriate evidence.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
