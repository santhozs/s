# SADA — Portfolio

Single-page portfolio for SADA (Strategy Manager & Graphic Designer, Coimbatore, India).
The whole site is one self-contained `index.html` (images and video are embedded), so there is no build step.

## Publish with GitHub Pages
1. Create a new repository on GitHub (for example `sada-portfolio`).
2. Upload the files from this zip to the repository root: `index.html`, `.nojekyll`, `README.md`, `robots.txt`.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Edit content
Open `index.html` in a text editor and search for:
- `const PR=[` — case studies (add a project by copying one object; fields are listed in the comment above it)
- `const MORE=[` — "More works" cards
- `const ART=[` — Insights articles (empty until you add some)
- `const EXP=[` — experience timeline and resume view

## Before sharing publicly
- Confirm you are allowed to show every client screenshot (for example the BFSI hiring tracker).
- Replace placeholder items (dashed boxes starting with `[`) with verified details.
- To offer a real resume download, upload a PDF to the repository and link to it from the resume buttons.
- Optional: once you have your final URL, add a `<link rel="canonical" href="...">` and `og:url`/`og:image` tags in the `<head>`.
