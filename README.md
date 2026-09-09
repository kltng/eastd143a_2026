# eastd143a_2026

Personal landing page — a single static `index.html`, no build step and no
dependencies beyond Google Fonts.

Styled after 1980s Kowloon at night: neon tube type, a vertical sign on a
bracket arm, rain over the hero, and an enamel nameplate in the footer.

## Served at

<https://kltng.github.io/eastd143a_2026/>

## Editing

Everything is in `index.html`. The design tokens (colours, type scale, fonts)
are the `:root` block at the top of the `<style>`. Content lives in the markup
below it.

Lines still needing real content are marked `TODO`:

```sh
grep -n TODO index.html
```

`.nojekyll` stops GitHub Pages running the file through Jekyll.
