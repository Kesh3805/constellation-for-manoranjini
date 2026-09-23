# A small universe

A short, procedurally generated night sky — about two minutes long — made as a personal gift.
It is a single self-contained `index.html`: HTML, CSS, vanilla JavaScript and WebGL2/GLSL.
No libraries, fonts, images, audio or network requests; everything you see is generated on the GPU.

## Run locally

Any static file server works:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000/>. (Opening the file directly also works in most browsers.)

## Deploy

Pushing to `main` runs `.github/workflows/deploy-pages.yml`, which uploads the repository root
as a GitHub Pages artifact and deploys it. Pages must be set to **Source: GitHub Actions**
(Settings → Pages), which the initial setup already did.

Live: <https://kesh3805.github.io/constellation-for-manoranjini/>

## Browser requirements

A browser with WebGL2: current Safari on iPhone/iPad (iOS 15+), Chrome on Android, and desktop
Chrome, Edge, Firefox or Safari. Without WebGL2 a short message is shown instead.
Quality adapts automatically on slower devices. There is no sound.

## The ending

Watch until the very end and let it rest for a moment.
Some things in the sky respond to a gentle touch — the last one most of all.
Keyboard: <kbd>Enter</kbd> or <kbd>Space</kbd> does the same. After it fades to black,
a tap anywhere plays it again.
