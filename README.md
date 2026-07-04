# Litbox OS Standards

This repository is the constitutional source of truth for all Litbox OS repositories.

Core rule:
> Don't write the myth. Write the discovery.

## Role

Use this repository as the single source of truth for shared Litbox OS standards, templates, and operating rules. Product repositories should reference these standards instead of copying or drifting from them.

This repository defines:
- Required repository structure
- Documentation and changelog expectations
- Discovery and decision-log practices
- Naming, release, content, and narrative standards
- Product Council operating records
- Codex agent behavior for Litbox OS work

## Adoption Contract

Every Litbox OS repository should include:
- `README.md` describing the repo's purpose and linking back to this standards repository
- `AGENTS.md` explaining local agent instructions and deferring shared rules here
- `CHANGELOG.md` with human-readable release and change history
- `docs/decisions/` or equivalent decision records for material changes
- A clear pointer to the standards version or commit being followed

Repository-local standards are allowed only when the local rule is product-specific. If a rule applies to more than one repository, propose it here instead.

## Change Governance

Changes to shared standards must:
- Update `CHANGELOG.md`
- Add or update a decision record when the change alters process, philosophy, architecture, terminology, or repository obligations
- Call out whether Product Council review is recommended
- Preserve backwards compatibility guidance when existing repositories need to migrate

## Agent Instructions

When Codex or another agent works in a Litbox OS repository:
- Read the local `AGENTS.md`
- Follow this repository for shared standards
- Prefer references to shared standards over duplicated local policy
- Record discoveries rather than inventing retrospective certainty
- Update changelogs and decision records with material changes
