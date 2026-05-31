FUP Tzofia — web font files
============================

Tzofia is a commercial font from FontUp (https://fontup.co.il/fonts/tzofia/).
After purchasing a web license you receive a zip with the web font files.
Drop them into THIS folder (assets/fonts/) using exactly these names:

  tzofia-light.woff2     /  tzofia-light.woff      (weight 300)
  tzofia-regular.woff2   /  tzofia-regular.woff    (weight 400)
  tzofia-medium.woff2    /  tzofia-medium.woff     (weight 500)
  tzofia-semibold.woff2  /  tzofia-semibold.woff   (weight 600)
  tzofia-bold.woff2      /  tzofia-bold.woff        (weight 700)
  tzofia-extrabold.woff2 /  tzofia-extrabold.woff  (weight 800)

The @font-face rules and the --font / --font-display variables in index.html
already point here, so the site will switch to Tzofia automatically once the
files exist. Until then it falls back to Frank Ruhl Libre + Assistant.

If your purchased files have different names, either rename them to match the
list above, or update the @font-face src paths at the top of index.html.
