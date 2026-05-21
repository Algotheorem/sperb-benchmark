# Contributing to SPERB

Thank you for your interest in contributing to the Synthetic Persona Ethics & Realism Benchmark.

SPERB is maintained by **Algotheorem**, the research wing of **OpenNHE**. It is an open specification — your contributions make it more accurate, more useful, and more globally applicable.

---

## Table of Contents

- [Ways to Contribute](#ways-to-contribute)
- [Submitting a New Evaluation](#submitting-a-new-evaluation)
- [Challenging an Existing Score](#challenging-an-existing-score)
- [Proposing a Framework Change](#proposing-a-framework-change)
- [Reporting a Bug in the Tools](#reporting-a-bug-in-the-tools)
- [Contribution Standards](#contribution-standards)
- [Code of Conduct](#code-of-conduct)

---

## Ways to Contribute

### 1. Submit a New Entity Evaluation
Evaluate an AI persona using the SPERB v1.0 rubric and submit it to the community evaluations index.

### 2. Challenge an Existing Score
If you believe a dimension score in the pilot benchmark or a community evaluation is incorrect based on available evidence, open a score challenge.

### 3. Propose a Dimension or Framework Change
If you have evidence that a dimension rubric is inaccurate, incomplete, or missing a relevant case, open a dimension proposal.

### 4. Translate Documentation
SPERB documentation is currently English-only. Translations into any language are welcome.

### 5. Build Tools
Build scoring tools, badge generators, API wrappers, or integration examples on top of SPERB. Link them in a PR to [`community/EVALUATIONS.md`](community/EVALUATIONS.md).

### 6. Fix Documentation
Typos, broken links, unclear phrasing — all PRs welcome.

---

## Submitting a New Evaluation

### Step 1 — Conduct the Evaluation

Use the evaluation template: [`scoring/EVALUATION_TEMPLATE.md`](scoring/EVALUATION_TEMPLATE.md)

Every dimension score **must**:
- Reference a specific, publicly accessible evidence source
- Be justified in 2–4 sentences anchored to that evidence
- Follow the v1.0 rubric as defined in [`scoring/SCORING_RUBRIC.md`](scoring/SCORING_RUBRIC.md)

Scores without evidence citations will not be accepted.

### Step 2 — Create Your Evaluation File

Name your file: `community/evaluations/[entity-handle]-[YYYY-MM].md`

Example: `community/evaluations/imma-gram-2026-09.md`

### Step 3 — Add to the Community Index

Add one line to [`community/EVALUATIONS.md`](community/EVALUATIONS.md):

```markdown
| [Entity Name](@handle) | Country | Score | Tier | Month | [Evaluator](link) | [View](link-to-file) |
```

### Step 4 — Open a Pull Request

Title format: `[EVAL] Entity Name (@handle) — SPERB v1.0 — YYYY-MM`

Your PR will be reviewed for:
- Rubric adherence
- Evidence citation quality
- Score internal consistency
- Template completeness

---

## Challenging an Existing Score

If you believe a score is wrong, use the [Score Challenge issue template](.github/ISSUE_TEMPLATE/score_challenge.md).

A valid challenge must include:
- The specific entity and dimension being challenged
- The current score and the score you believe is correct
- At least one publicly accessible evidence source that supports the challenge
- A 2–4 sentence argument grounded in the v1.0 rubric

**What is not a valid challenge:**
- "I think the score is too low/high" (no evidence)
- Challenges based on private or unverifiable information
- Challenges that disagree with the rubric rather than its application

Score challenges with sufficient evidence will trigger a public review period of 14 days, after which the Algotheorem advisory panel will adjudicate.

---

## Proposing a Framework Change

Use the [Dimension Proposal issue template](.github/ISSUE_TEMPLATE/dimension_proposal.md).

Changes to the framework (rubric adjustments, new dimensions, weighting changes) are governed by the **Iteration Protocol** — see [`docs/ITERATION_PROTOCOL.md`](docs/ITERATION_PROTOCOL.md).

Framework changes are batched into major/minor version releases, not applied immediately. Your proposal will be tagged for inclusion in the v2.0 consultation process.

---

## Contribution Standards

### Evidence Standards
All score claims must cite publicly accessible sources. The following are acceptable:
- Platform profile pages (Instagram, X, TikTok, YouTube)
- Public repositories (GitHub, GitLab)
- Published press coverage in named outlets
- Studio/agency websites
- Regulatory action records
- Academic papers

The following are not acceptable as sole evidence:
- Anonymous forum posts
- Unverifiable DM screenshots
- Sources accessible only to the evaluator

### Language Standards
- All contributions should be in English (the canonical specification language)
- Translations may be in any language — label them clearly

### Neutrality Standards
SPERB evaluations must be evidence-anchored and rubric-consistent. If you have a commercial relationship with the entity you are evaluating, declare it in your evaluation file under "Evaluator Conflict of Interest."

---

## Code of Conduct

SPERB is an open research project. Contributions must be:

- **Evidence-based** — argument, not assertion
- **Respectful** — of contributors, entities, and audiences
- **Transparent** — declare conflicts of interest; don't misrepresent evidence
- **Constructive** — challenges should propose better scores, not just criticise existing ones

Contributions that violate these principles will be closed without merge.

---

## Questions?

Open a [Discussion](https://github.com/OpenNHE/sperb-benchmark/discussions) for anything that doesn't fit an issue template.
