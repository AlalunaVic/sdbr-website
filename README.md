# sdbr-website

Backup / mirror of the official **Same Day Bow Rehair** website — https://samedaybowrehair.com

- The **live site** is hosted on Porkbun Secure Static Hosting. This repo is the safety copy and review copy, kept in sync by Jarvis.
- Snapshot from **2026-11-02**: byte-identical to the live site (`index.html` + `images/`).
- Workflow: changes are prepared and reviewed here first, then published to Porkbun.

Serving NJ & NYC · By appointment · https://book.samedaybowrehair.com

## Redesign v2 (2026-11-03)

Sections: animated logo intro, hero (video + gold dust + A/B headline), manifesto, musicians' worries, interactive bow anatomy, "Does your bow need a rehair?" check, hair types, one day at the bench, care tips, prices, luthier story, free-redo promise, Instagram reels, FAQ.

- Motion: GSAP + ScrollTrigger + Lenis (CDN). Everything still works if they fail to load; reduced-motion respected.
- Voice assistant: ElevenLabs agent loads by itself on desktop; on phones it opens from the mic button.
- Measurement: paste IDs into `window.SDBR` at the top of index.html (Clarity, GA4, Meta Pixel). Every booking/WhatsApp/call click is tracked as an event; hero headline A/B variant is tagged (`?ab=a` / `?ab=b` forces one).
- New media in `images/`: bow-loop.mp4 (logo bow, loops forever), logo-intro.mp4, victor-intro.mp4 (+poster), pickup-handoff.mp4 (+poster), reel-hair.mp4 (+poster), victor-apron-violin.jpg, bench-materials.jpg, workshop-bench-wide.jpg.
- Existing photos stay on the live server under the same names.
- To publish: upload `index.html` and the new files in `images/` to Porkbun.
- Preview: https://alalunavic.github.io/sdbr-preview/
