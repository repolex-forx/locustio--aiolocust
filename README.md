# Repolex Knowledge Graph of locustio/aiolocust

RDF knowledge graph data for [locustio/aiolocust](https://github.com/locustio/aiolocust), parsed by [repolex](https://repolex.ai).

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
rlex download locustio/aiolocust
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9b5eb4721c2a496ae7715e19fa95064a2510302b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9b5eb4721c2a496ae7715e19fa95064a2510302b
│           └── chunk-001.nq.gz
├── blob
│   ├── 0eacef7505163fea60b8c0d12661abfed88eab7f.nq.gz
│   ├── 0eb4d887f996990ab70ee5ce60a84ed118d6d14c.nq.gz
│   ├── 14d347500cc5a24873d9ed4b4cdbfe989e32036d.nq.gz
│   ├── 1640feb2cdb56281e3dcb53f644bb216935b6f0e.nq.gz
│   ├── 1aa0049792a2e01a800126c9dbc3d4675a92c89c.nq.gz
│   ├── 1bc45297d308bbd4028581eb4ae4fb9dd29b4a26.nq.gz
│   ├── 235c8484ca8fc10ecbc4523aad64213cee8b6e3e.nq.gz
│   ├── 23a898c2b0c08698b07f353569b0f252621fae9e.nq.gz
│   ├── 2534308d69ee6cd7183384327b84beda0fcbc02a.nq.gz
│   ├── 259a6f2df5791d16a8fd801a85864b6c8cfd4657.nq.gz
│   ├── 40b33493815ba54654aa584df4cc8d313b116f08.nq.gz
│   ├── 485b9bdfa2844d380cd16eb4d95605a0a1f0f34f.nq.gz
│   ├── 48ab01850fec6c2b60dbe852cad714fcd1aa51d6.nq.gz
│   ├── 48cb5b7befb62e32562e0808c60f516c2b42f81e.nq.gz
│   ├── 51cea35137c51b1994f23518cffd8e819c21a838.nq.gz
│   ├── 56930427aef3d9fadf68b040a52d3adfb169e252.nq.gz
│   ├── 593de55be6e2dfcdb570cdf7baf1cc807af67b11.nq.gz
│   ├── 59489fb9b36d2be3915794649ad6f9e96e50ac0c.nq.gz
│   ├── 5a255259f34de479a2bd83cd60c6aa560f2da043.nq.gz
│   ├── 661eb0fcc37878e1c3facbc808dcb09ff58ec392.nq.gz
│   ├── 66241e7cd098773556617bd72b4029cf01ba35d0.nq.gz
│   ├── 671411a6c5831f4784ddb22354f224368acad3d5.nq.gz
│   ├── 711fd52a8112bcaefef8b0a11c0aba34ec0fafe2.nq.gz
│   ├── 72d6af216c49e1430a4ce7ceec4ad83444760a49.nq.gz
│   ├── 74d53e8aac3ba4788b2e7b294ebe56dbf1974869.nq.gz
│   ├── 9e939015f0bb6ee5849519adb0cc0ddba4e2e9bd.nq.gz
│   ├── a32b4704b5dc3c7a5d801056ff6cbc5ebe02b6d1.nq.gz
│   ├── a5e710934889f5e0493c08d7b0203e1c1556aee7.nq.gz
│   ├── a6302781c0f9467df4fafd23a746f8c2411bb524.nq.gz
│   ├── aa0f19f2c2e6bad60ea74329edb4849dafb23c68.nq.gz
│   ├── afc8a59e71893545846fba3f4ac3c92d0e81b259.nq.gz
│   ├── b13a3cef677b59bc92edbe6c30d509412c705a0c.nq.gz
│   ├── b18f070e2b12bab5b4e2edc824d5b763408d9867.nq.gz
│   ├── bb650f60b7d940a3c7565c5686a0311b36530091.nq.gz
│   ├── bc1771208d8fdddc8d391dae23d86f99f75f384c.nq.gz
│   ├── c341f8a7689417a267153d7456b3da0b2d85d1db.nq.gz
│   ├── d0f9a3a7ef747b3ce22b0dd5d2a431e9b97d32e4.nq.gz
│   ├── d5629d4841ea3158cbfe627a62689f1ecd44dbc9.nq.gz
│   ├── d9bfa74bd2eb8e1d981be37a09dc5649c9709b7b.nq.gz
│   ├── d9cd329848934a30adeae8cb19507b38719bcd69.nq.gz
│   ├── e229b2666faf843e37bad999e1537ce5c596be20.nq.gz
│   ├── e5950aa3c0fdb3f7f1735612aaa984fc0ce03333.nq.gz
│   ├── e5ceda0df872005567b8b944d79652b1e49401bb.nq.gz
│   ├── e611b542f2028c5e27f1e94123ec4ac56c7b49b0.nq.gz
│   ├── e65d00c011917f595dce18a4fa9867e50e698bdf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec87ad8987223a1e76fde934b071867b405e078e.nq.gz
│   ├── f0435c7c651fbe57f31499c90d67665d6e4e3a9f.nq.gz
│   ├── f3afeaa307e1bbc643d950cd9180279b4892c658.nq.gz
│   ├── f8a14da7c09cfd3faf4f5121b1b9ac497b60f18c.nq.gz
│   ├── fdb6387061ecaa3cdf4d9e8c5a48c9727e213433.nq.gz
│   └── ff7b397b15ed95fa82ca8fdd81fcd2bbff9bff92.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9b5eb4721c2a496ae7715e19fa95064a2510302b.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 59 files
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

[locustio/aiolocust](https://github.com/locustio/aiolocust)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
