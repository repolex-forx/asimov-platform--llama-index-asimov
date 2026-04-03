# Repolex Knowledge Graph of asimov-platform/llama-index-asimov

RDF knowledge graph data for [asimov-platform/llama-index-asimov](https://github.com/asimov-platform/llama-index-asimov), parsed by [repolex](https://repolex.ai).

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
lexq download asimov-platform/llama-index-asimov
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── blob
│   ├── 056fce806d0b314ebd074d1a664a6fa90e135f89.nq.gz
│   ├── 0602c2d321426621f0a3d9ac3b5b5524434220ab.nq.gz
│   ├── 07c1cba5c8f538f74cbafeb6763ab41e0269a193.nq.gz
│   ├── 1d013ff92fa855fb03f148d15f9488c339392020.nq.gz
│   ├── 2156bd4d0a227c637e190d5474def7f1c5dd4577.nq.gz
│   ├── 2391f73aa051d3804285ce744f2e9a1c7e08993d.nq.gz
│   ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
│   ├── 3d8b120742757ea467156c51bc3713d5777b5cdb.nq.gz
│   ├── 4f281100bbc88754b13c8b7ed5090f214b2b254f.nq.gz
│   ├── 524f089bd74590450b8cdb8900439815a56e508b.nq.gz
│   ├── 599875071efcbb073ab956a47a5e02554163d575.nq.gz
│   ├── 5a7f97663bc558a26f18ea2cf82d17ff98382247.nq.gz
│   ├── 5a82b4d66e7b5e24ba6be6646b94ecb5a7a3a3e3.nq.gz
│   ├── 65fc2542170ef53c029aa90fef0bd0b2d73fbbda.nq.gz
│   ├── 68535ee6ae9db3175a0394927608def277718b86.nq.gz
│   ├── 6b73b3fb6071238698ea7435e6cb742a02c4be4c.nq.gz
│   ├── 71f61a6f0f4b69473f85d8730b0f7e57483ad177.nq.gz
│   ├── 771cfb85ba82d304b40ddb561dcb489287227e29.nq.gz
│   ├── 77d6f4ca23711533e724789a0a0045eab28c5ea6.nq.gz
│   ├── 7888bc4d8e042909bd076b88c185ae1f1d392fc7.nq.gz
│   ├── 83ee8a998733da70f31c216bfb3cc0353a0872d8.nq.gz
│   ├── 8460c12f3ef980930e18d2cebe97e424869ed757.nq.gz
│   ├── 859ac3ac3914f5adc07a780bf357ef676ee6d284.nq.gz
│   ├── 883f85cceaa33dee7a937c8c2b881ea5acc3224a.nq.gz
│   ├── 8aa9524e651fbb6655cbec1eaf8f07eed5b8ab3f.nq.gz
│   ├── a6f67842a2f2063ca361775a6c538a6baa413d9c.nq.gz
│   ├── a7aff625c20536dbf02f8d93f3bbc9e33fe3f6b5.nq.gz
│   ├── ad078fff6c269b218278917971610df979419716.nq.gz
│   ├── d1ffae6c5d3dd76f6e5f746541f37d1df488a62e.nq.gz
│   ├── d27a9edb092be1b4fc605a96f6ec6ecbb3aec306.nq.gz
│   ├── d9f4a805ea9dddb5ed43ef78ebc4dde72374c128.nq.gz
│   ├── dac703f703cb06328fffdd7c974f489f3af3f087.nq.gz
│   ├── dcbe25914f4bc40bb47e9e0ded436f0a92942aa4.nq.gz
│   ├── e051fb8f3a3fbdc2a95f09eaac4ade766dd4596c.nq.gz
│   ├── e3e57a8ce4ccbf74759a6df8fa4a3980ff1c9209.nq.gz
│   ├── e520e6277b2c37bd8fe85af4f589ef74cae71d6b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   └── efb98088164f5786b17e83ed384971fc3c74f93c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5f010572aa0513bfc4b5f6e466b1777b07292128.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

7 directories, 43 files
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

[asimov-platform/llama-index-asimov](https://github.com/asimov-platform/llama-index-asimov)

---
*Parsed on 2026-04-03 by [repolex](https://repolex.ai)*
