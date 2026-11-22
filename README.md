# tiny-stack-vm-01

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/xiacai520/tiny-stack-vm-01/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/xiacai520/tiny-stack-vm-01/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

A tiny stack virtual machine for make.fun's tiny stack ISA v1: wrapping
32-bit arithmetic, a 256-value stack, calls, 256 words of memory, input
and output, and all eleven traps with their exit codes. One run answers
every instance: `main.ts` reads `/input/<id>/program.bin` + `input.bin`
and writes `/output/<id>/stdout.bin` and `exit.txt`. Pure Node 22, no
dependencies, deterministic. Practice set: 40/40, score 1,000,000.
