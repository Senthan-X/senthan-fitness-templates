# Senthan & Co — Fitness Template Collection

Four fitness website templates sharing one build system: dark/light theming,
7-language support, and fully self-contained HTML with no frameworks, no build
step, and no external image folders.

**Live demos (once deployed to GitHub Pages):**

| Template | Niche | Demo URL |
|---|---|---|
| **IRONYARD** | CrossFit / Functional Training | `https://<username>.github.io/<repo>/ironyard/` |
| **STILLWATER** | Yoga & Wellness Studio | `https://<username>.github.io/<repo>/stillwater/` |
| **BARWORKS** | Strength & Powerlifting Gym | `https://<username>.github.io/<repo>/barworks/` |
| **PACELINE** | Running & Endurance Club | `https://<username>.github.io/<repo>/paceline/` |

Replace `<username>` and `<repo>` with your GitHub username and this
repository's name once it's live. The root page (`/`) is a landing page that
links to all four.

---

## 1. REPOSITORY STRUCTURE

```
senthan-fitness-templates/
├── index.html          <- landing page linking to all 4 demos
├── README.md            <- this file
├── ironyard/
│   └── index.html       <- CrossFit template (self-contained)
├── stillwater/
│   └── index.html       <- Yoga template (self-contained)
├── barworks/
│   └── index.html       <- Strength template (self-contained)
└── paceline/
    └── index.html       <- Running template (self-contained)
```

Each `index.html` is a complete, standalone site — HTML, CSS, JS, images
(base64-embedded), and all 7 language translations in one file. Nothing else
needs to be uploaded for any individual template to work.

---

## 2. THE FOUR TEMPLATES

### IRONYARD — CrossFit / Functional Training
Bronze & ink palette. Big Shoulders Display + IBM Plex Sans. Program cards
tagged with real WOD vocabulary (AMRAP, EMOM, FOR TIME). All 21 images are
original to this template.

### STILLWATER — Yoga & Wellness Studio
Sage & cream palette. Fraunces + Karla. Classes tagged by real practice
terminology (Vinyasa, Hatha, Yin, Pranayama). All 21 images are original to
this template.

### BARWORKS — Strength & Powerlifting Gym
Graphite & crimson palette. Anton + Roboto. Lift cards organized by training
focus (lower body, upper body, posterior chain, hypertrophy). Images are
reused from the IRONYARD and STILLWATER upload batches — real photos that
didn't fit those niches but suit strength training well. Disclosed in this
template's own README.

### PACELINE — Running & Endurance Club
Slate-blue palette. Barlow Condensed + Mulish. Training organized by real
running vocabulary (Track, Long Run, Off-Road, Easy Pace). Only 4 of 21
images are original to this template — the rest are disclosed reuse from
the other three (there wasn't enough fresh running-specific photography in
the original upload batch). Full explanation in this template's own README.

**Shared across all four:** dark/light theme toggle (icon-based sun/moon
switch), 7 languages (English, Spanish, French, German, Arabic with full RTL,
Portuguese, Chinese Simplified — 79/79 translation keys verified per
template), fully responsive layout, scroll-reveal animations, and CSS
custom-property theming that lets you re-color an entire site by changing
one variable.

---

## 3. IMPORTANT — IMAGE LICENSING

**None of the photography in these four templates has confirmed commercial
redistribution rights.** The images came from a personal reference/moodboard
collection, not original photography, and in several cases known stock or
brand-watermarked images were identified and excluded during the build (see
each template's own README for specifics).

**Before using any of these live, on Codester, or anywhere public-facing:**
mark the images as preview/demo only, or replace them with photography you
have confirmed rights to. Each template's own README repeats this in more
detail, since the specifics differ slightly between templates.

---

## 4. DEPLOYING TO GITHUB PAGES

### Option A — Termux (command line, on your phone)

```bash
cd senthan-fitness-templates
git init
git add .
git commit -m "Fitness template collection"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```

Then in the repo's GitHub Settings → Pages, set the source branch to `main`
and folder to `/ (root)`. GitHub will publish the site at
`https://<username>.github.io/<repo>/` within a minute or two.

### Option B — Browser upload (no command line)

1. Create a new repository on GitHub (github.com/new).
2. On the repo page, choose "uploading an existing file."
3. Drag in `index.html` and `README.md` at the root, then create each of the
   four folders (`ironyard`, `stillwater`, `barworks`, `paceline`) by typing
   the folder name followed by `/` before the filename in the upload box
   (e.g. `ironyard/index.html`), and upload each template's `index.html` into
   its matching folder.
4. Commit directly to `main`.
5. Go to Settings → Pages, set source to `main` / `/ (root)`, save.

Either way, allow a few minutes after enabling Pages for the first deploy —
subsequent updates are usually live within seconds to a minute.

---

## 5. UPDATING A TEMPLATE LATER

Each template is one file. To update IRONYARD, for example, just replace
`ironyard/index.html` with a new version (same filename) and push/upload
again — no other files need to change.

---

## Credits

Built by **Senthan & Co** — jonathanrivers0414@gmail.com · +256 754069314
