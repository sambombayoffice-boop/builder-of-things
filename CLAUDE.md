# CLAUDE.md

Project guidance for Claude Code.

## About this project

Builder of Things / Bombaybot — a premium AI-first studio portfolio website.
Static HTML site (`index.html`, `index-v2.html`) served via `http-server`.

- Run locally: `npm start` (serves on port 8080)
- Deploy target: Vercel (see `DEPLOY.md`, `vercel.json`)
- GitHub repo: `sambombayoffice-boop/builder-of-things`

## Working preferences (standing rules)

- **Everything must live in a GitHub repo.** No project should sit only on the
  local disk — work belongs in version control with a remote on GitHub.
- **Choose the right repo for each piece of work** rather than dumping
  everything in one place:
  - If the work clearly extends an existing project, commit it to that
    project's repo.
  - If it's a genuinely new, standalone project, it gets its own new repo
    (named for what it is), not a folder bolted onto an unrelated repo.
  - When it's ambiguous which repo something belongs to, ask before
    committing.
- Always commit with clear messages and push to the remote so nothing is lost.
