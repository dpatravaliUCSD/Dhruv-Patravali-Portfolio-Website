# Personal Portfolio · Bioinformatics Template

A clean, single-page site tailored for showcasing a bioinformatics-focused
computer science profile. Built with plain HTML/CSS/JS so it deploys instantly
to GitHub Pages without a build step.

## Structure

- `index.html` — semantic layout with modular sections (hero, metrics, expertise,
  projects, experience, publications, contact).
- `styles.css` — modern, responsive styling with CSS variables for quick tweaks.
- `scripts.js` — progressive enhancement (mobile navigation toggle, scroll spy,
  automatic year stamp).
- `assets/` — drop your résumé PDF, headshot, slide decks, and diagrams here.

## Quick start

1. **Preview locally**
   ```bash
   cd /Users/dhruv.patravali/Documents/Personal\ Portfolio
   python3 -m http.server 4000
   ```
   Visit `http://localhost:4000` to test interactions and responsiveness.

2. **Customize content**
   - Update hero copy, metrics, and cards inside `index.html`.
   - Swap placeholder project/publication links with real URLs.
   - Add or remove chips/bullets to match your expertise.
   - Replace `YOUR-LINKEDIN` and `YOUR-GITHUB` with live profiles.

3. **Add assets**
   - Export your résumé as `assets/Dhruv_Patravali_Resume.pdf` (or update the
     link in `index.html`).
   - Store screenshots, diagrams, or slide decks in `assets/` and reference them
     with relative paths (e.g., `assets/pipeline-overview.png`).

4. **Tune styling (optional)**
   - Adjust color tokens, spacing, or typography in `styles.css`.
   - Extend the layout using the existing utility classes (`grid`, `card`,
     `panel`, etc.).

## Deploy to GitHub Pages

1. Create a GitHub repository named `dhruv-patravali.github.io` (replace with
   your GitHub username).
2. Push the contents of this folder to the repository’s `main` branch.
3. In the repository settings, enable GitHub Pages (it should auto-detect the
   root). Your site will be available at
   `https://<username>.github.io/`.
4. Each time you update the site locally, commit and push to redeploy.

For project-specific subdomains (e.g., `portfolio` repo), push to `main` and
enable Pages for that repo; GitHub will host it under
`https://<username>.github.io/<repo>/`.

## Next steps

- Wire resume/contact buttons to Calendly, Notion, or mailto links as needed.
- Embed analytics (e.g., Plausible) by dropping their snippet near the end of
  `index.html`.
- Add blog posts or case studies by duplicating the `panel` component with new
  section IDs so navigation picks them up automatically.

