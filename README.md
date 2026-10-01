# Booth Builder catalogue

The published catalogue that the Booth Builder app downloads: served by GitHub Pages at
https://s-mireles.github.io/booth_builder_catalogue/.

Don't edit these files by hand. The app's catalogue build writes them from the authoring catalogue
(`tools/catalogue/build_catalogue.tscn` in the booth_builder repository; see its `docs/ADDING_CATALOGUE_ITEMS.md`):

- `catalogue.csv`: the items, with each one's pack and thumbnail, and the thumbnail pack;
- `finishes.csv`: the colours items can be ordered in;
- `packs/`: one download per item, its 3D model, and `thumbnails-<hash>.pck`, every thumbnail in one download;
- `thumbnails/`: one picture per item.

Files are named after their content, so a published file never changes; the build deletes those no longer listed.
`.nojekyll` makes Pages serve the files as they are.

## Licence

Copyright © 2026 Robinson Show Services. All rights reserved: the files are for the Booth Builder app only. See
[LICENSE.md](LICENSE.md).
