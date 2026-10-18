# Repolex Knowledge Graph of scverse/anndata

RDF knowledge graph data for [scverse/anndata](https://github.com/scverse/anndata), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/anndata
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e90df01da4a7676f5624edb2f63a8fbf089d339b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e90df01da4a7676f5624edb2f63a8fbf089d339b
│           └── chunk-001.nq.gz
└── blob
    ├── 0130c666d4366463dbfe81dcfef25975551df7ad.nq.gz
    ├── 022b61050c9ecdaeab266cfda4c2cbb96f8d49f7.nq.gz
    ├── 059cd082f6cf74d5a20da2276bc207b2e0c67e05.nq.gz
    ├── 06266aa845ee4117703234cdb1e326c94183f002.nq.gz
    ├── 0657a4be3dbf7ebf2b6438c671ba5db1ea697f69.nq.gz
    ├── 07012543d81da8ebb74f9ab3424ef09c0587a794.nq.gz
    ├── 075503276ec84d44c482150d6c7b1b8b1f997e6c.nq.gz
    ├── 07718cede56a9f243710bc8dae5ba66a3a85c6e8.nq.gz
    ├── 0895c4014a59a7458a729160713f62e7ec24625e.nq.gz
    ├── 08fe80fe4433514d1f1f79de6e204c19a5b8de16.nq.gz
    ├── 09a1f6f3dde3e3e62707995e6e56b12646fb0c8d.nq.gz
    ├── 0b4138b57cd1dae9fb575e3b92520fad7d396662.nq.gz
    ├── 0c6eae4f52e0da07f788ecd38d582a37d145da3f.nq.gz
    ├── 0d1318a3ff54d6c92c4c2be19e8849adf6646956.nq.gz
    ├── 0de9b8c2a334e5f2108fa5d03b1c3aae04968efd.nq.gz
    ├── 121e9b6dc504c48f62f2e8183f449ba87555fda6.nq.gz
    ├── 127f4d72c420dca7a00056ec2d7a047fdc99f4b7.nq.gz
    ├── 140c058e71b905823c78b7104301d0e0a4672d72.nq.gz
    ├── 1599425be6aad5be30996dbc56af6475d9c4a1a5.nq.gz
    ├── 1832b95a4698e71312e4153449666fa06a72995a.nq.gz
    ├── 1ab25338ce668b76730ed77e1d496e1b2c47152e.nq.gz
    ├── 1b5f4a21351c1496ac7e52d85c692f345c9da414.nq.gz
    ├── 1bc33742d63891f2462e9b87d4fb132fdf4447bc.nq.gz
    ├── 1bf63e95da896d656ab162e628b53f503ba9b6d8.nq.gz
    ├── 1c98a117e2dffe3517b714a156fcf06a866e7db3.nq.gz
    ├── 1d172bfa8cc489b9370adcf49a6243da7529948d.nq.gz
    ├── 1f48d25e94649bba736e59c6e5fc99ebb942e7e1.nq.gz
    ├── 2149a415836f21704aaf30ba448d2ead5969a434.nq.gz
    ├── 21e6b43ac906bca4fd09ef744600f22743928edb.nq.gz
    ├── 21f64036213e067b42cbcb9ffbad69901400c720.nq.gz
    ├── 22a40bc6e8dd993e9d95d1482bcf2ec5a08ea4ec.nq.gz
    ├── 22b72eeccb9b01d644819266c7928db83e584852.nq.gz
    ├── 23d8491ed992211140d912c3adfdb20ddc7e6b9a.nq.gz
    ├── 248bdc1e4302a385bda96ad7e728dd7e31fb5b7b.nq.gz
    ├── 249f6cf58fe0c8753ec75b0e3cbb3fca1eda3bf9.nq.gz
    ├── 254d8274918001421260856768be74a4153e0736.nq.gz
    ├── 2587ba8cb098d9d4ae70086581bc45e23b3e8de0.nq.gz
    ├── 259306320a60046791c90eb44d4716bd789f0638.nq.gz
    ├── 25dbada502db3dd265cee4caff67c620bc0d2fb1.nq.gz
    ├── 2615ee8d5a5371e3a285696d701f41bfc09d936d.nq.gz
    ├── 294643930ab6cb3de05062e9973b52a887c16056.nq.gz
    ├── 2a2b4e06d56e8e113b67fecd43b8938406338a06.nq.gz
    ├── 2ab7dbfdc84cb4afad2bb733eba6492782a670b4.nq.gz
    ├── 2c4da9cd62f95461145da3d702f4d8ca6394c4ec.nq.gz
    ├── 2d41eadf63419aa16d0274fb0b09900fa5e20d25.nq.gz
    ├── 2dd2e54d1920865399ecb0ecaac8f5edd366d5a1.nq.gz
    ├── 2f1b23f50cce00c1231e22f28a1eba69ab3a22af.nq.gz
    ├── 30e63f8b30570c701408d4efe003d224083d6abf.nq.gz
    ├── 31e0ecd1be53b52c31b0e983dc03d146c2737e2f.nq.gz
    ├── 32566ea0d7c0a26f0dbdd1883cc6b5c6de25fe8e.nq.gz
    ├── 3375ecd9042b405dfd296b7cef15e6fe3f26cf75.nq.gz
    ├── 33cbf284e7f238f72e3820803e99d26f2f0f32b7.nq.gz
    ├── 34c6b6229b6a03d653fc0bbc4015916e9dcda442.nq.gz
    ├── 36c9441fead472fd4e5c851f331e050af81a8f29.nq.gz
    ├── 370fb6f760d91c09233478a33d8619d19486cb37.nq.gz
    ├── 37780d74f1f6712f22abf88bfb27b7a504e80eef.nq.gz
    ├── 383085122b8ba7e7d9b8f8ef4cb876ed5098ce08.nq.gz
    ├── 3855f513fe771f9b3250f29c8fa4b29270ef6735.nq.gz
    ├── 3886a05eded354916a5f96b4daca78a6e9d11c99.nq.gz
    ├── 38c8bc6f1956566799a279651e2ae17a90711448.nq.gz
    ├── 3afdf4747544f34435bdac4f3b7ca88be1d5587a.nq.gz
    ├── 3c5216fa982f7c134238d3f16bf76b44932acbd8.nq.gz
    ├── 3cfacf85b288ab2f65228accc193040a112da5ea.nq.gz
    ├── 3fe17cf5aa850a677fe0eae299f81f99e359688a.nq.gz
    ├── 407ec8a7f29201fd0a319abbd9c9ce247246e91d.nq.gz
    ├── 41a6cdc5cc6c88d1cea01977736ed6a792ac80b2.nq.gz
    ├── 42045b8243922722a7aeb73c4e64b0fe49f840c0.nq.gz
    ├── 4272d0585d5d347d611bdbade018c97904760561.nq.gz
    ├── 433609251879b18ea1b3df70c44a85b4a11c8bed.nq.gz
    ├── 44b959d96d6e3c4f0acc14b6450a1711a43aa211.nq.gz
    ├── 45ab71583f4cb765dc611cfa8100400c5f1c8aed.nq.gz
    ├── 460af685f3a0e5a312411731c378b1d7cdb3b31c.nq.gz
    ├── 4679405de93e498b359040923c4e3a8f05e8c1b0.nq.gz
    ├── 47085c5a1df51741ecaf830cf76d2d2d83db824c.nq.gz
    ├── 484ba82c947cd4dfbbbb59fed317f736d8aeee34.nq.gz
    ├── 48f7a5e0681e9dd9ce42d2a1d974a24c4080765b.nq.gz
    ├── 4a1f7895e6a05ecf40ce6628f64ec1cc9f02da84.nq.gz
    ├── 4af9e2deee25227a2e561e8d187865d74d99b937.nq.gz
    ├── 4d3d065cd1403389a94142b6dc7b5d4eb4173013.nq.gz
    ├── 4d451288fc8f4b0111e860ae87fe3635c661e468.nq.gz
    ├── 4f115ae13fc3d1b5a0f8a62b78526a06fc249b5d.nq.gz
    ├── 516514ef44a8db095839ea065128ef0238280d3c.nq.gz
    ├── 51a9bd0a435a28439479a5593249da2c739e8a80.nq.gz
    ├── 5315119cc7377b551c66d2fc4541c9ead3883077.nq.gz
    ├── 533e9b46a08f3fcd0667218e523bf14a788b4c00.nq.gz
    ├── 5374a096e0349263b8f7bb967d55c6eea6859b8c.nq.gz
    ├── 53c0b7516f5ec93685e794c8ae1edc859973fd5e.nq.gz
    ├── 54458f9d12dbab32099c2b3c8b91f34c050d51f0.nq.gz
    ├── 548d1bdce9664eb527eb6adf2c7c400f27fd98b7.nq.gz
    ├── 54ab541a5b50a3b4301248e76ce36fb439edd9fb.nq.gz
    ├── 54fe09b55ff36da2494b4ce06dc950621d98ad58.nq.gz
    ├── 552273de4fec7f71cfa52ecac4f24a7a47f57ea7.nq.gz
    ├── 55356d31209ac55d3223c925500304fddf797bf9.nq.gz
    ├── 56a60ea36d04439f9a2b43c565c42c3ebe74134b.nq.gz
    ├── 56ab8c4fb839da6976578f239f557f0fed8329c1.nq.gz
    ├── 58685096955cdc9f1bdbf866f304b9166a54d65b.nq.gz
    ├── 58ef3d422382cf4e3264eb7ccc7635fd1d10ec10.nq.gz
    ├── 59259316324d72be7ef17735532fdf004dee48cf.nq.gz
    ├── 5b4174bb9412296f35c4ed0305f82e5c263977c0.nq.gz
    ├── 5b4bf63f854f1e6e2fc54c080704a49822813b5b.nq.gz
    ├── 5b62547f9aef3da3a38806baf365ea8c059675d6.nq.gz
    ├── 5c536d2801837cd8d34c3c4ec2c513e4461caa35.nq.gz
    ├── 5c5e9821550eb1b446a704b1b023aabf0ba08b0e.nq.gz
    ├── 5cb0e0ee254f55b49e3eddba10e6db48864e9f9d.nq.gz
    ├── 5cb8b43df614bae2bdcfc57ba1d6b31537229189.nq.gz
    ├── 60b7a352b89a66ad52cc32a36516b4910d92f179.nq.gz
    ├── 6123b12b292268092c06fe533027569e03e79d2e.nq.gz
    ├── 61b1d12705af2c34c26adee7642c650d80ab6ab2.nq.gz
    ├── 636f54cb4f1b390d2d10c1c7d8323a8804aa3a6b.nq.gz
    ├── 6a62307ea3352a2a8924f28defcc53d865919f88.nq.gz
    ├── 6a699380097fe03a6e33d8bc5f968fd0c82ca096.nq.gz
    ├── 6a8f90a80ed73c88f16a00349db530398fef6bc7.nq.gz
    ├── 6c45af0980a27c09ec4c70d9e1d3bb7227c3898b.nq.gz
    ├── 6ddb41161d26c8150f20d18a25569a7fd1fa6e57.nq.gz
    ├── 6e5e456482063e202824d160ab1910ba16036af9.nq.gz
    ├── 6f1af32b93ac283b8f364b72108af76b45994e2d.nq.gz
    ├── 6f992e79bcec77e4a4072ba21ce73d8cd8482d5e.nq.gz
    ├── 730f7f1c6b084a8fe1f15bd1b29a8693e50ec4f9.nq.gz
    ├── 74bcf8a68376495440b384aed9113d610f02c458.nq.gz
    ├── 74f24bb98e60961cac5ade2bc24af53a8ff3b035.nq.gz
    ├── 7549dc5c0fd87c1c3aaa830bd8dcf52365d8b954.nq.gz
    ├── 772c9e8b2fdde66164bedcba1f4182b649676336.nq.gz
    ├── 7770ef545fe273f0edb1fbae20244ae35b6c21df.nq.gz
    ├── 780f5a39cb67f25aa19262399930879e7f65f3ea.nq.gz
    ├── 78a2b4be5efd625dc9ffc0a31dbb92d603e7f4b4.nq.gz
    ├── 7918beffba657490f75a027a74672d799e625f26.nq.gz
    ├── 796f2c1341c26a107ac2298fd7add210106a812f.nq.gz
    ├── 7d0217d9f7086932e73a38c3cee6ffeaa5b44317.nq.gz
    ├── 7dbc44520500f5fa00d30ff2df2153b8134a5770.nq.gz
    ├── 7e1a1d3692f335ed726c60a966b054afb6c45eab.nq.gz
    ├── 7e7443b700183166f0c79554e6dbad83b7f06920.nq.gz
    ├── 82cc9212cd225a8672c02795f35b33c1ec71bd21.nq.gz
    ├── 834a7a7c4a9d2aa74f994692539edc1ddd930053.nq.gz
    ├── 8398ce84548f1297094fbefee8a7ed400f129163.nq.gz
    ├── 839c70f8e71c579308aaa899df3a31c6c63a5ad1.nq.gz
    ├── 83c573114f690e62ff5401dd152c2333f5b3ef94.nq.gz
    ├── 83da697efee8d96db92e2e488e02d76d57c3490e.nq.gz
    ├── 83f0ef18f7bcb7681458dc153c787ae52d3122d5.nq.gz
    ├── 858d2f5fda6e98a13bac9ef422410f8e4047b933.nq.gz
    ├── 85d63781bf7e5e32c703012997e7702a8896b71b.nq.gz
    ├── 867524bee1a310faf621b0a6b272c0693201fcc7.nq.gz
    ├── 86bfd66b7900e3439123b60fcbb4515135472d25.nq.gz
    ├── 8987285b7430b593308c26c1996061032a024c50.nq.gz
    ├── 8a4a687b1a1c88fb7e9dd5fbd6d00bea95576749.nq.gz
    ├── 8a8c0a02d5bc853e0df8d50683e59ae316b231b5.nq.gz
    ├── 8b878f9637e2c536e0d282a69c2f033a0d56df87.nq.gz
    ├── 8ca3fe38daa3bd445666ac3fc2512dce21a41010.nq.gz
    ├── 8dadb44633954d2cadc5ff6ea8c31e26e368a0f3.nq.gz
    ├── 8fd2630f15fc5feb4f48025be81762887085a57b.nq.gz
    ├── 90d906ccfd83ff5ddbaaf4b8e3d66aaa1a8f2e80.nq.gz
    ├── 912aa2ce1f07115842a1481c212e650191b3d301.nq.gz
    ├── 93d3c6769cc43f9d576d0318fc120a36717ac369.nq.gz
    ├── 9555285bdc44d4a75745594b62011287395c366c.nq.gz
    ├── 95855a49481c91eea1fc5efbd2d32af415f8d36c.nq.gz
    ├── 960d2aaf29ea8d2ef0e848f8c509cd5a4c17c39b.nq.gz
    ├── 9672591a8cb7c04b0711ea8275875a1c7d1e64e1.nq.gz
    ├── 96c94eeff09674f43aa8ca73f967007b9318bbe7.nq.gz
    ├── 9733732e35cc67ce5330857336d784b3fa2513a3.nq.gz
    ├── 97bb774a00563162ecbada0831df868e706657b0.nq.gz
    ├── 989405591ad31ca6bccaf8aaa1557ea0e9532c1c.nq.gz
    ├── 9b78d47c060b7c1eb027e044309e5559a1d1e5f8.nq.gz
    ├── 9c42a3ea24e1411ceffc020ae44407a2c57d05e2.nq.gz
    ├── 9cca5f3520f3d46a114259c6cbbd78da2f45b785.nq.gz
    ├── 9d6b596758928a3a51346142a06d279267793e32.nq.gz
    ├── 9e4954f8b28d247a029f46187de516e49c9ed839.nq.gz
    ├── a1276a3a3b4a4bb8401348330d8bbcae4dea026c.nq.gz
    ├── a285fb27a90b386891c9c1a0a301add474c3b475.nq.gz
    ├── a604592318b16e9d4e030667fefbc231a8630adb.nq.gz
    ├── a8c4eaa7b1edfa7eec53bf2467c20cf265260c93.nq.gz
    ├── aa21c163173b2d957a446ed0e9d87fc01abe0f3b.nq.gz
    ├── ab15a05ed635009bdc5625c753a9ee248f786f73.nq.gz
    ├── ad4aecf6a3e4a20255375c8e8aefc57d9ee368fd.nq.gz
    ├── adb7dc201a553c907b72a05b0b89bfcdbbfdc655.nq.gz
    ├── ae0aadb54d3f04a31d55ba21389095d637184566.nq.gz
    ├── ae90e91ced32c3e9bebd1f68f8d25c249fa86b6c.nq.gz
    ├── b0347956906ee12e9e923ae8a48fae5b2e353020.nq.gz
    ├── b104f4abe1410692d98a29bf780fef1db2e336f4.nq.gz
    ├── b112e947ba5e2d0fb1ee08d61b24c22643ea6eea.nq.gz
    ├── b278798524f2ba8b9a1bb9440bff2059ba3ac143.nq.gz
    ├── b3c5c5a81b4df32dd257906ee59bf7659f463d4a.nq.gz
    ├── b3e667ae30df636bd3992e1da39b2f806119500e.nq.gz
    ├── b58c5148cdb20299aa4c66562a9b526f6b9afc3f.nq.gz
    ├── b59c17cccabaa39ea978cd60825a3588c82d862d.nq.gz
    ├── b90cd6713b254fcbe51d7d4f00c26564c18c3c72.nq.gz
    ├── b9309af3ebf2abdde8785827437b49bff7a7c330.nq.gz
    ├── ba9c2ca2a3ea9f51b65dfce041deb619ba5589ff.nq.gz
    ├── bb555858b5d806173cc84b7f86def7844187452a.nq.gz
    ├── bf4241b386b989b0951ea7c1d04043021ba91562.nq.gz
    ├── bf684f514d793452b0b695bb0be4504a9cd602cc.nq.gz
    ├── c1e8a19f01e2d7b436bdedc49656f39bf3f40068.nq.gz
    ├── c21ad972198e051fee80a9f445b568af672d1986.nq.gz
    ├── c22fa467b8f7de71cce5026c51e32292cb2055ee.nq.gz
    ├── c4056be43a6d5199b8d790d6a384c4a9d07127e6.nq.gz
    ├── c478e1547a0c82aa53dabdbdb8b80be90f71234c.nq.gz
    ├── c5780589fee8f45096a4de5205a3e9140fe506b3.nq.gz
    ├── c5efe758681fc70f862dbcf34a8cbf2be1020175.nq.gz
    ├── ca64f18aa3040dc992cc693bfc723482520e4473.nq.gz
    └── cb48b24520e8866c5ee349d32bedb0037e6b7279.nq.gz

7 directories, 200 files
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

[scverse/anndata](https://github.com/scverse/anndata)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
