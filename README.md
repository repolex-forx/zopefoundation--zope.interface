# Repolex Knowledge Graph of zopefoundation/zope.interface

RDF knowledge graph data for [zopefoundation/zope.interface](https://github.com/zopefoundation/zope.interface), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/zope.interface
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c220969089921d58d24df3eb3e1588f75bd6c12a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c220969089921d58d24df3eb3e1588f75bd6c12a
│           └── chunk-001.nq.gz
├── blob
│   ├── 046cb6a827849c5e1b7c9edb0f5ec93c4e29df77.nq.gz
│   ├── 064647409c780db97a74bc4ce1d22ef78adbe572.nq.gz
│   ├── 0830b4d379bb7a596e19fd18bb223bbf0e0bbe4d.nq.gz
│   ├── 0898a04dcf467d2a74e331495cd5c83690f3ab6a.nq.gz
│   ├── 09a8de8522b559c5bf30958f0fb9bae135394b51.nq.gz
│   ├── 0da200ebedbb96c95d9f9fa3b22e58fff1c8d051.nq.gz
│   ├── 0ee017345d463193134c597b8040c4c7bd766931.nq.gz
│   ├── 1743f56c5566a77bfe6f49401e5184bdb26b8637.nq.gz
│   ├── 174a8e7ad13ea5a1faa6687a00e587853f6e5188.nq.gz
│   ├── 1bcb28abca0cc54b8aee23fba09c2405936db4a5.nq.gz
│   ├── 1ce44e0f5d3fafdd023aff08028120856e70a3b3.nq.gz
│   ├── 243dc9a1f0f5b62491bef40455528e60f48bc9e4.nq.gz
│   ├── 24b2606e80ddc75b3b06b50eed4a2b54b957efd4.nq.gz
│   ├── 256ddc9178dff56a2c4dbca5dc638ed56ccc4f65.nq.gz
│   ├── 2b8e7eb45bf21cdc5febe09bcbd45dafbdb88fb9.nq.gz
│   ├── 2c8657453f67881c12ef1518a7fb7a0bde65dc69.nq.gz
│   ├── 3455c445f8c0ff318e10402e9e9075c8a0afff45.nq.gz
│   ├── 36d1d3fddddcfbe9f9f95a34f186fbeaf564e4fc.nq.gz
│   ├── 37250377205234ea9114f82df6561eb3e3d56e06.nq.gz
│   ├── 380329532b165bb76475a3d3b801f32bfd426108.nq.gz
│   ├── 384b033eeb6914a48793879560da82ff7773bc3b.nq.gz
│   ├── 3b88f9f95feafc5539d8d42c6c83a4aabbf2f0b0.nq.gz
│   ├── 3c764392833a00f0a6bccc7ba029e13ef8a25ddc.nq.gz
│   ├── 3ca14ae275126a63e06c3b18fab110536611f951.nq.gz
│   ├── 3e1ecf87a7485aa45fc30ffa9d827156b9c4d5b4.nq.gz
│   ├── 457ceb4bf4bd237480dd96275a9fba91eca8d62f.nq.gz
│   ├── 47e3a65565b06a0554847086f986bb4f0af01f33.nq.gz
│   ├── 4e86514a1a1ba27f8f6e79ddc9bf792ad6da5093.nq.gz
│   ├── 50c88550f8a74d72ee2b5c3bf4708ca63a514b6f.nq.gz
│   ├── 5233e49b16447a0539214c16e7b9d2e9b2da0574.nq.gz
│   ├── 583bb291965ae9567d9a00df392b9332fe3dc1cf.nq.gz
│   ├── 5aed1b50145e5598c12afa52f157f0c4541d3db8.nq.gz
│   ├── 5bee470be3c5cd2c5ada5d3eb5b01640f3f2a29e.nq.gz
│   ├── 616c2dcbcea6a4e9a0a72283a30c8615618ef113.nq.gz
│   ├── 67d14487a90977dea085288294d24b3e4d7e25f8.nq.gz
│   ├── 6b20e09d324ef4ff2cfcd26a994efea380912c3a.nq.gz
│   ├── 6da620bc4e10d297328a8ffa75823a8f4fe2293a.nq.gz
│   ├── 726696664e7591cd6e9338a03f7251ccd1bb9e91.nq.gz
│   ├── 72684bff061d49f623cf6d6a1e27f1d9c41acbc7.nq.gz
│   ├── 745ad296e30a0d22340603818a7c42d1882dfbbf.nq.gz
│   ├── 75090d29724e160df07ffd3bbeb58c3f41af1d1b.nq.gz
│   ├── 77f3c744e601e8cdd746df3914bf9c9c8ea5365f.nq.gz
│   ├── 7855ce7daecd822d24905390bdb1cc31ab1e7a5c.nq.gz
│   ├── 78609a5f5a06dd7d09bef2926810c672a193b0a1.nq.gz
│   ├── 7cf3afdefd226f4c2561f625fc2f06d55daaefd3.nq.gz
│   ├── 825c578920521df13629c7ff4df06a05b09b04df.nq.gz
│   ├── 82b175a878d3a3e5ab6aac92c8774831a27f4c1a.nq.gz
│   ├── 8688939dbf1cc66c4ed294ca2d61219deaf1e232.nq.gz
│   ├── 8998e46e1f64a6c9a5c453fce348c15572c496a5.nq.gz
│   ├── 89f1ba8034c30591552287bc408d584d13971f8d.nq.gz
│   ├── 8ec85f80e828897c370cf387fa1b16dffc647a12.nq.gz
│   ├── 907579582286b12ddeb2576ea88fd2f424071f76.nq.gz
│   ├── 937695520dc9158ec75519a271433930faced186.nq.gz
│   ├── 9550daa1e4240d1b92a5d218516fd0d5a8a44bbd.nq.gz
│   ├── 9612b6f78416085b83559e6f25db035da8da2815.nq.gz
│   ├── 991e92e172b723a7ebd61e6f5f8ae820f178c117.nq.gz
│   ├── 9bafeb58428a8176559fe0cd83c5b56cf7dd58c9.nq.gz
│   ├── 9e543c83f5bdf0832196d7b512c81c0fb60d0ca4.nq.gz
│   ├── a1006493afaf00cb246af9bd1fd8b7184cbb006c.nq.gz
│   ├── a149072c467b39dba5b39be85ccc50b5ecd1da11.nq.gz
│   ├── a2cb86b7815a46230d98d687026d567e349ab2bc.nq.gz
│   ├── a35c3f90c1a6c4827c5330ec5db96263df6582dd.nq.gz
│   ├── a4a38a1803b01f191c832128836e48861d4a3612.nq.gz
│   ├── a6c57f5fb2ffba0a6af4278619c2983394d237cc.nq.gz
│   ├── af6d0e9dc484a4f7ff57b421ac6ffd65b62c5927.nq.gz
│   ├── b385beb287a48aebe588b5a052987a7909870877.nq.gz
│   ├── b47b3b5abac6a22df0f55eeda72aa1d0f87633c4.nq.gz
│   ├── b8581dd898cbb33e63961b4d181ff0ffbe5d03ee.nq.gz
│   ├── b86fb1e04c7c7ab2f2e900c445ed6171c8329c6f.nq.gz
│   ├── b93f9912fb89fbca705524a1608481faca4a44c0.nq.gz
│   ├── b9bfd40580b3f982550610b51ae097a72f003cea.nq.gz
│   ├── ba8586819a5519ead42e2bf9ee8a2010012b92d4.nq.gz
│   ├── bab7f94be5ef86cce49612e6cdab326a57143d7d.nq.gz
│   ├── c63f5a477ac1f6f01121dc40da1233c637ca8c29.nq.gz
│   ├── c97b10c3a829acdcbef27c54da0bb821978ed2ff.nq.gz
│   ├── ca9f0e1e6415b826a7e837806b8ef7a557e57565.nq.gz
│   ├── cc86fec927d873125bec82a4f05b9af8c4791e98.nq.gz
│   ├── d2f22a5310f8e07ba047f02bd2cd76b07b4845bd.nq.gz
│   ├── d34ea74bce1ee2c73fd48c4c4712c4c05562c19a.nq.gz
│   ├── d8ea0748268153e912c6441d4a73a7875dcab7c5.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── db0445f4683d6993a1c76148874ee2fa50824804.nq.gz
│   ├── defa8a15b949d10b2d691feb7f268889d3b2fb12.nq.gz
│   ├── e14e6e51797f60d31b1b58d75998c0b37cc0b231.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e62eec2685820226d926dae3ba92518b526a522e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e86bb0827e323a682b909b67cb9f905a58d95799.nq.gz
│   ├── e8a18e905dcbe1c9011369bd2a738300fe645510.nq.gz
│   ├── ea77bff52c31b6efd2a0fc6e425e132676fc1f68.nq.gz
│   ├── ea90732ceca20f4cfa7f79e3f7e32d2f6d04a005.nq.gz
│   ├── f14192a02536c874dfcecaf1668a8b5dca3058ad.nq.gz
│   ├── f18b7b9cb9f39ff24effae6e7ac12381407061ed.nq.gz
│   ├── f28e3eb615ef4405e74ab72e63d4a9f232895068.nq.gz
│   ├── f577d42ab803646f7b9cedd34914619f7dd8033e.nq.gz
│   ├── f58e32a6aac9dfa1c472a652382b766ce186a71f.nq.gz
│   ├── f59869c255b49170222eb086ceeed0d26acbc051.nq.gz
│   ├── f70a53099907d699b6054ed7f77c454c836aad68.nq.gz
│   └── ffee6a163301e8ce55668b2a9bbe412f51a594fd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c220969089921d58d24df3eb3e1588f75bd6c12a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 107 files
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

[zopefoundation/zope.interface](https://github.com/zopefoundation/zope.interface)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
