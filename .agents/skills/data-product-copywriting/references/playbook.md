# Copywriting playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Anchor copy in the data workflow and the output users can validate. Qualify freshness, correctness, scale, and cost claims; distinguish connectivity from correct recurring operation. Offer a sample or approved workload evaluation with clear prerequisites.

## Task-specific method

Explain what happens to data, how results are validated, and the workflow improved. Be precise about freshness, accuracy, and scale; each requires scope and evidence.

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

Facts: initial synthetic records matched between source and destination; inserts/updates documented; propagation not tested.

Finished copy: **Evaluate incremental ingestion with a reconciled sample.** Start with a synthetic source-to-destination example whose initial keys and values match. Inserts and updates are documented; test change propagation for your evaluation before relying on it. **CTA: Inspect the synthetic example.**

The initial comparison supports the initial-state claim, not "updates verified". Keep missing certifications and customer quotes out of this copy.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not fabricate proof or guarantees. Do not equate open source with free managed hosting, or compliance documentation with blanket certification.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
