# 结婚纪念日网站 · Anniversary Website

A gift site for 张伟 (Wei) & 许荔松 (Lisong). All in Chinese. 44 photos in five sections:
一 最初的你们 · 二 我们一家 · 三 你们俩 · 四 一起出发 · 五 我们走过的地方 (interactive map)

## Files — ALL at the repo ROOT (no subfolders)
```
index.html        <- the website
.nojekyll
photo-01.jpg ... photo-44.jpg
```
Keep everything together in one folder. The map uses Leaflet + OpenStreetMap/CARTO
(loaded from a CDN, no API key needed) and works on GitHub Pages out of the box.

## Run locally / publish
- Local:  python3 -m http.server 8000   (open http://localhost:8000)
- GitHub Pages: upload all files to repo root -> Settings > Pages >
  Deploy from a branch > main / root. Live at https://<user>.github.io/<repo>/

## Map locations (click a pin -> click a photo to enlarge)
Mount Rushmore SD · Hollywood LA · Universal Studios LA · Rocky Mountains CO ·
Gatlinburg TN · Great Smoky Mountains (5 photos) · Chicago IL (2) ·
Jackson Hole WY · Lincoln NE (state capitol selfie)

## Editing
- Names: search 修改名字 (张伟 / 许荔松); Sign-off: search 修改落款
- Remove a photo: delete its <figure>...</figure> line (hospital photos = photo-31, photo-32)
- Map pins/coordinates: edit the PLACES list near the bottom of index.html
