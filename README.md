# Repolex Knowledge Graph of kulshekhar/ts-jest

RDF knowledge graph data for [kulshekhar/ts-jest](https://github.com/kulshekhar/ts-jest), parsed by [repolex](https://repolex.ai).

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
lexq download kulshekhar/ts-jest
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bac2e77231418c35cb9b9946d7d871c0ee2322a1
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── bac2e77231418c35cb9b9946d7d871c0ee2322a1.nq.gz
│   └── repolex
│       └── bac2e77231418c35cb9b9946d7d871c0ee2322a1
│           └── chunk-001.nq.gz
└── blob
    ├── 01a46301381f70ba58999985c0e301a558b68df8.nq.gz
    ├── 021cf2d9afa5307c9480f885d17c999d85579c0e.nq.gz
    ├── 034c556074b56850d84a96045660a3690473e2b9.nq.gz
    ├── 03c3a2bc0d94a9a5e8c5d9182e42385206934e42.nq.gz
    ├── 04027505480e5d7727c684d8bad84f19965849ff.nq.gz
    ├── 0508cd7597233fc8e13283cef028d5eba01b3119.nq.gz
    ├── 053438f43cf57ff8d6e348ae7e34319ec9904f6b.nq.gz
    ├── 06731f36cc9d01923720b85aa71f754687084a0f.nq.gz
    ├── 070cf81530d2a327bbb67267f1d5d56309fac230.nq.gz
    ├── 07649fc13c38bd18a75c395894c9e22c43e0493d.nq.gz
    ├── 0872a70b32d5d054eb6ad1d0ac4085e251aa70c7.nq.gz
    ├── 089ae151335a5ebc2b44cc65c2478c3519efb319.nq.gz
    ├── 093a24d9464f9652015d4cf9d5bca0014f81627e.nq.gz
    ├── 0969e38fa692edd34e681d204df81e6fb6b8dab5.nq.gz
    ├── 0a6cd765d86b01b794cc79ea8378a1c75c4065fa.nq.gz
    ├── 0bc21b799ed280b85ef3f3159c2a961a977e502c.nq.gz
    ├── 0d6babeddbdbc9d9ac5bd4d57004229d22dbd864.nq.gz
    ├── 0dc9c5bf3fd81508e91ce582afde9e47267bb8dc.nq.gz
    ├── 0fa042b41023105e3f23ecf3ffd74f8dc5fac647.nq.gz
    ├── 0febcabd97ba65d4ca080478039e4f01c85437ff.nq.gz
    ├── 102e2d287745e3602ee9bd668bf7f34e9ceb876c.nq.gz
    ├── 1168ef4137b5a93d3ae15fdb94d6ab1c0d6a90b4.nq.gz
    ├── 11b42d5158d1da113a8d38252f184b006b5fadf2.nq.gz
    ├── 11ef1c9dadd73eb9a33244d68d8871ad262855b8.nq.gz
    ├── 11f02fe2a0061d6e6e1f271b21da95423b448b32.nq.gz
    ├── 11f95f0b9baffd5dc7a209b174668ed322902263.nq.gz
    ├── 127e66e99478e1a199b7f8b5be5df8134ec51fe7.nq.gz
    ├── 12e122ece3c6ece6d7adce2ad2d08d347dd51871.nq.gz
    ├── 131d33e207084267820f1013439caa2bc2e395d4.nq.gz
    ├── 1320eaaf28e775fac556fc16590599efae517435.nq.gz
    ├── 133ac185513565a6206f1463fd22fe0bdceb9f13.nq.gz
    ├── 14a5a95adf9d5d5ce34db95ad24748cd3f5aad5f.nq.gz
    ├── 14f2cf96e96836392c9fa52e672cd08508bca692.nq.gz
    ├── 152f7c27eb421024368a4e802f858d49973e697e.nq.gz
    ├── 15ca5de1f70deb0db64b52b0d5eac34922ced122.nq.gz
    ├── 167adb2aa2600f32b9f2cd03eb34813ae8723a97.nq.gz
    ├── 169f7e02e50a0c598ca65914230f9b590a3d56d9.nq.gz
    ├── 17eb95b91d6a1a12acb321d98e9496435392719b.nq.gz
    ├── 191b0c02a81f3b34c35cdab452cce8d9a20d0fb3.nq.gz
    ├── 199496e5ba340f258c883bc3d0a2b48b2fa64f65.nq.gz
    ├── 19a071d4bd733be19efa2bc82dd5047448ea5a8a.nq.gz
    ├── 1addbfe528e74c15037815794d114b4598b32856.nq.gz
    ├── 1b2207597317ae61be230cab75eb7c554e6335b4.nq.gz
    ├── 1d996a33655aba6cf60ab507d6446358f35ab585.nq.gz
    ├── 1f93b27344b3bccbb171c49800b5be47cd1323e7.nq.gz
    ├── 1fa544c2faa118def1b8395626d7a4e6759b060b.nq.gz
    ├── 1fe265d33ca4c484086cc3f3031a42e1ff6661d3.nq.gz
    ├── 2186e03abe614fa9cac8c476567cfa9475dcbef0.nq.gz
    ├── 22362145eef00a2293f27e80e83e019016be04e2.nq.gz
    ├── 223927a64b71d6a536db485687a0cb25078af3cf.nq.gz
    ├── 22b2eaa87730abb0077727c03dbeeaca8dcd1e2d.nq.gz
    ├── 23ad05951a6d8b6d65f8319bbb2d884b4af99d6e.nq.gz
    ├── 25ac984ae9480c0c265dcb8afd703669ba6eb0d9.nq.gz
    ├── 26e0e2b91de4c2682363eafc0e2e9c587e956320.nq.gz
    ├── 271d5298348381363d5dcc3871a529336316fe04.nq.gz
    ├── 2803116633a047e6a56385476b542d4204a544ae.nq.gz
    ├── 289eb5fbc6fd6e187c13460a6d38f14c95a4fdca.nq.gz
    ├── 28c24ab6606eca3e2d204a5ac0667cf85a3048d3.nq.gz
    ├── 2af9cf6455cbc6b4a78b0e7ebf1f8ff49a6dc714.nq.gz
    ├── 2bc7e58738d715d5052e24398bc25267d7d1606e.nq.gz
    ├── 2c7f942cdb4086b912ed66bcac37dcd2193ba4e0.nq.gz
    ├── 2cf6aa20ab0798232353c66d0a54ca5cce56ab89.nq.gz
    ├── 2d48a8e6f6d50080e460e4cbc449d497659b39d5.nq.gz
    ├── 2e4a6dfae13947aa8a21e51b8ffdb0ccaf96f6ed.nq.gz
    ├── 325232f38861477a9b680808f50f669e52a3aae5.nq.gz
    ├── 33062408fc06c46771669288cf89d1646fd23683.nq.gz
    ├── 33338c36d2c3c13630300d9f3827ac07601e8249.nq.gz
    ├── 33cb3ee332f8594b582801432c3535644a67eb15.nq.gz
    ├── 3432441200fc107e91d136b5ba2ab485a398c2e2.nq.gz
    ├── 345de85d61ed0e3f741a2d47d28de54a50cb0a49.nq.gz
    ├── 348b962b32a6e2c9b5f19c0bfcebdcf2337d970b.nq.gz
    ├── 34be19e6b8e0145a28c269ac8154715d0dc247a4.nq.gz
    ├── 34d1cdb47a1714d3d19aac87b0f4197f51822f6b.nq.gz
    ├── 350366f18f652b260fcb33ed98d16659aee237cb.nq.gz
    ├── 35c48fd2f957c8b16c5a03ba7f31d847c6530f6b.nq.gz
    ├── 3631ebe4eba2b2d80ad302d1e62b3748428800a7.nq.gz
    ├── 36fe5c8a33dde9b3783f87582131db09aec26a3f.nq.gz
    ├── 3887c42616074b3b4176020f29e66e832be7289f.nq.gz
    ├── 392dc2cc5c746d1729ede07bfe6f3bb9a7d901a4.nq.gz
    ├── 39300cd5383d8805234c883d1366ba3db13844ba.nq.gz
    ├── 3afdd6e38438be7612befbd4b656af7bed27a31a.nq.gz
    ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
    ├── 3c3ce8156fdc67cf72635c8f2122bb97e9657d2d.nq.gz
    ├── 3c47f8507f1feed2e10aad78d72bde9dd97f212d.nq.gz
    ├── 3c4bd4e013cc57ae2b9e123cd742e5ff9e0a0acb.nq.gz
    ├── 3cc28ff60529fd8b837dba53c85bdca86bbc49d8.nq.gz
    ├── 3d5b41cecec0b109abd718258456437293af7435.nq.gz
    ├── 3d814c7e52e4b5566597f5e4601a67e397d567b2.nq.gz
    ├── 3e30dc6a41540a1aa8dfbee506914b6745354e9c.nq.gz
    ├── 3fb654f7935f2cc77e8ab5d6b47f15d2d9958202.nq.gz
    ├── 3fff5c345c772982c7c6813edd5f3b892f50e546.nq.gz
    ├── 406d2fe018f08002ea5f22ed6ab95cd21c1c2aff.nq.gz
    ├── 40ca72d9c6c13d1bcf98ed4fe88baf41578e709f.nq.gz
    ├── 41c4b479f41460ccfa3fda3e70fec238d13bdf9a.nq.gz
    ├── 41d20c96768c819234daa630dade4647b8f29bbc.nq.gz
    ├── 41e46cd851848e0dfbb74005486de4bca66f21ab.nq.gz
    ├── 42926c5d26de47da5f8e29fcace58987900ead81.nq.gz
    ├── 42bedab77e5c3703ff7ecbe75140e22910a0c4c0.nq.gz
    ├── 4303ef290d6a1986b9cb49d9e6d89b6cc67b50dd.nq.gz
    ├── 44abf494dd9b32c62ac3ab8fd271bbccf9c93f6f.nq.gz
    ├── 46ff3c061f8666f5bceba6dfc9f858f1e4b8c145.nq.gz
    ├── 472d2ecaf41f1d51e0902358d4f44e6eb02b201e.nq.gz
    ├── 474aa49c9362aaeba42c339996ab9d763230e634.nq.gz
    ├── 47c51216269150abe9410da176bf8cf7953f24e2.nq.gz
    ├── 47e267fc5b75b85c79e7ba0e73475a7f725fc1c3.nq.gz
    ├── 47ef8c391921982d70712bd5b82c3178608d0b04.nq.gz
    ├── 4aa31cb429c71138e5742ddd7648a73e64939660.nq.gz
    ├── 4b8f61b29ff539b2a4085fbac30ca76366e1b3a3.nq.gz
    ├── 4bb9fb23395f2604fec7f3eb3f731f0473fb9974.nq.gz
    ├── 4bf9609538bcdb00fb85e7a9a41e1cde71a8be6f.nq.gz
    ├── 4c4ae5c6ecfb3a168f287e4f7631ef9058e8e10f.nq.gz
    ├── 4d6c08b787195596573d12f572783f332f0c803c.nq.gz
    ├── 4d846721419cd1cce7fd38d42e7a996329fddc2d.nq.gz
    ├── 4e500324c7217d6d503f42e51ce372a3fbc7011e.nq.gz
    ├── 4e65ad7abdc8600ff331bed6618f84d39622f4b6.nq.gz
    ├── 4e696acfa2ca4a3c11a424fc178ed6f53088d7cd.nq.gz
    ├── 4eb37fee05c6316c1c3fa2fac7c406dbf90d5b6c.nq.gz
    ├── 4f1138baffb9990eda70afc2fce452701fc17ab4.nq.gz
    ├── 504e09bd45366c3cf07b9d56333111579d5c857b.nq.gz
    ├── 5115ea7bc5895edf3ee91919db2f100692e08b64.nq.gz
    ├── 5193eff0cf425ce8ca92a6a5d8280fda8b44533b.nq.gz
    ├── 52091b1cca904238c13e364e37c7b4205c120529.nq.gz
    ├── 52aaef1d2452104517b38ed65ea62c9a305aaa66.nq.gz
    ├── 537e01372efac6c7a01ce7d925984c9e8664c3db.nq.gz
    ├── 5452b3bfd1ca2a3ca1f60bdcd650ee5364fb11df.nq.gz
    ├── 547bfd345b846a1f534b11d2a88eca34b4e7a48f.nq.gz
    ├── 54b714ef0f2b118af14e2dfd051396482e7c5cde.nq.gz
    ├── 54c4bda3d133a3d701c6dab0bb39227fe42c11e8.nq.gz
    ├── 5524c488961dd1ffbdc2818cec65b2a7c65d61a4.nq.gz
    ├── 5573ca60e2c7cd6630a8db0d15f8059be174b730.nq.gz
    ├── 560a9f5b386eb85141c10360282f0cf358243d1a.nq.gz
    ├── 57315d8fb73d545923a32b80364d49778195139c.nq.gz
    ├── 5746dd72d6b3332741232666f53c4b2a265544be.nq.gz
    ├── 58c4f5ec6711909e68785fb6921649cce6ee2d49.nq.gz
    ├── 5905b9ea3b280219a0c090d1b0e41da447f8f82c.nq.gz
    ├── 592e02c962c3c371a40dd7871e026c800ca9b9a3.nq.gz
    ├── 5a788a6b0a738951cb11ce1d1d6f7e74f884ca0f.nq.gz
    ├── 5b411e5c6035015478f763e15ce4ac5c48cd1fa3.nq.gz
    ├── 5b8a0edc8c2f90b0970100f408966cb67bdc6d7a.nq.gz
    ├── 5b9b38167eba07a52fd27f37e3820fa764ebcebb.nq.gz
    ├── 5c03a3ecc79e40f5593545f16a21e263246ccdfa.nq.gz
    ├── 5c9d82a0b75636d0193c957949d600e2bc277d8a.nq.gz
    ├── 5d0b49a2f3ad5d849e434456fd95e65fe2617f14.nq.gz
    ├── 5d738b78fa5aa579abd3a90400a5fd736623f92d.nq.gz
    ├── 5e06e0ddcc48390055d342096e5f8a845b5342a3.nq.gz
    ├── 5e41de24e4209140007fe3d3d3897845ae834ab0.nq.gz
    ├── 5e5b6eef62ce67d506b25ca08033ab04207240f2.nq.gz
    ├── 605a2ef8bf89b1922120f64ba82bd21143393e3c.nq.gz
    ├── 611137476d5684f9dc7f4cc2d5b5441a63f2eb2b.nq.gz
    ├── 6119ad9a8faaa5073a454f67b50fb98a25972fd2.nq.gz
    ├── 61b191d8708c94318d9f6b235a509c3608af52ce.nq.gz
    ├── 61f007295bf118b839f2c11ef7e51442ede06cbf.nq.gz
    ├── 6295fbb84d8f057d470cd9caf586fa2fa17147ef.nq.gz
    ├── 62c74f6d5308f4dd829a4072c6b63633c8f58447.nq.gz
    ├── 62cb36bf8ee76f182c015e0550dba510235bafe0.nq.gz
    ├── 62fa57d78cabe4563aa1c1eccb56d38911f33da9.nq.gz
    ├── 63d3bfdd796b47f73df276203effb9a4910d6c1b.nq.gz
    ├── 64478936b892d4be6732c41fcf2745eddec03457.nq.gz
    ├── 6473e50bead55982e4bfb9311cf28247bd2dc7c7.nq.gz
    ├── 64d88af61956561aee33adbe5ff543c90950b142.nq.gz
    ├── 6527caf7395ed31fa57ad79392c1540ec0255dca.nq.gz
    ├── 652bb42f553e9588174247066d4f138e6f16705a.nq.gz
    ├── 6582e1fc833bd59ca1ab729e606781b800b2be88.nq.gz
    ├── 65b8f123113823af0f9529981414209fff0a693d.nq.gz
    ├── 65c9fccff75141eb4b217e60aff02e90ba205b3b.nq.gz
    ├── 65da195086f583ace32f6b1659e6ae672657a533.nq.gz
    ├── 6766745a8cfb677f47f2c2a26828544d09fbd152.nq.gz
    ├── 678393086bf7cc60a100f54fb77639fcde76cde7.nq.gz
    ├── 67de8c6c91e20a8c7b605e2e524bfb87a35dd37f.nq.gz
    ├── 6879ec5c7d80e0476f6371971bc03524f41ffae1.nq.gz
    ├── 6ac40374b4024e0b00a3561eca8864d5aedfffff.nq.gz
    ├── 6c2cca0cf85a42095a29588e1021ae314828320b.nq.gz
    ├── 6c87de9bb3358469122cc991d5cf578927246184.nq.gz
    ├── 6d4045830fd3e363a565cadfbc7703a0157fec6c.nq.gz
    ├── 6deca66a7cfa74bed7b6906aa32e0a36990279bb.nq.gz
    ├── 6e8083df283de41f5c921b941d2cc943da5560d8.nq.gz
    ├── 6e8ee64807afbc920ab98311580c5feedb716ce4.nq.gz
    ├── 6ebf83b48e6fe901efafe98733339d9e37321571.nq.gz
    ├── 6ed7d0c0373e9e106375fa28f5bf4ef5010d9fbf.nq.gz
    ├── 6efb088dd5f83abfebc07d89e2a17a2ba2ccc78f.nq.gz
    ├── 6fb0d1edda84bc120b18fca8d75b7c8b738eadcb.nq.gz
    ├── 7014b67ed391adb7c187159f8a974eb93deffce8.nq.gz
    ├── 702b3a6fac9d569be071078c4fd15c52d5645a81.nq.gz
    ├── 70e5c3569d3c6718725a06ab47480d570a5fcc88.nq.gz
    ├── 710d67a31b37c973edcdf535f722d8f52b4be533.nq.gz
    ├── 714ac2b73c2d1c7be46fa6e87b7999466cb3724f.nq.gz
    ├── 715d77c14222e335a48dbf65756c11ddca4054c5.nq.gz
    ├── 71e39d8a622677788b35ef21d07ebb27cd6486b4.nq.gz
    ├── 71f7de17c7a4801bbdc370f3b6fc469d5c6cd56b.nq.gz
    ├── 72505a5168e4f96202a62fc9083ac198316ab637.nq.gz
    ├── 728429aab4d911a9cbd1c1eabc244169c422d87b.nq.gz
    ├── 72a0dce75bea3556959d561622f8e8d5154b6f77.nq.gz
    ├── 72ed85104c2314e93faeeb8246527c17923f81ae.nq.gz
    ├── 757b6deafcda058df064cfd6b997d689f14a210d.nq.gz
    ├── 767fff6cff58f4f9ad2806b81a6c9130dd895904.nq.gz
    ├── 76a290ca10d59ce9edc8a04b05db8e5adb03b1e9.nq.gz
    └── 76cb70f0b91ad5f797db6240ea4880cba90bfa8f.nq.gz

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

## Source repository

[kulshekhar/ts-jest](https://github.com/kulshekhar/ts-jest)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
