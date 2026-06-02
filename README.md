# HyperVault Professional Investor Website

This folder is ready to upload to GitHub Pages.

## What is included

- `index.html` - investor-facing landing page with animations, visual sections, deck gallery, and contact form.
- `assets/slides/` - high-quality slide images rendered from the attached HyperVault deck.
- `assets/thumbs/` - optimized thumbnail images for fast page loading.
- `assets/docs/HyperVault_Investor_Deck.pdf` - downloadable investor deck.
- `assets/docs/HyperVault_Problems_Gaps_Solutions.pdf` - optional deep-dive PDF.
- `.nojekyll` - keeps GitHub Pages from changing asset handling.

## Important: update contact email

Open `index.html` and find this line near the bottom:

```js
const CONTACT_EMAIL = "info@askiplex.com";
```

Replace it with your real investor contact email before publishing.

The form works on GitHub Pages without backend hosting. When a visitor submits the form, it opens their default email client with a pre-filled investor inquiry.

## Upload to GitHub Pages

1. Create a public GitHub repository, for example `hypervault-investor-site`.
2. Upload the extracted files and folders from this package. Do not upload only the ZIP.
3. Go to repository `Settings` -> `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select branch `main` and folder `/root`.
6. Save.
7. Your public link will look like:

```text
https://YOUR-GITHUB-USERNAME.github.io/hypervault-investor-site/
```

## Editing the page

Most website content is inside `index.html`. You can edit the text directly and replace images in `assets/slides/` if the investor deck changes.
