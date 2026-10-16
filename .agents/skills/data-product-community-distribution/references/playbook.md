# Community distribution playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Choose source/warehouse ecosystems and practitioner communities where the workload is relevant. Contribute a synthetic reconciliation example, operational lesson, or transparent methodology; never expose private customer queries or records.

## Task-specific method

Bring specific source/warehouse patterns, reconciliation lessons, operational examples, or transparent workload findings. Never share private customer queries or records as promotional proof.

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

Draft reply: "A green connector is only the first check. Reconcile exact keys and values, then update one known row and check the resulting state. Test deletes separately rather than inferring them from the initial load. [Affiliation: add your actual relationship before posting.] A five-row synthetic case is enough to start testing those semantics." No customer records or invented authorship; no post was sent.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not post, open promotional issues, contact maintainers, or send messages without authorization. No fake accounts, astroturfing, or unsolicited bulk outreach.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
