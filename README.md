# AuraSplat Project Page

A bilingual project page for **AuraSplat: Image-Conditioned Appearance Transfer for Driving Scenes via Feed-Forward Gaussians**.

This repository contains a static website and its visual assets. It does not require a build step. The paper PDF and source code are not currently linked from the page.

## Local preview

From this directory, start a local web server:

```bash
python3 -m http.server 8011
```

Open <http://localhost:8011/> for the English page or <http://localhost:8011/index-zh.html> for the Chinese page.

## Files

- `index.html` and `index-zh.html` — English and Chinese pages
- `styles.css` — shared styles
- `site.js` and `media.js` — shared interactions and media configuration
- `logo.jpg.png` — project page logo
- `assets/figures/` and `assets/videos/` — figures, videos, and posters

## GitHub Pages

Publish the repository's root directory from the default branch using **Settings → Pages → Deploy from a branch**. For a project repository, the site is served at `https://<owner>.github.io/<repository>/`; the Chinese page is at `https://<owner>.github.io/<repository>/index-zh.html`.

Before publishing, verify the author information and that the paper content and all figures, videos, and logos are cleared for public release. When the paper and code URLs are available, update both HTML pages.

The project demonstration video is currently a placeholder. When the video is ready, add it under `assets/videos/` and update the `hero` entry in `media.js` as described in the comments there; both language pages will use it.
