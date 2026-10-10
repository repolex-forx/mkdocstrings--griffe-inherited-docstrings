# Repolex Knowledge Graph of mkdocstrings/griffe-inherited-docstrings

RDF knowledge graph data for [mkdocstrings/griffe-inherited-docstrings](https://github.com/mkdocstrings/griffe-inherited-docstrings), parsed by [repolex](https://repolex.ai).

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
rlex download mkdocstrings/griffe-inherited-docstrings
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cf49f4e23ac1b9eac99bddaa67aeb72d25027a63
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cf49f4e23ac1b9eac99bddaa67aeb72d25027a63
│           └── chunk-001.nq.gz
├── blob
│   ├── 002b2a0406a2be01fdcfcd78c4a90218458ac9cd.nq.gz
│   ├── 0045d19b178b72444d6067efd066efb73394b6f4.nq.gz
│   ├── 0536cbbe261b2d97ed3d94f5b1fd86596a2ae486.nq.gz
│   ├── 0ca7fabfe18b401de8974a8668482dfddfb3b9e3.nq.gz
│   ├── 2008f6d9be4113bee8c4ecb161988b5db9db8885.nq.gz
│   ├── 23794762a313561d9f194cc104caf1fff3868256.nq.gz
│   ├── 2540e583c3f68dec71761f9bc6275d2b4c8c36f6.nq.gz
│   ├── 276c7e5e06bcf6635c7eace9cbc8092145f978db.nq.gz
│   ├── 2d46305a68da4b9569bf6813f4d2fb1131653842.nq.gz
│   ├── 2df98fbcac88d8d93c9d18648ba7d5a800100ce0.nq.gz
│   ├── 2fcf869f97e3db32d04bba2de14fc59596538076.nq.gz
│   ├── 30571233ab2743c8bfa278db17f69b884823c94f.nq.gz
│   ├── 35ec8f1917b21691560159f7e6051600f0674f58.nq.gz
│   ├── 3ec3220b9540eaf73e3bcbbc81a1cd5fdafe05b4.nq.gz
│   ├── 42d6119cf0fd2770783a295d0f6741b13179ae49.nq.gz
│   ├── 431d8d94a22bdba81ff2bbaa87ebd4b77e1d0d90.nq.gz
│   ├── 461f7e3d73ca89f0dee46d673a8057f563b9873f.nq.gz
│   ├── 51587578d052005002f5e1f131bfeb180807caed.nq.gz
│   ├── 51ff4f43a47909d082b78a4ea2e13d050049c8e0.nq.gz
│   ├── 5b25a00f43bcb9d2a68e49250995865e6608c26c.nq.gz
│   ├── 61935e5d49e2b4f90babe55d6bda7b7401cfc1b9.nq.gz
│   ├── 6f0f2faf32486394750d5d5421e2261430b73fef.nq.gz
│   ├── 7178622b080073eb79831b0a9b4668cd0eea00c7.nq.gz
│   ├── 73145eec7e2a896212b2a9165dcc7449f0abd318.nq.gz
│   ├── 79c610e3a06d02ceb11eed2e676f0abb9412d302.nq.gz
│   ├── 7fd71bc1a81305b9dd3602e0ca7a4a119b534862.nq.gz
│   ├── 812789e68bf5688ca56d42a80caecd04c1e0c4b4.nq.gz
│   ├── 82377e2175cb6a3e81bcd4650e4c158db89a8004.nq.gz
│   ├── 8c86871a50570ad74b54e31868d789df050ca604.nq.gz
│   ├── 8cd5e0ed09d97da6245eaf8bc39fa9d8b3cde307.nq.gz
│   ├── 8d60bde44f593de045c071d0763eee8b0d45a52d.nq.gz
│   ├── 8e568c33b8ab047b7b5a9cabc9381106a79ed35a.nq.gz
│   ├── 92ac8ec5dbe177b6e29da9600c7c3fd18d8069b9.nq.gz
│   ├── 975b5155b41e7a36c392dcf7ab0f7d690967de33.nq.gz
│   ├── 97724fa80f2fd81fddb1eb8b00029dc4fee78054.nq.gz
│   ├── 98cbfdd106f6af898b9ceed1ec1f707b532c5173.nq.gz
│   ├── 9aedc4ef377cc9037726a9d3f5ca5e69164598bf.nq.gz
│   ├── a09379f1b6893041a9e5249ae2b8e054b532cd23.nq.gz
│   ├── aacbe59290f38cae9a3b0f007ee63a5a9942c3fa.nq.gz
│   ├── b149d0120334ec19001efdbd479598561952c3a9.nq.gz
│   ├── b56a2866c098400c2cdb660aa908a99bfd0cba34.nq.gz
│   ├── b63b22aa06d54d54df46220aab865275b436abfa.nq.gz
│   ├── bb98d20109b93f40fad6947fa519cdeb8d16de86.nq.gz
│   ├── c2eda0df52a5c1bd708ad342b50fcc917be81192.nq.gz
│   ├── c4a180a3325cd3b07f80af8b9720a194260373a6.nq.gz
│   ├── c57f4729957d36feee74f8eb89c17558d4c83f1e.nq.gz
│   ├── c65d0760f4fb09c08e4ceb3ba4258594d98e1b1d.nq.gz
│   ├── dc711a48b9bd2f8029f3af22e74526a2cb8661f3.nq.gz
│   ├── dc9a8f17c6e3f0117661042120c4413a21065bce.nq.gz
│   ├── e3d28b38c94eeb9fa2ea0a955d3ff31c8c3ef6e6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6bb5b91b56c550fab69e0f2898006069366f3da.nq.gz
│   ├── eec7743363931f04ad6857c54118f9ec7cd3e82b.nq.gz
│   ├── f072271cb235e97740a9887ebc76955c62749a18.nq.gz
│   ├── f6ab1aa2cdbbb6aa245be35e5090520815c3f7ef.nq.gz
│   ├── f83d14f376a903bb31c47af967b1494787960e54.nq.gz
│   ├── f97321a5d0ecc1a536fc3eeca5a23f446efb07bd.nq.gz
│   ├── fa682f1a5c7e25d0900b7320f7e2dd2fefc1533b.nq.gz
│   └── ffda481c3f47d4924c963aa5adcf5896fc3f9bb6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cf49f4e23ac1b9eac99bddaa67aeb72d25027a63.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 67 files
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

[mkdocstrings/griffe-inherited-docstrings](https://github.com/mkdocstrings/griffe-inherited-docstrings)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
