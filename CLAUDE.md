# CLAUDE.md — LAQAB Website

## Stack
- Pure HTML/CSS/JS (static site)
- GitHub Pages on `gh-pages` branch
- Deployment at `kaifashraff.github.io/laqab/`

## Commands
- Deploy: `git push origin master:gh-pages --force`
- Both `index.html` and `laqab.html` must be in gh-pages
- GitHub Pages builds ~2 min after push

## Conventions
- Use `laqab.html` for dev, copy to `index.html` for Pages root
- All WA links: `wa.me/919987314177?text=...`
- Gold/black/cream theme via CSS custom properties
- Mobile-first responsive design
- Lead forms POST to Telegram Bot API + backup to dashboard API

## 12 Rules (Applied)
1. Think Before Coding — understand the brand positioning first
2. Simplicity First — static HTML, no build tools, no frameworks
3. Surgical Changes — edit only the section being changed
4. Goal-Driven — lead conversion is success criteria
8. Read before write — check current HTML structure before editing
11. Match existing style — gold/cream palette, serif headings, WA buttons
12. Fail loud — form submission must show visible success/failure
