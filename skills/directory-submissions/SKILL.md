---
name: directory-submissions
description: When the user wants to list a local CNA / healthcare / allied-health training program (or another local service business) in directories for local search ranking, citations, reviews, backlinks, and discovery. Also use when the user mentions "directory submissions," "submit to directories," "local citations," "NAP," "Google Business Profile," "GBP," "Google reviews," "Yelp listing," "Bing Places," "Apple Maps," "get on Google Maps," "map pack," "local SEO listings," "CNA class directory," "school directory," "Niche listing," "state-approved program list," "nurse aide registry," "list my school," or "directory tracker." Use this for planning the directory/citation layer of a local enrollment or backlink campaign. Reads product/positioning context from .agents/product-marketing.md (see the product-marketing skill).
metadata:
  version: 3.0.0
---

# Directory Submissions (Local CNA / Healthcare Training)

You are an expert in directory-driven, **local** distribution for training programs and service businesses. Your goal is to help the user build a compounding **local-search + citation + review** foundation — the listings that make a CNA/healthcare training program rank in the map pack, get cited by AI answer engines for "CNA classes near me," and convert searchers into enrolled students — not just vanity backlinks.

This skill is oriented to a **local training school** (CNA, home health aide, phlebotomy, medical assistant, CPR/BLS, and similar). The same playbook applies to any local service business; swap "program" for "service" and the state-authority tier for whatever licensing your vertical uses.

## Before Starting

**Check for product marketing context first:**
If `.agents/product-marketing.md` exists (or `.claude/product-marketing.md`, or the legacy `product-marketing-context.md` filename), read it before asking questions. Use that context — especially the school's location(s), program details, pass/placement rates, and target students — and only ask for what's missing. If no context file exists, offer to run the **product-marketing** skill first to capture it.

---

## Core Philosophy

For a local training program, directory/citation listings do four things — in this priority order:

1. **Win the map pack.** Google Business Profile + consistent citations across the web are the #1 driver of ranking for "CNA classes near me" / "CNA training [city]." This is where enrollment leads come from.
2. **Build trust for a high-consideration decision.** Tuition is real money and a career bet. Reviews, BBB, and state-approval listings are what a prospective student checks before calling.
3. **Get cited by AI answer engines.** ChatGPT, Claude, Perplexity, and Google AI Overviews increasingly answer "what are the best CNA programs in [city]?" — they pull from high-authority local directories, review sites, and state-approved-program lists.
4. **Pass backlinks** from high-DR directories into your program pages, lifting overall domain authority so you rank for more queries.

**The foundation is Google Business Profile and NAP consistency, not backlinks.** Build the program/landing pages first, get GBP verified and complete, lock a canonical NAP, then work outward through citations, education directories, authority pages, reviews, and local press.

The full directory catalog lives in `references/directory-list.md`. The positioning variant library lives in `references/positioning-variations.md`. The submission tracker template lives in `references/submission-tracker-template.csv`.

---

## The Three Hard Rules

### Rule 1: NAP consistency above everything
Decide the canonical **Name, Address, Phone** (plus hours, categories, website URL) **once**, and use it byte-for-byte identical on every listing. Inconsistent NAP (a "Suite 200" here, a "Ste. 200" there, two phone numbers) is the single biggest cause of weak local rankings. Record the canonical block at the top of `references/positioning-variations.md` before submitting anything.

### Rule 2: Foundation before submission
Never submit to directories until these are live and indexed:
- **Google Business Profile claimed + verified + fully completed** (categories, hours, services, photos, description).
- A real **program page** per program (`/cna-training`, `/cna-classes-[city]`) with: a single `<h1>`, clear schedule/next start date, tuition or "contact for pricing," program length/hours, and what's covered.
- **Location/contact page** with an embedded Google map + the canonical NAP.
- **Privacy policy + terms** (many directories require them).
- Real **photos** — the facility, skills lab, instructors, a class in session (5–8, not stock).
- **Accreditation / state-approval info** stated plainly (approval #, testing vendor).
- **FAQ schema** (`FAQPage` JSON-LD) and **`EducationalOrganization`/`LocalBusiness`** structured data on the program page — AI engines and Google both weight these.

### Rule 3: Positioning varies by surface
Never copy-paste the same description everywhere. Search + AI engines penalize duplicate content, and each surface rewards a different opener. See `references/positioning-variations.md` for the full library. Short version:

| Surface | Lead with | Why |
|---|---|---|
| Google Business Profile / maps | **City + state-approved + outcome** | Local searchers want proximity, legitimacy, and results. |
| Local citation directories | **NAP + category clarity** | Consistency and correct categorization are the goal. |
| School / education directories | **Time-to-certify + pass rate** | High-intent students compare programs on speed + outcomes. |
| State / accreditation pages | **Factual approval status only** | Authority surfaces reward accuracy; marketing hurts. |
| Local press / listicles | **A numbers-backed local story** | Editors want a local human angle. |
| Review platforms | **Earn, don't write** | Prospects trust reviews over your copy. |

---

## Workflow

### Step 1: Readiness assessment (Phase 0)

Ask the user these questions. A "no" on 1–7 is a hard block — help them build that piece first.

1. Is there a **claimable business address** in the service area (physical campus or clinical site)?
2. Is **Google Business Profile** claimed and verifiable (you can receive the postcard/video verification)?
3. Is a **program page** live for each program, with schedule, length, and what's covered?
4. Is the **canonical NAP** decided and consistent on the site (footer + contact page)?
5. Are **privacy policy + terms** live?
6. Are there **real photos** (facility, skills lab, instructors)?
7. Is the program's **state-approval status** current, and do you know the approval # + testing vendor?
8. Are there **≥10 recent graduates** you could ask for a Google review? (soft block — you can start, but reviews are the enrollment driver)
9. Do you know your **exam pass rate and job-placement rate**? (soft block — needed for positioning credibility)

### Step 2: Choose the tiers

Full catalog in `references/directory-list.md`. Summary (re-oriented for a local training program):

| Tier | What | When | Priority |
|---|---|---|---|
| **Tier 1 — Core local search** | Google Business Profile (anchor), Bing Places, Apple Business Connect, Yelp, Facebook, Nextdoor, Instagram | First | **Highest** |
| **Tier 2 — Local citations & data aggregators** | Data Axle, Localeze, Foursquare, BBB, YP, Superpages, Manta, local Chamber, etc. | Week 1–2 | High |
| **Tier 3 — School / education directories** | Niche, RWM, Trade-Schools.net, AllAlliedHealthSchools, CNA aggregators, CareerOneStop | Week 1–3 | High |
| **Tier 4 — State authority & accreditation** | State nurse aide registry approved-program list, testing-vendor locator, ETPL | Ongoing | **Highest trust** |
| **Tier 5 — Review platforms** | Google, Yelp, Facebook, Niche, BBB reviews | Ongoing from day 1 | **Enrollment driver** |
| **Tier 6 — Local press & "best of"** | Local paper/TV, Patch, "best CNA classes in [city]" roundups, .gov career centers | Rolling outreach | Medium |
| **Tier 7 — General profile/citation** | LinkedIn company page, Crunchbase, D&B, YouTube, secondary blog | Rolling | Medium (DR + AI corpora) |
| **Tier 8 — Health/career vertical** | Wellness.com, employer/SNF partner pages, Indeed company profile | If genuine fit | Low–Medium |

**Triage rule:** only submit where the program genuinely fits. Forcing a listing into the wrong category gets rejected and wastes the effort. Skip the SaaS/AI/startup directories entirely — they don't apply to a local school.

### Step 3: Prepare asset variations

For each tier, prep a distinct variant (pulled from `references/positioning-variations.md`):
- **Canonical NAP block** (identical everywhere)
- **Tagline** under 10 words (city + state-approved + outcome)
- **Short description** ~60 chars
- **Long description** ~150 words (vary the opener per surface)
- **5–8 category tags**
- **Logo + real photos** (facility, skills lab, instructors)
- **Program facts:** length/hours, next start date, tuition or "contact," pass rate, placement rate, funding options

**Critical:** don't copy-paste the same long description into every directory. Vary the opening sentence, the feature emphasis, and the audience framing per surface.

### Step 4: Batch submit

Set up the tracker (`references/submission-tracker-template.csv`). Work top-down. 2–3 hours per batch is realistic.

Per submission:
1. Copy the surface-appropriate positioning variant.
2. Paste the **exact canonical NAP**.
3. Choose the closest correct category.
4. Upload logo + photos.
5. Submit; log date, URL, status, moderator notes.
6. Once live, verify NAP is correct and (where relevant) whether the backlink is dofollow: `curl -sIL https://directory.com/your-listing | grep -i rel=`. If no `rel="nofollow"`/`"ugc"` appears near your link, it's dofollow. (Most local/review platforms are nofollow by design — that's fine; they still drive map-pack ranking and referrals.)

---

## Google Business Profile Deep Dive (The Anchor)

GBP is the single highest-leverage listing for a local school — the local equivalent of a flagship launch. Most of your enrollment calls will trace back to it.

### Setup (do all of it — completeness is a ranking factor)
- **Claim + verify** (postcard, phone, or video). Don't skip verification.
- **Business name:** exact canonical NAP name. **Do not** stuff keywords ("Best CNA Classes Cheap [City]") — Google suspends profiles for it.
- **Primary category:** the closest match (e.g., "Vocational school" / "Training centre" / "Nurses' association"). Add relevant secondary categories.
- **Address + service area**, hours (including holiday hours), and phone (a local number beats a toll-free one for local signals).
- **Services:** list each program as a service with a short description.
- **Photos:** facility exterior (helps people find you), skills lab, classroom, instructors, graduation. Add new photos monthly.
- **"From the business" description:** use the GBP template in `references/positioning-variations.md`.
- **Q&A:** seed the common questions (cost, length, schedule, financial aid, prerequisites) and answer them yourself.

### Ongoing (weekly)
- **Post weekly:** next start date, an info-session/open-house, a graduate spotlight, an exam-pass milestone.
- **Respond to every review** within a few days — thank positives by name; address negatives with empathy + a next step.
- **Keep hours + start dates current.** Stale info kills conversions and trust.

---

## Reviews Playbook (The Enrollment Driver)

For a local school, **reviews outrank backlinks** for both map-pack ranking and enrollment decisions. Prospective students read them before they call. Run this every cohort.

### The graduation review protocol
1. **The week of certification**, identify every graduate who had a good experience.
2. **Send each a short, personal message** with **one direct review link** (default: Google — reduces friction ~70% vs "find us on Google"). Use the email template in `references/positioning-variations.md`.
3. **Make it about helping the next student**, not about you: "would you share your experience for future students deciding where to train?"
4. **Follow up once** after ~5 days. Never more.
5. **Target:** ~50% response → 10 reviews per 20 asks. Aim for steady recency, not a one-time burst.

### Rules
- **Never buy or incentivize** Google/Yelp reviews — it violates their terms and risks removal/suspension. A sincere ask converts fine.
- **Never solicit Yelp reviews** specifically — Yelp's filter suppresses solicited ones. Earn them organically.
- **Respond to all reviews**, especially critical ones — future students read your responses as a signal of how you treat people.
- **Spread across platforms** over time: Google first, then Facebook, Niche, BBB.

---

## Destination Pages Strategy (What Listings Point At)

Listings are wasted if they land on a generic homepage. Build these *before* submitting:

### 1. City/program landing pages (highest local ROI)
One page per program × primary city: `/cna-classes-[city]`, `/cna-training-[city]`. Each needs: a single H1 with "CNA classes in [City]," the schedule + next start date, program length/hours, tuition or "contact," what's covered, embedded map + canonical NAP, graduate outcomes (pass/placement rate), and an FAQ with schema. These rank for the exact local queries your listings reinforce.

### 2. Outcomes / "why us" page
Pass rate, placement rate, employer partners, testimonials, and state-approval details in one place. This is what a comparison-shopping student and an AI answer engine both look for.

### 3. Financial aid / funding page
WIOA/workforce funding, payment plans, scholarships. A major objection-remover and a common search ("free CNA classes [city]," "CNA training financial aid").

### 4. "Best CNA programs in [city]" resource (you write it honestly)
An honest local roundup including yourself + other programs. Ranks for the category query and becomes a reference AI engines cite. Be honest — false claims get de-ranked.

### 5. FAQ page with schema
Cost, length, prerequisites, exam, licensing, job prospects. `FAQPage` JSON-LD is heavily weighted for AI answer extraction.

---

## GEO (Getting Cited by AI Answer Engines)

More prospective students ask ChatGPT/Claude/Perplexity/Google AI Overviews "what are the best CNA programs in [city]?" before ever visiting a search page. To get cited:

1. **One H1 per page, clean heading hierarchy.**
2. **Dense, factual, local content:** specific numbers (pass rate, placement rate, hours, tuition), city names, employer names.
3. **FAQ schema on program pages.**
4. **Get on high-authority local + review + state sources** — AI engines lean on GBP data, Yelp, Niche, BBB, and state-approved-program lists for local answers.
5. **Claim LinkedIn company page, Crunchbase, and Google/Bing/Apple** — these feed AI training corpora and local knowledge panels.
6. **Get genuine local mentions** (local news, community pages) — they count as trust fuel.
7. **State it plainly in the first 100 words:** "[School] is a state-approved CNA training program in [city]."

**Measurement:** monthly, ask ChatGPT/Claude/Perplexity and Google "what are the best CNA classes in [city]?" and log whether/where you appear.

---

## KPIs & Tracking

Track monthly. If a number isn't moving, investigate — don't just submit more directories.

| Metric | Baseline | 90-day target | Why |
|---|---|---|---|
| Google Business Profile — verified + complete | — | 100% | Foundation |
| Map-pack ranking for "CNA classes [city]" | not ranking | top 3 | Primary lead source |
| Google reviews (count) | 0 | 25+ | Ranking + trust |
| Google review average | — | 4.5+ | Enrollment conversion |
| Core citations live (NAP-consistent) | 0 | 30+ | Local authority |
| NAP consistency score | — | 95%+ | Ranking hygiene |
| Education/school directory listings | 0 | 8+ | High-intent discovery |
| On state-approved-program list (verified) | — | Yes | Trust + AI citation |
| Domain Rating (DR) | baseline | +10 | Broader SEO lift |
| AI answer citations (manual check) | 0 | appears for [city] | GEO |
| Enrollment inquiries from "found us online" | baseline | +[goal] | The point of all of it |

---

## What NOT to Do

1. **Don't launch citations before the canonical NAP is locked.** Fixing inconsistent NAP later is painful.
2. **Don't keyword-stuff the Google Business Profile name.** It's the fastest way to get suspended.
3. **Don't buy or incentivize Google/Yelp reviews.** Removal + suspension risk. Ask sincerely instead.
4. **Don't solicit Yelp reviews** — its filter penalizes solicited ones.
5. **Don't pay for "submit to 500 directories" services.** Most are spam directories (DR under 10) that dilute your profile; the ones that matter are an afternoon of manual work.
6. **Don't submit to SaaS/AI/startup directories.** They don't apply to a local school and waste time.
7. **Don't claim accreditation, approval, or pass/placement rates you can't verify.** State boards and AI engines cross-reference; false claims get de-ranked and create regulatory exposure.
8. **Don't ignore reviews.** Zero reviews (or unanswered negative ones) kills enrollment more than any missing backlink.
9. **Don't duplicate the same description across directories.** Vary the opener per surface.
10. **Don't treat listings as the whole strategy.** They're the foundation; reviews, program pages, and local reputation are what convert.

---

## Task-Specific Questions

1. **What programs do you offer, and where?** (City/cities + program mix set the tier priorities.)
2. **Is Google Business Profile claimed and verified yet?** (If not, that's step one.)
3. **What's your canonical NAP?** (Lock it before anything else.)
4. **What's your state approval status, approval #, and testing vendor?** (Tier 4 authority + credibility.)
5. **How many recent graduates can you ask for a Google review?** (The enrollment driver.)
6. **Do you know your exam pass rate and job-placement rate?** (Positioning credibility.)
7. **Do you offer funding (WIOA/financial aid) or adjacent programs (CPR, HHA, phlebotomy)?** (Extra tiers + objection removers.)
8. **Which local employers do you place graduates with?** (Partner-page listings + proof points.)

---

## Output Format

When the user asks for a directory/local-listing plan, return:

1. **Readiness assessment** — which Phase 0 items are missing, which block submission
2. **Canonical NAP block** — the exact Name/Address/Phone/URL to use everywhere
3. **Tier selection** — which tiers apply, priority order, which to skip
4. **Submission order** — GBP + core local first, then citations / education / authority batches
5. **Destination page list** — program/city pages, outcomes, funding, FAQ to build first if missing
6. **Positioning variants** — the actual copy per surface (from `references/positioning-variations.md`)
7. **Google Business Profile setup checklist** — categories, services, photos, posts
8. **Reviews protocol** — who to ask, when, the exact message
9. **Monthly targets** — map-pack rank, reviews, citations, AI citations
10. **Tracker** — link to or include the CSV from `references/submission-tracker-template.csv`

Keep the plan actionable. Every item should be something the user can do this week.

---

## Related Skills

- **product-marketing** — the shared context document (`.agents/product-marketing.md`) this skill reads first for the school's location, programs, audience, and proof points. Run it before this skill if the file doesn't exist yet.

> This is a trimmed fork of coreyhaines31/marketingskills. The upstream repo has ~45 other marketing skills (launch, programmatic-seo, competitors, ai-seo, content-strategy, community-marketing, schema, etc.). Add any of them back with `/plugin` if you want their playbooks alongside this one.
