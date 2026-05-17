# 🪦 Digital Graveyard (Digital Garden)

> “[One] who works with the door open gets all kinds of interruptions, but [they] also occasionally gets clues as to what the world is and what might be important.” — *Richard Hamming*

[![Powered by Quartz v4](https://img.shields.io/badge/Powered%20by-Quartz%20v4-7b97aa?style=flat-square)](https://quartz.jzhao.xyz/)
[![Editor - Obsidian](https://img.shields.io/badge/Editor-Obsidian-7a46f2?style=flat-square&logo=obsidian)](https://obsidian.md/)
[![Framework - Foam](https://img.shields.io/badge/Framework-Foam-007acc?style=flat-square)](https://foambubble.github.io/foam/)
[![Focus - Data & AI](https://img.shields.io/badge/Focus-Data%20%26%20AI-284b63?style=flat-square)](https://github.com/nichsedge)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE.txt)

Welcome to my personal digital garden, affectionately called the **Digital Graveyard**! This is a public space where I publish my notes, networked thoughts, and random tinkerings. It's a graveyard of ideas, specs, notes, and projects that are constantly being resurrected, updated, or left to rest in public. 

Explore the live site here: 🌐 **[nichsedge.github.io/digital-garden](https://nichsedge.github.io/digital-garden)**

---

## 🗺️ Garden Map

The content is organized inside the `content/` directory, following a clean taxonomy for networked thought:

*   🧠 **`content/Knowledge/`** — Networked thoughts, study logs, concepts, and mental models across Data, AI, and computer science.
*   🚀 **`content/Projects.md`** — A repository of side projects, specs, and a curation of "Things I Wish Existed".
*   📚 **`content/Read/`** — Key takeaways, summaries, and logs of books, papers, and essays.
*   ✍️ **`content/Write/`** — Personal essays, tech articles, and speculative writeups.
*   📄 **`content/Resume.md`** — Professional timeline and experience.

---

## 🛠️ Tech Stack & Workflow

This garden is designed for zero-friction writing and highly optimized web rendering:

*   **Editor:** [Obsidian](https://obsidian.md/) & [Foam](https://foambubble.github.io/foam/) for markdown-based, bidirectional linking.
*   **Static Site Generator:** [Quartz v4](https://quartz.jzhao.xyz/) (built on TypeScript, MDX, Preact, and rehype/remark).
*   **Deployment:** Automatic builds and hosting via [GitHub Pages](https://pages.github.com/).

---

## 🚀 Local Setup & Development

If you want to run or preview this digital garden locally, follow these steps:

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) (v22 or higher) and `npm` installed.

### 1. Clone the Repository
```bash
git clone https://github.com/nichsedge/digital-garden.git
cd digital-garden
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Run Development Server
Start the local server to watch for changes and auto-refresh:
```bash
npx quartz build --serve
```
Once running, open **`http://localhost:8080`** in your browser.

### 4. Build Production Bundle
To generate the static HTML files:
```bash
npx quartz build
```

---

## 📄 License

This digital garden is open-source and licensed under the **MIT License**. See [LICENSE.txt](LICENSE.txt) for more details.
