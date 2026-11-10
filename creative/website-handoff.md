# iMeow — Site Editing Session Handoff

**For:** the session making **real edits to imeow.store**.
**Store:** imeow.store · **Product:** cat air purifier (doubles as a scratcher).
**Last updated:** Aug 5, 2026.

> **You can and should ask me (the owner) questions.** Don't guess on facts (founder story, specs, real numbers, theme/app access, brand assets). Ask before building.

---

## The goal

**Increase conversion rate (CVR).** Cold Meta social traffic, $139 price, skeptical buyers. Current alarm: **~160 sessions, 0 add-to-cart, 0 purchases.**

---

## How this project is being built (workflow)

1. **Claude design session** builds the website structure + UI (visual design).
2. I bring that design **into Shopify**.
3. **You (the editing/Claude Code session)** implement + **polish** — Liquid/sections, sticky ATC, page speed, and the fixes below.

**IMPORTANT:** the incoming Claude-designed site **did not use everything we planned.** Part of your job is to **audit the design against this doc, flag the gaps, and recommend + make improvements — especially on the PDP** (see the PDP section).

---

## Priority 0 — diagnose the 0 ATC BEFORE polishing pages

160 sessions with 0 ATC is **not** a missing-pages problem — missing pages don't drive ATC to a literal zero. **Sequence the two candidate causes, don't guess:**

1. **Rule out the funnel first (binary, 5 min):** on a real phone, open the live ad **inside the TikTok app** and **inside Instagram**, land on the product page, and try to **Add to Cart → reach checkout**. Have we *ever* had an order?
   - Can't ATC → it's the funnel. Fix this before anything else.
   - ATC works / orders exist → funnel is fine → it's an **audience** problem (cheap low-intent clicks; 20–30% CTR, "cute/aww" comments = cat-video watchers, not buyers).
2. Also check: mobile load speed, Meta link-clicks vs Shopify sessions gap, a popup covering the buy button, and whether ATC is even *tracked* (orders but 0 ATC = tracking bug).
3. Install **Microsoft Clarity** (free) → watch session recordings to see where people drop.

---

## HOMEPAGE structure (this is the HOME page — NOT the PDP)

The alternating **claim → proof → claim → proof** rhythm we designed. It's built to reassure a skeptical cold-traffic buyer: every lifestyle claim is immediately backed by proof.

| # | Section | Its one job |
|---|---|---|
| 1 | **Cat w/ product** (hero) | Emotional promise + **scent-match to the ad** (same palette + animated mascot accent) + price + CTA + trust microcopy |
| 2 | Social proof | Star rating + "[X,000]+ cat households" |
| 3 | **Cat w/ product** (info 2) | **How it works** — HEPA pulls dust/dander/litter; scratcher + purifier combo; proof row (HEPA · dB · sq ft · filter life) |
| 4 | Social proof 2 | **UGC / community wall** — real cats + owners, #iMeow |
| 5 | **Product** | Premium real product photography, what's in the box, price tiers, guarantee, ATC |
| 6 | Social proof | **Video reviews** |
| 7 | **Cat w/ product** | **Lifestyle / community** — real cat + owner life, founder snippet, "join the family" + CTA |
| 8 | Social proof (reviews) | **Written review carousel** + rating + final CTA → FAQ → footer |

**Rules for the homepage:**
- **Each "cat w/ product" block = ONE distinct message** (don't repeat the same pitch 4×).
- **Vary the proof TYPE** across the 4 proof slots (rating strip → UGC wall → video reviews → written reviews). Four identical review carousels = padding.
- **Scent match lives in block 1** — palette + mascot + the ad's promise, so the clicker knows it's the same brand.
- **Sticky ATC on mobile** the whole scroll, not just section 5.

---

## PDP — audit the current one and improve it (SEPARATE from the homepage)

The design session may not have nailed the PDP. **Compare the current PDP to the checklist below, report the gaps, and fix them.** A high-CVR PDP for a $139 cold-traffic product needs:

**Above the fold (the buy box):**
- Price + **2-pack framed** ("$240 for 2 = $120 each, save $40")
- **Free shipping + 30-day money-back guarantee**
- **Star rating + review count** at the top
- **Proof row:** HEPA · under 30dB · covers ___ sq ft · filter life
- **Add to Cart** obvious; **variant selection** obvious if required
- **Sticky ATC** on mobile

**Scent + value:**
- **Top of PDP echoes the ad** (palette + animated mascot + the "clean air" promise) so the click-through feels continuous
- **Premium real product photography** — the #1 perceived-value lever at $139
- **Filter cost stated plainly and reframed as proof it works** (not a hidden razor-and-blades trap)
- **Remove the "#1 air purifier built for cats" claim** (unsubstantiated, flaggable, reads dropshipper)

**Below the fold:**
- Objection-handling near the buy box; reviews (video + written); UGC
- **Upsell/LTV:** Subscribe & Save, post-purchase one-click ("add a year of filters"), starter-kit tiers

**Deliverable:** a short gap report — "PDP has X, is missing Y, here's the fix" — plus the implemented changes.

---

## Creative / design direction

- **Colorful, vibrant, cat-lover, community-forward — but PREMIUM in execution.** Color doesn't cheapen a page; *cheap execution* does (clip-art, clashing colors, low-res, clutter, inconsistent type). Hold the line on craft: intentional palette, whitespace, quality photography, consistent identity.
- **The animated cat = a mascot/accent** that bridges the ad and the site (scent match) — used as illustration, not the whole page.
- **Real lifestyle content: cats AND people, photo AND video** (including photo → motion). Warm and real *is* compatible with premium.
- **Do NOT change the ads.** The animated ads are cheap and profitable; switching to human/lifestyle ads means a whole new budget test at higher CPM/CPC/CPA. Message match is the **site's** job — the PDP echoes the ad, not the reverse.
- **Brand voice:** envy → provider guilt → absolution; calm, matter-of-fact; the cat is **they/them** (unisex).

## Perceived-value guardrails ($139)

Protect these; none is threatened by color: high-quality **product photography**, **guarantee** + reviews + review count, **specs/proof**, **whitespace/restraint**, consistent **brand identity**.

---

## Facts I need to supply (ask me)

- **Founder:** name/persona + true origin story.
- **Proof numbers:** real customers/units, review count + rating, any press. *(Only what's true.)*
- **Specs:** HEPA type, dB, coverage sq ft, filter life.
- **Contact:** support email, response-time promise, socials, business location.
- **Pricing:** confirm $139 (1 unit) / $240 (2 units).
- **Community:** shelter/giving-back involvement (only if real).
- **Access:** Shopify theme editor access, installed apps, brand assets/logo/fonts.

---

## Guardrails

- **Funnel fix before pages** — don't polish over a broken button.
- **Only true claims / real numbers.** No fabricated proof (flaggable, repels skeptics).
- Storefront edits happen in the **Shopify theme editor / admin**. This repo (`shopify-mcp-v1`) is an MCP server for products/orders/customers and has **no page/blog tools** (could be added for programmatic publishing).

---

## Reference files (in `creative/`)

- `vo-lineup.md` — ad VO scripts + beat-synced storyboards (A1/B/C).
- `site-cvr-plan.md` — trimmed site plan (pages).
- `website-tasks.md` — funnel-first website task list.
