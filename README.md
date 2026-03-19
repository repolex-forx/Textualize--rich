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
│   │   └── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
│   ├── lsp
│   │   └── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
│   └── repolex
│       └── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
├── blob
│   ├── 03202f2cd29e25d150b047d8211bc7af5f4e67f7.nq.gz
│   ├── 0459369d190ff2377a8336429fb8cd7e1a08b3fe.nq.gz
│   ├── 05c863a93dd968675df9b4df6b1e047ae315660d.nq.gz
│   ├── 071957507bfc4cdd751dd2abc530f7a17aa97481.nq.gz
│   ├── 0a7d22fa1115873536c654bdcd13e08f859135f5.nq.gz
│   ├── 0bcc67969542b0c6a4597365c40b45fbcb6fcaf6.nq.gz
│   ├── 1477bd64f066992c07350edc2a3e84f8089c7b5e.nq.gz
│   ├── 14fb919ff5120db8314ec12c3354b269913f9512.nq.gz
│   ├── 184c219a9ee32e9d2f9b27054cb3d1fbda549c84.nq.gz
│   ├── 194564e761ddae165b39ef6598877e2e3820af0a.nq.gz
│   ├── 1debad2c4bbdce765480227bc05e8ac9144946f9.nq.gz
│   ├── 26ec6fffecb21e2c81b7cea3064480aa9d694b0d.nq.gz
│   ├── 273b0dbc209d1867b3067d9d3180b7b5578112d3.nq.gz
│   ├── 2903a3cdd73048a80a1f34362886b8879e90ff01.nq.gz
│   ├── 2951d6846f53686517cddfca71cd46c4b8d135aa.nq.gz
│   ├── 2c33d233f3ad7e48a34578d63ce77ebcb75b584e.nq.gz
│   ├── 2c9ac094f650480cd30aeca596fec4eed0d7fc0a.nq.gz
│   ├── 3079aa470d8290d6c75e99eef4aff75c8fde7a23.nq.gz
│   ├── 363eeb34a95910cfaf3dc5e0ef08f169856fd753.nq.gz
│   ├── 37b880d0d40e4181fa7bc1c3d7ad8225721a9563.nq.gz
│   ├── 390100ec8113ee52064e03b5d4331f7269b90336.nq.gz
│   ├── 3962ddc74a52c3d885021830fd87af4701acc1e6.nq.gz
│   ├── 3ae7fa68b48e22113199e4d73b84ebb6bdaf1a31.nq.gz
│   ├── 3d431ac5e9e3bc3bd0ebcaf750f8997990444c3f.nq.gz
│   ├── 40562b07fc2f2ad7a364d27b3aaed650c1b250cc.nq.gz
│   ├── 40d3a04a82d1d05c153698e92b681186dc32dcb5.nq.gz
│   ├── 40e054b908aa3390e5288fd34a14041d8b4c7dd0.nq.gz
│   ├── 43e4e870de8a742f663604325d17280a31f534db.nq.gz
│   ├── 45f5e99d9e886758da4ad879a3ed881cd33fa14e.nq.gz
│   ├── 479fd7f46195ec70a6b23511c6753e7e70ce161e.nq.gz
│   ├── 49f07c9a5ce800a4b155cdfc0c8d091ac832f1b9.nq.gz
│   ├── 4a592c867ac1c97dfbb5f5c040a1086bbb0cc03e.nq.gz
│   ├── 4bd9a371a1c1545c6dd2a25fcff73c07cb5e474b.nq.gz
│   ├── 4e0f3d7dae89bcd08eff7e98d988f1aed4a0c0bb.nq.gz
│   ├── 4f65314220f2831a0b246cf42fde02fab098ba04.nq.gz
│   ├── 51851beedc97779829311c97cd67e9715b8c5658.nq.gz
│   ├── 53a96180582be76dcfdc3c4e06748736db2c18be.nq.gz
│   ├── 5496d4681c7aff523f1a0fc5e89048e16611cbce.nq.gz
│   ├── 566ecd0f3956259be545c9a6dc01047ffb907dcc.nq.gz
│   ├── 56e1f92eaa067d1bc27dee10352b1a7305d53696.nq.gz
│   ├── 589a21cf8d7f1e2df5a401353b8f707cd164f606.nq.gz
│   ├── 5a6dec17511351657b765bdd2ca4d7491474ccfb.nq.gz
│   ├── 5bbb885dbecec1aa246f5b1a0ab597979dce7826.nq.gz
│   ├── 61547eb7757958b93fb6aa68971895ba0c76912b.nq.gz
│   ├── 623f83ca29c943dbf36fc43da061d629110341c6.nq.gz
│   ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
│   ├── 62e782d46f5bcb185821e6f7125e669c3a7332a5.nq.gz
│   ├── 6555bf95b56d69f1f5ce9eb2492f61e6b7decb20.nq.gz
│   ├── 6815e6858adac3483a62b42a851fe766c9d141dd.nq.gz
│   ├── 695c888e83a9b6cd3dd636f10d22b5e90d7bb827.nq.gz
│   ├── 6f750b220ebe8a0176d81a347ef40205b234f61b.nq.gz
│   ├── 74241c489c744237bb1fa88190378e855e7be377.nq.gz
│   ├── 76b41f4bb7808195caa44095e46ec57bbadf1ad0.nq.gz
│   ├── 7a6099b9441ec97faf903ef53823e38af53691cb.nq.gz
│   ├── 7b3a1e493ad99daca71ad8dbb66dbc7341ac7a4d.nq.gz
│   ├── 7bff6cd950953fff7eab6eb18dd7d68ed9934bfb.nq.gz
│   ├── 7f5a11ffe698cbe2d94d1e7b3fa790cc11701479.nq.gz
│   ├── 81e5aec95abf1013185c58e08032bab521db4367.nq.gz
│   ├── 8264b61f17478691de3d8cf6178f5324b9128b37.nq.gz
│   ├── 83c756435235782b7ff39c160a1ca993bbfaccbd.nq.gz
│   ├── 87b0e18ea86200f895b9654a03b3e29722ce8f1e.nq.gz
│   ├── 887b4e7c77d18223f5157c185cf04b0d910c03f1.nq.gz
│   ├── 8d9e799c3d85fd122477a0faab67c61f59bd387e.nq.gz
│   ├── 8dac1edcc1726d7db8585439eecd45749761cf6f.nq.gz
│   ├── 90f987a69032ca6fdab01cb5582e6ff316c46f8d.nq.gz
│   ├── 927686684ac7a08ec0194ed91e1fb4fcd9c74bd8.nq.gz
│   ├── 98f5bebb9025e3021d6f3a3ef4548f5852523e53.nq.gz
│   ├── 992348ef85a8f11f8b067b31e260abc13bf371fe.nq.gz
│   ├── 998f2903f1493ba42cd42a3a194fe1f6e0b0faff.nq.gz
│   ├── 9df415989a87e5c220f312cb0c15f623a58581b2.nq.gz
│   ├── 9e116df4fe2c27966a2fdee7ae77dc0f34b9213a.nq.gz
│   ├── 9f960e6b1bbf20e738ec4cf0aa542184cf125c1f.nq.gz
│   ├── a0050bec072403f2b53a1d8b6ad038ae0ee0fb84.nq.gz
│   ├── a06d70397abb8ec43b40d3b80decf0292ce1fea7.nq.gz
│   ├── a4111c326fcffc1fb3653fc368c30d558f72e0b2.nq.gz
│   ├── a4255f897f46511d51b6443e65753a2f4e1d4878.nq.gz
│   ├── ac467b6e869bdf7c5557aa012b2150225b9155d0.nq.gz
│   ├── ac811b610cf38c85aa2711f4a0afc471efa9c319.nq.gz
│   ├── aea0c60d527b73fb9d08262416b92f76ec6cbb15.nq.gz
│   ├── b98f558cd6993c9aac92d934a04f43cf7cdb6218.nq.gz
│   ├── ba6bb81036aeb06a6829cae2f15da4bc127e9eff.nq.gz
│   ├── bcaa6613847df279e0e2ee2e20cb7c617395a0cf.nq.gz
│   ├── be4d23dd6ab7073c7a82c98e7e66ffd5d4546b7d.nq.gz
│   ├── bf6db104a2c4fd4f3dc699e85f2b262c3d31e9a0.nq.gz
│   ├── c29e66e3996115e684e5e20cb4e1734041f3ec9a.nq.gz
│   ├── c2cd1c560219b8762286f0db88d4fa981e02a008.nq.gz
│   ├── c56356cf79de2ac0f910ffa55491a33c7ae37810.nq.gz
│   ├── c68a49b071e6a9b776060173a42830a5ffa7b233.nq.gz
│   ├── c8e491806fc392a1b137361280cec9f5bcb7066c.nq.gz
│   ├── ca7cec52af2c9a9a9a08e9aa725deb1604f7088b.nq.gz
│   ├── cdd09fba7f7c1698f210f3cd9e2bd21385c5e1bd.nq.gz
│   ├── cee34d58666b820b771a6dcd2cc8dc3ef203d41e.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── df23e0ae5d382a98d0b7596c7149e30ae0383eb4.nq.gz
│   ├── e02491750e2125c19cc5d8c7e8a5985fba6b73ed.nq.gz
│   ├── e19f0afabcf43bc2d231a9dd84b514ec906fed6c.nq.gz
│   ├── e5f36c915cd801be9a060ea0329dcd7706edec83.nq.gz
│   ├── ec7e743d2fab3393e949f89a1a62c0c20f40b450.nq.gz
│   ├── ed4daf54e91035d585640547d996ac192dd8141d.nq.gz
│   ├── f02ee19261dd706c9133c503f4c7a7aae56bef89.nq.gz
│   ├── f06eb3a19d32e3521e1dc003b2dc34ea37fa6ad0.nq.gz
│   ├── f2559d54aa5f3964a21e373dcd1fb1aeb2b9ce72.nq.gz
│   ├── f37deec496403f496cd3c08f6ac0bbd7de0d7cdf.nq.gz
│   ├── f5916bd6f53887c8fbec97e469b06dbcc97ea749.nq.gz
│   ├── f7c8dfc4d533e8c3966faad025cd96aa6eddcc73.nq.gz
│   ├── fa65f4fd9d1c59cbc29adde31502e359af24a595.nq.gz
│   ├── fce383cca44809dfe459945164e1e9543a65263b.nq.gz
│   └── ff5b8d4d3ba61c55a03c687fc8a762e1ae585808.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
└── files
    └── Textualize
        └── rich
            └── aggregate
                ├── ast
                │   ├── 008854c40772f647dfcb873bc3489e8a1c02d598.nq.gz
                │   ├── 11c305e1722a81c553a41fb9358f1058231757c5.nq.gz
                │   ├── 15623c5a57bf758b18542d5293ee319bbd59e829.nq.gz
                │   ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
                │   ├── 1ffbd443774cbc4bf9ddd968aef7c03322f33cf0.nq.gz
                │   ├── 20024635c06c22879fd2fd1e380ec4cccd9935dd.nq.gz
                │   ├── 247431544d407d2496e200124e7b5ed2d9e657c9.nq.gz
                │   ├── 25a1bf06b4854bd8d9239f8ba05678d2c60a62ad.nq.gz
                │   ├── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
                │   ├── 3473658d13a4e88e1e58a7be116ae6975ca13cf6.nq.gz
                │   ├── 36efcb5abe9ea8b6a7707243bec89a81e063c01a.nq.gz
                │   ├── 3827b4ae01aca1b4cb308f4c838da1b91384ad7d.nq.gz
                │   ├── 4bf3f19c04f47c60c4fe96b81afe708a0ad812dc.nq.gz
                │   ├── 5097f44092a4ba4ef7741755b3752d2aebe772a0.nq.gz
                │   ├── 550d391171934874ec85ef7bcad2292d8728c1ce.nq.gz
                │   ├── 573125e9b4eaa4b25bb1a911cf61e365b266afba.nq.gz
                │   ├── 5f55063b139e5fcb70dc75cbebd4195c48f1e9bc.nq.gz
                │   ├── 6261ca23bf838abaa0fa6478dc81ccb18a6949c0.nq.gz
                │   ├── 6b088eaf323cadf6b3caca5a1c584b611fae4668.nq.gz
                │   ├── 6d7ba589e2e37e91f12d0a0d4e4a6ae0c9e144a5.nq.gz
                │   ├── 7441bf27f3a023c9d3cd57229e4e5e06ec1b8e9f.nq.gz
                │   ├── 748dea614fa03ac8d3b1d66d14a2acc8c8ec223f.nq.gz
                │   ├── 7d00fa83f262ae3bd6fa6c27661e0894675900fc.nq.gz
                │   ├── 7e4a2db4afa29a59ff90d265ad115a225038a5d0.nq.gz
                │   ├── 84d9a1d8792ee76dcf8497f12fa69ee094aac282.nq.gz
                │   ├── 88b07b3ebc64356e6036bb8a2f33b006af64f7a7.nq.gz
                │   ├── 8a7f5d82ba7bbe108a17bdc75720d11852968aed.nq.gz
                │   ├── 8b185610d336693f2ff08c30157682ba7382d9ee.nq.gz
                │   ├── 932e26b6508ccc10469a091f5e629dee8f2c124b.nq.gz
                │   ├── 949e1f72fb9f2f90abb18cbdef47609a24febdb7.nq.gz
                │   ├── 966ebdaae590cad7ecde0630923e186430960e10.nq.gz
                │   ├── 96ea5feddfa8130ca8e961ab772dfdbb836cb3fa.nq.gz
                │   ├── 9a4fbf83c5051eaf94a88996292c438c895306d5.nq.gz
                │   ├── 9abc0292c1f96433e4f87b10d5dea0d617b0ab23.nq.gz
                │   ├── 9f2a426ea7b27e9ef41bb08bff7b0481d4755aa6.nq.gz
                │   ├── a27a3ee20bff6c6aa0642f31fb736e72d16abbce.nq.gz
                │   ├── a81230bcff8e66a6e16522a0ab9186416d615f09.nq.gz
                │   ├── aaea99f764bcd48a12fd09e5b53efd2bafd9281d.nq.gz
                │   ├── ac1a33da175972f895e894121df609d0cb1448fe.nq.gz
                │   ├── b391635ee4a325fb96ed531b00e4b55f66909639.nq.gz
                │   ├── c24ab497ead3a30758ac1208ce76b925057138ac.nq.gz
                │   ├── c3d0e3584202d66703d2bcf2aaf3e7740bef6e2d.nq.gz
                │   ├── cefafdc12e0220d139c704522979a0dc9b3f889b.nq.gz
                │   ├── cf606f0a3cab3dbe8f9fdaa2ccc4882c594ce2af.nq.gz
                │   ├── d9d59c6eda6d21f4515e9a8fe9496fa5e68f9500.nq.gz
                │   ├── e0a1fd3052a54144f54a20eb97bfc3f397658675.nq.gz
                │   ├── e338ab145797e57a5db73f37b3883a30592f0643.nq.gz
                │   ├── e34eadb3a9354c2469fa2112400ce2690f2663ba.nq.gz
                │   ├── e7849495bba31d9320e17c23f24d50f6e3447486.nq.gz
                │   ├── e9e72000c50f56654c89e119ff882e322e51ecf3.nq.gz
                │   ├── ecf3d7f1ca2b2a5ea9c36ce2b23ae576e0421b6c.nq.gz
                │   └── f2af8c9d54e9ebc14b32fe68ddaefd01b7e5a801.nq.gz
                └── dataflow
                    ├── 008854c40772f647dfcb873bc3489e8a1c02d598.nq.gz
                    ├── 11c305e1722a81c553a41fb9358f1058231757c5.nq.gz
                    ├── 15623c5a57bf758b18542d5293ee319bbd59e829.nq.gz
                    ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
                    ├── 1ffbd443774cbc4bf9ddd968aef7c03322f33cf0.nq.gz
                    ├── 20024635c06c22879fd2fd1e380ec4cccd9935dd.nq.gz
                    ├── 247431544d407d2496e200124e7b5ed2d9e657c9.nq.gz
                    ├── 25a1bf06b4854bd8d9239f8ba05678d2c60a62ad.nq.gz
                    ├── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
                    ├── 3473658d13a4e88e1e58a7be116ae6975ca13cf6.nq.gz
                    ├── 36efcb5abe9ea8b6a7707243bec89a81e063c01a.nq.gz
                    ├── 3827b4ae01aca1b4cb308f4c838da1b91384ad7d.nq.gz
                    ├── 4bf3f19c04f47c60c4fe96b81afe708a0ad812dc.nq.gz
                    ├── 5097f44092a4ba4ef7741755b3752d2aebe772a0.nq.gz
                    ├── 550d391171934874ec85ef7bcad2292d8728c1ce.nq.gz
                    ├── 573125e9b4eaa4b25bb1a911cf61e365b266afba.nq.gz
                    ├── 5f55063b139e5fcb70dc75cbebd4195c48f1e9bc.nq.gz
                    ├── 6261ca23bf838abaa0fa6478dc81ccb18a6949c0.nq.gz
                    ├── 6b088eaf323cadf6b3caca5a1c584b611fae4668.nq.gz
                    ├── 6d7ba589e2e37e91f12d0a0d4e4a6ae0c9e144a5.nq.gz
                    ├── 7441bf27f3a023c9d3cd57229e4e5e06ec1b8e9f.nq.gz
                    ├── 748dea614fa03ac8d3b1d66d14a2acc8c8ec223f.nq.gz
                    ├── 7d00fa83f262ae3bd6fa6c27661e0894675900fc.nq.gz
                    ├── 7e4a2db4afa29a59ff90d265ad115a225038a5d0.nq.gz
                    ├── 84d9a1d8792ee76dcf8497f12fa69ee094aac282.nq.gz
                    ├── 88b07b3ebc64356e6036bb8a2f33b006af64f7a7.nq.gz
                    ├── 8a7f5d82ba7bbe108a17bdc75720d11852968aed.nq.gz
                    ├── 8b185610d336693f2ff08c30157682ba7382d9ee.nq.gz
                    ├── 932e26b6508ccc10469a091f5e629dee8f2c124b.nq.gz
                    ├── 949e1f72fb9f2f90abb18cbdef47609a24febdb7.nq.gz
                    ├── 966ebdaae590cad7ecde0630923e186430960e10.nq.gz
                    ├── 96ea5feddfa8130ca8e961ab772dfdbb836cb3fa.nq.gz
                    ├── 9a4fbf83c5051eaf94a88996292c438c895306d5.nq.gz
                    └── 9abc0292c1f96433e4f87b10d5dea0d617b0ab23.nq.gz

15 directories, 200 files
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
*Parsed on 2026-03-19 by [repolex](https://repolex.ai)*
