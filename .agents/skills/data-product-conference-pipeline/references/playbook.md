# Conference pipeline playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Use synthetic records and a workload-evaluation worksheet. Qualify source/destination, correctness/freshness need, access owner, and platform approval without collecting sensitive data. Track agreed evaluations separately from scans and conversations.

## Task-specific method

Use synthetic data and a workload evaluation worksheet. Qualify source/destination fit, access ownership, correctness needs, and approval constraints without collecting sensitive records.

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

Demo uses synthetic Postgres records and a hosted warehouse; connectivity and credentials are still required for a live run. Prepare a labelled recording and static before/after reconciliation table for a network failure. Do not advertise a "no-network live demo". A useful next step is an agreed synthetic evaluation with an owner; a badge scan alone is not pipeline.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not scrape restricted attendee data, send unapproved messages, or report every scan as pipeline. Separate preparation from paid sponsorship or outreach execution.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
