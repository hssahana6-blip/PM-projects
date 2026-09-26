# Market Problems Table — Readio

**Company:** Readio  ·  **Feature / Product:** Readio — Reading Habit App
**Author:** Sahana  ·  **Date created:** 26 September 2026

> ⚠️ **Evidence caveat:** No primary research (interviews, surveys, win/loss) has been conducted yet. All market evidence below is drawn from secondary sources — competitor reviews (App Store/Play Store), public Goodreads/StoryGraph community threads, industry reports, and the competitive landscape mapped in this session. Every row is marked `[ASSUMPTION]` until validated with real interviews. Urgency, pervasiveness, and willingness-to-pay scores are directional, not measured. **Do not present these figures as validated data to investors without conducting at least 10 market visits.**

---

## Recommended NIHITO visits before the next draft

To validate this table, Sahana should speak with:

| Segment | Where to find them | What to ask |
| :--- | :--- | :--- |
| **Potentials** (non-readers, best for innovation) | Reddit r/books, r/selfimprovement; LinkedIn; friends/colleagues who say "I want to read more" | "What stops you from reading? Why haven't you tried an app?" |
| **Competitors' customers** (Goodreads, Bookly, StoryGraph users) | App Store reviews; Twitter/X #Goodreads; StoryGraph community Discord | "What problem does your current app not solve for you?" |
| **Evaluators** (people actively searching for a reading app) | App Store search behaviour; ProductHunt reading tools | "Why did you try this app? What were you hoping it would do?" |
| **Lapsed customers** (downloaded a reading app, stopped using it) | Churn surveys; App Store 1–2 star reviews | "What made you stop using it?" |

Target: **10 conversations minimum** before locking personas and positioning.

---

## Market Problems Table

| Persona | Problem (first person) | Market Evidence | Impact (1–5) | Priority (E × I) | Group |
| :--- | :--- | ---: | ---: | ---: | :--- |
| Lapsed Reader | "I keep meaning to read but days go by and I never open a book." | [ASSUMPTION] App Store 1–2★ reviews across Goodreads, Bookly cite "forgot to open the app" — est. 40%+ of low-rating reviews; Pew Research (2023): 26% of US adults read 0 books last year | 5 | 25 | Habit formation |
| Lapsed Reader | "I don't feel like I'm making progress so I give up mid-book." | [ASSUMPTION] Common Goodreads complaint thread theme; books feel infinite with no visible momentum signal | 5 | 20 | Progress & motivation |
| Lapsed Reader | "I can't find anything I actually want to read — genre filters don't match how I feel." | [ASSUMPTION] StoryGraph's mood/pacing feature grew to 5M users precisely because genre alone is insufficient for discovery | 4 | 20 | Discovery |
| Non-Reader | "Reading feels like a commitment I can't make — I don't have big blocks of time." | [ASSUMPTION] Behavioral research on habit formation; Duolingo's 5-min lesson format success is an analogue signal | 5 | 15 | Time & friction |
| Non-Reader | "Every reading app I've seen is built for people who already read a lot." | [ASSUMPTION] Gap confirmed in competitive analysis — no app onboards from zero reading habit | 4 | 12 | Onboarding |
| Lapsed Reader | "I finish a book and immediately forget what I learned or how it made me feel." | [ASSUMPTION] Readwise's core value prop validated by $119/yr willingness-to-pay from knowledge workers | 3 | 9 | Retention |
| Lapsed Reader | "My friends are on Goodreads but it feels like a performance, not reading." | [ASSUMPTION] Fable community threads; "social pressure" cited in Goodreads 1–2★ reviews | 3 | 6 | Social |
| Non-Reader | "I read articles for hours but don't count that as 'real' reading." | [ASSUMPTION] Reddit r/books discussions; no app credits cross-format reading equally | 3 | 6 | Format parity |

**Scoring guide:** Impact 1 = minor inconvenience → 5 = blocks the goal entirely. Evidence = estimated count of documented occurrences across secondary sources. Priority = Evidence × Impact (sort descending).

---

## Problems clearing the urgent + pervasive + willing-to-pay test

Based on secondary evidence, three problems are strong candidates for MVP scope:

1. **Habit formation** — "Days go by and I never open a book." Urgent (daily), pervasive (26% of adults read zero books), and analogues (Duolingo, Headspace) prove willingness to pay for habit products.
2. **Progress & motivation** — "I give up mid-book." Urgent for anyone in a book, pervasive across all reading apps' churn patterns, and directly addressable in the product.
3. **Discovery (mood-based)** — "Genre filters don't match how I feel." StoryGraph's 5M-user growth on mood/pacing alone is the strongest market signal available.

---

## Open questions / evidence to gather

- [ ] What percentage of lapsed readers cite "no time" vs. "wrong content" vs. "lost habit" as the primary reason? (Interview target: 10 potentials)
- [ ] What is the actual D30 churn rate for Bookly and Goodreads? (Proxy: App Store review patterns, sensor data)
- [ ] Is the non-reader willing to pay, or only the lapsed reader? (Critical for pricing model)
- [ ] Does cross-format parity (articles + books) meaningfully increase retention, or is it a nice-to-have? (A/B test candidate)
- [ ] What price point signals "serious tool" vs. "another free app I'll forget"? (Conjoint survey candidate)
