# Know the World regional data packs

This public repository hosts the manifest for the Know the World app. Versioned SQLite database files are attached to GitHub Releases.

Data sources: Wikidata, Wikipedia, and Wikimedia Commons.

Country flag SVGs are served from `flags/` for the app. They are from the
[flag-icons project](https://github.com/lipis/flag-icons) and distributed under
the included MIT license.

## Image collections

Licensed regional image archives are attached to the [v1.1.0 media release](https://github.com/Muhammad-Hassan-522/know-the-world-data/releases/tag/v1.1.0).
The [`media-catalog.json`](./media-catalog.json) file lists each archive, its size, and checksum. Every archive includes a `media-manifest.json` that maps Wikidata IDs to image paths and records source and license details.

The app displays images using URLs in its SQLite data packs. These archives are separate downloads and are not installed automatically with a database pack.
