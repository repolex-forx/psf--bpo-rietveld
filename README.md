# Repolex Knowledge Graph of psf/bpo-rietveld

RDF knowledge graph data for [psf/bpo-rietveld](https://github.com/psf/bpo-rietveld), parsed by [repolex](https://repolex.ai).

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
rlex download psf/bpo-rietveld
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 636b94cf7326d6ee39eada8d114f2fa0c5e13173
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 636b94cf7326d6ee39eada8d114f2fa0c5e13173
│           └── chunk-001.nq.gz
├── blob
│   ├── 03edd3a5c7ad69080c45c45bf4cb2505908446e3.nq.gz
│   ├── 04e27709749047462eb171b1560761f467ccc173.nq.gz
│   ├── 057a0f33bcc79671f3dddb75b7169c0b67854217.nq.gz
│   ├── 085ccaecaf5fa5c34bc14cd2c2ed5cbbd8e25dcb.nq.gz
│   ├── 08e79e0efcafb370fa1b5bc65e4636fc5c746a96.nq.gz
│   ├── 0905bce88c464910cb02475be07fb4ce3f6366a3.nq.gz
│   ├── 0c8cebcfaa94f4adeb96599ae6b3b0603a0fb539.nq.gz
│   ├── 0f5a1fa4cccb6330a5833d5642fe93425afb33cf.nq.gz
│   ├── 0fef73a90b53b717386abd312c793b307a9ca5ea.nq.gz
│   ├── 1cda9a53dc357ce07d3c67051b7615ebf7dc2f64.nq.gz
│   ├── 1df133a59119142396f0ed5b46252b0e1cc3a836.nq.gz
│   ├── 22a61359658d6936a31a7b6f3a6b508f5a6806d4.nq.gz
│   ├── 271014a2b7a4160e97eb024f520325cc32e2461e.nq.gz
│   ├── 28364be7727aab048fd26f284776a9789f628cb6.nq.gz
│   ├── 2e2dfc487a81a3e5a070ce836356eb26b9b48459.nq.gz
│   ├── 2fdcd7ac88451b80761c5c26a739d1eee320c2df.nq.gz
│   ├── 3cbb5950fcf1a6f953b6994c6cbcf692e58ede76.nq.gz
│   ├── 400531a2db11563e3961282a223f19f614c511eb.nq.gz
│   ├── 4ccc90157f0eedf741229cf5198c9a8edbee4313.nq.gz
│   ├── 4f964a99bedbaab2a8b49a0954b16f75050f0a6e.nq.gz
│   ├── 535270183eb9607bde3a0592dc9976d07e953253.nq.gz
│   ├── 569a07d85ce1324429bee89efdcff3216a894d8b.nq.gz
│   ├── 57d560c1f65aa23cee0e4aa7e26742627295aae9.nq.gz
│   ├── 58066498f7401372ff161279ca583762b0d6cef0.nq.gz
│   ├── 596b21276ec3302a04584dbc786e707206eca13a.nq.gz
│   ├── 5ad9178f862646253ad5d18226e908932f4f0979.nq.gz
│   ├── 5adb5b2d8a0005b16065f704c643141e903874ff.nq.gz
│   ├── 5df18aecc5ec002f86d412d33e752268c9fbef50.nq.gz
│   ├── 6040a4e4319772776bf4bde945f75a162947f81a.nq.gz
│   ├── 65710613d9ca8704fe07393a0471281f2c7bb0d2.nq.gz
│   ├── 6d1fc45f72f7519f3e8eb1493012b12b22674434.nq.gz
│   ├── 6d4ceb094da41c8a2125ab51b31a6a5ffaff3c8e.nq.gz
│   ├── 732468da2ceb1436bb5263d0226aeddf54bc614e.nq.gz
│   ├── 77619f0dc34e39275b1abfd9d987dda5f1c85013.nq.gz
│   ├── 8064324073a4da24ec82c8fed81d0e6ef5a7b2a4.nq.gz
│   ├── 81e98b900953a1f1714687fe2d4b563e30e2e686.nq.gz
│   ├── 87b0e6512f808d0bc87faa2f8ede485ec5977ebf.nq.gz
│   ├── 8e9dc956eb61f59091396ac6dae72937e7079743.nq.gz
│   ├── 8fb2884ced9fef16f0fce97d8e57da36a4314cb1.nq.gz
│   ├── 907463a1aea80e397244f9d83518468713c03aca.nq.gz
│   ├── 937ec8c4034b01646c35d15dec39e5eef3a50192.nq.gz
│   ├── 956ff931e6840003104742f846e20d90fb3ae507.nq.gz
│   ├── 9ba96f5b06327c967edaa23805682647b61e610e.nq.gz
│   ├── a4551de506e8cff91f0c59c7b5fbba88e3d7704f.nq.gz
│   ├── a8b75a1ff411d9e8a31974f123c8388759444853.nq.gz
│   ├── a90fc9ac6c18658cde210a64a64ce03bd81cecda.nq.gz
│   ├── b4e0833fcc3715afced975504b2385546284a88e.nq.gz
│   ├── bc024d64082c0fda3b41481a2a5eff18ce5923ee.nq.gz
│   ├── bdd2e4f827f736306c9ae38ae1ecead069b63031.nq.gz
│   ├── c4ffe9f403c85e69d1c6ab319046f29637bb748a.nq.gz
│   ├── c67b9a3b26bc3beacc0879d1c8bd24c3e9844731.nq.gz
│   ├── cdbabf7a74c2ea352c1cc179982d4a1a2e6daf38.nq.gz
│   ├── cebe08c98fd372179f4482d7dcdd931454debb37.nq.gz
│   ├── d24b9bedff5b4f215546c4bc46491ea007f85c6a.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d9e63a57544588bad6612e90ef2abeb5689aa959.nq.gz
│   ├── e0d45e8fcdb1d4234d90350a553f1dd771c37098.nq.gz
│   ├── e22bf12c5a2cd9aab9db26f09438421311ce81fd.nq.gz
│   ├── e416558502269560bc0faa9259c8e963002e2a62.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8dc0a3aa2e6a1abfefea1da49f0b114bc1abd54.nq.gz
│   ├── f0451630f14ae816a2bbb265848658e910ffd0a9.nq.gz
│   ├── f181721eaab3af543971e851d4ed3674b5acb7ec.nq.gz
│   ├── f2d89ea2f9a66336962dcb9a9469f0fbf6e23534.nq.gz
│   ├── fbeec5b35905f3143d5a1ccacef5a7686dd52a1a.nq.gz
│   └── fefe684496c15aad47170d016c64dffefa471f80.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 636b94cf7326d6ee39eada8d114f2fa0c5e13173.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 72 files
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

[psf/bpo-rietveld](https://github.com/psf/bpo-rietveld)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
