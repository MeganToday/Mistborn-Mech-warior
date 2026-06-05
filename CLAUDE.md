# Mistborn: Mech Warrior

## Project
A browser-based game combining Mistborn (Brandon Sanderson) themes with mech warrior combat.

## Workflow rules

### Commit and push regularly
- As work progresses, commit changes to Git **frequently** and push to GitHub so we never lose progress.
- Make a commit at every meaningful checkpoint: new feature scaffolded, bug fixed, refactor done, content added.
- Use **clean, descriptive commit messages** that explain the *why* in 1–2 sentences. Prefer imperative mood ("add player movement", not "added player movement").
- After committing, push to `origin main` immediately. Do not let local work sit uncommitted or unpushed for long.
- If a session ends with uncommitted work-in-progress, commit it with a `wip:` prefix and push, so nothing is lost.

### Repo layout
- `index.html` — entry point for the game (served via GitHub Pages).
- Additional assets (JS, CSS, images, audio) should live alongside or in clearly named subdirectories.

### Deployment
- The game is deployed via GitHub Pages from the `main` branch root.
- Public URL: https://megantoday.github.io/Mistborn-Mech-warior/
