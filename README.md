# Deepak Sharma — Portfolio

A personal designer portfolio site inspired by [billysweeney.com](https://billysweeney.com), featuring an audience-switcher intro section.

## Project Status
This is an in-progress single-page HTML portfolio. The intro/hero section is complete. The rest of the site still needs to be built out.

## What's been built
- **Nav** — logo + Work / About / Contact links
- **Hero section** — split into two columns:
  - **Left**: audience tab switcher ("Who are you?") with 6 personas, each showing a tailored headline + body copy
  - **Right**: photo placeholder (replace with real image)
- **Footer** — location + email

## Design Decisions
- Typography: Fraunces (serif, display) + DM Sans (sans-serif, UI)
- Palette: near-black ink (`#0f0f0f`) on warm off-white (`#fafaf8`)
- Style: editorial minimalism, inspired by billysweeney.com
- Tabs use `data-tab` / `data-panel` attributes for JS targeting
- Fade-up animation on panel switch via CSS keyframes

## What needs to be built next
1. **Work section** — case study grid or list
2. **About section** — longer bio, values, background
3. **Contact section** — email CTA
4. **Add real photo** — replace `.photo-placeholder` with `<img class="hero-photo" src="photo.jpg" alt="Deepak Sharma">`
5. Possibly split into separate CSS and JS files
6. Add a meta description and OG tags for sharing

## Personalization TODOs
- [ ] Replace placeholder copy in each tab panel with real content
- [ ] Update location in footer ("Seattle, WA")
- [ ] Update email in footer (deepak@sharma.design)
- [ ] Add real photo to hero-right
- [ ] Add real work/case studies

## File Structure
```
deepak-portfolio/
├── index.html       # Full single-file site (HTML + CSS + JS inline)
├── README.md        # This file
└── photo.jpg        # Add your photo here (referenced as hero-photo)
```

## Suggested Claude Code prompt to continue
> "I have a single-page designer portfolio in index.html. Please help me:
> 1. Split it into index.html, style.css, and script.js
> 2. Add a Work section below the hero with 3 placeholder case study cards
> 3. Add an About section with bio text
> 4. Add a Contact section with an email CTA
> Keep the same visual style: Fraunces + DM Sans, near-black on warm off-white, minimal borders."
