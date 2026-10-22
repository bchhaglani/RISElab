# RISE Lab website

A responsive, dependency-free static website for GitHub Pages. No installation or build step is required. Content remains readable without JavaScript, and all internal links work under a GitHub project subdirectory.

## Preview locally

Run `python3 -m http.server 8000` from this folder, then open http://localhost:8000.

## Publish on GitHub Pages

1. Create a public GitHub repository, for example `rise-lab`. For an organization homepage, use `<organization>.github.io` instead.
2. Upload the **contents of this folder**, including `.nojekyll`, to the repository root on the `main` branch. Do not upload only the ZIP or nest the site in another folder.
3. Open repository Settings → Pages. Under Build and deployment choose **Deploy from a branch**, then `main` and `/ (root)`, and Save.
4. Open the URL GitHub shows when deployment completes. A project site uses `https://<account>.github.io/rise-lab/`; an organization homepage uses `https://<organization>.github.io/`.

## Editing

- `index.html`: homepage and research summaries.
- `research.html`: research directions and project descriptions.
- `people.html`: director biography and future members.
- `join.html`: recruitment information and admissions link.
- `assets/style.css`: colors, spacing, typography, and responsive layout.
- Shared headers/footers are repeated in the four HTML files. Apply navigation changes to all four.

GitHub’s web editor can edit these files directly; commit changes to trigger deployment.

## Content to verify before public launch

- Confirm all research descriptions and the director bio.
- Add the preferred public lab email or faculty profile to the People and Join pages. No email address has been guessed.
- Add the student interest form once its URL is ready.
- Add verified publication citations, paper links, and project links. Unverified publication metadata and unpublished numerical results are intentionally omitted.
- Replace the initials panel with a provided headshot if desired.
- Confirm recruitment wording and funded positions before announcing specific openings.
- Check Penn State’s current branding guidance before adding university marks. This draft uses a text affiliation and a custom wordmark, not an official university logo.

No analytics, tracking, cookies, external fonts, or external scripts are included. No custom domain is configured. There are no runtime dependencies.
