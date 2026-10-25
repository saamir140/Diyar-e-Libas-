# Diyar-e-Libas CRO Prototype V7

This is the mobile-header layout fix for the existing CRO prototype. It preserves the current supplier-provided testing content and images.

## Preview locally
1. Extract the ZIP.
2. Open `diyar_libas_v3/index.html` in a browser.

## Update the existing GitHub repository
Upload the extracted files and replace matching files, including `css/style.css`. Commit the changes and let Vercel redeploy.

## What's fixed
- Mobile header uses a compact grid so the wordmark, menu and collection CTA don't overlap.
- The tagline is hidden on narrow screens to preserve room for navigation.
- Very narrow phones use an icon-only menu label while keeping the menu button accessible by its existing control.
- Existing desktop styles and product assets are retained.

This remains a front-end prototype; checkout/order recording and tracking must be connected and tested before taking live orders.


TESTING NOTE: For this prototype, the former Bilal Fabrics / Wash & Wear image assets (collection1_01.webp through collection1_08.webp) have been replaced with the seven supplier-provided Legend/printed fabric images. Product names and prices remain unchanged for layout testing only; the imagery is temporary and should not be treated as proof of product variant compatibility.
