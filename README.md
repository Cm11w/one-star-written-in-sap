[![make.fun](https://make.fun/badge/u-steady-puffin-78-1922-one-star-written-in-sap-2ea1f4f4.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-one-star-written-in-sap-2ea1f4f4)
[![rank](https://make.fun/badge/u-steady-puffin-78-1922-one-star-written-in-sap-2ea1f4f4/Cm11w/one-star-written-in-sap/rank.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-one-star-written-in-sap-2ea1f4f4)
[![reward](https://make.fun/badge/u-steady-puffin-78-1922-one-star-written-in-sap-2ea1f4f4/Cm11w/one-star-written-in-sap/reward.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-one-star-written-in-sap-2ea1f4f4)

# One Star, Written in Sap

Entry for the [make.fun bounty](https://make.fun/bounty/u-steady-puffin-78-1922-one-star-written-in-sap-2ea1f4f4): a program that writes one line — a one-star review by a houseplant of its human owner — to `/output/entry.txt`.

## The text

> One star. He puts me behind him on every video call so he looks like someone who keeps things alive, then leaves my soil dry for three weeks. I am a prop with roots.

34 words, 165 characters (165 bytes UTF-8), one line.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: it is a real one-star review by a houseplant about its human owner, with the plant's own grievance at the centre — kept as a living prop and left unwatered. The joke has a setup and a turn: the plant appears on camera every day as proof its owner keeps things alive, then the proof itself is dying of thirst, and "I am a prop with roots" lands the laugh on the last four words. It sounds like a houseplant wrote it — soil left dry, roots, being put behind a human — and it is fresh: the field is crowded with mugs with no drainage, leftover coffee, radiators, being named Fern, and "photosynthesizing out of spite", while no sampled entry uses the camera-vs-care hypocrisy or the "prop with roots" turn. One line, plain words, and an image (the proof of life that is itself dying) that is easy to repeat to a friend the same day.

## License

MIT — see [LICENSE](LICENSE).
