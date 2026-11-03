# sdbr-website

Backup / mirror of the official **Same Day Bow Rehair** website — https://samedaybowrehair.com

- The **live site** is hosted on Porkbun Secure Static Hosting. This repo is the safety copy and review copy, kept in sync by Jarvis.
- Snapshot from **2026-11-02**: byte-identical to the live site (`index.html` + `images/`).
- Workflow: changes are prepared and reviewed here first, then published to Porkbun.

Serving NJ & NYC · By appointment · https://book.samedaybowrehair.com

## Redesign v3 (2026-11-03) — inspired by landonorris.com, apple.com/airpods-pro, bruno-simon.com

- Hero: giant SAME DAY / BOW / REHAIR type, looping logo bow, Victor cutout portrait, mouse parallax, gold "bow hair" contour lines.
- 3D bow (three.js, built in code, no model files): scroll-driven camera through head, hair and frog; frog, eye, ring, slide and screw come apart; drag to turn, tap any part for details.
- Musicians' worries as a large-type accordion, editorial collage about Victor and El Sistema, price, promise, booking + FAQ.
- New media in `images/`: victor-cutout.webp, bow-loop.mp4, logo-intro.mp4, pickup-handoff.mp4 (+poster). Existing photos stay on the live server under the same names.
- Measurement: paste IDs into `window.SDBR` (Clarity, GA4, Meta Pixel). A/B on the hero line (`?ab=a` / `?ab=b`).
- To publish: upload `index.html` and the new files in `images/` to Porkbun.
- Preview: https://alalunavic.github.io/sdbr-preview/
