# Repolex Knowledge Graph of huggingface/carbon

RDF knowledge graph data for [huggingface/carbon](https://github.com/huggingface/carbon), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/carbon
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4ca3ce3e5c55e5821d6068bac5c6e3806027a26f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4ca3ce3e5c55e5821d6068bac5c6e3806027a26f
│           └── chunk-001.nq.gz
├── blob
│   ├── 017f92bae68da6ba2c5f4b038e4877637eacfe39.nq.gz
│   ├── 0377592e6c37bda6bea12df1c537140a7f64b0ad.nq.gz
│   ├── 037ef7cd8f13678d306c36d92382fbc0224bc43d.nq.gz
│   ├── 049d8752b1a711b38008283d1c3c687f1226cc57.nq.gz
│   ├── 04f87319239afe86c5f162a7f26cb8c0b4cd303e.nq.gz
│   ├── 0538f499c2449cc7c73a8a512f46c8ce393179eb.nq.gz
│   ├── 065dcc1eee608cdc44cfba7b9d8fe6fadcb7cee4.nq.gz
│   ├── 06e525f383e9e01b81b207bbe2212d4e2b962dc2.nq.gz
│   ├── 0a2a621734d09345947a91a8eaf4aa233fc3aaf0.nq.gz
│   ├── 15d249eb6deaada83be760a7dcf1c2982469f194.nq.gz
│   ├── 1a4db7ccd05028523b20727f788a2c6fd7e9ba5c.nq.gz
│   ├── 1cdb24367bba8e4f873301834dcc1592bc415e7b.nq.gz
│   ├── 1d5091932b742f545fca3b68425a9acc0d8becdb.nq.gz
│   ├── 1e13827153ad159e01eeb7173b1c5f11d6ec7cff.nq.gz
│   ├── 1e9486cfb27f25790308f75abefa1e0588c16089.nq.gz
│   ├── 1eee3307985df8304a950d4e66a441e30034d679.nq.gz
│   ├── 1f255660ca2c5cee91ffbaf96663bc65c1708df2.nq.gz
│   ├── 212e3f80918b7ae77def84ca556aabc87a459cd6.nq.gz
│   ├── 2181f174298f8061ff45cc86c118424beae9c23e.nq.gz
│   ├── 2272fb5399c5b020a81bd58996f2382272612212.nq.gz
│   ├── 2392ce8039de2fb290e9e8733a8397e06e3710ea.nq.gz
│   ├── 243069a16b1c7df4d7ed6952707bf19723838bbc.nq.gz
│   ├── 25dfb4026e204ff9f879c630c55ad2e862a600bf.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 289810afffe58feb282955dc60d53f91a494bcf4.nq.gz
│   ├── 2a9e0db6aa1758f7118e88ad58638f7dd6edde9d.nq.gz
│   ├── 2bb32fcd5e5d9064e71b1e41312ece0db5f5cc3d.nq.gz
│   ├── 2e67ae43b769d4f8aadacc960d2b0b9c3ae91f6e.nq.gz
│   ├── 2f3cdab19193d5c7ebd14b990961cab6ab55031f.nq.gz
│   ├── 33a3d1718a91ade51b4dc2af079e2d3d9c1c2506.nq.gz
│   ├── 3413ed86579fafafc295e4f8560452be77cde6c9.nq.gz
│   ├── 353503be87098a0efdc8202ca11bcd9fde1f73b3.nq.gz
│   ├── 3546ff41897f0a93c5a14be3fe920c00d72f908a.nq.gz
│   ├── 355681324ef7b8e81270375da9b9550c976d391e.nq.gz
│   ├── 37ed254a99fbce2c1a71ec7bb19c43072519cb61.nq.gz
│   ├── 386aa761f4f4cbb238eed732b110200720910c21.nq.gz
│   ├── 3921b897a719e42e1c0bd2c9c0594dd36782bc34.nq.gz
│   ├── 3a93bed07d8252a05e4af9d7a95cedfa49fbfe59.nq.gz
│   ├── 3ab2ea4423ead1eb99bba8a4206f9fa4d43969a6.nq.gz
│   ├── 3c0e198461fc3cc6cffff84adf6007d34385f1c6.nq.gz
│   ├── 3e63356b22f28b7e737331dedafd403e2d9cbeaf.nq.gz
│   ├── 3fdb43574dde188c2caf5fb4c2095ecd56023c3c.nq.gz
│   ├── 411f48db2baf0f3300741b6ad32addb2e0a4ee7a.nq.gz
│   ├── 4179849c3b969a23114487b89b3d016accfea856.nq.gz
│   ├── 421f3904e24a2d3f0b073139290d05cd84cc9c2f.nq.gz
│   ├── 434a2c6e21c626f111472587ee59dfc00eaf6b72.nq.gz
│   ├── 47b91b4d5e810f7e9a459b5c224134cad59cbea8.nq.gz
│   ├── 4be12f827af178218653407147ec9ec5c408f34e.nq.gz
│   ├── 52e7f94a953f37cfc2d6de7507b9473849caeae8.nq.gz
│   ├── 558813b35f33cbbe7501cbece8f33a6eaa85d9ba.nq.gz
│   ├── 560cba53063c4deeadb1f8815d946314acd9c36f.nq.gz
│   ├── 57a0d7fba05802333ab2b0df77193c36385b14cd.nq.gz
│   ├── 5b075f6dd9bae27339b7d85dc0d66ddeee838f7a.nq.gz
│   ├── 5f8c110912ac48ae2baf5c2390260fb87e33d394.nq.gz
│   ├── 5f9630678c63a89c827fee24ef66ca0a8d98e22a.nq.gz
│   ├── 610eec3678cb44b10b63761693a5595d49ea40f9.nq.gz
│   ├── 62642ad83609e1a926aea6306ede020e796039b7.nq.gz
│   ├── 645ceb0d87699e029d5ddaf5390f28463055bf8a.nq.gz
│   ├── 65adbc106220a82a6463c24910e5c4ac1f448db2.nq.gz
│   ├── 675b5e3cd445b6e1d3bb459c7a131f478f1d68ad.nq.gz
│   ├── 6897be7cbfc1342e6b09fdad1f945f277e611683.nq.gz
│   ├── 68c3ff1e623104709a231ed1cedf5b40a4ac4f54.nq.gz
│   ├── 6a0007876d31a8071af896175e1fa7a2e518f476.nq.gz
│   ├── 6d3c7196abb9bcc67373c1befef10f2c99d49722.nq.gz
│   ├── 6ec639d16874fb16e279a4dcbdb58aded732e133.nq.gz
│   ├── 6f7f5a72c9566751c2e0c2e5b2cd8177c7a5950f.nq.gz
│   ├── 6fe1e384a8b8842b60fc0752f7cc961dc58062c0.nq.gz
│   ├── 7231bfcff7b1decd247cea168ca583fc9faf3a41.nq.gz
│   ├── 72cbdf04a673e22cad3e1ea8be049988611dd177.nq.gz
│   ├── 73b6ce38f3755b867b9a580953fcad98dd7c2d2f.nq.gz
│   ├── 74104c6f675b5130573458da979649efb525770e.nq.gz
│   ├── 75349aba8d961409da4c8a0c45475d167ee1cebf.nq.gz
│   ├── 761d8892d12ecb14cc4cdcfca3feaede516db2f9.nq.gz
│   ├── 7795f7ef03ce50a975368e84ebea50b54349aa50.nq.gz
│   ├── 786e54fc067b8409cf289e833be2a75ffea6349e.nq.gz
│   ├── 787fa5d2365339abda228cb6f996b63bd5435d56.nq.gz
│   ├── 7a40c856778c12812d3cebfa85741182dda260bd.nq.gz
│   ├── 7de24932fbcccd4543361ad0fb104f72a0d39d91.nq.gz
│   ├── 8004ab0603de4434b70346c752b2f2023e9c63e0.nq.gz
│   ├── 8336b6763107fe047193b44d299ade9cf584bbfc.nq.gz
│   ├── 85c2ab2503e20fbc1faef1a55b21f950aaa09111.nq.gz
│   ├── 86eb185b2b6a8f0093d00628f851452e56daf0b7.nq.gz
│   ├── 880fd8537c1ddbbc589a75c82421104d1ccf4cda.nq.gz
│   ├── 88507df3f1cc51e857083ede46a4094ba583e07b.nq.gz
│   ├── 891b8dd63697cccbc45ae775edeae8029f07a906.nq.gz
│   ├── 89418e7fa6579cb5b2c5c3c8714627ccb19c887d.nq.gz
│   ├── 899783c22baf9ca7885e6957ebe415e6e1dae4fd.nq.gz
│   ├── 8d368dcee7f89bd5d6b41fc0f6a5551752a32062.nq.gz
│   ├── 918d07aaff44ccef36ffdd2810c89b108a73a83e.nq.gz
│   ├── 943afdbb385672e9259956ccae47fe3f0dc4e663.nq.gz
│   ├── 950caae2d49d4261e2afc142eb7ff2994987a181.nq.gz
│   ├── 9558250818a0b3710c7bf338eaf8c58a1ed8fd64.nq.gz
│   ├── 970304b048e33e2d4c0ee8c8aec63b308356616e.nq.gz
│   ├── 97d3115d8ec768ab2677f1d84fb0c5e49993074c.nq.gz
│   ├── 97d750795ba59e532d1ea368519610427c0a8f63.nq.gz
│   ├── 9a71855eb720b464d7cc9d2b23f10ddaac7374a3.nq.gz
│   ├── 9c8fbf6d45278365e99aa113ec61d991d505c75e.nq.gz
│   ├── 9f1e3edd36cfb30023ae40238749dae45897c710.nq.gz
│   ├── a142c3dfe04edd432af16c637c57df1327585630.nq.gz
│   ├── a584972bff945264ac52d02333b1b558bfa48a47.nq.gz
│   ├── a7392fa2a58a40d780c19d11a11decad340470ae.nq.gz
│   ├── a8380b870519792e0a3e31f10c91c4eb23ac9a4f.nq.gz
│   ├── a929d1a31411530a4e4501a484ddb49af091e683.nq.gz
│   ├── a958564dca1c854134a0cf2a7e010d57362e12ba.nq.gz
│   ├── a98150fd81190e914f7fd83d9cb18e7077c0e6ae.nq.gz
│   ├── a9ade7f69978597a5318d49f0725d4c3b8f75612.nq.gz
│   ├── aa492552e4db2abd6072cdea4a89972f6479757f.nq.gz
│   ├── ab0f9883ff91ae75ed27418784f24c74ff47137c.nq.gz
│   ├── ad31b3874557c12609befbe6086b9fa394536325.nq.gz
│   ├── ae19acfbee000950051a74b1055335ad895a1a2c.nq.gz
│   ├── af14e34b88522fd4a3b0e2fc21371961792f996f.nq.gz
│   ├── af498f3eced9c2434b80113f2f22d40395e0ab8a.nq.gz
│   ├── b33da651c3fed10d269937bd0598e7273d07edf5.nq.gz
│   ├── b5a1201f8a2ee8706b63f0f80c664a1fc61a7d9d.nq.gz
│   ├── b6eee63137f2260a934264b81eb81976a731271b.nq.gz
│   ├── b7346d18f3c6be77c70258864d8c964377e3eabf.nq.gz
│   ├── b779b5568efe2c6ff51aeec9f16eb6c6062903ed.nq.gz
│   ├── b87f30a37feac3de37c40c2c47d136286cd8bae4.nq.gz
│   ├── b9274e4a023c218bffbadd6cbfdbb727a601b9d9.nq.gz
│   ├── b9633ac00449f150c28026029c1d38db9e1d9d8e.nq.gz
│   ├── bbbd55cb494cf2a6e8f64181478aa8127c09b455.nq.gz
│   ├── bc7dc2fe7103f6947588d0aac90e093886637255.nq.gz
│   ├── bf79f1316666313a34a7f5cedde004d1216590c3.nq.gz
│   ├── c36b7df8242fa8cdf8885f1dd011ce925551fd44.nq.gz
│   ├── c6d9bec469c13828ccb30a960ddf07d5f9ed5600.nq.gz
│   ├── c7a145801a606010002519dc707ad12086190d0b.nq.gz
│   ├── c8cdeb360f10efc29ca36d12f4c795d33436fe32.nq.gz
│   ├── ca4a8ade07c85cd7fa59073db07959f42f2f2975.nq.gz
│   ├── ca78cfe64c5509ca0a576c40640ec5b6a06eba5f.nq.gz
│   ├── cbc525eda2e4f5bf570a240481f61fb7bbd08f07.nq.gz
│   ├── d1374d1979c5eba1b0e1284745ed831a6695ccb0.nq.gz
│   ├── d19f09e8c3ac16fa293af8ebb024222a42bcbfeb.nq.gz
│   ├── d2ea9fe0aaf77e504370157cc5ba6a0549710aec.nq.gz
│   ├── d37216873b45a58f9719c052b576610c671710b3.nq.gz
│   ├── d38108df6c2f1963660e9dc15616d9de8c19fae1.nq.gz
│   ├── d566bdfd121220cf0e257babafacf45616476152.nq.gz
│   ├── d6bf37407537f47145fc7ec017c581809c842c49.nq.gz
│   ├── d793a066101d4397ad46b36299ca0a6f1b8f21f0.nq.gz
│   ├── db2ce1288380b9abad3059ee37ea5dac8956f1e4.nq.gz
│   ├── dd8ca5ce7561d9d41dd3ed97ca83a12c27f16285.nq.gz
│   ├── de042c645b723ec5fde4d8792469ed3008d99caa.nq.gz
│   ├── de44212e636bc812eba0ebee78f5731f94bf1a5c.nq.gz
│   ├── e022792f5ca9c5f24ab70cfebc05789a601cf1bf.nq.gz
│   ├── e0c76f821c87fa42638179c620f991f2d3558a20.nq.gz
│   ├── e18f4cfe998f74f9a41c6633b742c340df7bab50.nq.gz
│   ├── e1a6b99ba63c14429e7ab00a39aea50c3e985157.nq.gz
│   ├── e4c4d2df04f9e380d1489061dab2d4979d90b234.nq.gz
│   ├── e622c98c8becf3c200c770a59e0bd33b70ed7583.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e888ffb01c4448dca09ef26bb3531776d79b7fca.nq.gz
│   ├── edaf750d8058459a368704f2e3c6185b883e31dd.nq.gz
│   ├── eeae131967a0bc9f78053dbd06be7be2d774fc5d.nq.gz
│   ├── f2efb9c8da29f1039b6a385890b9c728d3755f32.nq.gz
│   ├── f5d66607468fc63235e4ee0f1207fd10805d031a.nq.gz
│   ├── f757f1807b9e7cfe755087dd0138657ff05e826a.nq.gz
│   ├── fb0407c4e9bc6fe186313118bbeae7fcd2e41b36.nq.gz
│   ├── fca08175f66cd06ab20a0c3301a8e945d1595821.nq.gz
│   ├── fd557e6d7d6bdc1d47b8846383412057452e53a3.nq.gz
│   └── ff98d1d285479ee2636af3260f46e0bb6cfa5279.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4ca3ce3e5c55e5821d6068bac5c6e3806027a26f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 167 files
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

[huggingface/carbon](https://github.com/huggingface/carbon)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
