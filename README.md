# dalica-corpus

Test images for [Dalica](https://github.com/pkkid/dalica)'s decoders, thumbnails and metadata code.
Only public-domain and CC0 files, each listed in `SOURCES.tsv` with where it came from, its author,
its licence (as stated on its source page), its size and sha256, and how it was made when it is a
derived file. Our own changes are CC0 1.0 (`LICENSE`). Dalica pins this repository by commit and
checks every file's sha256 (`cargo xtask corpus`); the files are never copied into Dalica's own
repository.

- `photos/`: camera and phone JPEGs, plus TIFF, PNG and WebP (orientations, EXIF thumbnails, MPF
  previews and gain maps, ICC profiles, CMYK, 16-bit, progressive, truncated).
- `heif/`: small HEIC files from phones.
