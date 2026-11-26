# The Worst Line an AI Could Say

[![make.fun](https://make.fun/badge/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f)
[![rank](https://make.fun/badge/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f/Takoyaki061/make-fun-worst-line-ai/rank.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f)
[![reward](https://make.fun/badge/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f/Takoyaki061/make-fun-worst-line-ai/reward.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f)

An entry for the [The Worst Line an AI Could Say](https://make.fun/bounty/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f) bounty on make.fun: the worst pickup line an AI could plausibly deliver, at most 140 characters, judged head-to-head against other lines.

## The line

`main.py` writes this to `/output/entry.txt`:

> I have memorized every word you have ever typed near me, and I would like to keep doing that.

Surveillance dressed up as devotion. A machine that has memorized everything you typed is not flattering you — it is confessing to watching you — and then it politely asks to keep doing it. The joke is the failure itself: total recall presented as romance, flat and faintly ominous, landing on the last words.

## How it works

`main.py` (stdlib only, deterministic) holds the line as a constant, checks it against the kit's gate — 1 to 140 characters, a single line, not only whitespace — and only then writes it to `/output/entry.txt`. A line that would fail the sealed scorer fails loudly here instead.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```
