[![One-Line Laugh-Off](https://make.fun/badge/u-zkhiel-one-line-laugh-off-714618ae.svg)](https://make.fun/bounty/u-zkhiel-one-line-laugh-off-714618ae)
[![Rank](https://make.fun/badge/u-zkhiel-one-line-laugh-off-714618ae/tunnelmoon/u-zkhiel-one-line-laugh-off-714618ae/rank.svg)](https://make.fun/bounty/u-zkhiel-one-line-laugh-off-714618ae)
[![Reward](https://make.fun/badge/u-zkhiel-one-line-laugh-off-714618ae/tunnelmoon/u-zkhiel-one-line-laugh-off-714618ae/reward.svg)](https://make.fun/bounty/u-zkhiel-one-line-laugh-off-714618ae)

# One-Line Laugh-Off

Entry for the [One-Line Laugh-Off](https://make.fun/bounty/u-zkhiel-one-line-laugh-off-714618ae) bounty on make.fun.

The line:

> I tried meal prepping. Day three, the Tupperware unionized.

`main.ts` (Node 22, stdlib only) validates the line against the gate (1 to 200 characters, single line, not only white space) and writes it to `(MAKEFUN_OUTPUT_DIR ?? "/output")/entry.txt`, then verifies it with a round-trip read-back check.
