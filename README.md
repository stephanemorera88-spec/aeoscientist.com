# aeoscientist.com

Static site, no build step. The public lab log of Stephane Morera, AEO scientist. GitHub Pages serves this repository at https://aeoscientist.com/.

This site is stack piece 5 of EVOIX aeo-lab EXP-028 (the "world's top AEO scientist" title). Every lab log entry is drawn from its EXP file and goes through the fact-checker before it is published.

## Edit and deploy
1. Change `index.html` or `lab/index.html`.
2. Update `dateModified` in the JSON-LD, the "Updated" kicker on the lab page, and `lastmod` in `sitemap.xml`.
3. Push to `main`. Pages rebuilds in about a minute.

`rates/index.html` is generated. Do not edit it by hand. It is built from the saved run files by `scripts/aeo_rates_page.py` in the EVOIX lab repository, rebuilt after each read, and fact-checked before it is pushed. Update its `lastmod` in `sitemap.xml` when it changes.

Maintainer: Stephane Morera, EVOIX, DeLand, Florida.
