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
│   │   └── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
│   ├── lsp
│   │   ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
│   │   └── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
│   └── repolex
│       ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
│       └── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
└── blob
    ├── 00336c3e11762c13d7a58614c15032e0b82e5192.nq.gz
    ├── 01c6cafbe53f1fcb12f7b382b2b35e2fd2c69933.nq.gz
    ├── 03202f2cd29e25d150b047d8211bc7af5f4e67f7.nq.gz
    ├── 0459369d190ff2377a8336429fb8cd7e1a08b3fe.nq.gz
    ├── 05c863a93dd968675df9b4df6b1e047ae315660d.nq.gz
    ├── 06ab11ef5e38e46079824158d4e29eb9d6806f22.nq.gz
    ├── 06f813743edb0405a3810a24d7f5533d0dd0842f.nq.gz
    ├── 071957507bfc4cdd751dd2abc530f7a17aa97481.nq.gz
    ├── 08c6eba328a805fadf7e74db17dff4023c5ca7c4.nq.gz
    ├── 0a085c785df4b5889a0c678e5679e982b6af7931.nq.gz
    ├── 0a7d22fa1115873536c654bdcd13e08f859135f5.nq.gz
    ├── 0ae74bdde6a04295e9c0fbd17ef7edf5b5423d08.nq.gz
    ├── 0b46db1708291cc51eba57a3d43b356b85e43ce8.nq.gz
    ├── 0b7aaa575997b962a04d3c174cf03e51c0e6dbf0.nq.gz
    ├── 0bcc67969542b0c6a4597365c40b45fbcb6fcaf6.nq.gz
    ├── 1067417f252b12a002146fe1c3e5191e54c953ee.nq.gz
    ├── 1477bd64f066992c07350edc2a3e84f8089c7b5e.nq.gz
    ├── 14fb919ff5120db8314ec12c3354b269913f9512.nq.gz
    ├── 17851d4a6b14a911d676f206642eae1bc921b4ce.nq.gz
    ├── 184c219a9ee32e9d2f9b27054cb3d1fbda549c84.nq.gz
    ├── 194564e761ddae165b39ef6598877e2e3820af0a.nq.gz
    ├── 1af0d95c32152672dc4583296207907eb6534083.nq.gz
    ├── 1d1c6c1608a5b67046cb872f8a907903b590c691.nq.gz
    ├── 1debad2c4bbdce765480227bc05e8ac9144946f9.nq.gz
    ├── 1f2877bb2bd520253502b1c05bb811bb0d7ef64c.nq.gz
    ├── 205b2458cd1b097a7c9dc59cb4b098b31e34de9a.nq.gz
    ├── 244230d652762bfbcc5e106315c6d865dabb5891.nq.gz
    ├── 2455a404fcd3d6dedb92a2d3ab47a55f70ccd365.nq.gz
    ├── 26ec6fffecb21e2c81b7cea3064480aa9d694b0d.nq.gz
    ├── 273b0dbc209d1867b3067d9d3180b7b5578112d3.nq.gz
    ├── 2903a3cdd73048a80a1f34362886b8879e90ff01.nq.gz
    ├── 2951d6846f53686517cddfca71cd46c4b8d135aa.nq.gz
    ├── 29a263e6614597808a182216b51868c11e00c412.nq.gz
    ├── 2b0d250f7a0a5950699266c327b795a43da03717.nq.gz
    ├── 2c33d233f3ad7e48a34578d63ce77ebcb75b584e.nq.gz
    ├── 2c7ac3dbd54fd12bd3c72f0c74ae5212c2b8aaec.nq.gz
    ├── 2c9ac094f650480cd30aeca596fec4eed0d7fc0a.nq.gz
    ├── 3079aa470d8290d6c75e99eef4aff75c8fde7a23.nq.gz
    ├── 34366bff99dbcb4287b280d09b4cbd568aae6df8.nq.gz
    ├── 36286df379e28ea997bea3ee1fd62cadebebbba9.nq.gz
    ├── 363eeb34a95910cfaf3dc5e0ef08f169856fd753.nq.gz
    ├── 37b880d0d40e4181fa7bc1c3d7ad8225721a9563.nq.gz
    ├── 390100ec8113ee52064e03b5d4331f7269b90336.nq.gz
    ├── 3962ddc74a52c3d885021830fd87af4701acc1e6.nq.gz
    ├── 39b475dc376f2a0900a3728ffa9c68932a892a57.nq.gz
    ├── 3a2023154c3e450d06d75bcfb6d3583e189a99ed.nq.gz
    ├── 3ae7fa68b48e22113199e4d73b84ebb6bdaf1a31.nq.gz
    ├── 3bf39fb7536357dea380f8d346459903703d2218.nq.gz
    ├── 3c4c086095dcb1bc4e416259f42961ef6e56394e.nq.gz
    ├── 3d431ac5e9e3bc3bd0ebcaf750f8997990444c3f.nq.gz
    ├── 3f7440234ee7dde945aef0e8a42e8441f33fedc7.nq.gz
    ├── 40562b07fc2f2ad7a364d27b3aaed650c1b250cc.nq.gz
    ├── 40d3a04a82d1d05c153698e92b681186dc32dcb5.nq.gz
    ├── 40e054b908aa3390e5288fd34a14041d8b4c7dd0.nq.gz
    ├── 4203fe0404bc80990f8572ccb78778bd1dedd4fb.nq.gz
    ├── 424b81adbd881a4e85dbf43d31f3e116809ab077.nq.gz
    ├── 43e4e870de8a742f663604325d17280a31f534db.nq.gz
    ├── 442ea0679f284a24dedcf951a1ec3bea7362468f.nq.gz
    ├── 45f5e99d9e886758da4ad879a3ed881cd33fa14e.nq.gz
    ├── 460f4248b4db27b4082d9c80ee8ffbfa16d583ab.nq.gz
    ├── 479fd7f46195ec70a6b23511c6753e7e70ce161e.nq.gz
    ├── 49f07c9a5ce800a4b155cdfc0c8d091ac832f1b9.nq.gz
    ├── 4a1e227a17ade390eb76f5f5a6c242f664bb108d.nq.gz
    ├── 4a592c867ac1c97dfbb5f5c040a1086bbb0cc03e.nq.gz
    ├── 4bd9a371a1c1545c6dd2a25fcff73c07cb5e474b.nq.gz
    ├── 4e0f3d7dae89bcd08eff7e98d988f1aed4a0c0bb.nq.gz
    ├── 4f65314220f2831a0b246cf42fde02fab098ba04.nq.gz
    ├── 50ead9b1cb568fddb0b3f1e4841ff7af76051938.nq.gz
    ├── 51851beedc97779829311c97cd67e9715b8c5658.nq.gz
    ├── 53a96180582be76dcfdc3c4e06748736db2c18be.nq.gz
    ├── 5496d4681c7aff523f1a0fc5e89048e16611cbce.nq.gz
    ├── 5545d146f25342c6acbefed6750ba6af246d015d.nq.gz
    ├── 555da521151afd43b7fc9330f403ee91e1a62c4c.nq.gz
    ├── 566ecd0f3956259be545c9a6dc01047ffb907dcc.nq.gz
    ├── 56e1f92eaa067d1bc27dee10352b1a7305d53696.nq.gz
    ├── 57268a39dd106937701edaf7567157210d5eb10f.nq.gz
    ├── 589a21cf8d7f1e2df5a401353b8f707cd164f606.nq.gz
    ├── 5a6dec17511351657b765bdd2ca4d7491474ccfb.nq.gz
    ├── 5ae40c2b2146a3d30564181e70a4bf0cb573d7f2.nq.gz
    ├── 5b8e8586eecbe06c7b3d2389ffc261e15b0ac5c5.nq.gz
    ├── 5bbb885dbecec1aa246f5b1a0ab597979dce7826.nq.gz
    ├── 61547eb7757958b93fb6aa68971895ba0c76912b.nq.gz
    ├── 623f83ca29c943dbf36fc43da061d629110341c6.nq.gz
    ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
    ├── 62e782d46f5bcb185821e6f7125e669c3a7332a5.nq.gz
    ├── 63b2cdc5165b14d585ffaed7621ec14643c26f31.nq.gz
    ├── 649279b06ecbf98bfb22e2a7d9792edc7984a076.nq.gz
    ├── 6555bf95b56d69f1f5ce9eb2492f61e6b7decb20.nq.gz
    ├── 66678a9bb1100bdca0ca321a422596f198e10f5e.nq.gz
    ├── 680f2d8339a181d8a3deb26074b61ee8cc85b68d.nq.gz
    ├── 6815e6858adac3483a62b42a851fe766c9d141dd.nq.gz
    ├── 69551b25d68259585d312094e46cfc25b9126559.nq.gz
    ├── 695c888e83a9b6cd3dd636f10d22b5e90d7bb827.nq.gz
    ├── 6a247d793cff5e082e4bef8ec17e2486f9c777f8.nq.gz
    ├── 6ae9d219e32aae9684a615ee1a5f7e3b8f1c52be.nq.gz
    ├── 6f750b220ebe8a0176d81a347ef40205b234f61b.nq.gz
    ├── 70005f85e5b2e9414307aa2cb11300238b93efc4.nq.gz
    ├── 71eaa616b47a559f41336d16d38d5fb812d5284c.nq.gz
    ├── 73fd2fc6bce3061a6e3a621556757dbcb96174af.nq.gz
    ├── 74241c489c744237bb1fa88190378e855e7be377.nq.gz
    ├── 756bb95a2ce8eab23dbcd7d56d2037b26eab1997.nq.gz
    ├── 76b41f4bb7808195caa44095e46ec57bbadf1ad0.nq.gz
    ├── 76f7ce9c35e0dc2501c506e64bfa45077674fd84.nq.gz
    ├── 776645761c7d444e4420fc4182da2afba06f934c.nq.gz
    ├── 7a6099b9441ec97faf903ef53823e38af53691cb.nq.gz
    ├── 7a715407a606e438b2e33eaf4232fd1893e5702f.nq.gz
    ├── 7b1f55f210886cda272b765f7acf800c19c4a4e3.nq.gz
    ├── 7b3a1e493ad99daca71ad8dbb66dbc7341ac7a4d.nq.gz
    ├── 7bff6cd950953fff7eab6eb18dd7d68ed9934bfb.nq.gz
    ├── 7ce424962fbf6df746ad6d97f90d29cf39641767.nq.gz
    ├── 7f5a11ffe698cbe2d94d1e7b3fa790cc11701479.nq.gz
    ├── 80ad36e6356730d4a06ca8964a65fbdcefab831b.nq.gz
    ├── 81e5aec95abf1013185c58e08032bab521db4367.nq.gz
    ├── 8264b61f17478691de3d8cf6178f5324b9128b37.nq.gz
    ├── 83c756435235782b7ff39c160a1ca993bbfaccbd.nq.gz
    ├── 850f67a9108b06abb81c50472e25752199f8e628.nq.gz
    ├── 87b0e18ea86200f895b9654a03b3e29722ce8f1e.nq.gz
    ├── 887b4e7c77d18223f5157c185cf04b0d910c03f1.nq.gz
    ├── 8cd7b3c21ce9303b632b0ce0c1d073994a7b6349.nq.gz
    ├── 8d9e799c3d85fd122477a0faab67c61f59bd387e.nq.gz
    ├── 8dac1edcc1726d7db8585439eecd45749761cf6f.nq.gz
    ├── 90f987a69032ca6fdab01cb5582e6ff316c46f8d.nq.gz
    ├── 92606394b4141447f07274b2a9cce0570fd5a11f.nq.gz
    ├── 927686684ac7a08ec0194ed91e1fb4fcd9c74bd8.nq.gz
    ├── 92c30f2f28745252836ccbc51b5155e312694cdf.nq.gz
    ├── 92fe01669623ce54c10e935696ac8f078508b38d.nq.gz
    ├── 957c046a0df879b876f5043c39ad31da5d832e11.nq.gz
    ├── 98b9521230b82c4afc538bcc32ee7c86af623cd2.nq.gz
    ├── 98cf51b677f606e15a38405b96add59789593960.nq.gz
    ├── 98f5bebb9025e3021d6f3a3ef4548f5852523e53.nq.gz
    ├── 992348ef85a8f11f8b067b31e260abc13bf371fe.nq.gz
    ├── 998f2903f1493ba42cd42a3a194fe1f6e0b0faff.nq.gz
    ├── 9a1d7d10b58c1ce5bd60d8225069805075c1d138.nq.gz
    ├── 9df415989a87e5c220f312cb0c15f623a58581b2.nq.gz
    ├── 9e116df4fe2c27966a2fdee7ae77dc0f34b9213a.nq.gz
    ├── 9f960e6b1bbf20e738ec4cf0aa542184cf125c1f.nq.gz
    ├── 9fa83fd34215cdc898a302fcc70f04ed3e7d4848.nq.gz
    ├── a0050bec072403f2b53a1d8b6ad038ae0ee0fb84.nq.gz
    ├── a06d70397abb8ec43b40d3b80decf0292ce1fea7.nq.gz
    ├── a0ca11abd7315819d1d8204b766bb04b71d02438.nq.gz
    ├── a4111c326fcffc1fb3653fc368c30d558f72e0b2.nq.gz
    ├── a4255f897f46511d51b6443e65753a2f4e1d4878.nq.gz
    ├── a7bea90aa8ab3066512509b1124b7d28be9580f3.nq.gz
    ├── a7caafcde4929edc4531b7ed3bc680d37488147e.nq.gz
    ├── a9b835d1cde922d0deff08faaeea1749cf690ed5.nq.gz
    ├── ac467b6e869bdf7c5557aa012b2150225b9155d0.nq.gz
    ├── ac811b610cf38c85aa2711f4a0afc471efa9c319.nq.gz
    ├── acbac6337b30f285580d0ebf1aa2cae3eb0efe91.nq.gz
    ├── acbe050d2eacb51a4a7d7ad06a8cd091b1a95c84.nq.gz
    ├── acc4e0f9a997d4ac181db08f47a15b67e85db504.nq.gz
    ├── ad195ce17694e3fecc996a2b2f303efc0e1e1ee5.nq.gz
    ├── ad2c64fa97d2fb6d032e1283923b58a305f01b80.nq.gz
    ├── aea0c60d527b73fb9d08262416b92f76ec6cbb15.nq.gz
    ├── b19b13755c138e020f8c74ca9f2369d84b133cdf.nq.gz
    ├── b90b50df9f6cff323e0ed84f4eb6836297e64bc3.nq.gz
    ├── b9497ec7883c9ff4c6397eb066077a6a6a60e8ef.nq.gz
    ├── b98f558cd6993c9aac92d934a04f43cf7cdb6218.nq.gz
    ├── ba6bb81036aeb06a6829cae2f15da4bc127e9eff.nq.gz
    ├── bcaa6613847df279e0e2ee2e20cb7c617395a0cf.nq.gz
    ├── be4d23dd6ab7073c7a82c98e7e66ffd5d4546b7d.nq.gz
    ├── bef3701ec8fb7c886c5255a76e666aa9cb66ab16.nq.gz
    ├── bf6db104a2c4fd4f3dc699e85f2b262c3d31e9a0.nq.gz
    ├── c048eb17a972ed9c36b94476b2d6b3b7b6b7ba2f.nq.gz
    ├── c29e66e3996115e684e5e20cb4e1734041f3ec9a.nq.gz
    ├── c2cd1c560219b8762286f0db88d4fa981e02a008.nq.gz
    ├── c2d11cd9da35bda4472117f645acaea657b17bbc.nq.gz
    ├── c56356cf79de2ac0f910ffa55491a33c7ae37810.nq.gz
    ├── c68a49b071e6a9b776060173a42830a5ffa7b233.nq.gz
    ├── c837850fa34d2cc3f0de6ca8b8498bd8f53fb691.nq.gz
    ├── c8e21ec520d1f09f910e98563a541b2e7ea62ce1.nq.gz
    ├── c8e491806fc392a1b137361280cec9f5bcb7066c.nq.gz
    ├── ca7cec52af2c9a9a9a08e9aa725deb1604f7088b.nq.gz
    ├── cae8407af75bfae8e594f039f41d016929c0649d.nq.gz
    ├── cbdae6956859b833439958f00d478279e9f6e2b8.nq.gz
    ├── cdd09fba7f7c1698f210f3cd9e2bd21385c5e1bd.nq.gz
    ├── ceccedf0b9512f2b16e0909cb3b115522b24671b.nq.gz
    ├── cee34d58666b820b771a6dcd2cc8dc3ef203d41e.nq.gz
    ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
    ├── d281112e64728592ea6cb7c51aea7572b06bf5c8.nq.gz
    ├── d2c725fe50f3f81ed718745621290b2bcf9dff65.nq.gz
    ├── d4dba588ce95c48de73971753045183547ac23a9.nq.gz
    ├── d7a27022835e3806fe20d7a757ce0d5e3c290a5c.nq.gz
    ├── df23e0ae5d382a98d0b7596c7149e30ae0383eb4.nq.gz
    ├── dfbf6910758e6b8b9675bd22fdb8afe723b47e0a.nq.gz
    ├── e02491750e2125c19cc5d8c7e8a5985fba6b73ed.nq.gz
    ├── e19f0afabcf43bc2d231a9dd84b514ec906fed6c.nq.gz
    ├── e2c63e48dba05046bcf489f59b1f5b1c762ae69a.nq.gz
    ├── e5f36c915cd801be9a060ea0329dcd7706edec83.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── ea0728e92b01b4c5f25bcab1f41f8439e05d92e8.nq.gz
    ├── ec7e743d2fab3393e949f89a1a62c0c20f40b450.nq.gz
    ├── ed4daf54e91035d585640547d996ac192dd8141d.nq.gz
    ├── ee8cde009b3dc505d69c5ab7d3b6bc7c20d9098b.nq.gz
    └── f02ee19261dd706c9133c503f4c7a7aae56bef89.nq.gz

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
