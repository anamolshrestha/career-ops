# 008 — Affirm | Staff Software Engineer, Backend (Streaming)

**Date:** 2026-04-28  
**Score:** 4.5/5  
**URL:** https://job-boards.greenhouse.io/affirm/jobs/7000578003  
**PDF:** ✅ `cv-anamol-shrestha-affirm-streaming-2026-04-28.pdf`  
**Legitimacy:** High Confidence

---

## A — Match con CV

**Archetype:** Distributed Systems Engineer (Streaming / Platform)

Anamol is an exceptionally strong match for this role. Every core requirement maps directly to production experience:

| JD Requirement | Anamol Evidence | Strength |
|---|---|---|
| 8+ years industry experience | 8 years: AA (2018–2022), SEI (2022–2024), Fidelity (2024–present) | ✅ Exact |
| Apache Kafka at scale | SEI: Kafka + JMS event-driven arch, 100K+ trade events/day, exactly-once delivery, 99.95% reliability | ✅ Strong |
| Stream processing frameworks (Flink/Spark/Samza/Beam) | Kafka Streams at SEI; Flink/Spark not in CV but overlapping skill | ⚠️ Partial |
| Java or Kotlin | Java is primary language across all 3 companies | ✅ Strong |
| Kafka Connect + Schema Registry | Kafka-based pipeline at SEI — transactional producers, deduplication, retry mechanisms | ✅ Implied |
| High-throughput, fault-tolerant infrastructure | $2B+ daily trade volume, 99.95% delivery reliability at SEI | ✅ Strong |
| Leading technical projects + mentoring | Mentored 5+ engineers at Fidelity; drove architectural decisions | ✅ Present |
| Event-driven architecture | Full EDA at SEI (TBA MBS Kafka pipeline replacing synchronous flows) | ✅ Strong |

**Confluent Platform (Schema Registry, Tableflow)** — listed as "strong plus," not in CV explicitly. Anamol's Kafka depth implies familiarity but this is worth noting in the cover letter.

**Apache Iceberg / CDC tools** — "strong plus," not in CV. Not a blocker.

**Block A score: 4.5/5**

---

## B — North Star Alignment

This is the canonical target archetype: **Staff-level distributed systems / streaming platform engineer at a fintech company.** Affirm is a publicly traded BNPL fintech processing billions in loans — the scale and regulated environment mirror Anamol's background at SEI precisely.

The Streaming team is described as "the backbone of several online and offline workloads at Affirm" — this is a platform team, not a product team. Infrastructure ownership, streaming at scale, cross-team enablement: directly aligned with Anamol's work on the OpsWorX SDK platform at Fidelity and the Kafka pipeline at SEI.

**Block B score: 5/5**

---

## C — Comp

| Source | Amount |
|---|---|
| JD (TX / most US states) | $200,000–$250,000 base |
| JD (CA, WA, NJ, CT) | $225,000–$275,000 base |
| Anamol target | $200,000–$250,000 TC |

Base alone is within Anamol's target range. Add equity (P-grade + Equity Grade 13) + 100% medical coverage + monthly stipends. Total comp likely lands at $220–280K+ depending on equity grant.

**Block C score: 4.5/5**

---

## D — Cultural Signals

- **Remote-first company**, majority of roles remote ✅ (Anamol's preference)
- Strong benefits: 100% subsidized medical (employees + dependents), ESPP, Flexible Spending Wallets (tech, food, lifestyle, family)
- "People come first" stated core value
- Growing team — Streaming team described as backbone for multiple business lines
- Affirm is publicly traded (NASDAQ: AFRM), stable stage
- Streaming team collaborates with ML and Analytics — cross-functional, high-visibility

**Block D score: 4.5/5**

---

## E — Red Flags

- **Flink/Spark gap**: JD lists Flink/Spark as requirements; Anamol has Kafka Streams but Flink isn't explicitly in CV. This is the main gap. Mitigate by noting streaming platform expertise and willingness to ramp on Flink quickly.
- **Confluent Platform specifics**: Schema Registry + Tableflow listed as "strong plus" — Anamol's Kafka depth covers the concepts, but Confluent Cloud tooling may need calling out or addressing proactively.
- **Python requirement**: "Solid programming skills in Python, Java or Kotlin" — Python is secondary for Anamol (listed in skills, but Java is primary). Not a blocker.
- No major red flags on company stability, culture, or legitimacy.

**Block E: Minor gaps only, no blockers.**

---

## F — Global Score

| Block | Score |
|---|---|
| A — Match con CV | 4.5 |
| B — North Star | 5.0 |
| C — Comp | 4.5 |
| D — Cultural | 4.5 |
| E — Red Flags | -0.1 (minor gaps) |
| **Global** | **4.5/5** |

**Recommendation: Apply. Strong match. One of the clearest opportunities in this pipeline.**

---

## G — Posting Legitimacy

- **Tier: High Confidence**
- Active Greenhouse posting with Apply button live ✅
- Affirm is publicly traded (AFRM) — legitimate employer ✅
- Posting is for an existing role at the Streaming team (backbone platform team) ✅
- No ghost indicators

---

## Framing for Application

**Archetype:** Distributed Systems Engineer (Streaming Platform)

**Lead with:** SEI TBA MBS Kafka pipeline — "Architected end-to-end event-driven architecture using Kafka and JMS for $2B+ daily trade volume, processing 100K+ trade events daily with 99.95% delivery reliability."

**Secondary proof point:** Fidelity OpsWorX SDK Event Framework — "Reduced cross-application data propagation latency by 40% and cut inter-app communication failures by 60% for 50+ hosted applications."

**Address the Flink gap:** "Deep Kafka expertise with hands-on Kafka Streams; actively expanding to Flink for complex event processing pipelines."

**Cover letter hook:** "Affirm's Streaming team is doing exactly what I've spent 4 years building — the invisible backbone that lets product teams ship with confidence. At SEI I owned the Kafka pipeline that processed 100K+ trade events daily at 99.95% reliability. I want to do that at Affirm's scale."

---

## Story Bank Candidate (STAR+R)

**Situation:** SEI needed to onboard TBA MBS asset class with real-time settlement tracking  
**Task:** Design and build end-to-end Kafka pipeline for trade lifecycle  
**Action:** Architected producer/consumer topology, message-key deduplication, transactional producers, custom retry — replacing synchronous flows with async event streams  
**Result:** 100K+ trade events/day, 99.95% delivery reliability, 45% settlement latency reduction  
**Relevance:** Maps directly to Affirm Streaming team's mandate to build reliable, high-throughput data infrastructure
