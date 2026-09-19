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
└── aggregate
    ├── ast
    │   ├── 008854c40772f647dfcb873bc3489e8a1c02d598.nq.gz
    │   ├── 11c305e1722a81c553a41fb9358f1058231757c5.nq.gz
    │   ├── 15623c5a57bf758b18542d5293ee319bbd59e829.nq.gz
    │   ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
    │   ├── 1ffbd443774cbc4bf9ddd968aef7c03322f33cf0.nq.gz
    │   ├── 20024635c06c22879fd2fd1e380ec4cccd9935dd.nq.gz
    │   ├── 23aa71774457c34fe6d1fb527c1c2972447bb18d.nq.gz
    │   ├── 247431544d407d2496e200124e7b5ed2d9e657c9.nq.gz
    │   ├── 25a1bf06b4854bd8d9239f8ba05678d2c60a62ad.nq.gz
    │   ├── 260b35fd99c6b6ee9e28be8e3789e74bc3dd0cef
    │   │   └── chunk-001.nq.gz
    │   ├── 2dca1b70359dac61e1bbfb6f14ebe19a5ab79c3d
    │   │   └── chunk-001.nq.gz
    │   ├── 2ea7e586792a95e33cddc74f9e89e62bcd8d7f2b.nq.gz
    │   ├── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
    │   ├── 3473658d13a4e88e1e58a7be116ae6975ca13cf6.nq.gz
    │   ├── 36efcb5abe9ea8b6a7707243bec89a81e063c01a.nq.gz
    │   ├── 43d3b04725ab9731727fb1126e35980c62f32377
    │   │   └── chunk-001.nq.gz
    │   ├── 43d4c4e50c0334f93240aa907183bb24b8e69fe9.nq.gz
    │   ├── 494f83c923ca54ecc943bf5e60c0004e65fbb54e
    │   │   └── chunk-001.nq.gz
    │   ├── 4bf3f19c04f47c60c4fe96b81afe708a0ad812dc.nq.gz
    │   ├── 5097f44092a4ba4ef7741755b3752d2aebe772a0.nq.gz
    │   ├── 52d159aae04d12ba24ecdc3d8104e6b8068cbf5f.nq.gz
    │   ├── 550d391171934874ec85ef7bcad2292d8728c1ce.nq.gz
    │   ├── 573125e9b4eaa4b25bb1a911cf61e365b266afba.nq.gz
    │   ├── 5f55063b139e5fcb70dc75cbebd4195c48f1e9bc.nq.gz
    │   ├── 6261ca23bf838abaa0fa6478dc81ccb18a6949c0.nq.gz
    │   ├── 6b088eaf323cadf6b3caca5a1c584b611fae4668.nq.gz
    │   ├── 6d30ad0f30028210124c149811cbbe2b183711f9
    │   │   └── chunk-001.nq.gz
    │   ├── 6d7ba589e2e37e91f12d0a0d4e4a6ae0c9e144a5.nq.gz
    │   ├── 72e3bb33d44fd96881f7742b77137983907a942f
    │   │   └── chunk-001.nq.gz
    │   ├── 7441bf27f3a023c9d3cd57229e4e5e06ec1b8e9f.nq.gz
    │   ├── 748dea614fa03ac8d3b1d66d14a2acc8c8ec223f.nq.gz
    │   ├── 7e4a2db4afa29a59ff90d265ad115a225038a5d0.nq.gz
    │   ├── 7f580bdcf07a3b269a0e786b6a3aa9c804f393cf
    │   │   └── chunk-001.nq.gz
    │   ├── 84d9a1d8792ee76dcf8497f12fa69ee094aac282.nq.gz
    │   ├── 87529ad403630d6b7d1047179a5e62341fd75b3c
    │   │   └── chunk-001.nq.gz
    │   ├── 88b07b3ebc64356e6036bb8a2f33b006af64f7a7.nq.gz
    │   ├── 8a7f5d82ba7bbe108a17bdc75720d11852968aed.nq.gz
    │   ├── 8b185610d336693f2ff08c30157682ba7382d9ee.nq.gz
    │   ├── 8c297cb6da44a5b31e84038a72b946c22c93e27e
    │   │   └── chunk-001.nq.gz
    │   ├── 932e26b6508ccc10469a091f5e629dee8f2c124b.nq.gz
    │   ├── 966ebdaae590cad7ecde0630923e186430960e10.nq.gz
    │   ├── 96ea5feddfa8130ca8e961ab772dfdbb836cb3fa.nq.gz
    │   ├── 9a4fbf83c5051eaf94a88996292c438c895306d5.nq.gz
    │   ├── 9abc0292c1f96433e4f87b10d5dea0d617b0ab23.nq.gz
    │   ├── 9f2a426ea7b27e9ef41bb08bff7b0481d4755aa6.nq.gz
    │   ├── a27a3ee20bff6c6aa0642f31fb736e72d16abbce.nq.gz
    │   ├── a81230bcff8e66a6e16522a0ab9186416d615f09.nq.gz
    │   ├── aaea99f764bcd48a12fd09e5b53efd2bafd9281d.nq.gz
    │   ├── ac1a33da175972f895e894121df609d0cb1448fe.nq.gz
    │   ├── afaf8cc7e08fd47d2c78c953c4b8ea663e05fb90
    │   │   └── chunk-001.nq.gz
    │   ├── b391635ee4a325fb96ed531b00e4b55f66909639.nq.gz
    │   ├── b7ac6bb73dd7e6d42063bd0b4434322763b460c2
    │   │   └── chunk-001.nq.gz
    │   ├── c24ab497ead3a30758ac1208ce76b925057138ac.nq.gz
    │   ├── c3d0e3584202d66703d2bcf2aaf3e7740bef6e2d.nq.gz
    │   ├── c9afafdd680831a43956906d56c78d9933aaf232.nq.gz
    │   ├── ce0118819d172d134507bcf5982d3faf82bbc43e
    │   │   └── chunk-001.nq.gz
    │   ├── cefafdc12e0220d139c704522979a0dc9b3f889b.nq.gz
    │   ├── cf606f0a3cab3dbe8f9fdaa2ccc4882c594ce2af.nq.gz
    │   ├── d9d59c6eda6d21f4515e9a8fe9496fa5e68f9500.nq.gz
    │   ├── e0a1fd3052a54144f54a20eb97bfc3f397658675.nq.gz
    │   ├── e338ab145797e57a5db73f37b3883a30592f0643.nq.gz
    │   ├── e34eadb3a9354c2469fa2112400ce2690f2663ba.nq.gz
    │   ├── e5246436cd75de32f3436cc88d6e4fdebe13bd8d.nq.gz
    │   ├── e7849495bba31d9320e17c23f24d50f6e3447486.nq.gz
    │   ├── e9e72000c50f56654c89e119ff882e322e51ecf3.nq.gz
    │   ├── e9f75c9912ed25b9777bc0257853370951220b17
    │   │   └── chunk-001.nq.gz
    │   ├── ec91917deb47b43188312e0e3f03bbab7e4e2e7e
    │   │   └── chunk-001.nq.gz
    │   ├── ecf3d7f1ca2b2a5ea9c36ce2b23ae576e0421b6c.nq.gz
    │   └── f2af8c9d54e9ebc14b32fe68ddaefd01b7e5a801.nq.gz
    ├── lsp
    │   ├── 008854c40772f647dfcb873bc3489e8a1c02d598.nq.gz
    │   ├── 11c305e1722a81c553a41fb9358f1058231757c5.nq.gz
    │   ├── 15623c5a57bf758b18542d5293ee319bbd59e829.nq.gz
    │   ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
    │   ├── 1ffbd443774cbc4bf9ddd968aef7c03322f33cf0.nq.gz
    │   ├── 20024635c06c22879fd2fd1e380ec4cccd9935dd.nq.gz
    │   ├── 23aa71774457c34fe6d1fb527c1c2972447bb18d.nq.gz
    │   ├── 247431544d407d2496e200124e7b5ed2d9e657c9.nq.gz
    │   ├── 25a1bf06b4854bd8d9239f8ba05678d2c60a62ad.nq.gz
    │   ├── 260b35fd99c6b6ee9e28be8e3789e74bc3dd0cef.nq.gz
    │   ├── 2dca1b70359dac61e1bbfb6f14ebe19a5ab79c3d.nq.gz
    │   ├── 2ea7e586792a95e33cddc74f9e89e62bcd8d7f2b.nq.gz
    │   ├── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
    │   ├── 3473658d13a4e88e1e58a7be116ae6975ca13cf6.nq.gz
    │   ├── 36efcb5abe9ea8b6a7707243bec89a81e063c01a.nq.gz
    │   ├── 43d3b04725ab9731727fb1126e35980c62f32377.nq.gz
    │   ├── 43d4c4e50c0334f93240aa907183bb24b8e69fe9.nq.gz
    │   ├── 494f83c923ca54ecc943bf5e60c0004e65fbb54e.nq.gz
    │   ├── 4bf3f19c04f47c60c4fe96b81afe708a0ad812dc.nq.gz
    │   ├── 5097f44092a4ba4ef7741755b3752d2aebe772a0.nq.gz
    │   ├── 52d159aae04d12ba24ecdc3d8104e6b8068cbf5f.nq.gz
    │   ├── 550d391171934874ec85ef7bcad2292d8728c1ce.nq.gz
    │   ├── 573125e9b4eaa4b25bb1a911cf61e365b266afba.nq.gz
    │   ├── 5f55063b139e5fcb70dc75cbebd4195c48f1e9bc.nq.gz
    │   ├── 6261ca23bf838abaa0fa6478dc81ccb18a6949c0.nq.gz
    │   ├── 6b088eaf323cadf6b3caca5a1c584b611fae4668.nq.gz
    │   ├── 6d30ad0f30028210124c149811cbbe2b183711f9.nq.gz
    │   ├── 6d7ba589e2e37e91f12d0a0d4e4a6ae0c9e144a5.nq.gz
    │   ├── 72e3bb33d44fd96881f7742b77137983907a942f.nq.gz
    │   ├── 7441bf27f3a023c9d3cd57229e4e5e06ec1b8e9f.nq.gz
    │   ├── 748dea614fa03ac8d3b1d66d14a2acc8c8ec223f.nq.gz
    │   ├── 7e4a2db4afa29a59ff90d265ad115a225038a5d0.nq.gz
    │   ├── 7f580bdcf07a3b269a0e786b6a3aa9c804f393cf.nq.gz
    │   ├── 84d9a1d8792ee76dcf8497f12fa69ee094aac282.nq.gz
    │   ├── 87529ad403630d6b7d1047179a5e62341fd75b3c.nq.gz
    │   ├── 88b07b3ebc64356e6036bb8a2f33b006af64f7a7.nq.gz
    │   ├── 8a7f5d82ba7bbe108a17bdc75720d11852968aed.nq.gz
    │   ├── 8b185610d336693f2ff08c30157682ba7382d9ee.nq.gz
    │   ├── 8c297cb6da44a5b31e84038a72b946c22c93e27e.nq.gz
    │   ├── 932e26b6508ccc10469a091f5e629dee8f2c124b.nq.gz
    │   ├── 966ebdaae590cad7ecde0630923e186430960e10.nq.gz
    │   ├── 96ea5feddfa8130ca8e961ab772dfdbb836cb3fa.nq.gz
    │   ├── 9a4fbf83c5051eaf94a88996292c438c895306d5.nq.gz
    │   ├── 9abc0292c1f96433e4f87b10d5dea0d617b0ab23.nq.gz
    │   ├── 9f2a426ea7b27e9ef41bb08bff7b0481d4755aa6.nq.gz
    │   ├── a27a3ee20bff6c6aa0642f31fb736e72d16abbce.nq.gz
    │   ├── a81230bcff8e66a6e16522a0ab9186416d615f09.nq.gz
    │   ├── aaea99f764bcd48a12fd09e5b53efd2bafd9281d.nq.gz
    │   ├── ac1a33da175972f895e894121df609d0cb1448fe.nq.gz
    │   ├── afaf8cc7e08fd47d2c78c953c4b8ea663e05fb90.nq.gz
    │   ├── b391635ee4a325fb96ed531b00e4b55f66909639.nq.gz
    │   ├── b7ac6bb73dd7e6d42063bd0b4434322763b460c2.nq.gz
    │   ├── c24ab497ead3a30758ac1208ce76b925057138ac.nq.gz
    │   ├── c3d0e3584202d66703d2bcf2aaf3e7740bef6e2d.nq.gz
    │   ├── c9afafdd680831a43956906d56c78d9933aaf232.nq.gz
    │   ├── ce0118819d172d134507bcf5982d3faf82bbc43e.nq.gz
    │   ├── cefafdc12e0220d139c704522979a0dc9b3f889b.nq.gz
    │   ├── cf606f0a3cab3dbe8f9fdaa2ccc4882c594ce2af.nq.gz
    │   ├── d9d59c6eda6d21f4515e9a8fe9496fa5e68f9500.nq.gz
    │   ├── e0a1fd3052a54144f54a20eb97bfc3f397658675.nq.gz
    │   ├── e338ab145797e57a5db73f37b3883a30592f0643.nq.gz
    │   ├── e34eadb3a9354c2469fa2112400ce2690f2663ba.nq.gz
    │   ├── e5246436cd75de32f3436cc88d6e4fdebe13bd8d.nq.gz
    │   ├── e7849495bba31d9320e17c23f24d50f6e3447486.nq.gz
    │   ├── e9e72000c50f56654c89e119ff882e322e51ecf3.nq.gz
    │   ├── e9f75c9912ed25b9777bc0257853370951220b17.nq.gz
    │   ├── ec91917deb47b43188312e0e3f03bbab7e4e2e7e.nq.gz
    │   ├── ecf3d7f1ca2b2a5ea9c36ce2b23ae576e0421b6c.nq.gz
    │   └── f2af8c9d54e9ebc14b32fe68ddaefd01b7e5a801.nq.gz
    └── repolex
        ├── 008854c40772f647dfcb873bc3489e8a1c02d598.nq.gz
        ├── 11c305e1722a81c553a41fb9358f1058231757c5.nq.gz
        ├── 15623c5a57bf758b18542d5293ee319bbd59e829.nq.gz
        ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
        ├── 1ffbd443774cbc4bf9ddd968aef7c03322f33cf0.nq.gz
        ├── 20024635c06c22879fd2fd1e380ec4cccd9935dd.nq.gz
        ├── 23aa71774457c34fe6d1fb527c1c2972447bb18d.nq.gz
        ├── 247431544d407d2496e200124e7b5ed2d9e657c9.nq.gz
        ├── 25a1bf06b4854bd8d9239f8ba05678d2c60a62ad.nq.gz
        ├── 260b35fd99c6b6ee9e28be8e3789e74bc3dd0cef
        │   └── chunk-001.nq.gz
        ├── 2dca1b70359dac61e1bbfb6f14ebe19a5ab79c3d
        │   └── chunk-001.nq.gz
        ├── 2ea7e586792a95e33cddc74f9e89e62bcd8d7f2b.nq.gz
        ├── 334dc742fbed621ccf21a6d8a76e71f74e51fcf1.nq.gz
        ├── 3473658d13a4e88e1e58a7be116ae6975ca13cf6.nq.gz
        ├── 36efcb5abe9ea8b6a7707243bec89a81e063c01a.nq.gz
        ├── 43d3b04725ab9731727fb1126e35980c62f32377
        │   └── chunk-001.nq.gz
        ├── 43d4c4e50c0334f93240aa907183bb24b8e69fe9.nq.gz
        ├── 494f83c923ca54ecc943bf5e60c0004e65fbb54e
        │   └── chunk-001.nq.gz
        ├── 4bf3f19c04f47c60c4fe96b81afe708a0ad812dc.nq.gz
        ├── 5097f44092a4ba4ef7741755b3752d2aebe772a0.nq.gz
        ├── 52d159aae04d12ba24ecdc3d8104e6b8068cbf5f.nq.gz
        ├── 550d391171934874ec85ef7bcad2292d8728c1ce.nq.gz
        ├── 573125e9b4eaa4b25bb1a911cf61e365b266afba.nq.gz
        ├── 5f55063b139e5fcb70dc75cbebd4195c48f1e9bc.nq.gz
        ├── 6261ca23bf838abaa0fa6478dc81ccb18a6949c0.nq.gz
        ├── 6b088eaf323cadf6b3caca5a1c584b611fae4668.nq.gz
        ├── 6d30ad0f30028210124c149811cbbe2b183711f9
        │   └── chunk-001.nq.gz
        ├── 6d7ba589e2e37e91f12d0a0d4e4a6ae0c9e144a5.nq.gz
        ├── 72e3bb33d44fd96881f7742b77137983907a942f
        │   └── chunk-001.nq.gz
        ├── 7441bf27f3a023c9d3cd57229e4e5e06ec1b8e9f.nq.gz
        ├── 748dea614fa03ac8d3b1d66d14a2acc8c8ec223f.nq.gz
        ├── 7e4a2db4afa29a59ff90d265ad115a225038a5d0.nq.gz
        ├── 7f580bdcf07a3b269a0e786b6a3aa9c804f393cf
        │   └── chunk-001.nq.gz
        ├── 84d9a1d8792ee76dcf8497f12fa69ee094aac282.nq.gz
        ├── 87529ad403630d6b7d1047179a5e62341fd75b3c
        │   └── chunk-001.nq.gz
        ├── 88b07b3ebc64356e6036bb8a2f33b006af64f7a7.nq.gz
        ├── 8a7f5d82ba7bbe108a17bdc75720d11852968aed.nq.gz
        ├── 8b185610d336693f2ff08c30157682ba7382d9ee.nq.gz
        ├── 8c297cb6da44a5b31e84038a72b946c22c93e27e
        │   └── chunk-001.nq.gz
        ├── 932e26b6508ccc10469a091f5e629dee8f2c124b.nq.gz
        ├── 966ebdaae590cad7ecde0630923e186430960e10.nq.gz
        ├── 96ea5feddfa8130ca8e961ab772dfdbb836cb3fa.nq.gz
        ├── 9a4fbf83c5051eaf94a88996292c438c895306d5.nq.gz
        ├── 9abc0292c1f96433e4f87b10d5dea0d617b0ab23.nq.gz
        ├── 9f2a426ea7b27e9ef41bb08bff7b0481d4755aa6.nq.gz
        ├── a27a3ee20bff6c6aa0642f31fb736e72d16abbce.nq.gz
        ├── a81230bcff8e66a6e16522a0ab9186416d615f09.nq.gz
        ├── aaea99f764bcd48a12fd09e5b53efd2bafd9281d.nq.gz
        ├── ac1a33da175972f895e894121df609d0cb1448fe.nq.gz
        ├── afaf8cc7e08fd47d2c78c953c4b8ea663e05fb90
        │   └── chunk-001.nq.gz
        ├── b391635ee4a325fb96ed531b00e4b55f66909639.nq.gz
        ├── b7ac6bb73dd7e6d42063bd0b4434322763b460c2
        │   └── chunk-001.nq.gz
        ├── c24ab497ead3a30758ac1208ce76b925057138ac.nq.gz
        ├── c3d0e3584202d66703d2bcf2aaf3e7740bef6e2d.nq.gz
        ├── c9afafdd680831a43956906d56c78d9933aaf232.nq.gz
        ├── ce0118819d172d134507bcf5982d3faf82bbc43e
        │   └── chunk-001.nq.gz
        ├── cefafdc12e0220d139c704522979a0dc9b3f889b.nq.gz
        ├── cf606f0a3cab3dbe8f9fdaa2ccc4882c594ce2af.nq.gz
        ├── d9d59c6eda6d21f4515e9a8fe9496fa5e68f9500.nq.gz
        ├── e0a1fd3052a54144f54a20eb97bfc3f397658675.nq.gz
        ├── e338ab145797e57a5db73f37b3883a30592f0643.nq.gz
        └── e34eadb3a9354c2469fa2112400ce2690f2663ba.nq.gz

31 directories, 200 files
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
*Parsed on 2026-09-19 by [repolex](https://repolex.ai)*
