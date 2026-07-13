# Swostishree Gurukul — Website Redesign

A redesigned homepage for [Swostishree Gurukul](https://swostishreegurukul.edu.np/), an IB Continuum school in Sanobharyang, Kathmandu.

## Live preview
Once GitHub Pages is enabled (Settings → Pages → Deploy from branch → `main` → `/root`), the site will be live at:
`https://<your-username>.github.io/swostishree-gurukul-redesign/`

## Design decisions
- **Palette:** forest green `#1B4332`, burnt orange `#BC4B12`, golden `#D4A373`, navy `#1A2D42` — muted, institutional, warm.
- **Typography:** Crimson Pro (headings) + Atkinson Hyperlegible (body) + Noto Serif Devanagari (Nepali tagline).
- **Signature element:** the IB Continuum timeline (Early Years → PYP → MYP → DP → University).
- **Layout:** alternating text/image bands and a horizontal "Experience" strip, modeled on islington.edu.np.
- Images are hotlinked from the school's live site. For production, download them into an `images/` folder and update the `src` paths so the site doesn't depend on the old server.

## Structure
Single self-contained file: `index.html` (all CSS and JS inline). No build step — open it in a browser or serve statically.

## Editing tips
- Colors live in the `:root` CSS variables at the top of `index.html`.
- Each section is marked with an `id` (`#continuum`, `#programmes`, `#experience`, `#facilities`, `#news`).
- Stats in the stats strip must stay verifiable — do not add claims the school can't back up.

## TODO
- [ ] Inner pages (About, Admissions, Programme detail pages)
- [ ] Download and self-host images
- [ ] Real social media links in the footer
- [ ] Nepali language version
