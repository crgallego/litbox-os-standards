# Repository Standard

Every repo contains README, AGENTS, CHANGELOG and references shared standards.

## Required Files

Every Litbox OS repository must contain:
- `README.md`
- `AGENTS.md`
- `CHANGELOG.md`
- A decision log location, preferably `docs/decisions/`
- Links or references to the current Litbox OS Standards repository

## Source of Truth

Shared rules live in this standards repository. Product repositories should only define local rules for product-specific behavior, runtime setup, deployment, or domain context.

If a local rule would be useful to another Litbox OS repository, promote it here rather than duplicating it.

## Local README Requirements

Each repository README should explain:
- The repository's purpose
- Its owner or accountable team
- How it relates to Litbox OS
- Which shared standards it follows
- How to run, test, or validate the project when applicable

## Local AGENTS Requirements

Each repository `AGENTS.md` should:
- Link to this standards repository
- Name any local exceptions or additions
- Avoid restating shared standards unless a short pointer is needed for safety
- Tell agents where decisions, discoveries, and changelog entries belong

## Readiness Criteria

A repository is standards-ready when another contributor or agent can:
- Understand the repo's purpose from the README
- Find the shared standards without searching
- Identify how changes should be documented
- Make a small change and know where to record decisions, discoveries, and release notes
