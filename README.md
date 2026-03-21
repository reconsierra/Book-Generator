# 📚 Book Idea Generator

A browser-based creative writing tool for generating book premises, back-cover blurbs, and full series briefs. Built as a single HTML file — no installation, no server, no build step required.

**[Live Demo →](https://YOUR-USERNAME.github.io/book-idea-generator)**

---

## What It Does

Configure a wide range of story variables and generate a fully written book pitch, either as a structured template or powered by Claude AI (Anthropic). Works for single books or multi-book series with recurring characters.

---

## Features

- **12 Genres** — Thriller, Romance, Rom-Com, Fantasy, Sci-Fi, Horror, Mystery, Historical Fiction, Literary Fiction, Crime, Western, Children's
- **Genre-specific dropdowns** that change based on the selected genre
- **AI pitch generation** — connects to the Anthropic API to write a real back-cover blurb and title suggestion
- **Author Settings** — set your pen name, publisher, writing style, and comparable titles; these appear on every generated brief and are included in the AI prompt
- **Series Manager** — generate briefs for 2–12 books in sequence, with recurring characters, series arcs, and previous-book context fed to the AI
- **Taboo / Dark Elements** — toggle content warnings individually, save your preferred defaults
- **Word Count selector** — Short Story, Novella, Full Novel, or Epic
- **Randomise All** — auto-select every field randomly for unexpected prompts
- **Save / Load Presets** — bookmark your favourite configurations by name
- **Export / Import JSON** — back up and share your full configuration
- **Export PDF** — generates a print-ready story bible from your output

---

## Getting Started

No installation needed. Just open `index.html` in any modern browser, or visit the GitHub Pages URL above.

### Using AI Pitch Generation

1. Get a free API key at [console.anthropic.com](https://console.anthropic.com)
2. Click **Set API Key** in the toolbar
3. Paste your key — it is stored only in your browser's localStorage and never sent anywhere except Anthropic's API
4. Click **Generate with AI** — Claude will write a full back-cover blurb and title

Without an API key the tool still works and generates a structured template pitch instead.

---

## How to Use

1. **Select a genre** from the tabs at the top
2. **Fill in the common fields** — protagonist, setting, tone, themes, violence level, etc.
3. **Fill in the genre-specific fields** that appear below
4. **Choose a word count format** — Short Story, Novella, Novel, or Epic
5. **Toggle dark/taboo elements** as needed and save your defaults
6. Optionally **open the Series Manager** to set up a multi-book series with recurring characters
7. Click **Generate with AI** (or randomise first for inspiration)
8. Copy the output, export to PDF, or save as a preset

---

## File Structure

```
book-idea-generator/
├── index.html    ← the entire application
└── README.md     ← this file
```

Everything lives in `index.html`. There are no dependencies, frameworks, or build tools.

---

## Updating

To update the app, simply replace `index.html` in this repository. GitHub Pages will redeploy automatically within about a minute.

---

## Privacy

- Your Anthropic API key is stored in your **browser's localStorage only**
- It is never logged, shared, or sent anywhere other than directly to Anthropic's API
- Presets and author settings are also stored in localStorage — they do not leave your browser unless you export them manually as JSON

---

## License

MIT — do whatever you like with it.
