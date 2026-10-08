# Mesh-Sync — Calm coordination when networks fail

> A privacy-minded, offline-first disaster response coordination prototype built for **Hacknext 2.0**.

## 🚀 Live Demo

🔗 [https://meshsync-ggqc32v3.manus.space/](https://meshsync-ggqc32v3.manus.space/)

## 📌 About

**Mesh-Sync** is a local-first disaster response coordination tool. It is designed to work even when traditional networks fail, using offline-first architecture and mesh-style data propagation.

Key features:
- 🗺️ **Location Intelligence** — real-time map with survivor and responder tracking
- 📡 **Offline-first** — works without internet connectivity
- 🔒 **Privacy-minded** — no persistent cloud data storage
- 🚨 **Disaster response coordination** — designed for emergency scenarios

## 🛠️ Tech Stack

- **Frontend**: React + Vite
- **Mapping**: CartoDB basemaps
- **PWA**: Web App Manifest + Service Worker
- **Deployment**: Manus Space

## 📁 Project Structure

```
meshsync-site/
├── index.html              # Main HTML entry point
├── manifest.webmanifest    # PWA manifest
├── mesh-sync-mark.svg      # App icon
└── assets/
    ├── index-D_yEIiUh.js   # Compiled React application bundle
    └── index-Dptv4OSO.css  # Compiled styles
```

## 🏃 Running Locally

You can serve this site with any static file server:

```bash
# Using npx serve
npx serve meshsync-site

# Using Python
python -m http.server 3000 -d meshsync-site
```

Then open [http://localhost:3000](http://localhost:3000)

## 🏆 Hacknext 2.0

Built for the **Hacknext 2.0** hackathon.
