# Will you go on a date with me? 💗

A cute, interactive single-page "ask her out" site for sending to your girlfriend.
Pure HTML/CSS/JS — no build step, no framework, no Vercel. Drop-in for GitHub Pages.

## The flow
1. **"Will you go on a date with me?"** — the **No** button runs away from the cursor, only **Yes** works.
2. **Pick a day & time.**
3. **"What are you feeling?"** — food vibes, each tied to a real spot near Apkasų g. 17, Vilnius (1–3 km).
4. **The plan** — she taps **Copy the plan** (or **Send on WhatsApp**) and sends it back to you. 🥰

## Personalize (2 lines)
Open `index.html`, near the top of the `<script>`:

```js
const MY_NAME  = "";   // your name, shows in the plan. Leave "" to hide.
const WA_PHONE = "";   // your number, intl format no + (e.g. 37060000000), for the WhatsApp button.
```

Change the restaurants by editing the `FOODS` array right below.

## Run locally
Open `index.html` in a browser.

## Deploy (GitHub Pages)
Settings → Pages → Deploy from a branch → `main` / `/ (root)`. Live in ~1 min.
