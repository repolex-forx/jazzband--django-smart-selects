# Repolex Knowledge Graph of jazzband/django-smart-selects

RDF knowledge graph data for [jazzband/django-smart-selects](https://github.com/jazzband/django-smart-selects), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-smart-selects
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 780c1dfc2bb2868f7ad436345c480fa28e2db2bf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 780c1dfc2bb2868f7ad436345c480fa28e2db2bf
│           └── chunk-001.nq.gz
├── blob
│   ├── 022570239c27b0c2644be8b7a80dc7afb6605e1d.nq.gz
│   ├── 0655b2b29110f12fb9cb374a4287a7849333c911.nq.gz
│   ├── 0789ed9571c6475e6fc8a85084f5f50ca6ab2b26.nq.gz
│   ├── 0813055bfaf444e7373421d388ddc6c4012aca12.nq.gz
│   ├── 08f18be506915529411378fa1c639595ac398bce.nq.gz
│   ├── 1912e77a6df02116c3ae0328b5085dfe841c2f6e.nq.gz
│   ├── 19235ae5958cb045112afa89cf83a1eb8111c860.nq.gz
│   ├── 1c92f6fa975c383fc87ff3fd5922d4e914747304.nq.gz
│   ├── 244584615543802f33c8c8c882e0ce3b9de4b06e.nq.gz
│   ├── 26be5218cd9090025925bf568d4b24a2cf0f2bd0.nq.gz
│   ├── 2a1973d11919e9c5e92ed26dbb184dd419b51a28.nq.gz
│   ├── 2f9ea9b4d0415aeeb4067b33199bdde0203b631d.nq.gz
│   ├── 390d307cab1b2f00e0b2bb16c0e512e05bf5626f.nq.gz
│   ├── 3b9b9c62612fc3b4ef6c963c5906c2bd3983e550.nq.gz
│   ├── 3c16364c4227cb56c873cd4f35efa7719f5241d8.nq.gz
│   ├── 3e93e49c83ad48315ff52e73b97ecb091850fde9.nq.gz
│   ├── 3f5a038c2901774121150403f9ef90cbb2821da0.nq.gz
│   ├── 547e56d051b5e6f7833bf1fcd4ca270621f2265e.nq.gz
│   ├── 554e516564cd2233be96bfbdd7a57dbc7b2cde30.nq.gz
│   ├── 58557b6704bb2062f7e423f49cd6d54111784ac9.nq.gz
│   ├── 599b6a82cfd835b565cbda054802f46787fce6cf.nq.gz
│   ├── 616302dde0a7ed895118bfb49af9e1e252b81a95.nq.gz
│   ├── 6fabef73064643fb32a55b3de83e6522da43dc4a.nq.gz
│   ├── 761f7abf688c0e9d1549802ff068625b5e589479.nq.gz
│   ├── 767460167ffb3e965e170c75665f337981c7ed75.nq.gz
│   ├── 780617976484a97e815425afab4a46d49050f91c.nq.gz
│   ├── 78d6b5fde78379f565890014ecd62b0e30be8636.nq.gz
│   ├── 808ae3d760bbb3705a29d949d05066d8a551ed85.nq.gz
│   ├── 83a1c1ea73ee3495098652610ab803013680959c.nq.gz
│   ├── 928a0aa8be12f8f96368b7050cf388458c0180d0.nq.gz
│   ├── 980750f6a4100c7698214e819a5dff49fdd45bfa.nq.gz
│   ├── 99a4cbb9b4edb2ee3bb64d740515557122306a3d.nq.gz
│   ├── 99d5f8185c1d369f070e586a65d62e7ff0a525e7.nq.gz
│   ├── a62c20941dc15b2668ca4f84605cc6742c1d16cb.nq.gz
│   ├── a6c82500e7f7aef66513a35fdacc494b84dc2cbb.nq.gz
│   ├── accb8cce51db0fb831ec4605acb59d76225e690b.nq.gz
│   ├── ad78220bf6ae7568b9e1aff6428f7851beaa7865.nq.gz
│   ├── aeaa1a80c505025b0af81f88cdecc795265d8230.nq.gz
│   ├── aeab7eb10269b3267c503bf5c787b2aa70bed1b6.nq.gz
│   ├── b0e36ea623106e4a915f49ea1178899f47bf059c.nq.gz
│   ├── b46ca66af1fd91be9a7a54d333feee3b688575a9.nq.gz
│   ├── c08b16fa59d53ec3b6ed46bd9daad56a7898bf86.nq.gz
│   ├── c3731f3165b5199cc045fce61d35c348c6d8e972.nq.gz
│   ├── c3c504c6f38f7518b9180d6c1a4ef4372376a6fe.nq.gz
│   ├── c91aecb0ef19505b4f5694c92a07aa889d549214.nq.gz
│   ├── ca804cc87638904511234d95c9011133c863280a.nq.gz
│   ├── cccae9ad941273e7ee70717054fd5f2234df66a9.nq.gz
│   ├── ce62732dd83c24a7077c8b0c17c1b1b897e8d0c9.nq.gz
│   ├── dce76513d4119fa7a14c3d1ad9d5978bee266a23.nq.gz
│   ├── ddf21237ba0cc748f0683b5d302ce0d2a8afe715.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e68cd8fafa5e05c5482c52eb24f60966c4fa6bb8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f0b3a971ea662fa91f97890104b280ab2c0d9b8e.nq.gz
│   ├── fde784aeeb2a4fde8d08974a5dd1f55667f30d9f.nq.gz
│   └── fe326c8d7d106a3aec5dc5ab6a0c1c22605467b0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 780c1dfc2bb2868f7ad436345c480fa28e2db2bf.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 64 files
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

[jazzband/django-smart-selects](https://github.com/jazzband/django-smart-selects)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
