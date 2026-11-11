<p align="center">
  <a href="https://YOUR-USERNAME.github.io/YOUR-REPO/">
    <img src="assets/intro.svg" alt="ANONYMOUS // Cyber Security Club — OSINT" width="100%">
  </a>
</p>

<p align="center">
  <a href="https://YOUR-USERNAME.github.io/YOUR-REPO/"><b>[ ENTER THE PORTAL ]</b></a>
</p>

## ANONYMOUS // Cyber Security Club

Registration portal for our **OSINT (Open Source Intelligence)** event.

- Single-file site: `index.html` (Three.js 3D background, cinematic intro, registration terminal)
- Repo banner animation: `assets/intro.svg`

## Run locally

Open `index.html` in a browser. No build step is needed.

## Deploy on GitHub Pages

1. Push `index.html`, `README.md` and the `assets/` folder to the repo root.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
4. After about a minute the site is live at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.
5. Replace both `YOUR-USERNAME.github.io/YOUR-REPO` links at the top of this README with that URL.

## Connect the registration form

In `index.html`, find the `CONFIG` block and fill in `formAction`, `formLink` and the `entries` IDs from your Google Form. Until then the form runs in demo mode.
