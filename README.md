# Image Resizer

Resize an image to exact dimensions and download it as PNG or JPEG. Runs entirely in your browser, nothing is uploaded.

**Live:** <https://image-resizer.slippylabs.com/>

## What it does

- Resize an image to exact pixel dimensions, with an optional aspect-ratio lock.
- Export as lossless PNG or smaller JPEG.

## How it works

The image is drawn to a local `<canvas>` and read back out. Nothing is uploaded — the file never leaves the tab.

## Run it locally

A static site. No build step, no package manager, no dependencies:

```
git clone git@github.com:slippylabs/image-resizer.slippylabs.com.git
cd image-resizer.slippylabs.com
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

---

Part of [Slippy Labs](https://slippylabs.com). Every tool is indexed at
[projects.slippylabs.com](https://projects.slippylabs.com).
