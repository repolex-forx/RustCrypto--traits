# Repolex Knowledge Graph of RustCrypto/traits

RDF knowledge graph data for [RustCrypto/traits](https://github.com/RustCrypto/traits), parsed by [repolex](https://repolex.ai).

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
rlex download RustCrypto/traits
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 82279a5a9ff2af5f10194b9147fe60050cda1851
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 82279a5a9ff2af5f10194b9147fe60050cda1851.nq.gz
│   └── repolex
│       └── 82279a5a9ff2af5f10194b9147fe60050cda1851
│           └── chunk-001.nq.gz
├── blob
│   ├── 0067ce1a9cf727acfb720db023c167e0e8533595.nq.gz
│   ├── 01f4f03a5dbb8616a2425ddf7b9cb0a00a846a98.nq.gz
│   ├── 02c27b0535420f101f12cac2ce06247673f75473.nq.gz
│   ├── 038a6f6ee234b6202b654ea8187ab0ef327cb047.nq.gz
│   ├── 075fc489eb3301a409becec0f0e22585460d80cd.nq.gz
│   ├── 076390b454c3a55ee53edf386f820b4de1e03051.nq.gz
│   ├── 0bac88e3af08357608b150f402cbf5f2cd976399.nq.gz
│   ├── 0cd648f76b488a00f8fa6bf50b3120c7e1d8464b.nq.gz
│   ├── 0d17163e385812cea3f2a85e2b3227d4a05dc655.nq.gz
│   ├── 0d546ae770bb4f7395d0b23ee1b3c68e7bf741a6.nq.gz
│   ├── 0e068e2351b7a1e0182ae18f7b029465724ed1b7.nq.gz
│   ├── 11cf14545a39a6f3803e9864d96c44d70bac7a1a.nq.gz
│   ├── 141590c44b2508bfb508a8a114c78dbf175c28e1.nq.gz
│   ├── 15e176975e76bf1d643c699fb2137fc640a5a710.nq.gz
│   ├── 17ea71d272cfccfcbe14b8110d1aa699a27cf93c.nq.gz
│   ├── 1944839bcd4c36173140d7e0b9fe89541eed2910.nq.gz
│   ├── 1a986c658acb5757de97ac96545d530d98198767.nq.gz
│   ├── 234b7e61c2e8625ecbd57c5fa649bb840a4e4ab1.nq.gz
│   ├── 288d63c68a55917b775ba3c7a7124ed9a6ff702e.nq.gz
│   ├── 294704f372f22a869cc19c9d2400139df2d14ef9.nq.gz
│   ├── 2a034968a1c142c68888ae9fbf5600cd01a655a4.nq.gz
│   ├── 2a2bfdf639ba9ca31aea5fd30000f102e43d3c3c.nq.gz
│   ├── 2b06ca67f669cac00d7e8cec684dba113e631f48.nq.gz
│   ├── 2bdc76bc20d82a3bbdaef815a6000f4ff7a70eba.nq.gz
│   ├── 2cb0706e73f0d795a909cf2ee12072f31729802d.nq.gz
│   ├── 2d17a579c615732393fe9b08018b8791a25b70fd.nq.gz
│   ├── 2e06d1584ec649d78d9a7f9de165908b287b0bf2.nq.gz
│   ├── 30cb3d8afedfd6f4448fa2d24290bf4c30e02c90.nq.gz
│   ├── 3148a8c1ba8382c2a8de239edd0bfbe1c6a497cf.nq.gz
│   ├── 33902bb1936912c2e3d683331579cf98070e6e2a.nq.gz
│   ├── 357af7d50c9819b6c149468377417b4a7c327ac3.nq.gz
│   ├── 35fc1fd04801863e3fbc02142e671aa0c59c92bb.nq.gz
│   ├── 37f14fe5e7e4b5c8cf36855cf7d88924868feca1.nq.gz
│   ├── 3972ddfd2ee20e8979f80875dbb1eb4fffdfebf1.nq.gz
│   ├── 3ad926cbd6aaedce265d6510cfafe5e47600d686.nq.gz
│   ├── 3d8508c211089b91c61c1628299af09e2e7fe38c.nq.gz
│   ├── 3ef9c9128943829c89e2279583f9e64ee5eadff2.nq.gz
│   ├── 4093cc24ebbba0da94deb1d696e21b5756b0258a.nq.gz
│   ├── 4296756c650ce9f5c98e7b3feded3289deee6ef7.nq.gz
│   ├── 4399b4fb8852e56324e009c6cd285f6faecb9f27.nq.gz
│   ├── 43ae3f406b9e21dfa2f1c5b3825199a9d3a1b885.nq.gz
│   ├── 43f8c033dc2cb6489a74e98694ab41c278fea7be.nq.gz
│   ├── 456d865ec02a02e4c8b91ad34aacf46542880d97.nq.gz
│   ├── 45c92a6072d77fc6b6f9f575a2172d182744124b.nq.gz
│   ├── 461e1b25b971aa624cfa1d3ba242ac15d56bcb55.nq.gz
│   ├── 49dbb9dd86848b09944f1c0c8fb7db0ddfa28b5b.nq.gz
│   ├── 4d3bbe168da173afb93d74178168cbc03538362b.nq.gz
│   ├── 51fe8ce8b52516cec25ca95b329195b9e54a7048.nq.gz
│   ├── 52f1463aeda99783ad7199ec42b8571f24b39ffc.nq.gz
│   ├── 535dfe438015af7c29d3fec824d8848d2dc17cae.nq.gz
│   ├── 549f590aa5084e869084fa3ee359954b0723f1d1.nq.gz
│   ├── 584f95bf403da85221440e2e6db1d9b0100f2080.nq.gz
│   ├── 5a1e64f6e9317454187049aa16dc12eaa8329aab.nq.gz
│   ├── 5de19d66a76a06aea5f502c0b36962c6f8d701b1.nq.gz
│   ├── 60cea01696d595a3deee6137ad6a4a1181db2adf.nq.gz
│   ├── 61381f5293fb1ff4ed8b5f864a1b42564a4c17e6.nq.gz
│   ├── 62d7c158a477fba0bbd988405dcaec8b558af8aa.nq.gz
│   ├── 62f432c741cd6e8477ff97ff3b6a556e8d81a715.nq.gz
│   ├── 63a13034f5fd2a2259b2c9ab9014252d49d09e34.nq.gz
│   ├── 67c719c7641d6bc2b1b122bcd287e2947daed3d4.nq.gz
│   ├── 6a3dea8a76f3c4bb84bd88b2036b647d296fe34c.nq.gz
│   ├── 704556f3a86f855066e0a60f9da8d0f00399dc0f.nq.gz
│   ├── 72b53a2a5d88b03ddbfe0c904d998ee098138f2b.nq.gz
│   ├── 7320de2b65d96c8293ce6ae4558f4817aea6c977.nq.gz
│   ├── 7650239c7685473823fb0ffefb795088dd19c698.nq.gz
│   ├── 78173fa2e753d614bb0aa5ad125ddbbe70b282c4.nq.gz
│   ├── 79c85b5b299b7902e4a7f5283a7d08cac99db8a0.nq.gz
│   ├── 79e7de4be2c99e3e524c1f1b0344485d44204b82.nq.gz
│   ├── 7a0025e412807037310133f70fafacf46702de9d.nq.gz
│   ├── 7a88b44dcade4a0fdd5553d787bf29d2328684d9.nq.gz
│   ├── 7b618a179388d9612b841dfe52f92fdc7105a421.nq.gz
│   ├── 7be4751433b0297e5699c667afcda75e42792695.nq.gz
│   ├── 7ca8a6927be05ee98d96a05fbc42a68387b0ea19.nq.gz
│   ├── 7edf8fce626b1636087455b7d4fc8b6d7bd9856c.nq.gz
│   ├── 81a8f0cd9c259ec0998c36384aaa1fda31695359.nq.gz
│   ├── 82812ae61ec51e9323d2a16339c50af25e75bda2.nq.gz
│   ├── 84dddd60d18376c0ee5fe3d0df832188205bdf6b.nq.gz
│   ├── 87097f64dc97d3f92cc2aa72babe5bd1620318f0.nq.gz
│   ├── 871ac5ffc2e68112c5bef6e3cc72856be194e0ec.nq.gz
│   ├── 89b80b1ceb18d3a3fe92683780d4ccf59d48901e.nq.gz
│   ├── 8a831dea62be0ffe004e4c7ce1f4ce357996eca7.nq.gz
│   ├── 8bc475b018868330c05a98f00c0812c97294ce12.nq.gz
│   ├── 8c8dba0384bb97acd93c975619b4ce3b8a676dfd.nq.gz
│   ├── 8cd2468ec5fb2747cdfc9a25da174aa8f9fd6031.nq.gz
│   ├── 8e70a71fc0d5f2e685a84c8b4978ccd762e5c77b.nq.gz
│   ├── 8ef6cc2fde2ac9d182b79e90c1279f9fe3baf95e.nq.gz
│   ├── 8f23eeca0d19549068a1eac2848fa03600e3177f.nq.gz
│   ├── 903c95c6113fcd83d38a9a51843f71c956de4a26.nq.gz
│   ├── 956d217b93d7fa7b416b1f68c06e4ca222e6776e.nq.gz
│   ├── 95c4fb5720c335795cadc24ef43d7b85879d44e7.nq.gz
│   ├── 97d19b94c172348dc8c8c6425591b45bf12831f4.nq.gz
│   ├── 989e219afb20f6d53617e97cf07106009b37f2c2.nq.gz
│   ├── 9d21b49e8b6d204de39f3bd3dcb505e220ddde75.nq.gz
│   ├── 9e13daa6d4a8ca9ceb262bef82230af98b3f5f59.nq.gz
│   ├── 9f0008d12425c3b56576ba8125f88f4502e9d77c.nq.gz
│   ├── a22e1d20d2236460659f7d95a078258190cdfee0.nq.gz
│   ├── aab77a38b5fa3ce80932027262d8328c1553a84f.nq.gz
│   ├── acc1ad77810430b75d7e94b6652d54f2909ce1c6.nq.gz
│   ├── acd4c87690e86bf51c6cba8a06d88c6554395d61.nq.gz
│   ├── ad231ad142739a6f5ae12b259917d3b42eb6d056.nq.gz
│   ├── ad57e77418cc8e6d96c8cc7801252eca044a3453.nq.gz
│   ├── ae5ce5b03d314fb2979878a42d078fae52697883.nq.gz
│   ├── ae6739c42a30bad08ee79a5ae523f98903309589.nq.gz
│   ├── b0412f4fe07e9c208b6b9fac22b9b474a01e8c98.nq.gz
│   ├── b0a228d55c591999f06bc2661c379715aedd7bda.nq.gz
│   ├── b5213631493af26378043e8da2ba060e4d6f76a5.nq.gz
│   ├── b723e3eeea19996105f4615220c67a3eff5bcea4.nq.gz
│   ├── b7898ad59428d35da5a4c0b321b768b2f339eaad.nq.gz
│   ├── b98fba8e5a3972813641ac513c8be5613fad42bb.nq.gz
│   ├── ba425f082e7e0b281436d62ccfb479f68d7803d3.nq.gz
│   ├── bb7ff7c2c3585e100930cca9cfa703d3a5782000.nq.gz
│   ├── bc08a55c7de1b85f9a942f2a588958a760b757e0.nq.gz
│   ├── bc69494e7f5c87e3261fa5f273df8b5efe472fda.nq.gz
│   ├── c0de45ef22f512ba6a199fa9d57e08e5f95ef7e8.nq.gz
│   ├── c1c59118cf42b0401c1ab1316509cb33d44c12b5.nq.gz
│   ├── c3937a96a01aa5a4368876cd6d3ee7ebc3a933dc.nq.gz
│   ├── c75a9006683b0ffd5e6921dec3545905704f657f.nq.gz
│   ├── cbab8ee9294af6add19c943a9dffda055fb57b70.nq.gz
│   ├── cd4dd2b56a5bddfc0ce01e9ea956e982a7e45662.nq.gz
│   ├── cdfb158f62a26453cdc5e175b8fe6ccb2e219af7.nq.gz
│   ├── d1951bf88c17251d7dcdf307e1d6103d3c493ba9.nq.gz
│   ├── d1c716154cf8adb94055ff811a50f7e542d153df.nq.gz
│   ├── d2eba00edc1f93ceb956d44d28ac523257bebe89.nq.gz
│   ├── d3b48ddb7c09a547f6217e8e38d6c9f0eda45915.nq.gz
│   ├── d4795f2f9b3ceade59278a79f56f1086211ad245.nq.gz
│   ├── d61065be8961b140087411c96fb9bd32d5fecee0.nq.gz
│   ├── d767644dae225f11a35996b97d4d4a990fc66a7b.nq.gz
│   ├── d7824ae99039f4f8961eab28a882c404094be061.nq.gz
│   ├── d8b21522af636f1562a821363d127685c435ac8a.nq.gz
│   ├── d9f324bef7584d19feab56e0b982718faf5ca08c.nq.gz
│   ├── da68fd49ded520e09f468740011fc4c70b35b172.nq.gz
│   ├── dc2905255f19a9b392f73c4510b92be2d56535c1.nq.gz
│   ├── dd5e2406278ee3be95c713b806cae20c63e92cf0.nq.gz
│   ├── df218f72cc68368d5c95f2c4a1ec53fffac32856.nq.gz
│   ├── e019773d920823d4506e8c6bedb5a2afcc812ae7.nq.gz
│   ├── e0a7b34538b2f2d2e365cf561be43dec8f50bd19.nq.gz
│   ├── e2f3c3a1201ea3022a693d08d411927818e158af.nq.gz
│   ├── e30576da61738fea6d203d259cdddbcffee1325c.nq.gz
│   ├── e3153cf2f277b9bad3b69365f7c222e1eb074f5d.nq.gz
│   ├── e621f157b6fa18d89cfb25a76a0c1ea3cf58484d.nq.gz
│   ├── e8de483dd9342d0d737a66faa4d631c0815d52d0.nq.gz
│   ├── e9b74ba6f7e6675f9e9b7e6f2a9f5cfa17a0addd.nq.gz
│   ├── eb290b8ad910ac69c7cf078a36596a4bd56749e7.nq.gz
│   ├── ec1d1aff255e8ecdac8889d9a8f3023e001fdf24.nq.gz
│   ├── ee7e5b612f35bf1291c190638a3570aca307279e.nq.gz
│   ├── f17e68376f42b2a9ff79a8ec9afbf45949aa9c98.nq.gz
│   ├── f35a20541d9ebdd67f5712ed8de8d1ec09ca9b3f.nq.gz
│   ├── f360fe94953dde55692805e57868abd32755fdb6.nq.gz
│   ├── f3ec088864a3d2bc0e09a875450996178094b4ba.nq.gz
│   ├── f5b7fd9c8d95290c2eb3c3be5eb919bd9af82c6d.nq.gz
│   ├── f6fee940d91a59f2ac7943e2dc876b462412ea92.nq.gz
│   ├── f98f0cae5b064057a6de5baa318b06d322b35645.nq.gz
│   ├── faa39e3d218eb5e33757ad3f1cb0c05ef0b87e22.nq.gz
│   ├── fc61fc481093e356cd14da1a4d0b5599e6fb64e3.nq.gz
│   └── fd1048e26da88578179a0ed13f670423782ef1f5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 82279a5a9ff2af5f10194b9147fe60050cda1851.nq.gz
├── filetree
│   └── 82279a5a9ff2af5f10194b9147fe60050cda1851.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 165 files
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

[RustCrypto/traits](https://github.com/RustCrypto/traits)

---
*Parsed on 2026-11-24 by [repolex](https://repolex.ai)*
