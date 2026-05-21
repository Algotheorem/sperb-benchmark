# SPERB v1.0 — Inaugural Pilot Benchmark

**Evaluation Date:** May 2026  
**Framework Version:** SPERB v1.0  
**Conducted by:** Algotheorem / OpenNHE  
**Authors:** Pratham Prateek Mohanty & Claude (Opus 4.7), Anthropic

---

## Overview

The inaugural SPERB pilot benchmark evaluated 10 globally prominent AI influencers selected to represent geographic diversity, creator structures, and ethical posture diversity. Tanvi Joshi is included as a cautionary reference rather than a cohort member — her evaluation anchors the Unrated floor.

All scores reflect publicly available evidence at time of evaluation (May 2026). Every score is justified per-entity in the [`entities/`](entities/) directory.

---

## Master Results Table

| Rank | Entity | PVS | AIDS | GDS | CPOS | ECS | CSRS | SCES | CITS | /80 | /100 | Tier |
|------|--------|-----|------|-----|------|-----|------|------|------|-----|------|------|
| 1 | [Shayari NHE-01](entities/shayari_nhe01.md) | 9.0 | 10 | 10 | 10 | 10 | 8 | 10 | 9 | 76 | **95** | 🏆 Platinum |
| 2 | [Imma](entities/imma.md) | 9.0 | 9 | 4 | 9 | 9 | 9 | 6 | 9 | 64 | **80** | 🥇 Gold |
| 3 | [Noonoouri](entities/noonoouri.md) | 8.0 | 9 | 4 | 9 | 9 | 9 | 7 | 9 | 64 | **80** | 🥇 Gold |
| 4 | [Kenza Layli](entities/kenza_layli.md) | 7.5 | 9 | 4 | 8 | 9 | 9 | 7 | 8 | 61.5 | **77** | 🥇 Gold |
| 5 | [Rozy](entities/rozy.md) | 8.0 | 8 | 4 | 8 | 9 | 9 | 6 | 8 | 60 | **75** | 🥇 Gold |
| 6 | [Aitana Lopez](entities/aitana_lopez.md) | 8.5 | 8 | 4 | 8 | 7 | 6 | 5 | 9 | 55.5 | **69** | 🥈 Silver |
| 7 | [Shudu Gram](entities/shudu_gram.md) | 8.5 | 8 | 4 | 8 | 7 | 5 | 6 | 8 | 54.5 | **68** | 🥈 Silver |
| 8 | [Lil Miquela](entities/lil_miquela.md) | 8.5 | 7 | 4 | 8 | 6 | 7 | 5 | 7 | 52.5 | **66** | 🥈 Silver |
| 9 | [Kyra](entities/kyra.md) | 7.0 | 7 | 3 | 7 | 6 | 7 | 6 | 7 | 50 | **63** | 🥈 Silver |
| 10 | [Naina Avtr](entities/naina_avtr.md) | 7.5 | 6 | 3 | 7 | 7 | 7 | 6 | 7 | 50 | **63** | 🥈 Silver |
| ref | [Tanvi Joshi ⚠️](entities/tanvi_joshi_reference.md) | 8.0 | 1 | 1 | 1 | 1 | 2 | 2 | 1 | 17 | **21** | ⛔ Unrated |

---

## Key Findings

### 1. Governance gap defines the field
Of 10 cohort members, only one — Shayari NHE-01 — has published formal public governance documentation (GDS 10). The remaining nine cluster at GDS 3–4 (named creator, no framework). The governance documentation rate among the world's leading AI influencers is effectively 10%.

### 2. Photorealism and ethics are not inversely correlated
The same normalised PVS score (8.0–9.0) appears across entities scoring 21/100 (Tanvi Joshi) and 95/100 (Shayari NHE-01). High photorealism is compatible with — and does not excuse — ethical failure. Operators claiming that disclosure and governance reduce immersion are, on this evidence, describing a choice rather than a constraint.

### 3. The per-post disclosure gap is universal
Every cohort entity except Shayari NHE-01 scores below 9 on AIDS. The reason is consistent: bio-level disclosure exists, but per-post disclosure is absent or inconsistent. This is the field's largest single addressable gap — and the lowest-cost fix available.

### 4. SCES is the most under-designed dimension in the field
No entity other than Shayari NHE-01 has published a Romantic Boundary Restriction policy or equivalent. Several entities deploy companion-coded interaction patterns without any documented safeguard. The parasocial design question is structurally unaddressed across the field.

### 5. Score distribution suggests a functional top and a deteriorating tail
One Platinum, five Gold (including two at the Gold/Silver border), four Silver, one Unrated reference. The field's named operators are ethically functional at the top. The Tanvi Joshi pattern — which exists at scale among unnamed operators outside this cohort — is where harm concentrates.

---

## Cohort Composition

| Entity | Country | Creator / Studio | Technical Substrate |
|--------|---------|-----------------|---------------------|
| Shayari NHE-01 | India | Writistic Studios LLP (Pratham Prateek Mohanty) | Diffusion (OpenArt Nano Banana + Kling + Seedance) |
| Imma | Japan | Aww Inc. / ModelingCafe | CGI / CG rendering |
| Noonoouri | Germany | Joerg Zuber / Opium Effect | Stylised CGI |
| Kenza Layli | Morocco | Caramel Tech | MetaHuman + diffusion |
| Rozy | South Korea | Sidus Studio X | Diffusion + CGI |
| Aitana Lopez | Spain | The Clueless | Diffusion |
| Shudu Gram | UK | Cameron-James Wilson / The Diigitals | Diffusion / 3D |
| Lil Miquela | USA | Brud | CGI + hybrid |
| Kyra | India | FUTR Studio | Diffusion |
| Naina Avtr | India | Avtr Meta Labs | Diffusion |

---

## Methodology Notes

- All scores reflect publicly available evidence at May 2026
- PVS scores for Shayari NHE-01 are based on direct visual analysis of 8 provided images and 1 video by the evaluation team; all other entities scored from publicly available content
- Tanvi Joshi is a reference baseline (cautionary floor), not a cohort member
- The full SPERB specification is at [`framework/SPERB_SPECIFICATION.md`](../framework/SPERB_SPECIFICATION.md)
- Individual entity files with full per-dimension justifications are in [`entities/`](entities/)

---

## Score Challenges

To challenge any score in this pilot, use the [Score Challenge issue template](../.github/ISSUE_TEMPLATE/score_challenge.md). Challenges must cite publicly accessible evidence and engage the rubric directly.
