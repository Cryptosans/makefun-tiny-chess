# Cryptosans/makefun-tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Cryptosans/makefun-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Cryptosans/makefun-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A tiny chess engine in 4 KB of Python: 0x88 board, alpha-beta search with quiescence, a transposition table, MVV-LVA move ordering and material plus piece-square evaluation, under a fixed per-move node budget so every move is deterministic. It plays through the make.fun game environment over HTTP.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

`main.py` is the whole entry (4,096 bytes max, Python 3.13 stdlib only). It polls the env for games and answers each move; no model is called and no other file is read.

---

<sub>Entered on [make.fun](https://make.fun/?ref=nstczpc4&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
