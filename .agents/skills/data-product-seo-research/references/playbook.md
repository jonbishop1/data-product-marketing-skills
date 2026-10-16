# Seo research playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Separate conceptual education from operational source/destination, schema, recovery, freshness, and cost queries. A connector page needs verified behavior and a distinct task; do not map every possible product pair to an indexable page.

## Task-specific method

Distinguish conceptual data education from operational needs such as CDC recovery, schema migration, warehouse cost, or reconciliation. Verify that supported connectors and behavior fit the intent.

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

For this scenario, apply the task-specific method above and deliver: A sourced opportunity table with query, task, intent, evidence or estimate, product fit, proposed page, competing results, effort, and next action.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not invent volume, difficulty, or rankings. Search visibility and AI-answer citations need separate observations; neither guarantees adoption.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
