# Repolex Knowledge Graph of pydantic/pydantic-stack-demo

RDF knowledge graph data for [pydantic/pydantic-stack-demo](https://github.com/pydantic/pydantic-stack-demo), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/pydantic-stack-demo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5048e75c2390f60dbff90c94669939ff4f762e14
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5048e75c2390f60dbff90c94669939ff4f762e14
│           └── chunk-001.nq.gz
├── blob
│   ├── 02c819fd40f4d928c20ab42c67f02fc3b423a6c1.nq.gz
│   ├── 08304a8c708ce9affface8305ff0de44da30ca4f.nq.gz
│   ├── 1ca060bf2091c4389d1a50f6be677ef460f8024a.nq.gz
│   ├── 20dab857bc0b757b42e87ecebc996184630335ad.nq.gz
│   ├── 21f1906fd90d9346b3edd4a231a91a649f0dee22.nq.gz
│   ├── 227a6c6723b6136d17cdcd42288a01a5e5abcd25.nq.gz
│   ├── 351396cfa3313be763b636399c0622ba2ae81bb0.nq.gz
│   ├── 377524015af165f727a4c3cd3e9bf6fcd7612cbb.nq.gz
│   ├── 417f40e6eaf9e3e9d1eca6da2cb6b4f46718cb07.nq.gz
│   ├── 4d3513966d05e855ffcd7ae8324d4f335f2e056f.nq.gz
│   ├── 519d83b91a9bac18e2d336eb6d8a224601859913.nq.gz
│   ├── 5c2d8056ca0acfa7e04e9c0638b621b6de3e0c92.nq.gz
│   ├── 5f157f5592e540c8e89a93bb2191122579d842f8.nq.gz
│   ├── 6200ddf45cb61d772bf7068ee0195b4e412a359c.nq.gz
│   ├── 639311aca0afd2dcd97ca65fb68ca4852b277a22.nq.gz
│   ├── 644137623384cf76786dc1e893c084ef4abb0c38.nq.gz
│   ├── 652fe8dcd49bcce4af0f7feca5ec646631b986c5.nq.gz
│   ├── 69d070bb068d22cdb01f51f72faf2a3b94a6c59d.nq.gz
│   ├── 6b5f5f5cfeae6d58615c0f07afae6bb96968dd44.nq.gz
│   ├── 6edc5a20f3f9d45f8696ff1a83587534c4cccbae.nq.gz
│   ├── 772bb464a1fca810cd26327d36442f9ac06cbd0d.nq.gz
│   ├── 791717237302fc5c9930c1dddfe69aa9e3397378.nq.gz
│   ├── 8104fc57f2286d8ef66b3756eff63d1768623862.nq.gz
│   ├── 830c9105098bca8bd46f9e9be850bf198bed5683.nq.gz
│   ├── 89780aaf5c37fc43e9baaf14b246a6ab4104c57a.nq.gz
│   ├── 8b0f57b91aeb45c54467e29f983a0893dc83c4d9.nq.gz
│   ├── 923317c44fc06101681b9b9be7babe310ee3728f.nq.gz
│   ├── 93a9b20d4e60ed65f79e62680cb26f83903b98e8.nq.gz
│   ├── 9c452d1da6bfb963c59dc890a4a360697ed6aa13.nq.gz
│   ├── a45e02c010ffe52a6f0de97119655e8e852ee1ef.nq.gz
│   ├── a49ee134dae79dea829488ca5b320e2c365a8b81.nq.gz
│   ├── ab0dbe9ec7641ac73645c3c9b210d0ab01412023.nq.gz
│   ├── adef3aeb79e346f80388f3116776de87919c1627.nq.gz
│   ├── af75844767df11ccb16f51b08410a535727dcdc8.nq.gz
│   ├── b798f23d1a3e9ec5b98d6c93007c5adc673f7f3f.nq.gz
│   ├── c11860f5aede5720456a5906e8e762aad7fb835f.nq.gz
│   ├── c38386bf46578175b1f30e95352ed5d0c5f40dbd.nq.gz
│   ├── cd52505ef2f826a5aaa803292e86c725e60ced16.nq.gz
│   ├── cd9bbc0fb2ac83961f4ed748973b060f0275a475.nq.gz
│   ├── d810776e3964b2d55d71ff122d1765942b97e520.nq.gz
│   ├── d94e7deb72c90f03254225baf04f31b621b4877c.nq.gz
│   ├── d9ef4fee0fc9c67538404798ac282be4b7e80da0.nq.gz
│   ├── e4fba2183587225f216eeada4c78dfab6b2e65f5.nq.gz
│   ├── e5c428d4fc5562224a428d90988259c68e88ba5a.nq.gz
│   ├── e8bc71d874f370833a98484d0a32604f0595de42.nq.gz
│   ├── ec782edf165b01b142fd7a4d6017b334e3612b4c.nq.gz
│   ├── ecf80f2e01da9d6ebfcb3d4ee10d81e842af625e.nq.gz
│   ├── efd453ffdfdf5662479dc0fd55d0d61a77603c30.nq.gz
│   └── fb87f9e0af654e7e39dffbf99074bb3e64c9c9ce.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5048e75c2390f60dbff90c94669939ff4f762e14.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 56 files
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

[pydantic/pydantic-stack-demo](https://github.com/pydantic/pydantic-stack-demo)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
