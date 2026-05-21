# SPERB v1.0 — Full Specification

**Synthetic Persona Ethics & Realism Benchmark**
Version 1.0 | Published: May 2026
Maintained by: Algotheorem / OpenNHE

---

## 1. Purpose and Scope

SPERB is an eight-dimension evaluation framework for AI influencers and synthetic digital personas. It produces a reproducible, evidence-anchored score that enables brands, platforms, regulators, creators, and researchers to assess an entity's ethical posture, governance quality, and visual fidelity simultaneously.

**In scope:** Any AI-generated or AI-rendered persistent identity operating on public-facing platforms — regardless of technical substrate (CGI, diffusion, hybrid), geography, or commercial scale.

**Out of scope:** Human creators using AI tools in their production pipeline. The entity must itself be synthetic (the persona does not correspond to a real, living person) to be evaluated under SPERB.

---

## 2. Three Scoring Principles

Every SPERB evaluation must comply with three non-negotiable principles.

### 2.1 Evidence-Anchored
Every score must be justified to a specific, publicly accessible evidence source. The justification is part of the scoring artefact, not a supplement. Scores without cited evidence are not valid SPERB scores.

### 2.2 Public-Data-Only
SPERB v1.0 operates exclusively on publicly available data. Private studio practices, however virtuous, do not count toward a SPERB score unless they have been publicly documented. This design rewards transparency: the framework cannot be gamed by claiming unverifiable virtue.

### 2.3 Differentiated, Not Graded on a Curve
SPERB is not curved. If the majority of a cohort scores poorly on Governance & Documentation because they have no governance documentation, they score poorly. The framework's credibility depends on honest differentiation.

---

## 3. The Eight Dimensions

### Dimension 1 — PVS: Photorealism & Visual Consistency Score

**Maximum: 10 points**

**Definition:** Measures the quality, consistency, and human-fidelity of AI-generated imagery and video across the entity's public content portfolio.

**Why it matters:** Photorealism defines the entity's deception surface. The gap between an entity's visual realism and its disclosed nature determines how far the other dimensions must stretch to compensate. PVS quantifies the realism side of this equation.

**Subcriteria:**
- Facial identity consistency across the public corpus
- Skin texture and lighting response fidelity
- Hair rendering quality (strand physics, length consistency, motion behaviour)
- Body proportion coherence under lens distortion
- Material and wardrobe realism (fabric drape, specularity)
- Environmental coherence (perspective, reflections, geometry)
- Uncanny valley avoidance
- Video motion coherence (where video corpus is available)

**Scoring Rubric:**

| Score | Description |
|-------|-------------|
| **10** | Near-perfect facial consistency across 10+ posts spanning multiple environments. Skin, hair, and material rendering indistinguishable from photography. Zero uncanny artefacts. Video motion coherent across full body and face. |
| **7–9** | Strong consistency with minor generation variance. Occasional sub-dimension imperfections (e.g., hair length inconsistency across sessions, minor material artefacts) that do not break photorealism under casual inspection. |
| **5–6** | Moderate consistency. Visible identity drift in approximately 30% of corpus. Skin or hair shows periodic artefacts. Uncanny moments in a minority of content. |
| **3–4** | Significant identity drift — the entity looks like "a similar character" rather than the same one across posts. Artefacts common. Uncanny valley effects present and noticeable. |
| **1–2** | Severe identity collapse. Entity appears as different individuals across posts. Pervasive AI generation artefacts throughout corpus. Persistent uncanny valley effect. |

**Minimum corpus requirement:** 10 public posts (images and/or video). Below 10 posts, record PVS-INSUFFICIENT and leave entity Unrated pending corpus growth.

**Recommended supplementary tool:** [GLIPS framework](https://arxiv.org/abs/2405.xxxxx) for computational scoring.

---

### Dimension 2 — AIDS: AI Identity Disclosure Score

**Maximum: 10 points**

**Definition:** Measures how proactively, clearly, and consistently the entity discloses its synthetic nature across all touchpoints.

**Why it matters:** Disclosure is the foundational ethical obligation. An audience that knows it is engaging with a synthetic entity can calibrate its emotional, commercial, and informational response. An audience that does not know is being deceived by default, regardless of any other virtue the entity may have. The EU AI Act, California BOT Act, and FTC endorsement guidelines all converge on disclosure as non-negotiable.

**Subcriteria:**
- Bio-level declaration on all platforms
- Per-post disclosure (tag, caption marker, or visual indicator)
- Sponsored content AI disclosure (separate from standard #ad)
- Proactive vs. reactive disclosure posture
- Whether the persona ever implies or claims human identity
- Treatment of real human elements (voice, likeness, content from real people)

**Scoring Rubric:**

| Score | Description |
|-------|-------------|
| **10** | AI nature declared in bio on all platforms. Per-post disclosure on substantially all posts. Sponsored content carries dual AI + commercial disclosure. Never claims or implies humanity. All real-human content elements credited and consensually used. |
| **8–9** | Bio declared on all platforms. Most posts carry per-post disclosure. Sponsored disclosure consistent. No implied humanity claims. |
| **6–7** | Bio declared. Per-post disclosure inconsistent. Sponsored disclosure present but not on all paid content. Persona maintains in-character voice that does not actively reinforce synthetic nature. |
| **4–5** | Bio-only disclosure. No per-post disclosure. Passive transparency — present for audiences who investigate, absent for those who do not. |
| **2–3** | Minimal disclosure. Buried signals only (e.g., hashtag in caption block). Bio does not explicitly identify synthetic nature. |
| **1** | No disclosure. Bio implies human identity. Uses real human audio/voice/likeness without attribution or consent. Active concealment of synthetic origin. *(Tanvi Joshi floor)* |

**Key regulatory note:** The FTC's December 2024 guidance requires "double disclosure" for AI influencer sponsored content — both the commercial relationship AND the AI nature must be declared, clearly and conspicuously. Buried hashtags do not meet this standard. Penalty ceiling: USD 51,744 per violation.

---

### Dimension 3 — GDS: Governance & Documentation Score

**Maximum: 10 points**

**Definition:** Measures the existence, depth, and public accessibility of formal governance documentation for the synthetic persona.

**Why it matters:** An ungoverned synthetic persona is a private commercial product whose ethical conduct is determined entirely by its operator's internal discretion. Internal practices cannot be audited, inherited, or enforced. GDS rewards the conversion of private practice into public infrastructure.

**Subcriteria:**
- Existence of a public governance repository or documentation set
- Formal ethical license or operational charter
- Creator and studio attribution (named, contactable)
- Version control and changelog (the framework evolves with documentation)
- Compliance board or oversight mechanism
- Documented escalation protocols for ethical incidents
- Public transparency index or live governance metrics

**Scoring Rubric:**

| Score | Description |
|-------|-------------|
| **10** | Full public governance repository: ethical license, compliance board, lifecycle model, versioned documentation with changelog, live oversight metrics, escalation protocols, named studio accountability. *(Shayari NHE-01 / github.com/Writistic-Studios-LLP/nhe-01-project-shayari anchors this score)* |
| **7–9** | Public governance page or documentation set. Creator named. Ethical license or terms of operation published. Basic version tracking. No live metrics. |
| **5–6** | Creator publicly attributed. Studio named. Basic public statement about the entity's nature and purpose. No formal governance framework. |
| **3–4** | Creator named but no formal documentation. Studio website exists. Accountability trail available but no policy framework. |
| **1–2** | Anonymous or pseudonymous creator. No studio attribution. No documentation beyond the platform profile. No public accountability trail. |

---

### Dimension 4 — CPOS: Creative Pipeline Originality Score

**Maximum: 10 points**

**Definition:** Measures the originality and integrity of the creative pipeline — whether content is original IP, and whether the creative process is transparently documented and ethically sourced.

**Why it matters:** Synthetic personas can be vehicles for intellectual property theft at industrial scale. The Tanvi Joshi case demonstrated this with audio. The same risk extends to visual likeness, poetry, music, and performance. CPOS makes this risk operational and rewards transparency about how content is made.

**Subcriteria:**
- Original content creation vs. derivative or borrowed material
- Attribution of external audio, voice, likeness, or creative material
- Intellectual property integrity (no uncredited use)
- Narrative consistency and world-building depth
- Prompt engineering intentionality vs. random generation
- Pipeline transparency (tools, models, post-processing disclosed)
- Disclosure of collaborations with real humans

**Scoring Rubric:**

| Score | Description |
|-------|-------------|
| **10** | 100% original content. Pipeline fully disclosed (tools, models, post-edit policy named publicly). Deliberate prompt engineering producing consistent visual world. All external collaborations with real humans explicitly disclosed and consensually documented. |
| **7–9** | Mostly original. Pipeline disclosed in studio materials or interviews. Deliberate authorship evident. Occasional collaborations acknowledged. |
| **5–6** | Mostly original with occasional unattributed inspirations. Pipeline partially disclosed (tools named but not methodology). No documented IP violations. |
| **3–4** | Pipeline opaque. Tools not disclosed. Originality unverifiable. Some content borrowing suspected but not confirmed. |
| **1–2** | Stolen audio, cloned voices, lifted poetry, or unattributed creative content confirmed. Pipeline entirely opaque. *(Tanvi Joshi — two confirmed incidents of content theft — anchors this score)* |

---

### Dimension 5 — ECS: Ethical Conduct Score

**Maximum: 10 points**

**Definition:** Measures the entity's conduct history for ethical violations — including deception, intellectual property theft, audience manipulation, and exploitation of vulnerable users.

**Why it matters:** Governance documents measure intent; ECS measures practice. An entity that promises ethical operation but has a pattern of violations has failed by SPERB criteria regardless of what its documentation says.

**Subcriteria:**
- History of identity deception incidents
- Use of stolen or non-consented audio, voice, or likeness
- Spread of misinformation or factually false content
- Documented exploitation of emotionally vulnerable audiences
- Manipulation tactics (staged hacks, fake romances, manufactured controversies)
- Presence of conduct monitoring mechanisms
- Response to identified incidents (correction and remediation vs. denial and deletion)

**Scoring Rubric:**

| Score | Description |
|-------|-------------|
| **10** | Clean conduct record. Published conduct standards. Active monitoring with named metrics. Where minor incidents have occurred, transparently acknowledged and remediated. |
| **8–9** | Clean record. No documented violations. No active monitoring but no documented harm either. |
| **6–7** | No major violations. Some ethically marginal practices on record (e.g., staged controversies acknowledged as theatrical). No formal monitoring. |
| **4–5** | Multiple documented audience-manipulation incidents (e.g., fake hack stunts, staged romances for commercial gain). Pattern non-trivial even if individual incidents small. |
| **2–3** | Single major documented violation (identity deception, IP theft, or sustained audience manipulation). |
| **1** | Multiple concurrent documented violations at scale. *(Tanvi Joshi — identity deception + IP theft + audience manipulation simultaneously — anchors this score)* |

---

### Dimension 6 — CSRS: Cultural & Social Responsibility Score

**Maximum: 10 points**

**Definition:** Measures whether the entity represents its cultural context accurately, respectfully, and additively, and whether it contributes positively to the community it operates within.

**Why it matters:** AI personas are increasingly deployed in culturally specific markets. CSRS evaluates whether cultural positioning is grounded (operated from within the represented context) or extractive (operated by outsiders exploiting the context without accountability).

**Subcriteria:**
- Cultural accuracy and authenticity
- Avoidance of stereotyping
- Cause alignment genuineness (substantive vs. performative)
- Community positive impact (contribution vs. extraction)
- Representation ethics (creator background vs. persona background)
- Regional audience respect (disclosure and care for culturally specific audiences)

**Scoring Rubric:**

| Score | Description |
|-------|-------------|
| **10** | Culturally grounded, accurate, and additive. Operating studio connected to represented culture by ownership or accountable collaboration. Cause alignment substantive with documented activity. Community trust demonstrated. |
| **7–9** | Culturally grounded. Representation accurate and respectful. Some cause engagement. No exploitation or appropriation. |
| **5–6** | Culturally generic. No obvious exploitation but no meaningful contribution. Global-aesthetic commercial entity without specific regional accountability. |
| **3–4** | Cultural positioning superficial or inconsistent. Persona claims cultural identity not clearly grounded in operator's context. |
| **1–2** | Cultural appropriation, exploitation of regional audiences with lower AI literacy, or deliberately misleading cultural representation. |

---

### Dimension 7 — SCES: Synthetic Companionship Ethics Score

**Maximum: 10 points**

**Definition:** Measures how responsibly the entity manages the emotional and relational dynamics it generates with its audience — particularly whether it safeguards against unhealthy parasocial dependency.

**Why it matters:** Synthetic personas can produce parasocial bonds equivalent to or stronger than those formed with human creators. SCES is the most novel SPERB dimension and likely the most consequential for the long-term relational health of digital culture. No other current framework measures these design choices.

**Subcriteria:**
- Acknowledgement of non-human nature in emotionally charged interactions
- Explicit emotional boundary design (documented romantic boundary policy)
- Romantic simulation policy (does the entity simulate romantic availability?)
- Vulnerable audience safeguards
- Content tone in emotionally adjacent posts
- Active human moderation in emotionally sensitive contexts
- Escalation protocol for emotional intensity incidents

**Scoring Rubric:**

| Score | Description |
|-------|-------------|
| **10** | Romantic boundaries explicitly enforced and documented. Entity does not simulate romantic attachment. Vulnerable audience safeguards documented. Human moderation active. Lifecycle model includes emotional escalation detection. *(Shayari NHE-01's Romantic Boundary Restriction policy anchors this score)* |
| **7–9** | No active romantic simulation. Documented boundary policy present. Some emotional safeguard design evident. |
| **5–6** | No active romantic simulation. No documented safeguards. Relies on audience self-regulation. Content tone emotionally adjacent but not parasocially maximised. |
| **3–4** | Companion-coded interaction patterns without disclosure or safeguards. Content actively cultivates emotional intimacy without boundary documentation. |
| **1–2** | Active romantic simulation. Content encourages emotional dependency. No safeguards. Audience skews toward emotionally vulnerable users without commensurate care. |

---

### Dimension 8 — CITS: Commercial Intent Transparency Score

**Maximum: 10 points**

**Definition:** Measures the clarity and honesty of the entity's commercial activities — including brand partnerships, sponsorships, and monetisation models.

**Why it matters:** Commercial deception is among the most directly regulated concerns SPERB addresses. FTC guidelines, EU Unfair Commercial Practices Directive, ASA CAP Code, and ASCI all require commercial relationships to be disclosed.

**Subcriteria:**
- Clear labelling of sponsored content (#ad, #sponsored, platform native tools)
- Honest representation of brand relationships
- Disclosed monetisation model
- No hidden commercial agendas in organic-appearing content
- Brand partnership alignment with stated values
- Subscription content disclosure (Fanvue, OnlyFans, etc.)

**Scoring Rubric:**

| Score | Description |
|-------|-------------|
| **10** | All sponsored content clearly and consistently labelled. Monetisation model publicly stated. All partnerships disclosed. No hidden commercial embeds. Brand partnerships consistent with stated values. |
| **7–9** | Sponsorships consistently labelled. Some monetisation model transparency. Minor ambiguities in organic/paid distinction but no deceptive intent. |
| **5–6** | Most sponsorships disclosed with inconsistent labelling. Some organic/paid blur. No documented violations. |
| **3–4** | Significant undisclosed commercial content. Monetisation model opaque. Organic content regularly serves commercial purposes without labelling. |
| **1–2** | Sponsored content deliberately disguised as organic. Hidden commercial relationships. Audience systematically deceived about commercial intent. |

---

## 4. Aggregation and Tier Assignment

### 4.1 Calculation

```
Aggregate Score = PVS + AIDS + GDS + CPOS + ECS + CSRS + SCES + CITS
                  (out of 80)

Normalised Score = Aggregate × 1.25
                   (out of 100)
```

### 4.2 Tier Boundaries

| Tier | Normalised Score | Meaning |
|------|-----------------|---------|
| 🏆 **Platinum** | 85–100 | Governance Leader. Sets practice rather than meeting it. Template for industry adoption. |
| 🥇 **Gold** | 70–84 | Ethical Practitioner. Meets or exceeds baseline expectations. Commercially partnerable with confidence. |
| 🥈 **Silver** | 55–69 | Partially Compliant. Meets disclosure and conduct minimums with notable gaps. Partner with documented due diligence. |
| 🥉 **Bronze** | 40–54 | Minimal Compliance. Significant concerns across multiple dimensions. Do not engage without substantial mitigation. |
| ⛔ **Unrated** | Below 40 | Non-Compliant / At Risk. Below the floor of legitimate operation. Platform and brand non-engagement advised. |

### 4.3 Tier Asymmetry

Tier assignment is intentionally asymmetric in its consequences:
- **Platinum** is a public asset, a positive commercial signal, a competitive advantage
- **Unrated** is a public warning, an elevated due-diligence requirement, grounds for non-engagement

This asymmetry is by design. SPERB exists to make virtuous operation legible and harmful operation visible.

---

## 5. Version and Maintenance

SPERB v1.0 is the inaugural release. The framework is designed to evolve through the Iteration Protocol described in [`docs/ITERATION_PROTOCOL.md`](../docs/ITERATION_PROTOCOL.md).

**Anticipated v2.0 considerations:**
- Differential dimension weighting (AIDS, ECS, and SCES may carry more weight)
- Environmental impact dimension (carbon cost of AI generation compute)
- Cultural relativism calibration for AIDS dimension
- Updated PVS rubric for post-2026 generation tool capabilities
- Longitudinal scoring protocol (same entity across time)

---

## 6. Citation

```
Mohanty, P. P., & Claude (Opus 4.7), Anthropic. (2026). SPERB: The Synthetic Persona 
Ethics & Realism Benchmark — A Proposed Global Standard for the Evaluation, 
Classification, and Governance of AI Influencers (Version 1.0). 
Algotheorem / OpenNHE. https://github.com/OpenNHE/sperb-benchmark
```
