# KYC – video liveness guide

Prototype of the "راهنمای احراز ویدئویی" screen (Figma: KYC - BNPL, node 6001:290121).
A head-turn guide clip plays inside the face frame, and the blue arc/arrow follows the direction he turns.

- `prototype/head-turn-guide.html` – the page
- `assets/liveness-head-turn-guide_edited_compressed.mp4` – clip used by the page (256px, ~190 KB)
- `prototype/figma-assets/` – vectors exported from Figma (reference)

## Run

```bash
python3 -m http.server 8765
```

Live: https://tara-product-team.github.io/kyc/

Locally, open http://localhost:8765/prototype/head-turn-guide.html (the video needs a server; it won't play from `file://`).

Cue timings live in the `CUES` array at the bottom of the HTML.
