# 312Gitupload

Upload the **contents of this folder** to your GitHub repository root.

## GitHub Pages setting
- Source: Deploy from a branch
- Branch: your publish branch (usually `main`)
- Folder: `/ (root)`

## Entry
- `index.html` at repository root

## Asset map
- `assets/logo/unishare-logo.svg`
- `assets/images/press/press-01.png` ... `press-20.png`
- `assets/images/release/release-01.png` ... `release-07.png`

All image paths in `index.html` are package-local (`./assets/...`) and do not use `../` parent traversal.
