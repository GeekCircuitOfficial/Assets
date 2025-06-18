# 📦 Geek Circuit – Public Asset Repository

Welcome to the **official CDN-powered asset hub** of [Geek Circuit](https://geekcircuit.com) — serving optimized brand and UI assets across all platforms.

All files are delivered via **[assets.geekcircuit.com](https://assets.geekcircuit.com)** for fast, reliable, and versioned usage.

---

## 📁 Directory Structure

| Folder / Path                                      | Description                                     |
|---------------------------------------------------|-------------------------------------------------|
| `/img/logo/svg/`                                  | Standard logos (scalable SVG)                  |
| `/img/logo/webp/`                                 | Retina (`@2x`) logos in WebP format            |
| `/img/logo/avif/`                                 | Retina (`@2x`) logos in AVIF format            |
| `/img/logo/png/`                                  | Retina (`@2x`) logos in PNG format             |
| `/img/favicon/favicon.ico`                        | `.ico` favicon for legacy browser support      |
| `/img/favicon/favicon.png`                        | PNG favicon (32×32)                            |
| `/img/favicon/favicon.svg`                        | Scalable favicon (modern browsers)             |

---

## 🖼️ Logo Usage (Auto Retina + Format Fallback)

### ✅ Standard SVG (Preferred)

```html
<img src="https://assets.geekcircuit.com/img/logo/svg/light.svg" alt="Geek Circuit Logo" height="40">
```
### 💡 Retina-Optimized with <picture>
```html
<picture>
  <source srcset="https://assets.geekcircuit.com/img/logo/avif/light@2x.avif" type="image/avif">
  <source srcset="https://assets.geekcircuit.com/img/logo/webp/light@2x.webp" type="image/webp">
  <source srcset="https://assets.geekcircuit.com/img/logo/png/light@2x.png" type="image/png">
  <img src="https://assets.geekcircuit.com/img/logo/svg/light.svg" alt="Geek Circuit Logo" height="40">
</picture>
```

>  🔁 Replace light with dark for dark mode version.

## 🌐 Favicon Integration
```html
<!-- Modern browsers -->
<link rel="icon" type="image/svg+xml" href="https://assets.geekcircuit.com/img/favicon/favicon.svg">

<!-- PNG fallback -->
<link rel="icon" type="image/png" href="https://assets.geekcircuit.com/img/favicon/favicon.png">

<!-- Legacy support -->
<link rel="shortcut icon" href="https://assets.geekcircuit.com/img/favicon/favicon.ico">
```

## 🎨 Brand Colors
| Name           | Hex       | Usage                           |
|----------------|-----------|----------------------------------|
| Deep Navy      | `#0E2148` | Primary brand base              |
| Violet Blue    | `#483AA0` | Links, highlights               |
| Soft Lavender  | `#7965C1` | Secondary elements              |
| Soft Gold      | `#E3D095` | High-contrast accents (dark)    |

## ✅ Do’s and ❌ Don’ts
### ✅ Do

   - Use logos directly from https://assets.geekcircuit.com

- Prefer SVG for clean scaling and fast loading

- Use `@2x` AVIF/WebP/PNG logos on retina displays

- Match light/dark logo with your site’s theme

- Maintain minimum clear space around the logo

- Use `?v=1.0` or higher for cache busting

### ❌ Don’t

-    ❌ Modify, recolor, or crop logos

-    ❌ Stretch, squash, or distort proportions

-    ❌ Overlay logos on noisy or low-contrast backgrounds

-    ❌ Add filters, shadows, or outlines

-    ❌ Use old or unapproved versions

## 🛠 Asset Format Guidelines
| **Context**           | **Recommended Format**                                      |
|------------------------|-------------------------------------------------------------|
| Standard logo          | SVG                                                         |
| Retina displays        | AVIF `@2x` → WebP `@2x` → PNG `@2x` fallback                      |
| Favicon                | SVG → PNG → ICO                                             |
| Screenshots/images     | WebP or AVIF                                                |

## 📜 License & Attribution

Copyright © 2025 Geek Circuit. All Rights Reserved.
They are intended for official Geek Circuit properties unless explicit permission is granted.

For media kits, partnership inquiries, or extended use:

📩 support@geekcircuit.com
## 🌐 About Geek Circuit

Geek Circuit is a modern tech blog and creative hub, focused on:

-    💡 In-depth tutorials & how-tos
-    🔧 Hardware/software hacks
-    💻 Open-source builds & experiments