# DarkServer Icon Pack

Complete professional icon set for **DarkServer**.

## 🌐 Live demo

After enabling GitHub Pages (Settings → Pages → Deploy from branch `main` / root) :

**https://projectx667.github.io/darkserver-icons/**

## Contents (64 files)

| Platform | Files |
|----------|-------|
| **Android** | Adaptive foreground/background + mipmap-mdpi → xxxhdpi + round + Play Store 512 |
| **iOS** | All required sizes (29×29 → 1024×1024) |
| **PWA / Web** | 16→512 + maskable-192/512 + favicon + apple-touch-icon |
| **Splash** | 5 resolutions (phone portrait/landscape + iPad) |
| **Variants** | Debug (red **D** badge) & Staff (blue **S** badge) + adaptive foregrounds |
| **Logo** | Transparent / black / 512 + Open Graph 1200×630 |
| **Source** | Master 1024×1024 flat icon |

## Design

- **Style** : Flat, minimal, dark theme
- **Symbol** : Shield + padlock (security / privacy)
- **Colors** :
  - Background : pure black `#000000`
  - Shield outline : medium gray
  - Lock : pure white
- **Variants** :
  - **Debug** → red circular badge with white **D**
  - **Staff** → blue circular badge with white **S**

## Structure

```
darkserver_icon_pack/
├── android/          # Adaptive + densities + Play Store
├── ios/              # All iOS icon sizes
├── pwa/              # Icons + maskable
├── web/              # Favicons + apple-touch
├── splash/           # Splash screens
├── variants/         # Debug & Staff
├── logo/             # Logos + OG image
└── source/           # Master 1024px
```

## Download

The full ZIP (~5.8 MB) was generated during the icon pipeline.
You can find it in the generation artifacts or request a release upload.

## Usage notes

### Android Adaptive
Use `ic_launcher_foreground.png` + `ic_launcher_background.png`
(or the debug/staff adaptive foregrounds).

### PWA manifest example
```json
{
  "icons": [
    { "src": "/icons/icon-192x192.png", "sizes": "192x192", "type": "image/png" },
    { "src": "/icons/icon-512x512.png", "sizes": "512x512", "type": "image/png" },
    { "src": "/icons/maskable-512x512.png", "sizes": "512x512", "type": "image/png", "purpose": "maskable" }
  ]
}
```

---

Generated for DarkServer • Clean & ready for production
