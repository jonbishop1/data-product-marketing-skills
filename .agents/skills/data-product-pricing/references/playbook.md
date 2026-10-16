# Pricing playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Compare meters against volume, scan/compute behavior, concurrency, refresh frequency, retention, egress, and operating cost. Explain metering semantics, retries, failed jobs, predictability, and spend controls with explicitly observed or illustrative workloads.

## Task-specific method

Consider workload variability, refresh frequency, concurrency, retention, source volume versus scanned volume, egress, and controls that prevent surprise bills.

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

For this scenario, apply the task-specific method above and deliver: A meter comparison, workload scenarios, proposed package table, cost and predictability risks, customer-facing explanation, and research questions.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not copy a competitor's prices without checking workload fit. No universal free tier, trial duration, margin target, or seat-based default.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
