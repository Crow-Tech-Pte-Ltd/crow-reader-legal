<p align="center"><img src=".github/logo.png" width="112" alt="Crow Chinese Reader logo"></p>

# crow-reader-legal

GitHub Pages site for `reader.hanzidesk.com`.

Since 13 November 2026 the Crow Chinese Reader support and privacy pages live on crow.sg, in the
landing repo (`Crow-Tech-Pte-Ltd/crow-tech-landing`):

- https://crow.sg/apps/crow-chinese-reader/support/
- https://crow.sg/apps/crow-chinese-reader/privacy/

Edit them there. The old addresses keep working for existing store links and old links:
`reader.hanzidesk.com` is proxied through Cloudflare, whose redirect rules answer `/`, `/support/`
and `/privacy/` with an HTTP 301 to crow.sg. Every other path is served from this site. The pages
here (a `<meta http-equiv="refresh">` plus `location.replace()` with a canonical link) are only a
fallback if those rules are removed.

`review/foreground-media-playback-v2.mp4` is the Google Play foreground-service declaration video:
keep it here at this path.
