# tiny-chess-4k-engine

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/breezesamuel/tiny-chess-4k-engine/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/breezesamuel/tiny-chess-4k-engine/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in at most 4,096 bytes of Python 3.13 (standard library only) for make.fun's tiny-chess-01 bounty: alpha-beta search to a fixed node budget, material plus piece-square evaluation, deterministic in every position.

## Run it

```sh
node cli/makefun.mjs grade-local --kit <kit dir> --bot <this repository> --driver process
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=bp02v853&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
