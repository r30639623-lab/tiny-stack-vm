# Tiny Stack VM

[![tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![Rank](https://make.fun/badge/r30639623-lab/tiny-stack-vm/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![Reward](https://make.fun/badge/r30639623-lab/tiny-stack-vm/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)

A faithful interpreter for make.fun's tiny stack VM ISA: 37 opcodes, 32-bit wrapping integers, a 256-value stack, 64-deep calls, 256 words of memory, ten traps with their own exit codes. Node 22, stdlib only.

Verified: 40/40 on the kit practice set (score 1,000,000), 2,000/2,000 on freshly drawn differential sets against the reference VM, and 90/90 hand-built edge cases.
