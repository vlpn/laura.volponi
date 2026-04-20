# Academic Personal Website (GitHub Pages)

This repository contains a lightweight academic website designed in the style commonly used by economists.

## Pages

- `index.html`: Home
- `research.html`: Research output
- `teaching.html`: Teaching information
- `cv.html`: Embedded and downloadable CV
- `contact.html`: Contact details

## CV: visible + downloadable PDF

The CV file is stored at:

`assets/cv/laura-volponi-cv.pdf`

The page `cv.html` does two things:

1. Embeds this PDF for direct viewing in the browser.
2. Provides a download button for the same file.

To update your CV, replace only `assets/cv/laura-volponi-cv.pdf` with your new PDF using the exact same filename.

## Local preview

Open `index.html` directly in a browser, or use VS Code Live Server if you prefer.

## Deploy on GitHub Pages

1. Create a GitHub repository and push this project.
2. In GitHub, open Settings > Pages.
3. Under "Build and deployment", choose:
	- Source: Deploy from a branch
	- Branch: main
	- Folder: /(root)
4. Click Save. The site will publish from the `main` branch.

## Suggested next edits

- Replace placeholder research entries in `research.html`.
- Update your bio and education entries in `index.html`.
- Keep a monthly update in the footer line.
