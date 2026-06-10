# Repository Purpose

This repository powers the GitHub user website for `anthony-cervantes.github.io`.

Primary purpose:
- Serve as the root domain homepage.
- Host a links/landing page for public projects.
- Host project and portfolio content.

Current project site deployments (e.g., `patch-force-runtime-rebellion`) are separate repositories and are linked from this root site.

# What Not To Do Here

- Don’t edit gameplay code in this repo.
- Don’t commit binary game builds from other repos.
- Don’t edit GitHub Actions workflow files for other repos from this repo.
- Keep this repo focused on the website front-end assets and content.

# Preferred Workflow

- Default branch: `master`
- Edit content in `index.html` (or other site assets) and commit directly.
- Keep changes small and scoped.
- Commit with clear messages describing page/content updates.
- Push to `master` after review.

# Deployment

GitHub Pages is enabled for:
- `https://anthony-cervantes.github.io/`
- Legacy Pages source currently used in this repo.

After edits:
1. `git add <files>`
2. `git commit -m "..."`
3. `git push`
4. Wait for GitHub Pages build to complete.

# Assets and Links Notes

- Use HTTPS links for all external resources where possible.
- Keep root-page project links explicit and easy to maintain.
- Existing game project link:
  - `https://anthony-cervantes.github.io/patch-force-runtime-rebellion/`

# Safety / Security

- Do not commit credentials, tokens, API keys, `.env`, or secrets.
- Do not include sensitive data in public HTML or scripts.
