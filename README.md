# Rajeev Cosmetics Store — Website

## What's in this folder
- `index.html` — the whole website (structure, styling, and all interactive features in one file)
- `images/` — placeholder graphics for the storefront photo and product cards (swap these for real photos any time — just keep the same file names, e.g. `product-1.png`)

## Put this live on GitHub Pages (free hosting)

1. Go to https://github.com and log in (or create a free account).
2. Click the **+** icon top-right → **New repository**.
   - Name it anything, e.g. `rajeev-cosmetics-store`.
   - Set it to **Public**.
   - Click **Create repository**.
3. On the new repo page, click **uploading an existing file**.
4. Drag in `index.html` and the whole `images` folder (keep the folder structure — `images/` must stay a folder, not loose files).
5. Scroll down and click **Commit changes**.
6. Go to the repo's **Settings** tab → **Pages** (left sidebar).
7. Under **Build and deployment → Source**, choose **Deploy from a branch**.
8. Under **Branch**, choose `main` and folder `/ (root)`, then **Save**.
9. Wait 1–2 minutes, then refresh the Pages settings screen — it will show your live link, something like:
   `https://<your-username>.github.io/rajeev-cosmetics-store/`

That link is your live website. Every time you upload a new `index.html` (or new images) to the same repo, the live site updates automatically within a minute or two.

## Before you share the link
- Replace the images in `images/` with real photos of your shop and products (same file names).
- Update the placeholder store hours in the "Visit or message us" section of `index.html`.
- Update the Shipping/Returns/Refund text in the footer with your actual policies.

## What still needs a real backend (not possible with GitHub Pages alone)
GitHub Pages only hosts static files — it can't run a server. That means:
- Real payment gateways (UPI/card checkout) and live order tracking need a platform like Shopify/WooCommerce, or a custom backend.
- The newsletter signup form is visual only until it's connected to a real WhatsApp/SMS/email service.

Everything else — the product catalog, filters, live bill calculator, WhatsApp ordering, store status badge, and appointment booking — works as-is on GitHub Pages, since it all runs in the visitor's browser.
