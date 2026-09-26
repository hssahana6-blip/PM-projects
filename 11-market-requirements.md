# Readio — Market Requirements Document

*This document is confidential and subject to change. For internal use only. No external commitments can be made based on this document since it is in early planning stages. Content and timing are very likely to change.*

**Company:** Readio  ·  **Feature / Product:** Readio — Reading Habit App (MVP Release)
**Author:** Sahana  ·  **Contact:** [sahana@readio.app]  ·  **Date created:** 26 September 2026  ·  **Date last updated:** 26 September 2026

> ⚠️ **Evidence caveat:** No primary market research has been conducted. All market evidence counts are derived from secondary research (App Store reviews, Reddit threads, Pew Research, competitive analysis). Every evidence count is an estimate. All requirements should be treated as validated hypotheses until primary interview data replaces the secondary evidence. Conduct 10 user interviews before locking this MRD for engineering hand-off.

---

## Overview of Target Release

**Release goal:** Ship the Readio MVP — the minimum set of capabilities that demonstrates Readio's core promise: *a lapsed reader who uses Readio for one week reads more consistently than they have in months, and knows it.*

**Market forces driving this release:**
- 65 million US adults read zero books per year (Pew Research, 2023) — an unserved segment with demonstrated willingness-to-pay for habit-change tools (Duolingo, Headspace analogues)
- No major reading app onboards the non-reader or lapsed reader; the competitive window is open now
- The Product Canvas (Stage 09) sets three pre-launch conditions: validate willingness-to-pay (landing page), achieve D7 retention ≥ 35% (beta), and complete 10 primary interviews — this MRD defines what to build to meet condition 2

**Driving force:** Primarily content-driven (market problem, not a fixed date). The release is ready when D7 retention ≥ 35% in a 200-user closed beta — not when a calendar date arrives.

**Prior artifacts:** Market Problems Table (01), Win/Loss Interview Guide + Findings (02), Distinctive Competencies (03), Competitive Landscape (04), Personas — Priya + Rajan (05), Positioning + POC Worksheet (06), Product Canvas (09), Product Roadmap (10).

**Personas in scope:**
- **Priya** — the Lapsed Reader (primary user); adults who used to read, have lost the habit, and carry guilt about it
- **Rajan** — the Self-Improvement Seeker (economic buyer); pays for tools that produce demonstrable behaviour change

---

## Requirements

### GROUP 1 — Habit Ignition
*The hardest problem. Without this, nothing else matters. Users who don't start a second session in the first week will never convert to paid.*

**Requirement 1.1 — Non-judgmental onboarding that starts from zero**
Priya has the problem that every reading app she has tried assumes she already knows what she wants to read, leaving her without a starting point and making her feel like the app was not built for her — with a frequency of every time she opens a new reading app.

**Priority:** 18 (evidence) × 5 (impact — minimum purchase criteria) = **90**
*Evidence count: ~18 occurrences across App Store reviews ("assumes you're already a reader"), Reddit threads ("StoryGraph doesn't help if you don't know what genre you want"), competitive analysis (all 6 major competitors fail this test). Impact 5: without this, lapsed readers exit onboarding and never return — it is a purchase blocker.* [ASSUMPTION]

**Requirement 1.2 — Time-based daily reading goal (not page-based)**
Priya has the problem that she believes she does not have enough time to read, and page-based goals feel unachievable on a busy day, causing her to skip reading entirely rather than read for a shorter time — with a frequency of daily.

**Priority:** 22 (evidence) × 5 (impact) = **110**
*Evidence: ~22 occurrences across Reddit r/getdisciplined ("I can't commit to 30 pages a day"), App Store reviews of Bookly ("the page goal stresses me out"), Pew 2023 ("too busy" cited as reading barrier by ~38% of non-readers). Impact 5: time-based goal is the mechanism that makes the first session possible for lapsed readers — without it, the product does not work for this persona.* [ASSUMPTION]

**Requirement 1.3 — Frictionless session continuity**
Priya has the problem that reopening a reading app after a gap feels effortful — she has to remember where she was, navigate back to her place, and decide whether to continue — with a frequency of every reading session after the first.

**Priority:** 15 (evidence) × 4 (impact) = **60**
*Evidence: ~15 occurrences across Kindle and Bookly reviews ("lost my place", "too many taps to get back to reading"). Impact 4: directly affects whether users start a second session — losing even one friction point in re-entry measurably improves D7 retention.* [ASSUMPTION]

---

### GROUP 2 — Progress Visibility
*The reason lapsed readers give up mid-book. Without visible progress, the habit does not compound.*

**Requirement 2.1 — Forward-looking progress indicator (pages read, not pages remaining)**
Priya has the problem that progress indicators on her current reading apps show how much she has left — making a long book feel endless — rather than celebrating how far she has come, causing her to feel defeated rather than motivated — with a frequency of every reading session.

**Priority:** 20 (evidence) × 5 (impact) = **100**
*Evidence: ~20 occurrences across Goodreads and Kindle UX reviews ("I feel further away from the end every time I open it"), Reddit ("percentage remaining is demoralising"), Win/Loss Findings (progress invisibility is #2 hypothesised churn reason). Impact 5: this is the primary mechanism for preventing mid-book abandonment — Readio's core retention problem.* [ASSUMPTION]

**Requirement 2.2 — Reading streak with guilt-free gap protection**
Rajan has the problem that reading streaks on other apps reset to zero after a single missed day, making a missed day feel catastrophic and causing him to abandon the habit entirely rather than resume — with a frequency of every time he misses a day.

**Priority:** 18 (evidence) × 4 (impact) = **72**
*Evidence: ~18 occurrences across Duolingo community discussions ("streak anxiety"), Bookly 1–2★ reviews ("lost my 30-day streak and deleted the app"), Reddit r/getdisciplined ("streaks are motivating until they're not"). Impact 4: streak reset is a documented churn trigger; gap protection (one "freeze" per week) maintains motivation without removing accountability.* [ASSUMPTION]

**Requirement 2.3 — Week-over-week reading comparison**
Rajan has the problem that he has no way to see whether his reading is improving week-over-week, making it impossible to judge whether the app is working — which is the primary factor in his decision to upgrade to paid — with a frequency of weekly.

**Priority:** 16 (evidence) × 4 (impact) = **64**
*Evidence: ~16 occurrences across self-improvement app reviews ("I need to see I'm improving"), Rajan persona research (conversion triggered by visible behaviour change). Impact 4: this is the conversion mechanism — Rajan upgrades when he can see the habit forming.* [ASSUMPTION]

---

### GROUP 3 — The Reading Receipt
*Readio's most distinctive feature and primary retention mechanism. Ships in MVP because it defines the product.*

**Requirement 3.1 — Weekly Reading Receipt delivered every Monday**
Priya has the problem that at the end of every week she has no idea how much she read, leaving her with only a vague sense of guilt and no concrete evidence of progress — with a frequency of weekly.

**Priority:** 25 (evidence) × 5 (impact) = **125** *(highest priority in this MRD)*
*Evidence: ~25 occurrences across secondary research (this is the #1 market problem identified in the Market Problems Table). Impact 5: the Reading Receipt is Readio's positioning differentiator and primary retention mechanism — without it, Readio is just another reading tracker. It is also the product's primary viral loop.* [ASSUMPTION]

**Requirement 3.2 — Cross-format reading credit (articles count as reading)**
Priya has the problem that she reads articles and newsletters for 60–90 minutes daily but no reading app credits this as reading, reinforcing the belief that she is "not a reader" and preventing her from feeling the identity shift that would sustain the habit — with a frequency of daily.

**Priority:** 14 (evidence) × 4 (impact) = **56**
*Evidence: ~14 occurrences across Reddit r/books ("I read loads of articles but don't feel like a reader"), competitive gap (no app treats articles and books equally). Impact 4: cross-format credit is Readio's fastest path to the lapsed reader feeling like a reader — a necessary precondition for habit formation.* [ASSUMPTION]

---

### GROUP 4 — Switching & Acquisition
*Remove the barriers that prevent lapsed readers from trying Readio. Without these, growth is throttled at the top of the funnel.*

**Requirement 4.1 — Goodreads reading history import on day one**
Rajan has the problem that switching to a new reading app means losing years of reading history and his current reading lists, making the switching cost feel too high to attempt — with a frequency of once (at app install).

**Priority:** 16 (evidence) × 5 (impact) = **80**
*Evidence: ~16 occurrences across app-switching discussions on Reddit ("I can't leave Goodreads because my shelf is there"), Win/Loss Findings (Goodreads import identified as primary switching barrier). Impact 5: without import, a significant proportion of lapsed readers who are already on Goodreads will not switch — it is an acquisition blocker.* [ASSUMPTION]

**Requirement 4.2 — Free tier with core habit mechanics (no paywall on the habit loop)**
Rajan has the problem that he will not pay for a reading app he has not yet proven works for him — he needs to experience the habit forming before he will upgrade — with a frequency of in the first 7–14 days.

**Priority:** 18 (evidence) × 5 (impact) = **90**
*Evidence: ~18 occurrences across self-improvement app research (Duolingo, Headspace free-tier conversion model); Rajan persona (conversion window is 7–14 days; he pays only when he believes the habit is forming). Impact 5: paywalling the habit loop before the user experiences it eliminates conversion — the free tier is the acquisition mechanism.* [ASSUMPTION]

---

### GROUP 5 — Mood-Based Discovery
*Ships in MVP as a lighter version. Full mood+time discovery is Phase 2. Without at least a basic "what should I read next?" answer, users who finish their first book have nowhere to go.*

**Requirement 5.1 — Mood-first book recommendation (replaces genre filter)**
Priya has the problem that genre-based filters do not match how she actually chooses what to read — she thinks about how she wants to feel, not what category a book belongs to — causing her to spend more time browsing than reading — with a frequency of every time she looks for her next book.

**Priority:** 20 (evidence) × 4 (impact) = **80**
*Evidence: ~20 occurrences across StoryGraph discussions ("mood/pacing is why I use StoryGraph"), App Store reviews of genre-based apps ("the genre filters don't help me find what I'm in the mood for"). Impact 4: without a next-book recommendation, users who finish one book have no path forward — this is a D30 retention problem.* [ASSUMPTION]

---

## Persona Details

**Priya — the Lapsed Reader (User)**
Growth Manager, 29. Urban professional. Reads articles/newsletters 60–90 min daily. Has Kindle with three unfinished books. Last finished a book 8 months ago. Responds to non-judgmental progress signals. Will pay ~$8–12/month if the habit is visibly forming. Full persona: `05-persona-user-priya.md`.

**Rajan — the Self-Improvement Seeker (Buyer)**
Team Lead, 32. Has paid for Audible, Kindle Unlimited, Blinkist — barely uses any. Conversion window: 7–14 days. Primary objection: "another app I'll use for a week and forget about." Converts when he can see visible behaviour change. Price ceiling ~$8–12/month. Full persona: `05-persona-buyer-rajan.md`.

---

## Requirements Summary

| Requirement | Market Evidence | Impact | Priority (E × I) | Group | Group Order |
| :--- | ---: | ---: | ---: | :--- | ---: |
| 3.1 — Weekly Reading Receipt | 25 | 5 | **125** | Reading Receipt | 1 |
| 1.2 — Time-based daily goal | 22 | 5 | **110** | Habit Ignition | 1 |
| 2.1 — Forward-looking progress indicator | 20 | 5 | **100** | Progress Visibility | 2 |
| 1.1 — Non-judgmental onboarding | 18 | 5 | **90** | Habit Ignition | 1 |
| 4.2 — Free tier with habit mechanics | 18 | 5 | **90** | Switching & Acquisition | 4 |
| 4.1 — Goodreads import | 16 | 5 | **80** | Switching & Acquisition | 4 |
| 5.1 — Mood-first recommendation | 20 | 4 | **80** | Mood-Based Discovery | 5 |
| 2.2 — Streak with gap protection | 18 | 4 | **72** | Progress Visibility | 2 |
| 2.3 — Week-over-week comparison | 16 | 4 | **64** | Progress Visibility | 2 |
| 1.3 — Frictionless session continuity | 15 | 4 | **60** | Habit Ignition | 1 |
| 3.2 — Cross-format reading credit | 14 | 4 | **56** | Reading Receipt | 1 |

**Delivery sequence:** Group 1 (Habit Ignition) → Group 2 (Progress Visibility) → Group 3 (Reading Receipt) → Group 4 (Switching & Acquisition) → Group 5 (Mood Discovery). Groups 1–3 must ship together as the minimum viable product — the habit loop, progress signal, and Reading Receipt are inseparable.

---

## Approvals

| Name | Title | Date | Signature |
| :--- | :--- | :--- | :--- |
| | Systems Architect | | |
| | Interaction Designer | | |
| Sahana | Product Manager | 26 Sep 2026 | |
| | Development Manager | | |
| | Quality Assurance Lead | | |
| | Project Manager | | |

---

## Change Tracking

| Version | Date | Changes | Reason |
| :--- | :--- | :--- | :--- |
| 1.0 | 26 Sep 2026 | Initial draft | — |

---

## Open Questions / Evidence to Gather Before Engineering Hand-off

- [ ] Validate Requirement 1.2 (time-based goal): does 10 minutes feel achievable, or too low for some users? Run usability test with 5 lapsed readers
- [ ] Validate Requirement 3.1 (Reading Receipt): does Monday morning delivery drive re-engagement, or is another day/time better? Test in beta
- [ ] Validate Requirement 4.1 (Goodreads import): is this a true blocker, or a nice-to-have? Ask directly in 10 primary interviews
- [ ] Validate Requirement 5.1 (mood discovery): how many mood options is too many? StoryGraph has ~20; test with 3–5 options in MVP
- [ ] Confirm all evidence counts with primary interview data — current counts are secondary research estimates [ASSUMPTION]
