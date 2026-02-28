# gentle check-in 🌙

A private, minimal PWA to log moments when you're feeling sad — and track what you've done to feel better.

All data is stored **locally on your device** (localStorage). Nothing is sent anywhere.

---

## Deploy to GitHub Pages

1. **Create a new GitHub repository** (can be private or public — your choice)

2. **Upload all files** from this folder:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `README.md`

3. **Enable GitHub Pages**:
   - Go to your repo → **Settings** → **Pages**
   - Under *Source*, select **Deploy from a branch**
   - Choose **main** branch, **/ (root)** folder
   - Click **Save**

4. Your app will be live at:  
   `https://<your-username>.github.io/<repo-name>/`

---

## Install as a PWA

Once the site is live, open it on your phone browser:
- **iOS (Safari)**: Tap Share → "Add to Home Screen"
- **Android (Chrome)**: Tap the banner or menu → "Add to Home Screen" / "Install app"

This gives you a native-feeling app with offline support.

---

## Features

- 🌙 Tap "I'm sad" to open a journal entry
- ✍️ Write what you've done (or want to do) to feel better
- 📋 All entries saved with date & time, newest first
- 🗑️ Delete individual entries
- 📲 Installable as a PWA (works offline)
- 🔒 Fully private — stored only on your device
