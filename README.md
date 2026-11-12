# Jot & Check

A simple grocery list for iPhone and iPad that works offline.

- **Typed lists**: add items (separate several with commas), tick them off, drag ≡ to reorder. Checked items move to "In the cart".
- **Handwritten lists**: write on lined paper with a finger or Apple Pencil. Tap the box beside a line to tick it off and cross it out.
- **Reuse past lists**: tap ↻ on any list to get a fresh, unchecked copy. Star a list to keep it at the top as your regular list. Items you've typed before show up as one-tap suggestions.
- **Check at a store**: 🔍 next to an item opens Kroger, Walmart, Target or Costco search for it.
- **Backups**: Settings → Save backup / Restore backup (lists are stored only on each device).

## Put it online with GitHub Pages (free)

1. On github.com, click **+ → New repository**. Name it `jot-and-check`, set it to **Public**, and click **Create repository**.
2. On the new repo page, click **uploading an existing file**. Drag in everything from this folder: `index.html`, `sw.js`, `manifest.webmanifest`, `README.md` and the `icons` folder. Click **Commit changes**.
3. Go to **Settings → Pages**. Under "Branch", choose **main** and **/ (root)**, then **Save**.
4. After a minute or two the app is live at `https://YOUR-USERNAME.github.io/jot-and-check/`.

## Install on iPhone / iPad

Open the link in **Safari**, tap **Share** → **Add to Home Screen** → **Add**. Open it from the home screen icon once while online; after that it works without internet.

Tip: always open it from the home screen icon. iOS keeps an installed app's data, but may clear data for sites only visited in Safari.

## Updating

Edit the files, upload them to the repo again, and change `CACHE = 'jotcheck-v1'` in `sw.js` to `v2`, `v3`, and so on. Phones pick up the new version the next time the app is opened online (sometimes it takes two launches).
