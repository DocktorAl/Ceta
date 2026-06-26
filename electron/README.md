# CETA Diagram Editor — Desktop App

A desktop wrapper for the CETA Mermaid & SVG live diagram editor, built with Electron.

The app is fully self-contained — the Mermaid library is bundled inside `index.html` so it works with no internet connection.

## Requirements

- [Node.js](https://nodejs.org/) (v18 or later)
- npm (included with Node.js)

## Run locally

```bash
cd electron
npm install
npm start
```

## Build an installer

```bash
npm run build-win      # Windows — NSIS installer (.exe)
npm run build-mac      # macOS   — Disk image (.dmg)
npm run build-linux    # Linux   — AppImage (.AppImage)
```

Output is written to `electron/dist/`.

See [INSTALL.md](INSTALL.md) for end-user installation instructions.
