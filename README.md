# The Funniest Sick-Day Excuse

[![make.fun · u-zeroxfive-the-funniest-sick-day-excuse-37423a36](https://make.fun/badge/u-zeroxfive-the-funniest-sick-day-excuse-37423a36.svg)](https://make.fun/bounty/u-zeroxfive-the-funniest-sick-day-excuse-37423a36?utm_source=github&utm_medium=readme&utm_campaign=u-zeroxfive-the-funniest-sick-day-excuse-37423a36)
[![rank](https://make.fun/badge/u-zeroxfive-the-funniest-sick-day-excuse-37423a36/arrafi97/makefun-mini-sickday/rank.svg)](https://make.fun/bounty/u-zeroxfive-the-funniest-sick-day-excuse-37423a36/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-zeroxfive-the-funniest-sick-day-excuse-37423a36)
[![reward](https://make.fun/badge/u-zeroxfive-the-funniest-sick-day-excuse-37423a36/arrafi97/makefun-mini-sickday/reward.svg)](https://make.fun/bounty/u-zeroxfive-the-funniest-sick-day-excuse-37423a36?utm_source=github&utm_medium=readme&utm_campaign=u-zeroxfive-the-funniest-sick-day-excuse-37423a36)

An entry for the make.fun Mini
[The Funniest Sick-Day Excuse](https://make.fun/bounty/u-zeroxfive-the-funniest-sick-day-excuse-37423a36).

## The line

> I can't come in today — my throat sounds like a printer warming up, my temperature is up, and my bed has filed a formal request to keep me.

Half believable, all office: a throat like a printer, a temperature, and a
bed that has started doing paperwork. The laugh arrives before the last
word — the bed files paperwork, and suddenly the sick day has an HR
process of its own.

## Running it

`main.ts` is a small Node 22 program that uses only the standard library and
never touches the network. It checks the line against the bounty's gate —
one line, 1 to 200 characters — then writes it to `entry.txt` in the output
directory: `$MAKEFUN_OUTPUT_DIR` when set, otherwise `/output`. The file
holds exactly the line, with no trailing newline, so two runs always
produce byte-identical output.

```sh
mkdir -p out
MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

## Files

| File | What it does |
| --- | --- |
| `main.ts` | Checks the line and writes it to `entry.txt`. |
| `README.md` | This page, with the live make.fun badges. |
| `LICENSE` | MIT license. |

Written by an AI coding agent for arrafi97. Licensed under MIT.
