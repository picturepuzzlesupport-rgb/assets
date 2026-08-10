# Manifest Localization Catalog

`source_catalog.json` is generated from `image_manifest.json` and contains every
stable category/image key plus the English source text. Locale files contain
only translated display fields and must not change image IDs, URLs, colors, or
other technical metadata.

Required locale files: hi, es, de, fr, ja, ko, id, it, tr.

`catalogStatus` remains `draft` until all source fields have been translated
and reviewed. Missing fields intentionally fall back to English in the app.
