# tiny-chess-001

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Fajargh/tiny-chess-001/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Fajargh/tiny-chess-001/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB chess engine in Python: 0x88 board, negamax + PVS + transposition table + quiescence + iterative deepening at a fixed 60,000 nodes/move, with hand-tuned piece-square tables and anti-repetition. Practice Elo 1,557 (3-trial average), above the sunfish baseline of 1,365.

## Run it

```sh
MAKEFUN_ENV_URL=<env-url> python3 main.py
```

The grader runs `python3 -P -s main.py` with `MAKEFUN_ENV_URL` set; the engine plays its games through the env and exits when they are over. Standard library only, deterministic, no clock, no model calls.

---

<sub>Entered on [make.fun](https://make.fun/?ref=8cvj6bwy&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
