# Audience research playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Compare segments by source-to-consumer workflow, correctness/freshness need, access authority, and operational ownership. Distinguish analyst interest, engineering evaluation, platform review, and budget authority.

## Task-specific method

Segment by source-to-destination workflow, correctness and freshness requirements, regulated or sensitive data, operational ownership, and integration burden. Analysts and platform buyers may value different outcomes.

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

Deliver: An evidence-backed segment table, role map, ranked adoption barriers, audience language with sources, and a practical validation plan. Include what would falsify the recommended segment.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

A public complaint is not purchase intent. Do not turn a few accessible commenters into a population estimate or invent interview quotations.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
