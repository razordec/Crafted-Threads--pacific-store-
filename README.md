# Crafted Threads sample storefront

A responsive front-end demo for the requested Pacific-inspired product store. Files are separated:

- `index.html` — page structure and navigation
- `styles.css` — responsive visual styling
- `app.js` — sample products, category filtering, quantity controls, cart, and demo checkout interactions

## Run it

Open `index.html` in a modern browser. For local development, serve this folder with a static web server. No build step is required.

## Before launching for real

This is a front-end prototype, not a production commerce backend. Product data, prices, stock, photos, size/color selection, shipping, taxes, order records, and return terms are sample content. Update them with accurate business information. The demo checkout intentionally does **not** collect or process card data.

To accept payments, connect a secure hosted checkout from your chosen payment provider, configure it for your country and business, and implement order creation and verification on a trusted server/backend. Never put secret payment keys in `app.js` or any browser-delivered file. Connect a real inventory/order system, shipping/tax rules, privacy/terms pages, and an email marketing service before launch.

The current sample prices display USD. Change the currency formatter in `app.js` if your store uses another currency. Product imagery is generated with CSS shapes as placeholders; replace with product photographs and appropriate image descriptions.
