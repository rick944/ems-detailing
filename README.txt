EMS Detailing — Bilingual Site (EN/ES) for GitHub Pages
======================================================

Folder structure:
- /index.html        → Language chooser with auto-detect and redirect
- /en/index.html     → English site
- /es/index.html     → Spanish site
- /assets/*          → Logo, icons, CSS

How to publish:
1) Create a new **public** GitHub repository (e.g., ems-detailing-site).
2) Upload all files/folders from this package to the repo root (keep folders).
3) In the repo: Settings → Pages → Source: **Deploy from a branch**; Branch: **main**; Folder: **/(root)**; Save.
4) Test the default URL: https://YOUR-USERNAME.github.io/REPO-NAME/
5) Optional custom domain: Settings → Pages → Custom domain → enter **www.yourdomain.com**. Then in your DNS add **CNAME** for `www` → `YOUR-USERNAME.github.io` and enable **Enforce HTTPS**.

Editing:
- Update prices/services in **/en/index.html** and **/es/index.html**.
- Colors/layout live in **/assets/style.css**.
