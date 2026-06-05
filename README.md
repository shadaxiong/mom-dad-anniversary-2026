# 结婚纪念日网站 · Anniversary Website

A gift site for 张伟 (Wei) & 许荔松 (Lisong). Everything is in Chinese.

## Files — ALL at the repo ROOT (no subfolders)
```
index.html        <- the website
.nojekyll         <- lets GitHub Pages serve files as-is
photo-01.jpg ... photo-20.jpg   <- the 20 photos, next to index.html
```
`index.html` links to each photo by its plain lowercase name (e.g. `photo-03.jpg`).
Keep every file together in the same place and the images will load.

## Photo order (which upload became which file)
photo-01 family Christmas · 02 Mount Rushmore · 03 lake family · 04 Hollywood ·
05 snowy yard · 06 Universal Studios · 07 state fair · 08 mom on the counter ·
09 dad cooking · 10 lookout tower · 11 lake family · 12 Christmas (Santa hats) ·
13 family on couch · 14 ice cream · 15 snowy lake · 16 mountain selfie ·
17 gondola · 18 misty stairs · 19 the kiss · 20 by the stream

## See it locally
Double-click `index.html`, or:
```bash
python3 -m http.server 8000   # open http://localhost:8000
```

## GitHub Pages
1. Put `index.html`, `.nojekyll`, and all 20 `photo-*.jpg` at the TOP LEVEL of your repo.
2. Settings -> Pages -> Source: Deploy from a branch -> Branch: main / root -> Save.
3. Live at: https://<username>.github.io/<repo>/
4. If images don't show after editing, hard-refresh (Ctrl/Cmd+Shift+R).

## Editing
- Names: search `修改名字` (张伟 / 许荔松).
- Sign-off: search `修改落款`.
- Captions: each photo's `<figcaption>`.
