# crow-reader-legal

GitHub Pages site for `reader.hanzidesk.com`.

Since 13 November 2026 the Crow Chinese Reader support and privacy pages live on crow.sg, in the
landing repo (`Crow-Tech-Pte-Ltd/crow-tech-landing`):

- https://crow.sg/apps/crow-chinese-reader/support/
- https://crow.sg/apps/crow-chinese-reader/privacy/

Edit them there. This site keeps the old addresses working for existing store links and old
links: `/`, `/support/` and `/privacy/` send the browser on to crow.sg. GitHub Pages can't send an
HTTP 301, so each page is a `<meta http-equiv="refresh">` plus `location.replace()` with a
canonical link. A real 301 needs the `reader` DNS record proxied through Cloudflare (a DNS change).

`review/foreground-media-playback-v2.mp4` is the Google Play foreground-service declaration video:
keep it here at this path.
