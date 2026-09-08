# Five Lives of a Bronze

Entry for the **FLORA Museum Challenge** on Contra, 8 September 2026.

A Chola bronze was never meant to live in a glass case. She was cast to be dressed in silk, garlanded, and carried through the streets by lamplight. This entry takes the Met's tenth-century **Standing Parvati** (The Metropolitan Museum of Art 57.51.3, Open Access) and builds the world around her: five true moments from the thousand years between the mould and the museum.

| # | Life | When | Medium |
|---|------|------|--------|
| I | The Mould | ca. 920 CE | 35mm film |
| II | The Procession | ca. 950 CE | cinematic colour |
| III | The Burial | ca. 1310 CE | oil painting |
| IV | The Plough | 1932 | black and white |
| V | Gallery 240 | 2026 | museum photography |

## Links

- Showcase page: `index.html` (GitHub Pages: https://thehardikdewra.github.io/flora-museum-challenge-2026-09-08/)
- FLORA canvas, every node and pass: https://app.flora.ai/projects/ns75pfrkdk6fe2bk0kg78aynvh8e1e0t
- The original: https://www.metmuseum.org/art/collection/search/39325
- The challenge: https://contra.com/community/topic/floramuseumchallenge

## How it was made

Everything starts from the Met photograph as the source node on a FLORA canvas. Each life is an image-to-image generation wired to that source (Nano Banana 2), holding her pose, crown and gesture while the world changes around her. Gallery 240 took two passes; both stay on the canvas. The five panels close into one museum-label strip set in Haffer.

The canvas was driven through FLORA's MCP server (OAuth) rather than the browser: project creation, asset import from the Met URL, reference-guided generations, text nodes, arrangement and the final upload all went through the API. Notes in `BRIEF.md`; the Contra submission text in `CONTRA-SUBMISSION.md`.

## Files

```
index.html                      showcase page
assets/1-the-mould.png          life I
assets/2-the-procession.png     life II
assets/3-the-burial.png         life III
assets/4-the-plough.png         life IV
assets/5-gallery-240.png        life V, second pass
assets/5-gallery-240-first-pass.png
assets/final-five-lives-of-a-bronze.jpg
assets/met-39325-standing-parvati.jpg   source, courtesy The Met (CC0)
BRIEF.md                        concept, prompts, judging map
CONTRA-SUBMISSION.md            paste-ready submission text
```

Source image courtesy The Metropolitan Museum of Art, Open Access (CC0). Generated images by Hardik Dewra.
