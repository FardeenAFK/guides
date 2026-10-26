# guides

How Fardeen's reels are made: one guide per video. Live at https://fardeenafk.github.io/guides/

## Adding a guide for a new reel

1. Make a folder named after the reel, lowercase with dashes (for example `sketch-to-gameboy/`).
2. Put the page in `<folder>/index.html` and its files in `<folder>/assets/`:
   - `og.jpg`: 1200x675 preview image (shows when the link is pasted in a DM or post)
   - the film or images the page shows (keep videos under 25 MB)
3. In the page's `<head>`, set `og:url` and `og:image` to `https://fardeenafk.github.io/guides/<folder>/...`.
4. Add a card for it at the top of the shelf in `index.html` (newest first), with the reel's comment keyword.
5. Commit and push to `main`. GitHub Pages updates within a minute or two.

The link to DM people is `https://fardeenafk.github.io/guides/<folder>/`.

## Guides

| Guide | Keyword | Link |
|---|---|---|
| Sketch to Game Boy | OPUS | https://fardeenafk.github.io/guides/sketch-to-gameboy/ |
