# Yanqi Li — personal academic website

Plain HTML/CSS site for GitHub Pages. No build step.

- `index.html` — all page content
- `style.css` — layout and colors (light and dark mode)
- `files/Yanqi_Li_CV.pdf` — CV, exported from `../CV_Yanqi_Li_academic_v2.docx`

## Updating

- **CV:** re-export the Word CV to `files/Yanqi_Li_CV.pdf` (same name, so the links keep working).
- **Photo:** save as `files/photo.jpg`, then follow the comment above the `YL` circle in `index.html`.
- **Job market paper PDF:** save as `files/Yanqi_Li_JMP.pdf` and replace "Draft available on request" with
  `<a href="files/Yanqi_Li_JMP.pdf">PDF</a>`.
- Change "Last updated" in the footer.

## Publishing (one time)

1. Create a GitHub account, then a public repository named exactly `USERNAME.github.io`.
2. From this folder: `git remote add origin https://github.com/USERNAME/USERNAME.github.io.git`, then
   `git push -u origin main`.
3. On GitHub: Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. The site appears at `https://USERNAME.github.io` within a few minutes.
