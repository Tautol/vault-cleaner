# 🧹 Vault-Cleaner

Vault-Cleaner is a lightweight, local-first Markdown optimizer designed for "Second Brain" enthusiasts and users migrating their knowledge bases from Notion to Obsidian.

## 🚀 The Problem
Moving your notes between tools often leaves behind "digital exhaust"—ugly UUIDs, inconsistent tag casing, and broken absolute file paths. Manually cleaning thousands of files is a recipe for burnout.

## ✨ Features
- **Notion Artifact Scrubbing:** Automatically removes the long UUID strings and redundant metadata Notion adds to exports.
- **Tag Standardization:** Normalizes all `#tags` to lowercase to prevent duplicate categories (e.g., `#Work` and `#work` become one).
- **Relative Link Converter:** Swaps absolute Mac paths (e.g., `/Users/name/Vault/`) for relative paths (`./`), ensuring your links work across different devices.
- **100% Privacy:** All processing happens inside your browser. Your notes never leave your computer and are never uploaded to a server.

## 🤖 The Agentic Workflow (How this was built)
Vault-Cleaner is an experiment in **AI-native software development**. This project was not written by a human developer in the traditional sense, but orchestrated by **Hermes Agent**.

The development process followed a corporate structure:
1. **CEO (Hermes):** Set the strategy and managed the team.
2. **Market Analyst (AI):** Identified the underserved gap in the PKM community.
3. **Lead Developer (AI):** Architected the logic and wrote the code.
4. **Growth Hacker (AI):** Designed the distribution and lead-generation strategy.

By utilizing specialized sub-agents, the "company" moved from market research to a live, deployed product in under an hour.

## 🛠️ How to Use
1. Visit the live app: [https://Tautol.github.io/vault-cleaner/](https://Tautol.github.io/vault-cleaner/)
2. Paste your Markdown content into the editor.
3. Click the cleaning buttons that match your needs.
4. Copy the result back to your vault or download it as a `.md` file.

## 📄 License
MIT
