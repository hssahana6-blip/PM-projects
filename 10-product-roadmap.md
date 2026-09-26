# Product Roadmap — Readio

**Company:** Readio  ·  **Feature / Product:** Readio — Reading Habit App
**Author:** Sahana  ·  **Date created:** 26 September 2026  ·  **Version:** 1.0
**Horizon:** 24 months  ·  **Audience:** Internal (exec + engineering) and investor-facing

> This roadmap is a plan, not a commitment. It communicates direction and the market problems we intend to solve — not dated deliverables. Specific scope, dates, and sprint assignments live in the Release Plan. Themes and timelines will shift as we learn from the market. Under-promise so the team can over-deliver.

---

## Vision

Every person who wants to read more should be able to — regardless of how long it's been since they finished a book. Readio exists to make the reading habit accessible to the 65 million people the reading app market has never served: the lapsed reader, the aspiring reader, the person who reads articles for an hour a day and doesn't think it counts.

**Product vision:** A reading companion that starts where you actually are, celebrates every session, and makes next week look different from last week.

---

## Strategic objectives (outcomes, not features)

1. **Make the first reading session succeed.** The moment a user closes Readio having read something — even 5 minutes of an article — is the conversion event. Every Phase 1 decision is measured against: does this make a first session more likely?

2. **Make progress visible enough to feel real.** The primary reason lapsed readers give up is not lack of content — it is invisible progress. By the end of Phase 1, every user should be able to see, in plain language, how much more they read this week than last.

3. **Make the Reading Receipt the product's heartbeat.** The weekly summary is Readio's primary retention mechanism and its most distinctive feature. It must ship in Phase 1 and be worth looking forward to.

4. **Earn the right to expand.** Cross-format tracking, mood-based discovery, and social features are powerful — but only if the core habit loop works first. Phases 2 and 3 expand the product's reach once Phase 1 retention is validated.

5. **Own the lapsed-reader segment before the incumbents notice.** Goodreads, StoryGraph, and Bookly are not trying to serve this persona. The window to build a moat is open now; it will narrow as they grow.

---

## Roadmap

| Theme | Now → Month 4 | Month 5–8 | Month 9–14 | Month 15–24 |
| :--- | :--- | :--- | :--- | :--- |
| **Habit ignition** | Mood onboarding · 10-min daily goal · Session continuity | Contextual nudges · Chapter commitment | Smart re-engagement (gap detection) | Personalised habit coaching |
| **Progress visibility** | Chapter progress bar · Streak · Session history | Week-over-week comparison · Habit graph | Reading pace analytics · Monthly wrap | Long-form reading identity profile |
| **The Reading Receipt** | Weekly receipt (MVP) · Cross-format credit | Receipt personalisation · Shareable card | Receipt-driven re-engagement experiments | Annual reading wrap (Spotify Wrapped analogue) |
| **Discovery** | — | Mood + time-based recommendation | Trusted curator layer · Length filter | AI-assisted discovery · Social recommendations |
| **Cross-format** | Articles + books equally tracked | Newsletter integration | Podcast / audio tracking | Unified reading identity across all formats |
| **Growth & switching** | Goodreads import · ASO · Reddit organic | Referral programme · Content / SEO | Paid social (post D7 ≥ 40%) | Partnership channel (publishers, libraries) |
| **Monetisation** | Free tier defined · Pricing tested | Paywall implemented · 14-day free trial | Paid tier optimisation · Annual plan | Enterprise / gifting / family plan |
| **Market goals** | 200-user closed beta · D7 retention ≥ 35% | 10,000 MAU · 4% free-to-paid conversion | 80,000 MAU · Month-3 retention ≥ 70% | 300,000 MAU · Contribution-positive |

---

## Themes

### Theme 1 — Habit ignition
*The problem that matters most. Priority 25 from Market Problems Table.*

- **Market problem / persona:** Priya has the problem that days go by and she never opens a book. The intention is there; the activation is not. No existing app solves for this with warmth and specificity — they track what she reads, not whether she starts.
- **Desired outcome:** By the end of the first week, a new Readio user has read on at least 3 days and has a specific time and chapter set for their next session. Starting is no longer the hardest part.
- **Evidence:** Priority 25 (highest in Market Problems Table); Duolingo's 47% DAU/MAU proves the model at scale; Bookly's 7-day churn pattern shows what happens when habit mechanics are cold rather than warm. [ASSUMPTION]
- **Phase 1 (Now → Month 4):** Mood-based onboarding ("how do you want to feel?"), 10-minute daily goal as the default, session continuity (open the app → back in the book instantly), streak display.
- **Phase 2 (Month 5–8):** Contextual nudges ("you're 8 minutes from finishing this chapter"), chapter commitment ("when will you read next?" before close).
- **Phase 3 (Month 9–14):** Gap detection ("you haven't read in 3 days — here's a 5-minute article to restart"), personalised re-engagement.
- **Phase 4 (Month 15–24):** AI-driven personalised habit coaching based on individual reading patterns.

---

### Theme 2 — Progress visibility
*The reason lapsed readers give up. Priority 20.*

- **Market problem / persona:** Priya gives up mid-book because she can't see that she's making progress. A 400-page book looks the same on page 50 as it did on page 10. No app shows her how much more she read this week than last week in a way that feels meaningful.
- **Desired outcome:** Every Readio user can, in under 10 seconds, see that their reading this week is measurably more than last week. Progress is expressed in time and sessions, not pages and books.
- **Evidence:** Priority 20 in Market Problems Table; progress invisibility is the #2 hypothesised churn reason from Win/Loss Findings. [ASSUMPTION]
- **Phase 1:** Chapter-level progress bar showing pages read (not pages remaining), streak display, session history for the past 7 days.
- **Phase 2:** Week-over-week reading minutes comparison ("you read 47 min last week vs. 12 min the week before"), habit graph (3-week heatmap).
- **Phase 3:** Reading pace analytics, personalised monthly reading wrap.
- **Phase 4:** Long-form reading identity profile — a user's full reading history, shown as growth over time.

---

### Theme 3 — The Reading Receipt
*Readio's most distinctive feature. No competitor has this. Cuts across Priority 25 + 9.*

- **Market problem / persona:** Priya finishes a week and has no idea how much she read. She has a vague sense of guilt and no concrete sense of progress. Rajan wants a concrete record he can point to — "I read 47 minutes last week, 4× more than the month before."
- **Desired outcome:** Every Monday morning, Readio users receive a warm, specific, non-judgmental summary of their reading week. Open rate ≥ 60%. Users share the Receipt unprompted.
- **Evidence:** Spotify Wrapped's cultural moment (shared by 60M+ users in 2022) proves that a well-designed periodic summary generates organic virality. No reading app has built a weekly analogue. [ASSUMPTION]
- **Phase 1:** MVP Receipt — total minutes, pages turned, articles finished, streak, one highlight. Delivered in-app and via push notification every Monday morning.
- **Phase 2:** Personalisation ("your favourite reading time is 9pm"), shareable card (optimised for Instagram Stories / WhatsApp).
- **Phase 3:** A/B experiments on Receipt content to optimise re-engagement conversion.
- **Phase 4:** Annual Reading Wrap — Readio's Spotify Wrapped moment. Full year in review, designed to be shared.

---

### Theme 4 — Mood-based discovery
*The reason lapsed readers can't find what to read. Priority 20.*

- **Market problem / persona:** Priya spends more time browsing than reading. Genre filters don't match how she actually feels. She wants something calm to wind down with, but the app shows her "bestsellers in thriller."
- **Desired outcome:** A Readio user can go from "I want to read something" to opening a specific book or article in under 60 seconds, using mood and available time as the primary filters.
- **Evidence:** StoryGraph's 5M-user growth is substantially attributable to its mood/pacing tags — the clearest market signal available. Readio's differentiation is combining mood with available time and format. [ASSUMPTION]
- **Phase 2 (not Phase 1):** Discovery is a Phase 2 priority. Phase 1 focuses on users who already have a book in progress. Discovery becomes critical for the second and third book.
- **Phase 2:** Mood selector ("how do you want to feel?") + time filter ("something I can finish tonight") + format (book / article / short).
- **Phase 3:** Trusted curator layer — small set of real readers whose taste is profiled; recommendations attributed to a named curator, not an algorithm.
- **Phase 4:** AI-assisted discovery using reading history and mood patterns.

---

### Theme 5 — Cross-format reading credit
*The identity unlock for non-readers. Priority 6, but strategically important for TAM.*

- **Market problem / persona:** Priya reads articles for 60–90 minutes daily but doesn't count it as "real" reading. She has built a reading habit — she just doesn't know it. Showing her that she is already a reader is the fastest path to her becoming a Readio user who reads books.
- **Desired outcome:** A Readio user who reads only articles in their first week still receives a Reading Receipt, still sees a streak, and still feels the identity of "being a reader." Cross-format credit is the on-ramp.
- **Evidence:** No app treats article and book reading equally. This is a genuine gap. Long-term, cross-format tracking data is Readio's most defensible competitive asset. [ASSUMPTION]
- **Phase 1:** Books and articles tracked equally in session history and Reading Receipt.
- **Phase 2:** Newsletter integration (Substack, Beehiiv save-to-Readio).
- **Phase 3:** Podcast / audio chapter tracking.
- **Phase 4:** Unified reading identity across all formats — a user's complete intellectual diet.

---

## What this roadmap is NOT

- A list of features with ship dates — that is the Release Plan
- A commitment to deliver any specific item in any specific quarter
- A backlog — that is the engineering team's responsibility
- A response to any individual customer or investor request

Roadmap themes will shift as we learn. The market problems they address will not. If a theme changes, it is because we found a better way to solve the same problem — not because we changed what we believe the market needs.

---

## Open questions that will shape Phase 2 decisions

- [ ] Does Day-7 retention in beta clear 35%? If not, Phase 2 scope resets around habit ignition, not discovery.
- [ ] Does the Reading Receipt drive Monday morning re-engagement? Open rate is the leading signal.
- [ ] Does cross-format credit (articles = books) change how lapsed readers self-identify? (Usability test, Phase 1 beta)
- [ ] What is the actual free-to-paid conversion rate in the first 90 days? This determines whether Phase 2 growth spending is warranted.
