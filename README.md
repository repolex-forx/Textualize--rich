# Repolex Knowledge Graph of Textualize/rich

RDF knowledge graph data for [Textualize/rich](https://github.com/Textualize/rich), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download Textualize/rich
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
│   │   ├── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
│   │   ├── 84d9a1d8792ee76dcf8497f12fa69ee094aac282.nq.gz
│   │   └── 966ebdaae590cad7ecde0630923e186430960e10.nq.gz
│   ├── lsp
│   │   ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
│   │   ├── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
│   │   ├── 84d9a1d8792ee76dcf8497f12fa69ee094aac282.nq.gz
│   │   └── 966ebdaae590cad7ecde0630923e186430960e10.nq.gz
│   └── repolex
│       ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
│       ├── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
│       ├── 84d9a1d8792ee76dcf8497f12fa69ee094aac282.nq.gz
│       └── 966ebdaae590cad7ecde0630923e186430960e10.nq.gz
└── blob
    ├── 00336c3e11762c13d7a58614c15032e0b82e5192.nq.gz
    ├── 010ce3743566bc750c5e043199b0fa053fbe9e3e.nq.gz
    ├── 01c6cafbe53f1fcb12f7b382b2b35e2fd2c69933.nq.gz
    ├── 03202f2cd29e25d150b047d8211bc7af5f4e67f7.nq.gz
    ├── 036bcde0b1f318b3d22194ab1cca01cc4bcf9c3b.nq.gz
    ├── 0459369d190ff2377a8336429fb8cd7e1a08b3fe.nq.gz
    ├── 05c863a93dd968675df9b4df6b1e047ae315660d.nq.gz
    ├── 06ab11ef5e38e46079824158d4e29eb9d6806f22.nq.gz
    ├── 06de437202fa2615567bff20cddc369a073c3aa5.nq.gz
    ├── 06f813743edb0405a3810a24d7f5533d0dd0842f.nq.gz
    ├── 071957507bfc4cdd751dd2abc530f7a17aa97481.nq.gz
    ├── 074276b631405f9c5ae5a75acf0bcdaeaf966a6d.nq.gz
    ├── 077508fad535e832f5c6d969519d61aa61fff633.nq.gz
    ├── 07d526c50e1d532a99c45bd18399c0cb356fcbf7.nq.gz
    ├── 087740d5991f8c06b4bc0247f3b1cdd1b1a59057.nq.gz
    ├── 08c6eba328a805fadf7e74db17dff4023c5ca7c4.nq.gz
    ├── 09cf74aabbee36c38f326721aaf518da7826cfd6.nq.gz
    ├── 0a085c785df4b5889a0c678e5679e982b6af7931.nq.gz
    ├── 0a7d22fa1115873536c654bdcd13e08f859135f5.nq.gz
    ├── 0ae74bdde6a04295e9c0fbd17ef7edf5b5423d08.nq.gz
    ├── 0b46db1708291cc51eba57a3d43b356b85e43ce8.nq.gz
    ├── 0b7aaa575997b962a04d3c174cf03e51c0e6dbf0.nq.gz
    ├── 0b8f22dd777f0dbcb3fecd03bb0cd86ba0c25dd9.nq.gz
    ├── 0bcc67969542b0c6a4597365c40b45fbcb6fcaf6.nq.gz
    ├── 0bfb804c2e2be5e153ecdb1e40c6b5d49c1f63a1.nq.gz
    ├── 0c370d5fb89926055a955037bc248bf4a723a5b9.nq.gz
    ├── 0c548fc309b901f03fa79a2ebf7141b86ff3c95f.nq.gz
    ├── 0d78ca9f888f24bc2ec2043a7f370eaad4ec9dd7.nq.gz
    ├── 0d826bdaaa865d77f057fdcb0e03d6eb5738ab23.nq.gz
    ├── 0e2a2c5c38491a24635076389058aacdb7b6d9c9.nq.gz
    ├── 0edd22748d20119cf3d4139b6197675023a7bad0.nq.gz
    ├── 1067417f252b12a002146fe1c3e5191e54c953ee.nq.gz
    ├── 1108383708f84cf059239233408c7f534fb436ae.nq.gz
    ├── 112b7ba7c314939eef0dfe497655a6bda53a3753.nq.gz
    ├── 12278698cccfee5201c528b2d4a8314ee3fae3e8.nq.gz
    ├── 137f361aea96a7042fc17e7901aae09f5149f2d3.nq.gz
    ├── 1477bd64f066992c07350edc2a3e84f8089c7b5e.nq.gz
    ├── 14bcd02481f899753747e03855abf1e33ec1fa09.nq.gz
    ├── 14fb919ff5120db8314ec12c3354b269913f9512.nq.gz
    ├── 15ae06f6439a4c268143c9f3d18c4db366243b69.nq.gz
    ├── 169b1cf53f91ba41739de405c41a16abd6a83bf9.nq.gz
    ├── 16df34e1d55915d2ec44e7839f6910b27585a3db.nq.gz
    ├── 170f94b34d7a39230b6f5bed23de8e2e2083f33f.nq.gz
    ├── 1777d70eea73e30ab4aed3b248b1fd1c0e05a55c.nq.gz
    ├── 17851d4a6b14a911d676f206642eae1bc921b4ce.nq.gz
    ├── 184c219a9ee32e9d2f9b27054cb3d1fbda549c84.nq.gz
    ├── 1934e8421b6be2170b6d313b9a8a0fd4660bd379.nq.gz
    ├── 193739c6c93b411cd10c417a200cc32c5b855bbd.nq.gz
    ├── 194564e761ddae165b39ef6598877e2e3820af0a.nq.gz
    ├── 19b59828407e923d12e889da507eee9fc647e12b.nq.gz
    ├── 19b8d7433bd7ec18215da18dfdfc9de54d775e7f.nq.gz
    ├── 1af0d95c32152672dc4583296207907eb6534083.nq.gz
    ├── 1cac7b91b293eeef62055c1973170e922edee105.nq.gz
    ├── 1d1c6c1608a5b67046cb872f8a907903b590c691.nq.gz
    ├── 1debad2c4bbdce765480227bc05e8ac9144946f9.nq.gz
    ├── 1dfb7e75a80a77799e0b96848f842e3f9cebf2e4.nq.gz
    ├── 1f2877bb2bd520253502b1c05bb811bb0d7ef64c.nq.gz
    ├── 2033d7b98115adb0d0f1db2e90ae8977440e2cfe.nq.gz
    ├── 205b2458cd1b097a7c9dc59cb4b098b31e34de9a.nq.gz
    ├── 206c846de0bbbe3d7e060eea7c1768719bccd52e.nq.gz
    ├── 208d8acf6a15a0f6a7a67dc79fbeecaa50ad649b.nq.gz
    ├── 2100a46d7b661c8aaa5e5e78c75a46f143abc13c.nq.gz
    ├── 233804adff338dcd7e01f1de13894b1bfa108d6d.nq.gz
    ├── 23a34f5e96f6f2a749ced9da0c0854167bff7ed3.nq.gz
    ├── 23b192120eb8c5828a9dd0cd873e676c5206ced1.nq.gz
    ├── 244230d652762bfbcc5e106315c6d865dabb5891.nq.gz
    ├── 2455a404fcd3d6dedb92a2d3ab47a55f70ccd365.nq.gz
    ├── 24ef506172dee0ceeb56cd7a9a12c72ba9256eb4.nq.gz
    ├── 2573f3614d2db8cb9aa60232487b4d9c2462415f.nq.gz
    ├── 25772a0a59ef16bc386d87660fdebdd3c7c17f8c.nq.gz
    ├── 25e5237e7453f673910b9ab1049102c6c1cc6a13.nq.gz
    ├── 263e92d480bf3d5dad2c1745dee4cebcf7911ef9.nq.gz
    ├── 26ec6fffecb21e2c81b7cea3064480aa9d694b0d.nq.gz
    ├── 273b0dbc209d1867b3067d9d3180b7b5578112d3.nq.gz
    ├── 27dbfcbb9724a11c00f2334ea7b92cddce89141b.nq.gz
    ├── 2903a3cdd73048a80a1f34362886b8879e90ff01.nq.gz
    ├── 2951d6846f53686517cddfca71cd46c4b8d135aa.nq.gz
    ├── 2977495f299c8977d893018504ea498ef92a71c3.nq.gz
    ├── 29a263e6614597808a182216b51868c11e00c412.nq.gz
    ├── 2add8359f0ad17092c70b120d3abe5960126fb06.nq.gz
    ├── 2aed01727c20dd6283b0f1d2b4cc8eb9cbfae192.nq.gz
    ├── 2b0d250f7a0a5950699266c327b795a43da03717.nq.gz
    ├── 2b0f1425ff3aef884193805261f500cd7b22f782.nq.gz
    ├── 2b512ef82b7462061acf812cec32083b7cb2ecef.nq.gz
    ├── 2c1b9bfb1ce06526abd6443ada6bc7c7582b764c.nq.gz
    ├── 2c33d233f3ad7e48a34578d63ce77ebcb75b584e.nq.gz
    ├── 2c7ac3dbd54fd12bd3c72f0c74ae5212c2b8aaec.nq.gz
    ├── 2c9ac094f650480cd30aeca596fec4eed0d7fc0a.nq.gz
    ├── 2d926775af03b85c2bef899e9a97d6ba173a5f75.nq.gz
    ├── 2db134d7515ad2cf5aab3aeab3f09e5c57a4428f.nq.gz
    ├── 2e6fef7f5a1bf5552dc63f7d5078b19a847419da.nq.gz
    ├── 2ef306f3c65ea62a4e0e41844e0f16f9f980d421.nq.gz
    ├── 2ff91f64109d595246a00848a0e23e7a2c3f3a92.nq.gz
    ├── 3079aa470d8290d6c75e99eef4aff75c8fde7a23.nq.gz
    ├── 3190f65208b03e285bfb9ca521519e7a2d2c11a5.nq.gz
    ├── 327c131dcd2bf7753f1da360ca6aaf741fae1301.nq.gz
    ├── 328bbd964db106c2f839d90de8828b8d4304a2fe.nq.gz
    ├── 338c9299d03bb5b694dcce260ef3fc44b48b4a99.nq.gz
    ├── 33e431399ffb363f801ad1255b8b2cdcdaafab63.nq.gz
    ├── 3419825d90e5a1c186762af8ae35d9dcd8a61b9e.nq.gz
    ├── 34366bff99dbcb4287b280d09b4cbd568aae6df8.nq.gz
    ├── 36286df379e28ea997bea3ee1fd62cadebebbba9.nq.gz
    ├── 363eeb34a95910cfaf3dc5e0ef08f169856fd753.nq.gz
    ├── 37b880d0d40e4181fa7bc1c3d7ad8225721a9563.nq.gz
    ├── 390100ec8113ee52064e03b5d4331f7269b90336.nq.gz
    ├── 394fc3154010f94a6d7da2363f54a108e3281dc5.nq.gz
    ├── 3962ddc74a52c3d885021830fd87af4701acc1e6.nq.gz
    ├── 39b475dc376f2a0900a3728ffa9c68932a892a57.nq.gz
    ├── 3a2023154c3e450d06d75bcfb6d3583e189a99ed.nq.gz
    ├── 3a679b13d9a64c0252c625949293733f4ef2dbcc.nq.gz
    ├── 3a9cc32f11cdcd49f6ab77fc38497a9733bbd867.nq.gz
    ├── 3aab15edd400d8de0afcce7484d0e3d60b97f08a.nq.gz
    ├── 3ae7fa68b48e22113199e4d73b84ebb6bdaf1a31.nq.gz
    ├── 3b617e6edfb5560c03f2442ef5d323e733db8232.nq.gz
    ├── 3bf39fb7536357dea380f8d346459903703d2218.nq.gz
    ├── 3c4c086095dcb1bc4e416259f42961ef6e56394e.nq.gz
    ├── 3ca2b0ac87ea08d581b86a3a58be8c0d6bee5710.nq.gz
    ├── 3d431ac5e9e3bc3bd0ebcaf750f8997990444c3f.nq.gz
    ├── 3f0e3e45e1f5add380d7cfdd037a775306e6b30b.nq.gz
    ├── 3f7440234ee7dde945aef0e8a42e8441f33fedc7.nq.gz
    ├── 40562b07fc2f2ad7a364d27b3aaed650c1b250cc.nq.gz
    ├── 40d3a04a82d1d05c153698e92b681186dc32dcb5.nq.gz
    ├── 40e054b908aa3390e5288fd34a14041d8b4c7dd0.nq.gz
    ├── 41a9bc6006fec0b03ec786ea20debae70421961f.nq.gz
    ├── 41ae1ddf48400134cee80282d61a52537b3ccbff.nq.gz
    ├── 4203fe0404bc80990f8572ccb78778bd1dedd4fb.nq.gz
    ├── 420455d64897253f6d09560198ddd6c07517fdf5.nq.gz
    ├── 424b81adbd881a4e85dbf43d31f3e116809ab077.nq.gz
    ├── 43a929cc7b202064ad312e88b9168f3e275deb38.nq.gz
    ├── 43e4e870de8a742f663604325d17280a31f534db.nq.gz
    ├── 442ea0679f284a24dedcf951a1ec3bea7362468f.nq.gz
    ├── 45f5e99d9e886758da4ad879a3ed881cd33fa14e.nq.gz
    ├── 460f4248b4db27b4082d9c80ee8ffbfa16d583ab.nq.gz
    ├── 479fd7f46195ec70a6b23511c6753e7e70ce161e.nq.gz
    ├── 47d3b8e74873d96cd6c20bb18532060a4e012e70.nq.gz
    ├── 4930116b8eaea4f492a4541a576f7c205a88bc9e.nq.gz
    ├── 49f07c9a5ce800a4b155cdfc0c8d091ac832f1b9.nq.gz
    ├── 4a1e227a17ade390eb76f5f5a6c242f664bb108d.nq.gz
    ├── 4a592c867ac1c97dfbb5f5c040a1086bbb0cc03e.nq.gz
    ├── 4b9dd3dd81db2eb46ea0ce549106b242dc33ba6a.nq.gz
    ├── 4bd9a371a1c1545c6dd2a25fcff73c07cb5e474b.nq.gz
    ├── 4e0f3d7dae89bcd08eff7e98d988f1aed4a0c0bb.nq.gz
    ├── 4f65314220f2831a0b246cf42fde02fab098ba04.nq.gz
    ├── 505f215ca056b95e9ac12d9e7b2c299aa70530ec.nq.gz
    ├── 50ead9b1cb568fddb0b3f1e4841ff7af76051938.nq.gz
    ├── 51851beedc97779829311c97cd67e9715b8c5658.nq.gz
    ├── 520c668547661ab0e904c8c8e498fa008e87ba25.nq.gz
    ├── 52433e852d02bfadfe32daed0b1800dd89c1cbb3.nq.gz
    ├── 536a3de69c1a54d7be75f16c9fa07ce88bb57779.nq.gz
    ├── 53a96180582be76dcfdc3c4e06748736db2c18be.nq.gz
    ├── 546457a93d39c1b5fb3f2936da088a21ba58cb3f.nq.gz
    ├── 5496d4681c7aff523f1a0fc5e89048e16611cbce.nq.gz
    ├── 54b052551369519329717a6fbae28c2d613d6a9e.nq.gz
    ├── 5545d146f25342c6acbefed6750ba6af246d015d.nq.gz
    ├── 555da521151afd43b7fc9330f403ee91e1a62c4c.nq.gz
    ├── 566ecd0f3956259be545c9a6dc01047ffb907dcc.nq.gz
    ├── 56e1f92eaa067d1bc27dee10352b1a7305d53696.nq.gz
    ├── 57268a39dd106937701edaf7567157210d5eb10f.nq.gz
    ├── 5760dd393ce27eabecfb77d9511adb26a0a583e1.nq.gz
    ├── 589a21cf8d7f1e2df5a401353b8f707cd164f606.nq.gz
    ├── 58bde010836deec78d5081d267059f57fcecd780.nq.gz
    ├── 5a6dec17511351657b765bdd2ca4d7491474ccfb.nq.gz
    ├── 5adaa3dbed09a02d7207e1e1b6c3b93af3cd7904.nq.gz
    ├── 5ae40c2b2146a3d30564181e70a4bf0cb573d7f2.nq.gz
    ├── 5b221ab16af41f4b5dfdd8b322a922ce0f71138d.nq.gz
    ├── 5b8e8586eecbe06c7b3d2389ffc261e15b0ac5c5.nq.gz
    ├── 5bbb885dbecec1aa246f5b1a0ab597979dce7826.nq.gz
    ├── 5c6c0699deef7945fe2234f66a4999241d4346fe.nq.gz
    ├── 5e3798e86862e06aaec2ee2cc3986849c8699f8e.nq.gz
    ├── 5e697c1f8a96e407e0df6f0a9255071bfd71ed28.nq.gz
    ├── 5fe54e8590fcccfd8269a6a530537c8d1b8dc73a.nq.gz
    ├── 61547eb7757958b93fb6aa68971895ba0c76912b.nq.gz
    ├── 61a34b831dbaa92ea9983a7206e6eb3c772821ac.nq.gz
    ├── 61db2b0f03d62f667ee1ac07760deaeaeeb42a53.nq.gz
    ├── 623f83ca29c943dbf36fc43da061d629110341c6.nq.gz
    ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
    ├── 62e782d46f5bcb185821e6f7125e669c3a7332a5.nq.gz
    ├── 63b2cdc5165b14d585ffaed7621ec14643c26f31.nq.gz
    ├── 649279b06ecbf98bfb22e2a7d9792edc7984a076.nq.gz
    ├── 6555bf95b56d69f1f5ce9eb2492f61e6b7decb20.nq.gz
    ├── 65b2f2857f2447b8e6e8ad0d6c4dda0cf055368f.nq.gz
    ├── 66678a9bb1100bdca0ca321a422596f198e10f5e.nq.gz
    ├── 670988206de985adfc46daef2e924b48073161cd.nq.gz
    ├── 680f2d8339a181d8a3deb26074b61ee8cc85b68d.nq.gz
    ├── 6815e6858adac3483a62b42a851fe766c9d141dd.nq.gz
    ├── 68c467cde4c7f2b5d526551d9ed84b9918e15221.nq.gz
    ├── 68c96e5607a6b280ec3b53f0404c9acda0171768.nq.gz
    └── 68ebb5dfcbbc4bc7f9edbe32852d0dc65a1a7ad5.nq.gz

6 directories, 200 files
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

## Source repository

[Textualize/rich](https://github.com/Textualize/rich)

---
*Parsed on 2026-03-20 by [repolex](https://repolex.ai)*
