# AGENTS

Maintain shared standards only.

Every change should favor reuse, clarity, versioning, and narrative preservation.

## Operating Rules

- Treat this repository as canonical for shared Litbox OS behavior.
- Do not add product-specific implementation rules unless they are reusable across multiple repositories.
- Prefer links and references from product repos back to this repository instead of copying standard text into each repo.
- When a shared standard changes, update `CHANGELOG.md` and add or update a decision record.
- Recommend Product Council review when changes affect philosophy, process, naming, narrative strategy, or repository obligations.
- Keep examples and templates aligned with the standards they demonstrate.

## Review Checklist

Before finishing a change, verify:
- The changed standard states who must follow it.
- The changed standard explains when it applies.
- Migration impact is clear for existing Litbox OS repositories.
- `CHANGELOG.md` records the change.
- A decision record exists for material governance changes.
