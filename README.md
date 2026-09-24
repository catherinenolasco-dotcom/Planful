# Catherine Nolasco Portfolio: Director of People Operations

A static, single-page portfolio written for the Planful Director of People Operations role. It is an independent page styled after the Planful brand and is not affiliated with Planful.

## Files

- `index.html` is the finished page with fonts embedded. Publish this file.
- `src/content.py` holds all the text.
- `src/build_portfolio.py` builds `index.html` from the content.

## Publish with GitHub Pages

1. Create a new repository and upload `index.html` and the `src` folder.
2. Open Settings, then Pages.
3. Choose Deploy from a branch, select `main` and the root folder, and save.

## Rebuild after editing content

Run `npm i @fontsource/newsreader @fontsource/dm-sans` in the repo folder, then `python3 src/build_portfolio.py`. Copy the generated `index.html` into place.
