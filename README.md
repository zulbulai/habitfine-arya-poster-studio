# HabitFine × Arya Poster Studio

A Claude Skill for planning premium Instagram posters, carousel concepts, image-generation prompts, layout/compositing specs, and matching captions for HabitFine featuring Arya.

## Contents

- [`SKILL.md`](SKILL.md) — main Skill workflow and safety rules
- [`app-detail.md`](app-detail.md) — product claim register; features are not considered confirmed without evidence
- [`references/arya-character-bible.md`](references/arya-character-bible.md) — Arya identity consistency
- [`references/habitfine-brand-guide.md`](references/habitfine-brand-guide.md) — brand and official-logo rules
- [`references/instagram-layout-system.md`](references/instagram-layout-system.md) — canvas, safe areas and compositing
- [`references/instagram-caption-system.md`](references/instagram-caption-system.md) — caption, hook, hashtags and alt text
- [`references/app-feature-and-claims-policy.md`](references/app-feature-and-claims-policy.md) — claim verification
- [`references/poster-copywriting.md`](references/poster-copywriting.md) — copy principles
- [`references/image-generation-prompts.md`](references/image-generation-prompts.md) — prompt recipe
- [`references/negative-prompt-library.md`](references/negative-prompt-library.md) — negative prompts
- [`references/campaign-playbook.md`](references/campaign-playbook.md) — campaign concepts
- [`references/example-posters.md`](references/example-posters.md) — safe examples and QA
- [`assets/README.md`](assets/README.md) — asset manifest and availability notes
- [`assets/HabitFine-mascot.webp`](assets/HabitFine-mascot.webp) — uploaded transparent mascot reference
- [`screenshots/README.md`](screenshots/README.md) — dedicated folder and rules for genuine app screenshots

## Install/use

1. Download or clone this repository.
2. Ensure `SKILL.md` is at the root of the Skill folder.
3. Review `assets/README.md` and confirm every referenced asset exists before use.
4. Review `app-detail.md` against the current shipped app and update claim statuses only when evidence exists.
5. Package/import the folder in the Claude Skills interface and test both a neutral-awareness brief and a confirmed-feature brief.
6. Verify “only caption” and “only prompt” requests are respected.

## Canvas sizes

- Instagram feed: 1080 × 1350 px (4:5), default
- Story/Reel cover: 1080 × 1920 px (9:16)
- Square: 1080 × 1080 px (1:1)
- Carousel: 3–7 consistent slides

## Asset status

The uploaded transparent blue mascot is included at `assets/HabitFine-mascot.webp`. Other official icon and Arya reference images, along with genuine app screenshots, are not all uploaded yet; check `assets/README.md` for the exact manifest. Do not assume a filename means the file exists.

## Product-claim and offer safety

Do not invent UI, features, ratings, downloads, testimonials, prices, scarcity, or guaranteed outcomes. The `TRYYEAR` offer is user-provided but unverified and must not appear in public copy until current redemption and terms are checked.

## Validation status

The mascot asset and documentation updates were committed to the repository. This Skill has **not** been installed or runtime-tested inside Claude. Current app features and the promotion have not been independently verified.
