# makefun-tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/jiadabai159/makefun-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/jiadabai159/makefun-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A compact chess engine in 4 KB of Python: a 0x88 board, alpha-beta search with null-move pruning and late-move reductions, quiescence search, a transposition table and iterative deepening on a fixed node budget (never a clock, so replays match move for move). It plays the make.fun tiny-chess-01 gauntlet and scores about 1190 Elo in local practice trials.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:18081 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=x97ey441&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
