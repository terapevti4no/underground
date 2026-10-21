# Underground

A self-paced 5–4–3–2–1 sensory grounding practice. React, TypeScript, Vite and the shared `@terapevti4no/ui` library.

Published at https://terapevti4no.github.io/underground/.

## Development

Run `npm ci` and `npm run dev`, then open http://127.0.0.1:4180/. Build with `npm run build -- --base=/underground/`.

Five steps: see five things, feel four physical sensations, hear three sounds, notice two smells and one taste. Marks are reversible. A next arrow appears when all marks are filled; Skip and Finish are always available. Enter marks the next item and advances a completed step; Escape returns to the start. No timers or text entry. Theme and language are stored in `underground:v1`; practice progress stays in memory and resets on reload.

The shared UI package is installed from versioned GitHub Releases. `npm run ui:update -- --latest` installs a new release. GitHub Actions checks for new versions on a schedule, builds verified updates, commits dependency changes and deploys through Pages. `UI_AUTO_UPDATE=false` disables scheduled checks.

Reference for the step order: https://www.nhsinform.scot/healthy-living/mental-wellbeing/breathing-and-relaxation-exercises/grounding-exercises/
