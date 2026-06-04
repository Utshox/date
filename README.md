# Where do we eat? 🍽️ (Apkasų 17, Vilnius)

A single-file spin-the-wheel restaurant picker for spots near Apkasų g. 17, Vilnius.
Pure HTML/CSS/JS — no build step, no framework, no Vercel. Drop-in for GitHub Pages.

## Run locally
Just open `index.html` in a browser.

## Edit the places
Open the site, expand **"Edit the list of places"**, and edit lines in the form:

```
🍕 | Restaurant Name
```

Your edits are saved in the browser (localStorage). To change the built-in defaults
for everyone, edit the `DEFAULTS` array near the top of the `<script>` in `index.html`.

## Deploy to GitHub Pages
1. Push this folder to a GitHub repo.
2. Repo → **Settings → Pages**.
3. Source: **Deploy from a branch** → Branch: `main` → Folder: `/ (root)` → **Save**.
4. Wait ~1 min. Site is live at `https://<your-username>.github.io/<repo-name>/`.
