# Letters to You 💌

A romantic love letter blog — write sealed letters, lock them with a password, and share them with your special someone.

## Features

- ✉️ **Envelope UI** — click an envelope to open a letter with a wax seal animation
- 🕯️ **Candle header** — flickering candles for a warm, romantic feel
- 🔐 **Password lock** — seal any letter with a password; leave blank for an open letter
- ✍️ **Ink effect** — text types out on screen as if written in real-time
- 💾 **Local storage** — letters are saved in your browser
- ☁️ **Cloud sync** — save/load letters via GitHub API (backup & share between devices)
- 📱 **PWA** — installable as an app on your phone (offline support)

## How to Use

### Write a Letter
1. Tap **"Write a New Letter"**
2. Fill in **To**, **Title**, and your **Letter**
3. Optional: set a **password** to lock it
4. Tap **"Seal & Save Letter"**

### Read a Letter
- Tap any envelope to open it
- If locked, enter the password to break the wax seal and read

### Cloud Sync (share between devices)
1. Get a GitHub token: https://github.com/settings/tokens (enable `repo` scope)
2. Tap **"Save to Cloud"** — enter your token when prompted
3. On another device, tap **"Load from Cloud"**

> Token is saved locally in your browser. You only enter it once.

### Install as an App (PWA)

**Android (Chrome):**
1. Open the site
2. Tap the ⋮ menu → **Add to Home screen**
3. It will open as a full-screen app

**iPhone (Safari):**
1. Tap the Share icon → **Add to Home Screen**

Once installed, it works offline and runs without browser chrome.

## Tech Stack

- Pure HTML/CSS/JS — no frameworks
- GitHub API for cloud sync
- Service Worker for offline PWA support
- Hosted on GitHub Pages

## Links

- **Live site:** https://aloowwwwiamadhi-glitch.github.io/love-letters-pwa/
- **Source repo:** https://github.com/aloowwwwiamadhi-glitch/love-letters-pwa
