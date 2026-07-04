# Standards Repository Governance

Status: Accepted

Date: 2026-07-04

## Decision

The Litbox OS Standards repository is the canonical source of truth for shared repository structure, documentation expectations, changelog practice, discovery handling, decision records, and agent behavior across Litbox OS repositories.

Product repositories should reference this repository instead of duplicating shared standards locally.

## Context

Litbox OS needs a durable operating layer that can be applied across multiple repositories without drift. The initial standards were directionally correct but too brief to serve as a self-contained adoption contract.

## Rationale

Centralizing shared standards makes changes easier to review, version, migrate, and teach. It also protects the core Litbox OS practice of recording discovery instead of polishing uncertainty into after-the-fact mythology.

## Alternatives Considered

- Keep standards minimal and rely on contributor interpretation.
- Duplicate standards into each product repository.
- Treat each repository as fully independent.

## Consequences

- Standards changes require changelog updates.
- Material governance changes require decision records.
- Product repositories should link back to this repository for shared rules.
- Local exceptions must be explicit and product-specific.

## Revisit Conditions

Revisit this decision if the standards repository becomes too broad, if product repositories need versioned standard bundles, or if shared rules become difficult to apply without product-specific interpretation.

## Product Council Review

Recommended. This change affects Litbox OS process, repository obligations, and the philosophy of narrative preservation.
