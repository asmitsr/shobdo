# Shobdo — Accessible Reading for Everyone

Paste any Bangla or English text, hear it read aloud with word-by-word highlighting, and adjust the text to your eyes.

Built for the **Ctrl+V Hackathon** (Devpost) — theme: *making access easier*.

## Who it helps

- **Low-vision users** — large text, high-contrast themes (including yellow-on-black).
- **Dyslexic readers** — adjustable letter and line spacing.
- **Elderly users** — one-tap read-aloud, big controls, no clutter.
- **Bangla speakers** — reads aloud in Bangla (bn-BD) as well as English (en-US).

## Features

- **Read Aloud** — browser Web Speech API, Bangla + English voices, Play / Pause / Stop, speed 0.5×–2×.
- **Word highlighting** — the word being spoken lights up as it is read (with a timer fallback for browsers that don't fire word-boundary events).
- **Reading controls** — three font sizes, Light / Dark / High-Contrast themes, dyslexia-friendly letter and line spacing.
- **Accessible by design** — semantic HTML, ARIA labels, `aria-pressed` / `aria-live` status, skip link, visible focus styles, fully keyboard navigable, mobile-friendly.
- **Private** — all processing stays on the device. No server, no API key, no data leaves the browser.

## Run it

Open `index.html` in any modern browser, or visit the live site. No build step, no install.

## Tech

Single self-contained `index.html` — HTML, CSS, JavaScript, Web Speech API. No dependencies.
