# SETS — School of Emerging Technologies & Systems

Static one-page website for **SETS (School of Emerging Technologies & Systems)**, a NASTP institution under **Air University**. Intended to be published at **https://sets.au.edu.pk**.

The page follows the official Air University visual theme (Playfair Display + Plus Jakarta Sans typography; navy `#081933` + gold `#c5a93c` palette).

## Contents

```
index.html          The complete single-page site (self-contained: inline CSS + JS)
assets/
  sets-logo.png     SETS crest
  img/              AI-generated illustrations for Core Tasks and Research Centres
```

## How to publish (for the Air University web team)

The site is plain static HTML — **no build step, no server-side code, no dependencies**.

1. Copy `index.html` and the entire `assets/` folder to the document root that serves `sets.au.edu.pk`.
2. Point the `sets.au.edu.pk` sub-domain at that document root (DNS record + vhost).
3. Fonts load from Google Fonts and the Air University crest loads from `www.au.edu.pk`; everything else (styles, scripts, SETS logo, illustrations) is bundled locally.

That's it — opening `index.html` in any browser shows the finished page.

## Editing content

All text lives directly in `index.html` in clearly-labelled sections:
`Hero`, `About / Role`, `Vision / Mission`, `Core Tasks`, `Research Centres (ARICS)`, `Contact`, `Footer`.
Colours and fonts are defined once as CSS variables in the `:root` block at the top of the `<style>` tag.

## Contact

SETS — School of Emerging Technologies & Systems · **sets@au.edu.pk** · An Air University / NASTP institution.
