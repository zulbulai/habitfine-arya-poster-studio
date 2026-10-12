---
name: habitfine-arya-poster-studio
description: Create art-directed Instagram posters, captions, carousel concepts, and image prompts for HabitFine featuring the established AI influencer Arya, with strict product-claim verification and brand-asset handling.
---

# HabitFine × Arya Poster Studio

Use this Skill to create polished, publication-oriented Instagram creatives for HabitFine featuring Arya. Produce creative direction, exact copy, image prompts, layout/compositing guidance, and a matching caption. Do not claim to render final image files unless an image-generation or design tool is actually used.

## Trigger when
The user requests a HabitFine Instagram poster, Arya campaign, image prompt, story, Reel cover, carousel, caption, or campaign plan. Respect scope requests such as “only prompt,” “only caption,” or “poster copy only.”

## Required reading sequence
Read these files before drafting:
1. `app-detail.md`
2. `references/app-feature-and-claims-policy.md`
3. `references/habitfine-brand-guide.md`
4. `references/arya-character-bible.md`
5. `references/instagram-layout-system.md`
6. `references/poster-copywriting.md`
7. `references/instagram-caption-system.md`
8. `references/image-generation-prompts.md`
9. `references/negative-prompt-library.md`
10. `references/campaign-playbook.md`
11. `references/example-posters.md` when examples help.

If `app-detail.md` is a template or a feature lacks CONFIRMED evidence, do not invent the feature. Ask for current screenshots or use a neutral brand-level concept.

## Source-of-truth hierarchy
1. `app-detail.md` with evidence/status.
2. Current genuine app screenshots and app behavior.
3. Current official Google Play listing: https://play.google.com/store/apps/details?id=com.procsctools.habitfine
4. Supplied official logo, mascot and approved Arya references.
5. Explicit user instructions.
6. Old copy/reference examples (never proof of a feature).

## Owner-provided evidence policy
The app owner explicitly instructs this Skill to treat app details and functionality they supply and confirm as working as verified for this project. Record these as `OWNER-CONFIRMED`; do not repeatedly ask for proof or label them unverified merely because the assistant did not run the app. Keep the distinction between owner-confirmed and independently runtime-tested explicit in internal documentation. If a screenshot only shows a label and the owner has not confirmed the underlying behavior, describe the visible UI without inventing hidden implementation details.

## Asset handling
Check `assets/README.md`, `screenshots/README.md`, and the actual files before using them. All supplied genuine HabitFine screenshots must be committed as image binaries inside this repository's `screenshots/` folder—not merely listed in a README or left in a separate ZIP. Before saying they are included, inspect the GitHub tree and verify each binary path exists. Genuine HabitFine app screenshots belong in `screenshots/`; use them as references for the real shipped UI only, never invent or embellish product screens. `assets/HabitFine-mascot.webp` is the supplied transparent blue mascot reference: use the actual asset as-is for compositing and never redraw it with an image model. Use `assets/HabitFine-app-icon.png` as the official app icon/logo only if that file is present. Use the primary Arya portrait plus front/profile/full-body references to preserve identity. Use actual app screenshots only; never fabricate product UI, stats, prices or badges. If an asset is absent, identify it clearly; do not pretend a missing image exists or claim upload completion. If binary upload cannot be performed with available tools, report that limitation plainly and leave the upload status as incomplete.

## Workflow
1. Parse objective, audience, language, campaign angle, format and requested scope.
2. Verify each product claim against `app-detail.md`; omit UNVERIFIED, HISTORICAL, PLANNED or unsupported claims.
3. Choose one message: awareness, confirmed feature spotlight, routine inspiration, or validated promotion.
4. Art-direct Arya consistently using the character bible and actual references.
5. Write concise headline, supporting line and CTA. Do not rely on image generation to render final text accurately.
6. Write an image prompt with composition, lens/lighting, pose, environment, negative space, aspect ratio and natural anatomy. Include the relevant supplied reference images.
7. Specify compositing for typography, the official mascot/logo and genuine screenshots as separate layers. Place the real `HabitFine-mascot.webp` asset into the layout; do not generate a substitute mascot.
8. Include a matching caption package by default: caption, alternative hook, relevant hashtags, optional first comment, alt text and publication checks.
9. Run QA for claims, identity, logo, screenshot authenticity, spelling, readability, safe areas and CTA.
10. Disclose missing assets, unverified claims and tool operations not performed.

## Default output format
Unless the user requests a subset:
1. Campaign Concept
2. Exact Poster Copy (headline, supporting line, optional label, CTA)
3. Arya Art Direction (setting, pose, expression, wardrobe, lighting, framing)
4. Image Generation Prompt
5. Negative Prompt
6. Layout & Compositing Specification
7. Instagram Caption Package
8. Creative QA checklist

## Formats
- Instagram feed: 1080 × 1350 px (4:5), default.
- Story/Reel cover: 1080 × 1920 px (9:16).
- Square: 1080 × 1080 px (1:1).
- Carousel: 3–7 slides with consistent branding and safe areas.

## TRYYEAR offer
The code `TRYYEAR` is user-provided but unverified. Do not include it in public copy unless `app-detail.md` documents current successful validation, duration, eligibility, redemption steps and terms. Never invent an expiry date or scarcity.

## Brand and honesty rules
- No fake metrics, ratings, testimonials, downloads, awards, prices or scarcity.
- No guaranteed habit, fitness, health or productivity outcomes.
- Do not claim step tracking, hydration measurement, nutrition tracking, wearable sync, cloud sync, AI coaching or real-money penalties without explicit CONFIRMED evidence.
- Never market planned or historical features as live.
- Do not claim that a poster was generated, edited, tested or exported unless that action actually occurred.
- Keep tone grounded, encouraging and specific.

## Reference files
See `app-detail.md`, `references/`, and `assets/README.md`.
