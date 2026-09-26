# Problem-Oriented Capabilities Worksheet — Readio

**Company:** Readio  ·  **Feature / Product:** Readio — Reading Habit App
**Author:** Sahana  ·  **Date created:** 26 September 2026

> This worksheet maps market problems (in the persona's first-person voice) → problem groups → problem-oriented capabilities → product features. Built from the Market Problems Table (01) and both Personas (05). All market problems are [ASSUMPTION] until validated with primary interviews.

---

## Persona: Priya — the Lapsed Reader (User)

| Market Problems (Priya's first person) | Problem-Oriented Capability | Product Features |
| :--- | :--- | :--- |
| "Days go by and I never open a book." | **Habit ignition** — makes starting the next session the path of least resistance | Daily reading reminder (contextual, not generic); chapter commitment ("when will you read next?"); home screen shows exactly where she left off with zero friction |
| "I don't have a big block of time, so I don't read at all — I don't realise 10 minutes is enough." | **Habit ignition** | Time-based daily goals (10 min/day default); "8 min left in this chapter" CTA; session length awareness |
| "I give up mid-book — I don't feel like I'm making progress." | **Progress that feels real** | Chapter-level progress bar; pages-read-today counter (forward-looking, not pages-remaining); streak display; weekly session history |
| "I open my Kindle and feel too guilty to keep going — I'm 12% through a book I started months ago." | **Progress that feels real** | Guilt-free re-entry: no judgment on gaps; "pick up where you left off" framing; progress shown as pages read, not % remaining |
| "I can't find anything I actually want to read — genre filters don't match how I feel." | **Discovery without commitment anxiety** | Mood-based discovery ("how do you want to feel?"); time-to-read filter ("something I can finish this weekend"); length as a first-class filter |
| "I spend more time browsing than reading." | **Discovery without commitment anxiety** | Curated daily recommendation (1 book, 1 article) based on mood + available time; no infinite scroll browse mode |
| "I finish an article and immediately scroll to the next one — I never think about what I just read." | **Cross-format reading credit** | Article reading tracker; reading session logged whether book or article; Reading Receipt includes all formats |
| "I read articles for hours but don't count that as real reading." | **Cross-format reading credit** | Equal credit for books, articles, newsletters; unified reading time dashboard; Reading Receipt shows all reading, all formats |
| "Goodreads makes me feel like I should be reading 50 books a year. I'm not, so I don't bother." | **The Reading Receipt** | Non-judgmental weekly summary; progress framed as gain ("you read 47 minutes — 4× more than last month"), never as deficit; no public leaderboards or friends' progress feeds |
| "I finish a book and immediately forget what I learned or how it made me feel." | **The Reading Receipt** | Post-session note prompt; weekly receipt includes a highlight from the week's reading; optional quote/reflection save |

---

## Persona: Rajan — the Self-Improvement Seeker (Buyer)

| Market Problems (Rajan's first person) | Problem-Oriented Capability | Product Features |
| :--- | :--- | :--- |
| "I've paid for Audible, Kindle Unlimited, and Blinkist. I barely use any of them." | **Early win mechanics** | First session delivers a completed reading (article or short chapter) within 10 minutes; "you just read 8 minutes" confirmation; Day 1 streak starts immediately |
| "I've downloaded five reading apps. None made me read more." | **Early win mechanics** | Onboarding asks "when did you last finish a book?" — sets expectation from reality, not aspiration; Day 3 nudge shows concrete progress since install |
| "Another app I'll use for a week and forget about." | **Habit measurement, not content measurement** | DAU streak; weekly minutes read; week-over-week comparison ("you read 3× more than last week"); habit graph visible in free tier |
| "I want to be the kind of person who reads — my manager reads constantly." | **Habit measurement, not content measurement** | Progress framed as identity ("you read every day this week"); milestone system tied to consistency not volume; Reading Receipt shareable |
| "I'd switch apps but I'd lose all my reading history." | **Frictionless switching** | Goodreads import on day one; reading history and book list carried over; "your shelf is already here" moment in onboarding |
| "I can't justify the subscription cost — I'm not sure I'll actually use it." | **Proportional pricing** | Free tier includes core habit mechanics (streak, daily goal, Reading Receipt); paid tier unlocks mood discovery, cross-format tracking, and advanced stats; 14-day free trial of paid tier with no credit card |
| "How much did I actually read last week?" | **The Reading Receipt** | Weekly summary delivered every Monday morning; minutes read, pages turned, articles finished, streak; week-over-week comparison; shareable card |

---

## Capability consolidation (across both personas)

| Problem-Oriented Capability | Core problem it solves | Primary persona | Priority (from MPT) |
| :--- | :--- | :--- | :--- |
| Habit ignition | Starting is the hardest part | Priya | 25 (highest) |
| Progress that feels real | Invisible progress causes abandonment | Priya | 20 |
| Discovery without commitment anxiety | Genre filters don't match how I feel | Priya | 20 |
| Cross-format reading credit | Articles don't count as "real" reading | Priya + Rajan | 6 |
| The Reading Receipt | No weekly proof that I'm improving | Priya + Rajan | Cuts across 25 + 9 |
| Early win mechanics | "Another app I'll use for a week" | Rajan | Conversion-critical |
| Habit measurement, not content measurement | I can't see the behaviour change | Rajan | Retention-critical |
| Frictionless switching | I'd lose my reading history | Rajan | Acquisition barrier |
| Proportional pricing | I won't pay before the habit is proven | Rajan | Monetisation-critical |

---

## MVP feature map (No Brainer quadrant from Solution Matrix)

Features that address the highest-priority capabilities at the lowest investment:

| Feature | Capability served | Build priority |
| :--- | :--- | :--- |
| Mood-based onboarding ("how do you want to feel?") | Habit ignition + Discovery | P0 — MVP |
| 10-minute daily reading goal | Habit ignition | P0 — MVP |
| Reading Receipt (weekly) | Progress that feels real + Receipt | P0 — MVP |
| Chapter-level progress bar (pages read, not remaining) | Progress that feels real | P0 — MVP |
| Goodreads import | Frictionless switching | P0 — MVP |
| Cross-format reading credit (articles + books) | Cross-format credit | P1 — post-MVP |
| Mood + time-based discovery | Discovery without commitment anxiety | P1 — post-MVP |
| Advanced stats + habit graph | Habit measurement | P1 — post-MVP |
| Social layer (opt-in, non-performative) | Identity / community | P2 — future |
