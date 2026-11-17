# GitHub profile settings and repository cleanup

This checklist covers account-level changes that are not stored in the profile README itself.

## 1. Profile location

On GitHub, open **Your profile → Edit profile → Location** and change `Er-rich` to `Nador, Morocco` if that is the location you want displayed publicly.

## 2. Pinned repositories

On your profile Overview page, use **Customize your pins** and pin these six repositories in this order:

1. `Application-meteo-multi-villes`
2. `carnet-recettes`
3. `Nour-Academy`
4. `Nour-Academy--Partie-3`
5. `Marchica-Trips`
6. `21_exrecise_DOM`

Pin only repositories you are comfortable showing to recruiters. Keep the private repository private.

## 3. README image path

The profile README is set to use the existing banner image at:

`img/Développeur Full-stack.png`

Keep that exact file in the profile repository. The README uses a URL-encoded relative path so the space and accented character do not break the image URL.

## 4. Broken statistics cards

The old third-party GitHub statistics cards were removed from the replacement profile README because they appeared as broken images in the provided screenshot. GitHub already shows the native contribution calendar on the Overview page. Do not add guessed contribution totals or language percentages.

## 5. Clean tracked files from repositories

For repositories that contain `node_modules/` or `.DS_Store`, add the supplied `.gitignore` file. Then, from that repository's local folder, remove those paths from Git tracking while keeping local copies:

```bash
git rm -r --cached node_modules
 git rm --cached .DS_Store
```

Run only the command for a path that is actually tracked in that repository. Then stage and commit the `.gitignore` and index cleanup. The `--cached` flag keeps local files on disk.

**Do not delete `dist/` automatically.** A project may use that folder for GitHub Pages or another deployment. Check the deployment workflow first.

## 6. Repository name typo

The repository currently linked as `21_exrecise_DOM` contains a spelling mistake. A clean name would be `javascript-dom-exercises`, but rename it only after checking references, Pages settings, and any links that point to the old URL. GitHub normally redirects old repository URLs, but update the profile README and project links as well.

## 7. Email privacy

Your email was visible in the profile screenshot. Keep it public only if you are comfortable receiving messages there. You can remove it from the public profile settings and use LinkedIn as the contact route instead.
