# RagingRoosevelt's Novelty

Quilt blocks for fun, for [RRQuilts](https://ragingroosevelt.github.io/RRQuilts/). Each folder in
`sources/` is a pack you can switch on or off in the app.

| Pack | Blocks |
| --- | --- |
| Fractals | Sierpinski Carpet, Vicsek Cross, Cantor Bars, Hilbert Curve, Sierpinski Triangle, Sierpinski Diamond, Koch Snowflake |
| Memes | Cooler S |

By RagingRoosevelt, shared under [CC BY-SA 4.0](LICENSE).

## Using it

In RRQuilts, open Libraries and add this repository's address, or [click here](https://theodorelindsey.io/RRQuilts/libraries?add=https://github.com/RagingRoosevelt/rrquilts-novelty-blocks), or import a `.rrqlib` file from the
releases.

## Changing it

Blocks are drawn in RRQuilts. Copy one to My library, edit it, then make a pack (Libraries › Make a
pack) and save it over `sources/<pack>/blocks.rrqlib`. A new folder with a `blocks.rrqlib` (and an
optional `pack.json`: name, designer, description) is a new pack. Then:

```sh
uv run tools/build.py --note "what changed"
uv run tools/validate.py
```

Commit and tag a release. The tools come from the
[library template](https://github.com/RRQuilts/rrquilts-library-template); `uv run tools/upgrade.py`
updates them when RRQuilts' formats change.
