# mesh-guide.alicetech.io

An independent, community-run **Meshtastic hardware research guide** — a single, self-contained reference covering turnkey devices, development boards, radios, antennas, power, GPS, sensors, cases, and self-build paths.

- **Live site:** https://mesh-guide.alicetech.io
- **Content:** one static `index.html` (no build step, no frameworks, works offline)
- **Not affiliated with Meshtastic LLC.** “Meshtastic®” is a registered trademark of Meshtastic LLC.

## Files
- `index.html` — the full guide (research report + how-to)
- `CNAME` — custom domain record for GitHub Pages

## Deploying
1. Repo → **Settings → Pages → Build and deployment → Source: Deploy from a branch** → `main` / `(root)` → Save.
2. At your DNS host, add a `CNAME` record: host `mesh-guide` → value `<your-username>.github.io`.
3. GitHub automatically issues an HTTPS certificate for the custom domain.

## License & attribution
Content is original research citing official Meshtastic documentation. All product names and trademarks belong to their respective owners.
