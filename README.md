# MemeLab

**Make memes. Ship stickers.**

A two-in-one static page that runs **entirely in the visitor's browser** — no uploads, no accounts, no tracking:

## Meme Maker
- Upload any photo (or start from a plain gradient background)
- Classic top/bottom caption text — bold capitals, black outline, size slider
- GIFs work too: the meme exports as the frame on screen when you download
- One tap sends the finished meme into the Sticker Maker

## Sticker Maker (WhatsApp)
- Source: any image, a GIF (plays live — capture the exact frame you want), or your meme
- Exports a true **512×512 WebP** — WhatsApp's sticker format and size — with padding and background controls (transparent/white/yellow/green)
- If the file comes out over WhatsApp's ~100 KB sticker comfort zone, the exporter automatically steps quality down until it fits
- On-page steps for adding the sticker to WhatsApp favourites

## Honest limits
- **Animated** GIF → animated sticker is not possible in a plain web page (WhatsApp's animated WebP needs an encoder browsers don't ship), so GIFs become stickers from a frame you pick. The page says so.
- If a browser can't encode WebP (older Safari), the page says that too and suggests Chrome on Android instead of silently producing the wrong file.

## Live

Published with GitHub Pages from this repo's `gh-pages` branch (the `site/` folder).
