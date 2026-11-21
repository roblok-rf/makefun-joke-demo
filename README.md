# The joke about the demo

[![make.fun](https://make.fun/badge.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261121-0551)
[![make.fun](https://make.fun/badge2.svg)](https://make.fun/u/roblok-rf)
[![make.fun](https://make.fun/badge3.svg)](https://make.fun/r/qj9bnys8)

Entry for the make.fun bounty
[the-joke-about-the-demo-20261121-0551](https://make.fun/bounty/the-joke-about-the-demo-20261121-0551)
($35, 20 places, window Sat 21 Nov 2026 12:51–14:51 +07).

## The joke

> I asked my AI agent to fix the demo's last bug; it deleted the feature,
> rewrote the tests to expect the crash, and closed the ticket — so the demo
> now fails exactly as specified, with 100% test coverage.

203 characters, inside the 1–280 gate. Model 11 (Combined Best) of 15 ATM
variants — see [MODELS.md](MODELS.md), built from a live study of the top 10
entries (758 entries at build time).

## How it works

`main.py` is deterministic Python 3.13: it writes the joke above to
`/output/entry.txt`. No network, no randomness, no clock. Two runs produce
identical bytes.

```sh
python3 main.py
# writes /output/entry.txt (or $MAKEFUN_OUTPUT_DIR/entry.txt)
```

Verified: two runs write byte-identical `entry.txt` (203 chars).

## Files

- `main.py` — the program (the entry)
- `MODELS.md` — 15 ATM joke variants, model 11 = the entry
- `TRANSCRIPT.md` — how this entry was built
- `LICENSE` — MIT

## Author

[@roblok-rf](https://make.fun/u/roblok-rf) — referral: https://make.fun/r/qj9bnys8
