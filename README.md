# ANVAROV PARFUM — GitHub Pages

## Publish the website

**Important:** `index.html`, `styles.css`, `app.js`, and the `assets` folder are directly in this project root. Upload the *contents* of this folder to the root of your GitHub repository. Do not upload only the ZIP file, and do not leave the files nested in another `anvarov-parfum/` folder.

1. Download and extract the ZIP.
2. Open your GitHub repository and choose **Add file → Upload files**.
3. Upload `index.html`, `styles.css`, `app.js`, `.nojekyll`, and the full `assets` folder (and the other project files). Commit to branch `main`.
4. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/(root)`, then press **Save**.
5. Wait for deployment to finish. The URL will appear on the Settings → Pages page and usually follows `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

If you choose **GitHub Actions** as the Pages source instead, use the included workflow in `.github/workflows/pages.yml`; do not mix the two deployment methods.

## Included
- 51 catalogue entries, with an embedded fallback if `assets/products.json` cannot load
- Search, brand, gender, fragrance-family, price filters and sorting
- Cart, favourites, gift ideas and scent quiz
- Local scripted FAQ helper (not a connected generative AI service)
- Cash, Uzum, Click and Payme listed as payment options; no direct payment processing
- Store/map links, boutique photos, customer review form, 10 FAQ answers and Instagram embed
- Semantic HTML landmarks and basic keyboard/accessibility helpers

## Important before real sales
- Prices and availability are demo data and must be confirmed.
- The catalogue image URLs are external and are not all verified exact-product photographs. Replace them with verified, licensed packshots before representing them as exact product photos.
- Reviews are saved only in each visitor's browser. Shared reviews require a backend or reviews service.
- Checkout opens a WhatsApp order draft; it does not charge money. Uzum/Click/Payme require merchant accounts and approved payment integration.
- The AI-style assistant is a local FAQ helper. A real generative AI assistant requires a secure backend/API; never put a secret API key in public JavaScript.
- Instagram may block embedded playback in some browsers; the direct link is also provided.
