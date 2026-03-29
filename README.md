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
│   │   ├── 008854c40772f647dfcb873bc3489e8a1c02d598.nq.gz
│   │   ├── 11c305e1722a81c553a41fb9358f1058231757c5.nq.gz
│   │   ├── 15623c5a57bf758b18542d5293ee319bbd59e829.nq.gz
│   │   ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
│   │   ├── 1ffbd443774cbc4bf9ddd968aef7c03322f33cf0.nq.gz
│   │   ├── 20024635c06c22879fd2fd1e380ec4cccd9935dd.nq.gz
│   │   ├── 23aa71774457c34fe6d1fb527c1c2972447bb18d.nq.gz
│   │   ├── 247431544d407d2496e200124e7b5ed2d9e657c9.nq.gz
│   │   ├── 25a1bf06b4854bd8d9239f8ba05678d2c60a62ad.nq.gz
│   │   ├── 2ea7e586792a95e33cddc74f9e89e62bcd8d7f2b.nq.gz
│   │   ├── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
│   │   ├── 36efcb5abe9ea8b6a7707243bec89a81e063c01a.nq.gz
│   │   ├── 43d4c4e50c0334f93240aa907183bb24b8e69fe9.nq.gz
│   │   ├── 4bf3f19c04f47c60c4fe96b81afe708a0ad812dc.nq.gz
│   │   ├── 5097f44092a4ba4ef7741755b3752d2aebe772a0.nq.gz
│   │   ├── 52d159aae04d12ba24ecdc3d8104e6b8068cbf5f.nq.gz
│   │   ├── 550d391171934874ec85ef7bcad2292d8728c1ce.nq.gz
│   │   ├── 573125e9b4eaa4b25bb1a911cf61e365b266afba.nq.gz
│   │   ├── 5f55063b139e5fcb70dc75cbebd4195c48f1e9bc.nq.gz
│   │   ├── 6261ca23bf838abaa0fa6478dc81ccb18a6949c0.nq.gz
│   │   ├── 6b088eaf323cadf6b3caca5a1c584b611fae4668.nq.gz
│   │   ├── 6d7ba589e2e37e91f12d0a0d4e4a6ae0c9e144a5.nq.gz
│   │   ├── 7441bf27f3a023c9d3cd57229e4e5e06ec1b8e9f.nq.gz
│   │   ├── 7e4a2db4afa29a59ff90d265ad115a225038a5d0.nq.gz
│   │   ├── 84d9a1d8792ee76dcf8497f12fa69ee094aac282.nq.gz
│   │   ├── 88b07b3ebc64356e6036bb8a2f33b006af64f7a7.nq.gz
│   │   ├── 8a7f5d82ba7bbe108a17bdc75720d11852968aed.nq.gz
│   │   ├── 8b185610d336693f2ff08c30157682ba7382d9ee.nq.gz
│   │   ├── 932e26b6508ccc10469a091f5e629dee8f2c124b.nq.gz
│   │   ├── 966ebdaae590cad7ecde0630923e186430960e10.nq.gz
│   │   ├── 96ea5feddfa8130ca8e961ab772dfdbb836cb3fa.nq.gz
│   │   ├── 9a4fbf83c5051eaf94a88996292c438c895306d5.nq.gz
│   │   ├── 9abc0292c1f96433e4f87b10d5dea0d617b0ab23.nq.gz
│   │   ├── 9f2a426ea7b27e9ef41bb08bff7b0481d4755aa6.nq.gz
│   │   ├── a27a3ee20bff6c6aa0642f31fb736e72d16abbce.nq.gz
│   │   ├── a81230bcff8e66a6e16522a0ab9186416d615f09.nq.gz
│   │   ├── aaea99f764bcd48a12fd09e5b53efd2bafd9281d.nq.gz
│   │   ├── ac1a33da175972f895e894121df609d0cb1448fe.nq.gz
│   │   ├── b391635ee4a325fb96ed531b00e4b55f66909639.nq.gz
│   │   ├── c24ab497ead3a30758ac1208ce76b925057138ac.nq.gz
│   │   ├── c9afafdd680831a43956906d56c78d9933aaf232.nq.gz
│   │   ├── cefafdc12e0220d139c704522979a0dc9b3f889b.nq.gz
│   │   ├── cf606f0a3cab3dbe8f9fdaa2ccc4882c594ce2af.nq.gz
│   │   ├── e0a1fd3052a54144f54a20eb97bfc3f397658675.nq.gz
│   │   ├── e338ab145797e57a5db73f37b3883a30592f0643.nq.gz
│   │   ├── e34eadb3a9354c2469fa2112400ce2690f2663ba.nq.gz
│   │   ├── e7849495bba31d9320e17c23f24d50f6e3447486.nq.gz
│   │   ├── e9e72000c50f56654c89e119ff882e322e51ecf3.nq.gz
│   │   ├── ecf3d7f1ca2b2a5ea9c36ce2b23ae576e0421b6c.nq.gz
│   │   └── f2af8c9d54e9ebc14b32fe68ddaefd01b7e5a801.nq.gz
│   ├── lsp
│   │   ├── 008854c40772f647dfcb873bc3489e8a1c02d598.nq.gz
│   │   ├── 11c305e1722a81c553a41fb9358f1058231757c5.nq.gz
│   │   ├── 15623c5a57bf758b18542d5293ee319bbd59e829.nq.gz
│   │   ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
│   │   ├── 1ffbd443774cbc4bf9ddd968aef7c03322f33cf0.nq.gz
│   │   ├── 20024635c06c22879fd2fd1e380ec4cccd9935dd.nq.gz
│   │   ├── 23aa71774457c34fe6d1fb527c1c2972447bb18d.nq.gz
│   │   ├── 247431544d407d2496e200124e7b5ed2d9e657c9.nq.gz
│   │   ├── 25a1bf06b4854bd8d9239f8ba05678d2c60a62ad.nq.gz
│   │   ├── 2ea7e586792a95e33cddc74f9e89e62bcd8d7f2b.nq.gz
│   │   ├── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
│   │   ├── 36efcb5abe9ea8b6a7707243bec89a81e063c01a.nq.gz
│   │   ├── 43d4c4e50c0334f93240aa907183bb24b8e69fe9.nq.gz
│   │   ├── 4bf3f19c04f47c60c4fe96b81afe708a0ad812dc.nq.gz
│   │   ├── 5097f44092a4ba4ef7741755b3752d2aebe772a0.nq.gz
│   │   ├── 52d159aae04d12ba24ecdc3d8104e6b8068cbf5f.nq.gz
│   │   ├── 550d391171934874ec85ef7bcad2292d8728c1ce.nq.gz
│   │   ├── 573125e9b4eaa4b25bb1a911cf61e365b266afba.nq.gz
│   │   ├── 5f55063b139e5fcb70dc75cbebd4195c48f1e9bc.nq.gz
│   │   ├── 6261ca23bf838abaa0fa6478dc81ccb18a6949c0.nq.gz
│   │   ├── 6b088eaf323cadf6b3caca5a1c584b611fae4668.nq.gz
│   │   ├── 6d7ba589e2e37e91f12d0a0d4e4a6ae0c9e144a5.nq.gz
│   │   ├── 7441bf27f3a023c9d3cd57229e4e5e06ec1b8e9f.nq.gz
│   │   ├── 7e4a2db4afa29a59ff90d265ad115a225038a5d0.nq.gz
│   │   ├── 84d9a1d8792ee76dcf8497f12fa69ee094aac282.nq.gz
│   │   ├── 88b07b3ebc64356e6036bb8a2f33b006af64f7a7.nq.gz
│   │   ├── 8a7f5d82ba7bbe108a17bdc75720d11852968aed.nq.gz
│   │   ├── 8b185610d336693f2ff08c30157682ba7382d9ee.nq.gz
│   │   ├── 932e26b6508ccc10469a091f5e629dee8f2c124b.nq.gz
│   │   ├── 966ebdaae590cad7ecde0630923e186430960e10.nq.gz
│   │   ├── 96ea5feddfa8130ca8e961ab772dfdbb836cb3fa.nq.gz
│   │   ├── 9a4fbf83c5051eaf94a88996292c438c895306d5.nq.gz
│   │   ├── 9abc0292c1f96433e4f87b10d5dea0d617b0ab23.nq.gz
│   │   ├── 9f2a426ea7b27e9ef41bb08bff7b0481d4755aa6.nq.gz
│   │   ├── a27a3ee20bff6c6aa0642f31fb736e72d16abbce.nq.gz
│   │   ├── a81230bcff8e66a6e16522a0ab9186416d615f09.nq.gz
│   │   ├── aaea99f764bcd48a12fd09e5b53efd2bafd9281d.nq.gz
│   │   ├── ac1a33da175972f895e894121df609d0cb1448fe.nq.gz
│   │   ├── b391635ee4a325fb96ed531b00e4b55f66909639.nq.gz
│   │   ├── c24ab497ead3a30758ac1208ce76b925057138ac.nq.gz
│   │   ├── c9afafdd680831a43956906d56c78d9933aaf232.nq.gz
│   │   ├── cefafdc12e0220d139c704522979a0dc9b3f889b.nq.gz
│   │   ├── cf606f0a3cab3dbe8f9fdaa2ccc4882c594ce2af.nq.gz
│   │   ├── e0a1fd3052a54144f54a20eb97bfc3f397658675.nq.gz
│   │   ├── e338ab145797e57a5db73f37b3883a30592f0643.nq.gz
│   │   ├── e34eadb3a9354c2469fa2112400ce2690f2663ba.nq.gz
│   │   ├── e7849495bba31d9320e17c23f24d50f6e3447486.nq.gz
│   │   ├── e9e72000c50f56654c89e119ff882e322e51ecf3.nq.gz
│   │   ├── ecf3d7f1ca2b2a5ea9c36ce2b23ae576e0421b6c.nq.gz
│   │   └── f2af8c9d54e9ebc14b32fe68ddaefd01b7e5a801.nq.gz
│   └── repolex
│       ├── 008854c40772f647dfcb873bc3489e8a1c02d598.nq.gz
│       ├── 11c305e1722a81c553a41fb9358f1058231757c5.nq.gz
│       ├── 15623c5a57bf758b18542d5293ee319bbd59e829.nq.gz
│       ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
│       ├── 1ffbd443774cbc4bf9ddd968aef7c03322f33cf0.nq.gz
│       ├── 20024635c06c22879fd2fd1e380ec4cccd9935dd.nq.gz
│       ├── 23aa71774457c34fe6d1fb527c1c2972447bb18d.nq.gz
│       ├── 247431544d407d2496e200124e7b5ed2d9e657c9.nq.gz
│       ├── 25a1bf06b4854bd8d9239f8ba05678d2c60a62ad.nq.gz
│       ├── 2ea7e586792a95e33cddc74f9e89e62bcd8d7f2b.nq.gz
│       ├── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
│       ├── 36efcb5abe9ea8b6a7707243bec89a81e063c01a.nq.gz
│       ├── 43d4c4e50c0334f93240aa907183bb24b8e69fe9.nq.gz
│       ├── 4bf3f19c04f47c60c4fe96b81afe708a0ad812dc.nq.gz
│       ├── 5097f44092a4ba4ef7741755b3752d2aebe772a0.nq.gz
│       ├── 52d159aae04d12ba24ecdc3d8104e6b8068cbf5f.nq.gz
│       ├── 550d391171934874ec85ef7bcad2292d8728c1ce.nq.gz
│       ├── 573125e9b4eaa4b25bb1a911cf61e365b266afba.nq.gz
│       ├── 5f55063b139e5fcb70dc75cbebd4195c48f1e9bc.nq.gz
│       ├── 6261ca23bf838abaa0fa6478dc81ccb18a6949c0.nq.gz
│       ├── 6b088eaf323cadf6b3caca5a1c584b611fae4668.nq.gz
│       ├── 6d7ba589e2e37e91f12d0a0d4e4a6ae0c9e144a5.nq.gz
│       ├── 7441bf27f3a023c9d3cd57229e4e5e06ec1b8e9f.nq.gz
│       ├── 7e4a2db4afa29a59ff90d265ad115a225038a5d0.nq.gz
│       ├── 84d9a1d8792ee76dcf8497f12fa69ee094aac282.nq.gz
│       ├── 88b07b3ebc64356e6036bb8a2f33b006af64f7a7.nq.gz
│       ├── 8a7f5d82ba7bbe108a17bdc75720d11852968aed.nq.gz
│       ├── 8b185610d336693f2ff08c30157682ba7382d9ee.nq.gz
│       ├── 932e26b6508ccc10469a091f5e629dee8f2c124b.nq.gz
│       ├── 966ebdaae590cad7ecde0630923e186430960e10.nq.gz
│       ├── 96ea5feddfa8130ca8e961ab772dfdbb836cb3fa.nq.gz
│       ├── 9a4fbf83c5051eaf94a88996292c438c895306d5.nq.gz
│       ├── 9abc0292c1f96433e4f87b10d5dea0d617b0ab23.nq.gz
│       ├── 9f2a426ea7b27e9ef41bb08bff7b0481d4755aa6.nq.gz
│       ├── a27a3ee20bff6c6aa0642f31fb736e72d16abbce.nq.gz
│       ├── a81230bcff8e66a6e16522a0ab9186416d615f09.nq.gz
│       ├── aaea99f764bcd48a12fd09e5b53efd2bafd9281d.nq.gz
│       ├── ac1a33da175972f895e894121df609d0cb1448fe.nq.gz
│       ├── b391635ee4a325fb96ed531b00e4b55f66909639.nq.gz
│       ├── c24ab497ead3a30758ac1208ce76b925057138ac.nq.gz
│       ├── c9afafdd680831a43956906d56c78d9933aaf232.nq.gz
│       ├── cefafdc12e0220d139c704522979a0dc9b3f889b.nq.gz
│       ├── cf606f0a3cab3dbe8f9fdaa2ccc4882c594ce2af.nq.gz
│       ├── e0a1fd3052a54144f54a20eb97bfc3f397658675.nq.gz
│       ├── e338ab145797e57a5db73f37b3883a30592f0643.nq.gz
│       ├── e34eadb3a9354c2469fa2112400ce2690f2663ba.nq.gz
│       ├── e7849495bba31d9320e17c23f24d50f6e3447486.nq.gz
│       ├── e9e72000c50f56654c89e119ff882e322e51ecf3.nq.gz
│       ├── ecf3d7f1ca2b2a5ea9c36ce2b23ae576e0421b6c.nq.gz
│       └── f2af8c9d54e9ebc14b32fe68ddaefd01b7e5a801.nq.gz
└── blob
    ├── 00336c3e11762c13d7a58614c15032e0b82e5192.nq.gz
    ├── 0056a007ba93e92b3a715aec526da85afd2da511.nq.gz
    ├── 007f82a4a06c883854c2f648c64c0c74112ed7b1.nq.gz
    ├── 00a6277906594d76a791aa9a972c3996f5ba92eb.nq.gz
    ├── 00cb69138da5673d0576a40bdbc16261896237fd.nq.gz
    ├── 00eadcc930dc6aa0fe9a6a29c0f4ac1e8bb3be12.nq.gz
    ├── 01033c248f8bd62ac42c74ad6046cf64dbfa9087.nq.gz
    ├── 010ce3743566bc750c5e043199b0fa053fbe9e3e.nq.gz
    ├── 017eb426d5d2f2fc86b53b3abd1ea142200d0511.nq.gz
    ├── 01c6cafbe53f1fcb12f7b382b2b35e2fd2c69933.nq.gz
    ├── 02123317d53b65d8e521f972eca6b3cdace7236f.nq.gz
    ├── 021a8aaac154af1ba27f1ba991d1048433d4482b.nq.gz
    ├── 02be340721f8eb357a6be9b371c6ea061e4763f1.nq.gz
    ├── 02cab328251af9bfa809981aaa44933c407e2cd7.nq.gz
    ├── 02fdd0b0fb86634f4d297bc0bf01727cdbc3745d.nq.gz
    ├── 03202f2cd29e25d150b047d8211bc7af5f4e67f7.nq.gz
    ├── 0336b4068745f5165ee6ee8a970fc76216cb7b09.nq.gz
    ├── 036bcde0b1f318b3d22194ab1cca01cc4bcf9c3b.nq.gz
    ├── 044f1d71def372f7dc5006d3055be119d5ad20dd.nq.gz
    ├── 0459369d190ff2377a8336429fb8cd7e1a08b3fe.nq.gz
    ├── 046323eca755593e5e187ae235e63888a1023f82.nq.gz
    ├── 046476b55ff0b67029541af46a789201392a993c.nq.gz
    ├── 047ad767d79de9789d5ccae119b79cb85b5d398c.nq.gz
    ├── 04a30a53e20ca30fffc0b060df138e6d842b148d.nq.gz
    ├── 04b466003463589433782fa637744935b5344115.nq.gz
    ├── 04fbd713296a1643410aa2f422806f85ca64d93a.nq.gz
    ├── 05657d7bc7b9ec58340a6d8cf5b94d0b6db11f3d.nq.gz
    ├── 0598c7adcd26fac44fc80fb4cf07f86e6ba0b9ef.nq.gz
    ├── 05beeda4f9b7bf424d962cf223843cd4fcdd1e02.nq.gz
    ├── 05c863a93dd968675df9b4df6b1e047ae315660d.nq.gz
    ├── 05d41c993e056b6108b2270eda0965cfe9686330.nq.gz
    ├── 061cbd7fafa8977ff811b7845ad9f15cb35bc8d6.nq.gz
    ├── 06ab11ef5e38e46079824158d4e29eb9d6806f22.nq.gz
    ├── 06b12d7b0ca1ab64f59bbaf42df9e3626ed42bdb.nq.gz
    ├── 06ca5320940dad4ea1ca45d5969fa4a9a94e10f6.nq.gz
    ├── 06de437202fa2615567bff20cddc369a073c3aa5.nq.gz
    ├── 06f813743edb0405a3810a24d7f5533d0dd0842f.nq.gz
    ├── 070c9fd31975a2b54f53e6de56389768f38a7e25.nq.gz
    ├── 071957507bfc4cdd751dd2abc530f7a17aa97481.nq.gz
    ├── 074276b631405f9c5ae5a75acf0bcdaeaf966a6d.nq.gz
    ├── 074c024832bac7d86637eadf9e5da9a8ea9b5369.nq.gz
    ├── 076cb6669612f46d2a9d6ce2c64ee3b65a52cf23.nq.gz
    ├── 077508fad535e832f5c6d969519d61aa61fff633.nq.gz
    ├── 0787c33147b484432bcb4dc5523ab9c8d73bc197.nq.gz
    ├── 0790b1dadb847039d34a47344756ed3514f9e01b.nq.gz
    ├── 07943700ea8123e7af2b5dce493119203c058f1b.nq.gz
    ├── 07b7ce3dada01d26190d8ebfd75261e6b54983e5.nq.gz
    ├── 07b97291c7cb69feeb6d788de241b17f5a39aa03.nq.gz
    ├── 07c16425c0d4a859ae07db5b8c6c220d1dfe9c6d.nq.gz
    └── 07d526c50e1d532a99c45bd18399c0cb356fcbf7.nq.gz

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
*Parsed on 2026-03-29 by [repolex](https://repolex.ai)*
