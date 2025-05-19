# Clue Score Sheet 🕵️‍♀️

A sleek, installable Progressive Web App (PWA) for tracking your **Clue®** game progress. Designed to feel like a native app on desktop and mobile — even works offline.

![screenshot](./icon-192.png)

---

## 🚀 Live App

🔗 [Launch the app](https://ybarrap.github.io/clue-scorecard/)

---

## 🧩 Features

- ✅ Fully responsive scorecard for **Suspects, Weapons, and Rooms**
- ✅ Editable cells with **localStorage persistence**
- ✅ Works **offline** after first load (PWA powered)
- ✅ “**Install App**” prompt for supported browsers (Chrome, Edge, etc.)
- ✅ Manual install instructions for iOS Safari
- ✅ **Reset All Notes** button with confirmation
- ✅ Version display and auto-increment support

---

## 🗂 Files Overview

| File               | Purpose                                      |
|--------------------|----------------------------------------------|
| `index.html`       | Main app UI & logic                          |
| `manifest.json`    | PWA manifest (defines app behavior/icons)    |
| `service-worker.js`| Caches app for offline use                   |
| `icon-192.png`     | App icon (home screen, PWA install)          |
| `icon-512.png`     | Larger icon for splash screens, desktop use  |

---

## 📲 How to Install (User Instructions)

### Chrome / Edge / Android
- Visit the app link
- Click **“Install App”** when prompted, or use menu > “Install”

### iOS Safari
- Tap the **Share icon** (🧭)
- Select **“Add to Home Screen”**

---

## 🧪 Developer Notes

- Built using vanilla HTML, CSS, and JS
- Version tracked in UI (`index.html`)
- PWA cache version set in `service-worker.js` (`clue-sheet-cache-v1.0.1`)
- Changes may not appear immediately due to PWA caching — use `Cmd+Shift+R` to bypass cache or update the cache name

---

## 🛠 To Deploy Updates

1. Update files as needed
2. Bump version in `index.html` and `service-worker.js`
3. Commit and push to GitHub
4. GitHub Pages auto-serves updated files at:
