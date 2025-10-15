# KIN1 — Lucida Sans Dark Portfolio (4 pages)

Nav: **about / work / sketch / mail**. Uses Lucida Sans (web-safe stack).  
Image blocks are **flat color frames** ready to be replaced with JPG/PNG/GIF files.

## Replace color frames with your media
- In `work.html` and `sketch.html`, swap a `<div class="frame"></div>` with an image element, e.g.
  ```html
  <img src="assets/project-1.gif" alt="Project 1">
  ```
- GIFs work the same as JPG/PNG on GitHub Pages.

## Publish on GitHub Pages
1. Create a public repo named `USERNAME.github.io`.
2. Upload all files in this folder to the repo root.
3. Repo → Settings → Pages → Build from **Branch: main / Folder: /(root)** → Save.
4. Done. Add a `CNAME` file if you want a custom domain.

## Customize
- Colors and typography in `style.css` (magenta-on-black aesthetic).
- Edit text in `about.html`, `work.html`, `sketch.html`, `mail.html`.
