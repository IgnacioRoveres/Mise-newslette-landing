# Mise — Newsletter Landing Page

A clean, mobile-first landing page for a fictional weekly cooking newsletter, built to convert visitors into subscribers. Fully responsive and bilingual (English / Spanish) with automatic language detection.

**🔗 Live demo:** [mise-newsletter.netlify.app](https://mise-newsletter.netlify.app/)

> This is a portfolio demo. "Mise" is a fictional brand created to showcase lead-generation landing page design.

---

## Features

- **Single-goal, lead-gen focused** — one clear call-to-action ("Join the Newsletter") repeated at key points, benefit-driven copy, and a minimal email-only form to keep conversions high.
- **Bilingual with auto-detection** — detects the visitor's browser language on load and lets them switch between English and Spanish instantly with a flag toggle. No page reload.
- **Mobile-first & responsive** — designed for phones first, scales smoothly to desktop.
- **Fast & lightweight** — no frameworks, no build step, no dependencies. Loads instantly.
- **Accessible** — keyboard-visible focus states, reduced-motion support, semantic markup, and `lang` attribute updated per language.
- **Basic on-page SEO** — descriptive title and meta description.

## Tech stack

- HTML5
- CSS3 (custom properties, CSS grid, responsive layout)
- Vanilla JavaScript (language switching, form handling, scroll reveals)
- No libraries or frameworks

## Project structure

```
.
├── index.html      # Page structure
├── styles.css      # All styling
└── public/         # Images
    ├── hero.jpg
    └── sample.jpg
```

## Run locally

No build step required. Either:

- Open `index.html` directly in your browser, or
- Serve the folder with any static server, e.g.:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Notes

- Photography from [Unsplash](https://unsplash.com/) (free to use).
- The signup form is front-end only in this demo; in production it would connect to an email service provider (Mailchimp, ConvertKit, etc.).

## Author

**Ignacio Roveres** — Frontend Developer (React) · Landing Pages & Web Apps
🌐 [ignaciovroveres.com.ar](https://www.ignaciovroveres.com.ar/)