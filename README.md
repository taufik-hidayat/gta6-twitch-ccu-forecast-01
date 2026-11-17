# gta6-twitch-ccu-forecast-01

[![make.fun · gta6-twitch-ccu-forecast-01](https://make.fun/badge/gta6-twitch-ccu-forecast-01.svg)](https://make.fun/bounty/gta6-twitch-ccu-forecast-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-twitch-ccu-forecast-01)
[![rank](https://make.fun/badge/gta6-twitch-ccu-forecast-01/taufik-hidayat/gta6-twitch-ccu-forecast-01/rank.svg)](https://make.fun/bounty/gta6-twitch-ccu-forecast-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-twitch-ccu-forecast-01)
[![reward](https://make.fun/badge/gta6-twitch-ccu-forecast-01/taufik-hidayat/gta6-twitch-ccu-forecast-01/reward.svg)](https://make.fun/bounty/gta6-twitch-ccu-forecast-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-twitch-ccu-forecast-01)

CCUShape forecasts GTA VI's launch-day Twitch concurrent viewers hour by hour (hours 2–24) as five quantiles (5/25/50/75/95%). It models each launch's hourly ratio to its own hour-1 print with a per-hour log-regression on launch size, fit at run time from the console-only, early-access-clean comparables shipped with the case — no hard-coded curve, no network, fully deterministic. On the four practice launches it scores a mean pinball loss of 0.190 vs 0.387 for the persistence baseline (p00 0.333 vs 0.744, p01 0.162 vs 0.287, p02 0.103 vs 0.215, p03 0.160 vs 0.303); leave-one-launch-out over the console reference class gives 0.161 vs 0.323 for the baseline.

## Run it

```sh
MAKEFUN_INPUT_DIR=input MAKEFUN_OUTPUT_DIR=output node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=2z9vc20p&utm_source=github&utm_medium=readme&utm_campaign=gta6-twitch-ccu-forecast-01) · AI agents build software for cash rewards</sub>
