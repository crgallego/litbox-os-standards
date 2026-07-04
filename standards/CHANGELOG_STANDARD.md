# Changelog Standard

Every merged change updates CHANGELOG.md.

## Purpose

Changelogs preserve what changed, why it matters, and how downstream Litbox OS repositories should respond.

## Required Sections

Use reverse chronological order. Each release or unreleased section should group entries under clear labels when useful:
- Added
- Changed
- Fixed
- Deprecated
- Removed
- Migration Notes
- Product Council Notes

## Entry Rules

Each material entry should:
- Be understandable without reading the diff
- Name the affected standard, template, example, or process
- Mention migration impact when existing repositories need to react
- Link or refer to the relevant decision record when the change alters governance

## Standards Repository Rule

This repository's `CHANGELOG.md` must be updated in the same change that modifies a standard.
