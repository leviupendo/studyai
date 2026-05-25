# StudyAI 🎓 — Smart Study Pack Generator

An AI-powered study tool that analyzes any study material and instantly generates:
- **Key Topics** ranked by importance
- **Lecture-style Questions** following Bloom's Taxonomy (recall → analyze)
- **Memory Notes** with highlights for quick memorization

Built with plain HTML, CSS, and JavaScript — no frameworks, no build tools needed.

## How to Use

1. Open `index.html` in any browser
2. Enter your [Anthropic API key](https://console.anthropic.com)
3. Upload a `.txt` / `.md` / `.csv` file **or** paste your study material
4. Click **Analyze & Generate Study Pack**

## Tech Stack

- Vanilla HTML / CSS / JavaScript
- [Anthropic Claude API](https://docs.anthropic.com) (`claude-sonnet-4-20250514`)
- [Tabler Icons](https://tabler-icons.io) for UI icons

## Features

- Drag-and-drop file upload
- Topic importance ranking (High / Medium / Low)
- Bloom's Taxonomy question levels (Recall, Understand, Apply, Analyze)
- Reveal/hide model answers
- Concise memory notes with key highlight
- Fully responsive, works offline (except API calls)

## Setup

No installation required. Just open `index.html` directly in your browser.

You will need a free Anthropic API key:
1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Sign up / log in
3. Navigate to **API Keys** and create a new key
4. Paste the key into the app when prompted

## License

MIT — free to use, modify, and share.
