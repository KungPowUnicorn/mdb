# 🎨 Mika's Drawing Book

A simple, friendly drawing app for kids to experiment with digital art. It's a single HTML file: no install, no build step, no accounts. Everything runs in your browser and nothing is uploaded anywhere.

Works on desktop, tablet and phone.

## Getting started

1. Download `index.html`.
2. Open it in any modern browser (Chrome, Edge, Firefox, Safari).
3. Start drawing.

**Host it on GitHub Pages:** push `index.html` to the repo, then enable Pages under *Settings → Pages*.

## Features

### Sidebar tabs (hide or show it with the ☰ button)

| Tab | What's inside |
| --- | --- |
| ✏️ **Draw** | Pen, eraser, marker, crayon, calligraphy, rainbow pen, glitter, spray, fill bucket, color picker (eyedropper), highlighter, neon glow, dotted line, pixel brush, confetti |
| ▲ **Shapes** | Line, arrow, rectangle, square, rounded box, circle, semicircle, triangle, right triangle, diamond, trapezoid, parallelogram, pentagon, hexagon, octagon, star, 6-point star, starburst, heart, cross, lightning, speech bubble, cloud. Each can be **Outline** or **Solid** |
| ⭐ **Stickers** | 150+ emoji stickers in collapsible categories (animals, food, nature, vehicles, space, fantasy, sports, weather and more). Tap to stamp, or drag for a trail |
| 🔤 **Fonts** | Letters (upper and lower case), numbers, punctuation and symbols, each in its own category. Pick a font style, toggle bold/italic, or type your own word and tap the canvas to place it |

Brush size and color (picker + swatches) apply to every tab. For stickers and letters, brush size controls how big they are.

### The ⋮ menu (top right)

- **Canvas**: size presets (Small, Standard, Wide, Full HD, Square, Portrait, A4, Postcard), custom size, transparent background, and History (undo, redo, clear).
- **File**: save as PNG, save/load project (`.json`), and load an image onto the canvas. A checkbox controls whether the canvas **resizes to the image size**; when off, the image is scaled to fit the current canvas.
- **About**: a short description and links.

### Quality-of-life extras

- Undo/redo buttons in the header
- Eyedropper to pick a color from your drawing
- Transparent background with a real eraser (erases to transparent, not white)
- PNG exports are named with the date and time
- Small pop-up messages confirm saves, loads and resizes
- Canvas scales to fit any screen; touch drawing is supported

## Keyboard shortcuts

| Keys | Action |
| --- | --- |
| `Ctrl/Cmd + Z` | Undo |
| `Ctrl/Cmd + Y` or `Ctrl/Cmd + Shift + Z` | Redo |
| `[` and `]` | Smaller / larger brush |
| `Esc` | Close the menu |

## Saving and loading

- **PNG** is a flat image, ready to share or print. Transparency is kept if the background is transparent.
- **Project (`.json`)** stores the canvas so you can reload it and keep editing later.
- Drawings are not stored between visits, so save a PNG or project before closing the page.

## Notes

- Stickers are emoji, so they look slightly different on each device (Apple, Google, Windows, and so on).
- Fonts use the fonts already installed on the device, so no internet connection is needed. Exact looks vary a little by system.
- Undo history holds the last 30 steps.

## Credits

Made with ❤️ by [KungPowUnicorn](https://ko-fi.com/kungpowunicorn)
Source: [github.com/KungPowUnicorn/mdb](https://github.com/KungPowUnicorn/mdb)
