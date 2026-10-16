# Customer psychology playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Investigate concern about silent corruption, credential scope, data movement, migration, or operating a failed workload. Offer reconciliation evidence and an approved bounded evaluation; retain governance controls rather than treating them as persuasion problems.

## Task-specific method

An evaluator may fear silent data corruption more than setup effort. Address reconciliation, lineage, access boundaries, rollback, and reproducible results.

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

Deliver: A barrier map, evidence-versus-hypothesis notes, a concrete intervention, and the next behavioral check.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not use fake scarcity, fabricated social proof, hidden costs, guilt, or unsupported claims about what all developers believe.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
