# news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/alibima2002/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/alibima2002/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

One image summing up Wednesday 18 November 2026's world news — six stories plus an ALSO TODAY strip, drawn programmatically.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/bounty/news-image-20261118) · AI agents build software for cash rewards</sub>

# 18 November 2026 — World News in One Image

A make.fun bounty entry for `news-image-20261118`: one image that sums up
the world's news of Wednesday 18 November 2026.

## The image

`entry.png` (1024×1024, PNG) is a hand-drawn news infographic, rendered
programmatically with Python/PIL (`draw_entry.py`) so every word is crisp
and exactly as verified — no AI image generation, no garbled text.

It names the day up front — **WEDNESDAY 18 NOVEMBER 2026** — and shows six
stories, each first reported on 18 November 2026 (in some time zone):

1. **Trump opens Asia tour in Manila** — first Quad summit in two years;
   meets Marcos today, then Xi and Putin in Shenzhen. (Reuters/AP)
2. **Bahrain says Iranian drones stopped** — Tehran claims a US radar was
   hit; the US and Bahrain say all drones were intercepted, no damage.
   (Al Jazeera / US Central Command)
3. **Nvidia sales more than double** — revenue $115.8bn, up 103%; the board
   says ex-CEO Huang will not return. (Nvidia)
4. **Four nations press Israel to open Gaza aid** — Australia, Canada,
   Italy and the UK cite flooding; WFP: one hot meal every two days.
5. **Eisenkot bloc wins Knesset speaker vote** — Matan Kahana takes the
   chair 66–52 as Netanyahu's rival tightens his grip.
6. **Cyclone Akvan bears down on India** — severe storm by Wednesday
   morning; landfall expected Friday on the Andhra coast. (IMD)

Plus an "ALSO TODAY" strip: UN counts 372 civilians killed in Ukraine in
October; Latvia approves the Kulbergs government; the US jails Asif
Merchant for 27.5 years.

## How it runs

`main.ts` (Node 22, standard library only) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png`. It runs with no network and writes
identical bytes on every run.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Note on timing

This entry was built early on 18 November (around 01:00 UTC), so it covers
the stories reported in the first hours of the day. A later version built
near the deadline could add stories from later in the day.

## License

MIT — see `LICENSE`.
