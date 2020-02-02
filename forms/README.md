# Updating thumbnails
This should probably be done programmatically, either with something like [`PDF.js`](https://mozilla.github.io/pdf.js/), or a CLI tool...

1. Open PDF in Adobe Reader
1. `Edit` -> `Take a Snapshot`
1. Select entire document
1. Paste into mspaint
1. Resize to `200 x 258 (259)`
1. Save as `.gif` in [`/images/thumbnails`](../images/thumbnails)