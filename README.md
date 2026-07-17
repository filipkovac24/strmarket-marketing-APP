# STR Market — Marketing Post Generator

**Android app that turns a product photo into a ready-to-post social media promo in under a minute — built for and used daily by STR Market, a two-location retail business in Serbia.**

📥 **[Download the latest APK →](../../releases/latest)** · 🎬 **[Watch the 90-second demo →](
https://github.com/user-attachments/assets/76fc70cf-a8db-4695-8edc-a24af2e8f3a1
)** · 🌐 **[strmarket.org](https://strmarket.org/)**

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
| ![Capture]<img width="1080" height="2400" alt="Screenshot_2026-07-17-07-49-21-334_com market marketing" src="https://github.com/user-attachments/assets/aa9933f3-5b7f-464d-9773-5fb5b80007da" />

 | ![Templates]<img width="1080" height="2400" alt="Screenshot_2026-07-17-07-49-13-602_com market marketing" src="https://github.com/user-attachments/assets/93bdaefb-0527-460a-a844-4f692ee76dd1" />
 
 | ![Result]<img width="1080" height="2400" alt="Screenshot_2026-07-17-07-48-45-321_com market marketing" src="https://github.com/user-attachments/assets/794314a7-f047-492e-888f-dcb5e2df1412" />
 
 

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

Filip Kovacs — Computer Science student & developer, Pačir, Serbia
📧 filip.kovac.pacir@gmail.com




