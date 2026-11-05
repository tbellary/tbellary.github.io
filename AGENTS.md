# AGENTS.md — Rules for working on tbellary.github.io

This is Teja Bellary's personal website, hosted on GitHub Pages. Any AI agent editing this repo follows these rules.

## 1. Never publish
- **Personal phone number** or home/mailing address. Contact is via email and LinkedIn only.
- Government IDs, dates of birth, immigration or visa status, salary or compensation figures.
- Confidential employer information: internal JPMorgan Chase, ACTO, or Cambridge Brain Sciences data, roadmaps, code names, client names, or screenshots beyond what is already on the CV.
- Names, photos, or contact details of other people (classmates, colleagues, managers, references) without their consent.
- Grades, GPA, transcripts, or test scores unless Teja explicitly provides them for the site.
- API keys, tokens, passwords, or any `.env` / credential file.
- Invented or exaggerated content: every claim, metric, title, and date must come from the CV or from Teja directly.

## 2. Ask Teja first before
- Pushing, committing, or creating/changing anything on GitHub (repo settings, Pages, branches).
- Adding any new personal information not already on the CV (e.g., new roles, projects, photos).
- Changing wording of CV facts (titles, metrics, dates) — even small rephrasing of numbers.
- Adding third-party scripts, analytics, trackers, cookies, forms, or embeds.
- Deleting or overwriting existing files.
- Changing the overall design direction (colors, layout, vibe).

## 3. Style
- **Vibe:** professional and casual — confident, warm, plain English. No buzzword stacking, no emoji in body text.
- **Colors:** Columbia blue palette.
  - Columbia Blue `#B9D9EB` (accents, tiles)
  - Columbia Navy `#1D4F91` (headings, links, buttons)
  - Ink `#0F2440` (body text), Paper `#F7FAFC` (background), White `#FFFFFF` (cards)
- **Typography:** one clean sans-serif (Inter, falling back to system fonts). Generous line height.
- **Navigation:** streamlined — a single sticky top bar with section links; one-page scroll; no nested menus.
- **Content order:** mirror the CV exactly — Education → Experience → Additional Information.
- **Code:** plain HTML + CSS (+ minimal vanilla JS only if needed). No build step, no frameworks. Must work on mobile, pass basic accessibility (alt text, contrast, keyboard focus), and look right in light and dark mode.
- Keep files small and readable; images optimized for the web.
