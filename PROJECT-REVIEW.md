# Project-by-project actions

Use the README files in `project-readmes/` only for the repositories listed below. They are drafted from the project descriptions and requirements already shared in the conversation. Check the actual project scripts and folder names before adding any extra run commands.

## Replace the existing README with the supplied file

- `carnet-recettes/README.md` → repository `carnet-recettes`
- `nour-academy/README.md` → repository `Nour-Academy`
- `nour-academy-partie-3/README.md` → repository `Nour-Academy--Partie-3`
- `javascript-dom-exercises/README.md` → repository `21_exrecise_DOM`

## Keep the existing README and improve it instead

- `Application-meteo-multi-villes`: the existing README was already more complete. Keep it; add a genuine screenshot and a working live-demo URL only if one is available. Do not invent a demo URL.
- `Marchica-Trips`: the existing README was already comparatively detailed. Keep it; focus on cleaning tracked files and making its demo URL consistent with the actual deployment.

## Repository cleanup

The `.gitignore` in `gitignore-templates/` is a starter template. Merge its entries into each project's existing `.gitignore`; do not overwrite existing deployment rules.

For paths confirmed to be tracked, run the relevant command from that repository's folder:

```bash
git rm -r --cached node_modules
 git rm --cached .DS_Store
```

`--cached` removes files from Git tracking but leaves local copies in place. Only run the line for a path that exists and is tracked.

Do not remove `dist/` automatically. Check the Pages or deployment workflow first because the folder may be intentionally published.
