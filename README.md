# ArithCalc — Website

Static site for [ArithCalc](https://play.google.com/store/apps/details?id=com.arithcalc.app):
landing page + Privacy Policy. Hosted via **GitHub Pages**.

## Contents
- `index.html` — landing page
- `privacy.html` — Privacy Policy (EN + EL) — the URL you paste into Play Console

## Before publishing — fill the placeholders
Search for `<!-- EDIT -->` in `privacy.html` and replace:
- `[YOUR NAME / COMPANY]` / `[ΟΝΟΜΑ / ΕΤΑΙΡΕΙΑ]`
- `[YOUR EMAIL]` / `[EMAIL ΣΑΣ]`
- "Last updated" date

## Publish on GitHub Pages
1. Create a **public** GitHub repo (e.g. `arithcalc-website`).
2. Push these files to it:
   ```
   git remote add origin https://github.com/<username>/arithcalc-website.git
   git add .
   git commit -m "ArithCalc website: landing + privacy policy"
   git branch -M main
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Source: Deploy from a branch → main / root → Save**.
4. After ~1 min your site is live at:
   - `https://<username>.github.io/arithcalc-website/`
   - Privacy Policy: `https://<username>.github.io/arithcalc-website/privacy.html`
5. Paste the privacy URL into **Play Console → App content → Privacy Policy**.

> This repo is separate from the app repo (which stays private).
