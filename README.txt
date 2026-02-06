# Open-in-Browser Gate (Netlify) — with custom background

This folder is ready to deploy.

## Files
- `index.html` — instruction screen + auto-redirect if not in an in-app browser.
- `background.jpg` — your background image (replace with your own).
- `finger.png` — pointer icon top-right.
- `netlify.toml` — optional Netlify config.
- `README.txt` — these instructions.

## Quick Deploy (Drag-and-Drop)
1) Go to https://app.netlify.com/drop
2) Drag this entire folder onto the page.
3) Netlify will give you a live URL.
4) Rename the site in **Site settings → Domain management** to `heyallisonmylinks` so it becomes `https://heyallisonmylinks.netlify.app`.

## Change Redirect Target
`index.html` has:
const TARGET_URL = "https://heyallisonmylinks.netlify.app/";
Change this if you want to forward to a different page when NOT in an in-app browser.
(UTM parameters and hashes are preserved.)

— Generated 2025-11-12T10:26:55
