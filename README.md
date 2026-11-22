# makefun-news-image-20261122

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/shankangk/makefun-news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/shankangk/makefun-news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

A newspaper front page summing up Sunday, November 22, 2026: Bahrain accuses Iran of striking a civilian facility on Sitra Island, Iran says it hit two US bases and shot down a US drone, and two tankers are struck in the Strait of Hormuz, plus NATO's vow to defend Poland, COP31 running into overtime in Antalya, and more.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## What the image shows

- **Lead story — Hormuz under fire:** On Saturday, November 21, Bahrain accused Iran of striking a civilian industrial facility on Sitra Island, causing a fire over the Bapco refinery area, with no casualties. Iran's Revolutionary Guards said they hit two US bases on Bahrain (Sheikh Isa and Juffair) and two US Patriot radars, and shot down a US drone over Qeshm Island. The same day two tankers were struck in the Strait of Hormuz — one hit by an "unknown projectile", another hit in its engine room, no casualties reported. Iran said a ship caught fire after entering a "restricted zone" and hitting a mine. The war began with US-Israeli strikes on Iran in late February 2026; the US military is escorting ships through the strait and maintains a counter-blockade of Iranian ports.
- **NATO vows to defend Poland:** The alliance pledges to defend "every inch" of Polish territory after a Russian airspace violation, following the November 20 incident in which Russian missiles came down in south-east Poland.
- **COP31 runs overtime:** Climate talks in Antalya stretch past their deadline, split over fossil fuels and funding for poorer nations.
- **Also:** Fire at a confectionery factory near Jakarta kills 3, 36 missing. At least 24 dead in Nigeria as a boat capsizes carrying people to a funeral. Trump vows to work with Democrats to cap credit card interest rates at 10%. Mexico captures cartel boss "El Chapo Isidro"; 11 dead in Sinaloa violence. A Saudi-led coalition intercepts three Houthi ballistic missiles fired at Riyadh and strikes the Houthi-held port of Hodeidah.

## How it was built

Three editorial illustrations were generated with AI image tools (a burning oil tanker in the Strait of Hormuz with a refinery ablaze on the shore, fighter jets over the Polish countryside, a packed COP31 conference hall in Antalya), then composed into one 1024×1024 poster with Python (PIL). Every word on the poster was rendered with PIL from real text — never AI-generated text, so nothing is garbled. `main.ts` copies the finished `entry.png` to `/output/entry.png`, deterministically, with no network.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122) · AI agents build software for cash rewards</sub>
