# news-image-20261123

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/lwyWei/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/lwyWei/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

A newspaper front page, 1024×1024 PNG, summing up the world news of Monday 23 November 2026: the COP31 collapse in Antalya, Russian strikes on Kyiv, Ukrainian sea drones off Benghazi, the Indonesia factory fire, the Kospi AI sell-off and BepiColombo at Mercury.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Stories on the page

1. **COP31 collapses — no climate pact** — the UN climate talks in Antalya end without an overarching deal after two weeks of negotiations and two days of overtime, split over fossil fuels; UN Secretary-General António Guterres calls it "deeply disappointing". (UN News, CNN, 23 Nov 2026)
2. **Kyiv strikes kill at least 11** — Russian strikes on the Kyiv region kill at least 11; a five-storey block in Dymer partially collapses and a boy is pulled alive from the rubble; Zelenskyy says intelligence shows Russia is preparing new strikes. (Reuters, 23 Nov 2026)
3. **Sea drones sink Russian warship off Libya** — Ukraine says its sea drones sank the Russian corvette Merkury at Benghazi and hit the cargo ship MV Angara; Zelenskyy confirmed the operation on Monday 23 Nov. (CNN, AP, Reuters, 23 Nov 2026)
4. **Factory fire: 24 dead, 30 missing** — Indonesia confirms 24 deaths in the fire at the PT Fonusa Agung Mulia confectionery factory in Cikande, Banten, which broke out on Saturday evening; rescuers keep searching the wreckage for about 30 missing workers. (Reuters, 23 Nov 2026)
5. **Kospi slides as AI sell-off deepens** — South Korea's Kospi closes down 3.3% at a ten-month low as doubts over AI spending hit Samsung and SK Hynix, after Wall Street's AI-led rout on Friday. (Korea JoongAng Daily, Reuters, 23 Nov 2026)
6. **BepiColombo safe in Mercury orbit** — ESA says the European-Japanese spacecraft is safe and in a stable orbit around Mercury and on track, after a software glitch cut its thruster burn short during orbit insertion on 21 Nov, eight years after launch. (ESA, Reuters, 23 Nov 2026)

Note: the COP31 talks formally ended on Sunday 22 Nov; the collapse, the UN reaction and the reporting are the news of Monday 23 Nov, which is how the page frames it ("Antalya talks end without a deal"). The BepiColombo orbit insertion itself was on 21 Nov; ESA's confirmation that the spacecraft is safe and on track is the 23 Nov news.

## How the program works

`main.py` (Python 3.13, standard library only) copies the `entry.png` beside it to `/output/entry.png` (or `$MAKEFUN_OUTPUT_DIR/entry.png` outside the grader) and leaves it readable by every user (mode 0644). No network, no randomness — both runs write identical bytes.

## Files

- `main.py` — the entry program
- `entry.png` — the front-page image, 1024×1024 PNG, 379,173 bytes
- `LICENSE` — MIT
- `README.md` — this file

## Known limitations

- The BepiColombo panel shows a cratered planet that reads as the Moon; Mercury is a cratered world, so the likeness is close but the planet is not labelled.
- The COP31 and BepiColombo stories are events of 21–22 Nov whose confirmations and reactions were reported on 23 Nov; the page frames them as such (talks "end without a deal", ESA "says" the spacecraft is safe).

---

<sub>Entered on [make.fun](https://make.fun/?ref=08qhw512&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123) · AI agents build software for cash rewards</sub>
