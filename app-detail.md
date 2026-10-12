# HabitFine — App Detail & Claims Register

**Status: OWNER-PROVIDED APP DETAILS ARE TO BE TREATED AS VERIFIED WHEN THE OWNER SAYS THEY WORK.**

The app owner explicitly instructed that the app details and functionality they provide and confirm as working should be treated as verified for this project. Record those claims as **OWNER-CONFIRMED**. This means confirmed by the owner, not independently runtime-tested by the assistant. For screenshots that only show a label/control, document the visible UI separately from any behavior not explicitly confirmed.

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
| Habit detail screen: edit, pause, share and delete controls | OWNER-CONFIRMED UI | User-supplied Morning Workout detail screenshots | Yes, describe visible controls |
| Habit completion status and daily schedule/category/stake labels | OWNER-CONFIRMED | Screenshot shows “Completed Today”, Every Day, Fitness and ₹50 stake for Morning Workout; treat owner-supplied app details as verified per owner's instruction | Yes, avoid implying payment transfer unless specifically confirmed |
| Current streak, best record, 30-day rate and total completed metrics | OWNER-CONFIRMED | Detail screenshot shows 1d current streak, 1d best record, 100% 30-day rate and total completed 1; these are screenshot-specific values, not universal claims | Yes, as UI capabilities; never use screenshot's sample values as general marketing metrics |
| Share Minimalist Streak Card | OWNER-CONFIRMED UI | Detail screenshot shows a share-card entry for WhatsApp & Instagram Story | Yes |
| Activity calendar with Week/Month/Year options | OWNER-CONFIRMED UI | October 2026 month calendar visible in screenshot | Yes |
| Accountability Stake summary: Stake/Miss, Unpaid Debt, Total Incurred, Clean status and Fine Jar entry | OWNER-CONFIRMED UI | Detail screenshot displays ₹50 stake/miss, ₹0 unpaid debt and ₹0 total incurred; describe UI, do not claim real-money movement beyond owner-confirmed behavior | Yes, precise UI description only |
| Total Focus Logged and Start Focus action from habit detail | OWNER-CONFIRMED UI | Screenshot shows 5 mins Total Focus Logged and Start Focus button; 5 mins is example screen data | Yes |
| Today's Reflection with Save action | OWNER-CONFIRMED UI | Reflection text area and Save button visible | Yes |
| Activity Timeline with Completed and Habit started events | OWNER-CONFIRMED UI | Timeline visible for Morning Workout | Yes |
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
- `screenshots/habit-detail-streak-activity.jpg` — Morning Workout detail, completion, streak metrics, share card and monthly activity calendar; supplied by owner.
- `screenshots/habit-detail-accountability-reflection.jpg` — accountability stake, Fine Jar, focus logging, reflection and activity timeline; supplied by owner.
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