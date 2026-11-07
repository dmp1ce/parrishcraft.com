# parrishcraft.com

Landing page for Parrishcraft — the Parrish family Minecraft server.
Static single-file site served by GitHub Pages at **parrishcraft.com**.

DNS layout (managed via `scripts/namecheap-dns.py` in the nixos-config repo):

- `parrishcraft.com` (apex) → GitHub Pages A records (this site)
- `mc.parrishcraft.com` → 137.66.33.206 — the `dawson-mcrelay` fly.io
  blind relay forwarding the standard Minecraft port to the family
  server on dawson (fresh world, online-mode, whitelist).

Session record: `docs/session-notes/2026-11-06-minecraft-public-onramp.md`
in the nixos-config repo.
