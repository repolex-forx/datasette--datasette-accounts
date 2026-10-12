# Repolex Knowledge Graph of datasette/datasette-accounts

RDF knowledge graph data for [datasette/datasette-accounts](https://github.com/datasette/datasette-accounts), parsed by [repolex](https://repolex.ai).

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
rlex download datasette/datasette-accounts
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e3bd5c471f26f33b458b8f86c0abc2afbdd8e7b7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e3bd5c471f26f33b458b8f86c0abc2afbdd8e7b7
│           └── chunk-001.nq.gz
├── blob
│   ├── 009306ca94a3ac1068359cc1b02bc2f17312f449.nq.gz
│   ├── 0144f983c3951912cbf29e36aa58de37d8d65337.nq.gz
│   ├── 0515a9c440ecbcb46afc1d486e4d2a0c5b8c4b7a.nq.gz
│   ├── 05a90980b9eb277bb226cf4265fd94b2d1db9923.nq.gz
│   ├── 088a3bfe9358a414e90f97c48237586411d52f6b.nq.gz
│   ├── 0a4f875c37e7683e7ac316908dd8c34f3d580cc3.nq.gz
│   ├── 0ebb840558f0e5cd0f845c128250e9bf70d11603.nq.gz
│   ├── 109b329e27ff578705a5552f212ffea4d28c32c8.nq.gz
│   ├── 10be7924129a4c0f9fdbe92f3f4e9bab53a058a2.nq.gz
│   ├── 10de08747e4778629e1f54271468963e3aa6690b.nq.gz
│   ├── 1281e22688c4e56c19d11cc969f652522c77f99f.nq.gz
│   ├── 15a2ed666629d248d44f6470124bdc292ddf3ca1.nq.gz
│   ├── 19b3c77ff7f1da44e97c0e406944d62a88895bd2.nq.gz
│   ├── 1a0514b5b4df7dbbb59d164154e7ee6d498d9e1f.nq.gz
│   ├── 1ac2b90052c6a0164e6438142180ac80cfc0e719.nq.gz
│   ├── 1c7668b12158b1b61f0420cef8266c1a0003ad31.nq.gz
│   ├── 1dfcc834b01bfe19eeb0b5c110df761c18f15cd5.nq.gz
│   ├── 2025852811a5948e344e5388e28244b90a2edcc1.nq.gz
│   ├── 20d50db65fd1962df05a372b6c17f4f7ae88ddf4.nq.gz
│   ├── 2502ffd2d87b26a2e8fbb9fa32ca6fb635b36a24.nq.gz
│   ├── 2929c2de6b88673c1a98d43ffb924980da618266.nq.gz
│   ├── 2bba900452fb225978e07ba265bda64198feb0f2.nq.gz
│   ├── 2be08fddb1d113d7e82d1fdf6af489f3d0e4d687.nq.gz
│   ├── 2ca0c35737b2e0083707392412106d435af807fe.nq.gz
│   ├── 2d16fcbaa1cbd60d5681d8248ec130e945e4a857.nq.gz
│   ├── 31099d05f6a809df5d6383014efd6e819ad381f5.nq.gz
│   ├── 32e5582a6308e675233e9234f0ce1528a6a24493.nq.gz
│   ├── 331abca3c69e4252316525d9988a270fa74df7e3.nq.gz
│   ├── 335c0314cc1708539e6779f826e6e22763d0e854.nq.gz
│   ├── 361d8f95095b7f12c2d34999547dfa40446857f1.nq.gz
│   ├── 37c3b6da44ccc2afd255405507d7c44b576eb756.nq.gz
│   ├── 37e9677bca55858637ff228ca01e449aded068f7.nq.gz
│   ├── 3850c68ae0dc1e2a0536cce50250bc401835aec9.nq.gz
│   ├── 3851d4769652b652460539b0eb343b992271153d.nq.gz
│   ├── 38824d27bbbfe687352390c68034f856e375650c.nq.gz
│   ├── 39940da3972468459a3d017dc55e78b5112b576b.nq.gz
│   ├── 399e24d17291073e17faacccba3308f51ae04342.nq.gz
│   ├── 39a74ae5e0b84b153712fefc565a6ceeea7f9219.nq.gz
│   ├── 3a5ae9017f7f544cfd406c655b621fffe76c6885.nq.gz
│   ├── 42454affb1acd345fa86325d699390761dd04966.nq.gz
│   ├── 45e00fc5edf66b3e265557a981faaa767dad1318.nq.gz
│   ├── 468f17f4a4d46f093760aded68ce64d4d936329e.nq.gz
│   ├── 46f9782c1690d30ee30d99ba73199701a92d876b.nq.gz
│   ├── 4782f56f0f7cbf420c496ecc5b406ccdd78ce140.nq.gz
│   ├── 4abc0b8ac0fa294c54788617125e97024da52b26.nq.gz
│   ├── 4c75493457ad78d0e7d57024a530231db203aee2.nq.gz
│   ├── 4ce42c5dda7292e0b36eb537701c1e66ff790abb.nq.gz
│   ├── 4ed4888516cc5cae176f58d38cfa724ef7efbb08.nq.gz
│   ├── 525ca08c91957aefc59fda99776a661bba06ef53.nq.gz
│   ├── 565ebdcc2d04b4ccb3198c521a5541377220b5c3.nq.gz
│   ├── 597cfa33fff991c0e077a71ae2e9135e0921c86b.nq.gz
│   ├── 5cec808271cd44ce258a54d7b644a28a760099b2.nq.gz
│   ├── 5e0cb0e1c691f725266d05af93036c887c087cde.nq.gz
│   ├── 64de6907033099d7bb4ac4e40925167ad8a669e4.nq.gz
│   ├── 66e13b21995ee7b4542fae5b96925ade1f48c300.nq.gz
│   ├── 67d8b5ec95a7633fbdaeb6cf59105c7e0ce74238.nq.gz
│   ├── 681311eb9cf453d0faddf3aacaec7357e97ba8e9.nq.gz
│   ├── 6bd7e05d726f719c0f97d1719802f9eb70fd9b03.nq.gz
│   ├── 709288c5076d4c587db2e4c1a719fc704a6957ec.nq.gz
│   ├── 7098f441e93d8353fee5129924138263a2506f42.nq.gz
│   ├── 7afa69b67d64b63b3622c88c1747561932692467.nq.gz
│   ├── 7ca5a8dd2188f76d3b925cfb6537efdb3d17ac8f.nq.gz
│   ├── 7ec162a7019717defd747e96b87481eb75cc10ac.nq.gz
│   ├── 8173354958f5f840f6868c90e31c81db11888c42.nq.gz
│   ├── 88574020248eac12317879e891e901fd041ae4ea.nq.gz
│   ├── 88e3c4974088eb056ab3dce3b0ad8322be7340ee.nq.gz
│   ├── 8ba83f8d71ee7943c02c97ec7ddf3a36fae0479a.nq.gz
│   ├── 936530220a386a250eb14eed5db6ea6612c3e6a6.nq.gz
│   ├── 9934fecaaf39f6c5b76b61e35384af3c7d9bad84.nq.gz
│   ├── 9d5f7bd89cb399e7b719d110c5c801440b5a4936.nq.gz
│   ├── a2b9bb76519b39e11e9712d21d8dad7018b393c4.nq.gz
│   ├── a47829f6955111cca54380102ba8debb601c4933.nq.gz
│   ├── a6f3e302580d268b34e5e215302db82af414b39e.nq.gz
│   ├── a7249871ee8df789dd94f6ee013dbae8fa1d6390.nq.gz
│   ├── a9e53213e3c98d5e2cf7280f4a79cbe40e7f28f5.nq.gz
│   ├── b5b6593e3bc74f2f44510f30e7d24e83fdbe77bf.nq.gz
│   ├── bba2fbca73ff7c856dc206dd99fa7e285b545fe1.nq.gz
│   ├── bbc55e39282fcf86fee0c9f161899fd236497d10.nq.gz
│   ├── bc9d1e2c553ef33bc54d1ff0dbb0408548ac55c8.nq.gz
│   ├── bf09d78145c7776da9ea534295563ef97f705b2b.nq.gz
│   ├── c1ab0f6d156060f4346dad08af3047d4a6512683.nq.gz
│   ├── c3101b0bf555a2c5ead8625274b376cf7b313757.nq.gz
│   ├── c37e26696751a8a31851dfe3a253cb55212ab858.nq.gz
│   ├── c462f272969a9a93d41f1df1b369a785fedd7e98.nq.gz
│   ├── c49bbd9b5400427f259c25a7a3a0863db9e0c961.nq.gz
│   ├── c597fea88af78f06c86d66f7588540e69fc6e2f6.nq.gz
│   ├── c70e15c31b8bf834175473f3363c55836e1a3eae.nq.gz
│   ├── c91ad18ceabc42ae7c2b42fc9fc2fd55e79680b5.nq.gz
│   ├── ca8039a058a343d78228f90b2b6d9f77af59be08.nq.gz
│   ├── cad207bb0862d614ec3c396b37f3850b725c01a7.nq.gz
│   ├── cc76d05a75ec8bb695daef13104b791d7a417ebf.nq.gz
│   ├── d0e64483be5144a42bdbfdc2dd86fcbff6cb10dd.nq.gz
│   ├── d150582b22c8fe522274286a57b2ed0247a6fbb3.nq.gz
│   ├── d1944c2204d86d1c9fc1156e696c514eedb7bdb2.nq.gz
│   ├── d2d80c9460b272c3f7fdcc7928b8ab5ef7eff840.nq.gz
│   ├── d68211e5ff9a285793305de873bb98776ee328f0.nq.gz
│   ├── d68e231d5f215cf1a4bc9415d836291553b07598.nq.gz
│   ├── d838dcce6f1c9354148a9769764e95c1ecc02a92.nq.gz
│   ├── d8442798e685502d17394fae0d2f314fb5aa6dfb.nq.gz
│   ├── da594ed6b0fa4b1a71b1309c14d283d6d5312150.nq.gz
│   ├── dc6d43eb4226c3f7d7d8432035c4c27540150554.nq.gz
│   ├── de5bc3a6fd6ff9a26bb3505108b493d53e37527a.nq.gz
│   ├── de8c8bc57da52f2ad6ff5b10ea7f8c1cb16ff4b0.nq.gz
│   ├── e34fedacefcac03dd2310a39109105326f585248.nq.gz
│   ├── e505f6ab1ecb7ca436ebb72d06d7ec34f676fadb.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8c3be27b892a9a5db1b06c3ef366192d5f31d06.nq.gz
│   ├── ea878f489e7e64925a476fa6e958313d81400ba0.nq.gz
│   ├── ed845acdde75a3d386320a332b324d4d1822307e.nq.gz
│   ├── eee92fe9b545b2fd8acc12e1a199fc05f939e266.nq.gz
│   ├── f7b280133d1851d49ef3b5f9a504c23b5af1cc4a.nq.gz
│   ├── f7db8d1404579291e79452a7bfc1a753286d1cde.nq.gz
│   ├── f8a3cc40a9b540d08d5b1e4a5e507280e9f248e4.nq.gz
│   ├── f9643e316b6c28d41f44ee0b46109c10cc19a170.nq.gz
│   ├── fa5495a7a8de420fba0155db76545cb8908ff7a9.nq.gz
│   ├── fb1e47f57e1d49bdd8483bb2b3381634bdad45aa.nq.gz
│   └── fdc811966986674a5dbbd73840b9953fb662282d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e3bd5c471f26f33b458b8f86c0abc2afbdd8e7b7.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 124 files
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

[datasette/datasette-accounts](https://github.com/datasette/datasette-accounts)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
