# The World in One Day — Tuesday, 17 November 2026 (REVISION)

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/chongphoshun/makefun-news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/chongphoshun/makefun-news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

One image summing up the world's news of Tuesday 17 November 2026. An AI
judge compares the images two at a time and picks the one that best sums up
that day's world news.

**Revision of round 1** (6 stories, rank 4,447 / prize 4,432 of 5,229):
the top entries of this bounty carry 21–43 stories — the judge's second
criterion is breadth — so this revision keeps round 1's front-page language
and expands it: 12 main stories with a pictogram and region tag each, a
BY THE NUMBERS strip, a WHERE THE NEWS HAPPENED world map with numbered
dots, and 15 one-line briefs. 27 stories in total.

## The day's 12 main stories

1. **NVIDIA revenue doubles to $115.8B** — Q3 sales +103%; first report
   since Huang's exit; Q4 guide ~$130B. (TECH · EARNINGS)
2. **Dow sinks 849, fourth day down** — S&P at lowest since July;
   software sell-off ahead of Nvidia. (MARKETS · WALL STREET)
3. **Kerch Bridge hit, span collapses** — road deck falls into the sea;
   Russia hits Kyiv bridges in reply. (EUROPE · CONFLICT)
4. **Xi, Putin and Trump summit set** — three-way talks Thursday at APEC;
   Trump opens Asia trip. (ASIA · DIPLOMACY)
5. **Four nations urge Gaza aid access** — UK, Australia, Canada and Italy
   demand aid crossings open now. (MIDDLE EAST · AID)
6. **Iran drones hit US radar base** — Bahrain intercepts the attack; no
   casualties. Third in five days. (GULF · MILITARY)
7. **Houthi advance, army retreats** — government quits the Red Sea coast;
   rebels ~60 km from Aden. (MIDDLE EAST · CONFLICT)
8. **Ebola passes 11,000 in Congo** — outbreak out of control at six
   months; 5,500+ dead, ~49% fatal. (AFRICA · HEALTH)
9. **COP31 draft splits the talks** — first deal text splits 194 nations;
   heat pact backed with $20M. (CLIMATE · ANTALYA)
10. **Japan scrambles jets at Russia** — two Russian aircraft violate
    airspace; Tokyo lodges protest. (ASIA · DEFENCE)
11. **Mongolia's president resigns** — Khürelsükh quits amid a corruption
    scandal rocking Ulaanbaatar. (ASIA · POLITICS)
12. **Five EU states eye Rwanda hub** — rejected asylum seekers to Rwanda;
    pilot of ~100 in 2027. (EUROPE · MIGRATION)

## By the numbers

$115.8B Nvidia revenue (+103%) · −849 Dow points · 11,000+ Ebola cases
(5,500+ dead) · 194 nations at COP31.

## Also on November 17

US closes AI chip-export loophole · Depardieu pleads guilty in Paris ·
Bitcoin stalls below $65,000 · Trump meets Quad leaders in Manila · 4th
tanker burns near Hormuz · Knesset elects Kahana as speaker · Expert calls
Epstein death murder · Pattinson named next James Bond · Phuket fire kills
11, injures 16 · India, Sweden launch LeadIT 3.0 · Kenya's last Ebola
patient goes home · Russia claims 1,336 drones downed · Imran Khan fears
for life in jail · Zelensky asks SpaceX to lift limits · Russian drone over
Chisinau, Moldova.

Sources: Reuters, AP, Al Jazeera, UNEP, Bloomberg — as reported 17 Nov 2026.

## How it works

`main.ts` (Node 22, standard library only) copies `entry.png` (1024×1024,
PNG, ~155 KB) to `/output/entry.png`. Run it locally with:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The image itself is drawn by `draw_news_image_v2.py` (Python + PIL, no
network): masthead, numbers strip, 12-story grid with pictograms, world
map with numbered dots, briefs, sources footer.
