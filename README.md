<div align="center">

```
██████╗ ███████╗██╗   ██╗███████╗████████╗ █████╗ ██████╗ ████████╗
██╔══██╗██╔════╝██║   ██║██╔════╝╚══██╔══╝██╔══██╗██╔══██╗╚══██╔══╝
██║  ██║█████╗  ██║   ██║███████╗   ██║   ███████║██████╔╝   ██║
██║  ██║██╔══╝  ╚██╗ ██╔╝╚════██║   ██║   ██╔══██║██╔══██╗   ██║
██████╔╝███████╗ ╚████╔╝ ███████║   ██║   ██║  ██║██║  ██║   ██║
╚═════╝ ╚══════╝  ╚═══╝  ╚══════╝   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝   ╚═╝
```

# DevStart Learning Platform

**A full-featured, single-file web app for learning CLI, Git & HTML — built for the GoMyCode bootcamp.**

[![Made by Edwin](https://img.shields.io/badge/made%20by-Edwin%20Nyandika-39ff6a?style=flat-square&labelColor=0a0e0a)](https://github.com/edwinnyandika)
[![GoMyCode](https://img.shields.io/badge/GoMyCode-Bootcamp-ffc542?style=flat-square&labelColor=0a0e0a)](https://gomycode.com)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-zero-39ff6a?style=flat-square&labelColor=0a0e0a)](./index.html)
[![Single File](https://img.shields.io/badge/app-single%20file-4dc9ff?style=flat-square&labelColor=0a0e0a)](./index.html)
[![License: MIT](https://img.shields.io/badge/license-MIT-bd93f9?style=flat-square&labelColor=0a0e0a)](./LICENSE)

</div>

---

## What is DevStart?

DevStart is an interactive learning platform built as a **single HTML file** with zero dependencies. Originally a CLI assignment for the GoMyCode bootcamp, it grew into a full 8-page learning tool covering the three pillars of every developer's foundation: **Command Line**, **Git**, and **HTML**.

Everything runs in the browser — no servers, no build tools, no npm install. Just open `index.html`.

---

## Live Features

### 8 Pages, One File

| Page | What you get |
|------|-------------|
| **CLI Tasks** | 9 documented filesystem tasks (mkdir, touch, rm, mv, cp, echo, cat, cd, ls) with a live interactive terminal simulator |
| **Git Commands** | 15+ commands across 5 categories, full workflow walkthrough, and a live Git simulator |
| **HTML Guide** | Tag anatomy, semantic HTML glossary, common tags table, and full boilerplate |
| **Code Editor** | Live HTML/CSS/JS editor with real-time preview, 7 starter snippets, and VS Code shortcuts |
| **Quiz** | 20 questions (CLI + Git + HTML) with sound feedback, keyboard shortcuts, progress dots, and confetti |
| **Flashcards** | 40+ cards with 3D flip animation, mastery tracking, category filters, and .txt download |
| **Lexicon** | 15 curated terms with plain-English + technical definitions, coded examples, SVG visuals, and live Dictionary API search |
| **Code Game** | 3 game modes — Code Fill-In (drag & drop), Visual Decode, and Bug Hunt — with scoring and high scores |

---

## The Code Game

Three distinct game modes to build muscle memory for code:

**🧩 Code Fill-In** — Drag code pieces into blank spots in real snippets. HTML tags, Git flags, CSS properties, JS syntax. 8 levels, timed.

**🎨 Visual Decode** — Read colour-highlighted code and identify what each coloured part is — tag, attribute, value, selector, flag. 8 levels.

**🐛 Bug Hunt** — A code block has exactly one bug (typo, missing punctuation, wrong keyword). Click the broken line before the timer runs out. 8 levels.

All modes feature live score tracking, a countdown timer with urgency animation, streak bonuses, sound feedback, and confetti for high scores.

---

## The Lexicon

Every term ships with **two definitions**:
- **Plain English** — what it means in plain language, no jargon
- **Technical Depth** — the precise developer definition

Plus live syntax-highlighted code examples and SVG visuals (DOM tree, flexbox diagram, git branch graph, tag anatomy, and more).

The search bar is powered by the **Free Dictionary API** (`api.dictionaryapi.dev`) — search any English or programming word and get live results if it's not in the curated list.

---

## Tech Stack

```
index.html          ← the entire application
│
├── HTML            semantic structure, 8 page sections
├── CSS             CSS custom properties, grid, flexbox, animations
│   ├── JetBrains Mono (monospace) via Google Fonts
│   └── Syne (display) via Google Fonts
└── JavaScript      vanilla ES6+
    ├── CLI simulator (virtual filesystem in memory)
    ├── Git simulator (branch/commit state machine)
    ├── Live code editor (srcdoc iframe)
    ├── Quiz engine (20 questions, Web Audio API beeps)
    ├── Flashcard engine (flip animation, mastery set)
    ├── Lexicon renderer (accordion, SVG visuals)
    ├── Dictionary API client (fetch, error handling)
    ├── Game engine (3 modes, drag & drop, timer)
    └── Confetti (Canvas API particle system)
```

**External resources used:**
- [Google Fonts](https://fonts.google.com) — JetBrains Mono + Syne
- [Free Dictionary API](https://dictionaryapi.dev) — open source, no key needed

---

## Getting Started

**Option 1 — Just open it:**
```bash
git clone https://github.com/edwinnyandika/gomycode-cli-assignment.git
cd gomycode-cli-assignment
open index.html     # macOS
start index.html    # Windows
xdg-open index.html # Linux
```

**Option 2 — Live Server (recommended for development):**
```bash
# If you have VS Code + Live Server extension:
# Right-click index.html → "Open with Live Server"

# Or with Python:
python3 -m http.server 3000
# Visit http://localhost:3000
```

**Option 3 — Deploy to GitHub Pages:**
```bash
# In your repo settings → Pages → Deploy from branch → main → / (root)
# Your app will be live at:
# https://edwinnyandika.github.io/gomycode-cli-assignment/
```

---

## Assignment Context

This project was built as part of the **GoMyCode Full-Stack Bootcamp** — specifically the CLI & Git fundamentals checkpoint. The original assignment required:

- Documenting 9 CLI filesystem operations using Git Bash (Windows) and Termux (Android)
- Practising `mkdir`, `touch`, `rm`, `mv`, `cp`, `echo`, `cat`, `cd`, `ls`, `pwd`
- Initialising a Git repository and committing the documented work
- Pushing to GitHub

The project was then expanded into a complete learning platform with interactive tools, games, and reference materials — all while remaining a single deployable file.

---

## CLI Tasks Documented

| # | Command | Action |
|---|---------|--------|
| 1 | `mkdir devstart` | Create a new directory |
| 2 | `touch index.html` | Create a new empty file |
| 3 | `rm old-file.txt` | Delete a file |
| 4 | `mv file.txt newname.txt` | Rename / move a file |
| 5 | `cp source.txt backup.txt` | Copy a file |
| 6 | `echo "Hello World"` | Print text to terminal |
| 7 | `cat index.html` | Read file contents |
| 8 | `cd projects/web` | Navigate directories |
| 9 | `ls -la` | List directory contents |

All tasks were tested on **Git Bash (Windows)** and **Termux (Android)**.

---

## Git Workflow Used

```bash
# Initialise
git init
git remote add origin https://github.com/edwinnyandika/gomycode-cli-assignment.git

# First commit
git add .
git commit -m "feat: initial CLI assignment"
git push -u origin main

# Feature branch workflow
git checkout -b feature/interactive-quiz
# ... work ...
git add .
git commit -m "feat: add 20-question quiz with sound feedback"
git push origin feature/interactive-quiz
git checkout main
git merge feature/interactive-quiz
```

---

## File Structure

```
gomycode-cli-assignment/
│
├── index.html          ← entire application (HTML + CSS + JS)
├── README.md           ← this file
└── LICENSE             ← MIT
```

The entire platform — 8 pages, 40+ flashcards, 20 quiz questions, 24 game challenges, a dictionary API, confetti, sound, a live code editor, and two terminal simulators — lives in a single 230KB HTML file.

---

## Quiz & Game Stats

| Feature | Count |
|---------|-------|
| Quiz questions | 20 (7 CLI, 7 Git, 6 HTML) |
| Flashcards | 40+ (14 CLI, 14 Git, 12 HTML) |
| Lexicon terms (curated) | 15 |
| Fill-In game levels | 8 |
| Visual Decode levels | 8 |
| Bug Hunt levels | 8 |
| Starter code snippets | 7 |
| CLI simulator commands | 10+ |
| Git simulator commands | 8+ |

---

## Keyboard Shortcuts

**Quiz:**
- `1` `2` `3` `4` — select answer option
- `Enter` — advance to next question

**Code Editor:**
- `Ctrl+S` / `Cmd+S` — run code
- `Tab` in textarea — insert 2 spaces

---

## Colour Scheme

The platform uses a dark terminal aesthetic inspired by classic dev environments:

```css
--bg:          #080c08   /* deep black-green background */
--green:       #39ff6a   /* neon green — primary accent */
--amber:       #ffc542   /* warm amber — warnings, attributes */
--blue:        #4dc9ff   /* bright blue — tags, info */
--purple:      #bd93f9   /* soft purple — selectors, JS */
--red:         #ff5555   /* red — errors, wrong answers */
```

Fonts: **JetBrains Mono** for all code, **Syne** for headings and UI.

---

## Contributing

This is a personal bootcamp project, but contributions, suggestions and bug reports are welcome.

```bash
# Fork the repo, then:
git clone https://github.com/YOUR_USERNAME/gomycode-cli-assignment.git
cd gomycode-cli-assignment

# Create a branch
git checkout -b fix/your-fix-name

# Make changes to index.html
# Test by opening in browser

git add .
git commit -m "fix: describe what you changed"
git push origin fix/your-fix-name
# Open a pull request on GitHub
```

---

## Acknowledgements

- **GoMyCode** — for the bootcamp curriculum and this assignment
- **JetBrains** — for the beautiful monospace font
- **Free Dictionary API** — for the open-source dictionary endpoint
- The wider open-source community for inspiration

---

<div align="center">

Built with `>_` and ❤️ by **Edwin Nyandika**
<br>
GoMyCode Bootcamp · 2024–2025

```
> git push origin main
Enumerating objects: 3, done.
Writing objects: 100%
To github.com/edwinnyandika/gomycode-cli-assignment.git
   ✓ main → main
```

</div>
