# ratnor.github.io — Personal Portfolio

Personal portfolio and photography site for **Ratna Emani** — Application Engineer, API Developer, and AI systems builder based in Oakville, ON.

Live at **[ratnor.github.io](https://ratnor.github.io)**

-----

## Stack

Plain HTML, CSS, and vanilla JavaScript — no build step, no dependencies, no framework.

One file: `index.html`.

-----

## Features

- **Work** — Selected projects: multi-agent developer tooling, RAG pipeline PoC, personal finance AI system, IoT prototype
- **About** — Career timeline, skills, and education
- **Photography** — Landscape, street, and travel photography
- **Contact** — Links to LinkedIn, GitHub, and email
- Fully responsive — mobile, tablet, desktop
- Scroll-reveal animations, fixed nav with active state tracking
- Film grain texture, warm dark editorial aesthetic

-----

## Editing

Everything is in `index.html`. No build process required.

**To update content:** open `index.html` and edit the relevant section directly.

**To update photos:** replace the `.jpeg` files in the repo root. Update the `src` attribute in the corresponding `<img>` tag in `index.html` to match the new filename. Note: filenames with spaces must be URL-encoded in the `src` (e.g. `IMG 9302.jpeg` → `src="IMG%209302.jpeg"`).

**To deploy:** push to the `master` branch. GitHub Pages serves directly from root — no build step needed. Changes are live within ~60 seconds.

-----

## Repo structure

```
ratnor.github.io/
├── index.html          # Entire site
├── DSCF1301.jpeg
├── DSCF1329.jpeg
├── DSCF1399.jpeg
├── IMG 9302.jpeg
├── IMG 9328.jpeg
├── 100 0857.jpeg
└── verrena1merge.jpeg
```
