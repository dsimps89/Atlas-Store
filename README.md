# Atlas Archive - $0 GitHub Pages V1

## Publish
1. Create a GitHub repository.
2. Upload the contents of this folder (not the folder itself).
3. In GitHub: Settings > Pages > Deploy from branch > main / root.
4. Open the Pages URL.

## Change prices / text
Open `/admin/` on the live site or open `admin/index.html` locally. Edit product fields, download `products.js`, then replace `data/products.js` in GitHub and commit.

## Add another atlas
1. Create a protected preview (the admin page has a browser-only preview maker).
2. Put it in `assets/previews/`.
3. Add a product object to `data/products.js` (or duplicate one using GitHub's editor).

## Security model
- NEVER upload print-ready master PDFs to the public repository.
- Only reduced, permanently watermarked previews belong in `assets/previews/`.
- This zero-cost version has no real server/database/admin authentication.
- Orders are created in the browser and sent using the customer's email app.
- E-transfer payment must be manually verified before an order is treated as paid.

## Receipt
Checkout creates a printable receipt. The customer uses the browser's Print command and chooses Save as PDF.

## Version 2 visual upgrade
V2 introduces a redesigned editorial/archival storefront: animated grid hero, poster stack, acid-lime archive identity, responsive asymmetric catalogue, category filters, redesigned cart drawer, ordering explainer, and mobile layouts. No paid service is required for the storefront itself.
