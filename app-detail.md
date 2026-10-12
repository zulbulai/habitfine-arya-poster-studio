# HabitFine — App Detail & Claims Register

**Status: PARTIALLY DOCUMENTED FROM USER-SUPPLIED SCREENSHOTS; behavior and entitlements still need verification against the current app build.**

This is the source of truth for public product claims. A visible label proves that the UI displayed that label in a supplied screenshot; it does not by itself prove backend behavior, eligibility or current availability.

## Product identity
- Product name: HabitFine: Daily Habit Tracker
- Android package: `com.procsctools.habitfine`
- Official listing supplied by project owner: https://play.google.com/store/apps/details?id=com.procsctools.habitfine
- Brand ambassador: Arya, a fictional/AI-generated adult Indian fitness-lifestyle creator.

## Status definitions
- **SCREENSHOT OBSERVED** — label/control is visible in a user-supplied screenshot; behavior is not independently tested.
- **CONFIRMED** — verified in the current app build or current official listing with evidence.
- **UNVERIFIED** — mentioned in prior notes or screenshots but implementation/current availability not checked.
- **PLANNED** — future capability only; never market as available.
- **NOT SUPPORTED** — explicitly ruled out or no evidence; do not claim.

## Feature claim register

| Claim | Status | Evidence / limit | Public use now? |
|---|---|---|---|
| Daily habit dashboard, completion counts and progress presentation | SCREENSHOT OBSERVED | Home dashboard screenshot supplied earlier; calculations not tested | Describe only the visible UI, avoid outcome promises |
| Streak label on habit/dashboard UI | SCREENSHOT OBSERVED | Home screenshot; calculation/reset rules not tested | No streak duration guarantees |
| Focus / Morning Workout timer UI | SCREENSHOT OBSERVED | `focus-timer.jpg` referenced in earlier screenshot manifest; timer behavior not independently tested | UI-only wording until tested |
| Theme mode: System, Light, Dark | SCREENSHOT OBSERVED | `appearance-theme-accent-palette-preview.jpg` | UI-only description |
| Named accent palettes: Electric Violet, Crimson Flame, Neon Flame, Sunset Amber, Royal Gold, Emerald Mint, Cyber Teal, Ocean Blue, Deep Indigo, Berry Rose | SCREENSHOT OBSERVED | Appearance screenshot displays 10 palette names | UI-only description |
| Background surface choices: Default, Gradient, Dot Matrix, OLED Black, Custom | SCREENSHOT OBSERVED | `appearance-background-check-button.jpg` | UI-only description |
| Check button style: Square/Circle; app icon style: Default/Neutral/Accent; card density: Expanded/Compact | SCREENSHOT OBSERVED | Appearance settings screenshots | UI-only description |
| Celebration options: Confetti, Fireworks, Surprise me, None | SCREENSHOT OBSERVED | `appearance-icon-density-celebration.jpg` | UI-only description |
| Settings menu: Appearance, Preferences, Audio Studio, Widgets, Data, Support, Accountability & Fines, Achievements | SCREENSHOT OBSERVED | `settings-main-menu.jpg`; destination screens/behavior not tested | Mention only as visible menu labels |
| To-Do screen with All/Inbox/Work lists, Today/Tomorrow/Upcoming/Completed filters, priorities and time-of-day labels | SCREENSHOT OBSERVED | `todo-tasks-screen.jpg`; persistence/notifications not tested | UI-only description |
| HabitFine Plus screen displays an active yearly plan, 365 Days Left, Unlimited Habits, Full Analytics, Streak Freeze, Fine Savings, Widget Studio, 10 Theme Palettes, Spreadsheet Export, Automatic Backup | SCREENSHOT OBSERVED | `plus-yearly-plan-features.jpg`; screenshot does not verify current prices, eligibility or backend behavior | Do not make broad availability/entitlement promises without verification |
| Daily habit tracking/check-offs | UNVERIFIED | Current behavior and limits need test | No detailed feature promise |
| Streak tracking calculation and freeze behavior | UNVERIFIED | Current app behavior needs test | No duration promises |
| Analytics details and charts | UNVERIFIED | Plus screen says Full Analytics / All charts; actual charts need inspection | Avoid exact analytics promises |
| Audio Studio, offline soundscapes and alarm sounds | UNVERIFIED | Settings label says “Check-in tones, alarms & offline soundscapes”; behavior not tested | No detailed promise |
| Widgets and five widget styles | SCREENSHOT OBSERVED | Settings screen says “Home screen widgets (5 styles)”; each style and refresh behavior not tested | UI-only wording pending test |
| Data backup, import, automatic backup, spreadsheet export | UNVERIFIED | Menu/paywall labels visible; formats, destinations, schedule and restore need test | No backup-safety guarantees |
| Accountability & Fines / Fine Savings / penalty vault / UPI | SCREENSHOT OBSERVED | Menu/paywall labels only; exact mechanics and money movement unverified | Never imply real money transfer or automatic penalty without verification |
| Achievements, badges and discipline milestones | SCREENSHOT OBSERVED | Menu label says “Badges and discipline milestones”; details not tested | UI-only wording |
| Historical prices ₹21/month, ₹99/year, ₹249 lifetime | HISTORICAL — UNVERIFIED | Current billing/paywall required | Never publish without verification |
| Promo code `TRYYEAR` gives one year of Pro free | USER-PROVIDED — UNVERIFIED | Test redemption, duration, eligibility and terms | Do not publish yet |
| Automatic 10,000-step tracking | NOT SUPPORTED BY CURRENT EVIDENCE | A habit named “10,000 Daily Steps” is not proof of sensor-based step tracking | No |
| Hydration measurement, nutrition tracking, wearable/cloud sync, AI coach | NOT SUPPORTED BY CURRENT EVIDENCE | No explicit implementation proof | No |
| Guaranteed habit formation, health outcomes or productivity gains | NOT A VALID PRODUCT CLAIM | Cannot be guaranteed | No |

## Screenshot evidence log
- `screenshots/appearance-icon-density-celebration.jpg` — appearance controls and celebration options; screenshot supplied by user, October 2026 conversation.
- `screenshots/appearance-background-check-button.jpg` — background/check-button/icon/card-density choices; screenshot supplied by user, October 2026 conversation.
- `screenshots/appearance-theme-accent-palette-preview.jpg` — theme mode, 10 accent palettes and live preview; screenshot supplied by user, October 2026 conversation.
- `screenshots/settings-main-menu.jpg` — settings menu; screenshot supplied by user, October 2026 conversation.
- `screenshots/plus-yearly-plan-features.jpg` — yearly plan and listed Pro features; screenshot supplied by user, October 2026 conversation.
- `screenshots/todo-tasks-screen.jpg` — To-Do UI; screenshot supplied by user, October 2026 conversation.

The renamed image files are packaged in the separately provided `habitfine-screenshots-renamed.zip`. Their binary contents are not yet verified as uploaded to this GitHub repository.

## TRYYEAR validation checklist
- [ ] Code currently works in the intended redemption flow.
- [ ] It grants exactly one year of HabitFine Pro.
- [ ] Eligibility and redemption limits are known.
- [ ] Expiry date, if any, is confirmed.
- [ ] Terms are recorded accurately.
- [ ] Offer is active at publication time.

If any item is unknown, omit the offer or flag it as awaiting confirmation in internal drafts only.

## Updating
Do not promote SCREENSHOT OBSERVED or UNVERIFIED to CONFIRMED based on old copy, AI-generated posters or memory. Test current behavior and record evidence before publishing claims.