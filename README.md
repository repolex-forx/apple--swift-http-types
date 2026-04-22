# Repolex Knowledge Graph of apple/swift-http-types

RDF knowledge graph data for [apple/swift-http-types](https://github.com/apple/swift-http-types), parsed by [repolex](https://repolex.ai).

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
lexq download apple/swift-http-types
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 45eb0224913ea070ec4fba17291b9e7ecf4749ca
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 45eb0224913ea070ec4fba17291b9e7ecf4749ca.nq.gz
│   └── repolex
│       └── 45eb0224913ea070ec4fba17291b9e7ecf4749ca
│           └── chunk-001.nq.gz
├── blob
│   ├── 0023a5340637983755c8c19c18cc2c2bb1dbda1c.nq.gz
│   ├── 05829acf8ed0de8cd8207b30e28d774917903f2b.nq.gz
│   ├── 08891d83f67181f147fc91135bf6c0016a2bea7e.nq.gz
│   ├── 1088ae427f38192f99c49c59e6dd794f36953c6b.nq.gz
│   ├── 11e4d1b5cbbf747af4db4e59a4d7e3bc0c3ab00e.nq.gz
│   ├── 15ba245209439101d13e26e2ef5440c6e139b1e0.nq.gz
│   ├── 181a5f35118fc3b609d841aaee46a805106bceba.nq.gz
│   ├── 19f21409e29bc74e204b989b4739ae4260f66d1e.nq.gz
│   ├── 1df5fd70ebb540e7331d68eeb3a42070c53ed740.nq.gz
│   ├── 30b79cc64c7e84eb289fb9cd64dc7ab6d1ee781c.nq.gz
│   ├── 33ff1c0a88450a5d05e5e38d1414b9d0a0aec766.nq.gz
│   ├── 3ea9832371a6e58ab6aa7546938a18d8a8d49e25.nq.gz
│   ├── 41cebc9554c857e091973ea02d76bc59de9566e6.nq.gz
│   ├── 4e15cec23de570be0688ae5c73eec777a09fc42b.nq.gz
│   ├── 502763a0d6f7c133d8405e98a2be30b5e3e2652c.nq.gz
│   ├── 550505e4558301218d608c38dbc623e6b28ed67f.nq.gz
│   ├── 5b63be56c18b3c561a985a80dac3350ab1426659.nq.gz
│   ├── 5e24d39ba048e9faa7499b0cd1c22f421ae2da16.nq.gz
│   ├── 65002a83eee65c0b1c171095f015c2a160b0ecce.nq.gz
│   ├── 76501d7d627101e572fcb0a1e14eccf450c16d26.nq.gz
│   ├── 7a3e371a7262f4ca8a276543163d3f0d728a4983.nq.gz
│   ├── 7bd880d577cae3f04d55b891d6ab1298cc859c06.nq.gz
│   ├── 7c90ef4cfc8c41936f228f94ebe20f13d64f3aad.nq.gz
│   ├── 7fa06fb305f0cce527bebbd49722fed34c6cb71d.nq.gz
│   ├── 8645aa9c19a479edffac669c2fe607566b0e2dde.nq.gz
│   ├── 991e20d005178b20aa6beeb7eb871df4734622ff.nq.gz
│   ├── a5c08f7e4b9f96fa37e8923729a1c52f4a72be6a.nq.gz
│   ├── a6b3e03484f266f78a03af8e98a81e52b5216c6a.nq.gz
│   ├── b2b3db3b5ed92fdeaf24bab8254a559b5c247ac0.nq.gz
│   ├── b882c7c86ae3ecc20d9cd0283b52fc654cff50a6.nq.gz
│   ├── bc880db0df575811726b30a1710580d01dd8aae0.nq.gz
│   ├── c2cf74fffcf5842ceafb309c21bbeb45de9168ef.nq.gz
│   ├── c842badd73298b573a41ddd3d7a0f1e538f9e93a.nq.gz
│   ├── cdf2de62713208c3249268eaad5115e79f09c4d2.nq.gz
│   ├── cf70159690efbd118a1bdde01d51d691cccb3f7b.nq.gz
│   ├── d2da2f1aca37d8ad8d75f30a8ac6eab54f827145.nq.gz
│   ├── d30466d1040a243efee4c1886b79ff025bbcbff0.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── e29eb84641301518c171ed2374bf1c36f8140e5d.nq.gz
│   ├── f0b61209051711ae9cb403a1ac694ed6ad5741fe.nq.gz
│   └── f3260d269c3c76b8bfd33266bd4370014b13338b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 45eb0224913ea070ec4fba17291b9e7ecf4749ca.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 50 files
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

[apple/swift-http-types](https://github.com/apple/swift-http-types)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
