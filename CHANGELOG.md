# Changelog

All notable changes to SPERB will be documented here.

This project follows [Semantic Versioning](https://semver.org/): MAJOR.MINOR.PATCH

- **MAJOR** — Breaking changes to scoring rubric or tier boundaries
- **MINOR** — New dimensions, weighting changes, or significant rubric updates
- **PATCH** — Clarifications, documentation fixes, tooling updates

---

## [1.0.0] — 2026-05-21 — Inaugural Release

### Added
- Full SPERB v1.0 specification — 8 dimensions, 80-point aggregate, 100-point normalised
- Individual dimension specifications: PVS, AIDS, GDS, CPOS, ECS, CSRS, SCES, CITS
- Tier classification system: Platinum, Gold, Silver, Bronze, Unrated
- Inaugural pilot benchmark — 10 AI influencers evaluated (May 2026)
- Per-entity evaluation files for all pilot cohort members
- Interactive CLI evaluator (`tools/evaluate.js`)
- Score calculator and tier classifier (`tools/score.js`)
- Markdown report generator (`tools/report.js`)
- Evaluation template for manual use
- Scoring rubric reference card
- Adoption guide for brands, platforms, and regulators
- Regulatory alignment mapping (EU AI Act, FTC, California BOT Act, ASCI)
- Iteration protocol for SPERB v2.0 development
- Glossary of terms
- Community evaluation submission process
- GitHub issue templates: score challenge, new evaluation, dimension proposal
- CC BY 4.0 open license

### Framework Decisions (recorded for v2.0 reference)
- Equal weighting across all 8 dimensions (10 points each) — differential weighting deferred to v2.0
- Public-data-only evidence requirement — private studio data not counted unless published
- Tanvi Joshi case anchors the Unrated floor as a reference calibration point
- Shayari NHE-01 anchors the Platinum ceiling on GDS and SCES dimensions

---

## [Unreleased] — v1.1.0 (planned)

### Proposed
- PVS scoring rubric update for 2026–2027 generation tool capabilities
- Video corpus scoring guidance (currently under-specified)
- Cultural relativism calibration notes for AIDS dimension
- SPERB score badge generator for evaluated entities

---

## Iteration Protocol

SPERB versions are developed through open consultation. See [`docs/ITERATION_PROTOCOL.md`](docs/ITERATION_PROTOCOL.md) for the full v2.0 development process.

To propose a change, open an issue using the [Dimension Proposal template](.github/ISSUE_TEMPLATE/dimension_proposal.md).
