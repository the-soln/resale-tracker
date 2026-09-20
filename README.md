# Resale Tracker

Inventory, profit and funds tracker for resellers. Runs entirely on your device; nothing is sent to a server except optional barcode lookups.

## Files

- `index.html` - the whole app
- `manifest.webmanifest`, `sw.js`, `icon-*.png` - what makes it installable on a phone and usable offline

## Use on a computer

Double-click `index.html`. Everything works except the camera scanner (browsers only allow the camera on a real web address). You can still type barcodes.

## Install on your phone

Phones only allow "Add to Home Screen" apps and camera access from an `https://` address, so this folder has to be hosted. Free options that take a few minutes:

### Option A: GitHub Pages (free, permanent)
1. Create a free account at github.com and click **New repository**. Name it `resale-tracker`, keep it **Public**, click **Create**.
2. Click **uploading an existing file**, drag every file in this folder in, click **Commit changes**.
3. Go to **Settings > Pages**. Under **Branch** choose `main` and `/ (root)`, click **Save**.
4. After a minute your app is at `https://YOURNAME.github.io/resale-tracker/`.

### Option B: Netlify Drop (free)
1. Go to app.netlify.com/drop and sign in (free).
2. Drag this whole folder onto the page. You get an `https://something.netlify.app` address immediately.

### Then, on your phone
- **Android (Chrome):** open the address, tap the **Install app** banner, or the menu (three dots) > **Install app**.
- **iPhone (Safari):** open the address, tap **Share**, then **Add to Home Screen**.

The app icon now opens full-screen, works offline, and can use the camera to scan barcodes (allow camera access when asked).

## Your data

Data is stored in the browser you use it in. Each address (computer file, phone app) has its own copy. To move data: **Backup** on one, then **Restore** on the other. Do a Backup now and then; it is a small file you can keep anywhere.

## Updating the app

Upload the new files to the same place. Open the app twice (the second open picks up the update).
