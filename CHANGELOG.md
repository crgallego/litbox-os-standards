# Changelog

## Unreleased

### Added
- Added a repository adoption contract to define how Litbox OS repositories should reference this standards repository.
- Added change governance requirements for standards updates, including decision records and Product Council review recommendations.
- Added decision record `2026-07-04-standards-repository-governance.md` establishing this repository as the canonical shared standards source.
- Added `.gitignore` rules to keep local machine files and chat downloads out of the standards repository.

### Changed
- Hardened `MASTER_CODEX_PROMPT.md` with review expectations for standards readiness.
- Expanded `AGENTS.md` with operating rules and a review checklist for agent work.
- Expanded repository, changelog, decision-log, Git, documentation, and discovery standards with concrete adoption and governance requirements.
- Aligned reusable templates with the expanded standards so downstream repositories can adopt the contract directly.

### Migration Notes
- Litbox OS repositories should link to this standards repository instead of duplicating shared standards locally.
- Product repositories should keep only product-specific exceptions in their local `AGENTS.md` files.
- Existing repositories should add or verify `README.md`, `AGENTS.md`, `CHANGELOG.md`, and a decision-log location.

### Product Council Notes
- Product Council review is recommended because this change affects process, repository obligations, and narrative governance.

## v1.0.0
- Initial standards repository.
