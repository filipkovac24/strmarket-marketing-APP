# STR Market — Marketing Post Generator

**Android app that turns a product photo into a ready-to-post social media promo in under a minute — built for and used daily by STR Market, a two-location retail business in Serbia.**

📥 **[Download the latest APK →](../../releases/latest)** · 🎬 **[Watch the 90-second demo →](VIDEO_LINK_HERE)** · 🌐 **[strmarket.org](https://strmarket.org/)**

---

## What it does

Store workers — not designers — create the promotional posts. The workflow:

1. **Snap a photo** of any product on the shelf.
2. The app **generates a clean cutout** of the product from the photo.
3. Worker enters the **product name and price**.
4. The app **renders the post**: the cutout and product data are composed into one of dozens of 1080×1080 template designs, drawn entirely in code.
5. **Download to gallery** — ready to upload to Facebook or Instagram.

No design skills, no Canva, no waiting for "the marketing person." The templates guarantee every post looks on-brand regardless of who makes it.

## Screenshots

| Capture & cutout | Template selection | Generated post |
|---|---|---|
| ![Capture](screenshots/01-capture.png) | ![Templates](screenshots/02-templates.png) | ![Result](screenshots/03-result.png) |

*(More in the [screenshots](screenshots/) folder.)*

## Technical highlights

- **C# / .NET MAUI** — single codebase targeting Android.
- **SkiaSharp rendering pipeline** — every template is drawn programmatically at 1080×1080; the app ships **zero static image assets** for the designs. Layouts, typography, and color schemes are all code.
- **Product cutout generation** from worker-taken photos — no studio photography needed.
- **Android MediaStore integration** for saving finished posts directly to the device gallery.
- Designed for non-technical users: the entire flow is tap-through, in the workers' own language.

## Why the source is private

This is production software built for STR Market's internal use, so the source code is not published. This repository distributes the app (see [Releases](../../releases)) and documents it.

Interested in how it's built? I'm happy to walk through the architecture and code in a call — contact below.

## Author

**Filip Kovač** — Computer Science student & developer, Pačir, Serbia
📧 filip.kovac.pacir@gmail.com

---

*Also see my other projects: [GameStore (PHP/MySQL, full source)](GITHUB_GAMESTORE_LINK) · [SwissKnife (.NET MAUI desktop)](GITHUB_SWISSKNIFE_LINK) · [SEF/eFaktura integration architecture](GITHUB_SEF_LINK)*
