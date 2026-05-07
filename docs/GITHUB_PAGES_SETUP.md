# GitHub Pages Setup

## Local Structure

```text
github-pages-benchmark/
  index.html
  codex/
    index.html
  claude/
    index.html
  prompts/
    app_recipe_site.md
    research_sushi_market.md
  docs/
    GITHUB_PAGES_SETUP.md
```

## GitHub Pages Settings

Use these repository settings:

- Settings > Pages
- Source: Deploy from a branch
- Branch: `main`
- Folder: `/(root)`

GitHub Pages will publish:

- Top page: `https://<owner>.github.io/<repo>/`
- Codex result: `https://<owner>.github.io/<repo>/codex/`
- Claude result: `https://<owner>.github.io/<repo>/claude/`

## Important Privacy Note

GitHub Pages sites are publicly available on the internet even when the source repository is private, depending on plan and organization settings. Do not publish confidential business data, customer data, API keys, tokens, or internal-only documents here.

## After Running The Benchmark

Replace these files:

- `codex/index.html` with Codex's generated app
- `claude/index.html` with Claude Code's generated app

Then commit and push to `main`.
