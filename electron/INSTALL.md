# Installation

## Option A — Run directly in a browser (no installation)

Open `mermaid.offline.html` (one level up from this folder) in any modern browser. No installation required, works offline.

## Option B — Run as a desktop app (Electron)

### Prerequisites

Install [Node.js](https://nodejs.org/) (v18 or later) — npm is included.

### Steps

```bash
cd electron
npm install
npm start
```

This opens the editor in its own window without browser chrome.

## Option C — Build a standalone installer

Run the appropriate build command from inside the `electron/` directory:

| Platform | Command | Output |
|----------|---------|--------|
| Windows | `npm run build-win` | `dist/CETA Diagram Editor Setup.exe` |
| macOS | `npm run build-mac` | `dist/CETA Diagram Editor.dmg` |
| Linux | `npm run build-linux` | `dist/CETA Diagram Editor.AppImage` |

Distribute the output file to end users — they do not need Node.js installed to run it.
