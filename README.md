# Plant Website

A simple, responsive static website showcasing plants and their care information. This repository contains the front-end assets (HTML, CSS, JS) and a Tailwind-based build setup.

## Features
- Responsive layout and styles (Tailwind CSS)
- Static HTML content with a small JS enhancement (`main.js`)
- Source CSS (`input.css`) compiled to `output.css` using Tailwind
- Images and assets included in the `assets/` and `Images/` folders

## Tech
- HTML, CSS, JavaScript
- Tailwind CSS (devDependency, used to compile `input.css` → `output.css`)

## Quick start

Prerequisites: Node.js and npm (or npx).

1. Install dependencies (if you have a package manager):

```powershell
npm install
```

2. During development run Tailwind in watch mode to rebuild `output.css` when `input.css` changes:

```powershell
npm run watch
```

3. Open `index.html` in your browser (or use a local static server) to view the site.

Notes:
- The `watch` script in `package.json` runs: `tailwindcss -i ./input.css -o ./output.css --watch`.
- If you prefer a single build without watch, run the equivalent Tailwind CLI command without `--watch`.

```markdown
# 🌿 IndorePlants — Plant Website

A small, responsive static site showcasing plants — built with HTML, Tailwind CSS and a tiny bit of JS.

## ✨ Highlights
- Responsive layout (Tailwind CSS)
- Minimal JS for UI touches (`main.js`)
- Images & assets included

## 🚀 Quick start
Prereqs: Node.js + npm

1. Install dependencies:

```powershell
npm install
```

2. (Dev) Rebuild CSS on change:

```powershell
npm run watch
```

3. Open `index.html` in your browser or serve the folder with any static server.

## 📁 Project (short)
- `index.html` — entry page
- `input.css` → `output.css` — Tailwind source & generated CSS
- `main.js` — site JS
- `assets/`, `Images/` — images and static assets

## 🔗 Live demo
[Visit the demo](https://indoreplant.vercel.app)

---






