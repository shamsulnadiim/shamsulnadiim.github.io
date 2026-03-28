# N M Shamsul Islam Nadiim — Portfolio Website

A 6-page dark portfolio website built for GitHub Pages.

## Files
- index.html      — Home / Landing
- about.html      — About, Skills, Photography, References
- portfolio.html  — Academic Projects, Competitions, Logos (tabbed)
- research.html   — Publications, Abstracts, Conferences
- cv.html         — Work Timeline, Education, Awards, Certifications, Volunteering
- contact.html    — Contact form + social links
- shared.css      — All shared styles (fonts, nav, footer, buttons)
- shared.js       — Cursor, scroll, mobile nav
- images/         — FOLDER: put all your photos here (see below)

## Adding Photos

Create a folder called `images/` in the same directory as the HTML files.

### Profile & About Page (about.html)
- `images/profile.jpg` — Hero portrait (3:4 ratio, face visible, 400x530px min)
- `images/about.jpg`   — Secondary portrait for home page

### Photography Gallery (about.html)
From your portfolio PDF (page 19), save the 5 photos as:
- `images/mihrab.jpg`       — Mihrab, Kusumba Masjid (B&W)
- `images/rose-garden.jpg`  — Rose Garden (B&W)
- `images/a-glance.jpg`     — A Glance (B&W)
- `images/in-trouble.jpg`   — In Trouble (B&W)
- `images/a-fuss.jpg`       — A Fuss (B&W, alley scene)
- `images/photo-6.jpg`      — Any additional photo

### Portfolio Projects (portfolio.html)
From your portfolio PDF pages 5-11:
- `images/adamjee-hero.jpg`       — Adamjee Jute Mill render (PDF page 8)
- `images/bulldozers-hero.jpg`    — Beyond Bulldozers (PDF page 9)
- `images/threads-hero.jpg`       — Threads of the City (any suitable image)
- `images/gazipur-hero.jpg`       — Gazipur University model

### Competition Boards (portfolio.html)
From PDF pages 13-15:
- `images/oranges-call.jpg`      — Orange's Call board (PDF page 13 right side)
- `images/living-canopy.jpg`     — A Living Canopy board (PDF page 14 right)
- `images/regenerating-island.jpg` — Regenerating Island (PDF page 15 right)
- `images/eternal-voices.jpg`    — Eternal Voices (any placeholder)

### Logo Images (portfolio.html)
From PDF page 20:
- `images/logo-arcaad.jpg`     — ArcAAD logo
- `images/logo-duetian.jpg`    — DUETian.com logo
- `images/logo-mushfiqur.jpg`  — Mushfiqur Rahim MR15 logo

## How to Add a Photo (example)
In about.html, find the placeholder div:
```html
<div class="bio-photo-ph">
  <div class="big">NI</div>
  <div class="ph-tag">Profile photo</div>
</div>
```
Replace with:
```html
<img src="images/profile.jpg" alt="N M Shamsul Islam Nadiim">
```

## GitHub Pages Deployment
1. Create a GitHub repo named `username.github.io`
2. Upload ALL files (all .html, shared.css, shared.js, and images/ folder)
3. Go to repo Settings > Pages > select `main` branch > Save
4. Site live at `https://username.github.io`

Or use any other repo name, then deploy via:
Settings > Pages > Branch: main > Folder: / (root)
URL: `https://username.github.io/repo-name/`
