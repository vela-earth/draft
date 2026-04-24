# VELA — Market Entry & Project Development

Website for VELA, a Cape Town-based consultancy bridging European climate and agricultural solutions to Southern African markets.

**Live site:** [vela.earth](https://vela.earth)

---

## Project structure

```
vela-website/
├── index.html      # Main HTML
├── styles.css      # All styles
├── main.js         # Mobile nav, scroll behaviour, fade-in animations
├── images/         # Add team photos here (see below)
└── README.md
```

---

## Deploying via GitHub Pages

1. Push this folder to a GitHub repository (e.g. `vela-website`)
2. Go to **Settings → Pages**
3. Under *Source*, select **Deploy from a branch → main → / (root)**
4. Your site will be live at `https://yourusername.github.io/vela-website/`

If you own the domain `vela.earth`, add a `CNAME` file to the repo root containing just:

```
vela.earth
```

Then point your DNS to GitHub Pages per [GitHub's custom domain docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

---

## Adding team photos

1. Create an `images/` folder in the project root
2. Add your photos as `images/tijmen-laan.jpg` and `images/jan-willem-kruijt.jpg`
3. In `index.html`, find the team section and replace each placeholder `<div>` with an `<img>` tag — instructions are in the comments directly above each placeholder

---

## Updating content

All content lives in `index.html`. Key sections:

| Section | ID / selector |
|---|---|
| Navigation | `<nav>` |
| Hero | `<section class="hero">` |
| Stats | `<div class="stats-section">` |
| Mission | `<div class="mission-section">` |
| How we work | `<section id="solutions">` |
| Expertise tags | `<div class="expertise-tags">` |
| Client work / cases | `<section id="cases">` |
| Team | `<section id="team">` |
| Funding instruments | `<section id="funding">` |
| CTA | `<div class="cta-section">` |
| Footer | `<footer>` |

---

## Colors

| Token | Hex | Usage |
|---|---|---|
| `--dark` | `#1a1a18` | Text, dark backgrounds |
| `--sand` | `#f0ece3` | Main background |
| `--teal` | `#1d5c4a` | Primary brand colour |
| `--lime` | `#c8e86a` | CTA buttons, accents |
| `--text-muted` | `#6b6960` | Body copy, secondary text |

---

© 2026 VELA · Cape Town, South Africa
