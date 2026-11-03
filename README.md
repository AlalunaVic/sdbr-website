# sdbr-website

Backup / mirror of the official **Same Day Bow Rehair** website — https://samedaybowrehair.com

- The **live site** is hosted on Porkbun Secure Static Hosting. This repo is the safety copy and review copy, kept in sync by Jarvis.
- Snapshot from **2026-11-02**: byte-identical to the live site (`index.html` + `images/`).
- Workflow: changes are prepared and reviewed here first, then published to Porkbun.

Serving NJ & NYC · By appointment · https://book.samedaybowrehair.com

## Redesign (2026-11-02)

- `index.html` redesigned: video hero, "what musicians worry about" section, one-day timeline, prices, luthier story, free-redo promise, FAQ.
- New media in `images/`: victor-intro.mp4 (+poster), pickup-handoff.mp4 (+poster), victor-apron-violin.jpg, bench-materials.jpg, workshop-bench-wide.jpg.
- Existing photos are referenced by their current names in `images/` on the live server (not stored in this repo).
- To publish: upload `index.html` and the new files in `images/` to Porkbun, keeping the existing images there.
- Preview: https://alalunavic.github.io/sdbr-preview/
