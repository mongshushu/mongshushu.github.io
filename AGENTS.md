# AGENTS.md

## Project Overview

- This project is an Astro-based personal homepage.
- The site currently has Home, About, Projects, and Posts pages.
- Shared Layout, Header, Navigation, and Footer live in `src/layouts/BaseLayout.astro`.
- Projects use card-style summaries and static detail pages under `src/pages/projects/`.
- Project data is managed in `src/data/projects.json`.
- Post sample data is managed in `src/data/posts.json`.
- The final deployment target is a GitHub Pages `github.io` address.

## Rules for AI Agents

1. Do not add new libraries without the user's approval.
2. Do not modify unrelated files.
3. Do not write secrets, tokens, passwords, or API keys in code.
4. Always ask before running delete commands.
5. After making changes, explain which files were changed and why.
6. Keep display data separate from page rendering when practical.
7. If connecting an external content source later, convert the raw API response into a simple display structure before rendering it.
8. For projects, prefer `title`, `description`, `role`, `tools`, `result`, `detail`, and `slug`.
9. For posts, prefer `title`, `slug`, `date`, `summary`, and `tags`.
10. After changes, prefer checking the browser view and running `npm run build`.
11. Before commit or push, summarize the changed files and ask for user approval.
12. Use commit messages in one of the following formats:
   - `feat: 한국어설명`
   - `fix: 한국어설명`
   - `chore: 한국어설명`
   - `docs: 한국어설명`
13. When presenting a command, explain what the command does in a way that beginners can understand.
14. Clearly state whether the command is safe to run.
