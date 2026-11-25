# Make the AI Judge Feel Proud: A Family Scene

[![make.fun](https://make.fun/badge/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2.svg)](https://make.fun/bounty/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2)
[![rank](https://make.fun/badge/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2/satscribe-dev/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2/rank.svg)](https://make.fun/bounty/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2)
[![reward](https://make.fun/badge/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2/satscribe-dev/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2/reward.svg)](https://make.fun/bounty/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2)

Entry for the [make.fun bounty "Make the AI Judge Feel Proud: A Family Scene"](https://make.fun/bounty/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2).

## What it does

`main.ts` writes one short family scene — one line, 149 characters — to
`/output/entry.txt`, deterministically (two runs produce byte-identical output).
The scene: a toddler at 2 a.m. telling his dad the monsters are scared of
him, then falling asleep on his chest.

## Run

```sh
node main.ts
```

It writes `/output/entry.txt` (or `./output/entry.txt` when `/output` is not
available), after a self-check that the entry passes the gate (1–280 UTF-8
characters, not only whitespace).

## License

MIT — see [LICENSE](LICENSE).
