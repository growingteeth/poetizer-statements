# Poetizer Statements — GitHub Pages setup

This package is the complete website in a single file: `index.html`.
No build step, no workflow, no other files needed.

## Deploy (mobile Chrome, same flow as ClownWatch / CRTV)

1. Download `poetizer-statements-site.zip` on your phone and unzip it with the Files app.
2. In Chrome, go to github.com and sign in (growingteeth).
3. Create a new repository:
   - Name: `poetizer-statements`
   - Visibility: Public
   - Create repository
4. In the new repo, tap "uploading an existing file" and upload `index.html`.
   Commit the change.
5. Go to repo Settings → Pages:
   - Source: "Deploy from a branch"
   - Branch: `main`, folder `/ (root)`
   - Save
6. Wait a minute or two, then open:
   https://growingteeth.github.io/poetizer-statements/

That address opens in any browser, including Instagram's in-app browser —
no Muse account or app needed.

## Updating the site later

When statements are added or edited on the Muse version, ask for a fresh
export, then in the repo: Code → index.html → edit/upload → replace the file
with the new `index.html` and commit. Pages redeploys automatically.
