<!-- Auto-generated guidance for AI coding agents working in this repo -->
# Copilot / AI agent instructions — thinhngotony

This repository currently contains a single project README (a personal profile / portfolio README). Use these instructions to be immediately productive and avoid making noisy or incorrect edits.

- Quick repo snapshot
  - Primary file: `README.md` (HTML-flavored Markdown with profile badges and external image URLs).
  - No build scripts, package manifests, test directories, or source folders present.
  - Default branch: `master`.

- Goals for edits
  - Preserve the README's structure and external badges (profile view, trophy, stats images). These are intentionally external links and should not be removed without user confirmation.
  - Keep personal contact and portfolio links intact: e.g., `https://thinhngotony.github.io/`, resume link, and social links.

- What to read first
  - `README.md` (root) — contains the full visible surface of the project.

- Project-specific patterns and examples
  - Badges and stats are image embeds that reference external services. Example patterns to preserve:
    - `https://komarev.com/ghpvc/?username=thinhngotony...`
    - `https://github-profile-trophy.vercel.app/?username=thinhngotony`
    - `https://github-readme-stats.vercel.app/api?...`
  - Links to portfolio and resume are canonical: keep them when editing copy or adding sections.

- Developer workflows (discoverable)
  - There are no build/test commands discoverable in the repo. Any change to site-like content should be verified by:
    1. Rendering the README in GitHub (use the repo README preview) or
    2. If the user maintains a GitHub Pages site (`thinhngotony.github.io`), confirm the live site if the change is intended for that page (ask the user first).

- Safety rules for automated edits
  - Do not add or remove external images/badges without explicit instruction from the user.
  - Avoid adding large new toolchains (e.g., package.json, Dockerfile) unless the user asks; this repo is currently a static profile.
  - When adding files, place new code under a clear top-level folder (for example `src/` or `site/`) and mention that in the PR body.

- Pull request / commit guidance
  - Keep commits small and focused (single logical change per commit).
  - PR description should include: purpose, files changed, and any manual verification steps (README render, link checks).

- When in doubt
  - Ask the repo owner (contact in `README.md`) before making non-trivial content or external-link changes.

If this file should include other project artifacts or workflows (build commands, tests, CI), tell me what to look for and I will merge them into this guidance.
