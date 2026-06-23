# Resume Website (GitHub Pages Ready)

This is a minimal, professional one-page resume site for **Dao Nguyen**.

## How to host on GitHub Pages
1. Create a new repo named: `username.github.io`
2. Upload all files in this folder to the repo root.
3. Commit & push. Your site will be live at `https://username.github.io/`.
-> https://hongdao-jp.github.io/resume/

## Customize
- `index.html`: edit your name, contacts, sections.
- `assets/img/avatar.png`: replace with your photo (84x84 or larger).
- `assets/css/style.css`: tweak colors/spacing if needed.
- -------------------

# NGUYEN THI HONG DAO Portfolio Resume

Drake-inspired single-page portfolio resume, updated from the latest CV dated 2026-06-22.

## Files
- `index.html`
- `style.css`
- `script.js`

## Avatar
Replace the `PHOTO` placeholder in `index.html` with an image tag:

```html
<img src="avatar.jpg" alt="NGUYEN THI HONG DAO" />
```

Then place `avatar.jpg` in the same folder.

## Publish on GitHub Pages

```bash
git init
git add .
git commit -m "Update portfolio resume"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
git push -u origin main
```

Then enable GitHub Pages:

Settings -> Pages -> Build and deployment -> Source: Deploy from a branch -> Branch: main / root.

