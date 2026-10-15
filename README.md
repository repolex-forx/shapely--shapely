# Repolex Knowledge Graph of shapely/shapely

RDF knowledge graph data for [shapely/shapely](https://github.com/shapely/shapely), parsed by [repolex](https://repolex.ai).

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
rlex download shapely/shapely
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 737cc734ca238216ddb29b933e24b710e82765c7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 737cc734ca238216ddb29b933e24b710e82765c7
│           └── chunk-001.nq.gz
└── blob
    ├── 005b2b8ecb88f5be4c72f63ce5737bc8a9bd9a68.nq.gz
    ├── 02b3bf7a5cedcba26849b97d0f93a8dde24d4ef1.nq.gz
    ├── 02d76a8e27d15b84374b7fb79af6d56b5fe130be.nq.gz
    ├── 045ad37553860855cd359e9addfafd7e92e09ad7.nq.gz
    ├── 064f8ec735a64e56e3af6264b244843ac7706094.nq.gz
    ├── 06ccbc533d35de00e17e90e610665d11dd93d71a.nq.gz
    ├── 0709939862e4b2e924023ce8fd9a7fda60484152.nq.gz
    ├── 0839035bd1c44e254b48c18018a51462fdb9becd.nq.gz
    ├── 0a2855c8ec54805e60ae06b5c0ed8c40673a43cb.nq.gz
    ├── 0b9bc7018d527834cda52eed490d3f6a2fba3c53.nq.gz
    ├── 0ba8ba7182f2fa504351424e7b6e2e4dbde793dc.nq.gz
    ├── 0d043e17b2a1d1142b4e1123bc6a3ec95911e2d8.nq.gz
    ├── 0d22664d232d1e1e5d197d064ab83e5d9b42bde3.nq.gz
    ├── 0e596605612faecfbb56afcb0ea49eb94efd3334.nq.gz
    ├── 1037839fa57be5cc7217a7e378436c4849dc5b12.nq.gz
    ├── 10751b5334977f3ef6955db0585e7f18f6f83a94.nq.gz
    ├── 113200570de0c9a16e1479810170406129f1e5a8.nq.gz
    ├── 14404da7baf355038afc3cc66633ce12190ddc76.nq.gz
    ├── 146f451d74879306675b89d6a3c4860bde816b60.nq.gz
    ├── 15c1ca7dfbaca72ef4f6df9f7ba22b12645f257a.nq.gz
    ├── 17e6373e2db6d612adab86693487752313eba127.nq.gz
    ├── 17e9a60ea0394f443790233a986a03c4b1cc7ee5.nq.gz
    ├── 17f3c5bd94b62ef8edfc5e8314ffc102c1d4ea9e.nq.gz
    ├── 18e34c2f5355ec74242ae07ef790513466f382a5.nq.gz
    ├── 1ba41c521752d0eab299541b187e1b0446983a73.nq.gz
    ├── 1bc5d1abb0362002d2e348ecec782ce6da517ed3.nq.gz
    ├── 1c21fbca08057f966e34a14623ea09f8c90665a6.nq.gz
    ├── 1c684a28c03795b788e34cafb79f840a1917821e.nq.gz
    ├── 1cce76a3f16774df44dcd18347a77ce4e7852b6a.nq.gz
    ├── 1d46540ef353439578daa4b2ad61676f49952f50.nq.gz
    ├── 1dc7ae6d463e11fe5f5e292f9a6e2ccf0bebb348.nq.gz
    ├── 1e730932245342ab35975f1a6613b3d53edd11b5.nq.gz
    ├── 1fe16aba2837103f540279c452b58d088c07942f.nq.gz
    ├── 21d7cbfd6a5d146fbd40d606880409120e8086f8.nq.gz
    ├── 22be7f81d61e4ed0589b88ecd63c93b9fc54dd84.nq.gz
    ├── 231c75aa4fb15d442fe1a09bfa5452ae66b61f75.nq.gz
    ├── 23273a7c226939b7f1408f4d06403be1d9e470ec.nq.gz
    ├── 235488b2821cc14bf5537404bb3815f6b67055de.nq.gz
    ├── 26ae927c28ca7911a45d4870feaa2675ae8e8781.nq.gz
    ├── 289feac2d9f1c3a5ae2361e5961fa026bb54f603.nq.gz
    ├── 28ae504352a2b23fb9aabec458993acc9e529229.nq.gz
    ├── 2aaef71a6c0d950b7ec408e90b357d43f3aefe7d.nq.gz
    ├── 2d616d380f99d35515b9d6396e06d85acc40060a.nq.gz
    ├── 2e489fc6316110aeebf347483a42f8e61ca96018.nq.gz
    ├── 2f21b2211821c65e75c93b1e4f3d65707bb73f24.nq.gz
    ├── 2f5b4895eb0eab91c6fd90fde9bbac3318b1c153.nq.gz
    ├── 2f5dbbad0edd5ca2e009a6b06fe65f5cc40ef98c.nq.gz
    ├── 310fb33ef16b310eaaf3dc4d5e383ca05e057447.nq.gz
    ├── 31f60d7a3e02ad23552f0dfce60bb6a8754666d2.nq.gz
    ├── 323b2772726dcd5401258e02c929d74031f49bf7.nq.gz
    ├── 326a8d694cf22eca7b873df17f85e1843f1ababf.nq.gz
    ├── 32aae55aa6da0ba08d4cec289940c4dd35a4999b.nq.gz
    ├── 34a3b8b3c865fdbef9ad160f4c8c15f0fd246895.nq.gz
    ├── 355af1e43e28f43872461c1b996aa6d1ea3f54eb.nq.gz
    ├── 356f462907a7d5bb32b2c3b2b5d2eb97eee86c83.nq.gz
    ├── 3599f9b20109df9ab0f83014b0dc24d65cf644df.nq.gz
    ├── 3667365ef44c46a736ee98676265c8cec71bcbe4.nq.gz
    ├── 372411cbb2bc6368db25f7ee6267affb3cd3ba13.nq.gz
    ├── 375d04dea3e8b30ebeeb1e99641d5615de9c455c.nq.gz
    ├── 37c00448976dda597394595c7e6de56ecdcf9d96.nq.gz
    ├── 3974ab69e06dee353bff4d4292410839bf37c92b.nq.gz
    ├── 3a50fd61ea0e076e0f3de7cf52ade4a48969ada5.nq.gz
    ├── 3a78b32f9c0cce1d808ab2c1deaf3421b143c5da.nq.gz
    ├── 3ae161d7aeae9fabcdd250a3783d2718316d2ffe.nq.gz
    ├── 3bb78516842114d7c66aab77fbceaf683369e68d.nq.gz
    ├── 3bd2f10663be50f77512cb1fd81fec8b1906378e.nq.gz
    ├── 3cda7b0ef45553dcfb53dcc51ef103e5e74c419a.nq.gz
    ├── 3cdf3177171f026b1167aeca82280a268d8b9731.nq.gz
    ├── 3d7b96d72b51c99ae14104147de18bc8b5545454.nq.gz
    ├── 40d5a536323587d83fefd6d4e1798ee9736eff25.nq.gz
    ├── 41c9628f421518b53ff3347ed608385af02ba9b7.nq.gz
    ├── 42e5b78ca090bd073c90a7d8f7f3b8aa692e4858.nq.gz
    ├── 4305032a2f204280c239ae55e287b33320d301bd.nq.gz
    ├── 43322e30b82ec2d116846b91cac723f35f34d96b.nq.gz
    ├── 43615ab412819f7ba53417a56f6beb7e0a362045.nq.gz
    ├── 46afa8097064b4fccf823f12482e41df51ca4d0a.nq.gz
    ├── 475410b01fad3c2b3ce478b4eb59cd1b38f15e09.nq.gz
    ├── 47a608b7c80b2f1708f0ac99cb19edafa2d23f52.nq.gz
    ├── 47d2a8b7f68bf83c2e03ea14fe7da0821f778b60.nq.gz
    ├── 47e5c015b9aa6de91b71d942316adc16a4e7e86b.nq.gz
    ├── 47fb98d8d6159fdb7cacbeb3eb3140362be77ef8.nq.gz
    ├── 48f058d871d9c26aac99e25388afb06394592ea5.nq.gz
    ├── 49462c2e11bf5d1360560cc84c68694ff70eef68.nq.gz
    ├── 4cc285a3f346d51fa5a584b707f8ba17aea167a8.nq.gz
    ├── 4f1a2d8bc0ec92629bb3679cb6409b138a5fa1b6.nq.gz
    ├── 4f1a634f5920613b3172008a8e3a12a86f85a32a.nq.gz
    ├── 4fccb4922ec164765767fb5cd5db64854c017509.nq.gz
    ├── 5008cc35b4c5b3c905ed8d88850bf9510ec68b25.nq.gz
    ├── 501aba48b8a0176054312659433e56fde292b476.nq.gz
    ├── 50af72c91e0ed85f36d072f249757e0d727f86fe.nq.gz
    ├── 51ef63d6490f9dcab60046b5cbc8d795d9367952.nq.gz
    ├── 53c79b215569f0248947183d62209d82b299ceb3.nq.gz
    ├── 56164b78cb3ce78825aeb571c02be379f42dcf8c.nq.gz
    ├── 57545b9b4cce71c8bdf4170d28b7d6d92fb2164f.nq.gz
    ├── 582a97e936e89bf32baea5116bc8f4e160f112df.nq.gz
    ├── 59dc043540f6808e878af7ebedd9b03aa126e751.nq.gz
    ├── 5a9cf55ead792ae8cf694d0724108aab26f719fd.nq.gz
    ├── 5bb14164ef7bfc1434d777262b68e23d9aebcba7.nq.gz
    ├── 5c1c7336fd8d2c122ee6d543fbc80b5c965128b4.nq.gz
    ├── 5c912f5190fb7d1f388374b33c9a2a09915ffb55.nq.gz
    ├── 5d1898ef396070e810b5a3db372a3733f5de3066.nq.gz
    ├── 5e6d21271b4d8fbac1396c0ff7d79527614950ca.nq.gz
    ├── 5e86c313518f9ce3eacae5673312a5e1c1d9587a.nq.gz
    ├── 5eaa855671b6f4a7d8c71672d0b7477ea503af32.nq.gz
    ├── 5f6ad2f72c6db0578d29b2e0b49ab8ce7df2ae79.nq.gz
    ├── 60e5a2e4173cf85991c4e247b7a44efaa7233073.nq.gz
    ├── 61416f77fcef14eca875d7cd94c40ffba877652d.nq.gz
    ├── 6237250e2924d74d897dfe960aeac807b43fe570.nq.gz
    ├── 637e66ab930230ec398596d87ba2e46073f69ea8.nq.gz
    ├── 63b5cd0aa2c6b11a9174bffac8484ee85c03b1be.nq.gz
    ├── 64dab2da4222143d354c0eda15ed5dc56ea1fcda.nq.gz
    ├── 66ca1e4a390bf196627b59626e4f7a876e8edd16.nq.gz
    ├── 67e36d6a2b8a680c2dbc69e34730c43cf65965d0.nq.gz
    ├── 68313d1dd73434a42da04a7659ccbb230b4ed541.nq.gz
    ├── 6861dfce35d7c2f0194a111387e3c92942851fd7.nq.gz
    ├── 688f26fe99ee88eda98fb25d1351dd269e0f9b82.nq.gz
    ├── 68906495a53569a716ecddd92d512b45926a7f45.nq.gz
    ├── 6970bd804e9e435a86aad36432315a62948a2b41.nq.gz
    ├── 6adbff5610f23ce97baaa5b735a1695661853c1a.nq.gz
    ├── 6aea44ffdbcc5e8b2299129145b4c89994495e17.nq.gz
    ├── 6d1590751885de75550b5f413a9dd008dd51a6ef.nq.gz
    ├── 6fdc83a57a710544024d6f89810ee6911ea8c27c.nq.gz
    ├── 736e974f835067e7e00fa83a1ec508f8304103c6.nq.gz
    ├── 7419f5e6d9a67d5ccfc29010ca56ee2db088c35c.nq.gz
    ├── 76519cc0d053a7a74d9eda1b31a22c8bcb6ec85f.nq.gz
    ├── 78a357999c8755075d96bb5c8bcb7bd832ba517c.nq.gz
    ├── 78a4175ee4baaba8030fe127083fb29cbb8fdfa7.nq.gz
    ├── 7980174cea394c679914d8edaca7bdc1675a6e03.nq.gz
    ├── 7ab3d0077b04691871024041231a059bd66a029d.nq.gz
    ├── 7b7a4081c58020193c2b84030bcb76aa0c68e1af.nq.gz
    ├── 7bc19c9521b67f93f66087fcbeab574d5019d344.nq.gz
    ├── 7da01b7d32938db774387bd3bd77a5d2313cae3a.nq.gz
    ├── 7e4ed7b2a90235c8cbcc446a115ab61eee16d9c6.nq.gz
    ├── 7f2e5240b2916ccf2efc3f89b34f44e1ecf3db62.nq.gz
    ├── 8103f240c85f386b36727a45da92a93da01c07f6.nq.gz
    ├── 829943ba757b689bcb82e6fbc16ad47d94776e70.nq.gz
    ├── 83f859d681775434caccf5a4372a7fb3536268a4.nq.gz
    ├── 83fd8b8ac1099a58b2a519e045455ddb031a8d13.nq.gz
    ├── 84071217919f5b04073dc8a7b50db33abf198f87.nq.gz
    ├── 845b50c5ae5fdcbc415103c24d54283434f09c8a.nq.gz
    ├── 8557524ab18fd39f3c0d105fddc17e20bcee1a06.nq.gz
    ├── 85850d361ef6d9844d6e075a170aac96c73ccb23.nq.gz
    ├── 87ac30178965c14b798005922fbe3ccc855eed7c.nq.gz
    ├── 8835d500773217587df51fbd5b0f18544c2d6bfa.nq.gz
    ├── 893a92009d65e845dc8975c92f467d4436130bc5.nq.gz
    ├── 8976caa35a84273913b356566eddb3eab07a624e.nq.gz
    ├── 8ae478dc6b48f64822c99e16ec5c481267e372ec.nq.gz
    ├── 8b8b732f6c205ab22b1e10dd4137ee985bce6491.nq.gz
    ├── 8b99bb9bcb492437b0ee7737ffaf776f03f3c413.nq.gz
    ├── 8cb06166c8c6155cfc4d2d2c9d362486ba2bf2dc.nq.gz
    ├── 8da19e018bd825b1be2c56e30123452194f77f8c.nq.gz
    ├── 8f3f85016c5b6a5bbcfd90c26366732178cbf77a.nq.gz
    ├── 8faf9230f6460f4ab345d320688d3c7647ce7746.nq.gz
    ├── 91360dab7bfb4d63261b050b0f8d49ba0cce547e.nq.gz
    ├── 91477a04e9ca759a04152a866ceafa0a145fb109.nq.gz
    ├── 91dab3aefb75c22e8d812619027913458750dae0.nq.gz
    ├── 92a55eab9beb307d5f77535aa08d6cbd373001a7.nq.gz
    ├── 9313fba443a0a0ba32d0a22475aff1816d593305.nq.gz
    ├── 94d01d368246b2ca994dded86359f74a556255c3.nq.gz
    ├── 957c92848e85a861140ed1d60f031ef7f22b5a4b.nq.gz
    ├── 95989b7c56c1d97e7fb1b4695596e2b784a02016.nq.gz
    ├── 96360a97065cb0b79eec5ac172b4ecb1700df077.nq.gz
    ├── 96fa545067f9b8d0a7ac41d28f752211101abbf9.nq.gz
    ├── 97095b2b07cea231abf49e423657644729f8d182.nq.gz
    ├── 971cc3ddbb5406f46f2df1d9ab59b903e5c7dd32.nq.gz
    ├── 98cb42733132b6444da1c9841a11b4a1e210924f.nq.gz
    ├── 9995c89adb5946f95382b1cd1ee55defca43b87f.nq.gz
    ├── 9b47e948cf5e77ff96f58a9712561df527903d9a.nq.gz
    ├── 9c0cbd7b1bfe41876639fb81c735614168a9a645.nq.gz
    ├── 9c1d805901f3f8ba31a20a94647871d27638ec8a.nq.gz
    ├── 9c31d053c82fcf5cced0c542dc09e980d08d4d4e.nq.gz
    ├── 9da226239b31da471bddf0850ebb3c116af1878e.nq.gz
    ├── 9ec8663c7061904069b0a5d41f24e1d31619260c.nq.gz
    ├── 9edc57b0e9ea68647eb62ee86a9877a362490ec9.nq.gz
    ├── a05cb0c4f3985036578ba3fcd267cd50313588f2.nq.gz
    ├── a08f3f7013c760e5725742e530fb4dc472a8623d.nq.gz
    ├── a0dc3d09360761082ba730d7b74d85883e70314b.nq.gz
    ├── a1180405ceb5601231fc5b5e67ffae4000161711.nq.gz
    ├── a14d3cbb83be42ef0ca2dc63f1f7e3a4dc01141f.nq.gz
    ├── a2caff758951be30b5d42ba7be7592ecfebec950.nq.gz
    ├── a37de85a5fee77b2b2d333f094b61b3e5513ed04.nq.gz
    ├── a4a44dd651755343812f860c8c009cf43df39e2b.nq.gz
    ├── a5aa7e15c8aa8052ed680c36c97005678fa909eb.nq.gz
    ├── a811448e3ef9ebbfe0b46f8d1e0430f4afdbe08b.nq.gz
    ├── a849d9663106ff4aed3b70d612db8de5662d052d.nq.gz
    ├── a85ec6fa4b122d07db1c669e3b37372c9d32c79d.nq.gz
    ├── a9f74b494db8bdae37aca3b0c7997aa9d6cbfa75.nq.gz
    ├── a9f824093e37fa8538fe55bca23c76e973b55125.nq.gz
    ├── aa4a53f356fb88f8e160b41d22bf7bbe018179a6.nq.gz
    ├── ab35d707b5a9b855649c2c4df6e8094b877be9d3.nq.gz
    ├── ac27a84869a2cb5b416c12fc1fcf57aa6f626958.nq.gz
    ├── acaa99e38aaa8b3f07dec5ffdccc5a9806912cbb.nq.gz
    ├── acb7ae5b0489934dd61ff2538b46981db21fdefb.nq.gz
    ├── ae9028f5193e2c4fc002403c3e8a73e02f32ff5c.nq.gz
    ├── af6a1e60a7effdc9b506898e57c3ea81c5457a8c.nq.gz
    ├── aff917d3d41b94a77053cbe15a3653bf74ad6ddb.nq.gz
    ├── b091e0a23e2e76537c13fdc2a2967d8e18ce958f.nq.gz
    └── b0dde298d90b770aea01b4878845b25057194ef6.nq.gz

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

[shapely/shapely](https://github.com/shapely/shapely)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
