# Win/Loss Findings — Readio (Reading App Category)

**Company:** Readio  ·  **Feature / Product:** Readio — Reading Habit App
**Author:** Sahana  ·  **Date created:** 26 September 2026
**Interviews:** 0 wins, 0 losses (no interviews conducted yet)  ·  **Conducted by:** Sahana

> ⚠️ **Evidence caveat:** No interviews have been conducted. This findings report is pre-populated with hypotheses drawn from secondary research — App Store reviews (~50 reviewed across Goodreads, Bookly, StoryGraph), Reddit threads (~20 posts), and competitive analysis. Every finding is `[ASSUMPTION]` and must be replaced with real interview data before being used in investor conversations or product decisions. Run the interview guide (02-win-loss-interview-guide.md) with a minimum of 8 respondents first.

---

## Why people stay with competing apps (hypothesised "wins" for competitors)

| Theme | Hypothesis | Secondary evidence | Interview count |
| :--- | :--- | :--- | ---: |
| Social network lock-in | Users stay on Goodreads because their friends and reading history are there — not because the product is good | App Store reviews: "I'd leave but my friends are here" pattern; 150M registered users | [ASSUMPTION] |
| Content access | Kindle/Audible users stay because the reading app is bundled with content they're already paying for | Amazon ecosystem integration; Kindle Unlimited link | [ASSUMPTION] |
| Community & book clubs | Fable retains users through author-led clubs and real-time discussion — belonging, not features | Fable acquired by Scribd 2025; 100K+ clubs | [ASSUMPTION] |
| Habit already formed | StoryGraph retains users who already have a reading habit — detailed stats satisfy existing readers | 5M users; StoryGraph Plus $50/yr conversion | [ASSUMPTION] |

---

## Why people leave competing apps (hypothesised "losses" for competitors = opportunities for Readio)

| Theme | Hypothesis | Secondary evidence | Interview count |
| :--- | :--- | :--- | ---: |
| Habit never formed | App downloaded with good intentions, habit never stuck — app becomes guilt reminder | Bookly: common 1–2★ pattern "used it 3 days and forgot"; ~40% estimated churn rate within 7 days | [ASSUMPTION] |
| Wrong onboarding | Apps assume user already knows what they want to read — non-readers are left without a starting point | StoryGraph's genre-first onboarding excludes "I don't know what I want" users | [ASSUMPTION] |
| Social pressure | Goodreads' public shelves and reading challenges create performance anxiety — triggers avoidance | Reddit r/books: "Goodreads makes reading feel like a chore" — recurring theme | [ASSUMPTION] |
| Progress invisible | No signal of progress on a book until finished — mid-book abandonment has no recovery mechanism | Kindle: no "well done for reading 10 pages" — progress is only visible at completion | [ASSUMPTION] |
| Price mismatch | Premium tiers priced for power users ($99–$120/yr) — lapsed readers won't pay before the habit is proven | Readwise $119.88/yr; Bookly Pro ~$29.99/yr; StoryGraph Plus $50/yr | [ASSUMPTION] |

---

## The buying process (hypothesised — how people choose a reading app)

1. **Trigger** — A moment of resolution ("I want to read more this year") or a specific recommendation from a peer
2. **Search** — App Store keyword search ("reading habit", "book tracker"); Reddit recommendations; ProductHunt
3. **Evaluation** — Screenshots and reviews in App Store; tries 1–2 apps simultaneously; 7–14 day free trial window
4. **Decision to keep** — Based on whether the app changed behaviour in the first week, not on feature completeness
5. **Decision to pay** — Converts only if the habit is visibly forming; price point must feel proportional to value experienced

---

## Competitor strengths and our gaps

| Competitor | Where they beat Readio today | Evidence (interviews) |
| :--- | :--- | ---: |
| Goodreads | Network effects — 150M users, friends already there; catalog depth; review volume | [ASSUMPTION] |
| StoryGraph | Mood/pacing discovery; detailed reading stats; strong Goodreads-refugee community | [ASSUMPTION] |
| Bookly | Session timer; ambient sounds; reading speed tracking; focused habit mechanics | [ASSUMPTION] |
| Readwise Reader | Cross-format (books, articles, newsletters, YouTube); spaced repetition retention; power-user depth | [ASSUMPTION] |
| Kindle | Content + reading in one app; device integration; Goodreads sync; Amazon ecosystem | [ASSUMPTION] |
| Fable | Book clubs; community belonging; author access; social reading done well | [ASSUMPTION] |

---

## What would have changed the outcome (hypothesised)

From secondary research, the three most likely answers a real interview would surface:

1. **"If it had made me feel like a reader in the first session"** — an early win, a meaningful progress signal, a moment of satisfaction within the first 10 minutes. No current app does this for the non-reader.
2. **"If it hadn't assumed I already knew what I wanted to read"** — a mood-first, commitment-light discovery flow. StoryGraph comes closest but still starts with genre.
3. **"If I hadn't felt judged for not reading enough"** — a non-performative social layer. Goodreads' public shelves and reading challenges actively repel lapsed readers.

---

## Recommendations (hypothesised — validate before acting)

1. **Design the first session as the product's core promise.** The moment a user closes the app on day 1 having read something — even 5 pages — is the conversion event. Every onboarding decision should be measured against: "does this make a first reading session more likely?"
2. **Price to the habit, not the content.** Don't compete on content access (Amazon owns that). Price the habit layer — ~$6.99–$9.99/month — as a behaviour-change tool, not a content subscription.
3. **Build Goodreads import on day one.** The switching cost of leaving reading history behind is a documented churn barrier across multiple apps. Remove it.

---

## Open questions / evidence to gather

- [ ] Conduct minimum 8 win/loss interviews using the guide in `02-win-loss-interview-guide.md`
- [ ] Validate: is "habit never formed" the primary churn reason, or is it "wrong content"?
- [ ] Validate: does the non-reader have a different churn profile than the lapsed reader?
- [ ] Quantify: what % of users who complete day-3 sessions convert to paid? (benchmark from Duolingo, Headspace analogues: ~8–15%)
- [ ] Validate: Goodreads import — is this a blocker or a nice-to-have? Ask in the interview directly.
