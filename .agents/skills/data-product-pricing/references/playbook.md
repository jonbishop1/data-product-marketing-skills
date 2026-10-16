# Pricing playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Select the data workload only when a brief labels a separate developer workload. Do not import that other product's human/CI identities or requests into this offer. If this data product has no supplied user count, a numeric seat scenario is unavailable. Compare data volume, scan/compute, refresh, retention and egress; billed resource use and change counts are distinct.

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

## Completed example

Facts: one million source rows, 5% change daily; scanned bytes, compute, retries and egress unknown.

50,000 changed rows/day is an illustrative daily activity estimate if the percentage means distinct changed rows per day. Over 30 days this is 1.5 million change occurrences, not necessarily 1.5 million distinct source rows. It does not establish billed bytes, repeated writes, or cost.

Compare a workspace base plus explicit workload allowance, changed-record meter, and measured compute/scan meter. Recommend testing the base-plus-allowance hypothesis for predictability; define retries, failed jobs, alerts and hard caps as proposed terms. First measure actual billed resources and customer budget fit. Do not mix a separate developer workload's CI identities into this product or invent a validated price.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not copy a competitor's prices without checking workload fit. No universal free tier, trial duration, margin target, or seat-based default. Final audit: does any sentence imply no current billing from an unknown price, vendor automation cost from local execution, or cost under-recovery without cost data? Remove that inference from the recommendation itself. Provide a useful proposed offer even when current terms are unknown.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
