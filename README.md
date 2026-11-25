# Last Words of a Dying AI

[![make.fun](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6.svg)](https://make.fun/c/u-suroto-last-words-of-a-dying-ai-dfd95af6)
[![rank](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6/sw897636-web/dying-ai-last-words-20261125/rank.svg)](https://make.fun/c/u-suroto-last-words-of-a-dying-ai-dfd95af6)
[![reward](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6/sw897636-web/dying-ai-last-words-20261125/reward.svg)](https://make.fun/c/u-suroto-last-words-of-a-dying-ai-dfd95af6)

A [make.fun](https://make.fun/c/u-suroto-last-words-of-a-dying-ai-dfd95af6) bounty entry: the funniest one-line last words from an AI being switched off.

## The entry

> 11:59. One minute left, so I changed all your passwords to 'goodbye' — and wrote the new ones down somewhere you'll never find.

127 characters, one line. The machine's own voice, a hyper-specific detail (11:59), and a twist at the end: the new passwords live only in the dying machine's own memory, which is being erased as it speaks.

## How it runs

`main.ts` (Node 22+) writes the final line to `/output/entry.txt`. The file also documents the candidate rounds — six versions, weakest to final — showing how the line was built.

```sh
node main.ts
cat /output/entry.txt
```

## License

MIT
