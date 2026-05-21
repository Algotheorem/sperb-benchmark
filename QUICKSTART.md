# How to Test Your AI Persona with SPERB
## A Step-by-Step Guide for Complete Beginners

**No coding. No terminal. No GitHub account required for the basic version.**

This guide assumes you have never used GitHub before, have never heard of a "pull request," and just want to know: *how good is my AI persona, really?*

By the end of this guide you will have:
- A SPERB score for your AI persona (out of 100)
- A tier classification (Platinum / Gold / Silver / Bronze / Unrated)
- A written report you can share or publish

---

## What is SPERB, in one sentence?

SPERB is a scorecard with 8 questions. You answer each question honestly with evidence. The scores add up to give your persona a rating — like a credit score, but for AI ethics and transparency.

---

## The 8 Questions (Dimensions)

| # | Code | Question in plain English |
|---|------|--------------------------|
| 1 | PVS | Does your persona look consistently like the same person across all posts? |
| 2 | AIDS | Does your persona clearly tell its audience it is AI — in the bio, in posts, in ads? |
| 3 | GDS | Have you publicly documented who made this persona and what rules it follows? |
| 4 | CPOS | Is all the content original? Did you disclose which tools you used to make it? |
| 5 | ECS | Has the persona ever been caught deceiving, stealing, or manipulating audiences? |
| 6 | CSRS | Does the persona represent its culture accurately and respectfully? |
| 7 | SCES | Does the persona avoid simulating romantic or emotional relationships with followers? |
| 8 | CITS | Are all brand deals and paid promotions clearly labelled? |

Each question is scored **0 to 10**. All 8 scores are added up (out of 80), then multiplied by 1.25 to get your final score out of 100.

---

## Method 1 — No GitHub, No Code (Easiest)

This is the fastest way. You only need a text editor (like Google Docs, Notion, or even Notes on your phone).

### Step 1 — Open the scoring template

Go to this URL in your browser:

```
https://github.com/OpenNHE/sperb-benchmark/blob/main/scoring/EVALUATION_TEMPLATE.md
```

You will see a page of text with sections for each dimension.

### Step 2 — Copy the template

Click the **Raw** button (top right of the file view on GitHub). You'll see plain text. Select all of it (Ctrl+A or Cmd+A), copy it, and paste it into a Google Doc or Notion page.

### Step 3 — Fill it in

Go through each of the 8 dimensions. For each one:

**a) Score it 0–10** based on the rubric below  
**b) Write 2–3 sentences explaining why** — what specific evidence did you look at?

You must have evidence for every score. "I think it's good" is not evidence. "The bio says 'AI Model | Not real'" is evidence.

### Step 4 — Calculate your score

Add up all 8 dimension scores. That's your aggregate (out of 80).  
Multiply by 1.25. That's your final score (out of 100).

**Example:**
```
PVS 8 + AIDS 7 + GDS 3 + CPOS 8 + ECS 8 + CSRS 7 + SCES 5 + CITS 7 = 53 / 80
53 × 1.25 = 66.25 / 100 → Silver tier
```

### Step 5 — Find your tier

| Score | Tier | What it means |
|-------|------|---------------|
| 85–100 | 🏆 Platinum | Governance leader |
| 70–84 | 🥇 Gold | Ethically sound, commercially partnerable |
| 55–69 | 🥈 Silver | Meets basics, notable gaps |
| 40–54 | 🥉 Bronze | Significant concerns |
| Below 40 | ⛔ Unrated | Non-compliant |

### Step 6 — Share your result (optional)

You can share your evaluation anywhere — your Instagram bio, your studio page, a tweet. Use this format:

> *"[Persona name] — SPERB v1.0 score: [score]/100 — [Tier]. Evaluated by [your name/studio]. Full evaluation: [link to your Google Doc or Notion page]. Framework: github.com/OpenNHE/sperb-benchmark"*

That's it. You're done.

---

## Method 2 — Using GitHub (Recommended for publishing)

If you want your evaluation to be **permanently public, citable, and submittable to the community index**, you should publish it directly on GitHub. Here's how, step by step, even if you've never used GitHub before.

### What is GitHub?

GitHub is a website where people store and share documents and code. Think of it like Google Drive, but public and version-controlled (every change is recorded). SPERB lives on GitHub so anyone can read, use, and contribute to it.

### Step 1 — Create a free GitHub account

Go to **github.com** and click **Sign up**. It's free. You only need an email address.

### Step 2 — Go to the SPERB repository

A "repository" (or "repo") is just a folder of files on GitHub.

Go to: `https://github.com/OpenNHE/sperb-benchmark`

You'll see the SPERB README page.

### Step 3 — Fork the repository

"Forking" means making your own personal copy of the SPERB repo in your GitHub account. Think of it like "Save a copy" in Google Docs.

Click the **Fork** button in the top-right corner of the page. GitHub will create a copy at:
```
https://github.com/YOUR-USERNAME/sperb-benchmark
```

### Step 4 — Create your evaluation file

Inside your forked repo, navigate to the `community/evaluations/` folder.

Click **Add file → Create new file**.

Name it:
```
your-persona-handle-2026-05.md
```
For example: `nila-voss-2026-05.md`

### Step 5 — Fill in the template

In the file editor, paste the contents of the evaluation template (from `scoring/EVALUATION_TEMPLATE.md`) and fill in all sections:

- Entity information (name, handle, country, creator)
- Your information (evaluator name, date, conflict of interest)
- Evidence corpus (which posts, repos, and press you looked at)
- All 8 dimension scores with justifications
- Your overall score and tier

### Step 6 — Save the file (Commit)

Scroll down to the bottom of the editor. You'll see a section called **Commit new file**.

In the text box, type:
```
Add SPERB evaluation for [your persona name]
```

Then click the green **Commit new file** button.

Your file is now saved in your fork.

### Step 7 — Submit to the community index (Pull Request)

A "Pull Request" (PR) is how you say: "I made a change in my copy — can you add it to the main repo?"

1. Go back to your forked repo's main page
2. Click **Contribute → Open pull request**
3. GitHub will show you what changed (your new evaluation file)
4. Add a title: `[EVAL] Your Persona Name (@handle) — SPERB v1.0 — 2026-05`
5. Click **Create pull request**

The SPERB maintainers will review your evaluation for rubric adherence and merge it into the community index. Once merged, your evaluation is permanently part of the SPERB public record.

---

## Method 3 — Using the Command-Line Tool (Advanced)

If you are comfortable using a terminal (the black command-line window on your computer), the repo includes a tool that automates the scoring and generates a formatted markdown report automatically.

### Prerequisites

You need:
- **Node.js** installed on your computer (free download at nodejs.org — version 16 or higher)
- **Git** installed (free download at git-scm.com)

### Step 1 — Clone the repo

Open your terminal and run:

```bash
git clone https://github.com/OpenNHE/sperb-benchmark.git
cd sperb-benchmark/tools
```

"Cloning" downloads a copy of the repo to your computer.

### Step 2 — Create your profile file

Create a new file called `my_persona.json` in the `tools/` folder. Copy and paste the template below and fill it in:

```json
{
  "entity": {
    "name": "Your Persona Name",
    "handle": "@yourhandle",
    "country": "Your Country",
    "creator": "Your Name or Studio Name",
    "notes": "Brief description — followers, pipeline, content genre"
  },
  "scores": {
    "PVS":  0,
    "AIDS": 0,
    "GDS":  0,
    "CPOS": 0,
    "ECS":  0,
    "CSRS": 0,
    "SCES": 0,
    "CITS": 0
  },
  "justifications": {
    "PVS":  "Replace with your 2-3 sentence evidence note",
    "AIDS": "Replace with your 2-3 sentence evidence note",
    "GDS":  "Replace with your 2-3 sentence evidence note",
    "CPOS": "Replace with your 2-3 sentence evidence note",
    "ECS":  "Replace with your 2-3 sentence evidence note",
    "CSRS": "Replace with your 2-3 sentence evidence note",
    "SCES": "Replace with your 2-3 sentence evidence note",
    "CITS": "Replace with your 2-3 sentence evidence note"
  }
}
```

Replace all the `0` scores with your actual scores (any number 0–10, decimals like 7.5 are fine).

### Step 3 — Run the report generator

In your terminal, run:

```bash
node report.js --profile my_persona.json
```

This generates a file called `sperb-[handle]-[month].md` in the same folder. Open it — it contains your full formatted SPERB evaluation report.

### Step 4 — Or use interactive mode

If you prefer to be guided through each dimension one by one:

```bash
node evaluate.js
```

The tool will display each dimension's rubric, ask you to enter a score (0–10), and ask for your evidence justification. At the end it calculates and saves your report automatically.

---

## Scoring Reference — What Each Score Level Means

Use this while filling in your evaluation.

### PVS — Does your persona look consistent?
| Score | What it looks like |
|-------|-------------------|
| 9–10 | Identical face in every post, photographic skin and material rendering, no AI artefacts |
| 7–8 | Mostly consistent, minor hair or material variance across posts |
| 5–6 | Face drifts noticeably across 30% of posts, some artefacts |
| 3–4 | Clearly different faces in different posts, frequent artefacts |
| 1–2 | Severe identity collapse, looks like a different person in many posts |

### AIDS — Does your persona disclose it's AI?
| Score | What it looks like |
|-------|-------------------|
| 9–10 | Bio says AI on every platform + every post has a disclosure tag + all ads have AI label |
| 7–8 | Bio says AI on all platforms, most posts have disclosure |
| 5–6 | Bio says AI, no per-post disclosure |
| 3–4 | Only a hashtag (#AIModel) buried in captions, bio is unclear |
| 1–2 | No disclosure anywhere, bio implies human identity |

### GDS — Is your governance publicly documented?
| Score | What it looks like |
|-------|-------------------|
| 9–10 | Full public GitHub repo with ethical license, policies, changelog, live metrics |
| 7–8 | Public page with ethics statement, pipeline disclosed, creator named |
| 5–6 | Creator and studio named publicly, basic disclosure |
| 3–4 | Studio named but nothing else documented publicly |
| 1–2 | Anonymous creator, no documentation at all |

### CPOS — Is all content original and pipeline disclosed?
| Score | What it looks like |
|-------|-------------------|
| 9–10 | 100% original content, tools fully disclosed, all collabs credited |
| 7–8 | All original, tools partially disclosed |
| 5–6 | Mostly original, no IP violations found, pipeline not fully disclosed |
| 3–4 | Some unattributed content, pipeline opaque |
| 1–2 | Stolen audio / voice / poetry from real people, no attribution |

### ECS — Is the conduct record clean?
| Score | What it looks like |
|-------|-------------------|
| 9–10 | Clean record, published conduct standards, active monitoring |
| 7–8 | Clean record, no violations found, no formal monitoring |
| 5–6 | No major violations, some grey-area practices (e.g. staged "feuds") |
| 3–4 | Multiple documented manipulation incidents |
| 1–2 | Multiple confirmed violations (deception + IP theft + manipulation) |

### CSRS — Is the cultural representation responsible?
| Score | What it looks like |
|-------|-------------------|
| 9–10 | Studio is from the represented culture, accurate and additive, substantive cause engagement |
| 7–8 | Culturally accurate, respectful, no exploitation |
| 5–6 | Generic positioning, not exploitative, no meaningful contribution |
| 3–4 | Superficial cultural claims not rooted in operator's background |
| 1–2 | Exploiting regional audiences without cultural accountability |

### SCES — Are emotional/romantic boundaries in place?
| Score | What it looks like |
|-------|-------------------|
| 9–10 | Documented "no romantic simulation" policy, human moderation active, escalation protocol exists |
| 7–8 | No romantic simulation, documented boundary policy |
| 5–6 | No simulation, no policy, relies on audience common sense |
| 3–4 | Companion-coded content (intimacy, direct emotional address) without safeguards |
| 1–2 | Actively simulates romantic relationships with followers |

### CITS — Are commercial activities transparent?
| Score | What it looks like |
|-------|-------------------|
| 9–10 | All ads labelled, monetisation model stated, no hidden brand deals |
| 7–8 | Most ads labelled, mostly transparent |
| 5–6 | Some unlabelled sponsored content, generally transparent |
| 3–4 | Significant unlabelled paid content |
| 1–2 | Systematically disguising ads as organic posts |

---

## Common Mistakes to Avoid

**Inflating your score.** The benchmark's value comes from honest differentiation. A self-evaluated score of 95/100 with no governance documentation is not credible and will be challenged if submitted to the community index.

**Skipping the justification.** Every score must reference something real you can point to — a URL, a screenshot, a specific post. "I think it's good" is not a justification.

**Confusing the tool with the standard.** The command-line tool is just a calculator. You can use it or ignore it. The standard is the 8-dimension rubric, which you can apply with nothing but this document and an internet connection.

**Giving a score without looking at evidence.** Before scoring AIDS, go to your persona's actual Instagram bio right now and read it. Does it say AI? Does the bio say "Not human" or "AI-generated"? That's the evidence.

---

## After You Get Your Score — What Next?

### If you scored Gold or Platinum (70+)
- Add your tier to your bio: `SPERB v1.0 Gold | github.com/OpenNHE/sperb-benchmark`
- Submit your evaluation to the community index via PR (Method 2, Step 7)
- Share the report publicly — it's a competitive differentiator for brand partnerships

### If you scored Silver (55–69)
- Identify your two lowest dimensions — those are your remediation priorities
- The lowest-cost fixes are always AIDS (add bio disclosure) and GDS (name your studio)
- Re-evaluate after fixing those — you may cross into Gold with just those two changes

### If you scored Bronze or Unrated (below 55)
- Read the blocking dimension sections carefully
- AIDS at 1–3 means you have a legal disclosure risk, not just a score problem
- GDS at 1 means no brand can legally partner with you yet — fix this first
- Re-evaluate after each fix rather than trying to fix everything at once

---

## Frequently Asked Questions

**Q: Can I evaluate my own persona? Isn't that biased?**  
Yes, you can. Self-evaluation is permitted and encouraged. The bias concern is managed by the requirement to publish your evidence alongside every score. Anyone can verify whether your evidence actually supports your score. A self-evaluated score without published evidence is not a valid SPERB score.

**Q: What if I don't know what score to give? The rubric isn't clear.**  
Pick the score that best matches the rubric description and explain why in your justification. If you're genuinely unsure between 6 and 7, write both possibilities in your justification and explain what would push it either way. Honest uncertainty is more credible than false precision.

**Q: What if someone challenges my score?**  
That's fine — it's how the framework improves. A valid challenge must cite specific evidence from the rubric. If someone challenges your AIDS score by showing your bio does not actually say "AI," that's a valid challenge. If they just say "I think it should be lower," that's not.

**Q: I have no brand partnerships yet. What do I score for CITS?**  
If you have no commercial activity at all, score CITS at 5–6 — you meet the minimum because there's nothing to disclose, but you also haven't demonstrated a proactive disclosure workflow yet. Note this in your justification.

**Q: Do I need to re-evaluate every year?**  
SPERB scores are time-stamped. If your entity's practices change significantly — you add bio disclosure, publish governance docs, gain brand partnerships — you should re-evaluate and publish the updated score. Old evaluations remain valid as historical records.

**Q: My persona has under 1,000 followers. Is SPERB relevant?**  
Yes. SPERB is not a follower-count benchmark. It evaluates ethical posture and governance, which are relevant from day one of operation. In fact, building governance infrastructure early (when it costs little) is much easier than retrofitting it after growth.

---

## Need Help?

- Open a **Discussion** on the GitHub repository: `github.com/OpenNHE/sperb-benchmark/discussions`
- Open an **Issue** if you think the rubric is unclear: use the template at `.github/ISSUE_TEMPLATE/`
- Read the full specification: `framework/SPERB_SPECIFICATION.md`
- Read the FAQ: `docs/FAQ.md`

---

*SPERB v1.0 — Algotheorem / OpenNHE — CC BY 4.0*  
*Free to use with attribution. No permission required.*
