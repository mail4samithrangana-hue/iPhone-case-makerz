# CaseCraft — Free iPhone Case Maker

A 100% free, browser-based iPhone case design tool. No payments, no login, no server needed.

**Live Demo:** [https://mail4samithrangana-hue.github.io/iPhone-case-maker/](https://mail4samithrangana-hue.github.io/iPhone-case-maker/)

---

## Features

- ✅ **44 iPhone Models** — SE through iPhone 17 (17 series marked as unverified)
- ✅ **30+ Templates** — 10 categories: Minimal, Neon, Luxury, Cyberpunk, Marble, Abstract, Nature, Gradient, Tech, Typography
- ✅ **Canvas Editor** — Drag, scale, rotate layers; full undo/redo (30 states)
- ✅ **Image Upload** — PNG, JPG, WebP supported
- ✅ **Text Layers** — Fonts, glow, outline, shadows, curved text, letter spacing
- ✅ **Shapes & Stickers** — Rectangles, circles, triangles, stars, hearts, 15+ emoji stickers
- ✅ **Background Engine** — Solid, gradient, transparent + patterns (grid, dots, stars, waves, circuit, marble, binary, matrix)
- ✅ **Safe Area & Camera Cutout** overlays for every model
- ✅ **Export** — PNG (72–600 DPI), SVG preview, Project JSON
- ✅ **Local Storage** — Autosave, project gallery, import/export JSON
- ✅ **Model Preset Editor** — Edit any model's dimensions, save & export presets
- ✅ **Dark/Light Mode** — Toggle in toolbar
- ✅ **Performance Mode** — Disables animations for lower-end devices
- ✅ **Fully Offline** — Works without internet after first load
- ✅ **Mobile-friendly** — Touch drag and pinch-to-scale supported

---

## File Structure

```
iPhone-case-maker/
├── index.html          ← Landing page
├── app.html            ← Main editor
├── templates.html      ← Template browser
├── gallery.html        ← Saved designs
├── help.html           ← FAQ & shortcuts
├── privacy.html        ← Privacy policy
├── terms.html          ← Terms of use
├── 404.html            ← Not found page
├── css/
│   └── styles.css      ← All styles (dark theme, glassmorphism)
├── js/
│   ├── models.js       ← iPhone model presets (44 models)
│   ├── templates.js    ← 30+ premade templates
│   ├── storage.js      ← LocalStorage manager
│   ├── editor.js       ← Canvas editor engine
│   ├── export.js       ← Export wizard (PNG/SVG/JSON)
│   ├── gallery.js      ← Gallery page logic
│   └── app.js          ← Editor page orchestrator
├── assets/
│   ├── templates/      ← (future: template thumbnail images)
│   ├── stickers/       ← (future: custom sticker images)
│   └── icons/          ← (future: icon assets)
├── robots.txt
├── sitemap.xml
└── README.md
```

---

## Running Locally

Simply open `index.html` in any modern browser. No build step, no npm, no server required.

To view it like a real website locally, you can use VS Code's **Live Server** extension (click "Go Live" at the bottom right).


---

## 🚀 GitHub Pages Deployment

This project is 100% static HTML/CSS/JS and is designed for GitHub Pages.

1. **Create a new repository** on GitHub (name it `iPhone-case-maker`).
2. **Upload or Push** your files to the `main` branch.
3. Go to your repo **Settings → Pages**.
4. Under **Build and deployment → Source**, ensure **"Deploy from a branch"** is selected.
5. Select the **main** branch and folder **/(root)**, then click **Save**.
6. Your site will be live at `https://USERNAME.github.io/iPhone-case-maker/`.


### ⚠️ Important: Final Configuration
- Open `index.html` and replace `[YOUR-GITHUB-USERNAME]` with your actual GitHub username in the meta tags.
- Verify that your repo name matches `iPhone-case-maker`. If it's different, update the `baseurl` in `_config.yml` and the paths in `robots.txt` and `sitemap.xml`.


---

## Editor Quick Reference

| Action | How |
|--------|-----|
| Move layer | Drag on canvas |
| Resize image | Ctrl+Scroll or Properties panel |
| Rotate layer | Drag orange ⬤ handle |
| Add text | Click "+ Add Text Layer" |
| Undo | Ctrl+Z |
| Redo | Ctrl+Shift+Z |
| Delete layer | Click layer → Delete key |
| Nudge 1px | Arrow keys |
| Nudge 10px | Shift+Arrow keys |
| Export | Click 📤 Export in toolbar |
| Save | Click 💾 Save in toolbar |

---

## iPhone 17 Models

iPhone 17 series dimensions are estimated placeholders (the phone wasn't released at time of writing). The editor displays a warning banner when these models are selected. You can edit preset dimensions via the ⚙️ button next to the model selector.

---

## License

MIT License — Free to use, modify, and distribute.

---

*CaseCraft is 100% free with no payments, no checkout, and no monetization of any kind.*
