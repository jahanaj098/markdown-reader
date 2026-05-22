# Markpad — Markdown Editor

A fast, dark-themed Markdown editor that runs entirely in the browser. No backend, no login, no tracking.

## Features

- **Open** any `.md`, `.markdown`, or `.txt` file — click or drag & drop
- **Live preview** with syntax-highlighted code blocks
- **Split / Edit / Preview** modes
- **Save / Download** your file back to disk (`Ctrl+S`)
- **Word, character & line** count in real time
- **Tab** support inside the editor (2-space indent)
- Works 100% offline after the first load

## Deploy to Vercel (one-click)

1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → **New Project** → Import the repo
3. Leave all defaults → **Deploy**

That's it. Vercel auto-detects it as a static site.

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Ctrl / Cmd + S` | Save / download file |
| `Ctrl / Cmd + O` | Open file picker |
| `Tab` | Insert 2-space indent |

## Local dev

Just open `index.html` in any browser — no build step needed.

## Tech

- [marked.js](https://marked.js.org/) — Markdown parsing
- [highlight.js](https://highlightjs.org/) — Code block syntax highlighting
- [Syne](https://fonts.google.com/specimen/Syne) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) + [Lora](https://fonts.google.com/specimen/Lora) — fonts
