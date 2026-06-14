# Final Web Project — How to Host & Submit

## What's in this folder
```
final-web-project/
├── index.html          ← Bootstrap professional home page
├── resume.html         ← Bootstrap HTML résumé page
├── css/
│   ├── custom.css      ← overrides Bootstrap (never edit Bootstrap itself)
│   └── scratch.css     ← from-scratch stylesheet
├── html/
│   ├── scratch.html    ← FROM-SCRATCH page (this URL is what you submit)
│   └── app.html        ← Spanish flashcard web app
└── images/             ← hero, flags, profile, culture (all home-made)
```

## Before you publish — 2 quick swaps
1. **Your photo:** replace `images/profile.jpg` with a real photo of yourself (keep the same filename, or update the `src` in `resume.html`).
2. **Tableau viz (optional):** the page ships with a working sample graph from Tableau's own docs. To use your own: go to public.tableau.com → open any viz → Share icon → **Embed Code** → copy the viz URL and paste it into the `src` of the `<tableau-viz>` tag in `html/scratch.html`.

## Publish to GitHub Pages
1. Go to github.com and create a **new repository** (e.g. `web-project`). Make it **Public**.
2. On the repo page, click **Add file → Upload files**, then drag in the WHOLE contents of this folder (index.html, css/, html/, images/). Commit.
3. Go to **Settings → Pages**.
4. Under "Build and deployment", set **Source: Deploy from a branch**, Branch: **main**, folder **/ (root)**. Save.
5. Wait ~1 minute. GitHub shows your site URL at the top of the Pages settings.

## Your submission URL (the scratch page)
It will look like:
```
https://YOURUSERNAME.github.io/web-project/html/scratch.html
```
Paste THAT into MyEducator (not index.html). Open it on your phone too, to confirm it works for anyone.

## Self-grading checklist (matches the assignment questions)
- ✅ Hosted online (GitHub Pages)
- ✅ Professional Bootstrap pages + custom override CSS (`custom.css`)
- ✅ HTML résumé (not a PDF) — `resume.html`
- ✅ From-scratch page — `html/scratch.html`
  - ✅ Embedded YouTube video (TED-Ed, allows embedding)
  - ✅ Custom background color (`scratch.css` body)
  - ✅ On-page anchor (Jump-to links)
  - ✅ Unordered list nested inside an ordered list (Countries card)
  - ✅ Image not from Bootstrap (hero, flags)
- ✅ Custom stylesheet (`scratch.css`): 10+ styles, font color, font family, 3+ positioned divs, linked & applied
- ✅ Interactive Tableau graph (not an image)
- ✅ Navigation from scratch page back to professional pages
- ✅ Web app linked from scratch page; app links back to scratch page

## Test the YouTube video AFTER hosting
Embedded YouTube does **not** play from a local file — it only works on the live (https) site. Open your hosted scratch page and press play to confirm. If a video ever shows "Video unavailable," it just means that creator disabled embedding — swap the ID after `/embed/` in the iframe for another video.
