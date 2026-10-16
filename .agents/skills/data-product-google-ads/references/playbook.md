# Google ads playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Tie query groups to supported source/destination workloads and buying context. Qualify access, platform fit, correctness needs, and an evaluation owner; account for delayed enterprise qualification and distinguish students from deployable accounts.

## Task-specific method

Tie terms to supported workload and connector needs. Qualification may require deployment fit, permissions, data scale, and a credible evaluation owner rather than an inexpensive lead.

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

Facts: documented source/destination pair and initial synthetic reconciliation. Draft headline: "Evaluate Incremental Ingestion". Description: "Inspect a synthetic source-to-destination example. Plan the correctness checks for your workload." Review production and platform queries against documented fit rather than claiming support. Budget and conversion-upload configuration remain pending supplied account facts; drafting does not spend.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not default to business-hours delivery, mobile bid cuts, or a fixed conversion-count rule. Do not claim causality from attributed pipeline or upload sensitive customer data without authorization.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
