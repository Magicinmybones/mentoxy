# Mentoxy landing page

Static prototype prepared for Cloudflare Pages. Open `public/index.html` locally or serve the `public/` directory with any static web server. All fonts and images are in `public/assets/`.

The opening composition has a one-time entrance sequence, including the visible cards' titles and data. It stops after the initial load, and users who prefer reduced motion see the page immediately.

The navigation, contact, and call-to-action links are placeholders from the supplied prototype (`href="#"`). Connect them to real destinations when those pages or actions are available.

## Deploy

The `public/` directory is the Pages output directory. For a direct upload, run `npx wrangler pages deploy public --project-name mentoxy --branch main` from this folder. For Git integration, select `public` as the output directory and leave the build command blank.
