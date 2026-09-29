# Ecom Marketplace Tracker

A single-file, client-side work tracker for managing e-commerce marketplace operations (Amazon, Noon, Trendyol, Amazon Vendor) across multiple client brands: tasks, listings, issues, account health, and connection status per marketplace.

## Deploy with GitHub Pages
1. Upload `index.html` and `.nojekyll` to the repo root (see below).
2. Settings → Pages → **Source: Deploy from a branch** → Branch: `main`, folder: `/ (root)` → Save.
3. Live in a minute or two at:
   `https://hassan-stk.github.io/Ecom-Marketplace-Tracker/`

`.nojekyll` stops GitHub Pages from running the file through Jekyll, which isn't needed for a static single-file app and can otherwise interfere with the build.

## Data
Everything is stored locally in the browser (localStorage), nothing is sent to a server. Each browser/device has its own copy. Use **Settings → Export backup** in the app to save your data, and **Import backup** to restore it elsewhere.
