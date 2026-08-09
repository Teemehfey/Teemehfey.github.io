# Wostok Energy Trading Co., Ltd — website (built files)

This repository contains the **built** static site for wostokenergy.com,
served via GitHub Pages. `index.html` is the entry point.

Do not edit these files by hand. The source project lives in
`Wostok_Energy_Website/wostok-site/` on the office Mac; to update the site,
edit the source there, run `npm run build`, and replace the contents of this
repository with the new `dist/` output (keeping the `.nojekyll` file).

`.nojekyll` is required: without it GitHub Pages ignores the `_astro/` folder
(any folder starting with an underscore) and the site loses its styles.
