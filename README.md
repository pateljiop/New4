# NEW4® — Interactive Worlds

A responsive concept hub for 20 experimental web experiences, with a dedicated real-time Three.js cyber-mascot scene.

## Run locally
Open `index.html` in a modern browser. Open `cyber-mascot.html` for the dedicated 3D experience. No build step is required, but the Three.js page needs internet access to load its ES modules from jsDelivr and a browser with WebGL support.

## What's included
- 20 concept cards with category filters and interactive preview prototypes.
- Dedicated `cyber-mascot.html` page using Three.js, OrbitControls, procedural panda geometry, headphone details, realtime lights, a holographic halo, floating data chips, and an interactive scene.
- Drag-to-orbit and scroll-to-zoom camera controls; reset camera, pause/resume mascot idle animation, hide/show floor grid, click mascot to trigger a response, wave button, and cyan / after-hours vibe switch.
- Responsive desktop/mobile layout, keyboard-friendly controls, and reduced-motion-aware CSS.
- Local terminal demo: `/help`, `/about`, `/skills`, `/worlds`, `/random`, `/wave`, `/clear`.

## Scope and limitations
The panda is procedurally assembled from Three.js geometry; it is not a scanned or externally authored GLB character. This is a first dedicated 3D experience, not a claim that all 20 concepts are production-complete. The remaining concepts still need their own dedicated pages and proper implementations. Demo commands are local and no external AI service, backend, multiplayer, audio engine, video processor, or AR device integration is connected. Validate third-party CDN availability and browser WebGL support before deployment.

## Deploy
This is a static site. It can be deployed with GitHub Pages or another static hosting provider from the repository root. The 3D experience loads Three.js as browser ES modules from jsDelivr, so deployment visitors need access to that CDN.
