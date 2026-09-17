# Senthan & Co — Fitness & Gym Collections

One repository for two distinct Fitness & Gym collections. Collection 1 contains
four established templates. Collection 2 expands the category into seven new
business models using the dedicated `Fitness and Gym.zip` source pack.

## Collection 1 — Foundations (live)

| Template | Niche | Demo URL |
|---|---|---|
| **IRONYARD** | CrossFit / Functional Training | `ironyard-index.html` |
| **STILLWATER** | Yoga & Wellness Studio | `stillwater-index.html` |
| **BARWORKS** | Strength & Powerlifting Gym | `barworks-index.html` |
| **PACELINE** | Running & Endurance Club | `paceline-index.html` |

The root page is the collection gateway and links to every live template.

## Collection 2 — Expansion

1. **KINTU ATHLETIC CLUB** — premium full-service fitness club (live)
2. Personal trainer and coaching business
3. Group-training and HIIT studio
4. Fitness, nutrition and habit coaching
5. Boutique women's fitness studio
6. Recovery and athletic-performance facility
7. Everyday fitness and lifestyle brand

These directions deliberately fill gaps left by Collection 1. They are not
replacement versions of IRONYARD, STILLWATER, BARWORKS or PACELINE.

---

## 1. REPOSITORY STRUCTURE

```
senthan-fitness-templates/
├── index.html                 <- collection gateway
├── README.md                  <- this file
├── ironyard-index.html        <- Collection 1 / functional training
├── stillwater-index.html      <- Collection 1 / yoga and wellness
├── barworks-index.html        <- Collection 1 / strength and powerlifting
├── paceline-index.html        <- Collection 1 / running and endurance
└── collection-2-kintu-index.html <- Collection 2 / premium fitness club
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

### KINTU ATHLETIC CLUB — Premium Full-Service Fitness Club
Collection 2's first template. Mineral-black, rust and electric-lime art
direction for a Kampala club combining strength, conditioning, mobility,
recovery, coaching, class schedules and three membership tiers. It uses ten
distinct images from the dedicated `Fitness and Gym.zip` source pack and
includes responsive layouts, light/dark modes, seven languages with Arabic
RTL, defensive local preferences, scroll reveals and a Back-to-Top Button.

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
3. Upload `index.html`, `README.md`, and each self-contained template HTML file
   at the repository root.
4. Commit directly to `main`.
5. Go to Settings → Pages, set source to `main` / `/ (root)`, save.

Either way, allow a few minutes after enabling Pages for the first deploy —
subsequent updates are usually live within seconds to a minute.

---

## 5. UPDATING A TEMPLATE LATER

Each template is one file. To update IRONYARD, for example, replace
`ironyard-index.html` and push again — no other template file needs to change.

---

## Credits

Built by **Senthan & Co**.
