# Motion Quest — v2.0 Quest Crew Practice, Audio & Mobile

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

The finished character art is used for **actual cards and coach screens**, not placeholder emoji. The app uses 9 illustrated movement loops for Ollie and 6 illustrated mobility loops for Pogo. Bramble has a polished illustrated wall-push-up loop. Other strength variations currently use stylized movement sketches plus variation-specific form instructions. They should not be mistaken for full production-quality character animations or individualized exercise instruction. The original video remains linked from the app so users can compare the source routine when helpful.

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


## v1.7 — Polished illustrated motion, phase one

- Three movement-specific, frame-by-frame illustrated Ollie sequences: breathing/reach, arm waves, and wide-stance ballet squats. These new assets are stored under `assets/demos/` and must be uploaded with the revised `index.html`.
- Coach-specific SVG guide designs for Ollie, Pogo, Bramble, Zip, Draco, and Lumi, replacing the identical rabbit head used for every coach in the prior build.
- Improved mobile demonstration sizing, a visible coach portrait, and working separate pause and slower-speed controls for the new illustrated frame sequences.
- A corrected app initialization order: challenge presets now initialize before the app state is created. This fixes a potential startup failure present in v1.5.
- `Replay cues` now announces the actual technique cues (when the browser's speech system is available), not just the exercise name.
- Existing workout history, 162 achievements, the 67-day challenge, strength levels, and settings remain saved in the same browser storage.

**Important:** This is not the final illustrated animation set. Only the three named motions have full-color frame assets; other movement examples still use simplified coach-specific vector sketches. They are visual reminders, not anatomically certified form instruction. Complete, polished form-accurate animation assets for all nine flow movements, stretches, and strength variations remain a production goal. Do not represent these simplified sketches as professional form demonstrations.

**Updating an existing repository:** Upload the revised `index.html` and the **new `assets/demos/` folder**. Keep the existing `assets/*.webp` character portraits. Updating `README.md` is optional. For a new repository, upload the entire complete package.


## v1.9 — Bramble’s Strength School and Pogo’s Stretching

This release preserves the previous full app, including Ollie's 9-movement flow, its achievements, timers, voice controls, challenge rules, and local data format.

**New:** Six full-color illustrated Pogo loops are included for the stretch routine and the warm-up in Start My Morning: breathing & reaching, shoulder rolls, neck turns, arm circles, hip shifts, and gentle steps.

**New:** Bramble's Strength School gives a different technical guide for every one of the 23 selectable entries across five exercise families: 5 push-up options, 4 squat options, 5 core options, 5 pulling choices (including skip), and 4 glute/balance options.

- Open Workouts and select each exercise's level; click **Preview form** for a no-timer practice screen.
- Every variation includes its own setup, movement, breathing, common mistakes, easier option, and equipment guidance.
- The same variation-specific cues appear beside the active workout timer, and switching variations changes the guidance.
- The beginner wall push-up has its own illustrated frame-by-frame Bramble loop (6 frames). Other strength variations still use labeled stylized sketches and written guidance; do **not** treat these as finished photographic or pose-verified character demonstrations.
- A compact pinned movement clock appears on mobile workout screens, keeping the countdown and current move visible while scrolling.
- Art assets and records remain browser-local. No additional hosting or service dependencies are required.

### Update your existing GitHub repository

If you have v1.7 already, use the v1.9 Update Only ZIP: replace `index.html`, add the new `assets/demos/pogo-*` folders, and add `assets/demos/bramble-wall`. `README.md` is recommended but optional. Keep all existing `assets/demos/ollie-*` and `assets/*.webp` unchanged. The full ZIP includes everything and can replace the repository contents instead. **Do not upload the ZIP itself**; extract and preserve the folder structure. No additional `docs` folder changes are necessary for this incremental update.

### Visual-quality limitations

Animated illustrations are instructional approximations and have not been validated by a qualified exercise professional. The Bramble image generation successfully produced the complete wall push-up loop, but production-quality illustrated loops for the other 21 non-skip strength choices still require individual artwork and review. The app distinguishes these from illustrated loops rather than pretending they are complete.


## v2.0 — Zip, Lumi, Draco / Audio and Mobile update

- A new **Practice with the Quest Crew** panel in Workouts offers full no-timer practice screens and movement selection for Zip, Lumi, and Draco, with illustrations where available, form cues, gentler versions, and saved strength variations.
- Zip’s Quick Boost now has independent anime-style illustrated loops for marching and low-impact hops. His arm waves and wide-stance squat still use coach-specific animated sketches with their original form cues.
- Lumi’s four Recovery & Calm exercises now include coach-specific spoken/written recovery guidance and gentle adjustments. The illustrated character portrait remains in the app; detailed, exercise-specific full-color frame sequences for Lumi are still an artwork task.
- Draco’s Challenge Quest now provides exercise-by-exercise coaching for all eight steps and respects the user’s chosen strength variation. His challenge movements use the existing form sketches unless another illustrated coach demonstration is available; do not interpret them as new fully animated dragon sprites.
- Audio mixer: gentle/arcade/soft/silent chimes, adjustable sound volume, exercise name vs. short vs. full form announcements, three-second sound toggle, in-workout Mute, and preview. Voice choices depend on browser/device.
- Mobile: more compact illustration/timer/instruction layout, enlarged touch targets, preserved sticky countdown, in-demo remaining-time readout, improved phone landscape layout, optional supported screen-awake setting (HTTPS and device permitting), Focus Mode, and reduced-motion behavior.
- Full GitHub upload and a smaller update-only package are included. No account is needed and the storage key is unchanged.

**What remains:** full-color, exercise-specific illustrated animations for Lumi, Draco and the remaining Zip exercises, plus most of Bramble’s non-wall-push-up strength variations. Animations are creative teaching aids and have not had professional technique review.


## v2.1 — The Adventure Begins

The v2.1 update expands the existing workout-focused prototype with tangible game rewards:

- Permanent lifetime XP: all completed daily and weekly quest bonuses are recalculated from **all saved session dates**, so the lifetime total no longer drops at midnight.
- Six illustrated, selectable training worlds (Sunrise Meadow, Bamboo Sanctuary, Crystal Caverns, Cloudpeak Terrace, Dragon Summit, Moonlit Garden) unlocking at fixed lifetime XP thresholds. The selected world appears behind your workout demonstration and as an illustrated location banner.
- Every Quest Crew coach gains independent training XP and coach levels for workouts associated with their specialty (regardless of which favorite coach is displayed).
- 12 milestone treasure chests. Each chest can be claimed **once**, awarding collectible Starlight; Starlight is a keepsake score, not purchasable or spendable currency.
- Collectible illustrated medal styling for the achievement gallery, plus four permanent 67-day victory relics for Explorer, Momentum, Iron Quest and Custom Quest.
- Reward animations for new badges, level-ups, chest claims and day 67. The full illustrated Quest Crew celebrates a completed 67-day challenge.
- Weekly quests and improved XP breakdown. Reward triggers come from completed, locally stored workout records. No account, connection, leaderboard, or money involved.

The adventure's missed-day rules remain unchanged. For safety, reward credits never depend on weight or unusually intense exercise. Prior v2.0 local progress stays compatible because the same storage key and data fields are retained; exports/imports include the added world, chest, and relic fields. Previously earned achievement IDs are preserved.

**Important testing note:** automatic reward calculations can be triggered from self-reported/local browser records. This is not a tamper-resistant verification of physical exercise. Browser-only data is not shared or synced between devices. New background artwork is original and bundled under `assets/worlds/`.
