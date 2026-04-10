# Repolex Knowledge Graph of utkarsh2102/rubocop-packaging

RDF knowledge graph data for [utkarsh2102/rubocop-packaging](https://github.com/utkarsh2102/rubocop-packaging), parsed by [repolex](https://repolex.ai).

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
lexq download utkarsh2102/rubocop-packaging
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fe87c122db6e93a69cb2cf42afb370eddbe86432
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── fe87c122db6e93a69cb2cf42afb370eddbe86432.nq.gz
│   └── repolex
│       └── fe87c122db6e93a69cb2cf42afb370eddbe86432
│           └── chunk-001.nq.gz
├── blob
│   ├── 021a03bf9ae32af4b1fd0c3cb6e9e908eeaae9a1.nq.gz
│   ├── 02b69fcc0b9e8b53670076e1a3cb3a2e55b76411.nq.gz
│   ├── 02cb4d12d75d8ed29932fdbdc53748f44385d6b3.nq.gz
│   ├── 03a20cf57949514b98d46ecb80dcb1aca4989def.nq.gz
│   ├── 0586c4a121fc9b76c445a3f01e55a9bdc76c8df2.nq.gz
│   ├── 0c2c0fc47f4ea130222acc929a1717c21012b7fb.nq.gz
│   ├── 0e0c3d8cfd3b6de681c09fcf739ed0e56aff36ea.nq.gz
│   ├── 13da248defce2e2b1bf133216ea2b5e9533fb6f3.nq.gz
│   ├── 31a0c03295c8d6d251c9aaa0c4c843e5371b0d0f.nq.gz
│   ├── 34c5164d9b56c7d528f061c97f2d2fe02c834bdd.nq.gz
│   ├── 4cbe9f82e869449280a480a29623b01c8f90fee0.nq.gz
│   ├── 54f43bf94f0db41fe9481f4ea74c99ddb18375bf.nq.gz
│   ├── 5b494db1ebef361091395e22ab6e9acb86df9276.nq.gz
│   ├── 5cc837ab35ce6e2b1e282cd667ddb8f0f3ba6982.nq.gz
│   ├── 5ed3f42a041b1de97ddabe6b3ae3f523af464a55.nq.gz
│   ├── 5f46da2bf75c168dcc46104b1164a46c9c3b774a.nq.gz
│   ├── 6e76f6c9b52864ed2a42ae296c33c77723eeed90.nq.gz
│   ├── 744006455afc649f23fb4c8f201502a08e25bc22.nq.gz
│   ├── 795d8de7033e602a768a468bc921f440c9066e1b.nq.gz
│   ├── 7b2ecdcfb0fd2b36ca761dd9c98e0ea5f6bbd2ff.nq.gz
│   ├── 7c811f3399b6c013325c64b6caee023350474a0a.nq.gz
│   ├── 7d527f353f36676a9fdd4deca6bd03a384227094.nq.gz
│   ├── 80680905a14ccb853da22dcce9bdb15c9bc7b77f.nq.gz
│   ├── 823db60a3c619eb5b28896d5498e101213d6d439.nq.gz
│   ├── 85c2f53d86e7c6018e309ee5b600bfe2d7862b81.nq.gz
│   ├── 9064820868d56d7389680a44ace96e2ec69c0971.nq.gz
│   ├── a2d94209e0f176cec252d620f0dc990673b6f17d.nq.gz
│   ├── a869ff5bda87758080b9d65f58da21b743c7a5fd.nq.gz
│   ├── af9f0a5da8bf10209b4bfe8e92eb6933f2fa487d.nq.gz
│   ├── d3d9739f7b4c9516614350ace1278110b0033a3c.nq.gz
│   ├── dc0c1fdca2c62efa666bf781a9dbc8632a768239.nq.gz
│   ├── e10c1d2249ac4283cc590825ed9831cffce36e80.nq.gz
│   ├── e90774443438fb0c4039c32f7778dfab83ca3192.nq.gz
│   ├── ead3a7b09beff3945a6916914f84090b88d8a3ca.nq.gz
│   ├── eb27e2241ff9f1c21801ca5492aa1c742637addb.nq.gz
│   ├── ecd5ad4e3cd68396610524a835a170723d7ca975.nq.gz
│   ├── edaa007a23c8a8a6c73c8ccfb2e385988be53d6f.nq.gz
│   └── fb8187f19cb3e28ebb9e6b693e66dea3665301dc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── fe87c122db6e93a69cb2cf42afb370eddbe86432.nq.gz
├── filetree
│   └── fe87c122db6e93a69cb2cf42afb370eddbe86432.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 48 files
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

[utkarsh2102/rubocop-packaging](https://github.com/utkarsh2102/rubocop-packaging)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
