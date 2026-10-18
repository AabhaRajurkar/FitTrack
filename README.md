# FitTrack — Fitness & Wellness

A responsive fitness dashboard inspired by the FitTrack Figma UI/UX concept.

## Features
- Welcome, login demo, onboarding, dashboard, workout library/details, workout timer, progress, profile, and settings.
- Forest-green/lime design tokens, responsive styles, and mobile navigation.
- Working workout filters, saved-workout toggles, onboarding preferences, rest timer, and dark-mode toggle.
- Vite build and GitHub Actions deployment to GitHub Pages.

## Run locally
Requires Node.js 20+.

```bash
npm install
npm run dev
```

Build locally with `npm run build`.

## GitHub Pages
The included workflow builds the static site and deploys it automatically whenever code is pushed to `main`.

1. Open **Settings → Pages**.
2. Set the source to **GitHub Actions**.
3. Open **Actions** and check the `Deploy FitTrack to GitHub Pages` run.
4. Once the run succeeds, visit https://AabhaRajurkar.github.io/FitTrack/.

The Vite configuration uses a relative asset base so the site works from the repository path.

## Demo limitations
This is a front-end demo. Sign-in, saved account data, privacy, and support actions are placeholders; there is no backend or authentication provider. Charts and user activity use sample data. Exercise imagery loads from Unsplash.
