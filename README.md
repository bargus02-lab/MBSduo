# MBSduo

A gamified, Duolingo-style learning app for mortgage-backed securities. Navy & white theme, 7 sections, 36 units, 180 questions — beginner to advanced.

**Play it:** https://bargus02-lab.github.io/MBSduo/

## Structure

- `MBSduo.html` — single-file source (open it directly in a browser).
- `dist/index.html` — the static build deployed to GitHub Pages.
- `.github/workflows/deploy.yml` — pushes `dist/` to the `gh-pages` branch on every push to `main`.

## Local play

Open `MBSduo.html` in any browser — no install required. Progress saves to `localStorage`.

## Sections

1. Foundations
2. Securitization 101
3. Agency MBS
4. CMOs & Tranches
5. Risk & Valuation
6. Non-Agency & CMBS
7. Trading & Markets

Hearts regenerate every 30 minutes, daily streak tracks consecutive play days, badges unlock at milestones.
