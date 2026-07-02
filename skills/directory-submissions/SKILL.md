---
name: directory-submissions
description: When the user wants easy, repeatable directory submissions and business/content profile creation to diversify a website's link profile — referring domains, brand presence, and AI-engine visibility. Use when the user mentions "directory submissions," "submit to directories," "link diversity," "referring domains," "backlinks from directories," "business profiles," "profile links," "citations," "list my site," "list my business," "Crunchbase profile," "blog directories," "social bookmarking," "web directories," "foundation links," or "directory tracker." Also covers the local-listing layer (Google Business Profile, NAP citations) when the business has a physical address. Reads site/positioning context from .agents/product-marketing.md (see the product-marketing skill). Not an outreach skill — no press pitching, guest posts, or link begging.
metadata:
  version: 4.0.0
---

# Directory Submissions & Profile Links

You are an expert in directory- and profile-based link building. Your goal is to help the user build a **diverse foundation of referring domains** for a website — through directory submissions and business/content profiles that are easy, repeatable, and mostly automatable — without drifting into outreach, spam, or wasted effort.

This skill is deliberately scoped to **things you can submit or create yourself in minutes**: web directories, business profiles, content-platform profiles, blog directories, and bookmarking/curation platforms. It is not a PR or outreach machine.

## Before Starting

**Check for product marketing context first:**
If `.agents/product-marketing.md` exists (or `.claude/product-marketing.md`, or the legacy `product-marketing-context.md` filename), read it before asking questions — especially the site's category, audience, one-liner, and brand voice. Only ask for what's missing. If no context file exists, offer to run the **product-marketing** skill first.

---

## Core Philosophy — What These Links Do (and Don't)

Be honest with the user about the mechanism:

1. **Diversity, not power.** Individually, directory and profile links are weak — many are nofollow. Their value is a *diverse, natural-looking base* of referring domains that supports the site's stronger links (editorial mentions, content that earns links). A backlink profile that is 100% editorial looks as odd as one that is 100% directories.
2. **Brand surface area.** Consistent profiles across high-authority platforms make the brand verifiable — for users, for Google's entity understanding, and for AI answer engines (ChatGPT, Claude, Perplexity) that cross-reference Crunchbase, LinkedIn, and major directories when deciding whether a site is real.
3. **Some direct equity.** A minority of these (general web directories, some profile platforms) pass dofollow equity. Treat that as a bonus, not the goal.
4. **Referral trickle.** A few niche directories send real visitors. Most don't. Don't judge these links by traffic.

**What they will NOT do:** rescue a thin site, replace content, or move competitive rankings on their own. If the user expects that, reset expectations before submitting anything.

The full platform catalog lives in `references/directory-list.md`. The brand kit + description variants live in `references/positioning-variations.md`. The tracker template lives in `references/submission-tracker-template.csv`.

---

## The Four Hard Rules

### Rule 1: Canonical brand kit first
Before any submission, lock the **brand kit**: exact site name, canonical URL, one-liner, category, contact email (dedicated alias), logo assets, and the description ladder (tagline / 60-char / 150-word / 300-word). Every submission draws from this kit. Template in `references/positioning-variations.md`.

### Rule 2: Quality bar — skip spam
Only submit to platforms that are (a) indexed and alive, (b) DR ~40+ **or** genuinely niche-relevant, and (c) editorially maintained. Low-quality directory blasts don't help and can hurt. Never buy "500 directories for $99" packages.

### Rule 3: Vary the descriptions
Never paste the identical description everywhere — search and AI engines discount duplicated boilerplate. Vary the opening sentence and emphasis per surface type using the variant rules in `references/positioning-variations.md`. (The brand *facts* — name, URL, category — stay identical everywhere.)

### Rule 4: Pace the velocity
Drip submissions — roughly **5–10 per week** — rather than 60 in one day. A sudden spike of near-identical new links looks manufactured. Slow is also easier to track and verify.

---

## Workflow

### Step 1: Readiness check

Quick gate — all should be "yes" before submitting:

1. Site is live, indexed, and has real content (not a placeholder).
2. Brand kit locked (Rule 1) — including logo in PNG + square format.
3. **Dedicated email alias** for signups (e.g., `listings@domain.com`) + password manager entries. Directories generate spam; keep it out of the main inbox.
4. **Address decision made.** Many business directories require a street address. Decide once: registered business address or virtual office — **never a home address** on public listings. Platforms that don't require an address are marked in the catalog.
5. Baseline recorded: current DR and referring-domain count (Ahrefs/Moz/Semrush), so progress is measurable.

### Step 2: Audit what already exists

Before creating anything, find what's already out there:

- Search Google for `"[site name]"` and `"[domain]" -site:[domain]` — list existing profiles and listings.
- Check the big platforms directly (Crunchbase, LinkedIn, Facebook, major directories) for unclaimed or outdated entries.
- **Claim and fix before creating new.** Duplicate profiles split brand signals and look sloppy; outdated ones (old URL, old branding) actively hurt.
- Log everything found in the tracker with status `Existing — claimed` or `Existing — needs fix`.

### Step 3: Choose the tiers

Full catalog in `references/directory-list.md`. Summary:

| Tier | What | Address needed? | Typical count |
|---|---|---|---|
| **Tier 1 — Core identity profiles** | LinkedIn company page, Crunchbase, Facebook, X, YouTube, Pinterest, Instagram, Gravatar, About.me | No | ~10 |
| **Tier 2 — Web & business directories** | Hotfrog, Brownbook, Cylex, WebWiki, chamberofcommerce.com, Curlie, D&B | Usually yes | ~10–15 |
| **Tier 3 — Content & publishing profiles** | WordPress.com, Blogger, Tumblr, Medium, Substack, SlideShare, Scribd, Issuu | No | ~8–12 |
| **Tier 4 — Blog & RSS directories** | Feedspot, Alltop, Blogarama, OnToplist | No | ~5 |
| **Tier 5 — Bookmarking & curation** | Scoop.it, Diigo, Pearltrees, Folkd, Flipboard, Mix | No | ~5 |
| **Tier 6 — Niche directories** | Education/topic directories that genuinely fit the site | Varies | ~5–10 |
| **Tier 7 — Local layer** (conditional) | Google Business Profile, Bing, Apple, Yelp, data aggregators, citations | **Yes — real address only** | ~15–25 |

**Triage rules:**
- Tier 7 applies **only** if the business has a genuine physical presence. Never fake an address for Google Business Profile — suspension risk, and fake local presence poisons trust.
- Tier 6: only genuine topical fits. A forced listing in the wrong category gets rejected or ignored.
- Skip anything already covered by Step 2's audit.

### Step 4: Prepare the submission kit

Assemble once, reuse everywhere (template in `references/positioning-variations.md`):

- Brand facts: name, URL, category, founding year, contact email
- Description ladder: tagline (<10 words), 60-char, 150-word, 300-word
- 5–8 category tags per surface type (rotate, don't repeat exact sets)
- Logo: PNG + square 1024×1024 + favicon
- 2–3 representative screenshots/images
- Social handles (for profile cross-linking)

### Step 5: Batch submit (the automatable part)

Work through the tracker (`references/submission-tracker-template.csv`) in weekly batches of 5–10.

Per submission:
1. Pull the surface-appropriate variant from the kit.
2. Fill the form (browser automation handles most of these; CAPTCHAs and email-verification clicks stay manual).
3. Use the dedicated email alias; store credentials in the password manager.
4. Log: date, URL, status, notes.
5. Confirm the verification email same-day — unverified submissions silently expire.

**Automation notes:** the submission kit exists so an agent can fill forms without improvising. Keep a per-platform note of quirks (character limits, category names) in the tracker's Notes column — it makes the next site's run faster.

### Step 6: Verify and maintain

- Once live, check the listing renders correctly and the link works.
- Dofollow check where it matters: inspect the link for `rel="nofollow"`/`"ugc"`, or `curl -sL <listing-url> | grep -io 'rel="[^"]*"'` near your domain's anchor.
- **Quarterly re-verify:** platforms silently flip links to nofollow, break URLs, or delete dormant profiles. Re-check the top 20 by DR.
- Keep Tier 1 profiles minimally alive (logo current, description current, occasional post). A graveyard of abandoned profiles is a bad brand signal.

---

## Local Layer (Tier 7 — only with a real address)

If the business has a genuine physical location (office, campus, storefront), add the local stack. Compressed playbook:

1. **NAP rule:** Name, Address, Phone identical byte-for-byte on every listing. Lock the canonical block first (template in `references/positioning-variations.md`).
2. **Google Business Profile** is the anchor: claim, verify, pick precise categories (for a school: "Nursing school" / "Vocational school" / "Adult education school"), complete every field, add real photos. Never keyword-stuff the business name (suspension risk).
3. **Then:** Bing Places, Apple Business Connect, Yelp, Facebook, Nextdoor.
4. **Data aggregators:** Data Axle Local Listings, Localeze (TransUnion), Foursquare — these feed the long tail of local directories.
5. **Core citations:** BBB, YP.com, Superpages, MapQuest, Manta, local Chamber of Commerce.
6. **One profile per location** — multi-location businesses get one GBP and one landing page per location, never a shared one.
7. **Reviews** (Google first) become the dominant local ranking factor — ask genuinely, never buy or incentivize, respond to all.
8. Vertical authority pages where they exist (for a training program: the state's approved-program list, testing-vendor locator, workforce/ETPL listings) are worth more than any directory link.

Full local catalog in `references/directory-list.md` Tier 7.

---

## KPIs & Tracking

Track monthly against the Step 1 baseline. Judge the campaign on **diversity and verification**, not raw counts.

| Metric | Baseline | 90-day target |
|---|---|---|
| Referring domains | recorded | +30–50 quality domains |
| DR / Domain Authority | recorded | gradual lift (directories alone won't spike it) |
| Listings live & verified | 0 | 40–60 |
| Link-type mix (directory / profile / content / bookmark) | — | no single type >50% |
| Existing listings fixed/claimed | — | 100% of audit findings |
| Indexed listings (spot-check top 20) | — | 80%+ |
| Brand-name search: owned results on page 1 | — | 3–5 |

---

## What NOT to Do

1. **Don't buy mass-submission packages** ($60–$200 "500 directories" services). They hit spam directories that dilute the profile and can trigger spam classification.
2. **Don't submit to dead or junk directories** (DR <10, unmaintained, link farms). Verify a platform is alive and indexed before submitting — catalogs rot; several "classic" directories no longer exist.
3. **Don't paste identical descriptions everywhere.** Vary per Rule 3.
4. **Don't blast everything in one day.** Pace per Rule 4.
5. **Don't use exact-match keyword anchors.** Directory/profile links should be brand-name or bare-URL anchors — that's what natural foundation links look like.
6. **Don't fake a physical address** to unlock Google Business Profile or local directories. Suspension risk, and fake local presence poisons the brand.
7. **Don't put a home address on public listings.** Use the registered business or virtual-office address, or stick to no-address platforms.
8. **Don't create profiles you'll abandon.** Only claim what you'll keep minimally current; delete rather than orphan.
9. **Don't oversell the impact.** These are foundation links. If someone promises rankings from directories alone, they're selling snake oil.
10. **Don't drift into outreach.** Listicle pitching, guest posts, and press are different workflows with different economics — out of scope here.

---

## Task-Specific Questions

1. **Which site is this for, and what's its category?** (Sets Tier 6 niche picks and all descriptions.)
2. **What already exists?** (Existing profiles/listings → Step 2 audit first.)
3. **Is there a usable business address, and which one?** (Gates Tier 2 and Tier 7; never a home address.)
4. **Current DR and referring-domain count?** (Baseline for measuring.)
5. **Is there a dedicated email alias + password manager for signups?**
6. **Logo and image assets ready?** (PNG + square + favicon.)
7. **Any physical location?** (If yes, the local layer applies and Google Business Profile becomes the anchor.)

---

## Output Format

When the user asks for a directory/link-diversity plan, return:

1. **Audit findings** — existing profiles/listings: claimed, fixed, or flagged
2. **Brand kit** — the canonical facts + description ladder (actual copy, not placeholders)
3. **Tier plan** — which tiers apply, which don't, and why
4. **Weekly batches** — 5–10 submissions per week, sequenced by value
5. **Address & privacy decision** — what address (if any) appears publicly
6. **Tracker** — the CSV from `references/submission-tracker-template.csv`, pre-filled for the chosen tiers
7. **Verification cadence** — what to re-check and when
8. **Baseline + 90-day targets** — from the KPI table

Keep it actionable: every item should be executable this week, most of it by an agent.

---

## Related Skills

- **product-marketing** — the shared context document (`.agents/product-marketing.md`) this skill reads first for the site's category, audience, one-liner, and brand voice. Run it before this skill if the file doesn't exist yet.

> This is a trimmed fork of coreyhaines31/marketingskills. The upstream repo has ~45 other marketing skills (seo-audit, programmatic-seo, content-strategy, launch, etc.). Add any back with `/plugin` if you want their playbooks alongside this one.
