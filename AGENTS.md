# AGENTS.md

Guidance for AI coding agents working on the Varbase AI Agents recipe.

- Read `CHANGELOG.md` and the merge request and issue comment history first.
- Add an entry under `## [Unreleased]` in `CHANGELOG.md` for every change.
- Commit and merge request titles use the Drupal commit-type format: `{type}: #{issue-id} Summary`.
- Never bump the version or create a tag without the maintainer's approval.
- All configuration lives in `recipe.yml` and the recipe's own `config/`, never in `config/install` or `config/optional`.
