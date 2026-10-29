# cvwebpage

Source of my portfolio site, published with GitHub Pages at
[abelmamo.github.io/cvwebpage](https://abelmamo.github.io/cvwebpage/).

It is a single static page (`index.html`, no build step) with the images in
`assets/`. Every number on the page comes from the `results/` folders in
[computer-vision-projects](https://github.com/abelmamo/computer-vision-projects).
The before/after image at the top is a held-out test image from the nucleus
segmentation project, run through the trained model.

Pushing to `main` redeploys the site through `.github/workflows/static.yml`.
