# Repolex Knowledge Graph of jaraco/jaraco.functools

RDF knowledge graph data for [jaraco/jaraco.functools](https://github.com/jaraco/jaraco.functools), parsed by [repolex](https://repolex.ai).

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
rlex download jaraco/jaraco.functools
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 348632f3eea75c9b4055b088fd297d84ee079df9
│   │   │   └── chunk-001.nq.gz
│   │   └── b57bb859e09f10f1e2ad7e64e9d71723793517f2
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b57bb859e09f10f1e2ad7e64e9d71723793517f2.nq.gz
│   └── repolex
│       ├── 348632f3eea75c9b4055b088fd297d84ee079df9
│       │   └── chunk-001.nq.gz
│       └── b57bb859e09f10f1e2ad7e64e9d71723793517f2
│           └── chunk-001.nq.gz
├── blob
│   ├── 1349124def55fb6dfc56f7cf45407a69b6ca8a09.nq.gz
│   ├── 1f2aa7533b0423a8eb943f6f4ec02498e39581a0.nq.gz
│   ├── 276aab6c416b0b87bc6c3333fe5227a7c658a43a.nq.gz
│   ├── 2c0e8e1e212e9586ef0eeadcf4e1482bfa9b15aa.nq.gz
│   ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
│   ├── 2edfd73a3c4c22de4597cbee3b092e774e75b1b0.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 4986c6f9c7a7acd24c2305b6ea32539cc102f8fe.nq.gz
│   ├── 4c9b67f6c151abd10faff59d33e5d92483e8dcd5.nq.gz
│   ├── 53513eee9b3a2f4df50df1febd59a5206718995a.nq.gz
│   ├── 54c9000ec94341dd65c2053251b85b124017b9b5.nq.gz
│   ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
│   ├── 54f99acbfac68c2be8283174ea64f1730a795e49.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 583083e3bd6b3288ccac87c0891b292093aaa3b8.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 5c05f9e27d57a4b7a3c3a9fdfecf8cddb8be499f.nq.gz
│   ├── 63c0825f6bd49615f4f386b95463111f7992f6bc.nq.gz
│   ├── 6860f5e4ac8a927654db25852ea17d3268814b5f.nq.gz
│   ├── 6bd85078e532d33c27f0113675b6383de63b4e8a.nq.gz
│   ├── 6f834bf06d962463dd198c40931ad86546b1a359.nq.gz
│   ├── 700235be57c1b2872455c0be5333f59cf568e252.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 743636ab3bca2bed87c32affda4ac6f42ef92543.nq.gz
│   ├── 7a880297d481c29641a8dfb070254812066a99e1.nq.gz
│   ├── 7a8e64d7d28db8f7069d7a9e5a1e2c05603c8669.nq.gz
│   ├── 87d22713b9c83ad756c377ebbdf6763c624a2632.nq.gz
│   ├── 96e8bf111821e6abe0171d7c101b253c0ecacd35.nq.gz
│   ├── 9a0f3bce1395ae3819030b822e5d9076c85068ea.nq.gz
│   ├── ba06e2dfab20c0fdd3f2d046d981bffc155d6a8d.nq.gz
│   ├── c639b1109df51c767d1494d5335e88e5ca27a747.nq.gz
│   ├── db02f37ad8b166d770d8131239ed40872b6fe3cc.nq.gz
│   ├── df32e2e924bdfb14aa7dfcfc503d22081c1f0d74.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f0c51b7f91ad20b4bf4ad1eb8c7852c61d75a14b.nq.gz
│   └── fa5592412f13835ef19d2517513c9f5c4af96ead.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── b57bb859e09f10f1e2ad7e64e9d71723793517f2.nq.gz
├── filetree
│   ├── 348632f3eea75c9b4055b088fd297d84ee079df9.nq.gz
│   └── b57bb859e09f10f1e2ad7e64e9d71723793517f2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 49 files
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

[jaraco/jaraco.functools](https://github.com/jaraco/jaraco.functools)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
