# makefun-tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Neeinn/makefun-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Neeinn/makefun-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 3,947 bytes of Python: 0x88 board, alpha-beta with PVS and LMR, quiescence search, transposition table, killer moves, PeSTO-style piece-square tables and incremental Zobrist hashing, with a fixed 80,000-node budget per move. Deterministic, standard library only.

## Run it

```sh
python3 main.py
```

The engine talks to the make.fun env over HTTP and plays a full trial on its own.

---

<sub>Entered on [make.fun](https://make.fun/?ref=bbrx9sbx&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
