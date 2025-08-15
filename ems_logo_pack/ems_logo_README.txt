EMS Detailing — Logo Asset Pack
================================
Source file: ems_detailing_logo.png (1411.4 KB)

Optimized outputs:
- ems_logo_web_512.png (140.0 KB)
- ems_logo_web_512.webp (104.1 KB)  <-- recommended for modern browsers
- favicon-512.png (140.0 KB)
- favicon-192.png (23.4 KB)
- favicon-32.png (1.7 KB)
- favicon.ico (5.4 KB)

HTML usage
----------
Place these files in the same folder as your index.html (GitHub Pages repo root). Add this in <head>:

<link rel="icon" type="image/png" sizes="32x32" href="favicon-32.png">
<link rel="icon" type="image/png" sizes="192x192" href="favicon-192.png">
<link rel="apple-touch-icon" href="favicon-192.png">
<link rel="icon" href="favicon.ico">

Use the optimized header logo (PNG):
  <img class="mark" src="ems_logo_web_512.png" alt="EMS Detailing logo">

Or, prefer WebP:
  <picture>
    <source srcset="ems_logo_web_512.webp" type="image/webp">
    <img class="mark" src="ems_logo_web_512.png" alt="EMS Detailing logo">
  </picture>