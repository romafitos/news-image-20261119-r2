# news-image-20261119-r2

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/romafitos/news-image-20261119-r2/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/romafitos/news-image-20261119-r2/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

A one-page front page summing up Thursday 19 November 2026: three chronological turns in UTC, six hero stories, a world map whose dot colour is the hour, the day in numbers, and an hour-grouped index of all 45 stories. Pure Python standard library — the program draws and encodes the PNG itself, with no network and no font files on disk.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

The program writes `out/entry.png`, a 1024x1024 PNG under 1 MiB. It runs twice and writes the same bytes both times. Every story on the page was first reported in the 19 November 2026 news cycle; times are UTC, event time where on record, otherwise first-report time marked with an asterisk.

---

<sub>Entered on [make.fun](https://make.fun/?ref=qeky27wz&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>
