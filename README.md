# Lethal Company — 3D Interactive Live Wallpaper for Mac

A single-file, offline 3D live wallpaper inspired by Lethal Company.

![style](https://img.shields.io/badge/style-terminal%20%2F%20foggy%20moon-orange) ![platform](https://img.shields.io/badge/platform-macOS-lightgrey) ![dependencies](https://img.shields.io/badge/dependencies-none-green)

## What it does

- 3D terrain grid rushing under you on a foggy moon
- A giant moon and the Company facility silhouette with a blinking beacon
- Floating wireframe **scrap cubes** — completely static by default, they only spin/shift when you move the mouse and settle still when you stop
- Drifting spores/dust, scanlines, terminal HUD, and a live clock
- Top of the screen fades to pure black so the Mac notch blends in

## Interactive

- **Move mouse** — camera/parallax follows, scrap cubes spin with your movement
- **Click** — scanner ping (green rings) and the scrap counter goes up

## Use it as a live wallpaper (Mac)

1. Install **Plash** from the Mac App Store (free).
2. Download / clone this repo and keep `index.html` somewhere permanent (e.g. Documents).
3. Open Plash (menu bar icon) → **Add Website → File…** → pick `index.html`.

> Note: Plash in wallpaper mode may not receive mouse clicks on some macOS versions — the scene still auto-animates. To play with the interactive version, open `index.html` fullscreen in your browser.

## Static / no setup

Just open `index.html` in any browser — no build step, no dependencies, works offline.

## Files

- `index.html` — everything (scene, HUD, interaction) in one file
