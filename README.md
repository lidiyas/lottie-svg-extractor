# Lottie SVG Extractor

A lightweight HTML tool to **preview a Lottie animation from JSON** and **export any exact frame as a clean SVG** — all locally.

## Why
Previewing Lotties is easy. Extracting **one precise frame** as a reusable SVG (for UI specs, docs, or static assets) is where most workflows break. This tool closes that gap with zero friction: **copy/paste JSON → preview → export frame**.

## Features
- Paste Lottie JSON and preview instantly (no uploads)
- Playback controls: **play/pause, reverse, loop, autoplay**
- Export **any frame** as a **clean `.svg`**
- Works locally in the browser (ideal for messy icon libraries + quick demos)

## Getting Started
### Option A — Run locally
1. Clone or download this repo
2. Open `index.html` in your browser

### Option B — GitHub Pages
If this repo is hosted with GitHub Pages, just open the published URL.

## How to Use
1. Copy a Lottie JSON payload
2. Paste it into the input area
3. Click **Load/Preview**
4. Use controls to play, pause, reverse, loop, or autoplay
5. Choose a **frame number**
6. Click **Export SVG** to download the frame as `.svg`

## Export Notes
- “Frame” refers to the Lottie timeline frame index.
- The exported SVG is intended for **static usage** (UI assets, documentation, specs).
- Output quality depends on the original Lottie content (e.g., raster layers may not convert into pure vectors).

## Privacy & Security
- Runs locally in your browser.
- Your Lottie JSON is **not uploaded** anywhere by this tool.

## Tech
- Pure HTML/CSS/JS (no build step required)
- Lottie rendering via the standard web player (implementation may vary per repo setup)

## Limitations
- Some complex Lottie features may not export perfectly to SVG (e.g., certain effects, masks, embedded images).
- Large animations may impact performance depending on device/browser.

## Contributing
PRs and issues are welcome:
- Bug reports (include a minimal JSON sample if possible)
- Edge cases for SVG export
- UX improvements (frame scrubbing, better error handling, etc.)

## License
MIT License
