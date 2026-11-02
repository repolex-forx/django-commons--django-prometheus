# Repolex Knowledge Graph of django-commons/django-prometheus

RDF knowledge graph data for [django-commons/django-prometheus](https://github.com/django-commons/django-prometheus), parsed by [repolex](https://repolex.ai).

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
rlex download django-commons/django-prometheus
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5093c6366d1c88f0597bf9cbdcb40e09e9f56c8b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5093c6366d1c88f0597bf9cbdcb40e09e9f56c8b
│           └── chunk-001.nq.gz
├── blob
│   ├── 06ddef5612f8675c4bc3d1d91d62334a8b5be11c.nq.gz
│   ├── 0f898663a7ee21be1a5bca892b9f5f4c07f03168.nq.gz
│   ├── 1138f84cdfd5382f3cafe4bf9946862744190907.nq.gz
│   ├── 1e96e430f515b2a8a59a126bb8c12bf54b39c161.nq.gz
│   ├── 222ec8163a9821a6ad80bacc64a0bf58ae9f3efe.nq.gz
│   ├── 23651927445f8630f46b1c6f04284fc0f9280de8.nq.gz
│   ├── 23e8ae0dda5645cfdd48f6eebf727cdecf8bfe2e.nq.gz
│   ├── 24bd5a43afc2281aac02deaafa6b38a9fe6c3748.nq.gz
│   ├── 292df53d9abf69abeed292d45a623901a8fb6651.nq.gz
│   ├── 2aa4eacdf4b5f13c8b583e31af0ac3232d9bfc22.nq.gz
│   ├── 3664d028d9599cb9a8b4215490fea409ee6cbc36.nq.gz
│   ├── 3761a1fbf71a95b2b148a31d1050e5d326d35815.nq.gz
│   ├── 39df0de3db05ab4616dd6abd27587bec500bbb03.nq.gz
│   ├── 3d3793f4bf76ccd94db4d3d9ba7199d4c43be451.nq.gz
│   ├── 44e4845cd530df166ba12fc5cd6421abd3394034.nq.gz
│   ├── 47d8abb038b4671f1444a0738af1cdd34cfe7697.nq.gz
│   ├── 48c5034db576fc34d939b4edc9b4344a42ec7093.nq.gz
│   ├── 49231f6798406a87765878c8398b1e78cdda41eb.nq.gz
│   ├── 4eb3dab96a3d7c0c28a8c18531f0570fa4694488.nq.gz
│   ├── 534ffeb9247bae1e8bb661c593cab10a2d422ed2.nq.gz
│   ├── 539608f1f7777c57e48b07692be51961351c2544.nq.gz
│   ├── 54d6e04da3f53aa8f85874eac7a0e2e9db06d895.nq.gz
│   ├── 54d722d4ca84be2a4979f7d2f969a96acf873200.nq.gz
│   ├── 5e520520ab7482aa7c201c43fae2a50d997c1f10.nq.gz
│   ├── 604ece0820d5fb96935007f4a7c9a7070dc3468d.nq.gz
│   ├── 60e7a3e9d842c2d3d828cc7ed21ced0bf7bb631d.nq.gz
│   ├── 61f34d276b98f6c7329d754942e98fe104877ad5.nq.gz
│   ├── 6a7ce8c9905305f4b51dd780968002b201bdb314.nq.gz
│   ├── 6e9e8c421b6a10252bff4be2ac29d3d762142a70.nq.gz
│   ├── 78a7cb17b093728dcb4ece8498de2bfc5bf20743.nq.gz
│   ├── 8292413a9a2d57803534727c92601ccf0487d63b.nq.gz
│   ├── 85393936199a693b26fcebae8172288c06a4b880.nq.gz
│   ├── 8dada3edaf50dbc082c9a125058f25def75e625a.nq.gz
│   ├── a179337e07875c7ae299a4e894b4339fb6258033.nq.gz
│   ├── a2152e0b970badc35431d863a32c10f9eac13ba8.nq.gz
│   ├── a49c289b1ed99b0dab4499c118319531cf2061b0.nq.gz
│   ├── b4be737b2c2c3e1b54ffbc6935a74b1bb7144349.nq.gz
│   ├── b777ed764f840ef597ceae8e0406d25466c3f554.nq.gz
│   ├── ba222eb91d2ee9c4221edc50d779bc80ec0c534f.nq.gz
│   ├── c1a7121c1bd6c9648bc686c95b1c7a94dd69cdd3.nq.gz
│   ├── c5e237bdc674e7692ce5cacd34e7e9f5a92187e7.nq.gz
│   ├── c87e7c9c879812a0a95f15c8df634e1776ef7ff0.nq.gz
│   ├── cca58c0f783c36dc403ccdf002ef8cc13ae470f9.nq.gz
│   ├── cf085c3c3c0fff628cf835cbcaaaf4a56a1df151.nq.gz
│   ├── d158a2ce09c1dc9191c29318a94b51070b64434a.nq.gz
│   ├── d4473ed9536c6a832b155ff96c69713dfdc9fe06.nq.gz
│   ├── d6b1c6d04f324c12a3a836990f1e34be6b96f2f6.nq.gz
│   ├── d73a26ec302978f367063ef346aa6c95caa478b7.nq.gz
│   ├── d962141dfeb8229d060722be39bb2d846a4f7298.nq.gz
│   ├── dced90158964d54f916339329eec528d18c91ec2.nq.gz
│   ├── df33b372dd886f41ed58db28c5244ff8862f4724.nq.gz
│   ├── e1dfcec6f6fbadc7a70a452ee847fc725f4384ae.nq.gz
│   ├── e264db364bd492a96d179de51d3a32848f9d445d.nq.gz
│   ├── e29a5c6261a5f9b3e2ef8481dda2b696fc99c86d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e83eab4a0546681067aa4e3cad0338839ac003e6.nq.gz
│   ├── eb71e414e76bf3b25456f982be688c62e79e4ad4.nq.gz
│   ├── ebd135468f14fb407bb77cbd2d1978aa19db6d2f.nq.gz
│   ├── ed8e8e9facd91d51dd84728d6b1be445a8016aec.nq.gz
│   ├── eeaa3d605c52479d5b211b0d0428a71d016714ac.nq.gz
│   ├── ef53478b23a39e724a58d200e43ec135c6a1be17.nq.gz
│   ├── f1e6ac583811b946405c1791fcd64168a24fb153.nq.gz
│   ├── f23a7d2fb9949abbe37a4d13d6aaa678ed44f74e.nq.gz
│   ├── f2ad705dd27aa911f619ef8933f71025fd10dd6e.nq.gz
│   ├── f578d5f46e1a0c2f0141f988bc553cdbe2af774b.nq.gz
│   ├── f673d46345d84a20e09632fc24dc39ae3ff55517.nq.gz
│   ├── faf00661c2f98e498e21b970254d7e919970dd2e.nq.gz
│   └── fffbfeb0820e817437bc9957ea169b7ca5c2ff3b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5093c6366d1c88f0597bf9cbdcb40e09e9f56c8b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 76 files
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

[django-commons/django-prometheus](https://github.com/django-commons/django-prometheus)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
