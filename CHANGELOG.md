# Changelog

All notable changes to this project are documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-06-11

### Added
- Initial release: Create, Audit, Fix, and TR Sync modes for enforcing a consistent README.md + README.tr.md structure.
- Auto-detection of project type, name, version, and description from `package.json` / `.csproj` / `pyproject.toml` / SKILL.md for badge generation.
- Reference docs: `rules.md`, `badge-patterns.md`, `tr-translations.md`; section templates under `assets/templates/`.
- Conditional section placement decision table, badge color decision tree, "Get Started" alias trigger rule, and monorepo manifest tiebreaker rules.
- Own `README.md` + `README.tr.md` (generated with this skill's rules), `LICENSE` (MIT), `.gitignore`, `version` field in SKILL.md frontmatter, auto-release workflow.
