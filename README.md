# Repolex Knowledge Graph of astropy/ccdproc

RDF knowledge graph data for [astropy/ccdproc](https://github.com/astropy/ccdproc), parsed by [repolex](https://repolex.ai).

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
rlex download astropy/ccdproc
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6bab63d0b98f85eab0b4f9e1cbc1ef28087cb7ad
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6bab63d0b98f85eab0b4f9e1cbc1ef28087cb7ad
│           └── chunk-001.nq.gz
├── blob
│   ├── 030f7ab01f319df6201c441418c12be41070bb37.nq.gz
│   ├── 03f4d86327483bdabc8fc9397cc7b68aead9ed26.nq.gz
│   ├── 0548a488403d765912980acf792a3aab747d38bc.nq.gz
│   ├── 059d98d8bd4c3d468e41675a5db504826f440d6e.nq.gz
│   ├── 0fa59f28180b7e104f894478f79eb423811c583e.nq.gz
│   ├── 136a946807a927492b57fc15dc45c5967900b4bd.nq.gz
│   ├── 157c193b142e2784c55cd77b0e8fefbb32e4749d.nq.gz
│   ├── 16217194a93a6d51c2c53697c949abd48515c84a.nq.gz
│   ├── 16a1f370f095bb0e8425fafe3192b89ee7337220.nq.gz
│   ├── 16ff9f616749d860e3f887768f9fa6befd30b979.nq.gz
│   ├── 17fbd9270765bc290c1d8f59d9a0c61f5c0e1ae3.nq.gz
│   ├── 197c01f93cdd3004d434d2457f4c92ee402b7ee7.nq.gz
│   ├── 19905a3cf847d0ee320a765e394f548ca2a3f04e.nq.gz
│   ├── 19c939cb09098dc40c59d0e2b03a4e7077fdecaf.nq.gz
│   ├── 1a7ce5b39f5a4e0bde4a231c06f355a698e01468.nq.gz
│   ├── 1e56b709b7ee91ea0159d015669936129dbad877.nq.gz
│   ├── 20b0c8a6f9f1e51eb3e24b0a280ef7abebbb3690.nq.gz
│   ├── 230cd6e20ddda4a66b501be05af441ced411c102.nq.gz
│   ├── 236ce420e0c1a93c125fc8a19cfe716dd4a0ef6d.nq.gz
│   ├── 27cd1b70830571e1187b2ddc11a78967f663cbe7.nq.gz
│   ├── 27e7401f30797069b2f1e0c358631ebf668c5493.nq.gz
│   ├── 29b13902eff676a85076d6388c86c2102d1bfe0d.nq.gz
│   ├── 2eedf9428d66bfe8518da6b5a22a470553a1c3f1.nq.gz
│   ├── 2ff7e2a6b3f5fd926a79e1a55871d18657ecc96a.nq.gz
│   ├── 3003521f5d4623589b5b44022b4b1d7345e2d8bb.nq.gz
│   ├── 301adcb09034711e12d6f398beed47423ab161e5.nq.gz
│   ├── 30f4acc8fd57f6170d9d86bf603f85e9ed948dcc.nq.gz
│   ├── 31349f6dccd37687e8fbea6e6a1a65b6e91f5278.nq.gz
│   ├── 3492498b676ec9e2d301e8de62ce83f3ec11e6f8.nq.gz
│   ├── 37a9b11176f5eec289f9ac862dadf29fe4da5d4c.nq.gz
│   ├── 3d98934b6d020d10194f3d7b7cc3886519b3c4ac.nq.gz
│   ├── 3ecab8142876a3c16483c818d7a6794ff70b2744.nq.gz
│   ├── 41d4d3ff0f42210d367c53d390a4812cfe4e189d.nq.gz
│   ├── 434ad4ea81d7eeb5bf357528775825362b787e30.nq.gz
│   ├── 437612610db96c19297cef1b42e823055d4f4183.nq.gz
│   ├── 43e7424f276a51e3ab00133407641023098a5b2b.nq.gz
│   ├── 43f8f9e311e1e1a19721d1f0716e439beb2087a3.nq.gz
│   ├── 4495bc486964f85e414cb933298a44d6f9276e70.nq.gz
│   ├── 45ee10fe8cdd27ef40881bad05cba564844232ec.nq.gz
│   ├── 48f14a994422374ffb6cc12aca5756c822e43a2b.nq.gz
│   ├── 50e39532758f5e2478de337df88bf771f5b7b925.nq.gz
│   ├── 54fd6a9d6fd9dc7f4dbc49cef53fde2ef276ff0f.nq.gz
│   ├── 5835a6271bfd2c82f378859b3299a907413c8119.nq.gz
│   ├── 5c8395e5631000dc11cc752d5268cafcab4083fe.nq.gz
│   ├── 5cfcaebcc02d48ac3368165b0d453d73db5af4d9.nq.gz
│   ├── 5d85b69c519fee4f99c408c29350a1647fbd204d.nq.gz
│   ├── 5e378a896f4ee57b3ac084b10ff761b7ab268a4f.nq.gz
│   ├── 5ec8676eca267ad5ba1150abe699dbf283377784.nq.gz
│   ├── 5f937f87ce44a46370cd45081a8192bbad91f2d3.nq.gz
│   ├── 65a535a48df0005ad096c57a5405d3a3e9243ea7.nq.gz
│   ├── 67a9169b5eb855d4ceaa9d85405bc6c0b99cc2be.nq.gz
│   ├── 68630fe7f9399c094dc6f12ea0cd0f90d1da5e83.nq.gz
│   ├── 6ad7471a025cd582743631ba3ac7d13ba72093be.nq.gz
│   ├── 6bc5ed0a79f18326631c9d200e5a72bf6edd293d.nq.gz
│   ├── 6c46d361a3f3ab7f0997572af2fee3910bc6c489.nq.gz
│   ├── 7d0398121f89bf5fe0856a85f24f90405b448258.nq.gz
│   ├── 7df3795d0af630373fe99151858b237918f71a8d.nq.gz
│   ├── 81104753f3f6f7d02d4f4dce778de3f1535f2bde.nq.gz
│   ├── 8715927c61b59ea52053914fc3548a813bfd15ec.nq.gz
│   ├── 87407921c16273207e874f1941b83c9fd6b3d787.nq.gz
│   ├── 8df1addfb0c186ba7922170f717580bc7450ed92.nq.gz
│   ├── 91e2209b27e2a177dde97fec7bb8271c5293eb74.nq.gz
│   ├── 93dfe92b9c98e009c2f75b6477817411d3a15585.nq.gz
│   ├── 956c3c6c176f9c017ab07687e432182e7aee318d.nq.gz
│   ├── 9594d14b7658994ec114bfc1679a7faba8c8cb93.nq.gz
│   ├── 98595164e4c737cbb9a173a524c473f4110d0dd3.nq.gz
│   ├── a09bd5b61a73bc946663d8fb522cd993110ff3ed.nq.gz
│   ├── a135e0bb4a200b5caa8dd564230678b3e24c0f14.nq.gz
│   ├── a2bda4f9be37233eb9dc67b6c541bc6fec862b07.nq.gz
│   ├── aa2715365f099d60ec51a93633a25f7ba58ac571.nq.gz
│   ├── ae2dc9f804c8c91494abd37c12d27a6a8f2e177e.nq.gz
│   ├── b5213d335a8261c022d0bd247fa267ee92777215.nq.gz
│   ├── b6212d937b48aaf1bbb8f90838752cb143e209a2.nq.gz
│   ├── b6dae5eac8e8f70a97e8fb2d20fb5db22680852b.nq.gz
│   ├── b7a93af58b4753ddfcd85767955a13c3db441c53.nq.gz
│   ├── b87e13b2971f1f4de2716912b639c25969673599.nq.gz
│   ├── c1a59c34cef2d372b9e79d30ebc1884d4251ca67.nq.gz
│   ├── c37cdd1d3a232ed5a2f6ea3cfa6122d381a0aaee.nq.gz
│   ├── c4fdb9e563d4f76274c6947e633a107e781f3eeb.nq.gz
│   ├── c750873c053cca6585dfb30e75d26e02aeb9b56b.nq.gz
│   ├── c7979506d6bfcb9819fad6b4955ee871e08eb175.nq.gz
│   ├── cfd5c9789813b3d909d3e2e28de65250b8d91fc6.nq.gz
│   ├── d157139a6c6fa598868ea9c86b739e9b19cddb3a.nq.gz
│   ├── d353d766bebc3b12eeca6c4bad1ce43adf33f20f.nq.gz
│   ├── d5064c9773ebc5f1ef03fde234e95bae1328e684.nq.gz
│   ├── d72d30d5532ef5e6523ae4e11f68e793695a2002.nq.gz
│   ├── dd4e1266cb60bf411c032a6febc4cf72c969fd4f.nq.gz
│   ├── de641a21006407bcac178462eec58fb24f142875.nq.gz
│   ├── e3c53d1318f42d7859f1aeb2fa9ef3bda78ca00f.nq.gz
│   ├── e6981b2c5c511aa70f267aafea6b150fd9afac57.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8f3df1b68f9ddf1b918091a569503242540ff07.nq.gz
│   ├── ecdbed7dd97139185585c1cc066b05bf76c3525e.nq.gz
│   ├── edbde32486249b81f6e1fffe193f3b4634a6ea17.nq.gz
│   ├── ee99bb3c90d627b9c5973972dc8d447c882d870b.nq.gz
│   ├── f34a16c866ea03974d5fa96b1cfbc84824f89df7.nq.gz
│   ├── f8c244a91349a3bc53f5d969d2e40350b89217d8.nq.gz
│   ├── f94f4971c04a3a93c5f2a01e64bf14e70de2b447.nq.gz
│   ├── fea39a4903d95ced57dc5bf158b32da5c2428bc4.nq.gz
│   ├── fec66ce33637d2935fa387531cc4acdfca55b051.nq.gz
│   └── ffbeae7b693b8990a38b834ade6a97d8a7daaa14.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6bab63d0b98f85eab0b4f9e1cbc1ef28087cb7ad.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 109 files
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

[astropy/ccdproc](https://github.com/astropy/ccdproc)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
