# Motion Quest — v1.5 guided movement demo update

**Move · Flow · Grow**

A character-led movement companion designed for middle schoolers and accessible to a wider audience. The app uses full-color anime-style fantasy and animal characters **inside the real interface**. It works as a static website and stores user activity in browser local storage; no account is required.

## Install or publish

Upload `index.html` and the entire `assets/` directory to the root of a GitHub repository. Under **Settings → Pages**, select **Deploy from a branch**, `main` and `/ (root)` to publish. Or open `index.html` locally in a current browser. No build command or dependencies are required.

## Implemented now

- Six original full-color mascot character illustrations in workout, home, and cast screens.
- Nine-movement morning flow (60 seconds each, exactly 9 minutes when transition pauses are off).
- Six 30-second warm-up movements; combined start-my-morning routine totals 12 minutes.
- Gentle recovery and quick workout options; timed bodyweight strength circuit.
- Individual strength-variation choices saved on this device.
- Large color-changing timer; pause, restart, skip, and end controls; optional short transitions, chimes, and browser voice announcements with selectable device voices, adjustable narration speed, and a voice preview.
- Basic workout history, week graph, 14-day calendar, streak, optional energy rating, backup/import, and self-reported weekly report.
- Responsive phone/tablet layout, optional larger Workout Focus Mode, and reduced-motion control.

## Important visual fidelity note

The finished character art is used for **actual cards and coach screens**, not placeholder emoji. The workout screen now includes a dedicated **animated guided movement demo panel** for the nine-move flow, stretches, and beginner strength variations. These demos are simplified coaching visuals inside the app and are meant to support the live technique cues—not replace careful form instruction or professional guidance. The original video remains linked from the app so users can compare the source routine when helpful.

## Health and privacy

Movement suggestions are generic, low-pressure and include alternatives. This is not medical guidance. No birth date or weight is requested; local records don't sync across browsers/devices. Exports contain activity data chosen by the user. No student names or identifiers are required.

## Files

- `index.html` — entire standalone web app.
- `assets/*.webp` — six real game-style coach illustrations.
- `docs/design-system.md` — cast, brand, screen map, and release scope.


## What's new in v1.1

- **Choose a voice** in Settings: enable Spoken cues, select a device voice/accent, choose speaking speed, and press Preview voice. This uses the built-in Web Speech API; voice choices vary by browser/device and may require installed speech packs. No recorded character-specific voice actors are included.
- **Phone layout** is automatic: navigation moves to the bottom and workout panels stack for narrow screens. There is no separate mobile URL or mobile file.
- **Workout Focus Mode** can be enabled from Settings or directly during a workout to hide navigation and give more space to the coach image and timer. Switch off using Exit focus view.
- Existing local progress is preserved when overwriting the repository with v1.1 files in the same site/origin.


## v1.2 — Gamification

Adds the optional 67-Day Adventure with Explorer, Momentum, and Iron Quest (reset-on-missed-day) rules, a 162-badge collection (derived from completed workout history), lifetime XP, levels, daily quest board, and nine adventure milestones. Existing browser progress, guide choice, voices, and workout timers are preserved. Backup exports now include challenge settings. The rewards are progress markers, not proof of physical activity. Strict mode resets challenge run progress after missed days but never deletes completed workout history or previously earned badges.

## v1.3 — Custom Quest challenge rules

The 67-Day Adventure now has four selectable rule sets: Explorer, Momentum, Iron Quest, and **Custom Quest**. Open **My Progress**, scroll to **The 67-Day Adventure**, and select **Custom Quest** to configure:

- **Missed-day consequence:** no deduction (record a detour), deduct 1–7 challenge days, or reset the current 67-day run.
- **Weekly grace allowance:** 0–6 excused missed days per seven-day challenge block (counted from the adventure start date).
- **Scheduled rest days:** select days of the week that will not incur missed-day penalties; completed workouts on those days still count.
- **Minimum movement target:** any completed workout, or 3, 5, 9, 12, 15, 20 or 30 total minutes per day. Multiple completed sessions on the same day may combine to qualify.

A challenge day counts only after its movement threshold is met. The current calendar day is not penalized until it ends. Changing challenge rules recalculates current adventure progress retroactively from the start date. Finished workout records and permanent earned badge IDs remain saved. A completed 67-day run remains completed. Challenge settings and earned badges are included in exported/imported backups.

This is an optional personal challenge, not a medical or mandatory fitness standard. Rest days and gradual progression are encouraged. The rules rely on the browser's local calendar and user-controlled records, so this is not tamper-resistant proof of exercise.

**GitHub update from v1.2:** replace `index.html` only. The existing `assets/` folder and other files can remain as they are. The README update is optional.

## v1.4 — Always-visible workout cues

The countdown timer and three primary movement cues now appear side by side in a compact layout on phones, tablets and desktops, including Focus Mode. The gentler option is shown with the instructions. Detailed cues remain available in an expandable section. Coach portraits remain decorative and are not represented as exercise-form demonstrations. Existing progress and challenge rules are unchanged.


## v1.5 — Guided movement demos

This release adds an in-app animated coach demo area to the workout screen. The current movement now shows a dedicated animated demonstration panel with playback controls, a slower-speed option, and a replay voice cue button. The system supports:

- the full 9-move morning flow
- the six warm-up / stretch movements
- beginner strength variations for push-up, squat, core, pulling, and glute practice

The demo panel stays inside the workout screen and is designed to remain readable beside the timer and live cues on smaller screens. The selected strength variation changes the demo that is shown. Existing progress, achievements, challenge rules, and assets are preserved.
