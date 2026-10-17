# Toaru Visual References

[Browse the reference library](https://lulu0119.github.io/toaru-visual-references/)

An unofficial visual research index for *A Certain Magical Index*, *A Certain Scientific Railgun*, and Academy City. Collected on 2026-10-17.

The library contains 2,873 unique downloaded images, with 250 manually selected references related to screens, devices, signage, research environments, and magical graphics. The full collection also includes character shots and illustrations; it is not an official UI design specification.

## Sources

- 1,144 official stills and world-setting images
- 902 animation frames reproduced in commentary pages
- 399 creator design sheets and illustrations
- 428 animation/location comparison images

Every image links to its source page. `sources.csv` and `manifest.json` preserve source URLs, dimensions, and file hashes. Identical file hashes were deduplicated; alternate crops or encodings may remain.

All original images belong to their respective rights holders. This index does not grant a license to reuse third-party images, and it is not affiliated with the franchise or its production companies. Consult the linked original sources for attribution and usage terms.

## Static site

`index.html` contains the gallery, search, filters, pagination, and full-size viewer. `images/` stores originals and `_thumbnails/` stores browsing previews. All site resources use relative paths and work under the GitHub Pages project URL.

GitHub Pages publishes the root of the `main` branch. `.nojekyll` ensures the thumbnail directory is served unchanged. No build step or external runtime dependency is required.
