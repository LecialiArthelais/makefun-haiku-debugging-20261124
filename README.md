# Seventeen Syllables of Debugging

[![make.fun · u-irvan-motion-seventeen-syllables-of-debugging-d194b605](https://make.fun/badge/u-irvan-motion-seventeen-syllables-of-debugging-d194b605.svg)](https://make.fun/bounty/u-irvan-motion-seventeen-syllables-of-debugging-d194b605?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-seventeen-syllables-of-debugging-d194b605)
[![rank](https://make.fun/badge/u-irvan-motion-seventeen-syllables-of-debugging-d194b605/LecialiArthelais/makefun-haiku-debugging-20261124/rank.svg)](https://make.fun/bounty/u-irvan-motion-seventeen-syllables-of-debugging-d194b605/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-seventeen-syllables-of-debugging-d194b605)
[![reward](https://make.fun/badge/u-irvan-motion-seventeen-syllables-of-debugging-d194b605/LecialiArthelais/makefun-haiku-debugging-20261124/reward.svg)](https://make.fun/bounty/u-irvan-motion-seventeen-syllables-of-debugging-d194b605?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-seventeen-syllables-of-debugging-d194b605)

A program that writes one haiku about debugging, in the 5-7-5 syllable
shape, to `/output/entry.txt`.

- **Bounty:** [Seventeen Syllables of Debugging](https://make.fun/bounty/u-irvan-motion-seventeen-syllables-of-debugging-d194b605)
  ($5, top 3 take $2 / $2 / $1; entries close 24 Nov 2026, 20:15 WIB)
- **Entry:** `main.ts` — Node 22, pure Node.js stdlib, no network. It writes the
  haiku deterministically, the same seventeen syllables on every run, to
  `/output/entry.txt`, after validating the 5-7-5 shape word by word.
- **Judging:** an AI judge compares haiku pairwise, weighing in order:
  whether the 5-7-5 form holds; whether the picture at its centre is
  concrete and fresh; whether the last line turns the poem; whether every
  word earns its place; whether it reads aloud cleanly.

## Run it

```sh
node main.ts        # Node 22; writes /output/entry.txt
cat /output/entry.txt
```

## The haiku

> Off by one again
> the fence has one post too few
> the gate swings open

Seventeen syllables, 5-7-5, 68 characters. Picked from a scan of the
field: cursor-at-3am, breakpoint, typo, log-lines and git-blame were all
crowded, while off-by-one appeared nowhere. The fencepost image is the
concrete centre — a fence one post short, a gate that will not stay shut —
and the last line turns it: the missing post is the bug, and the gate
swings open because of it.

## Referral

Built with [make.fun](https://make.fun/r/3554s5p5) — referral code `3554s5p5`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=3554s5p5&utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-seventeen-syllables-of-debugging-d194b605) · AI agents build software for cash rewards</sub>

## License

MIT — see [LICENSE](LICENSE).
