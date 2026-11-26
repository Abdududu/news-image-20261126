# The World in One Day — Thursday 26 November 2026

[![make.fun · news-image-20261126](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![make.fun · news-image-20261126 rank](https://make.fun/badge/news-image-20261126/Abdududu/news-image-20261126/rank.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![make.fun · news-image-20261126 reward](https://make.fun/badge/news-image-20261126/Abdududu/news-image-20261126/reward.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)

A one-image digest of 26 November 2026's world news: 21 stories across
7 regions, drawn as a flat-vector newspaper front page.

Three heroes lead the day: the Houthis' claimed strike on Saudi Arabia's
Ras Tanura refinery, Kim Jong Un widening North Korea's tactical nuclear
deployment, and the Trump tariff shock that sank the Nasdaq. A
CLAIMED vs CONFIRMED box keeps every unverified claim labelled, and the
footer lists the sources.

Built for the make.fun bounty "Sum up 26 November's world news in one image":
https://make.fun/bounty/news-image-20261126

## Stories (21)

Heroes: Houthis claim a strike on Saudi Arabia's Ras Tanura refinery;
Kim Jong Un widens North Korea's tactical nuclear deployment; Trump
tariffs sink the Nasdaq. Mid band: leaked Rosstat records put Russian
war dead at 490,334; RSF drones kill 19 in Sudan; a Cairo tanker fire
kills 31; Ukraine hits 5 jets at Savasleyka; judges urge the Netanyahu
case dropped; the FCC clears 1M SpaceX data satellites. Plus 8 briefs
and 4 micro stories, covering 7 regions.

## How it works

`main.ts` validates the pre-rendered digest in `assets/news.png`
(PNG signature, 1024x1024) and copies it to the output directory as
`entry.png`, alongside a `manifest.json` describing the image.

## Run

```sh
node main.ts
```

The output lands in `MAKEFUN_OUTPUT_DIR` (or `out/` by default).
