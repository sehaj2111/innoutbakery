# In 'N' Out Bakers & Pizza Cafe — Fixed GitHub & Vercel Deployment Package

## What Was Fixed
In the previous archive (`innout-bakers-website.zip`), `index.html` pointed to external files inside an `assets/` folder (`assets/logo.jpg`, `assets/image.jpg`, `assets/hero_opt.mp4`, etc.). Because `assets/` contained over 100 files, GitHub's web uploader either skipped or flattened those files, causing all images and videos on `innoutbakeryasr.vercel.app` to break.

In this fixed package:
- **`index.html` is 100% self-contained** — your official logo, both looping videos (`hero section.mp4` and `bakery.mov`), all 18 custom cake designs, store & hamper photos, and all 80+ Bakery & Pizza Cafe menu images are embedded directly inside `index.html`.
- **Zero external image folders required** — there are only 3 files at the root of this zip (`index.html`, `vercel.json`, `README.md`), so GitHub's file upload limit will never block any asset.

## How to Update Your GitHub Repo & Redeploy on Vercel
1. Unzip `innout-bakers-vercel-fixed.zip` on your computer.
2. Open your GitHub repository (`https://github.com/sehaj2111/innoutbakery`).
3. Click **Add file** -> **Upload files**.
4. Drag and drop **`index.html`** (and **`vercel.json`**) into the upload box so it replaces the old `index.html`.
5. Click the green **Commit changes** button at the bottom.
6. Vercel (`https://innoutbakeryasr.vercel.app`) will automatically detect the commit and redeploy within ~15–30 seconds with every image, logo, and video working properly!
