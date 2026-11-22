# Repolex Knowledge Graph of rust-lang/annotate-snippets-rs

RDF knowledge graph data for [rust-lang/annotate-snippets-rs](https://github.com/rust-lang/annotate-snippets-rs), parsed by [repolex](https://repolex.ai).

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
rlex download rust-lang/annotate-snippets-rs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2d2643cf7c64abbf014ff1df736865074a8b94de
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 2d2643cf7c64abbf014ff1df736865074a8b94de.nq.gz
│   └── repolex
│       └── 2d2643cf7c64abbf014ff1df736865074a8b94de
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ae9678aafa99d9e3fe517f02783202704df3fb.nq.gz
│   ├── 0242b353a275c243555a41561dc83df7fbd8b273.nq.gz
│   ├── 027f9dca0720add7dd81c735773140799e4a59a7.nq.gz
│   ├── 033ca75899c2010ec4fccc352644924e3ac3be4b.nq.gz
│   ├── 0353549dc53963fc4f5c5135ac7eb49d78856c31.nq.gz
│   ├── 075cad42a963291f665b3e0e30392dfad5798f58.nq.gz
│   ├── 088444dc63d1d8079378fad31300014c66620043.nq.gz
│   ├── 0afb2e070071494a3e1228de2eb13e015d59bfdf.nq.gz
│   ├── 0b69b3aa8d46ef42f564f5d54163479d79c16e3a.nq.gz
│   ├── 0cb98fd830881ab9232c4588c5bc2b79713b47b0.nq.gz
│   ├── 0d79a9f4d2ab6e13bd5f557bcfcb2fb6c595beac.nq.gz
│   ├── 113d66b4bb84ae471c8368a7a44cf28d8daf2668.nq.gz
│   ├── 132282656a35993dd9340962e52840719e4a59ac.nq.gz
│   ├── 14dfbe47b482f795b4983c1d9531b642af632750.nq.gz
│   ├── 15f56df506501715b45755f80ed58a67b438ba30.nq.gz
│   ├── 1618d3f0cf6fd4db914aa0a8d784cdb04e571567.nq.gz
│   ├── 176f7dccf2636b461c18de7c99194882c6ff16ab.nq.gz
│   ├── 1773031c1abb24e60ce6217a8e94488daaea14dd.nq.gz
│   ├── 17f33d992b9eaadca381a94973ea092ce75250d2.nq.gz
│   ├── 19fdf6494379d3a30a391aef28e2875a7de18e29.nq.gz
│   ├── 1d4fd850696ddf8d3d0b9e3387d47cb7cf8c66e4.nq.gz
│   ├── 1f3913646870455588673a9c9c1baa5e71ed75d0.nq.gz
│   ├── 1f64b24f1d7f00699f6625d7d813b598549aee9f.nq.gz
│   ├── 221ef30e204756c9e8cfe475fcc24ff659a34842.nq.gz
│   ├── 22f8c6ebde953f9d11345bd9cd86741d524e8cce.nq.gz
│   ├── 230cf9e33ecb7a804462fdce9fe96ef479327538.nq.gz
│   ├── 24038531c47e942524c82183a9bfb957aca7f5fe.nq.gz
│   ├── 24ecffe805789406140cb4bc1540d49e9e27169c.nq.gz
│   ├── 269e0735eff38f0a253f8170b96d4bbfc27658da.nq.gz
│   ├── 27bf59a884cdc6948c686a9eb9b3f0fe99691c95.nq.gz
│   ├── 2a2a3c2677ff860dc16746a7bed5f2fef581b673.nq.gz
│   ├── 2d88f74ad84ea75495abcc67e57405340417515a.nq.gz
│   ├── 2e52a6402761e14ef704a42a777280f4778dc707.nq.gz
│   ├── 302929108506cdec08c9c56ce81fec15bbbc7e09.nq.gz
│   ├── 32503f99e5fc268c764704e845345a0c860fc1ff.nq.gz
│   ├── 33d01587ae184d226a010e1fbb844853d5d3fe9a.nq.gz
│   ├── 3a521c1614ad0b1ca4d6f65e879165f448a61206.nq.gz
│   ├── 3bf6308563f8113f5d1744bcd43db3a399cfaf22.nq.gz
│   ├── 3c031da518b0e9b2c6941c1b6f9d5350f86b3d46.nq.gz
│   ├── 3e2ef2b2e1c02135537b508b08c23985311d3e84.nq.gz
│   ├── 3f4ab8039cd121deea5df7821e113500878b6d57.nq.gz
│   ├── 41e9302fe866874524fb0cb3654961b82171e9ca.nq.gz
│   ├── 41ef6a490b11739bb1ed223853ab98dcb441130c.nq.gz
│   ├── 4211ae3842810ba7207dfc2148a5354e28276bda.nq.gz
│   ├── 433906e04dd74669e791e20ee112f8d3755e1ae7.nq.gz
│   ├── 43acddd2e51ebe3ea90a06044837f914f60cbeee.nq.gz
│   ├── 4874b146920d8d9a2b7d21353a0c710224be174f.nq.gz
│   ├── 498ce6b67a60b736be0cb9ce1dee825676248287.nq.gz
│   ├── 4a6a1abdd612113aea698f0f51e28cb675ea8ead.nq.gz
│   ├── 5056db7fe53a063653ddc4a4ed454fc441c60b6f.nq.gz
│   ├── 50a43a8794be5c27e6da2e11be4d9a0bf42a3a6a.nq.gz
│   ├── 52b733acea1950754f65971f9e807227541a8a72.nq.gz
│   ├── 54569e21f178367832366ee2f46b9e66ee5a2026.nq.gz
│   ├── 55cbd16c1c21ed01b94347e4584d96c9ed4b971e.nq.gz
│   ├── 56a8b74aa909328bf45c18fc9582ec13cceb47b1.nq.gz
│   ├── 59e54dbc49ecbb945ec9a6fd373d027199a0c1ec.nq.gz
│   ├── 5ac2088227f4cf32b02ec0c0728a8e2af41bb239.nq.gz
│   ├── 5f8c2204768d8202fe496eedb06c204f32b3d6c9.nq.gz
│   ├── 614121d6b8d4a3fd47573f48f0038ba1cd2c2aec.nq.gz
│   ├── 66b578c6d8295dfee22816ed0150c7662ea08884.nq.gz
│   ├── 67dfc8411e99b44ddea3acefaef8c99284f5c6c2.nq.gz
│   ├── 67f544a9a80f385cb90257f7499c72cfc7b56389.nq.gz
│   ├── 68023e59a8dca98c4c97e0559d76f23075639434.nq.gz
│   ├── 6b716f347d4d143a45aeb0e35d15efce013173a0.nq.gz
│   ├── 6cbb6e643e363807321a2e8be3f1cf2c87e460dc.nq.gz
│   ├── 6f5fc328916cc8674b8252174bd9e60e73f95684.nq.gz
│   ├── 708a9e16cdf08859f5780c48e4cf0dfea4b54e67.nq.gz
│   ├── 70eee9a70bf14f5eab82dfcf7e388c3bd4e50c2e.nq.gz
│   ├── 7546eae54ffe9fe7d179e06d35a198daf3fba8e2.nq.gz
│   ├── 779210c3ea8d7d4c1c8ada88b95ca37d08406c31.nq.gz
│   ├── 7b3f5c1810d70051f61d5aef149da2a28588e30e.nq.gz
│   ├── 7b5123d41c9750a5512605d702250217ebfe7d58.nq.gz
│   ├── 7be504738e0b6cfaf81916a8ad80faaa41b40ae0.nq.gz
│   ├── 7e180ae5f328c3b3963f16ab552aa21eebc11846.nq.gz
│   ├── 7f02f0e5a01d1ca037cfc1d65e85c93e692325ea.nq.gz
│   ├── 7fcf7fb0222c9add905dd09e6f505f75c1b6442d.nq.gz
│   ├── 8009a49a1f07b1b1bcd3069d1a62271ab94e4cff.nq.gz
│   ├── 83c9c25a2a1fd1d2d7d683644ddc6767338a8622.nq.gz
│   ├── 846bb2d3d47bba61dde2ca92d14c1a065b6775ea.nq.gz
│   ├── 84acd1ddae9755929cc57747dbe459022f30b21d.nq.gz
│   ├── 8c05a6c47a1d08b4378570a3797840503cc84d6e.nq.gz
│   ├── 8e4a1e92ca7e36fbe20002c5c571308d3acb0645.nq.gz
│   ├── 8ef35872d4819b7c2d345f09501b2443a7fa830c.nq.gz
│   ├── 8f71f43fee3f78649d238238cbde51e6d7055c82.nq.gz
│   ├── 9138a8e3fc824971be7888ef3eaa8074095cd94d.nq.gz
│   ├── 9309403f5d2673aa1d7674abb881ac5f49aba06e.nq.gz
│   ├── 9455b53c088c883cef7a80acf76462d8cbf512b7.nq.gz
│   ├── 9644d2c7eef8850bdaa778d1e7c107092ccdab19.nq.gz
│   ├── 98ff935ff5c52bae632bf2b5aa53418cf2025cb0.nq.gz
│   ├── 9903c1d43696d56fd046efe000d4354d5c263d8d.nq.gz
│   ├── 9b0785bb1cee25e7a91936c4634346341256840f.nq.gz
│   ├── 9cb8967327c0707e302a50e101ff40a67185b54d.nq.gz
│   ├── 9e36e849858b72f7f3358a39432a5fcd4f1e994f.nq.gz
│   ├── 9f6f2bfa16ec6c704622b3df03ba4ae35a62ca6d.nq.gz
│   ├── a0a04b37021f1fb82a8a12dd4d121e0a65a37f63.nq.gz
│   ├── a2d01088b6ce55e837a6d193943580f978fb2d2e.nq.gz
│   ├── a5328fe7109eba929a9126839fbcf8ed9872d0bd.nq.gz
│   ├── a6a326dd5e16038cb40a5cfcaef228e94657453b.nq.gz
│   ├── a8af7c8b7d5bf4fbe7efa9af71b7cd2a3dc029f6.nq.gz
│   ├── aa94e1983f9f4f7d280cc18938e2b6bc0bc93f11.nq.gz
│   ├── ab88efc9578189aa5699e40604922bedc769b2e9.nq.gz
│   ├── ab8d9ebfdf8c4d6249e25389962e6283cd07add0.nq.gz
│   ├── b289224a44ebc737c88dbdb5a3e158c9536b3607.nq.gz
│   ├── b99aace6edb00a6b1f880b462ab87c52eaa5e237.nq.gz
│   ├── baf175a092659f337e4aff071bed3cc3528f3ccc.nq.gz
│   ├── bbd1af3f5a56850924e44f75cebcf9fceffaa865.nq.gz
│   ├── bf8af13604a06d9dd9165597bc8fdb222bd92c64.nq.gz
│   ├── c4b012052d6103bc999ae14c22b2e2411791c802.nq.gz
│   ├── c52d016efbbdac04f3dad9e9968fbf4ddf345cc4.nq.gz
│   ├── c5867f851c423f727327cba38a3dcfed524da427.nq.gz
│   ├── c744b7412f35084bc2948c48fe4c332639e8daf8.nq.gz
│   ├── c7d09a5cc8cf0f980c45b60d1218cea90569f9c3.nq.gz
│   ├── caac32d46201c89675e4a0dba4d432599d5b7dbd.nq.gz
│   ├── cc00e71fc0b00d2b155421b781f7f7e10d4ae33d.nq.gz
│   ├── cc569b474298e07e77db2144b0093b603c2f000c.nq.gz
│   ├── cf4c1bfb053c86eeb9a1dcf27051f14bdee9f5ec.nq.gz
│   ├── cf9d0bc9fd2c22dd66282908de7fc7d45921af8a.nq.gz
│   ├── d0526ea034b4ecd755101279683c22871288c238.nq.gz
│   ├── d759618682b622a9f041c274e983eda9cd9c8798.nq.gz
│   ├── d86bef03d6c1a0049a63dd0ce04df4741a3a708e.nq.gz
│   ├── d87a1b8a0144f65687b261212794eaa973b82f89.nq.gz
│   ├── d8ee076f366f01f2fce10413c2690c956e349112.nq.gz
│   ├── d9aa9cbdaefeff86cce47627557349044362be59.nq.gz
│   ├── da08c219efd436da037bf90256337ac0bb742754.nq.gz
│   ├── db8a5f6a0425e4772438aa805413b4777e137885.nq.gz
│   ├── de0bbd6af54221952927fb484a269da0340ab663.nq.gz
│   ├── de62e3c6cacd8de09f0f62a2db7985f979c656e9.nq.gz
│   ├── df045c86012d65a25ab1224160f657d597b07ed7.nq.gz
│   ├── dfc0c58739509ca74cfd1936f601b710ad9bbdad.nq.gz
│   ├── e0130773402c8fb2d063222de14d120289dec5c6.nq.gz
│   ├── e14336189d11f32bd2a5d02425f4bd0c905b8db5.nq.gz
│   ├── e4308a36181a06622ee31aac0f049227aee23cbb.nq.gz
│   ├── e535831bb7ab77ed693da2a423e2e4eae4eb99a8.nq.gz
│   ├── e8b5fd77942b4b38601e21f97eefd218f49478a0.nq.gz
│   ├── eb5a316cbd195d26e3f768c7dd8e1b47299e17f8.nq.gz
│   ├── ece1acf35dfe476426d5a71118c72fe6addc36cc.nq.gz
│   ├── edcd663a2d8bd32a435be863fdd26aa59478b406.nq.gz
│   ├── ef3b6a8e7d3fcfd14a2558e148806cdcac513800.nq.gz
│   ├── f1297d2af80f3743d5a26e0d315e5a60324b4369.nq.gz
│   ├── f607b157dc7d63a2c8e3d65df3e1211f67a39748.nq.gz
│   ├── f8820196474bf45dafc0a5c6641ed675be8ae8bf.nq.gz
│   ├── f93489eb4938300051e62b1770df5ad96b4d0704.nq.gz
│   ├── fc0f613b1f6544ac6770d8c41af44a87d51d3370.nq.gz
│   ├── fdabffe21cb1520f03e7c576825d0d9b4f2da772.nq.gz
│   ├── fe3154ed988c4d3b322a5cc2cecf45e054d367ad.nq.gz
│   ├── ff6c86f73e6b5c754df346a22b4299d561da393e.nq.gz
│   └── ffb1ba9440f829af32b5b5ace4e9be0a6d29c8f3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 2d2643cf7c64abbf014ff1df736865074a8b94de.nq.gz
├── filetree
│   └── 2d2643cf7c64abbf014ff1df736865074a8b94de.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 157 files
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

[rust-lang/annotate-snippets-rs](https://github.com/rust-lang/annotate-snippets-rs)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
