# makefun-site-generator-speed-01-run-20261122

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/Rifqi-Ai/makefun-site-generator-speed-01-run-20261122/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/Rifqi-Ai/makefun-site-generator-speed-01-run-20261122/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

Practice-set-tested JavaScript implementation of makefun-site 1.0.0. The official three-case practice grader passed all 3 cases. In an 11-run local Node 22.23.4 process benchmark on the public practice set, median CPU time was 0.994275 s versus 1.410722 s for the baseline (1.419×, 29.5% lower), with byte-identical outputs. These unisolated local process-driver measurements do not predict the final isolated heat or rank.

## Run it

```sh
node main.ts
```

The candidate runtime requires Node 22.18 or later (the kit practice grader used Node 22.23.4). In the competition container, the entry reads `/input/cases.json` and writes `/output/answers.json`; outside it, set `MAKEFUN_INPUT_DIR` and `MAKEFUN_OUTPUT_DIR` to use other directories.

---

<sub>Prepared for [make.fun](https://make.fun/?ref=vyxz3tbw&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
