PANTRY - HOME GROCERY MANAGER
=============================

Put it on GitHub Pages (works from a Windows computer)

1. On github.com create a new PUBLIC repository (for example "pantry").
2. Click "uploading an existing file".
3. Drag everything that is INSIDE this folder onto the page:
   index.html, catalog.js, manifest.webmanifest, sw.js and the icons folder.
   The files must be at the top level of the repository.
4. Click "Commit changes".
5. Settings > Pages > Source: "Deploy from a branch" > Branch: main, folder: / (root) > Save.
6. After 1 to 2 minutes your address appears, like https://YOURNAME.github.io/pantry/
7. Open it in Safari on your iPhone > Share > Add to Home Screen.

Updating later: upload the changed files to the same repository and commit. Then
open the app twice (the first open downloads the update, the second shows it).

How the app works

- Home: search, Add item, Scan bill, the four counters (Items, Running low,
  Use soon, Out of stock) and 26 category tiles. Tap a counter to see those items.
- Tap a category to see EVERY product in it (from the catalog), grouped by
  subcategory. Tap + to put a product in your pantry, or tap the product for details.
- Pantry: only what you have at home, with filters.
- Buy List: finished and running-low items are added automatically, no duplicates.
  Tick an item to record the purchase (quantity, price, store, expiry).
- Prices: latest, lowest, highest and average price, plus purchase history.
- Settings: expiry warning days, language (English / Tamil names first),
  currency, your own products, backup and restore.

Files

- index.html            the app
- catalog.js            the master catalog (26 categories, 401 products, Tamil names, aliases)
- manifest.webmanifest  app name and icon settings
- sw.js                 makes the app open without internet
- icons/                Home Screen icons

Notes

- Your data is saved only on your phone. Use Settings > Download backup now and then.
- The Home Screen app keeps its own data, separate from the Safari tab.
- Bill scanning needs internet (it downloads a reader the first time you use it).
- Items saved by the earlier version of this app are moved over automatically.
