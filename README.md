# Repolex Knowledge Graph of ray-project/travis-tracker-v2

RDF knowledge graph data for [ray-project/travis-tracker-v2](https://github.com/ray-project/travis-tracker-v2), parsed by [repolex](https://repolex.ai).

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
rlex download ray-project/travis-tracker-v2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a2e4a6f2e745ba497480e69b476c3a0e98976354
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a2e4a6f2e745ba497480e69b476c3a0e98976354
│           └── chunk-001.nq.gz
├── blob
│   ├── 01d6609040a093f59ecbaaecc46a660ac0dd6cfd.nq.gz
│   ├── 02ccdf2c7e4579137febfdc4bb7443d316b21e02.nq.gz
│   ├── 0b5245e85c7d56a64ea136123d8fd61828df2448.nq.gz
│   ├── 0f5c4bc5b518e2ba429dfa59db9c52729074ebe4.nq.gz
│   ├── 12d178c609f3c05618c463254659483794f4ad22.nq.gz
│   ├── 239786e5eae553957978011fb90985b7b197524a.nq.gz
│   ├── 2e23fae450235cc8f1421fe6646fc791bf82f25f.nq.gz
│   ├── 3f08733a15a9c57c396e9f584539c08d4fa99581.nq.gz
│   ├── 3f2972b3ea13eed4e2ef0952db9adc45a3158fe3.nq.gz
│   ├── 461e4f799e89b6f2e2fc0de911a0b5386d976e5b.nq.gz
│   ├── 4f179a6d9cac3853d20ad5abe016a389dc523570.nq.gz
│   ├── 50bb247b719b60f941ed3a8254e413ad891cbfee.nq.gz
│   ├── 51f48e7c89e227cdc7a629cb99cf588a0afd7140.nq.gz
│   ├── 57a1cde31e198c5441c18d40a436307069f45dda.nq.gz
│   ├── 580aa6d31a872695e45648e91a169cef08c9a554.nq.gz
│   ├── 593b28e3c85fc25253d2c273066ab083b677c5a3.nq.gz
│   ├── 5d0964c01d09b029b3ec9c7924fb9e60c8cef426.nq.gz
│   ├── 5d26662b2d688c92f5823a7e3d1d80f11e5e656f.nq.gz
│   ├── 69e179d78ff94a3ab764db2e54d35b9c7ecb08f8.nq.gz
│   ├── 6f214b034d8a65439d21fa33b4e87cda9dbf3b47.nq.gz
│   ├── 6fe06196a5ac6f1a2856174bed0d46e4e5a947a0.nq.gz
│   ├── 73be8a3456f56a454d5735c59dc30a08410693ca.nq.gz
│   ├── 768d6091e641c58aad5b2af22c296da480ccda17.nq.gz
│   ├── 7de2966309b7cde7f1356767fc61a13a6074954c.nq.gz
│   ├── 7e24e4304cc6ad6c82f252332733b79da5a2a7ff.nq.gz
│   ├── 86c25186aa61d531c4226a8bdeb8fa89ee6c2553.nq.gz
│   ├── 894f5b46269d661fd7322b1f5696678232a73eb6.nq.gz
│   ├── 8d6052c3cda553c294f2a659ff691f3631a60969.nq.gz
│   ├── 919512ca3f5bf5c5884a3f0fcc6a9992296e2cbe.nq.gz
│   ├── 98300653a33ef8e729e53a0a3253f50171865e73.nq.gz
│   ├── 9d0379fb7a6eef66a32eaa87499d48a9c10f5dde.nq.gz
│   ├── a0bdcbc6e0320c2a7c27aa4ab4f8f6704d9fd173.nq.gz
│   ├── a42479a9eb7e1bc8482950591470cd091199a30e.nq.gz
│   ├── a7e4be1cbfdd7a83da403dc72bb28fd3b5efcfd8.nq.gz
│   ├── a84321b3af5f9d854fdd505a788fe616962a1f79.nq.gz
│   ├── aa261df6ba4db2da41e390574791e756f8359488.nq.gz
│   ├── b54ddf7e4eeaac743c71c4fe55b88b184f6e2723.nq.gz
│   ├── bbfb21d513c2a1acae77fc9926fc95f30544685c.nq.gz
│   ├── bcd26f9bbe6c5ef4c6a88cad3e9b6b425881cb69.nq.gz
│   ├── c0d7ee6ff9062cf61151dae420489a4e13474a49.nq.gz
│   ├── c4400d5b72e6391b04411b6785511a9e1e828a1b.nq.gz
│   ├── cf779ffd0866d6133d9ff936d697cef22140ca52.nq.gz
│   ├── d67f337ea1b5d3c4e8220713bd9cf11800a11b7a.nq.gz
│   ├── d8fe68ed90daf31e7638280b28c2f93ebf31537a.nq.gz
│   ├── d9aad4b196495656281184b8f259b8cdb2ce07b7.nq.gz
│   ├── e097847c9c3e412042a9f50811f8a52719341384.nq.gz
│   ├── e4966b72a9359a05d5533a1b389ecf0585601509.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e798faef6e4b319510d2864c07a6a96c4c620782.nq.gz
│   ├── ea6ff545a246caa64074ba809bbc86fcb8589071.nq.gz
│   ├── ea987c5b23d6682d757370d0a4eac2e5826f115d.nq.gz
│   ├── eb9b4ed64c9ecfb34844e4e15b1fd30ef1ab053b.nq.gz
│   ├── f10a8af84e7588fd9efa391caed9710f358815f0.nq.gz
│   ├── f1cdfc4ac904b2b2906feffb1f7108f6a0d166e3.nq.gz
│   ├── f7ad685f35788e84e519a027e761a97b16c08da8.nq.gz
│   ├── f98b69d19a8252bfd7c1c3a4d2a580e760314f54.nq.gz
│   └── f9b64f1bcb3be580da52f76c7bb2150ecdf1ecb8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a2e4a6f2e745ba497480e69b476c3a0e98976354.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 65 files
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

[ray-project/travis-tracker-v2](https://github.com/ray-project/travis-tracker-v2)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
