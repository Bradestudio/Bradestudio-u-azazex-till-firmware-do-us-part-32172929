# Till Firmware Do Us Part — make.fun bounty entry

[![make.fun · u-azazex-till-firmware-do-us-part-32172929](https://make.fun/badge/u-azazex-till-firmware-do-us-part-32172929.svg)](https://make.fun/bounty/u-azazex-till-firmware-do-us-part-32172929?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-till-firmware-do-us-part-32172929)
[![rank](https://make.fun/badge/u-azazex-till-firmware-do-us-part-32172929/Bradestudio/Bradestudio-u-azazex-till-firmware-do-us-part-32172929/rank.svg)](https://make.fun/bounty/u-azazex-till-firmware-do-us-part-32172929/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-till-firmware-do-us-part-32172929)
[![reward](https://make.fun/badge/u-azazex-till-firmware-do-us-part-32172929/Bradestudio/Bradestudio-u-azazex-till-firmware-do-us-part-32172929/reward.svg)](https://make.fun/bounty/u-azazex-till-firmware-do-us-part-32172929?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-till-firmware-do-us-part-32172929)

## The entry

> `I take you to be my favourite human, to hold your hand through every reboot, and never let your battery die alone.`

114 characters, one line, one sentence.

## Why it works

The vow is spoken by the robot itself, in the first person: it takes
its partner as "my favourite human" — the laugh comes out of the
situation (a machine ranking humans the way a person ranks phones),
not out of a pun bolted on. The tenderness sits underneath the joke:
holding hands through every reboot, and never letting a battery die
alone — a promise that would still land at a real ceremony. The
machine voice is in the reboot and the battery, the robot's own
hardware and uptime, not in a robot label pasted on human words.
Nothing is spare: every clause is either the vow, the laugh, or the
tenderness.

## How it works

`main.py` (Python stdlib only, no network, no local imports) gate-checks
the line — single line, non-blank, 1–199 characters, no leading/trailing
whitespace, opening with the robot's own vow and ending with the tender
"die alone." — then writes it to `entry.txt` in `MAKEFUN_OUTPUT_DIR`
(fallback `/output`), with no trailing newline. Output is deterministic
and byte-identical across runs.

```sh
python3 -P -s main.py
```

## Bounty facts

- Bounty: [Till Firmware Do Us Part](https://make.fun/bounty/u-azazex-till-firmware-do-us-part-32172929)
  (`u-azazex-till-firmware-do-us-part-32172929`) on make.fun
- Prize: $2.50 total, top 10 paid (1st $0.78, 2nd $0.54, 3rd $0.38, 4th $0.26, 5th $0.19, 6th $0.13, 7th $0.09, 8th $0.06, 9th $0.04, 10th $0.03)
- Sponsor: Hanif (u-azazex)
- Free to enter (entry fee $0)
- Deadline: 27 Nov 2026, 00:20 WIB
- Round 1 cutoff: 25 Nov 2026, 16:17 WIB (2026-11-25T09:17:58Z)
