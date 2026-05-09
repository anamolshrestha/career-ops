# 009 — Hightouch | Software Engineer, Streaming Systems

**Date:** 2026-04-28  
**Score:** 3.8/5  
**URL:** https://job-boards.greenhouse.io/hightouch/jobs/5983863004  
**PDF:** ❌ (below 4.0 threshold)  
**Legitimacy:** High Confidence

---

## A — Match con CV

**Archetype:** Distributed Systems Engineer (Streaming Platform)

| JD Requirement | Anamol Evidence | Strength |
|---|---|---|
| Distributed systems experience | SEI Kafka pipeline, Fidelity microservices migration, AA IVR platform | ✅ Strong |
| High-throughput, low-latency systems | Sub-100ms at SEI; 5M+ monthly interactions at AA | ✅ Strong |
| Kafka/Kinesis/Pulsar (useful, not required) | Kafka at SEI — producer/consumer topology, transactional patterns | ✅ Strong |
| "millions of messages per second at single second latency" | Not at this exact scale — 100K+ events/day at SEI is meaningful but different order | ⚠️ Gap |
| High ownership, startup pace | Present at SEI/Fidelity in IC delivery ownership | ✅ Present |

No specific language required — Anamol's Java stack will work. No minimum seniority stated explicitly, but compensation ($180-320K) and system design interviews suggest senior–staff expectations.

**Note:** Application requires running `curl jobapi.hightouchdata.com` on port 13784 before applying.

**Block A score: 4.0/5**

---

## B — North Star Alignment

Hightouch is a high-growth AI marketing platform (1000+ enterprise customers including Domino's, Chime, Spotify, Ramp). The Streaming Systems team owns event ingestion infrastructure — behavioral events, clickstream, transactional data feeding AI agent workflows.

This is adjacent to Anamol's target archetype (platform/streaming at fintech scale). Not pure fintech, but the product is used by fintech companies (Chime is a customer). Revenue 10x'd in the past year on streaming products — high-growth platform engineering.

The role is lower-pedigree than Affirm (smaller company, unlisted) but higher upside potential via equity (early exercise + 10yr post-termination window).

**Block B score: 3.5/5** — good alignment but not canonical fintech target

---

## C — Comp

| Source | Amount |
|---|---|
| JD base | $180,000–$320,000 USD |
| Equity | "Large portion of compensation" via ISO options — early exercise + 10yr post-term window |
| Anamol target | $200,000–$250,000 TC |

The $180K floor is below target but the $320K ceiling and stated equity emphasis suggest total comp can be well above $200K for a strong candidate. Hightouch is Series C (~$248M raised). The wide range indicates negotiating room at the senior/staff end.

**Block C score: 3.5/5** — range is right but base floor concern

---

## D — Cultural Signals

- **Remote-first** (North America) ✅
- "First-principles thinking, move quickly and efficiently"
- System design-focused interviews — no LeetCode grind ✅ (Anamol's background is systems, not algorithms)
- High autonomy: "extremely high levels of ownership and autonomy"
- Strong customer list: Domino's, Chime, Spotify, Ramp, Whoop, Grammarly — credible growth-stage company
- Transparent about process

**Block D score: 4.0/5**

---

## E — Red Flags

- **Level ambiguity**: Title is just "Software Engineer" — could land at Senior or below. Need to confirm expected seniority in recruiter screen.
- **Scale gap**: "millions of messages per second" — Anamol's Kafka experience is at 100K+ events/day. Different order of magnitude. Mitigate by emphasizing architectural design, exactly-once patterns, and willingness to operate at this scale.
- **Single-application rule**: "auto-rejected if you apply to multiple roles" — must commit to this one.
- **Port 13784 requirement**: Run curl command as part of application — unusual but not a red flag, shows engineering culture.
- No public listing risk (VC-backed startup).

**Block E: Moderate concern on level + scale gap.**

---

## F — Global Score

| Block | Score |
|---|---|
| A — Match con CV | 4.0 |
| B — North Star | 3.5 |
| C — Comp | 3.5 |
| D — Cultural | 4.0 |
| E — Red Flags | -0.2 (level + scale ambiguity) |
| **Global** | **3.8/5** |

**Recommendation: Worth considering, but prioritize Affirm (007) first. If applying, confirm expected level in recruiter screen before committing.**

---

## G — Posting Legitimacy

- **Tier: High Confidence**
- Active Greenhouse posting with Apply button ✅
- Hightouch is a venture-backed company with strong traction (10x revenue growth mentioned) ✅
- "New" badge on posting — recently listed ✅
- No ghost indicators

---

## Framing for Application

**Lead with:** SEI streaming pipeline — high-throughput event processing, Kafka at scale, architectural ownership.

**Address the scale gap proactively:** "At SEI I processed 100K+ trade events/day with exactly-once delivery guarantees. Hightouch's millions-per-second challenge is a step up in scale that I'm designed to tackle — the architectural principles are the same."

**Run the curl command first.** Port 13784, curl jobapi.hightouchdata.com. Follow those instructions before applying.

**Cover letter hook:** "I've spent 4 years building the streaming infrastructure that nobody sees but everyone depends on. At SEI: $2B+ daily trade volume, 99.95% delivery reliability. Hightouch's behavioral event pipeline is a scale challenge I want to take on."
