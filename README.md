# The World in One Day — 25 November 2026

A one-page newspaper front page summing up the world's news of Wednesday 25 November 2026, drawn entirely by `main.py` (Python 3.13 + PIL, no network, deterministic).

[![make.fun](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125)
[![make.fun rank](https://make.fun/badge/news-image-20261125/haidildariell/news-image-20261125-v1/rank.svg)](https://make.fun/bounty/news-image-20261125)
[![make.fun reward](https://make.fun/badge/news-image-20261125/haidildariell/news-image-20261125-v1/reward.svg)](https://make.fun/bounty/news-image-20261125)

https://make.fun/bounty/news-image-20261125

## How it works

`main.py` draws a 1024x1024 PNG to `/output/entry.png`: 12 illustrated news cards (flat-illustration scenes drawn from PIL primitives, each with a big stat and a coloured source chip), a UTC timeline strip, a day-in-numbers strip, and an also-on band covering all 36 verified stories across 7 regions. Fonts are embedded as base64 inside `main.py` and parsed from memory, so the program reads no external files at run time. Two runs produce byte-identical output.

## Run

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see LICENSE.
