# Repolex Knowledge Graph of jupyterhub/dockerspawner

RDF knowledge graph data for [jupyterhub/dockerspawner](https://github.com/jupyterhub/dockerspawner), parsed by [repolex](https://repolex.ai).

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
rlex download jupyterhub/dockerspawner
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a73d0de667e43a6967d4c870c00d6b11c9a0dd17
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a73d0de667e43a6967d4c870c00d6b11c9a0dd17
│           └── chunk-001.nq.gz
├── blob
│   ├── 02d8327ae43be8a9e173fbdf9c7d7d03e4e00ca7.nq.gz
│   ├── 0dc89813dc10ed07777226c26d348a19ce3afb93.nq.gz
│   ├── 105ed330b1f58360b1d5c591a560e2b10f93b030.nq.gz
│   ├── 14f97e7d3649965d83150a7a1d38fc4827fd1cd9.nq.gz
│   ├── 1964791af0db3b718839d87b5327900af8213052.nq.gz
│   ├── 1c2c4c366a596564c8f28f7c3a1893d3905cd5c0.nq.gz
│   ├── 207818fc98fc25c21e9d190e12a3f7267da9ae67.nq.gz
│   ├── 2198ff649d46eb1c6ae46eb52dbbe9dffe9ec5b6.nq.gz
│   ├── 2ec40de2f76d5c01e2f44953c95b1d5b04384364.nq.gz
│   ├── 342fbfea0cca17995fe472fe69b876fa53d42dcd.nq.gz
│   ├── 3e2444fbcdb2038f4fbb4fbdcf0262e6c1448fbe.nq.gz
│   ├── 3f6ecd224ee63e0b551bde0e10f212a6123bcb04.nq.gz
│   ├── 407decba689604de01fdd7044be4992c3e53aa5f.nq.gz
│   ├── 454af4953d5b77d6392058906ff170dd55939bda.nq.gz
│   ├── 46caeb217ee9eb3b2f996dc791e0c377d2646d90.nq.gz
│   ├── 4a0db052fa272420a781d626bb55458cf3b72e3a.nq.gz
│   ├── 4d17fbd2ee134deedb9440f1536f8b4988c46346.nq.gz
│   ├── 4e835db53c49355fa593d4eed51b496326ead2ce.nq.gz
│   ├── 50706ee4b1175787830d42e5e187257b9f978fb2.nq.gz
│   ├── 583b72b922cdf8bdfcf2bede30f59910f094ae03.nq.gz
│   ├── 58654bf9ccba069a0420e1a18b45742433fd8778.nq.gz
│   ├── 5a5fe86db443150dfd303496e6ad1436de8bc878.nq.gz
│   ├── 5f4498516b0c1853280c2fe0eca0cab235d31468.nq.gz
│   ├── 60f0a384d5b66c7a40e27d260bb83b102adece9f.nq.gz
│   ├── 6135b1367eaa1c189dfd3361babe7a49330b99a7.nq.gz
│   ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
│   ├── 656e15f1386d18a3c9c380b9842aad2b0c0b4ccd.nq.gz
│   ├── 67e57c010580dea0640e1fa88531069cf5758f1e.nq.gz
│   ├── 68d0f782421fcb94d6a9944d1d64fb0bd2b88d12.nq.gz
│   ├── 71c265a6f6e0e632b1a696340ba7577f90999bde.nq.gz
│   ├── 71f5216d1eb416d49fdd2d9d67510ddf4c759659.nq.gz
│   ├── 7acb78df0d5f57298fdfa0002235c2e5e105f0cb.nq.gz
│   ├── 8031851cf9a6f9f7252ab598a6d28a9f43fb3e04.nq.gz
│   ├── 8119da573dde446c69357eb69ed46eeb48fc5a40.nq.gz
│   ├── 81223b4b4024154b890496af8ffe04bca43d0211.nq.gz
│   ├── 815a9af14e2dd40f998a82afe49089c84b973810.nq.gz
│   ├── 82999e0430725d5bab3dda8028720ce347060ac1.nq.gz
│   ├── 868bc01653c9fc97c83b58180b1807029464fba4.nq.gz
│   ├── 88f38f7ba7e09c41f80c17d58b45167f79f3c59d.nq.gz
│   ├── 8c4ee9eff8f69510f61bcca9e49216f57bce690e.nq.gz
│   ├── 8d34bf0659e125f777c98cf96b58f11b755c5bef.nq.gz
│   ├── 9021fb51e4a26eeff7e0aa75f9f26d9860344684.nq.gz
│   ├── a08d1ce7c8424ed00faf79849238ac4ecca22029.nq.gz
│   ├── a3271af092e006b6a560a81e4da3e0ff714558cd.nq.gz
│   ├── a86350a27d4eda99524d202bef4e15580d69198f.nq.gz
│   ├── b303ecb58e97ca29d8dc9c3b586754f610633388.nq.gz
│   ├── b6e837bed2772b80bd39ecde591a2444cccc8166.nq.gz
│   ├── b9916dfc3d2c3ae233df90118a81e85c971e00a7.nq.gz
│   ├── bc25caf4e882f50939c947f2199827c326be1fd2.nq.gz
│   ├── bee74fdbdec04e9a0ace83635b0013c33124c04b.nq.gz
│   ├── bf704d801ce2de14625e91235ad8718206ffed74.nq.gz
│   ├── c28140723bff3b5cf0136e8f819efbf98292a12b.nq.gz
│   ├── c51ee83461aa74851b5f08a7d01a83d220f80377.nq.gz
│   ├── c55401a9e23d46faf2478ea1df86c6ef13b6faaf.nq.gz
│   ├── cb4368b544cedada66bd9e766530d51fc4f7e07e.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── d9a7ce1ef6ee7663a1f2e6352053555ac0a98574.nq.gz
│   ├── e187a550f25e0292b89708a49befbae02db1b306.nq.gz
│   ├── e578a690595c0709850eeeb6e370a0cbf31503f6.nq.gz
│   ├── f1c6db6a0db83cbc560c8301465a8812d72ab966.nq.gz
│   └── ffdf84e2314ca24a8b508642368dbba3bc61c7cc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a73d0de667e43a6967d4c870c00d6b11c9a0dd17.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 69 files
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

[jupyterhub/dockerspawner](https://github.com/jupyterhub/dockerspawner)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
