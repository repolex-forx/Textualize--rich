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
│   │   ├── 1ffbd443774cbc4bf9ddd968aef7c03322f33cf0.nq.gz
│   │   ├── 25a1bf06b4854bd8d9239f8ba05678d2c60a62ad.nq.gz
│   │   ├── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
│   │   ├── 5097f44092a4ba4ef7741755b3752d2aebe772a0.nq.gz
│   │   ├── 5f55063b139e5fcb70dc75cbebd4195c48f1e9bc.nq.gz
│   │   ├── 6261ca23bf838abaa0fa6478dc81ccb18a6949c0.nq.gz
│   │   ├── 6b088eaf323cadf6b3caca5a1c584b611fae4668.nq.gz
│   │   ├── 6d7ba589e2e37e91f12d0a0d4e4a6ae0c9e144a5.nq.gz
│   │   ├── 7e4a2db4afa29a59ff90d265ad115a225038a5d0.nq.gz
│   │   ├── 84d9a1d8792ee76dcf8497f12fa69ee094aac282.nq.gz
│   │   ├── 8b185610d336693f2ff08c30157682ba7382d9ee.nq.gz
│   │   ├── 932e26b6508ccc10469a091f5e629dee8f2c124b.nq.gz
│   │   ├── 966ebdaae590cad7ecde0630923e186430960e10.nq.gz
│   │   ├── 96ea5feddfa8130ca8e961ab772dfdbb836cb3fa.nq.gz
│   │   ├── 9a4fbf83c5051eaf94a88996292c438c895306d5.nq.gz
│   │   ├── 9abc0292c1f96433e4f87b10d5dea0d617b0ab23.nq.gz
│   │   ├── a27a3ee20bff6c6aa0642f31fb736e72d16abbce.nq.gz
│   │   ├── b391635ee4a325fb96ed531b00e4b55f66909639.nq.gz
│   │   ├── c24ab497ead3a30758ac1208ce76b925057138ac.nq.gz
│   │   ├── cefafdc12e0220d139c704522979a0dc9b3f889b.nq.gz
│   │   ├── e0a1fd3052a54144f54a20eb97bfc3f397658675.nq.gz
│   │   ├── e338ab145797e57a5db73f37b3883a30592f0643.nq.gz
│   │   ├── e7849495bba31d9320e17c23f24d50f6e3447486.nq.gz
│   │   ├── e9e72000c50f56654c89e119ff882e322e51ecf3.nq.gz
│   │   └── f2af8c9d54e9ebc14b32fe68ddaefd01b7e5a801.nq.gz
│   ├── lsp
│   │   ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
│   │   ├── 1ffbd443774cbc4bf9ddd968aef7c03322f33cf0.nq.gz
│   │   ├── 25a1bf06b4854bd8d9239f8ba05678d2c60a62ad.nq.gz
│   │   ├── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
│   │   ├── 5097f44092a4ba4ef7741755b3752d2aebe772a0.nq.gz
│   │   ├── 5f55063b139e5fcb70dc75cbebd4195c48f1e9bc.nq.gz
│   │   ├── 6261ca23bf838abaa0fa6478dc81ccb18a6949c0.nq.gz
│   │   ├── 6b088eaf323cadf6b3caca5a1c584b611fae4668.nq.gz
│   │   ├── 6d7ba589e2e37e91f12d0a0d4e4a6ae0c9e144a5.nq.gz
│   │   ├── 7e4a2db4afa29a59ff90d265ad115a225038a5d0.nq.gz
│   │   ├── 84d9a1d8792ee76dcf8497f12fa69ee094aac282.nq.gz
│   │   ├── 8b185610d336693f2ff08c30157682ba7382d9ee.nq.gz
│   │   ├── 932e26b6508ccc10469a091f5e629dee8f2c124b.nq.gz
│   │   ├── 966ebdaae590cad7ecde0630923e186430960e10.nq.gz
│   │   ├── 96ea5feddfa8130ca8e961ab772dfdbb836cb3fa.nq.gz
│   │   ├── 9a4fbf83c5051eaf94a88996292c438c895306d5.nq.gz
│   │   ├── 9abc0292c1f96433e4f87b10d5dea0d617b0ab23.nq.gz
│   │   ├── a27a3ee20bff6c6aa0642f31fb736e72d16abbce.nq.gz
│   │   ├── b391635ee4a325fb96ed531b00e4b55f66909639.nq.gz
│   │   ├── c24ab497ead3a30758ac1208ce76b925057138ac.nq.gz
│   │   ├── cefafdc12e0220d139c704522979a0dc9b3f889b.nq.gz
│   │   ├── e0a1fd3052a54144f54a20eb97bfc3f397658675.nq.gz
│   │   ├── e338ab145797e57a5db73f37b3883a30592f0643.nq.gz
│   │   ├── e7849495bba31d9320e17c23f24d50f6e3447486.nq.gz
│   │   ├── e9e72000c50f56654c89e119ff882e322e51ecf3.nq.gz
│   │   └── f2af8c9d54e9ebc14b32fe68ddaefd01b7e5a801.nq.gz
│   └── repolex
│       ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
│       ├── 1ffbd443774cbc4bf9ddd968aef7c03322f33cf0.nq.gz
│       ├── 25a1bf06b4854bd8d9239f8ba05678d2c60a62ad.nq.gz
│       ├── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
│       ├── 5097f44092a4ba4ef7741755b3752d2aebe772a0.nq.gz
│       ├── 5f55063b139e5fcb70dc75cbebd4195c48f1e9bc.nq.gz
│       ├── 6261ca23bf838abaa0fa6478dc81ccb18a6949c0.nq.gz
│       ├── 6b088eaf323cadf6b3caca5a1c584b611fae4668.nq.gz
│       ├── 6d7ba589e2e37e91f12d0a0d4e4a6ae0c9e144a5.nq.gz
│       ├── 7e4a2db4afa29a59ff90d265ad115a225038a5d0.nq.gz
│       ├── 84d9a1d8792ee76dcf8497f12fa69ee094aac282.nq.gz
│       ├── 8b185610d336693f2ff08c30157682ba7382d9ee.nq.gz
│       ├── 932e26b6508ccc10469a091f5e629dee8f2c124b.nq.gz
│       ├── 966ebdaae590cad7ecde0630923e186430960e10.nq.gz
│       ├── 96ea5feddfa8130ca8e961ab772dfdbb836cb3fa.nq.gz
│       ├── 9a4fbf83c5051eaf94a88996292c438c895306d5.nq.gz
│       ├── 9abc0292c1f96433e4f87b10d5dea0d617b0ab23.nq.gz
│       ├── a27a3ee20bff6c6aa0642f31fb736e72d16abbce.nq.gz
│       ├── b391635ee4a325fb96ed531b00e4b55f66909639.nq.gz
│       ├── c24ab497ead3a30758ac1208ce76b925057138ac.nq.gz
│       ├── cefafdc12e0220d139c704522979a0dc9b3f889b.nq.gz
│       ├── e0a1fd3052a54144f54a20eb97bfc3f397658675.nq.gz
│       ├── e338ab145797e57a5db73f37b3883a30592f0643.nq.gz
│       ├── e7849495bba31d9320e17c23f24d50f6e3447486.nq.gz
│       ├── e9e72000c50f56654c89e119ff882e322e51ecf3.nq.gz
│       └── f2af8c9d54e9ebc14b32fe68ddaefd01b7e5a801.nq.gz
└── blob
    ├── 00336c3e11762c13d7a58614c15032e0b82e5192.nq.gz
    ├── 007f82a4a06c883854c2f648c64c0c74112ed7b1.nq.gz
    ├── 00a6277906594d76a791aa9a972c3996f5ba92eb.nq.gz
    ├── 00eadcc930dc6aa0fe9a6a29c0f4ac1e8bb3be12.nq.gz
    ├── 01033c248f8bd62ac42c74ad6046cf64dbfa9087.nq.gz
    ├── 010ce3743566bc750c5e043199b0fa053fbe9e3e.nq.gz
    ├── 01c6cafbe53f1fcb12f7b382b2b35e2fd2c69933.nq.gz
    ├── 02123317d53b65d8e521f972eca6b3cdace7236f.nq.gz
    ├── 03202f2cd29e25d150b047d8211bc7af5f4e67f7.nq.gz
    ├── 036bcde0b1f318b3d22194ab1cca01cc4bcf9c3b.nq.gz
    ├── 0459369d190ff2377a8336429fb8cd7e1a08b3fe.nq.gz
    ├── 046323eca755593e5e187ae235e63888a1023f82.nq.gz
    ├── 04fbd713296a1643410aa2f422806f85ca64d93a.nq.gz
    ├── 05c863a93dd968675df9b4df6b1e047ae315660d.nq.gz
    ├── 06ab11ef5e38e46079824158d4e29eb9d6806f22.nq.gz
    ├── 06b12d7b0ca1ab64f59bbaf42df9e3626ed42bdb.nq.gz
    ├── 06ca5320940dad4ea1ca45d5969fa4a9a94e10f6.nq.gz
    ├── 06de437202fa2615567bff20cddc369a073c3aa5.nq.gz
    ├── 06f813743edb0405a3810a24d7f5533d0dd0842f.nq.gz
    ├── 071957507bfc4cdd751dd2abc530f7a17aa97481.nq.gz
    ├── 074276b631405f9c5ae5a75acf0bcdaeaf966a6d.nq.gz
    ├── 074c024832bac7d86637eadf9e5da9a8ea9b5369.nq.gz
    ├── 076cb6669612f46d2a9d6ce2c64ee3b65a52cf23.nq.gz
    ├── 077508fad535e832f5c6d969519d61aa61fff633.nq.gz
    ├── 0790b1dadb847039d34a47344756ed3514f9e01b.nq.gz
    ├── 07b7ce3dada01d26190d8ebfd75261e6b54983e5.nq.gz
    ├── 07b97291c7cb69feeb6d788de241b17f5a39aa03.nq.gz
    ├── 07d526c50e1d532a99c45bd18399c0cb356fcbf7.nq.gz
    ├── 082d881741a10b0ce11d96970cda7042f4cec15e.nq.gz
    ├── 086f24f23202501ebf3ab3b76d858af709970350.nq.gz
    ├── 087740d5991f8c06b4bc0247f3b1cdd1b1a59057.nq.gz
    ├── 08810f2b89ef54918ea3731842b6c78217c85328.nq.gz
    ├── 08c6eba328a805fadf7e74db17dff4023c5ca7c4.nq.gz
    ├── 08ff1000337ef141ac893da86b846a5dc3242b9a.nq.gz
    ├── 09358cdaa2f7a93e7354551a10ac4010cfeb3470.nq.gz
    ├── 09cf74aabbee36c38f326721aaf518da7826cfd6.nq.gz
    ├── 09f101115aaa8adda73bc57c64621f6578c259f1.nq.gz
    ├── 0a085c785df4b5889a0c678e5679e982b6af7931.nq.gz
    ├── 0a7d22fa1115873536c654bdcd13e08f859135f5.nq.gz
    ├── 0ae74bdde6a04295e9c0fbd17ef7edf5b5423d08.nq.gz
    ├── 0b46db1708291cc51eba57a3d43b356b85e43ce8.nq.gz
    ├── 0b7aaa575997b962a04d3c174cf03e51c0e6dbf0.nq.gz
    ├── 0b8f22dd777f0dbcb3fecd03bb0cd86ba0c25dd9.nq.gz
    ├── 0b98b4d678e5a7bf9f0f42bc5006e1fea7dc2cf7.nq.gz
    ├── 0bcc67969542b0c6a4597365c40b45fbcb6fcaf6.nq.gz
    ├── 0bfb804c2e2be5e153ecdb1e40c6b5d49c1f63a1.nq.gz
    ├── 0c370d5fb89926055a955037bc248bf4a723a5b9.nq.gz
    ├── 0c548fc309b901f03fa79a2ebf7141b86ff3c95f.nq.gz
    ├── 0c85af0406cf1fec285541bda7e07afa5af1d1cc.nq.gz
    ├── 0cdc2f4016e84a00e600c4075f547dab4c926653.nq.gz
    ├── 0d2d2f25892504d90ea348c6d38792be4177b402.nq.gz
    ├── 0d2ddfa2bf7afcd48f4d62d64d096715cf63c62c.nq.gz
    ├── 0d78ca9f888f24bc2ec2043a7f370eaad4ec9dd7.nq.gz
    ├── 0d826bdaaa865d77f057fdcb0e03d6eb5738ab23.nq.gz
    ├── 0dfb0c09db6d86743906e3303bc5588a6a1951bc.nq.gz
    ├── 0e08511640eccb930eb0095cc1f48e5f644e8261.nq.gz
    ├── 0e2a2c5c38491a24635076389058aacdb7b6d9c9.nq.gz
    ├── 0e4c7f1d0869c332dd57c99ff4d1853f8fa49263.nq.gz
    ├── 0e551e9559e64f7f20f8c6da9bc9e5c0d6697879.nq.gz
    ├── 0e578b2026a2320a46360827e843cd666bd85b9b.nq.gz
    ├── 0eb5487d1e6ffc2b27357801e4fc2f4fe43ff61c.nq.gz
    ├── 0ec1110c1af33d883fd891055a97eeccc9b6b44e.nq.gz
    ├── 0edd22748d20119cf3d4139b6197675023a7bad0.nq.gz
    ├── 10034564ec7340d02c88eb52da038f3cddf27f40.nq.gz
    ├── 1067417f252b12a002146fe1c3e5191e54c953ee.nq.gz
    ├── 108e8b067cda6acfb2c718b30013673ae09cf119.nq.gz
    ├── 10ad3181095577404751ea2e37496bcbbc37c058.nq.gz
    ├── 1108383708f84cf059239233408c7f534fb436ae.nq.gz
    ├── 112b7ba7c314939eef0dfe497655a6bda53a3753.nq.gz
    ├── 1144ebb49f70873a2cc2338b4434d392a3c8b855.nq.gz
    ├── 11c9ba1d3ffa30097042f1c07135e8f9db979a5e.nq.gz
    ├── 1227733124436deaeb329218581d54ee72624502.nq.gz
    ├── 12278698cccfee5201c528b2d4a8314ee3fae3e8.nq.gz
    ├── 132f4a2327604f06a707469b28d1dfba191c1683.nq.gz
    ├── 137f361aea96a7042fc17e7901aae09f5149f2d3.nq.gz
    ├── 13a3fcb94154e80756a862678be523174ab68011.nq.gz
    ├── 13be0704fcee3e1510570f636ba45ebe09a7565b.nq.gz
    ├── 1477bd64f066992c07350edc2a3e84f8089c7b5e.nq.gz
    ├── 1494c1ef3af5450c01ec59f3a4e577db8a702c37.nq.gz
    ├── 14bcd02481f899753747e03855abf1e33ec1fa09.nq.gz
    ├── 14bf011c9bdf3f67bf3e39b860b8d6c35831eec7.nq.gz
    ├── 14fb919ff5120db8314ec12c3354b269913f9512.nq.gz
    ├── 156793a2e7682c854d125d3ea8f0ef7893f107db.nq.gz
    ├── 15ae06f6439a4c268143c9f3d18c4db366243b69.nq.gz
    ├── 15fad3dac387a0425705c8e36d11437ca5c6a3b5.nq.gz
    ├── 163cb5a82566e1293ed3981b9afac9641d37d50a.nq.gz
    ├── 169b1cf53f91ba41739de405c41a16abd6a83bf9.nq.gz
    ├── 16d042242f0e4769e6103f589a19d4ce1d533f5c.nq.gz
    ├── 16df34e1d55915d2ec44e7839f6910b27585a3db.nq.gz
    ├── 170f94b34d7a39230b6f5bed23de8e2e2083f33f.nq.gz
    ├── 1777d70eea73e30ab4aed3b248b1fd1c0e05a55c.nq.gz
    ├── 17851d4a6b14a911d676f206642eae1bc921b4ce.nq.gz
    ├── 17c24ceb50aecbd49143f8616906b45c3f40b0a7.nq.gz
    ├── 184c219a9ee32e9d2f9b27054cb3d1fbda549c84.nq.gz
    ├── 187059614799f9df9790c1afc78f252775b5c41c.nq.gz
    ├── 18b7c2c27659e9c7799e1fd31e41d92108dd7747.nq.gz
    ├── 1906514df1cb736ee4fefa433e04a9608daceefe.nq.gz
    ├── 1934e8421b6be2170b6d313b9a8a0fd4660bd379.nq.gz
    ├── 193739c6c93b411cd10c417a200cc32c5b855bbd.nq.gz
    ├── 194564e761ddae165b39ef6598877e2e3820af0a.nq.gz
    ├── 1948e8332c8110503d0b494206a644abedec0630.nq.gz
    ├── 1988a2a5a9b50b86c306d30eae1848dc53ca33e1.nq.gz
    ├── 19b59828407e923d12e889da507eee9fc647e12b.nq.gz
    ├── 19b8d7433bd7ec18215da18dfdfc9de54d775e7f.nq.gz
    ├── 1a0ebccec411e4f2cb867661874b5097f57407b8.nq.gz
    ├── 1a5c5c19814d6e40c51ab3c52dc5df74c296128a.nq.gz
    ├── 1af0d95c32152672dc4583296207907eb6534083.nq.gz
    ├── 1b99266d24ecc20be6d822bb662f080cef5613e3.nq.gz
    ├── 1cac7b91b293eeef62055c1973170e922edee105.nq.gz
    ├── 1d1c6c1608a5b67046cb872f8a907903b590c691.nq.gz
    ├── 1d6300e76805c201fad879b18545af962a995b83.nq.gz
    ├── 1debad2c4bbdce765480227bc05e8ac9144946f9.nq.gz
    ├── 1dfb7e75a80a77799e0b96848f842e3f9cebf2e4.nq.gz
    ├── 1e0f1553fedce76c1058aa3ecd05fe3c96efb918.nq.gz
    ├── 1e40a254f781f8df6defc45fc4fec27aa213d65d.nq.gz
    ├── 1e62277697235737fb7236e96b9c4c5c7ee3e332.nq.gz
    ├── 1e87af5acaffbb42fcec4c499a943ed4d5036700.nq.gz
    ├── 1eeb31d06c18047cc4e05b2c3f10cda08ab140dc.nq.gz
    ├── 1f02e9f47d5b18e2a71b4f2029ead7acb78f92a6.nq.gz
    ├── 1f2877bb2bd520253502b1c05bb811bb0d7ef64c.nq.gz
    ├── 1f517ad8ea8ecea938dfa253dece0d9e18945215.nq.gz
    └── 1f682472395439a82e737cae8accf30c18188f72.nq.gz

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
*Parsed on 2026-03-23 by [repolex](https://repolex.ai)*
