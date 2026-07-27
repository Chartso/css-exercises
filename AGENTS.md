# AGENTS.md

## Purpose
This repository is a collection of static CSS exercises for The Odin Project. Each exercise lives in its own folder and is solved by editing the provided `index.html` and/or `style.css` files.

## How to work effectively
- Read the exercise `README.md` in the selected exercise folder before changing files.
- Use the exercise self-check list as the primary requirements source.
- Open the HTML file in a browser or preview extension to verify visual results.
- There is no build or test toolchain in this repo. Do not assume npm, webpack, or any bundler is required.

## Repo structure
- `foundations/`, `advanced-html-css/`, and `intermediate-html-css/` contain exercise directories.
- Typical exercise folder contains:
  - `index.html`
  - `style.css`
  - `README.md`
  - `solution/` (reference example solution only)

## Recommended behavior for AI agents
- Prefer adding styles to existing selectors rather than duplicating selector definitions.
- Do not modify or use `solution/` files unless the user explicitly asks for a comparison or explanation.
- Keep edits scoped to the current exercise folder unless asked to make repo-wide cleanup.
- When asked for help, explain CSS concepts and selectors clearly instead of only giving final code.

## Important notes
- The root `README.md` warns against opening PRs to merge exercise solutions into the upstream repository. Treat this repo as a personal practice fork.
- If a task is ambiguous, ask which exercise folder or learning outcome the user wants to address.

## Reference
- [Repository README](README.md)
