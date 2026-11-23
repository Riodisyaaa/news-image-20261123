# The World in One Day — Monday, 23 November 2026

[![news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/Riodisyaaa/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/Riodisyaaa/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123)

A newspaper-front-page image summing up the world's news of **Monday, 23 November 2026**.

## The image

`entry.png` (1024×1024) is a front page, "THE WORLD IN ONE DAY", dated Monday, 23 November 2026.

**Three lead stories**, each with a drawn illustration:

- **COP31 talks collapse in Turkiye** — the final draft omits the words "fossil fuels"; the EU and others reject any deal without a phase-out.
- **Russian cargo ship still on fire off Finland** — after a drone attack in the Baltic Sea; warnings the Ukraine war is spilling into the region.
- **Drone hits a Kyiv region building; 14 missing** — President Zelenskiy reports at least 14 people missing.

**The day in brief** — 22 more dated stories across every region and field: South Korea's education minister resigning over AI exam cheating; the Indonesia factory fire; the Lisbon cost-of-living march; Nepal PM Shah's talks with Modi; India's record 720/9 in Wellington; the Strait of Hormuz conflict; Nvidia chip sales to China; Liverpool's rout of Manchester United; the Congo Ebola response; 24 civilians killed in South Sudan; the Democrats' historic 258-seat US House majority; the Houthi missile intercept; Myanmar's ASEAN rebuke; the Gulf of Oman tanker incident; Pakistan's hope for a US–Iran deal; the Ferrari row over the Las Vegas crash; Paolo Bulgari's death at 89; India A vs Pakistan A; the ₹4,000-crore Arunachal push; BJP MP Wadkute's death; and Anupama's world snooker title defence. A "day in numbers" box and a world weather strip close the page.

Every story is dated 23 November 2026 and drawn only from that day's reported news. All illustrations are drawn by hand in SVG/CSS — no photographs, no external images.

## How it is built

`index.html` holds the whole front page (hand-drawn SVG illustrations, system serif type). It was rendered once to `entry.png` with a headless browser; `main.ts` (Node 22, standard library only) simply copies `entry.png` to the output directory, so both grader runs write byte-identical output.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Licence

MIT — see [LICENSE](LICENSE).
