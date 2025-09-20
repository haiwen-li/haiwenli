# Personal Website

Chic, minimal static site with a white background and simple top navigation.

## Local preview

Open `index.html` directly, or serve the folder:

```bash
# Python 3
python3 -m http.server 5173
# or Node
npx serve --listen 5173 --single --yes
```

Visit `http://localhost:5173`.

## Structure

- `index.html` — Home
- `projects.html` — Projects
- `publications.html` — Publications
- `cv.html` — CV
- `contact.html` — Contact
- `styles.css` — Shared styles
- `assets/` — Images and icons (replace `og-image.png`, `favicon.svg` as desired)

## Deploy

Any static host: GitHub Pages, Netlify, Vercel, Cloudflare Pages.

- GitHub Pages: push to a repo, enable Pages for main branch/root.
- Netlify/Vercel: connect repo or drag-drop. Build: none. Output: `/`.

## Customize

- Update name, bio, and email in all pages.
- Replace placeholders in Projects/Publications.
- Add `assets/Haiwen-Li-CV.pdf` and update link in `cv.html`.
