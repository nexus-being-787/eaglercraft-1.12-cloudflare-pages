# 🎮 Eaglercraft 1.12.2 — Cloudflare Pages & Standalone Web Client

Private & Optimized Minecraft 1.12.2 Web Client edition designed for fast browser play, high FPS, and seamless Cloudflare Pages deployment.

---

## ✨ Features
- **Cloudflare Pages Ready**: Includes `_headers` for optimized caching of `assets.epk` and `classes.js`.
- **Standalone Offline Edition**: Includes `1.12.html` (all-in-one single HTML file playable locally or hosted anywhere).
- **Custom Shaders & Resource Packs**:
  - `Ultra_64x_DarkGUI_Pack.zip`
  - `Crystal_PvP_FPS_Boost.zip`
  - `Golden_Sunset_Shader.zip`
- **Mobile & Desktop Controls**: Built-in touch support and keyboard/mouse compatibility.

---

## 🚀 Deployment to Cloudflare Pages

1. Fork or push this repository to your GitHub account.
2. In the [Cloudflare Dashboard](https://dash.cloudflare.com/), go to **Workers & Pages** → **Create application** → **Pages**.
3. Select **Connect to Git** and choose this repository (`eaglercraft-1.12-cloudflare-pages`).
4. Set build settings:
   - **Framework preset**: `None`
   - **Build command**: *(leave empty)*
   - **Build output directory**: `/`
5. Click **Save and Deploy**!

---

## 📁 Repository Structure
```text
├── index.html          # Main web client entrance
├── 1.12.html           # Standalone single-file HTML edition
├── classes.js          # Compiled client engine
├── assets.epk          # Game assets bundle
├── _headers            # Cloudflare HTTP caching rules
└── resourcepacks/      # Included HD & shader packs
```
