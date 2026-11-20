# iMeow — "Fur Babies" Commercial Creative Brief
**Handoff for Claude Code session** · Aug 6, 2026

---

## Context

**Brand:** iMeow (imeow.store) — air purifier built for cat households
**Price:** $139.99 (1 unit) / $239.99 (2 units), free shipping
**Channel:** Meta ads (Feed + Reels), 9:16 vertical
**Deliverable:** ~20s commercial-style video ad, assembled from AI-generated clips

**Why this ad exists:** The account's proven creative (`bolt`) runs on an *envy* mechanism — an animated cat watching a neighbor cat who has clean air. This spot tests a second, different angle: **recognition**. The viewer sees their own chaotic cat household on screen, laughs, and then gets hit with the thing they'd stopped noticing.

**Emotional arc:** funny and relatable → turn at 0:12 → warm resolution.

---

## ⚠️ Compliance Constraints (non-negotiable)

The previous ad was rejected under Meta's **Unacceptable Business Practices** policy. These rules exist to avoid a second strike, which risks account restriction.

- **No Instagram/Facebook UI mimicry.** No platform icons, fake like counts, follow buttons, or comment UI.
- **The on-screen meter must be clearly stylized.** Label it **"chaos level"** — never "AQI," never a µg/m³ reading, never anything that looks like a measured air-quality result.
- **No absolute efficacy claims.** Use "helps capture" / "runs quietly in the background," never "removes 99%" or "eliminates."
- **No health or allergy claims.** No sneezing, allergies, breathing, or respiratory language anywhere in captions or copy.
- **Disclose AI-generated content** in Meta's ad settings.

---

## Shot List

| # | Time | Shot | Caption | Chaos Level |
|---|---|---|---|---|
| 1 | 0:00–0:02 | Tabby sprints left→right, cushion tumbling in its wake | **sometimes the fur babies get the zoomies** | 🟢 GOOD |
| 2 | 0:02–0:04 | Macro: cat shakes a plush toy, cotton bursting out | | 🟢 GOOD |
| 3 | 0:04–0:06 | Low angle: second cat launches off the sofa back, mid-air | **and it gets a little hectic** | 🟡 FAIR |
| 4 | 0:06–0:08 | Wide: shredded couch arm, fur drifting in window light | | 🟡 FAIR |
| 5 | 0:08–0:10 | Woman smirking/laughing, chasing a cat right→left | **ok maybe a lot hectic** | 🟠 POOR |
| 6 | 0:10–0:12 | Slow-mo: cotton and fur suspended in a shaft of light | **you stop noticing after a while** | 🔴 BAD |
| 7 | 0:12–0:14 | Cat lying calmly in the haze, slow blink, rack focus to her face | **but the air always notices** | 🔴 BAD |
| 8 | 0:14–0:16 | Purifier powers on, light ring, fur drawn toward intake | | 🟠 → 🟡 |
| 9 | 0:16–0:18 | Room bright and clear, cats asleep near the unit | **iMeow embraces the chaos** | 🟢 GOOD |
| 10 | 0:18–0:20 | Product card | **From $139.99 · Free shipping** | 🟢 |

### The turn (0:12)
Shot 7 is the pivot. Hold it a beat longer than feels comfortable, cut the music to silence, and let the rack focus land on her face. Everything before is comedy; everything after is warmth. If this beat is rushed, the ad is just a funny cat video.

---

## Generation Approach

**Do not attempt one continuous clip.** Realistic cat motion degrades badly over long durations. Generate **10 separate 2–3s clips** and assemble. The rapid cutting reinforces the chaotic energy, so the constraint helps.

Generate **4–5 variations per shot.** Most will fail — cats in motion are the hardest thing to generate. Budget for the volume.

### Base style block — prepend to every prompt

```
Cinematic commercial film, shot on ARRI Alexa with 35mm anamorphic lens,
shallow depth of field, soft directional key light through large windows
with warm bounce fill, modern upscale living room with neutral palette and
natural wood, dust and fur particles catching the light, slow deliberate
camera movement on a gimbal, high production value, color-graded warm and
clean, no text.
```

### Per-shot action prompts

| # | Action |
|---|---|
| 1 | a tabby cat sprints across frame left to right in slow motion, cushion tumbling in its wake, particles kicked into the light |
| 2 | macro close-up, a cat shakes a plush toy, white cotton fibers bursting out and drifting through a sunbeam |
| 3 | low-angle hero shot, a cat leaps off the back of a sofa toward camera, mid-air, fur suspended around it |
| 4 | wide shot, a shredded couch arm with stuffing exposed, loose fur drifting through window light |
| 5 | a woman laughing warmly, reaching toward a cat running past her, smooth tracking shot, natural performance |
| 6 | slow motion detail, cotton fibers and cat fur floating through a shaft of window light against a dark background |
| 7 | a cat lying calmly on a rug, blinking slowly, dust visible in the air around her, soft rack focus onto her face |
| 8 | product hero shot, a white cylindrical air purifier switches on, subtle light ring illuminating, fur particles drawn toward the intake, dark clean background |
| 9 | wide establishing shot, the same living room now bright and clear, two cats asleep near the purifier, golden hour light |

### Consistency requirements
- Same room description, palette, and lighting direction in **every** prompt
- Same cat breed and coat color across shots 1, 3, 6, 7, 9
- Slow motion on shots 1, 3, 6 — biggest signal of commercial polish, and it makes floating particles readable
- Shot 8 uses a **different lighting setup**: darker, higher contrast, product-hero treatment. That contrast is what sells the purifier as a solution rather than set dressing.

---

## Chaos Level Meter

Persistent overlay, top-right corner, small.

- Rounded pill: colored dot + label
- Label reads **"chaos level"** — never AQI or a numeric reading
- States: 🟢 GOOD → 🟡 FAIR → 🟠 POOR → 🔴 BAD → back to 🟢
- Animate the transitions (~0.3s color/label crossfade) so viewers register the change
- Clean sans-serif, semi-transparent dark background, subtle. Designed, not meme-y.

---

## Audio

- Upbeat playful indie/lo-fi with forward momentum through 0:00–0:12
- **Full silence at 0:12** for the "but the air always notices" beat
- Warm, calm re-entry the moment the purifier powers on at 0:14
- Sound design: cat paws, a knocked cushion, a soft toy-shake — keep it light
- Purifier power-on gets a low, satisfying hum — resolution, not machinery

---

## Captions

Burned in, added after video generation. Bold sans-serif, high contrast, centered lower third, safe from Reels UI overlap. Lowercase for the comedy beats, sentence case for the turn.

---

## Post Copy

> Cat households are chaos and we wouldn't change it. But she's breathing all of it — fur, dust, litter, and whatever's left of the couch. iMeow runs quietly in the background so the room stays fresher.
>
> From $139.99 · Free shipping · 30-day returns
> 👉 imeow.store

**Headline:** Built for cat households
**CTA:** Shop now

---

## Definition of Done

- [ ] 10 clips generated, best variation selected per shot
- [ ] Assembled to ~20s, 9:16, cuts on the beat
- [ ] Chaos meter overlay animated across all states
- [ ] Captions burned in per the shot list
- [ ] Music with the 0:12 silence drop and 0:14 re-entry
- [ ] Compliance pass: no platform UI, no AQI language, no health claims, no absolute efficacy claims
- [ ] AI-content disclosure enabled in Meta ad settings
- [ ] Launched as a **new ad in a separate test ad set** — do not add to an ad set with purchase history
