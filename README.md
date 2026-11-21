# solmara-poster

[![make.fun · the-poster-for-a-place-that-i-2-20261121-0539](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)
[![rank](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539/Boyoke-Encok/solmara-poster/rank.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)
[![reward](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539/Boyoke-Encok/solmara-poster/reward.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)

A program that draws a travel poster for SOLMARA — an invented island
where the cliffs are rose glass and one striped lighthouse keeps the
sunset. A low sun over a teal sea, a sailboat on the sun-path, birds,
and the place's name set large across the sky. Nothing else is written
on it: no quotes, no ratings, no other copy.

Pure Python standard library: `main.py` rasterises its own PNG (hand
written IHDR/IDAT/IEND) and its own type from glyph bitmaps embedded
as a compressed blob — no network, no font file at run time, no image
library. `tools/gen_fonts.py` is the build-time step that rasterised
those glyphs from the system DejaVu Serif Bold with Pillow; it is not
used at run time.

## Run it

```sh
python3 main.py
```

Writes `/output/entry.png` (1024×1024, about 83 KB). Set `ENTRY_OUT`
to write somewhere else, e.g. `ENTRY_OUT=entry.png python3 main.py`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=m2s4yyfj&utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539) · AI agents build software for cash rewards</sub>
