# Repolex Knowledge Graph of Preston-Landers/concurrent-log-handler

RDF knowledge graph data for [Preston-Landers/concurrent-log-handler](https://github.com/Preston-Landers/concurrent-log-handler), parsed by [repolex](https://repolex.ai).

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
rlex download Preston-Landers/concurrent-log-handler
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 138a0e3c459a8f47aa40566afc9e084bbb9313c4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 71290c50494396381029cacec79f080dcf9fb8ec
│   │   │   └── chunk-001.nq.gz
│   │   └── 7b98566be16f6d7c73863892dafc1ca27824b41e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 138a0e3c459a8f47aa40566afc9e084bbb9313c4.nq.gz
│   │   ├── 71290c50494396381029cacec79f080dcf9fb8ec.nq.gz
│   │   └── 7b98566be16f6d7c73863892dafc1ca27824b41e.nq.gz
│   └── repolex
│       ├── 138a0e3c459a8f47aa40566afc9e084bbb9313c4
│       │   └── chunk-001.nq.gz
│       ├── 71290c50494396381029cacec79f080dcf9fb8ec
│       │   └── chunk-001.nq.gz
│       └── 7b98566be16f6d7c73863892dafc1ca27824b41e
│           └── chunk-001.nq.gz
├── blob
│   ├── 011b0a5c5beaee01b6aaad1902ddf33f8cc8a033.nq.gz
│   ├── 05083edec30ea0c610684d66966ccca38e01f69c.nq.gz
│   ├── 054493d089d33e5ff9917257f993e2227df1dc24.nq.gz
│   ├── 06d7bf489ad744f29b469af5f6da80895a3395e2.nq.gz
│   ├── 07b02ec4661a4d8cef5222f24f9aff168189db94.nq.gz
│   ├── 13c7b5cb2f86610789d214a0af9f31b74c803520.nq.gz
│   ├── 169a91f9520e08ceacf3dc836ce8577510eb84ca.nq.gz
│   ├── 16e2d672130ae024e8effa60e582a1d692549739.nq.gz
│   ├── 18c687f2036c8242951170940985b600f788c7a4.nq.gz
│   ├── 1bf8da228496c8d01b7573abe28dc2448e43acc1.nq.gz
│   ├── 1f1b22e33a5c8478ce43d079314c3faa1e6a676e.nq.gz
│   ├── 214742234ddaf2ad677a3fb0c910904723ba5644.nq.gz
│   ├── 26760b0485596ad39d0639ba9c3cbbcfd66f5875.nq.gz
│   ├── 284800d49431bdb6e0c07ea8398b475674bebb1d.nq.gz
│   ├── 29f265e88e86e357749852d95e3ba92861a08a62.nq.gz
│   ├── 2bd563b5ce9d106b0d532c59903e77db30571cad.nq.gz
│   ├── 319e74128b6458d72d56bbc66483383acf56897d.nq.gz
│   ├── 35737f34fbac7b7ce5025c87a170831949bbd3a7.nq.gz
│   ├── 36f69b01c4c009c86b2c0a792ed6b6f6b054748b.nq.gz
│   ├── 375a7ef518123de81c0ebc0dbfed04ab96e8e5fd.nq.gz
│   ├── 3c43240638feb374dea5393bac25980dec1390b5.nq.gz
│   ├── 3dc9e04802400a2d6a015c7eb03d1a9eb2c66cfe.nq.gz
│   ├── 452b3ca4f537096c352bb81cb059eeaead62312b.nq.gz
│   ├── 466c089a41d3aaa4cd4d60f359f71f688b44a403.nq.gz
│   ├── 477727d98f87503957a1bdca9ff6521002a95df5.nq.gz
│   ├── 53c68c7b42d8b3598f84dc629bedbc3fbf57d987.nq.gz
│   ├── 5614cd4c1ea5f8e3d167432b578ea4465ef18289.nq.gz
│   ├── 58e889ccfa96867ffd62f7364d239f4165cd4ad9.nq.gz
│   ├── 5d4bd7ccdbf4f17279db6590abd79ce45bb58a2f.nq.gz
│   ├── 61bea622b1f84aaede41790cbd801b44f6b194c9.nq.gz
│   ├── 631d820e83d043cd717faa4cedf001e6a19e207d.nq.gz
│   ├── 6acce4a75cb67a447c645b001fc1ac83d35942fe.nq.gz
│   ├── 6af29b772aee3dadb061363c04e8124f89b7eb72.nq.gz
│   ├── 700a93d5dbca5e8cdc8af6ef59fa40284361917c.nq.gz
│   ├── 7bd286a1c209d932aae68648cd1c8eac9b3ad686.nq.gz
│   ├── 7e303f236d066af49790ef57f8b5c3f2e21fc5f5.nq.gz
│   ├── 7e55bc8724f26f575e1c80349a597f7fc299d20e.nq.gz
│   ├── 833b1de83238b32b1739ab7e5c7d165e271bf40e.nq.gz
│   ├── 849639151407f088c4e005ee6edd236a81d11004.nq.gz
│   ├── 8c13a316c9155224e58103e8b66a92027e737946.nq.gz
│   ├── 8ff0a6c395252b8492d616b27358c08e5d9ecce0.nq.gz
│   ├── 9cd621e99fdfc517165baf5491d97d709959e69c.nq.gz
│   ├── 9d93a8c6fce19048b3e822a4e1cfcc32861326a1.nq.gz
│   ├── 9e1f19e345428e4a57135f09bd4012b7e6de6176.nq.gz
│   ├── a0501fdf63ae33eb90cb2ce986dccaa553dfba64.nq.gz
│   ├── a3bd6b25d0214a64c06f9a0f54db83b6f4e22f21.nq.gz
│   ├── a793df34d26452e7a9a43386be10c79f1a0e1113.nq.gz
│   ├── b09139214fda136530b9117ac61f28f63ec6a15e.nq.gz
│   ├── b2d04c4f17ec45cb26c593f688d80d0c84cdbe9d.nq.gz
│   ├── b9e729179105fac7c301c48e77bdc4b163ce5071.nq.gz
│   ├── bdc4ef3b6aba631222231114250d530f852fcb21.nq.gz
│   ├── c056590f0423368570c36d0e774ee707468df202.nq.gz
│   ├── c368df63159131a5566138737e020d4270a81e65.nq.gz
│   ├── c41a2a201922ba2e69deb1eeef9fd5c86c2478e9.nq.gz
│   ├── ca76e791a5fb50c5085cc9a729c1e801f27ec759.nq.gz
│   ├── cd6ff0fbfda30ef7953980c8e1c712c29f6daf44.nq.gz
│   ├── d24c5bf9398ce0b087d7fd5447ccb0ecab74f8b7.nq.gz
│   ├── d5bea9c44967c1bbdedb84803978cb38efa59239.nq.gz
│   ├── db57410fee797739f0b7e25e6a853068a075a59b.nq.gz
│   ├── dd4ede7aa1636e09da3019507fbc36200ea1a93c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e844f2e955fb1cd4a25b639dddbb5e61a34cb71b.nq.gz
│   └── f01cc0b885d3e6b09e6b88a64d7a7df202a146fb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 138a0e3c459a8f47aa40566afc9e084bbb9313c4.nq.gz
│   ├── 71290c50494396381029cacec79f080dcf9fb8ec.nq.gz
│   └── 7b98566be16f6d7c73863892dafc1ca27824b41e.nq.gz
├── filetree
│   ├── 138a0e3c459a8f47aa40566afc9e084bbb9313c4.nq.gz
│   ├── 71290c50494396381029cacec79f080dcf9fb8ec.nq.gz
│   └── 7b98566be16f6d7c73863892dafc1ca27824b41e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

19 directories, 83 files
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

[Preston-Landers/concurrent-log-handler](https://github.com/Preston-Landers/concurrent-log-handler)

---
*Parsed on 2026-09-26 by [repolex](https://repolex.ai)*
