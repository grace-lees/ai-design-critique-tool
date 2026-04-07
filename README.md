# ai-design-critique-tool

A browser-based design critique tool powered by the Anthropic API. Built to speed up design review cycles by giving structured, multi-mode feedback on any design.

## What it does

- Six critique modes: UX, visual design, accessibility, copy, motion, and overall
- Paste a design description or upload context — get structured feedback instantly
- Markdown export for sharing with teams
- Built as a single HTML file — no setup, no dependencies, runs in the browser

## Why I built it

Design critique was a bottleneck. Getting async feedback from teammates took days. This cuts that to seconds and gives more consistent, structured notes than ad-hoc Slack messages.

## Stack

- Vanilla HTML/CSS/JavaScript
- Anthropic Claude API
- Single-file architecture for portability

## How to use

1. Clone or download `critic-v4.html`
2. Open in any browser
3. Add your Anthropic API key when prompted
4. Start critiquing

## Roadmap

- [ ] Image upload support for direct screenshot analysis
- [ ] Saved critique history
- [ ] Team mode for collaborative review sessions
