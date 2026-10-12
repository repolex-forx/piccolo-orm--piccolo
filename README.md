# Repolex Knowledge Graph of piccolo-orm/piccolo

RDF knowledge graph data for [piccolo-orm/piccolo](https://github.com/piccolo-orm/piccolo), parsed by [repolex](https://repolex.ai).

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
rlex download piccolo-orm/piccolo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2556bbf2af69070d9a0d2ea468d7b9cd576fd2d3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2556bbf2af69070d9a0d2ea468d7b9cd576fd2d3
│           └── chunk-001.nq.gz
└── blob
    ├── 0089f811a4420edf28815bb00606096306c63f6d.nq.gz
    ├── 00c02009198c7babab441fc11a7d2fb39bb45f4a.nq.gz
    ├── 01345b3f33390720e3a5d8ab3e0e246bd0cdd1bd.nq.gz
    ├── 01ed90681bab1354002f0d63a50f7927a2f03f0e.nq.gz
    ├── 03b9827caee24ddbaa0486492d5bfacd00638c25.nq.gz
    ├── 0447ebca824bd0a01b077311f62d7844e9f5456c.nq.gz
    ├── 04b57823dba96beb7d88e0c0888f11054a9520e6.nq.gz
    ├── 068e398b81548a17e0fbfebc93fde67239b33640.nq.gz
    ├── 06cb5f1334451d3a7a7e9116a6a129f218a338b9.nq.gz
    ├── 084da7c6c5f48ea82ff4fd99025bfb008db5b82f.nq.gz
    ├── 08cc48a2b4b13ca0a4122420f41ceaa9698a044c.nq.gz
    ├── 08cd7a7c27f13505abb93b8bf7c68245288d0c9b.nq.gz
    ├── 0924967a317fb534416ae580f1d35c6bbde260f4.nq.gz
    ├── 09abb9de81ec7969d71c4765f22cfe450d2bc746.nq.gz
    ├── 0a400c3dfd58f8cd89b25cc237c40a854e3dd446.nq.gz
    ├── 0b6763e0c1e45db2d4d1509a5f19b0711949b70c.nq.gz
    ├── 0be80ebef8135d6c037917397347d5ca9e7803cf.nq.gz
    ├── 0c1a11fa60e73a2afaac90e5cd91c07ac7dffbfd.nq.gz
    ├── 0c7323b2f830343bc1bb6c283d7663dde9d8f70e.nq.gz
    ├── 0c94768d42bb8a0f0bc6b99ce44decc724c4b4b6.nq.gz
    ├── 0d45d3a357e7dcecfbb9f3019448976b1edd7ef2.nq.gz
    ├── 0d6645efff7c0375a9c15947c9318ae4b72523a7.nq.gz
    ├── 0d6828ddf3fbdd10d350ad777685a9e067f14edf.nq.gz
    ├── 0e0c91a614475eb87d702e9f594f7d016431211d.nq.gz
    ├── 0e92ee92abc0c9c554d34ed93d12aebfd408bdb8.nq.gz
    ├── 0f14f4210a0a042b9defb3d623722242cc442889.nq.gz
    ├── 0f6686cf98ed1b2690b878336de51342b153d131.nq.gz
    ├── 1106cd3508660eaa0004c74c338765b316291fc7.nq.gz
    ├── 113baa520803d8848fd1c7febb0bbc55ba25d79c.nq.gz
    ├── 11b9bf65152ec8d5dcedbba2a7a202f19abffff8.nq.gz
    ├── 11c68a688f16cabc2a30f6453f5d01bbd8a03712.nq.gz
    ├── 123bb5a6635dcc995979e0d0627926179a92590f.nq.gz
    ├── 12b7e67a783e71e66aafc55a2b02ebd6080a2523.nq.gz
    ├── 143c336c395dcb9e70c26e4020911fb4dbfe262a.nq.gz
    ├── 14582f90314f57133cbb147e7760166647d23e63.nq.gz
    ├── 1549709a64e343f3714b33085e7d330c40a6fa67.nq.gz
    ├── 1628c475819f9e45fb0adb579e6afb0de4ffc6a6.nq.gz
    ├── 16e541a43f4b2a33f7d01faedc9558e14a3510ad.nq.gz
    ├── 17ac134d3d6760d58a3efcda38cd363270d4101c.nq.gz
    ├── 18c35e33710b2c8cd313a0a6919b7818dc6f6fda.nq.gz
    ├── 18e36c38373ddfdbd1f0dff080eea8242bad9473.nq.gz
    ├── 19669c61bd81304cfd50d025f925c434ce9a48cf.nq.gz
    ├── 19a012aa290d027374c165b3229423b8c5a3309d.nq.gz
    ├── 1a33a418c5d50ae6f6ba7521ea54cf587a216379.nq.gz
    ├── 1b2d9f0828dc64f1bf1b04a0cd717b45c42b2593.nq.gz
    ├── 1b3328fed0b371017fd2c8f9924f704254971df2.nq.gz
    ├── 1b3346637f5f2751da5c35b27bb7f8a5b1271e3e.nq.gz
    ├── 1b54800e63561cd49b42b7c5429ff6f49f1ecfe1.nq.gz
    ├── 1b7340b80bf93851197567074298350540581f73.nq.gz
    ├── 1bbb44f723f2fd46eaf4432201f6464acfc430f3.nq.gz
    ├── 1bda3fd0cae301835a37b913d406b089cac423e7.nq.gz
    ├── 1c04150f1703543e77710b6d93952ff22be65d94.nq.gz
    ├── 1c5918999bd555da4c5050f2090eeeee62c44a74.nq.gz
    ├── 1c858d42559d02225be75fe5332f7061da56eccd.nq.gz
    ├── 1c979f94bc82ab6f4b4e7565f57086417c5b3db9.nq.gz
    ├── 1ca4ed7d4e49e920b77f74f9c181380464a358a0.nq.gz
    ├── 1d7d14047b80fe5c88526c63f4eddf6dc30b4a7f.nq.gz
    ├── 1df58816cf9fcab587e1e5af78b6cf42c48389c1.nq.gz
    ├── 1fa310efa15072f22cd04992589085cf176bfe46.nq.gz
    ├── 1fc4a464ed14b801d3211a829262e9be28b7328b.nq.gz
    ├── 218acd458000c13425ebc57a6700c66c5e067886.nq.gz
    ├── 21c3903ab7f673bb22033e3c182f57d3f2e20768.nq.gz
    ├── 22c65e6deaa439466ed73115856f61ab0c9be395.nq.gz
    ├── 22e6eb8526bea4f3bf0edbc95d1ccd0ecc8797fb.nq.gz
    ├── 235d5e4c91be771f2a3cd9e5c86754cf8186be53.nq.gz
    ├── 2379ff22827d25f03c73b77cb924b966e8fc26e3.nq.gz
    ├── 239ecd90e5c4431f3b1f6377143dceb32609085a.nq.gz
    ├── 24a913fcaf170f6d2086e11c01ba31f138a31dda.nq.gz
    ├── 259642eb095a2a17395e5e4c3fa48f871f011b28.nq.gz
    ├── 25b72e8e3a55d9597c6ee0533997b12d62fd3422.nq.gz
    ├── 25d1b9494a67d1428e15281cbcbe3e42ecb078a7.nq.gz
    ├── 2886ad94fed52743c9cf0b53103405ac774fa006.nq.gz
    ├── 28f2db1c317925e1e72399ff89033ae572b6f8b0.nq.gz
    ├── 29396d7dfd717217e7835c42b2be1fff2145d583.nq.gz
    ├── 29669a097edcdce37a013cbd0bc44993a653c7ee.nq.gz
    ├── 2afc9b781b86c27d25803ce25ddabc4c5cd2ddab.nq.gz
    ├── 2b1840c58627b15d50d9b31153d5444d6d651ef9.nq.gz
    ├── 2b35a4f65d1398dcfd5fd583f21c09f45a72eaf7.nq.gz
    ├── 2bc2cc5f9d9972fa48132b3d3721b09bb5ff7d0a.nq.gz
    ├── 2d90059cd8de3e4c6445926d91cedb92a62aba5b.nq.gz
    ├── 2e6ec3d3a9904ab70030bd4dc826dd8c6bbbf8e5.nq.gz
    ├── 2e91ea548bc027551d73e3914f435e24b8cf4608.nq.gz
    ├── 2ed15d87f568def43f7c1e12fb783844347ac48b.nq.gz
    ├── 2ef4c2a8c62e227d43631b7327e0ce29a2f2e3df.nq.gz
    ├── 2f2f320e02a83f43ea808424f15daf4e592389fb.nq.gz
    ├── 30ce3639e9c0f110769f05d5c8410fa1fdaee683.nq.gz
    ├── 30fb6e73c804ef60b204d7313072ceb555ee8130.nq.gz
    ├── 31eb4cfa7bdc3e29c6f8a7db7d391de8f3d3cb5c.nq.gz
    ├── 32057b9f0a13ea6d98e27ca65e0b8c0ab4cc5a30.nq.gz
    ├── 32a6be15b13ee9e23765eebfde3532d73dac391b.nq.gz
    ├── 330645c362ca3c2a459e145ad05b3e36c01017b9.nq.gz
    ├── 34e2af4ee8cf998b84ca67f7fca5963bcb94e566.nq.gz
    ├── 35247400c91687b57409d645b7607def3f6e255b.nq.gz
    ├── 35ff6727e3b70c73d2850a9e612013b233c26ff1.nq.gz
    ├── 36a3b6330f6d302b6e44e0215cd066dc2bf58606.nq.gz
    ├── 36d5b10c21eff21d6953d31d0433dece532e0283.nq.gz
    ├── 373cad7865a8068f6c8aacfaeb780f0b2a022e25.nq.gz
    ├── 37a98d37bf072f79650caeac7e541071d99f554c.nq.gz
    ├── 37b5fbc1761294fa5a126c5bf02866f748af1364.nq.gz
    ├── 39d6298144243ed1cd130092df74703fe6c9bce8.nq.gz
    ├── 3a349d23ab064eed98472f562759b9bff8b57ba2.nq.gz
    ├── 3ae989b5e58e33494e2351e115decc72ccc52f0a.nq.gz
    ├── 3b1a95a4e261e0548c0dcb65e61a4034622fa495.nq.gz
    ├── 3b5352d58b46ef50577d6080134112fa59769183.nq.gz
    ├── 3c61ae9b6318f50533d65e22f26d9c768ad53ec9.nq.gz
    ├── 3c77d4ded42970c8cd91fb5bd2a7bec8350268a9.nq.gz
    ├── 3c931f50289ecaac6e76955ad40f641075b978a9.nq.gz
    ├── 3cce94e1f7b700b196a174e663f5a30e23946d6b.nq.gz
    ├── 3cf8c61196e7c0b86db5ffcb73603adc82b6ba2a.nq.gz
    ├── 3d89c6da2d45dd2fd927d70825005fbb03d136b0.nq.gz
    ├── 3def36fdac25b3c4f02ba507a8120e0431f7b9b1.nq.gz
    ├── 3fe3a815884b719a60f3ee335ca64b75b1d2b18a.nq.gz
    ├── 40ae595179ddb60d83c1790a5e97df35893c3034.nq.gz
    ├── 4160189ad96ce4e679771ce4c6ecf15dc04d18d7.nq.gz
    ├── 41afc18237933bcf81beba9f398e64e50e44beb8.nq.gz
    ├── 41f1a0f16d65d2a1fdbf974a7f87f910d1358314.nq.gz
    ├── 42a2703f97a16fd168b4eae4525c1e409377e874.nq.gz
    ├── 446e6f20f2f049528ce90eeb7b4e197113e1894b.nq.gz
    ├── 4498e9f389d61ba26f669500d1ea0b4a4236a6ea.nq.gz
    ├── 45a3b7c12128a59f74b4bebe1377d416b0f5db9e.nq.gz
    ├── 46ea60f978b415565b6c79cc8f0ce9df9bd56b63.nq.gz
    ├── 47cf6944fd79102b6d8e859894a14b96d2a44f10.nq.gz
    ├── 48048ce5ad68b27f33a233d666dcb1778c541808.nq.gz
    ├── 482e0a21defcd3542705db2ad26c336c4e661f33.nq.gz
    ├── 4831569babe13abaab0114fc1e3b505d42c388e1.nq.gz
    ├── 4840380036eef73616c3094e59ff3fce716470ff.nq.gz
    ├── 48609827a2b1ea0644e952e6695930771338a29c.nq.gz
    ├── 486c46165580b73c280cfe0ee7101262787c961c.nq.gz
    ├── 48ca4eb813dc4c82bd501e4b9bf450e3510b047b.nq.gz
    ├── 494b4fc89d3a5d03b25309cf9bebb674cb968595.nq.gz
    ├── 4970a2c7a2dfab4dd07cb4fd5423bb6e9e736be9.nq.gz
    ├── 499d5600722f3086a0766d94d3106c5a70e39ea9.nq.gz
    ├── 49a7ffe2a956b5f597d847049ef4c1de916cb1a8.nq.gz
    ├── 49f07807675550c7862a8eacb6eb32d0eea678e8.nq.gz
    ├── 4b24f7fd6c38b81e2c0ecf3bac12b99d6e71aa10.nq.gz
    ├── 4b7c533720902e6a490bc9dad07192dbdbe8135e.nq.gz
    ├── 4cecf39b5e13b07408524707df87ad0464089ba6.nq.gz
    ├── 4d44c96f50d7586adce44b7a4b40a67a967930f3.nq.gz
    ├── 4e1e0aaf4360ac4928e25b4245e8ec87361cd194.nq.gz
    ├── 4f36bf99f089e314640ec0ca02b924cdd502472b.nq.gz
    ├── 4f72022a0c142e894a215ce3b2419c2af1029767.nq.gz
    ├── 5054bcf90262d8caf51a3bbb25cba400c399a179.nq.gz
    ├── 525aded5c097d8d1dd669bc9552308a85d945372.nq.gz
    ├── 52618761be55301cbce2b479f71376afb087c75d.nq.gz
    ├── 52a94fff8bc39740dce9686eef0e0517d6e9238f.nq.gz
    ├── 52eaf191c1aa26ca681cfbf802dcca181a3d3451.nq.gz
    ├── 532cf309d01faf52d24828712bedc72227e7b40a.nq.gz
    ├── 5396f2bcfb5d7c07bd0c5aa77238ca5dfb4f2063.nq.gz
    ├── 54401f9f30935c3433c6482f7815c80364025f68.nq.gz
    ├── 548efa9b595dee3bf1106acda4ed1bdf97b520f9.nq.gz
    ├── 54f7c28e5ead4c2409cc4c068320e3dd20b5a2a2.nq.gz
    ├── 55704f02a7abdf0736146c27a9c9bb6c186748e7.nq.gz
    ├── 55da9bb2ce5f63b1575c7264a336bb7a97b162c4.nq.gz
    ├── 56525287f234065623c72f10cb7651a1a0a2ebfd.nq.gz
    ├── 568445c2ea23ae19ac5f1d37b97b0f7de4adfd23.nq.gz
    ├── 569462d3c2d5746b8bb4a6b12151ab299a30fce7.nq.gz
    ├── 5780fb690077386829be6488d6453de9159df978.nq.gz
    ├── 57a456afff7816dcfc39d65d4134716465218f9a.nq.gz
    ├── 5817d007b1cb085513c9f6e82802927b346c17db.nq.gz
    ├── 5884daeee6e2c5c39620918ea5420e3721ef19ef.nq.gz
    ├── 58a8f55370ea6958ffdeda979507b52987c2faa3.nq.gz
    ├── 597b33bd6d325c5eaa0a477ecd987d8a4d4f9733.nq.gz
    ├── 598d9d37c1454f734fe6e8d9f8246f818249d5c2.nq.gz
    ├── 5a4e9615db76c42b1d09209f45c4b71cd0b2c57a.nq.gz
    ├── 5a5f59a6e408a64fc22b71c680d9b7e6900336b0.nq.gz
    ├── 5a95015a05b265c9854f68b73aea84c33fd17e8d.nq.gz
    ├── 5aaa6cf14ce5598ecff934c9b0dabb6a2f68eb34.nq.gz
    ├── 5acf00f1cd6195a41b06fc42a0c0a80932cfb69d.nq.gz
    ├── 5b00db3f6d1f497086bbfec7ac2861dc1eb8f060.nq.gz
    ├── 5be16158c079e79d48b27c993b4b15b58b1fb63a.nq.gz
    ├── 5bf490c095497948d9c81f630ff8cc830bbc0264.nq.gz
    ├── 5c85816fd1353277806d92d77cfd95f8d6948523.nq.gz
    ├── 5d72c52f529ac256dfbc8523251e45328485b24c.nq.gz
    ├── 5d884210dad040fa1b43b16ec68b28f9e581cd97.nq.gz
    ├── 5f96613977834561bba17956922552397d0b1dbd.nq.gz
    ├── 5fcbde41e06e6af45171fe1bc33ac671aa896a29.nq.gz
    ├── 603264170f578785878e5ecf4c3709e53aeb34fd.nq.gz
    ├── 614a974fcee8f4c5cdb9a37cc297da21eec46270.nq.gz
    ├── 616652eb83a2bd4e64e954cbd4325af993b01956.nq.gz
    ├── 61a54e7611c8be2afd318b472198d4128529e040.nq.gz
    ├── 6292c2d712d778170afc120500921109fb7155bc.nq.gz
    ├── 62abc25dd5e689a931da94f3f6422feb8290fb3e.nq.gz
    ├── 62aea2a38a3fa5c953471b322a32190adfb616d9.nq.gz
    ├── 634701869e027231a95092a5295a478cc5f293f6.nq.gz
    ├── 63ae909919d7c19c1dd40155d3a2d6aae0ce2326.nq.gz
    ├── 63c8809e57e0d665b69f82cd3e92a5c9dab06e09.nq.gz
    ├── 641bda3485da2fd1e57e1093f3c3684823b98d37.nq.gz
    ├── 64ae4b4d84f394731ea181d8248fbaf8b0469028.nq.gz
    ├── 65d922a9ca87af5c6cd5633405f0c1b923cdf3d2.nq.gz
    ├── 6648d6d0bf491b59daedebfc564ae62c3a93f3e1.nq.gz
    ├── 66915ad4f1ee3cc02531d0ab434563353928c49a.nq.gz
    ├── 68bed672b82e0ca4b9a56b6db6e598bcd2d175fd.nq.gz
    ├── 68f3d6b0068794eccae8907b8406ee5cce538021.nq.gz
    ├── 691ed55c2d0c004188b0290c24cb782f5fbef9d8.nq.gz
    ├── 6a91c3fe5a0d834268ab06ab6f05e21e5bd6c40e.nq.gz
    ├── 6b31afa0066f9bec6a3c2b49c1b60696e76921c1.nq.gz
    ├── 6b94727640219f15f2a3e791d3e8e6d7d32ee77c.nq.gz
    └── 6bd8deb49a2e75cc5cf5f8f8f473b742049ba015.nq.gz

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

[piccolo-orm/piccolo](https://github.com/piccolo-orm/piccolo)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
