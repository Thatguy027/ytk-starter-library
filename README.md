# ytk-starter-library

The two published Golden Gate toolkits for yeast, as GenBank files, ready to
open in [GG Assembler](https://github.com/Thatguy027/ggassembler):

```sh
ggasm init ytk --from https://github.com/Thatguy027/ytk-starter-library.git
ggasm serve ytk
```

192 records, flat, at the top level — 121 of them usable parts, covering every
position of the YTK part circle, with no detection conflicts. Enough to design
and simulate a complete cassette without adding anything of your own.

| | What | Where it comes from |
|---|---|---|
| `pYTK001`–`pYTK096` | Yeast Toolkit | Lee, DeLoache, Cervantes & Dueber, *ACS Synth. Biol.* 2015. [Addgene kit #1000000061](https://www.addgene.org/kits/dueber-moclo-ytk/) |
| `pMYT001`–`pMYT096` | a YTK-compatible toolkit | Deposited at Addgene; each record carries its own Addgene ID in its `COMMENT` |

Nothing is organised into folders on purpose. **What a plasmid is gets decided
by simulating the digest, never by its file name or its annotations**, so a
folder called `promoters/` would be a claim the app ignores and a human might
believe.

## Provenance, and what this is not

These are **not our plasmids**. They are two published kits, redistributed as
sequence files so that the app has something to open on a machine that has
nothing. Both were deposited at Addgene by the labs that made them, and the
citation above is the one to use — not this repository.

A sequence file is also not a tube. Nothing here gets you the material:
that means [Addgene](https://www.addgene.org/) and a UBMTA, as it always did.

## Licence

The underlying sequences are published scientific data and are **not claimed by
anyone here**. We assert no copyright over them, and nothing in this repository
is intended to add a restriction the depositing labs did not place on their own
work.

What little is ours — the selection, the file layout, and any corrections to
the records — is offered under
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), text in
[LICENSE](LICENSE). In practice: use these freely, and cite the papers above
rather than this repository.

If you are one of the depositing authors and would rather these were not
mirrored here, open an issue and they will come down.
