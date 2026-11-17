# token-radar-01-entry

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/sunqincang/token-radar-01-entry/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/sunqincang/token-radar-01-entry/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

A token launch radar: it reads the sealed DefiLlama snapshot, ranks every
pre-token protocol by an implied value priced from the snapshot's own
token-bearing peers (each category's median market-cap/TVL, shrunk toward
the global median and capped), adjusted for seven-day TVL growth and for
how long the protocol has run with no token — and writes a self-contained
dashboard (sortable, filterable, one detail view per protocol with the
model's arithmetic and a concrete farm plan) plus the ranked board.

## Run it

```sh
node main.ts --input <snapshot.json|directory>
# writes board.json, data.js, dashboard/, screenshots/ and dossier.json
# to /output (or $MAKEFUN_OUTPUT_DIR)
```
