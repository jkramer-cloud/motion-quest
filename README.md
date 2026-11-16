# Motion Quest — first working prototype

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
- Large color-changing timer; pause, restart, skip, and end controls; optional short transitions, chimes, and browser voice announcements.
- Basic workout history, week graph, 14-day calendar, streak, optional energy rating, backup/import, and self-reported weekly report.
- Responsive layout and reduced-motion control.

## Important visual fidelity note

The finished character art is used for **actual cards and coach screens**, not placeholder emoji. However, character portraits currently have an **idle float only** and are **not exercise-form demonstrations**. The next major art milestone should be pose-accurate, movement-specific animations for each of the nine morning-flow activities and for bodyweight modifications. Do not represent idle animations as exercise instruction. The original video is linked from the app so users can check the creator's demonstration.

## Health and privacy

Movement suggestions are generic, low-pressure and include alternatives. This is not medical guidance. No birth date or weight is requested; local records don't sync across browsers/devices. Exports contain activity data chosen by the user. No student names or identifiers are required.

## Files

- `index.html` — entire standalone web app.
- `assets/*.webp` — six real game-style coach illustrations.
- `docs/design-system.md` — cast, brand, screen map, and release scope.

