# OPCAB / CABG を学ぶ — 学習リソース集

A single-page, QR-shareable collection of coronary-artery-bypass (OPCAB/CABG) learning
resources, built for a talk at the **U-40 近畿支部 BLS** (Japanese young cardiac surgeons'
Basic Lecture Course).

**Live page:** https://ktonai103.github.io/opcab-learning/

The speaker shows **one QR code** (to this page) on a presentation slide; the audience scans
it, lands here on their phone, and can open any of the five curated resources.

## Resources

| # | Resource | Source |
|---|----------|--------|
| 1 | Off-Pump Beating Heart Surgery (Video Series) | Prof. Tristan D. Yan |
| 2 | Supreme Quality Arterial OPCAB — TOPCAB | Prof. Tohru Asai |
| 3 | ESS Website (expert surgical video library, login required) | Johnson & Johnson MedTech |
| 4 | U-40 ONLINE BLC ハンズオン (CABG) | オンラインBLC U-40 |
| 5 | 冠動脈吻合の教科書 | チームWADA |

## How it's built

- Self-contained static `index.html` (inline CSS, no build step).
- Thumbnails stored locally in `assets/` (downloaded from YouTube) for offline-robust display.
- A single share QR code (to this page) pre-generated as crisp SVG + high-res PNG (`qrencode`).
- Hosted on GitHub Pages.

All videos and sites are the property of their respective owners; links are provided for
educational reference only.
