# web-basics

Welcome — this repository is a friendly starter kit for learning the basics of web development with HTML and CSS.
It's intentionally simple so students can open and edit everything directly in the browser using vscode.dev on a Chromebook.

## What you'll find in this repo

- `index.html` — a well-commented, accessible, beginner-friendly example page.
- `styles.css` — modern, commented CSS that shows variables, flexbox/grid, responsive breakpoints, and simple transitions.

## Goals

This project helps learners to:

- Edit HTML and CSS in the browser (no installs required).
- Learn semantic HTML elements and accessible patterns.
- Use modern CSS features (variables, Flexbox/Grid, media queries).
- Complete small challenges that build confidence.

## Quick start — open in vscode.dev (Chromebook-friendly)

1. Open a browser and go to: `https://vscode.dev/github/Wm-Mason-Girls-Who-Code/web-basics`
	 - This opens the repository directly in the browser editor (vscode.dev). No local installs required.
2. Click `index.html` in the file explorer to open it.
3. Edit the code on the right. Changes are saved to the repo when you commit (see "Saving changes" below).

## Previewing your page

Option A — Quick preview using an online static preview service (no setup):

- Open this URL in a new tab to view the rendered page (replace branch/path if you change them):

	https://htmlpreview.github.io/?https://raw.githubusercontent.com/Wm-Mason-Girls-Who-Code/web-basics/main/index.html

Option B — RawGithack (stable raw hosting for testing):

- https://raw.githack.com/Wm-Mason-Girls-Who-Code/web-basics/main/index.html

Option C — If students clone locally on a laptop/desktop, they can open `index.html` directly in the browser.

Notes about vscode.dev and live previews:

- vscode.dev runs entirely in the browser and can't run local dev servers. Use the preview links above or enable GitHub Pages for a more permanent hosted copy.

## Saving changes (editing on vscode.dev)

1. Make edits to `index.html` or `styles.css` in the editor.
2. Use the Source Control view (left bar) to stage your changes, add a commit message, and commit.
3. Push changes to GitHub using the push button in the status bar or the Source Control view.

If students don't have push access, they can fork the repo and edit the fork.

## Learning checklist (suggested path)

1. Open `index.html`. Read the comments and find the "TODO" exercise markers.
2. Change the site title and the hero text.
3. Modify colors in `styles.css` by changing the CSS variables at the top.
4. Add a new "feature" card in the Features section and style it.
5. Make the page responsive: use the media query in `styles.css` as a starting point.

## Exercises and challenges

- Beginner (15–30 min):
	- Change the main heading text and update the color variables.
	- Add a new list item to the features list.

- Intermediate (30–60 min):
	- Create a second section that uses CSS Grid with 3 items that wrap on small screens.
	- Add :hover transitions to the feature cards.

- Advanced (60+ min):
	- Add a theme toggle using CSS variables and a tiny script (optional).
	- Replace the hero area with an image background and keep accessible text contrast.

## Teaching tips for advisors

- Encourage semantic markup: use <header>, <nav>, <main>, <section>, and <footer>.
- Talk about accessibility: alt text for images, visible focus states for links, and good color contrast.
- Let students experiment — small, fast iterations build confidence.

## File overview

- `index.html` — example page and in-line comments.
- `styles.css` — main stylesheet using CSS variables and responsive rules.

## Contributing

If you want to add lessons, tasks, or fixes:

1. Fork the repo.
2. Make changes in a branch.
3. Open a pull request explaining your addition.

## License

This repository is licensed under the `LICENSE` file in the project root.

## Requirements coverage

- Provide a basic HTML + CSS page: Done (`index.html`, `styles.css`).
- Make it usable in `vscode.dev` on Chromebooks: Done (instructions + no build tools).
- Include a very detailed README to guide new members: Done (this file).

---
If you'd like, I can also add a short tests/checklist file, an activity worksheet, or a small JavaScript enhancement to show interactivity. Tell me which you'd prefer next.
