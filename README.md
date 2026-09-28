# Meridian AI — Marketing Site (placeholder brand)

A static marketing site inspired by the general structure of a modern AI-consultancy
landing page (hero → problem/"gap" stat → who-we-are → delivery model → services →
social proof → contact CTA → footer), built from scratch with original copy, design,
and code.

**"Meridian AI" is a placeholder brand name** — swap it for the real name before
launch. It appears in:

- `<title>` tags and meta descriptions on every page
- The `.brand` text in the header/footer on every page
- Footer copyright line

A simple find-and-replace of `Meridian AI` across the `.html` files will rename it.

## Structure

```
index.html          Home
services.html        Services
about.html           About
team.html            Team
blog.html            Blog index
blog/*.html          Blog posts
contact.html         Contact form
privacy.html         Privacy policy (placeholder — needs legal review)
assets/styles.css    Shared styles (dark theme, lime accent)
assets/main.js       Mobile nav toggle + contact form handling
```

## Running locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000

## Publishing

This is a static site — it can be hosted on GitHub Pages, Netlify, Vercel, or any
static host. For GitHub Pages: Settings → Pages → Deploy from branch → `main` / `/ (root)`.

## Notes

- The contact form is front-end only (no backend). Wire it to a form service
  (Formspree, Netlify Forms) or your own endpoint before launch.
- Team photos are placeholder initials — replace with real headshots.
- Client "trusted by" logos are placeholder text wordmarks — replace with real
  logos (with permission) or remove the section.
