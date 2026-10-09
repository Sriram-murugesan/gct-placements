# GCT Placements

A static page celebrating students placed at leading organisations. Deployed on Vercel.

## Structure

```
index.html              The page (styles and slider script are inline)
assets/students/        Student photos (480×600 JPG, 4:5 crop)
assets/logos/           Company logos (SVG)
vercel.json             Vercel config (clean URLs, asset caching)
```

## Adding a student

1. Add a 480×600 photo to `assets/students/`.
2. Add the company logo to `assets/logos/` if it isn't already there.
3. In `index.html`, copy one `<article class="pod">…</article>` block and update the photo, stipend/package, name, role, department, logo and message.

The mobile slider picks up new cards automatically.

## Deploying

Import this repository in Vercel (Framework preset: **Other**, no build command, output directory: root). Every push to `main` redeploys.
