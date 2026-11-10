# Joseph J. Hay — Cloudflare Pages website

A responsive, static HTML/CSS/JavaScript reconstruction based on the published website and supplied screenshot.

## Files

- `index.html` — page structure and copy
- `styles.css` — responsive editorial styling
- `script.js` — mobile navigation and copyright year
- `assets/` — place the final book cover images here

## Book cover assets

Add authorized cover artwork with these exact filenames:

- `assets/true-middle.jpg`
- `assets/emotional-equity.jpg`
- `assets/space-between-us.jpg`

The original image assets were not available as downloadable source files in this reconstruction, so the cover locations are placeholders until you add the real artwork.

## Before launch

1. Replace each `#amazon-*` placeholder URL in `index.html` with the appropriate Amazon author/book URL.
2. Confirm author biography and reader-review section content.
3. Add a favicon and social-sharing image if desired.
4. Test the site at mobile and desktop sizes.

## Deploy to Cloudflare Pages

### Direct upload

1. Sign in to Cloudflare.
2. Open **Workers & Pages** and create a Pages project.
3. Choose **Direct Upload**.
4. Upload the contents of this folder (the `index.html` file must be at the root).
5. After the first deployment, open the project's **Custom domains** section and add your domain.
6. Follow Cloudflare's DNS setup instructions. If the domain is already on Cloudflare DNS, the required records can generally be added there.

### Git-based deployment (recommended for ongoing changes)

1. Commit this folder to a GitHub repository.
2. In Cloudflare Pages, create a project connected to that repository.
3. Set the build command to blank / none for a plain static site.
4. Set the build output directory to the repository root (`/` or the project root, depending on the setup UI).
5. Add your custom domain in the Pages project.

No server-side runtime, package manager, or build step is required.
