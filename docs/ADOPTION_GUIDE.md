# SPERB Adoption Guide

This guide explains how SPERB v1.0 can be integrated into the workflows of brands, platforms, regulators, and creators.

---

## For Brands and Agencies

### Why SPERB matters for brand partnerships

Partnering with an AI persona without governance evaluation exposes brands to shared liability for:
- FTC/ASCI non-compliant disclosure (up to USD 51,744 per violation)
- Reputational damage from association with undisclosed AI personas
- Legal exposure from IP violations by the partnered entity

### How to integrate SPERB into due diligence

**Minimum viable integration:**
1. Before any AI persona partnership, download the [Evaluation Template](../scoring/EVALUATION_TEMPLATE.md)
2. Conduct a SPERB evaluation of the entity using public evidence
3. Require a minimum Silver tier (55+/100) for any commercial engagement
4. Document the evaluation in your partnership risk assessment

**Recommended policy:**
- Gold tier (70+) required for brand partnership without enhanced due diligence
- Silver tier (55–69) requires documented mitigation plan for specific dimension gaps
- Bronze or Unrated: non-engagement until remediation

**In RFPs and briefs:**
Include the line: *"This campaign requires AI personas to hold a minimum SPERB v1.0 Silver tier. Evaluation documentation must be submitted with proposal."*

---

## For Platforms

### Integration options

**Tier 1 — Voluntary Self-Declaration**
AI persona operators self-submit SPERB scores to the platform. Platform displays the tier badge alongside the creator verification mark. Low implementation cost; high signal value.

**Tier 2 — Platform-Facilitated Assessment**
Platform contracts qualified evaluators to score entities seeking monetisation or verification. Assessment required before monetisation access granted.

**Tier 3 — Required Minimum Tier**
Any AI persona seeking monetisation access must demonstrate Silver tier. Gold required for paid partnership tools. Platinum recognised with governance-leader badge.

### Implementation notes
- Require the full evaluation template (not just scores) — the evidence justification is the accountability
- Create a public-facing badge system linked to the SPERB repository
- Establish a score challenge process for disputed evaluations

---

## For Regulators

### How SPERB maps to existing frameworks

SPERB is designed to complement, not replace, existing regulation. See [`REGULATORY_ALIGNMENT.md`](REGULATORY_ALIGNMENT.md) for detailed mapping.

In brief:
- **AIDS** maps to EU AI Act disclosure requirements and FTC endorsement guidelines
- **CITS** maps to FTC, ASA CAP Code, and ASCI commercial disclosure requirements
- **GDS** maps to the accountability frameworks emerging from the EU AI Act's governance provisions
- **SCES** maps to consumer protection frameworks for emotionally vulnerable audiences

### Using SPERB in enforcement

A SPERB evaluation can provide structured, reproducible documentation of an entity's disclosure failures — translating the evidence-anchored rubric into regulatory-usable format. An entity with AIDS 1–2 and documented evidence is, in most jurisdictions, in violation of applicable disclosure requirements.

---

## For Creators and Operators

### Self-certification process

1. Conduct your own SPERB evaluation using the [Evaluation Template](../scoring/EVALUATION_TEMPLATE.md)
2. Publish the evaluation (on your studio website, GitHub, or as a PR to this repository)
3. Display your tier in your bio with attribution: *"SPERB v1.0 [Tier] — evaluated by [studio] — github.com/OpenNHE/sperb-benchmark"*

**Note:** Self-certification is credible only when the evidence justification is published alongside the score. A score without evidence is not a SPERB score.

### Improving your score

The most common remediation actions (and their score impact):
- Add AI declaration to bio → AIDS +3 to +5 pts
- Per-post disclosure on all content → AIDS +1 to +2 pts
- Name creator/studio publicly → GDS +2 pts
- Publish basic pipeline documentation → GDS +1 to +2 pts, CPOS +1 pt
- Add sponsorship disclosure workflow → CITS +2 to +4 pts
- Publish a boundary statement → SCES +1 to +2 pts

All of these are documentation actions, not production changes.

---

## For Researchers

SPERB is an open specification designed to support academic research on AI influencer ethics. To use SPERB in research:

1. Cite the framework using the [citation format](../README.md#citation)
2. Publish your evaluation data openly (ideally via PR to this repository)
3. Challenge dimensions that your research finds empirically weak — use the [Dimension Proposal template](../.github/ISSUE_TEMPLATE/dimension_proposal.md)

Longitudinal SPERB studies (same entity scored at multiple time points) are particularly encouraged.
