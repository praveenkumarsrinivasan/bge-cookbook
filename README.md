# EggHead Cookbook

A collection of tried-and-tested recipes for the Big Green Egg and kamado-style cooking -- from low-and-slow smokes to high-heat sears.

Built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/). Live at https://praveenkumarsrinivasan.github.io/egghead-cookbook/

## What's Inside

- **63+ recipes** across beef, chicken, lamb, pork, seafood, sides, desserts, sauces & rubs, vegetarian
- **Techniques** -- temperature guides, roasting charts, steaming charts, Big Green Egg startup process
- **History** -- the story of kamado cooking from ancient clay pots to modern ceramics (3,000+ years)
- **Visual guides** -- Big Green Egg component illustrations and cooking setup diagrams

## Recipe Categories

| Category | Count |
|----------|-------|
| Beef | 13 |
| Chicken | 12 |
| Pork | 8 |
| Lamb | 5 |
| Seafood | 3 |
| Sauces & Condiments | 6 |
| Sides | 6 |
| Desserts | 3 |
| Techniques | 6 |
| Vegetarian | TBD |

## Quick Start

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Open http://127.0.0.1:8000 in your browser.

## Build

```bash
mkdocs build
```

## Adding Content

1. Add or edit markdown files under `docs/`.
2. Update `mkdocs.yml` under `nav` if adding a new page.
3. Preview with `mkdocs serve`.

## Deploy

Automatically deploys to GitHub Pages via GitHub Actions on push to main/master.

Manual deploy:

```bash
mkdocs gh-deploy
```

## Project Structure

```
egghead-cookbook/
├── docs/
│   ├── index.md                 # Homepage
│   ├── history.md               # Kamado cooking history
│   ├── recipes.md               # Master recipe index
│   ├── recipes/                 # 10 category folders
│   └── assets/
│       ├── images/              # Recipe and component images
│       └── stylesheets/         # Custom CSS
├── mkdocs.yml                   # Site configuration
├── requirements.txt             # mkdocs-material==9.5.33
└── .github/workflows/           # GitHub Actions CI/CD
```
