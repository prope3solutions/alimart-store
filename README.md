# Alimart

Interactive preview of the Alimart online supermarket web app (sample data only), built by Prope3 Solutions.

Shoppers browse products, fill a cart and place delivery or pickup orders. The store owner manages orders and inventory. The app can be installed from Chrome as a web app.

A static site with no build step and no dependencies:

- `index.html` is the whole app
- `manifest.webmanifest`, `sw.js` and the `icon-*` files make it installable and let it open offline

## Deploy on Vercel

Import this repo at vercel.com/new. Set Framework Preset to **Other**, leave the build command and output directory empty, then deploy. Vercel serves it over https, which Chrome needs for "Install app".

## Edit the store

Store name, delivery fee, free-delivery amount and delivery areas are in the `CFG` block near the top of the script in `index.html`. Products and sample orders are the lists just below it.
