# Poster photos (docs)

This folder holds the GitHub Pages site for serving photo assets to Unity.

How to use
- Put your images in the photos/ folder (e.g., docs/photos/img001.jpg).
- Update manifest.json to reflect your images and ordering.
- Enable GitHub Pages for this repository and set the source to the "docs/" folder (if not already set).

Pages URL (once Pages is enabled):
https://ddawnanddusk-cloud.github.io/posterLogo/

Notes
- This scaffold includes a manifest.json and a simple browser viewer (index.html).
- Git LFS is recommended for many or large images; a .gitattributes file was added at repo root to track common image types with LFS.
git add docs/README.md git commit -m "Trigger Pages rebuild: touch docs/README.md" git push origin main
