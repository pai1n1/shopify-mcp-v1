# iMeow — Website / CVR Handoff

**For:** the session that will make the **real edits to imeow.store**.
**Store:** imeow.store · **Product:** cat air purifier (doubles as a scratcher).
**From:** the strategy/creative session. Last updated: Aug 5, 2026.

> **You can and should ask me questions.** Don't guess on facts (founder story, specs, real numbers, theme/app access). If anything below is unclear or you need assets/credentials, ask before building.

---

## The goal

**Increase conversion rate (CVR).** Traffic is cold Meta social, $140 price point, skeptical buyers. Right now: **~160 sessions, 0 add-to-cart, 0 purchases.** That number is the emergency and it drives the order of work below.

---

## Priority 0 — diagnose the 0 ATC BEFORE building pages

160 sessions with 0 ATC is **not** a missing-pages problem — missing trust pages lower CVR at the margin, they don't drive it to a literal zero. Two candidate causes; **sequence them, don't guess**:

1. **Rule out the funnel first (binary, 5 min):** on a real phone, open the live ad **inside the TikTok app** and **inside Instagram**, land on the product page, and try to **Add to Cart → reach checkout**. Also: have we *ever* had an order?
   - Can't ATC → it's the funnel. Stop everything else and fix it.
   - ATC works / orders exist → funnel is fine → it's an **audience** problem (low-intent cheap clicks; the ads show 20–30% CTR at very cheap CPC with "cute/aww" comments — the fingerprint of cat-video watchers, not buyers).
2. Also check: mobile page-load speed, Meta link-clicks vs Shopify sessions gap, a popup covering the buy button, and whether ATC is even *tracked* (orders but 0 ATC = tracking bug).

Install **Microsoft Clarity** (free) and watch session recordings to see where people actually drop.

---

## What I want built, and why

Trust pages — to prove iMeow is a **real, trusted, cat-loving brand** and kill the "is this a dropshipper?" skepticism that stops a cold visitor from spending $140. **I have everything except these trust pages.**

| Page | Why |
|---|---|
| **Homepage** | Trust + proof of business, cat-heavy, community-driven |
| **Founder page** | Humanizes the brand, tells our story |
| **Contact page** | Legitimacy + reachability lowers purchase anxiety |
| **Blog page + cat research articles** | Substantiates our claims, builds authority, SEO |
| **UGC / community wall** | Real cats + real customers = social proof and community |

**Homepage section order:** Hero → Proof of business → Cats/community (UGC) wall → Founder snippet → Blog sections → Reviews (we have video + written) → FAQ (we have) → Footer (contact, blog, our story, socials).

(Full page structures are in `creative/site-cvr-plan.md`.)

---

## Creative direction — IMPORTANT shift

The ads use a Pixar-style animated cat (the winning `bolt` envy angle). For the **website**, I want a different, warmer register:

- **REAL lifestyle content — cats AND people.** Real homes, real cat parents with their cats, the purifier living in an actual room. Not the animated look.
- **Both formats: photo AND video.** Static lifestyle photos *and* short lifestyle videos. Where useful, animate a photo into video (photo → motion) so we get both out of one asset.
- Warm, authentic, community feel — this is the trust layer, so it should feel human and real, not like an ad.
- Keep brand voice consistent with the campaign: envy → provider guilt → absolution; calm and matter-of-fact; refer to the cat as **they/them** (unisex, works for any cat).

---

## Facts I need to supply (ask me)

Don't invent these — ask:
- **Founder:** name / persona + the true origin story (why iMeow was built).
- **Proof numbers:** real customers/units sold, review count + rating, any press. *(Only what's true — fake proof is flaggable and repels skeptics.)*
- **Specs:** HEPA type, noise (dB), coverage (sq ft), filter life. (For the buy-box proof row + blog.)
- **Contact:** support email, response-time promise, socials, business location.
- **Pricing:** confirm $140 (1 unit) / $240 (2 units).
- **Community:** any shelter/giving-back involvement (only if real).
- **Access:** Shopify theme editor access, which apps are installed, brand assets/logo/fonts.

---

## Upsell / LTV (filters + scratchers) — where the profit is

At a ~$58 CPA on a $140 order, first-order profit is thin; the **consumables** (replacement filters + scratcher pads) are the real margin. Build:
- **Subscribe & Save** on the product page (auto-ship filters/pads, discounted).
- **Post-purchase one-click upsell** ("add a year of filters" on the thank-you page).
- **Starter-kit tiers** (unit / unit + 1yr filters / unit + 2yr filters + scratchers).
- Frame the replacement as **proof it works**, not a hidden razor-and-blades cost.

---

## Guardrails

- **Funnel fix before pages** — don't build pretty pages over a broken button.
- **Only true claims / real numbers.** No fabricated proof.
- **Remove the "#1 air purifier built for cats" claim** (unsubstantiated, flaggable, reads dropshipper).
- Storefront edits happen in the **Shopify theme editor / admin** — this repo (`shopify-mcp-v1`) is an MCP server for products/orders/customers and has **no page/blog tools** yet (could be added if we want programmatic publishing).

---

## Reference files (in `creative/`)

- `vo-lineup.md` — ad VO scripts + beat-synced storyboards (A1/B/C).
- `site-cvr-plan.md` — trimmed site plan (homepage + trust pages structure).
- `website-tasks.md` — funnel-first website task list.
