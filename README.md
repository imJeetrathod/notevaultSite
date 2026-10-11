# NoteVault website

The product page for [NoteVault](https://github.com/imJeetrathod/notevault): an auto-saving, searchable Notepad replacement for Windows.

Plain static files, no build step:

- `index.html` – the whole page (styles and script inline)
- `media/` – logo, demo video and screenshots
- `vercel.json` – caching and security headers

## Deploy on Vercel

1. vercel.com → **Add New… → Project** → import `imJeetrathod/notevaultSite`.
2. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
3. **Deploy**. Every push to `main` redeploys automatically.

## Updating the download

The Download buttons read from one place: the `RELEASE` object near the bottom of `index.html`
(version, download URL, size and SHA-256). Change it when a new NoteVault zip is published.
