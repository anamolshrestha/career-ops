# 011 — Anthropic | Staff / Senior Software Engineer, AI Reliability

**Date:** 2026-04-28  
**Score:** 4.0/5  
**URL:** https://job-boards.greenhouse.io/anthropic/jobs/5113224008  
**PDF:** ❌ (borderline — generate if decided to apply)  
**Legitimacy:** High Confidence

---

## A — Match con CV

**Archetype:** Distributed Systems / Platform Engineer (Reliability Focus)

| JD Requirement | Anamol Evidence | Strength |
|---|---|---|
| Strong distributed systems background | SEI Kafka pipeline, Fidelity OpsWorX SDK, AA IVR — 8 years cross-company | ✅ Strong |
| Reliability-minded software engineer (SRE background welcomed) | 99.95% delivery reliability at SEI, 45% settlement latency reduction, $2B+/day trade volume | ✅ Strong |
| SLOs/SLIs, observability, incident response | Metrics-driven systems (latency, throughput, error rates) at every role | ✅ Present |
| "Jump into unfamiliar systems during incident" | Demonstrated cross-team debugging and delivery at Fidelity | ✅ Present |
| High-availability, multi-region infrastructure | SEI distributed platform; not multi-cloud explicitly | ⚠️ Adjacent |
| ML serving infrastructure, GPU/accelerator experience | Java backend engineer — no ML hardware exposure | ❌ Gap |
| Open-source infrastructure contributions | Not listed in CV | ❌ Gap |

The role targets "reliability-minded software engineers and SREs" — Anamol is a reliability-focused platform engineer but not a dedicated SRE. The framing on incident response and cross-team collaboration is a strength, not a stretch. ML-specific experience (GPU/TPU, InfiniBand, RDMA) is a "strong candidate" nice-to-have, not required.

**Block A score: 3.8/5** — strong dist systems fit, partial reliability framing, limited ML infra

---

## B — North Star Alignment

Anthropic is the highest-pedigree AI safety company in the world. The AIRE (AI Reliability Engineering) team owns reliability for Claude's serving path — the exact systems that deliver Anthropic's core product. This is cross-cutting infrastructure work at extraordinary scale.

This is not fintech but it is elite-tier platform engineering. The career signal value of "AI Reliability at Anthropic" is exceptional — opens doors at every top AI/fintech company post-tenure. The mission (reliable, interpretable, steerable AI) is meaningful.

Anamol already applied to Anthropic Senior SWE Platform (report #6, Applied). This is a different team (AIRE vs. Connectivity). Having both active may require coordination.

**Block B score: 4.5/5** — highest-pedigree opportunity in the pipeline

---

## C — Comp

| Source | Amount |
|---|---|
| JD annual comp | $325,000 – $485,000 USD |
| This includes | Base salary + equity at Anthropic |
| Anamol target | $200,000–$250,000 TC |
| Anamol walk-away | $170,000 |

The $325-485K range is 1.5–2x Anamol's stated target. Even at the floor, this blows past the $200K target by $125K. Anthropic's equity (likely options/RSUs in a company valued at ~$61B as of 2025 fundraise) is also meaningful.

**Block C score: 5.0/5** — top-of-market, exceptional comp

---

## D — Cultural Signals

- **25% in-office**: SF | NYC | Seattle. Not DFW. This means ~1 week per quarter of travel from Fort Worth TX.
  - At $325-485K total comp, quarterly travel is a reasonable trade-off
  - Not the same as weekly hybrid commuting — treat as "high-comp travel role"
- **Mission-driven**: AI safety, industry-defining work
- "Few teams offer this kind of dynamic, cross-cutting exposure to systems that matter most"
- Collaborative, cross-functional (partners with every team at Anthropic)
- Engineers are trusted to own outcomes across team boundaries

**Block D score: 3.5/5** — quarterly travel is an adjustment from ideal but manageable at this comp

---

## E — Red Flags

- **In-office 25%**: Not remote-pure. Requires quarterly trips to SF/NYC/Seattle. This is the primary concern.
- **SRE framing**: Job title says "AI Reliability" but responsibilities blend SRE, SWE, and infra. Anamol is primarily a platform SWE not a dedicated SRE. Strong candidate but framing adjustment needed.
- **Already applied to Anthropic (#6)**: Two active applications at the same company. Standard practice is one application per company. However, this is a completely different team (AIRE vs. Platform/Connectivity). May need to declare both in the application or let Anthropic's recruiting team coordinate.
- **Competitive pipeline**: Anthropic's AIRE team likely draws SRE talent from Google/Meta/AWS. Anamol's background is fintech, not hyperscaler infra.

**Block E: Moderate concern on location + SRE framing + dual-application.**

---

## F — Global Score

| Block | Score |
|---|---|
| A — Match con CV | 3.8 |
| B — North Star | 4.5 |
| C — Comp | 5.0 |
| D — Cultural | 3.5 |
| E — Red Flags | -0.3 (travel + dual-app) |
| **Global** | **4.0/5** |

**Recommendation: Apply, with caveats. Highest comp in the pipeline. Quarterly travel is manageable at this salary. Coordinate with Anthropic recruiting about the existing #6 application before submitting — or add a note in the application. Lean into distributed systems reliability work (SEI metrics, settlement latency, 99.95% uptime) and platform engineering at scale.**

**Note on dual Anthropic applications:** Anthropic's site doesn't explicitly prohibit multiple applications. They'll likely coordinate internally. In the "Additional Information" field, note: "I've also applied to the Platform team (Connectivity). Happy to discuss which team is the better fit."

---

## G — Posting Legitimacy

- **Tier: High Confidence**
- Active Greenhouse posting with full JD and Apply button ✅
- Anthropic is a publicly known company, verified careers page ✅
- $325-485K range is consistent with known Anthropic compensation bands ✅

---

## Framing for Application

**Lead with:** 8 years of distributed systems reliability at financial scale — SEI's $2B+/day trade volume, 99.95% delivery reliability on TBA MBS Kafka pipeline, 45% settlement latency reduction. Platform engineering that other systems depend on.

**Bridge to AI Reliability:** "Platform reliability is my specialty — not for a single product but for the infrastructure other engineers rely on. That's exactly what AIRE does for Claude."

**Address the SRE gap:** Mention cross-team incident response (AA IVR $3M/yr savings, emergency delivery fixes) and metrics-driven operations even if not titled SRE.

**Cover letter hook:** "I've spent 8 years building the systems nobody thanks until they break. $2B in daily trades processed without incident. That discipline — building invisible reliability — is what I want to bring to Claude."
