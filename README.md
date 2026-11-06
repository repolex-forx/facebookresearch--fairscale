# Repolex Knowledge Graph of facebookresearch/fairscale

RDF knowledge graph data for [facebookresearch/fairscale](https://github.com/facebookresearch/fairscale), parsed by [repolex](https://repolex.ai).

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
rlex download facebookresearch/fairscale
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 146f160241651e1211c4247979f159a4ef43b54a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 146f160241651e1211c4247979f159a4ef43b54a
│           └── chunk-001.nq.gz
└── blob
    ├── 01262e3a367abe3f59c9656f14b9d2ac54e752f5.nq.gz
    ├── 013539801066d3311519437098f69d8bc39a38e4.nq.gz
    ├── 0189beb1683e120598c64ca28f84080f842f9a91.nq.gz
    ├── 0270940ec7d9ecbeca169fc82b1b68b7c7bc4451.nq.gz
    ├── 028d058592d624ca40795f836112eda4f9a15c7b.nq.gz
    ├── 033b0021b98e13aee835b6a682600ae023048445.nq.gz
    ├── 03574e8c835a357a67457775502b580675e82d6a.nq.gz
    ├── 03c2c51e0470e3d6055ea550c5642c7604f49092.nq.gz
    ├── 042eb92b5cf62d245133fc26c92628270b1c7a51.nq.gz
    ├── 04b38a3bdf8df8974d2da944033656618a9d9add.nq.gz
    ├── 0536b1e1d4c3f6b3d5af7458f2c7406bea845418.nq.gz
    ├── 05ce643c76b2a4bdbb9eecebd4b06a0d7191679c.nq.gz
    ├── 05ff22094db0ef84a0e9ec281ebaa317503d4398.nq.gz
    ├── 066f7252c85c5d0593dddd344d3f8dc7b62994f3.nq.gz
    ├── 0677d4dded7bb871b3d4f03671cf087d0bf2dc39.nq.gz
    ├── 070457cbfacb1587d96eabaad5f82cc2cdeb5dc7.nq.gz
    ├── 074612be6735bfdef20c5274f7cd5738826f8b92.nq.gz
    ├── 0815b86c13c384f93a86e24c48d26260e3c59270.nq.gz
    ├── 097c59aec9d702c74768ffa9d591f7a6adb1222d.nq.gz
    ├── 09f8d459cb2e1492d656d59e9fd28757e5a740d3.nq.gz
    ├── 0b8f7ab0db49ad689682ab2b677f40e4fbf66b8f.nq.gz
    ├── 0bb014f1863ec567457dea37702114d7f6c9a002.nq.gz
    ├── 0bcc5bda30a3bfedf37d0a71afeb29da44c3ecec.nq.gz
    ├── 0bcd7b4dbdf5430c837d317a7d67569b30cd3c93.nq.gz
    ├── 0c3f24a303c813bd81202dfb478b41d81b8f4cce.nq.gz
    ├── 0ce01786b097395691683643aa49a99b98488cc1.nq.gz
    ├── 0ec763e47b24714548f9c7da562513fe6ed1e0e7.nq.gz
    ├── 0fdab8364105ac97042c1bea67ae2e8817420164.nq.gz
    ├── 1115b4ce20d471ee8af24c96d1417bd141a70f8f.nq.gz
    ├── 11983771c5a75fa738a5946951bcf9318d665947.nq.gz
    ├── 12e45bbc2dfb9b81e5f41a1af5367a1fc7c578a2.nq.gz
    ├── 1302af97435ad5b730676521ead3f31c7f6dd08b.nq.gz
    ├── 131d0a9b168c42c9d40d8a3c75f6c4304db366b9.nq.gz
    ├── 1511225ca42ecd54ffa44ee540614b8157581c6f.nq.gz
    ├── 153aa51b01e53faac4d9dde2f6bee9c811ff8701.nq.gz
    ├── 15b4258231b8dad01d6d64a076e1f50025f18c37.nq.gz
    ├── 1740d3706ade8e389ab2022fadde9be972c14078.nq.gz
    ├── 179e49355e86d5291faa237474b198eabda29b73.nq.gz
    ├── 180f2d5595793db6e8349d9675836a38dfd6d405.nq.gz
    ├── 182c77e6255507e78fb789f4ba3e8587f656891a.nq.gz
    ├── 189576a5967c2e8a94fd16958f22bcf0574f5599.nq.gz
    ├── 19de13ac3f31ee49b622661d6e1ea0f83f4e8877.nq.gz
    ├── 1b6ad87f213446000c35dc837566e151d1b00721.nq.gz
    ├── 1c5e1a0e6612227100476e0e9367884d55bdd30e.nq.gz
    ├── 1dcbdc880c841c954ddaa4318162e25415fbac9d.nq.gz
    ├── 1f919d5f4c86f4f145dbde029f1417cf4dcb1a85.nq.gz
    ├── 1ff46d87a2d064d5ae11d1216c46d9f12c52240a.nq.gz
    ├── 204e7b8e9973197cbc929f3eecc418e86a68b512.nq.gz
    ├── 212af149fe7a2133ea9f97822e59cdc1f992f21c.nq.gz
    ├── 22160d7ba65bccacf6f5e8eb006a656428d9d199.nq.gz
    ├── 2350164cd6660661736ec5ec4c96d3502a3aa75a.nq.gz
    ├── 23bf47b852e1c04a4caf2f411f67a8d95ab2518c.nq.gz
    ├── 245612a654246f5bbb9f213535096d94bdea5129.nq.gz
    ├── 24e2d252ad1a8bba1a273c787141b80c75feb5ee.nq.gz
    ├── 254e7a37d38742c55383af1dfb2d8258052d795e.nq.gz
    ├── 2911795fa6aee8a63c363345856bd541553a973b.nq.gz
    ├── 294e040394ea579d5e4d8fe554d7885a88d92504.nq.gz
    ├── 29697d89ca4d160364615467aca968e137a896ce.nq.gz
    ├── 29e9103308b0af6377c27ecd70346c93fabf46f1.nq.gz
    ├── 2a333c69746aa35db9da9b396f25fd377840835b.nq.gz
    ├── 2a3941183aa8e0f55e123d52695caea12e95ef43.nq.gz
    ├── 2a72e29cd996121ba3efb86f2a0b13067908abe9.nq.gz
    ├── 2a7a8f983c9e762913f4868ab33ae535e8fc5fba.nq.gz
    ├── 2c0a89d63687ccd0b8ecbd6276d363181db0a4b9.nq.gz
    ├── 2c2ef3cc2f37987591f6f55d8bfa0c7b26f21547.nq.gz
    ├── 2c71b386f9443c80441494abe7d9b6986442b011.nq.gz
    ├── 2c7f4ede8f91d153ceef72c60e17ac58ed8a9fa0.nq.gz
    ├── 2c8b66d4419a44b3f5d5046c6086ecd86166aaa2.nq.gz
    ├── 2ca41fbcafae2409ad230f5cca9a89e06b38b297.nq.gz
    ├── 2cf339de26e5302611bda9bb9c713885d3b20c59.nq.gz
    ├── 2d03c07e0593e1915109fe650bee29de69a2c387.nq.gz
    ├── 2effbb0e7efc2a6b423c882addc7d895f0939a80.nq.gz
    ├── 30956f0877ce3922272367f8dbbf81d4d2dd2392.nq.gz
    ├── 30e93d81d1fbc63677184594b935ffe4a80f1977.nq.gz
    ├── 32e843344a41dc8b4149eb450fa0085f939d858f.nq.gz
    ├── 33a1f7f1401d6a70ab47c4e35a4576cc6a605d33.nq.gz
    ├── 33f016aca97043eaef67340e3421d53ae6e48a4e.nq.gz
    ├── 35752ae01f84b8a659075e8f768ac121aef102e7.nq.gz
    ├── 35e624c18665ebcb6677ac13659872a35a9154ae.nq.gz
    ├── 367fb298ac26f6a1c470949e4fa7b034c09703cf.nq.gz
    ├── 36b1915baa5797dcd919156607a926b468a87d43.nq.gz
    ├── 36cbdd2ab508cf1ba1bd8d616d343de12761076f.nq.gz
    ├── 37d392e07e6a77ddd39a05603ad0698c52c859cc.nq.gz
    ├── 39980a888f15323d38783ee9f9ec637a6a0676ac.nq.gz
    ├── 3a75231a1319485975db77de72016ae7fa985716.nq.gz
    ├── 3a8640e927d9d8d29e52b8ee45d9ae2832621012.nq.gz
    ├── 3aedc1c00292624cdc51e9867852787bf552ffc0.nq.gz
    ├── 3c0dbb5d077eb9175c7807d76da7b37c5c2bf37e.nq.gz
    ├── 3d3366e7dc5a221dae8c50e06fa171e1ec6b255b.nq.gz
    ├── 3ece36ef7aa9b9f2df32c30d0aadbb22845d389d.nq.gz
    ├── 3fa506a41adbbf95df57c7a03ea66112ea911e0d.nq.gz
    ├── 3fccd6cf7b2929e974fff298062216fcca0a2b8a.nq.gz
    ├── 42d3207f300761b9dfcd5e9d1b9897c07172a412.nq.gz
    ├── 42fa45f2eb65883f91c7255c48ffcdb47d401385.nq.gz
    ├── 4341b92860dd1e556c5db0642148705907d460ca.nq.gz
    ├── 43b8d330663d13b7f14248d3e2cf049512bfcbb4.nq.gz
    ├── 457f5ac13ff6c5dfbbab52dcfd243ef648cb96b7.nq.gz
    ├── 46e3dfffbd253b091469f42f8f9e6c4aa90ef355.nq.gz
    ├── 48182ffb53a7a0391af9e4c5e1477d7e4181f70f.nq.gz
    ├── 49a63759b59624db7f2fea7d1213eaa9ac26203c.nq.gz
    ├── 4a32153d5aeeaf08fef5dadab70702a053787ae8.nq.gz
    ├── 4a3c3604b20556dbfd748d12ce25a2254e0270a6.nq.gz
    ├── 4a7f996b70fa191f3bc0cc55db29baf932229ac2.nq.gz
    ├── 4af84c0d29819ba14d8cb0ce922c6fc0540b0f35.nq.gz
    ├── 4b1aca1989685c72c6aff5cad28b3f0fcc50d144.nq.gz
    ├── 4b79662af834db6b9c4747532da577782dae5e01.nq.gz
    ├── 4c61b0ac1dede90fb65712c98b44fd801ac015fc.nq.gz
    ├── 4e268f96c3bc29e6480f8f399b2f963826ede6a5.nq.gz
    ├── 4f725dfa2251e93783dbe32438612faeb4ce9ba2.nq.gz
    ├── 504c9c5c6e9dd5d42e20193132506f2611556e47.nq.gz
    ├── 508b65505683165169a979b4ba9d9674b2faf05d.nq.gz
    ├── 50fbc1f5d4af3d9b72645f39eae8a42604ea5c27.nq.gz
    ├── 510379e8e24fff41dddff7d1df66eb78815861fe.nq.gz
    ├── 510426c6a917aae54dca2ced0c746af5a9513247.nq.gz
    ├── 5166ba9d01fd529a1a55c81ea62e4be8cfca886d.nq.gz
    ├── 51e3cac241b658c05e16b0c17662e6166cdcc9b8.nq.gz
    ├── 520747f363e0c7b6e99f388781126d2d0840b7c5.nq.gz
    ├── 523630c647d2016f86cd1488c2e60fb3846c8dad.nq.gz
    ├── 526c270b079f12b91745b802d9cf26d8f3445058.nq.gz
    ├── 53aaede576fac4d1a6ec78cbbce48115ff9ee9bc.nq.gz
    ├── 541c9c56445196c7c5037d0ff3b632223ba9654b.nq.gz
    ├── 54e45488288601fe332aba10b8d7479eb385fea8.nq.gz
    ├── 56facd4658c77d0335a2ba8efc7b7393361d668e.nq.gz
    ├── 5796201015147573c7ef5cf99c1a344251ce8c67.nq.gz
    ├── 579f5eb104588d3e7bb52e0259be8b08dd0f5424.nq.gz
    ├── 57acb16c4ac10ea7e13f2ee59fc340a1f588b046.nq.gz
    ├── 57e1496311f938b812832f32da189ec9ca164d8b.nq.gz
    ├── 58559276c73e7392b647a49ca652aff881a1fb46.nq.gz
    ├── 5884033d99ab2f0dbf4dbcbc3cde860d738f822b.nq.gz
    ├── 595a4ebb7c1977a9b0c7a742e40ab1efd27bd630.nq.gz
    ├── 5a5df5f80a5633affb712b640a7e4cb8d020610e.nq.gz
    ├── 5a6048b3b3787ed8414442bc382183df9cede647.nq.gz
    ├── 5a72e8f417131c733067b125eae7adba8d7d5366.nq.gz
    ├── 5b8658761ae19b2c8b40c5fc81b2112db825cb96.nq.gz
    ├── 5bbb56b060cf11cd496ada812a4ab33880c695e0.nq.gz
    ├── 5c26c0a8ed4f6f3e695dfacf42b370c7d62b84ca.nq.gz
    ├── 5d5d348ad6d846ef26be6d1431d0c9544edc7abf.nq.gz
    ├── 5d8b5bbea00ef46fb956a5ff816556e3c536ae3f.nq.gz
    ├── 5df1012acd430e3236b063c288fd00bf844bc9a2.nq.gz
    ├── 601077d9eedb754b75fbd5a0b5cdd4d7b554f7af.nq.gz
    ├── 604778339da9289ecfbcbbd2b360c9cb2b3147aa.nq.gz
    ├── 619976c853b8547322a4b4d5d5408b2aea83a41b.nq.gz
    ├── 61d5edd217e9b6a26eefb12e87a18e1b05cd311c.nq.gz
    ├── 620ff8cc7b0b4685d5ea68a05956cf8575322b84.nq.gz
    ├── 624ccc7850a52e10d08ae4e8afede7de0fa3be97.nq.gz
    ├── 630dddea8f434199b431c023b05aa5c39dcd9553.nq.gz
    ├── 63a590d9a4e09dadc186121f9a346ca5c93a1b96.nq.gz
    ├── 64144e8dcf07404847e96a0ee34922af9432730e.nq.gz
    ├── 650242637124dbd701a5695a2c686fc28d73ac4c.nq.gz
    ├── 65141170d4b682e7a31a24bc2a6baea015c6bfa7.nq.gz
    ├── 6537dc5a825ac36a03347749cf8644540bb72c92.nq.gz
    ├── 65ce903019452742946570f2e058132efc8c5edc.nq.gz
    ├── 664abac0450d08139f0e0a0e7e2d857779df2f10.nq.gz
    ├── 664dc41f51b8f8698804353ac6be591d5e1dcc3a.nq.gz
    ├── 6677db08c0dcd87f7570a3249f61cc3eabe0532a.nq.gz
    ├── 6ae4a710e4e7ff7f3f2067b593ef9a90be88bb7e.nq.gz
    ├── 6bda7755a25365bf10ad4a90e3d7cd9a90c27a40.nq.gz
    ├── 6bf2cbe6b49a67b8b9947f46d60022148baebc55.nq.gz
    ├── 6cac6874c3a9ce5314375530a1439205d47615eb.nq.gz
    ├── 6d4d14a6268b8e9ca41a4fc25e15a6e6455e0ee1.nq.gz
    ├── 6eabaf5499334801be91d1fe45e0bf1b7fd3a624.nq.gz
    ├── 6ecfeaab45e0cb972aa2bddfd9da8e4052853b88.nq.gz
    ├── 7032c1d1f0963b4656ac6da4d651c83d23cbfa37.nq.gz
    ├── 71f8cf2843c7c263d4b6ddf1de36bc3a5ee59d44.nq.gz
    ├── 721fef2a73b61f9ab944c02b5c57d2f2513ed4bc.nq.gz
    ├── 728655a4c81bd8ba766bff2e2b2e7b58fc7775a8.nq.gz
    ├── 72d5e0757ce30c090a82e43050cb54d6d2a47083.nq.gz
    ├── 72ddca97f02fe7664fca779ef344506691852aa2.nq.gz
    ├── 73db196b17cba5919d42222f7582e4a82f5a2a59.nq.gz
    ├── 756910928a84b41c0bc4c434db6da8a08623d833.nq.gz
    ├── 76b6dea1e9902bcebfd3988d697c466a47954561.nq.gz
    ├── 77523d633cf019af917d3757e2dd011a2e5ccde3.nq.gz
    ├── 785beeed4766b8284c8e104a2885fc2110702ebb.nq.gz
    ├── 78d0961c518b60c3915b144113c1f38a9fdba569.nq.gz
    ├── 79bd80ca6f80d648ecf8593123a90f1bf94ee99b.nq.gz
    ├── 79e6169096d2f65869aed1402ce601eb9bd91129.nq.gz
    ├── 7a48eb70a261dfaeec051c6dea4d2cc1171a88e1.nq.gz
    ├── 7b78c6c46cf43d16e317867eeac089b1d192562b.nq.gz
    ├── 7cfecb2f3560535874281c8f75ea3c3474139aee.nq.gz
    ├── 7f47c61f4416618bb9b08179b65c83e15e10ccc6.nq.gz
    ├── 801218a4896e881de81d88e992d2ddb90c984d6f.nq.gz
    ├── 80859863a653ee7370988e7251e785cad1550bb9.nq.gz
    ├── 81247ecc17b59b0a4987b7d560dfb65724db7b86.nq.gz
    ├── 826dc1cf2f58051b25586ee09d5b6ec3eadc9e42.nq.gz
    ├── 83106904a185648aec4fa0433a136e139d43bcf1.nq.gz
    ├── 84de1d568376710b4998778595f5512148eb16ea.nq.gz
    ├── 86b47606c5e3d07bb18e5793e47c6dae3672ed3e.nq.gz
    ├── 86c28660052ce773351b1cbb9a4e7a72d9ab8cd1.nq.gz
    ├── 8754ae197eeaa304c91c1b2cbc10d251ed9c67f4.nq.gz
    ├── 8866db267815702192842d7360a9f4ebae5a647f.nq.gz
    ├── 8a114f5a87d340e55a2397186d35d30811fa4cbf.nq.gz
    ├── 8a2af49f4895012154940ca6ca64086e60a0c9d0.nq.gz
    ├── 8ae55dc6bf429471b430ed929f4c2e3da01afc4e.nq.gz
    ├── 8b0cb5994cd8257f9beda015ea57cf641eb92f16.nq.gz
    ├── 8bd18b5b5612d355d770821077e563a263bd55e4.nq.gz
    ├── 8cadd2a21f0200e0ea762b14fe9e807f4f1f00ae.nq.gz
    ├── 8dee0ede96152af537dbc3cb4e25999cdb02d0f2.nq.gz
    └── 8e234fdc516d081352e8a0926e178da3b4914cba.nq.gz

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

[facebookresearch/fairscale](https://github.com/facebookresearch/fairscale)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
