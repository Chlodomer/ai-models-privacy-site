# AI Models, Privacy, and Academic Practice

A static faculty-facing web guide based on the April 27, 2026 meeting on AI privacy, model choice, context, validation, and assessment.

## Live Site

Once GitHub Pages finishes publishing, the site will be available at:

https://chlodomer.github.io/ai-models-privacy-site/

## What This Is

This guide is intended for Bar-Ilan faculty, clinicians, researchers, and students who need practical AI guidance without technical jargon. It focuses on:

- choosing the right AI tool for the task
- handling sensitive or identifiable material responsibly
- giving AI systems enough context to work well
- checking AI outputs against real evidence
- designing assessment that proves understanding

## Project Structure

```text
.
├── index.html
├── assets/
│   ├── design-concept.png
│   ├── faculty-workshop.png
│   ├── local-workstation.png
│   └── source-validation.png
├── PRODUCT.md
├── DESIGN.md
└── README.md
```

## Local Preview

No build step is required. Open `index.html` directly in a browser, or run a tiny local server from this folder:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Updating the Site

Edit `index.html` and the files in `assets/`, then commit and push:

```bash
git add .
git commit -m "Update site"
git push
```

GitHub Pages will republish automatically after the push.

## Notes

The site is static HTML, CSS, JavaScript, and image assets. There are no external packages, no server code, and no private data files in this repository.
