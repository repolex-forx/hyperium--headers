# Repolex Knowledge Graph of hyperium/headers

RDF knowledge graph data for [hyperium/headers](https://github.com/hyperium/headers), parsed by [repolex](https://repolex.ai).

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
rlex download hyperium/headers
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8db1b786d414cc43e4d77e73b0f7afdcf061be59
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8db1b786d414cc43e4d77e73b0f7afdcf061be59.nq.gz
│   └── repolex
│       └── 8db1b786d414cc43e4d77e73b0f7afdcf061be59
│           └── chunk-001.nq.gz
├── blob
│   ├── 0098f6270c4013a1b47e0ed2a7753f9df6e43198.nq.gz
│   ├── 03ed691ed612c481ec953203c01c0ee71325b18b.nq.gz
│   ├── 08de5ccfd272605ed168087096d8468baa98217c.nq.gz
│   ├── 0ef63635d037acec61d3c1a63c96577b86d27c0e.nq.gz
│   ├── 0f417563a66357185d5f1903103be4f67dcc825e.nq.gz
│   ├── 0f7b4746de2f4fff1b7f517c13f2d5b00290bca1.nq.gz
│   ├── 1378e121c400f11513c02d9a8ade4651b6d4a480.nq.gz
│   ├── 1d2b3f4197925ea9ddc901442c10cf89e6c8c1d1.nq.gz
│   ├── 248fc24e79c8cf10588762cfc315bf0992659795.nq.gz
│   ├── 24ca786b465658225e9b11ed34bc758e8acd7d51.nq.gz
│   ├── 25f090ba47d2eee796acb771820e8bc33f0e4249.nq.gz
│   ├── 2ac1537960e6998528b1edb5d8d7fd08a52ece61.nq.gz
│   ├── 2b9a8ed0715b97e11c19dadebcf6106a1cd3cae9.nq.gz
│   ├── 2e275f00292145d78d77fa95f243b28863cc8841.nq.gz
│   ├── 2e7419bad84eda4cfe7eb0f9e3345cddc9322b89.nq.gz
│   ├── 306515817119bfce674cab724732ba641bd44011.nq.gz
│   ├── 30989b9a29ece9f342dbcdeb0b9c5bbaa9f35e07.nq.gz
│   ├── 317bc91cc270d503e63407300c7fad5383eafc4c.nq.gz
│   ├── 3192c82675445b4362ab59129c3e7786dc97e800.nq.gz
│   ├── 33845e2edf57cf3bbc727989e0d8f0d7aa7b20e6.nq.gz
│   ├── 37bfa323a61b6d3da910af017799d4fdcbd91607.nq.gz
│   ├── 3c3fde33ee2ad3033a64df0bf5956cbeb469d61d.nq.gz
│   ├── 40f2de40c6de7514f2ce23bcccb5c35f3a3f5f89.nq.gz
│   ├── 43b73b87870081da2b0394f49987f0c636bd39f0.nq.gz
│   ├── 44f8f33916109002e388ef3fa7d520f6e24e8240.nq.gz
│   ├── 460c22a55f70e5bf2d1537e97f4badec3a0be7a4.nq.gz
│   ├── 471334f8872772cedcf3df2423a57bac6f0f111c.nq.gz
│   ├── 4980b963eac1e87c9f7d466fe58e8abe64c73c0b.nq.gz
│   ├── 4c5a96d57c9516b93a00787d9f7afcae10e12b00.nq.gz
│   ├── 4fde9efc3d605ee00db41b9ddebec784242f4a22.nq.gz
│   ├── 507bde996499fcc4d9dd0280de5fc6b728f95969.nq.gz
│   ├── 5122e97114c7b2dd2fe127075c2ca72ea5b1ac6d.nq.gz
│   ├── 53a32bdcc6af6c4fbc49e0d4df5ac6cd749d8949.nq.gz
│   ├── 551840dce25e110c0d621fd7ade24e8aa6a0d9ea.nq.gz
│   ├── 554bffb2f633ce07d586e9333de45ccd45af4b95.nq.gz
│   ├── 57f0d944beffe993506d5c60b59218674c899e39.nq.gz
│   ├── 58d18a4e2835823fe41dd1110f11b43ab8b12ad5.nq.gz
│   ├── 5976393268e20d512c404ddd0137bd014cf5a9a9.nq.gz
│   ├── 5a3f462829846a5f7497a785b2d8cefadb125d0a.nq.gz
│   ├── 601a3fecff8834b5ce85da7719074cef72125cc2.nq.gz
│   ├── 624412e0b97fe581f9fe588477819367ab88c12c.nq.gz
│   ├── 6a3613eed498b4c00623b4779842929a79fb5bfa.nq.gz
│   ├── 6b75f0728759bae971ecc34a55138768c367acdc.nq.gz
│   ├── 6d199d16b44f0957543ca698338252e74015e108.nq.gz
│   ├── 71870ca3818c1bf09c26cc2837924bd6b54c4b2f.nq.gz
│   ├── 72728ca4fce320eb3fd4ae633fdc16f81bd69597.nq.gz
│   ├── 7551c2ad887b367c99db00140b92b52fb1277949.nq.gz
│   ├── 779ce6512284c8172926bff35025ad78104daa1c.nq.gz
│   ├── 78883d9a64fb66358fa34d9817b29b753038bab6.nq.gz
│   ├── 7bf76c2e7dafd81a95c00431de26aa8ba1f83062.nq.gz
│   ├── 8020014cf8936d26d94bbbe14a9898042222f020.nq.gz
│   ├── 85021f133012a225c066e9c0498c83f6b91a72b3.nq.gz
│   ├── 870d083a9953732e2a5b3311c812770c66224beb.nq.gz
│   ├── 89a80dc0145bf456703baf2f95b51e77b2d8fc5b.nq.gz
│   ├── 8eec616212182ed345ded80862a4978a010fab9b.nq.gz
│   ├── 8fb416e0eaac59c7a0bf065781958284feb169c1.nq.gz
│   ├── 8fd232b220e8e0749ebcf688033134554c78b02d.nq.gz
│   ├── 918487a98ca92e5937d4c99ef60422f393e6d21c.nq.gz
│   ├── 92272015409f1ed0e38c027fe730dab20364b147.nq.gz
│   ├── 93b65fd1305512a51ee5457aab2f9c0a4655554b.nq.gz
│   ├── 95bf04a5c624547d701c5d22ca763ba8180db18d.nq.gz
│   ├── 95c8a4cbd04a133365a7ec627a755a604f7cc185.nq.gz
│   ├── 960d02967752e3134984398c056e9aecf121ae1d.nq.gz
│   ├── 9805cbfaf5c171033daaff6883ff476476ba69a0.nq.gz
│   ├── 98d7a9b1ab0bb55b77fb32acfd04910539a88408.nq.gz
│   ├── 9e274525685ed45618f70697d9b051c73e562d32.nq.gz
│   ├── a23a00bf0178565d3df682fc45d26257069f93dc.nq.gz
│   ├── a47d9e03481f5177fecf75232536f680d8f63083.nq.gz
│   ├── a57c7ff3ec84c7d698268f23a4b5b628c0a046b1.nq.gz
│   ├── a9d37c560c6ab8d4afbf47eda643e8c42e857716.nq.gz
│   ├── aef73758763e781e629379e3d817623fe3b4d959.nq.gz
│   ├── bc2a84795889762c92b8675852ea4ea19f1e4794.nq.gz
│   ├── bcc797280db596190dacb69e50978bd2ad1ab29d.nq.gz
│   ├── bd235b0eb9163d787035f0fc05ef65b834e85c44.nq.gz
│   ├── c1c914dfa614ca7954463670869d02d0213e15b8.nq.gz
│   ├── c2499b0a0ddf3c5c6aee0fa1102cb9fe6d40b838.nq.gz
│   ├── cb1353233be6b1f62d3167ac59162687d1442371.nq.gz
│   ├── d0d7acf02ef6b86a8a0ac47ff634cd3db75ca720.nq.gz
│   ├── d270fa72518e3f50718768b4fc25853a613bf3bb.nq.gz
│   ├── d353059dbbf5cc5e50a1786c57ea69868b2e2861.nq.gz
│   ├── da4525116bcd934abf81c670313793a4c9075429.nq.gz
│   ├── ea5b60640b01f74e295037aa8a6b7d4ea278a739.nq.gz
│   ├── ec8dcc54cd16ca8d99ae661639cea426a0383847.nq.gz
│   ├── eed923842e653f1c5a4dad310ce45612963a9aa0.nq.gz
│   ├── f8a82bbc59019305cd9bfc55c4bd7f90ba9092e5.nq.gz
│   ├── f92a36970ad432c16c56a85648a5d6d29420f7c5.nq.gz
│   ├── faee2ac9105839bf621cf69ddf7b5af8bf9d372d.nq.gz
│   ├── fc972dd3c7152d9df5281ab08ba7c1da39be75e5.nq.gz
│   ├── ff2f204edd8f3fe952d1c6b808dbf02516276310.nq.gz
│   └── ff91732ea194d50231776d23e167cc9cb8319fbb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 8db1b786d414cc43e4d77e73b0f7afdcf061be59.nq.gz
├── filetree
│   └── 8db1b786d414cc43e4d77e73b0f7afdcf061be59.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 100 files
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

[hyperium/headers](https://github.com/hyperium/headers)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
