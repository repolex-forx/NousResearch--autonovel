# Repolex Knowledge Graph of NousResearch/autonovel

RDF knowledge graph data for [NousResearch/autonovel](https://github.com/NousResearch/autonovel), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download NousResearch/autonovel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d165f267a0ffd34f3b0a70a8a72ac38cb8e4a542
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d165f267a0ffd34f3b0a70a8a72ac38cb8e4a542.nq.gz
│   └── repolex
│       └── d165f267a0ffd34f3b0a70a8a72ac38cb8e4a542
│           └── chunk-001.nq.gz
├── blob
│   ├── 0f8ca0d0ac2c3355edb10cd1a26e5ee8d192b093.nq.gz
│   ├── 10837d9c6b28aee8105e4a64964ba309ee7624cc.nq.gz
│   ├── 15ac1898f5ba4c58a8da92d4a415dad5d82154e5.nq.gz
│   ├── 181c1daa1a6e817ef7e466e5c7dbee72af729766.nq.gz
│   ├── 18826a2087ef133565814468b5722505a75728a0.nq.gz
│   ├── 1c5dd12ff7cf0ad19bf9c8c87910ddd1760a00af.nq.gz
│   ├── 1ccf65ac1316a2c98b87792257f49053c7da9738.nq.gz
│   ├── 21b9f0f9978b701ba46c23df2e8b53e211b0465d.nq.gz
│   ├── 22009f35430b0b00145abaf3479200f12085ea25.nq.gz
│   ├── 24725df99a6869e3bc50d37244542f6d75633ae6.nq.gz
│   ├── 3038aa63bfae0649e396645fb9cedec5624668a9.nq.gz
│   ├── 34e2b7bf6d42331b57ebcffde857ec5426e5a274.nq.gz
│   ├── 3c5d1309ab5280b251ad3f9617d2f8afb093c97f.nq.gz
│   ├── 48dc7eccfac226a6dc39ebcbaba4483a76261b11.nq.gz
│   ├── 5065872c4c46d7d8306217860588049474bf2d95.nq.gz
│   ├── 507c51aeee473512eacbb08f497e8ba5313372fc.nq.gz
│   ├── 5090c5f3cf8e9fa9fab90045ae8a019aa0e22bbc.nq.gz
│   ├── 514bfd40d88a1379791cb7c8c5a9fba4cae062a8.nq.gz
│   ├── 5a46d387766f264b2fbb68cb3901446940fee8fc.nq.gz
│   ├── 5a6eff022ccce634cfe425e2f3465baa6a6a790d.nq.gz
│   ├── 5c20ec64d17f640dc6707779690d79ad5e16f94a.nq.gz
│   ├── 5ce88b788d244d0903ad4f6e0174acbf2ef64de5.nq.gz
│   ├── 5d11fa903c66b1846a34abac48f5f6764a0d08b3.nq.gz
│   ├── 5db65ddf9d0816f509f24b081f8292da319489db.nq.gz
│   ├── 60f05b47166254e00942cc07bc13bab85ca63e28.nq.gz
│   ├── 6416d38c7a886ac13dfbde35f81e1bdce8d0d141.nq.gz
│   ├── 6663c1771579262e16108168a8c53bc87c9ccfbf.nq.gz
│   ├── 666c6d911ccbce5e7dacb0337f9a1c19850a4df5.nq.gz
│   ├── 675af8514f8997a5785f394cbb2d1a7bab20dd5b.nq.gz
│   ├── 6927b53a7c718444591d3bc2a9735b64914539ba.nq.gz
│   ├── 7480f3c47e4c6ff531151d974e14df29f482abf7.nq.gz
│   ├── 7c969773cb78976a3ffe31cb03dbc5d1584ac1af.nq.gz
│   ├── 7ead5c2b7e09c9c67d941a2c131c29ad32ddef69.nq.gz
│   ├── 813bd367a40e4617286a5161ce77f1e8d66f4d75.nq.gz
│   ├── 82e2745f33405f7a0c6e7abd5b59f425dc0f75ff.nq.gz
│   ├── 876e47c014cdce833102cef94c324dbdec32ccb4.nq.gz
│   ├── 9017f87cbf53c02564e729b338bfc92500c0fde2.nq.gz
│   ├── 927563b3960b869463dd824ea811546f6f20e41c.nq.gz
│   ├── 9bac5cdca7e6f5ab9602759d66766bdfbc302240.nq.gz
│   ├── a04848c74a646101e90ba0e855220649d0fffb29.nq.gz
│   ├── aa3b07c92a4e6db1efb38d0dd36d137a9a0d7450.nq.gz
│   ├── ad043eb23a091317e21262eff7f7467786177bc0.nq.gz
│   ├── aef01f3272ba9a9f41e29fa96e20f5e1da77d3ae.nq.gz
│   ├── bb0d6d48530a4fcd9cc5c43ed828be5ae8a44ed9.nq.gz
│   ├── bf700a0dad7b32183dea579ac4ba314fdfae8c08.nq.gz
│   ├── bfbfc6e21cfd819cc187d6fd47800fe5681338b8.nq.gz
│   ├── bfd2cf2874851bb8c7bd7f7e7345c6eecfa4a789.nq.gz
│   ├── d581c2dc4dee634f82b7adb0ae280ba4578f0604.nq.gz
│   ├── e4fba2183587225f216eeada4c78dfab6b2e65f5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb4915734de0f259a5863d3dbc1b984a138ec00b.nq.gz
│   ├── ef1e96f7c13a72c73c9888ceff98e689ba04fe04.nq.gz
│   ├── f6381881fcb76ecd212af20f22fb0c18282c8fe1.nq.gz
│   ├── f6bd1a8c7908b0782a05117c361617c7ef916a63.nq.gz
│   ├── f7b738cb0c6c10cc80b9d19aef4292f54cc15511.nq.gz
│   └── fc8747c177c568742b0d2ea6245fc78593a55b21.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── d165f267a0ffd34f3b0a70a8a72ac38cb8e4a542.nq.gz
├── filetree
│   └── d165f267a0ffd34f3b0a70a8a72ac38cb8e4a542.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 66 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[NousResearch/autonovel](https://github.com/NousResearch/autonovel)

---
*Parsed on 2026-10-04 by [repolex](https://repolex.ai)*
