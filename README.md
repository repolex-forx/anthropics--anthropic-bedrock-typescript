# Repolex Knowledge Graph of anthropics/anthropic-bedrock-typescript

RDF knowledge graph data for [anthropics/anthropic-bedrock-typescript](https://github.com/anthropics/anthropic-bedrock-typescript), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download anthropics/anthropic-bedrock-typescript
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 70576ee6759fb81a893343ae5815bcfa0abbc3f7
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 70576ee6759fb81a893343ae5815bcfa0abbc3f7.nq.gz
│   └── repolex
│       └── 70576ee6759fb81a893343ae5815bcfa0abbc3f7
│           └── chunk-001.nq.gz
├── blob
│   ├── 026b90d6ada06fabd72c6beb7e50ab085414fe16.nq.gz
│   ├── 04ea5c6a12e2c6968dcabaeaabac861f3a2079c1.nq.gz
│   ├── 050a00c8710465f230b463d88092c62ffa346631.nq.gz
│   ├── 05fa8b55afca6445e6e6406bbac00b01292b43b4.nq.gz
│   ├── 0651c89c0c6690f43c6c85da956f4c1713d793da.nq.gz
│   ├── 0ae2216fe6de50fb8077e9535ea8b373c7474ac1.nq.gz
│   ├── 0ae43e21bc366f0a67b017e69c78bb1b67346b5e.nq.gz
│   ├── 0f811fc25a4e9c9280440ef4fa41d6230dcf6782.nq.gz
│   ├── 18c6328252bc26a50428fcd64ad50775bd2726d2.nq.gz
│   ├── 1a20e415017abe38d1aaacb195c4e39407858171.nq.gz
│   ├── 1c66ca975648161856ccfab775a86772105b6c24.nq.gz
│   ├── 1e06d0ff18f570e15a6a98fe707088b8a7496ed4.nq.gz
│   ├── 226fb15a022a4851823fc16fe5dd977669868ca0.nq.gz
│   ├── 2398baf353f228071173614d5be42cc742016b75.nq.gz
│   ├── 2625a8b700c2dcca8e876b2ef1ee16e29308d2b5.nq.gz
│   ├── 35eccc0723d5313a00b685318ce094b625adc671.nq.gz
│   ├── 3787318b797fec2f1933f938e0d8fc02321f44f3.nq.gz
│   ├── 3a84594c447dc19c5ded240423de8ab5ecc9a37f.nq.gz
│   ├── 4d6c9f3572292aad62e8fc60d5d87de8c6f82cae.nq.gz
│   ├── 4facad5ad3ef7cf346d083f4064779d7d7fa2593.nq.gz
│   ├── 4ff351383278a4b2ed4afbbfd7d9d134f648f81b.nq.gz
│   ├── 50a85669e06df7501e3d04835b0ef327fa4dbf93.nq.gz
│   ├── 5346dd82b6eb315179dc6bb6c0f9f7065deee589.nq.gz
│   ├── 58b3944a13bc5ad9839bc97444daf80449fbc4c4.nq.gz
│   ├── 5b530ee1b7943d28435f4f6897a73090fff0a3e6.nq.gz
│   ├── 60f0e7a3514bfc1511b2a0915e07d5467ae00025.nq.gz
│   ├── 62b7a39ee71f7c2de99910e2e019121fb85225e7.nq.gz
│   ├── 6ce350a243396898d0422f6f7707e04b53a3cde6.nq.gz
│   ├── 73df5600ccecaec9138f2e2e636159688f05131e.nq.gz
│   ├── 7554f8b20ae58485df49010107f79349db1c5943.nq.gz
│   ├── 798b60481534e993121b443a540c4b0bd710e99d.nq.gz
│   ├── 7c8fc4926b9022b962012f0a7454172e334fdc94.nq.gz
│   ├── 7dc510be2370bbc27f7254d0e9f949c1939a2a78.nq.gz
│   ├── 7eebe9a6206ecbb8dbff0705d05656817e01b90e.nq.gz
│   ├── 80b0e8944c4e76cf6173380178f88ed90798167a.nq.gz
│   ├── 8620986869d3aecc10e39bf295c6b1c49417c3d2.nq.gz
│   ├── 8d5aaab0c13a56739f8870baf847a61ac46a68ec.nq.gz
│   ├── 8e498fd343a94eb959a431f684d2909d0279664c.nq.gz
│   ├── a6fa34950d116670ba65e1e11adb4836cf2da25a.nq.gz
│   ├── a7c35416ef3c45c79e1d172f010d2daa4b445a38.nq.gz
│   ├── a9c42ebeb67ccc037faa41ea3ec5c5c52435c3ba.nq.gz
│   ├── ac71a66cf790ec2b4cc699891aed7671a6233dd7.nq.gz
│   ├── ad9f9a8206d8549a5a39ed4b8d1c26d6e4390c30.nq.gz
│   ├── af3b11188aec98ff0b50e909c6c9ecc2d3da1f30.nq.gz
│   ├── af75adaf6d06059844e582448ae18eae192aa705.nq.gz
│   ├── b12ee408a9c9b5cb08fcf1f22801227cb8d21a1e.nq.gz
│   ├── b1babe4448c710852ecf9f9dedfb8608784991c1.nq.gz
│   ├── b30941359d5a636bda934427b35c4c2046859242.nq.gz
│   ├── b31698f780b28f6187a3875497e4df5549c7a15b.nq.gz
│   ├── b61b2ea3326cb26dd1d60a50a6d2ef9915e80ca5.nq.gz
│   ├── b64288515ec711bbd3ce4519879efc4686786b88.nq.gz
│   ├── b7189987c8be0b8e68969ddefea48d3f2fb49e80.nq.gz
│   ├── b8b0ef55adb69fd8fd0c5ed2da2d2845e2c63a8f.nq.gz
│   ├── c18619dd13dcf85163eaaf7f1e7c969b3bd5e05c.nq.gz
│   ├── c7d6e5576f5eed5f18ee5cc8cbb1b633fa2653d8.nq.gz
│   ├── c9fd12d97425e102f3d793841d296e402af6970b.nq.gz
│   ├── cdcd61488970a88933d243db7ab67734cbfef06c.nq.gz
│   ├── cf076993bf4d56cf93ca2082532b5173e73138c6.nq.gz
│   ├── d03365a2bdcae9549941c4647dd1ce602318774d.nq.gz
│   ├── d226ad0254455e1f558ec45abe7a69f2897ff8b2.nq.gz
│   ├── d4a0a69b35a83d4ed3b690ab7e368aea08995cc1.nq.gz
│   ├── d55fc4d671e9d517d06657d44298d964f6b62a23.nq.gz
│   ├── d7755070baf84504ad1f106e1516f3a62ada11fd.nq.gz
│   ├── d9810da8e0782b2ffe3378f95665c8171a2f2c35.nq.gz
│   ├── da92cdff56f97cf1add8f41e5fe5240ce81e9273.nq.gz
│   ├── dd094d669ae114a6cd45d4c7d7bb0cc4db862490.nq.gz
│   ├── ddbdb799c8d3a5a22f9400270cb1b71b570c202a.nq.gz
│   ├── e053254b35e5219b06a26c1c6296158ce66f0f6d.nq.gz
│   ├── e35de41b3946d3da73695c689e48df8809b9f670.nq.gz
│   ├── e56e9891bc21a8a590ef2dc13cd95d6fe62786a7.nq.gz
│   ├── e9f2d70b0c9509fe4342bfcb7402742b30022743.nq.gz
│   ├── eaf5e7fcdf7bb26d97f744b29d54a8ff4760178d.nq.gz
│   ├── ed83d1445079901186741d4baa5f58d8769f1890.nq.gz
│   ├── ee7a38156c2c51d00416c19815623d0d1126497b.nq.gz
│   ├── f390e9a8d9beaca66150de8eeff1ac2f4cfbf8ff.nq.gz
│   ├── f6bcbfda9e39edbca06a66fdc42e3716b7f82860.nq.gz
│   ├── f72d78444e03511cb08867c3893600c0cc616ee5.nq.gz
│   ├── f972b6e186df4050c50410bbf7967a28d1a1f704.nq.gz
│   ├── fa26e5e8661e67e71a56c211a161cc328870649d.nq.gz
│   ├── fa9d74407681f8e1f3d24cb0c32189b48715da03.nq.gz
│   ├── fc6160fb10c10a0b9379efd20062e4828a94b74c.nq.gz
│   └── fc9d5b94fd65588f78e9fd3b22458fe046acb8a5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 70576ee6759fb81a893343ae5815bcfa0abbc3f7.nq.gz
├── filetree
│   └── 70576ee6759fb81a893343ae5815bcfa0abbc3f7.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 92 files
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

## Source repository

[anthropics/anthropic-bedrock-typescript](https://github.com/anthropics/anthropic-bedrock-typescript)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
