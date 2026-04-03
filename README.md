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
├── aggregate
│   ├── ast
│   │   └── 5f010572aa0513bfc4b5f6e466b1777b07292128.nq.gz
│   ├── lsp
│   │   └── 5f010572aa0513bfc4b5f6e466b1777b07292128.nq.gz
│   └── repolex
│       └── 5f010572aa0513bfc4b5f6e466b1777b07292128.nq.gz
├── blob
│   ├── 0332b32e3b4c0ab2129447997e1829379e7ab500.nq.gz
│   ├── 04f3a3a5d8affd7a38a2996e0d27bb9e056d7bc4.nq.gz
│   ├── 056fce806d0b314ebd074d1a664a6fa90e135f89.nq.gz
│   ├── 0602c2d321426621f0a3d9ac3b5b5524434220ab.nq.gz
│   ├── 06f92fc6c85c99b6f2ecfce377f8ddcd7720eda6.nq.gz
│   ├── 07c1cba5c8f538f74cbafeb6763ab41e0269a193.nq.gz
│   ├── 07c6e4e2f8c252cc3b71c30add3f57f82feb83bb.nq.gz
│   ├── 0d719ccb5964a712b9ff88177ef5b41449c888d5.nq.gz
│   ├── 0f5c46748603821b43af9d6212c24707173d26a7.nq.gz
│   ├── 0fe2c55b1d6c648b8b7fb024910eab7432600d62.nq.gz
│   ├── 12cc36fbdc90138cbccafa57c663b4bc144e936c.nq.gz
│   ├── 13edb27f8341a15f7ef6805243c5be8572913129.nq.gz
│   ├── 14bf92db58ba5835894d39816d5c8dae2760f2a7.nq.gz
│   ├── 1640154fdfa9bcce6240cd825bfdb0e63581b460.nq.gz
│   ├── 17d0d9409a71ab0f3e8a47555b7aa87906313f92.nq.gz
│   ├── 1cb1f4aea1f5021bcaf2c222d99e31d45441bdb0.nq.gz
│   ├── 1d013ff92fa855fb03f148d15f9488c339392020.nq.gz
│   ├── 1da31cb9fb062dd4bd97df721df8795e533dabf0.nq.gz
│   ├── 1f4ae6f8a2b5b9a5b0051154f15ae6fd40f55f3c.nq.gz
│   ├── 2156bd4d0a227c637e190d5474def7f1c5dd4577.nq.gz
│   ├── 21f3f2282d52dd9c490bbfe7c2e01752eed25687.nq.gz
│   ├── 231e88ea065b2e58e9a60a36a9eb5dc0cb117080.nq.gz
│   ├── 2391f73aa051d3804285ce744f2e9a1c7e08993d.nq.gz
│   ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
│   ├── 2958f37dfd26d9304df21c909b747a61a586aeec.nq.gz
│   ├── 2aca52303f8ce9a3095ede98883590af08beb533.nq.gz
│   ├── 2b761c1293dea3fec4fa73670e1f96ae5add6c1b.nq.gz
│   ├── 2f8b5cfb6b922c0f9aa5f315dbf06fdb9806efbd.nq.gz
│   ├── 2fb5b0dca69dd614eac771b46d95cc9973bf9d58.nq.gz
│   ├── 339bfc2a432825a81386a7f930a510d317ea6075.nq.gz
│   ├── 35cec7b0e4afbe071c04aa8b22790ebb4f759e88.nq.gz
│   ├── 3d8b120742757ea467156c51bc3713d5777b5cdb.nq.gz
│   ├── 3e35222c460b5860273f4ba2fe774e89d38da373.nq.gz
│   ├── 46cc7af7032836a095f9993134803df6f988f39d.nq.gz
│   ├── 47a89d609dc70103d7e3bfd609f4201e7cd94186.nq.gz
│   ├── 498e3a16e08584c7d56d253a08632584d7c350c7.nq.gz
│   ├── 4a05d0576b394885bcf10453d3e7050ebd091bff.nq.gz
│   ├── 4dc965161ccd381233ed4f5c697b1594f60097f3.nq.gz
│   ├── 4e379d2bfeab6461d0455bf5bbb8792845d9bbea.nq.gz
│   ├── 4e4fba2ad7388399bef352d7876f9b00d82a1d79.nq.gz
│   ├── 4f281100bbc88754b13c8b7ed5090f214b2b254f.nq.gz
│   ├── 502154c221b4d00b73af3ec3d957385566958689.nq.gz
│   ├── 516ed16c24d1c5686637c9a610c0f78f49f65db1.nq.gz
│   ├── 524f089bd74590450b8cdb8900439815a56e508b.nq.gz
│   ├── 580e41b37c278fb8de03d2497b8c7560a6289b50.nq.gz
│   ├── 599875071efcbb073ab956a47a5e02554163d575.nq.gz
│   ├── 5a7f97663bc558a26f18ea2cf82d17ff98382247.nq.gz
│   ├── 5a82b4d66e7b5e24ba6be6646b94ecb5a7a3a3e3.nq.gz
│   ├── 5bbdef93a9c28e5ec6669c997491a901073a6654.nq.gz
│   ├── 5e52ffb10c9afdc1345d0439a9ab6d67051f52ec.nq.gz
│   ├── 5e9531e64e071ddfb79f2ebaf32ef524f2e89694.nq.gz
│   ├── 5f8b600d1ade974c245bb1f77dac81662fd30298.nq.gz
│   ├── 6143ecf9c917478e0d7e67ba90c07365551fdac2.nq.gz
│   ├── 6324d401a069f4020efcf0ff07442724b52f47c2.nq.gz
│   ├── 65fc2542170ef53c029aa90fef0bd0b2d73fbbda.nq.gz
│   ├── 68535ee6ae9db3175a0394927608def277718b86.nq.gz
│   ├── 6aa1ef5cab4d028d0fff27b22a8aa11cdcfc90e1.nq.gz
│   ├── 6b73b3fb6071238698ea7435e6cb742a02c4be4c.nq.gz
│   ├── 71f61a6f0f4b69473f85d8730b0f7e57483ad177.nq.gz
│   ├── 75421d762bf481d4e0b3908a9d6b6bba44bb77d9.nq.gz
│   ├── 757b8d663e201b718d5581b7f4d5ea4989ddcdc2.nq.gz
│   ├── 771cfb85ba82d304b40ddb561dcb489287227e29.nq.gz
│   ├── 77d6f4ca23711533e724789a0a0045eab28c5ea6.nq.gz
│   ├── 7888bc4d8e042909bd076b88c185ae1f1d392fc7.nq.gz
│   ├── 794d8afb01590c860f0de7bfad5586c5df6b63d7.nq.gz
│   ├── 7bd62d00a770fdde9456eb23268ce13f42d2ebf4.nq.gz
│   ├── 7ee8ff7a901170efb125c57add58e7841a29d1e8.nq.gz
│   ├── 83ee8a998733da70f31c216bfb3cc0353a0872d8.nq.gz
│   ├── 8460c12f3ef980930e18d2cebe97e424869ed757.nq.gz
│   ├── 859ac3ac3914f5adc07a780bf357ef676ee6d284.nq.gz
│   ├── 883f85cceaa33dee7a937c8c2b881ea5acc3224a.nq.gz
│   ├── 8aa9524e651fbb6655cbec1eaf8f07eed5b8ab3f.nq.gz
│   ├── 8adfa25da8c65d7b19255dbaf2cfa5fa5708c9cb.nq.gz
│   ├── 8b58ec04a5676d67629db1d0d8c09b3fe1921326.nq.gz
│   ├── 8dec464ad01bfd3d42f53ac17be22557732374df.nq.gz
│   ├── 93669dfa3aaa8e06f0eabf297d46a334bca3c05d.nq.gz
│   ├── 951982195d53d8e777cbb6c2c713e342c1f1d37f.nq.gz
│   ├── 991ec2b7aad2013cac9069f8523c3f87d278927e.nq.gz
│   ├── 99fa1d453459af39cc4cc17ee1b34831729cee59.nq.gz
│   ├── 9f00be737be0b45ab84e550dbb3fb66e23e4b734.nq.gz
│   ├── a0a48e4025e55dd64284c2554eee43e4e227362c.nq.gz
│   ├── a6f67842a2f2063ca361775a6c538a6baa413d9c.nq.gz
│   ├── a77d24eb62e6102760cc4a8851269a6bab50ba58.nq.gz
│   ├── a7aff625c20536dbf02f8d93f3bbc9e33fe3f6b5.nq.gz
│   ├── ad078fff6c269b218278917971610df979419716.nq.gz
│   ├── ae6b6da8e065de6cafdfad96e36b35fabc351293.nq.gz
│   ├── b1b02d85efea5a9e4df06fa0f08eeac2606260a4.nq.gz
│   ├── b32e1d04a0a16cc355b5b120b143b5510661d201.nq.gz
│   ├── b708184d97a467382b1762cfded700b17cb1cf7d.nq.gz
│   ├── b737a205c9bebf19b9e3c639397d993da76b14bd.nq.gz
│   ├── bc0bf883c85ab39f3f2da69457748d77f2269567.nq.gz
│   ├── bdc9c9c3a2ac34886d4ae3c13604a434dc74b0e7.nq.gz
│   ├── c0e4e7ad74c2c57c5e18f5139b81778d9f84c436.nq.gz
│   ├── c25f1c0e5c3824c09a074b9459e2d6c391b02b35.nq.gz
│   ├── c5f0f3690f1332c6ddf619c7a3e8a12c07934cb8.nq.gz
│   ├── cb9d28217ddde687bea905033f5926ed8b9a3097.nq.gz
│   ├── cd8caa246424c5cee3d81c5c9b2537385483e940.nq.gz
│   ├── cd8ea03c75aaf15b2f55e7d452f70a0e9af6efd8.nq.gz
│   ├── d03a2de88b044a364f7903dbe9c307ec30f5e497.nq.gz
│   ├── d1d1c70cd785900627c311befdabcc0c55a41259.nq.gz
│   ├── d1ffae6c5d3dd76f6e5f746541f37d1df488a62e.nq.gz
│   ├── d27a9edb092be1b4fc605a96f6ec6ecbb3aec306.nq.gz
│   ├── d5d1aaa2bec88232895da8c7db801955d6ed8dc3.nq.gz
│   ├── d9f4a805ea9dddb5ed43ef78ebc4dde72374c128.nq.gz
│   ├── dac703f703cb06328fffdd7c974f489f3af3f087.nq.gz
│   ├── dbba9e24aa3b78467b5dbf683d03654e8dbe1dae.nq.gz
│   ├── dc3c589d882df567738b0c1880e405ff00b06d31.nq.gz
│   ├── dcbe25914f4bc40bb47e9e0ded436f0a92942aa4.nq.gz
│   ├── dd23298e4437814b608dffa57c44b53240c69cc5.nq.gz
│   ├── dda9a8bb74313f824d1dd748393591967a02dd59.nq.gz
│   ├── e051fb8f3a3fbdc2a95f09eaac4ade766dd4596c.nq.gz
│   ├── e1ab21dc282551cf0896a351af18b7ebe3abd7f6.nq.gz
│   ├── e3e57a8ce4ccbf74759a6df8fa4a3980ff1c9209.nq.gz
│   ├── e520e6277b2c37bd8fe85af4f589ef74cae71d6b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e70fb7b07f4ae669f65d63663209711d8251553d.nq.gz
│   ├── e83d902be4536b71fbdeb0e686130c1bbb39d1e7.nq.gz
│   ├── e9c2d5f5b9bd1de30dd8ec00a1761f1cc53514d1.nq.gz
│   ├── ea9df01d5fd0a8bec302209002b5de5b90c9ebc1.nq.gz
│   ├── ee4d9362508d63f9e156fe9ee1b11ebc1a3e86d6.nq.gz
│   ├── ee788c3fec9a79c21876fbab327b9ae702b9ef92.nq.gz
│   ├── efb98088164f5786b17e83ed384971fc3c74f93c.nq.gz
│   ├── f0e7180d3b08dea3694bfbb98867178550c879e5.nq.gz
│   ├── f1eddbfcbd13d9fa7963e6776c75a6909b7858ad.nq.gz
│   ├── f25c4ec273ba481652494c3d28108e1119e73167.nq.gz
│   ├── f2fa10ebccbf706a5532f1a88573e3ff5aa4eb91.nq.gz
│   ├── f368f2f71ba312b593285d3009e727a7a9e868b5.nq.gz
│   ├── f3ab8b6fa5d3cf7304d63c1a7108a157854cdf63.nq.gz
│   ├── fbc40dc64c7ae88def89605c4a56faded312397b.nq.gz
│   ├── fdd06854aaff591397f362bb1ba93120ad2acb14.nq.gz
│   └── ffc519aa4ad3e43386762b5f6b43b87651a312d2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 5f010572aa0513bfc4b5f6e466b1777b07292128.nq.gz
├── filetree
│   ├── 1f41623e429812b8dc9339fa0c50c7ec506d327c.nq.gz
│   └── 5f010572aa0513bfc4b5f6e466b1777b07292128.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 141 files
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
