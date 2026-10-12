# Repolex Knowledge Graph of graphql-python/graphene-federation

RDF knowledge graph data for [graphql-python/graphene-federation](https://github.com/graphql-python/graphene-federation), parsed by [repolex](https://repolex.ai).

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
rlex download graphql-python/graphene-federation
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 653357cf08908264fe5abcbcbcdac4f49bd41cdd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 653357cf08908264fe5abcbcbcdac4f49bd41cdd
│           └── chunk-001.nq.gz
├── blob
│   ├── 003b1cf094098a3b3d2d816a5dbfc67c1b711501.nq.gz
│   ├── 004413dd5585f43888d18599ec2e5f8d5fa1c93e.nq.gz
│   ├── 03e35434e4f8ce547d8808f7d981c9cd6cb06b2c.nq.gz
│   ├── 04a105dc38c35b3f58bafb02ac10cb20477e16aa.nq.gz
│   ├── 06e3844c6dcacac4bef37b3963beaa5257162721.nq.gz
│   ├── 07119caa42a895842e4fdeff2f733c834de76e98.nq.gz
│   ├── 07f61ee8815d3411129448cd19437bf9f7077a25.nq.gz
│   ├── 0aa820390ab495883f28ccdc796c902e78ab55ac.nq.gz
│   ├── 0b90b1d83d26f4e42469c11b7d52e05852e491ad.nq.gz
│   ├── 0c2cf4327f1fc43c237eb2a8ee5775d206b2ca0a.nq.gz
│   ├── 0c9bf6701f9db6020ee9b9e5f155b712eab2ffa6.nq.gz
│   ├── 111e80f653d70fc7e95ab3ff81d1965eaf9c9fe1.nq.gz
│   ├── 189e27eaf8cf7295cdaa562070b70c0417cf4def.nq.gz
│   ├── 18bc3f50a5adddc7077d9f25508990cb7f61fe52.nq.gz
│   ├── 18d205c54d25c7bf5b4787b6ccfd5824d5a9d5d2.nq.gz
│   ├── 194f22c961ff0d04b944925318930cf7dd93308c.nq.gz
│   ├── 19d492fe478bcc29b7688082e2fe46772f3dc414.nq.gz
│   ├── 1bbb9bab86b149f7e92586022e27ea04a0d8800d.nq.gz
│   ├── 1c9d7e6aa0b673778da2405d20f896925f283b3e.nq.gz
│   ├── 1dee96d787b92a5d7be9f42ce3972fddb30dd01e.nq.gz
│   ├── 203306d952596808e9d6a5032faa69dc51a60bb3.nq.gz
│   ├── 2075b21637d04aadc0f18ae17715fb7e9a77f8d5.nq.gz
│   ├── 21c514b30911a685f18c70e1eab3cc459fc4fe61.nq.gz
│   ├── 2250c10542bfacd85d5052ef920cf3bafeb7e090.nq.gz
│   ├── 22ca0e8904bbbb45d693bc3538b1eec6b8c203eb.nq.gz
│   ├── 232545c4d3c6cbfbc602f464bdf2dfce2b89fb1f.nq.gz
│   ├── 23b9836a23d5629b21bb2c3b2e2113a1a795ce4f.nq.gz
│   ├── 2672e53d46d6ba7bbf3a11d65e6ea48a45bbad1a.nq.gz
│   ├── 276cae5eeb30fef633e33f6b70cbe85665686b3e.nq.gz
│   ├── 27b7f2ef37f3d1c2325fe15b8b6b067c73ebd306.nq.gz
│   ├── 28a9a9bc3cc3a43792922b8d13ce57d25710cc3a.nq.gz
│   ├── 28e25f7532e967dd8e39338757d0f4a3013e1953.nq.gz
│   ├── 2c0bb5dffd1a60325c49b05fa95fa1178c421583.nq.gz
│   ├── 2c1722e9bffd476a4dd37808fe09c5288f90be79.nq.gz
│   ├── 2d798c9b9af17572fb6937662eb2e1c41b49b85a.nq.gz
│   ├── 314927efe89ba22e78888a826ca6b887be80d52c.nq.gz
│   ├── 321e5ca09d0fec5a6ef31f33007b48e5b9491a93.nq.gz
│   ├── 32ffbb96f2ee0234fa2042c1c082c1b116c92ceb.nq.gz
│   ├── 3518310b8b0d54c4f0362344dbd5766618e8b2bc.nq.gz
│   ├── 35accdac45a7dc66cf1d3a93253878624e139a91.nq.gz
│   ├── 374141f3e36b911eb6b648cfa4dab7944ad119bc.nq.gz
│   ├── 378a5a5871927b64fc17878df700164e72861097.nq.gz
│   ├── 389eaa5d9cba5125ded597d2e82ed93e4cfebe33.nq.gz
│   ├── 3910916134801384b707d885cdea4e07f919d414.nq.gz
│   ├── 39e27f6838d21cdf148979504a221104c41e600e.nq.gz
│   ├── 3bf2a67b91e49328fbeca699ab1dbbec170c4daa.nq.gz
│   ├── 3cfcf377b51e4543db1227c578e2ee4eea69a397.nq.gz
│   ├── 3dfd30918fdffeda61297606886c92b4430b86e2.nq.gz
│   ├── 3e0ebdaaa230f7094f679b0c51dc10845d5993e6.nq.gz
│   ├── 406698148be3cfaa48f6abebf81d6ee85d34be3d.nq.gz
│   ├── 413f0259881d3d4a909346a39365eb5a854a1cdc.nq.gz
│   ├── 43030417189361bfb195820e41ce952eb22e8014.nq.gz
│   ├── 43824c2ea28efea328e6875de8511c59d6d5ed86.nq.gz
│   ├── 484f842ae66faf187d90554c8debd00779671f77.nq.gz
│   ├── 494e97a7a703545e2c9876e067e6d9a17fda8e64.nq.gz
│   ├── 4df72bfc6902541a29024389e7e3c62ab1ce295c.nq.gz
│   ├── 4eaefa0e0f237204e7c67ea31338303f2a423a7c.nq.gz
│   ├── 4f0cbb47c7eca567f35412cc8d5400f6d8b0cc35.nq.gz
│   ├── 503b4e5e4dc6ce20d60101c63eb8e43dccb79876.nq.gz
│   ├── 53924bc0d1ef681f802bc1843b88e917ffaeffa1.nq.gz
│   ├── 53c56a0877718274a5043240dedf983921424841.nq.gz
│   ├── 5424df8f452cd71869c7a09785e01abe5fb08ec9.nq.gz
│   ├── 55377e16a4de59eca8e512051aeff1fb33e584f9.nq.gz
│   ├── 56ce62d05af3d034536fa5c2a19bc033af780d35.nq.gz
│   ├── 574f372462419d88ca67aa9525b11faa4a2949c9.nq.gz
│   ├── 5b52db70176a24fdc4bb5e6071b04548fc204359.nq.gz
│   ├── 5c6b900046f8d1d1cee4313770a6de39b784e790.nq.gz
│   ├── 5c70c045622830673af3ecb45e0ccb8226bb7035.nq.gz
│   ├── 5e3ff240bca77d68167573a519088507af92bee9.nq.gz
│   ├── 5f0b7121494eee21e6b14f4421a46bae09a3d716.nq.gz
│   ├── 5fcf93fe48824259d28f176838aa56812d2eacf9.nq.gz
│   ├── 62870c2f592e589f1c02bed033179ce7b4650bb2.nq.gz
│   ├── 6551753c2a50a79bb7ea68fa6d2371f1c259db90.nq.gz
│   ├── 6679188fa36896749c6cd63a4fe473445923952b.nq.gz
│   ├── 6714bab9f4f3d21ddb510f3211b7a601dac27106.nq.gz
│   ├── 69caf55df506828317ea0760f32a6610922cbbdc.nq.gz
│   ├── 70c0e0f5f7c04fa0217f209265d5ef1b7e7a0873.nq.gz
│   ├── 71d13ffba18511087b53eecf70ff18aeac3a1004.nq.gz
│   ├── 7339a266d86cf70f90249d989040c4d0b9152c81.nq.gz
│   ├── 736669d03008c76fc3244f6f384d3ff54c604393.nq.gz
│   ├── 74330d74010f52b9c5f2327b60939599cf91d243.nq.gz
│   ├── 74d207f6177f14bff3a6e8a76fe90a72ec2b8504.nq.gz
│   ├── 74d7b4cb2ca389d7621f3e36d6a4f4f4b63620ba.nq.gz
│   ├── 7531f1427d5473991aaa48874ead22326270a7b7.nq.gz
│   ├── 75551c8f5dac3c39a91b87934f6355a6b52b1525.nq.gz
│   ├── 757aef447fc874a0019a65ea60c512d98bba6e60.nq.gz
│   ├── 765074e3b59e005773ea787bb6257421dbdc9488.nq.gz
│   ├── 76b1b3c3f8c698ad1414e5233e8dbc77cfe214a1.nq.gz
│   ├── 7842917feabce4eab48956e7abd1f9501e646bff.nq.gz
│   ├── 78c859755630def6a42e503fb00323fd2f30e5d1.nq.gz
│   ├── 791fa7056101a07cc9ee7d1b457dc50fd4e1c530.nq.gz
│   ├── 7a236879d46234e656ccc18ae6db2f043ecdb03e.nq.gz
│   ├── 7a31230f33189def24ce291854643837903c4981.nq.gz
│   ├── 7a811f793b1255118982e267722d31b415022ae1.nq.gz
│   ├── 7d2c1fdc67d653b522cf10fdce3f22e47830553b.nq.gz
│   ├── 7ecf821b6c6d62478af7e2e76b224525f0a4f323.nq.gz
│   ├── 7f1c08b47af75b329e05332031e6a0a8a56dbab9.nq.gz
│   ├── 7f41cf0110ac2e02e382274910c0306baa3d9fc4.nq.gz
│   ├── 815ff2c111a8d12c6a6aa25ce92c6035252c09a7.nq.gz
│   ├── 81cbc36a12883db993e5259a0fb819fc53591288.nq.gz
│   ├── 85c3fd382a72da9c6ec82d293ed8bb35d56663ce.nq.gz
│   ├── 867b4cd3a1c899bc137bddae64b3e5a7c704c3a2.nq.gz
│   ├── 86cf8d43ef67dd9895a7a3e4bfb3c84dc473481a.nq.gz
│   ├── 87c6efb15ed1e373c6b723f11652614f870c7537.nq.gz
│   ├── 88df38247de55930912514cd5fa75c2b54b24511.nq.gz
│   ├── 8ac3be18a889b801f6e0d6851e613aae77e9fa21.nq.gz
│   ├── 8bf001573b3bff8304d899de4c4321feaa95de8f.nq.gz
│   ├── 8c832336ebac068c5870da551af6a10e659def60.nq.gz
│   ├── 8dbcd77f763527a273a364e63be3ecf359d81e3d.nq.gz
│   ├── 8dcca6773d3591901a04f1e2f48aee0c59acab41.nq.gz
│   ├── 8e5e4a0e5e527112f36634b25f8beecc920ae01c.nq.gz
│   ├── 8f3e35f5c90686ddc8e1204955cef713ce950b6c.nq.gz
│   ├── 91423f6ff0cc788bc20861648bab20cbdf78bcdf.nq.gz
│   ├── 915ee9f878058327359856bcb1d14fca60df816e.nq.gz
│   ├── 92562aedac7165750f97018261d328230f96e476.nq.gz
│   ├── 92a66b34bfac9784d7e9d2e2491744e24781c917.nq.gz
│   ├── 9472e5aa3ca114e2c55805a69550b6773501d8cd.nq.gz
│   ├── 96fca37a1b763a7262292ad938a37bda75d3c90f.nq.gz
│   ├── 9775088e3088ae27dbef990bbe50e284460b2fd4.nq.gz
│   ├── 98afe4265948a31f9fb6577e8303b8d78210a687.nq.gz
│   ├── 9cfb00f573c65f2bcbd7361a6b8bbac46e456d65.nq.gz
│   ├── a5fae1d149dcad7c0623358ec44bf061bb1e719b.nq.gz
│   ├── a626dbe111051b1eb6c91361b52350b2df9e1ed7.nq.gz
│   ├── a772648f053e538e4108310952e4b50aaa4b7710.nq.gz
│   ├── a9cef2f1a36cec42294978cfc761bb8e21177381.nq.gz
│   ├── aac4f1675b8febd37268e8548f4c14a0bc3cf63d.nq.gz
│   ├── ab0f8dd4ed29ff401cceb38be4996fb18e758ea3.nq.gz
│   ├── ab58fcb02ede70ae882b341c5799a2cee7c98821.nq.gz
│   ├── ac2a88cbf91337f6bd31ddfc15d68313b0ada1bc.nq.gz
│   ├── ad5a0962252fbe5c5cbdc4948ff6ff872bd2be88.nq.gz
│   ├── ae1465700edd778633f170f52a266b60a01b44d8.nq.gz
│   ├── ae5e16679011e3daccea784cd58a54d3496a0ac0.nq.gz
│   ├── ae76ba8378ae948320a6c6c83b0c437d9b9047f9.nq.gz
│   ├── af09cc56480d2fb20feaddd4eb1cd9614e9bde71.nq.gz
│   ├── affab19c4ef43b1e4857d97868bf78b276defb15.nq.gz
│   ├── b170941b4a59e0b4f8b3305fe0f6073282803245.nq.gz
│   ├── b41f1e6af253631aeebc3ed3cfa35ce432bd1463.nq.gz
│   ├── b663f46b393bfbc3bdd19b41257b832928b2fb1b.nq.gz
│   ├── b75272b3e72143c9ed012dce6bea271a79bde853.nq.gz
│   ├── b7b90331ddfd7c76f594fb64eb2195f97111088e.nq.gz
│   ├── b7f969e60165bf4074c3304f0f637df2e1b1ea70.nq.gz
│   ├── bb7424c38d6c14d03e2828eaec3ee8c88557f50d.nq.gz
│   ├── bc07ff83df34ad39918ad05e299b991cd6f0aec5.nq.gz
│   ├── c074619facc8f7282a7f08999fc036fde691e671.nq.gz
│   ├── c0f6dc801cfe9461cbca504a09b3601a09246c8c.nq.gz
│   ├── c1fd4a75490a853284aeb0fb56f28c0a03fe55c0.nq.gz
│   ├── c3c984f3635da2ecbb8b19237ebb92b4607a79a5.nq.gz
│   ├── c477a7a03b7fb0dc263d5d571f12fc2774f441ab.nq.gz
│   ├── c50482f96b5b1c7eb6f4d0ebe9d794e570eeea62.nq.gz
│   ├── c58f8f5379c01a243ecd27013129ced57bd28784.nq.gz
│   ├── c6bbe8494293138600d0a6b4a07768b3fa69e83f.nq.gz
│   ├── c895a59bf314beb4a589f76f77723fb28f7bc9bb.nq.gz
│   ├── c9a36dfe84a79a26b85b88d28d7d2153d60e3033.nq.gz
│   ├── ca310626e0a6502e0bc06903ced951263c15e064.nq.gz
│   ├── ca4b8efd08096c943ab43e118c6e6695fd9d28b0.nq.gz
│   ├── ca8363be660a00483e5121c4f981ec2d2bbbe4f3.nq.gz
│   ├── ca8a6adfb4b5d8af15da5b893499590b9ad866fb.nq.gz
│   ├── cba49d9e0c3d66148fcdf385741a1baa50eb29fc.nq.gz
│   ├── cc8a641610d591ad4d77e0d7ab4da9e57755d44a.nq.gz
│   ├── cd2371c0d47bc1a736574a244117a96d888e33ca.nq.gz
│   ├── cd4d73abbd42b9dc668c1c3b7f3581b73fd3ba67.nq.gz
│   ├── cf0b5c6e7c38b46464bd6ca991e68c22137e7a97.nq.gz
│   ├── d07dfaf8898c8b8662316aa7e454c88f871cc3b7.nq.gz
│   ├── d0ee373cecbb09d238dcbb7de6a466b3fb22abe5.nq.gz
│   ├── d0fb5b5c2c1981afad1bf12e486130fdc8129c71.nq.gz
│   ├── d2087b8a2652f20fb8d05e9c0e75aa0217cf4020.nq.gz
│   ├── d4857ab8fa5e7cae2ea11cf8e2fbd8b181cdae33.nq.gz
│   ├── d56928428e512a48d0e7b5b8de45e5b50793c902.nq.gz
│   ├── d5fe4e936dc710c6255f599a41be4643c6df107c.nq.gz
│   ├── d903ea2ea5c6d556ce9784fa283c6533014f0630.nq.gz
│   ├── daa819007fd9c239aa713dadf559274f6420a05f.nq.gz
│   ├── dc107b34acdcba6cef1df0e30ec486bb73bb72d8.nq.gz
│   ├── de5a2ae99dc3879057ff0817ce28e0de44b5bfbd.nq.gz
│   ├── df7063341a068c5ddf6858628227a1915c6c68bc.nq.gz
│   ├── e16baf86ba73d1d2dc876ecd4ca4f542dca91c3d.nq.gz
│   ├── e179c9a0c1a464c54725e94acf0642ceea927cd7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6ff4bb40ded0fd1d87dfcbaa6878a1bd2300c67.nq.gz
│   ├── e797c61a4a5f0e8c5fd20c9324a3d5a9f4da8c9b.nq.gz
│   ├── e7bca915e98a7d8bc661bbb510fffe6015290941.nq.gz
│   ├── e80ef8b7a350ec60a12d29ae4bec8d87374acd7a.nq.gz
│   ├── e9d22dc778a0bc0356e6b7ef48eecda3d8717dbe.nq.gz
│   ├── e9f845030745490a12539c5d5de3f3d83cc89977.nq.gz
│   ├── ebff3a82a51f94d0f33dbe524dc24ae01580506e.nq.gz
│   ├── ec309be7ba6ca3a6f62e8f6cd850d1134532c7a5.nq.gz
│   ├── f0c4d0d6be155972dac713074bf26db3b7255d8d.nq.gz
│   ├── f370561165faa8862b6463d12f7c446700914d2e.nq.gz
│   ├── f3d485f3dbbae962809f25fe9aea94ae06f34e16.nq.gz
│   ├── f438018706e01b193c936553a18b21acdc26267c.nq.gz
│   ├── f487e9045e76fd03ab8c35caea0e5ef83728aa3b.nq.gz
│   ├── f59c3fc2f5643aa8931bb27931ff048e230a2443.nq.gz
│   ├── f7e41678f36d91a951ad2edf6c0eaeaf51c6f3f0.nq.gz
│   ├── f827711c11e36dcdd6ee1bf297e4a28a8a19ed95.nq.gz
│   ├── f926bca189105db995f21a7e148c704824d4d763.nq.gz
│   ├── fb4b41a90538edd74535849371620b0a503315fd.nq.gz
│   ├── fec2211a6b37292d12e7934b88f597d09bfefe15.nq.gz
│   └── ffbcca5a68f70fabaf88dd9d184f3223f2ecc026.nq.gz
└── branch
    └── branch.nq.gz

8 directories, 200 files
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

[graphql-python/graphene-federation](https://github.com/graphql-python/graphene-federation)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
