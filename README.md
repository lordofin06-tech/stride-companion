# Stride Companion

Stride Companion is a mobile-first walking companion for Android browsers. It requests browser motion permission, listens to the `devicemotion` stream, estimates step-like movement locally, and keeps daily progress and recent walks in local browser storage.

## GitHub Pages

The latest static build is published from `main` with the project-site base path. Open the live site at:

https://lordofin06-tech.github.io/stride-companion/

Motion sensor access requires a secure context (HTTPS) and a browser/device that exposes motion events. On Android Chrome, open the site on the phone, tap **Enable motion access**, and move the phone once to confirm the signal. If motion access is unavailable, the app provides manual walk logging.

## Development

The Replit app source lives under `artifacts/stride-companion`. The published bundle is in the root `index.html` and `assets/` directory for GitHub Pages. The app uses no backend for sensor counting; steps and walk history stay on the device.
