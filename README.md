# Repolex Knowledge Graph of python-hyper/hpack

RDF knowledge graph data for [python-hyper/hpack](https://github.com/python-hyper/hpack), parsed by [repolex](https://repolex.ai).

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
rlex download python-hyper/hpack
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c2edbee3b5508e0b1689877fe6f173eafb097aef
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c2edbee3b5508e0b1689877fe6f173eafb097aef
│           └── chunk-001.nq.gz
└── blob
    ├── 0133ffddc81876097172733a2213554c16e56a15.nq.gz
    ├── 01bdbbf8cb167f10fac9f5de989587c3617acbee.nq.gz
    ├── 02a344af8a41f86f05c6dc8682b36632a5b3d8fd.nq.gz
    ├── 02d790d4510ea8767843894afeb54158dd34b30f.nq.gz
    ├── 0348f67df3426af7f6db1e446ee8ca19d5f27383.nq.gz
    ├── 034c167d2e7f6618d244de66af06ef1fcd965b79.nq.gz
    ├── 0550746fb3def13b54a727782da6ee0ebef19eab.nq.gz
    ├── 073bbfff588a791896cc5eb3fd08bf7d2d7b03e1.nq.gz
    ├── 07890e25fb884cc86eb924af06aa745807ecb457.nq.gz
    ├── 082e9bbec531562442292c33e84f227a807bb154.nq.gz
    ├── 0992d652d7cae9c4e91c017c8aa96e26d5bf2915.nq.gz
    ├── 0a0077dcd2c513fba07037e70e0b38717e87a160.nq.gz
    ├── 0a247ca39fd29c4023e413c3767f45930005851f.nq.gz
    ├── 0c06b3e6d2a688375ab3ee333c78378f5a34a726.nq.gz
    ├── 0c5bf3114a38b7c09daf8b453420cd6a34e64977.nq.gz
    ├── 0d91a28bc4842a9cebef90b7ad859ae13af76b8a.nq.gz
    ├── 0da023489829c67364483307cfea3a9d95bd6b3a.nq.gz
    ├── 0ea789f41737fe1fc1500efa3645e7bdb9126f6f.nq.gz
    ├── 0ee4c8f301192f12c7a9289e6eb42f3384cdd4dc.nq.gz
    ├── 0f0423748e258999033a3d1c0073928b5529ee59.nq.gz
    ├── 0f12f080a14e24803a92be178aa53eee9d454821.nq.gz
    ├── 11327f0a5ea961570a14bdd960bd9149385510a7.nq.gz
    ├── 11b7b3bf7eccecdcb1d6debd5a849425a264f63f.nq.gz
    ├── 12cc128e16e7179e35312cb864ca2590ba5e541b.nq.gz
    ├── 13016b76c23cf8517974d9b08a89aeabbfc16bbe.nq.gz
    ├── 13204505a4834c00260e793841d0cba75f03623b.nq.gz
    ├── 133257557586e81ae6ee8bf9b04dde9ee9426b70.nq.gz
    ├── 1345cf19b21bccdfa614494d298ed485a4665961.nq.gz
    ├── 143ced203fccff28abecffbedc0bde1072f4568c.nq.gz
    ├── 146ee7911125b36975a64757e5cd05b74886d78c.nq.gz
    ├── 14b7aa61407f9c3fff45df0cf85a835b2afb9667.nq.gz
    ├── 14d13e0561702ba7f80a7ef1fe4fe898cc2f07ac.nq.gz
    ├── 153d3df6380492dc99b3472e524e9495e5782798.nq.gz
    ├── 1718c8887f0635bb9df1e02e560f30898d133552.nq.gz
    ├── 19c68b9c484a020d5860822fe0e4fd3dd5394613.nq.gz
    ├── 1a67be70626fe5747e67dd6fba446a5965952e0c.nq.gz
    ├── 1aff8abab56c3da259c6687212e21c97cb273277.nq.gz
    ├── 1b18130dd63081f71f08bff516f074e639dac606.nq.gz
    ├── 1bd29a3285918d7180747dafec53948bd534ae0c.nq.gz
    ├── 1bf07183854555d83db693288ebf9143c9a48443.nq.gz
    ├── 1c41c03cfb56733e6b25f64cb395b6ac944e8add.nq.gz
    ├── 1c55de02a76f3662dea15ec7461f4af2a466964d.nq.gz
    ├── 1c7412c92f6b605434c64c2e02da49e6f3054984.nq.gz
    ├── 1c8389b3abcbca04ac42819d3494335bb22f5054.nq.gz
    ├── 1c9476cb199f5e7283187a754ea78f96413674ec.nq.gz
    ├── 1c9bf483b7526620dbabb57e4edc0cc7f844e2ea.nq.gz
    ├── 1cdef257ee6c7dd2104edaa5455be49e8dbdf841.nq.gz
    ├── 1d8ad168d2c49c6cf5e467750933b3710907371b.nq.gz
    ├── 225f66061dab464cb92ec27745663366a3775193.nq.gz
    ├── 23d9ce26886d4f802761c46d86d91640437cb255.nq.gz
    ├── 2571ea816dfb66e5516cdc6c10d76ec5325050cd.nq.gz
    ├── 261297c6f66fdd707513dac323c6ebd2268cc54d.nq.gz
    ├── 265ed31b1a636817c463a231924a00246c8597e2.nq.gz
    ├── 26813045f0ec6e1701c246668bc5f321c1772c63.nq.gz
    ├── 269132fa6ece5052d6345c983f80203235732002.nq.gz
    ├── 26c5a59adedc8b83cff6b6524510592f24c301f5.nq.gz
    ├── 2a9d25716bff57683eeba7020f7cb65579c0169d.nq.gz
    ├── 2c0ed52183a7fafe5b735bb1a97b0e2a31310dee.nq.gz
    ├── 2c2705bf6aee93028492d53c1a050b88bb28c00e.nq.gz
    ├── 2c5d22d31b1b4bb9be3833bb3046ca6f2493f218.nq.gz
    ├── 2c9de67b00d62d234ebf8eb344141b5b29a28e53.nq.gz
    ├── 2dffd45b92e1ebb18608fee4d30dcf6cbadd288d.nq.gz
    ├── 2e3f30823e394603872b2392708f24d1c3164796.nq.gz
    ├── 2e47f326c4d3bf27e8074f21adb3b71ea631a984.nq.gz
    ├── 2e9d75aedcb71374f8190f5eb88d79bd5fc6f306.nq.gz
    ├── 2eaa6dfddfeb03b1bd97702f14153222c78b9fc8.nq.gz
    ├── 2ee78596eb4061c0841654a79756727fbe0a86be.nq.gz
    ├── 2f16672b7f4133ddef75487cddbd81e035a7eb48.nq.gz
    ├── 300c92679721301e525c8d321b47a4fb92c7c02f.nq.gz
    ├── 3083e92e5cea032f9e63ee2da22042ce34ecbea5.nq.gz
    ├── 322b844b37d624117c95ab1a6b25cacae3907260.nq.gz
    ├── 32564d97a9a0c047671dad5526deb01287af49eb.nq.gz
    ├── 344e124747e03e3e11d951171c11d321a5c923ce.nq.gz
    ├── 347bf6cb3dd192e8dfedc3799ee385b46034954d.nq.gz
    ├── 34be73aaf5d5beef359f76e63e9fe4b6f07a97a7.nq.gz
    ├── 3514d8ff4e72f3513eb215078981b3f8ce391c30.nq.gz
    ├── 37b4922d7739396ca12510a7b2b109c5d1416ceb.nq.gz
    ├── 38038632d8712d9fc326629f67d631f9aed647e8.nq.gz
    ├── 3b27fd7f96d3f2bcca2a995aa6130bedcfb99395.nq.gz
    ├── 3ca401b63ee758866cb6cc5290d7dff8a5ebcd42.nq.gz
    ├── 3d7e5bed2a03d89550d8a474d92d61670f0b752d.nq.gz
    ├── 3d812502652bc06572357e5653d3afeae9e7ae04.nq.gz
    ├── 3dbc9f323d83a91b2be1aa16609544a14139d9bc.nq.gz
    ├── 3de8cf243575f2d1b598bf65e9e95ca209d75a5b.nq.gz
    ├── 3fa611169dbe9421a9c9b33322ec55e44d4e2224.nq.gz
    ├── 400c9b4644524724a1934122e9fb3f7f04433295.nq.gz
    ├── 401fb70470fba87a0fb0cefc5b1275b3158caae7.nq.gz
    ├── 40b15e36b26b0b81e2038771a8b75d998d54397c.nq.gz
    ├── 40cc546c0a42ec01479e6867f2abf396c3f542f4.nq.gz
    ├── 41d0cc5def08c3466f1521b037cae8573d55885a.nq.gz
    ├── 41daf328e915c4f02b63c73dac9927c18ea80cf3.nq.gz
    ├── 41dd2128b349488df84c2c8dcf63931b05132129.nq.gz
    ├── 42c6cc4a7890cab564769f47a747516c234472ae.nq.gz
    ├── 431628d2c5678cb8d05acb635918ab4c2fdd1124.nq.gz
    ├── 43377fba2d35abf5a8b97b187f0904f34305d4f3.nq.gz
    ├── 434857916ab5b808d26bc5aa1509dd44afc7d3bd.nq.gz
    ├── 440925876172cd38153f03c17776d5cb9fd5b017.nq.gz
    ├── 44178b442f279b3b813ad09de91100ece139bede.nq.gz
    ├── 4417d4f9b45a468b95a0db612f020a102c1fb424.nq.gz
    ├── 4434d1b6bb0c57014c642b89640b0f1e1df02a80.nq.gz
    ├── 445138a243de13c259e29349fbc1bb5439e30d12.nq.gz
    ├── 44d521f3fc0c6c5a42f2687861b20064b6922013.nq.gz
    ├── 44f9bab3f4ed5afd864d31fc8d0995b17a96109b.nq.gz
    ├── 45d299c88a1a0c57da1cf2c1fa3f50d9814aa390.nq.gz
    ├── 480ef8cdd4a57abea21151e0da5618c65ee16a5e.nq.gz
    ├── 4956909a77b2f6367fce3267bee8ba3026acd218.nq.gz
    ├── 49a66211019b8f1e9a845ca9be8f02516bd43c8a.nq.gz
    ├── 4a971edd8149e98ec267688b15a6e78d6fba0f2f.nq.gz
    ├── 4b75ef769686a94443660a2ef272e714d00d0755.nq.gz
    ├── 4ba03507539af1c6a1770e79cf02c70528794ca1.nq.gz
    ├── 4c7ceef13f5e318e7498d60525ad27a1080b6e09.nq.gz
    ├── 4ccd56553a4fd026b654cf1ca6001b074e36fc62.nq.gz
    ├── 4d5e1ce049e038ec467eee3121ab7dacc40bdff6.nq.gz
    ├── 4d62626344e8f9f3cb6f9d0949b0407497056913.nq.gz
    ├── 4d778157b64a43d8b80c4cdce4ec537c0545162d.nq.gz
    ├── 4d9da62e4df92210e8f919f32d080a5be2be24c0.nq.gz
    ├── 4da0efa37204d583bbd0d4ced38e7dc57e1cc6a5.nq.gz
    ├── 4de3ee8b39ea621156b684e5ec4b32523229f586.nq.gz
    ├── 4e444d780ec4c4554f058315aaaadf52314ab5d7.nq.gz
    ├── 4eb71c21d7fa19b8d62861b37bab8001b22744a9.nq.gz
    ├── 4efb1a3efd99b23214d6ac1e5f546b85f446a16f.nq.gz
    ├── 4fc2ff5bbe39a4a413a8982cc2bc8346d1f6c14d.nq.gz
    ├── 504dbea4c9c0d77dfb0711a02e41fb8df0a7c0b4.nq.gz
    ├── 50fa4ca87fc958845ff44f1bb4e47fec7324055f.nq.gz
    ├── 51f5083fd124101158333f13a162ece58a254118.nq.gz
    ├── 53cb962078a21792dc6c18be599d3cb0bae7d949.nq.gz
    ├── 5452d3cf0d58ff058bbf60aab1afc503c6547118.nq.gz
    ├── 54aab3bbcbc0b13705fd3e18dce9a94cd97717f1.nq.gz
    ├── 54c282ee270bc718c5d080d720a48dd4e4d80131.nq.gz
    ├── 556067a0aab034afe954c2a58cde09f63bfd8344.nq.gz
    ├── 55aba32f70733da272769a88a9b4da5acd9b1f33.nq.gz
    ├── 55d9df26ec915af1a20c7e0566c71718a7b8f1ea.nq.gz
    ├── 56034ff496379fbb0743ee07800bf3b9a032bf8f.nq.gz
    ├── 56a86274a9e91b7c9d1208eeabb5477fb4b78024.nq.gz
    ├── 56cbdc9e9ef3550ee9597f0d2027429a2e6c90bf.nq.gz
    ├── 5738845bc4669efe8ad2871dda3568927433000d.nq.gz
    ├── 5757b85796fe55ef431a03a697f9c4073210cdf2.nq.gz
    ├── 58681d0cd40f6380473b7af5bbf41e1dce33425c.nq.gz
    ├── 587c526c722b1ff3ed529501da17ef77537b38dc.nq.gz
    ├── 588c11508cf1eb478bdc363bd0fb45d2b058cd49.nq.gz
    ├── 58dea5eadf5bb07dcc41ce03e68fe27c08ce48f8.nq.gz
    ├── 58fbd44afd0f0d3e8b6de0942a34f57acfdb3020.nq.gz
    ├── 59ff2c0d9324d384eb10f7de8dc86804a11e8803.nq.gz
    ├── 5c6bdcde502fe5c10cef742f71c0e02ddd7953ad.nq.gz
    ├── 5d7c442d533b2ab3ef80c163c4a99bcb2893531e.nq.gz
    ├── 5ea40229c0c4c7946863f2084981f824b3e89acc.nq.gz
    ├── 60ec3279752116469706fe4a958fa68b6945466f.nq.gz
    ├── 6149b57a0e55613ebbcb80f6fb573098e4c237d9.nq.gz
    ├── 6173eccd9cf81a793a494259923328146e67ab7a.nq.gz
    ├── 6176b5dd1c58d45277665e8eff33296245474c54.nq.gz
    ├── 6238ae458ac3dfb0d1040670162a283c15f511c5.nq.gz
    ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
    ├── 62be1348972dd5197c9c4f53cd92e72f9bf226d1.nq.gz
    ├── 62f43e2550951c519e57fa602594b927653ac889.nq.gz
    ├── 63284deb9a8d3b0201fb460b6091b4e4279bd458.nq.gz
    ├── 637d99706e98e5e3fddc00aeaa19d2a1e37fde3f.nq.gz
    ├── 641d2097aa0caafa416d02fad016f21cfaef1a9a.nq.gz
    ├── 64253a62540bfad7c0a062de686f2b9f88265af1.nq.gz
    ├── 64493ec523ccee1e27636628a2f79265df34c63d.nq.gz
    ├── 649a8d5f5939c961e065d0da3d864718ccfb393a.nq.gz
    ├── 64b642cfc05d731c025b31ea083e5cff4caa7035.nq.gz
    ├── 64bf0512da119655d611eeff0f7f6adbd59d445f.nq.gz
    ├── 65158ca235e3807c7ea6ffe691abd6c6f18e62b4.nq.gz
    ├── 66d9aff7775ff4698e9e60dfb4518279ba90d6a5.nq.gz
    ├── 67c92f37ee559c225c0affe1ae74f7eb081c186b.nq.gz
    ├── 686aa684bd45f4522511a589801e66a5dfd6ef3c.nq.gz
    ├── 696964b5da3e83bca9a8b899abac1afb7d0c8569.nq.gz
    ├── 69feaf88f20ad02d0ca1842b675650a469464619.nq.gz
    ├── 6b2dba68f97b9faa3208a40c4ef5266a23d10417.nq.gz
    ├── 6b95fffcf95f48ac48a107d730ad82390eeba4b4.nq.gz
    ├── 6cf9dc2524a598025615be38748f3297586ed62d.nq.gz
    ├── 6d0a725b74e3248ee3b26f5892e43aa7820772e5.nq.gz
    ├── 6d30e677f0ce19e95b7f70a9226c4781f019456a.nq.gz
    ├── 6d5e2845ad1bd59c9e2fe6fc71a5d181c1ff17c2.nq.gz
    ├── 6e019965962ba9f6a178be8e57c097594b09e714.nq.gz
    ├── 6ecb39dc3129de7b617f6da460c541820d33ce2f.nq.gz
    ├── 6f528e1bf8dc4971f6af7c76f835ede63b08d343.nq.gz
    ├── 7116e55249c0824f20e490ad125a6e3c7c58aa0d.nq.gz
    ├── 712ff64af6534fd281b358da67474286c31d7c62.nq.gz
    ├── 713f83465bed3a398b3ec3a3b6a1e584a65af45a.nq.gz
    ├── 72384c60baf74fded7dac9d6cbf529da80eb7e41.nq.gz
    ├── 72cadd433ea510cecc1294b8c6fdc2cddb685c4f.nq.gz
    ├── 72da8b56a6ca3180f95f46671130b1da3b37abc6.nq.gz
    ├── 7335f343e5fa909ab35f41b6ea640defe233c90f.nq.gz
    ├── 74dac51ef2e0890697e8c149fc1e8e7c77729c41.nq.gz
    ├── 75110579a2c6fe5eea1eeaba0f0fa6c77de5d6fc.nq.gz
    ├── 76d15db88b6c82b2c6fed9dcd7f261433cf30592.nq.gz
    ├── 76e9ca79063ebcee15511f7cb3af9f01afe5e0d9.nq.gz
    ├── 773e45f1d4ca1c39adae3615bd8a62dd69faca77.nq.gz
    ├── 77537489099c4f9306f5bad4d3e621ce5a170219.nq.gz
    ├── 77a6d77cc8c2de3449c7a5f00070d156d3119e87.nq.gz
    ├── 78292c264fb61ed279686a9d02a55a879da64a64.nq.gz
    ├── 792a01f3c3a06b5c280c62ad5d484c39e1bc4dfa.nq.gz
    ├── 79c1cb572e1730af9ed80a05734f19de930652ed.nq.gz
    ├── 79db65ad53925bbf6b6852c0df29fdb94043429a.nq.gz
    ├── 7a18ac6cefc7cae22f94ce5a117827458049fa14.nq.gz
    ├── 7a7cb2a7b98895b22cf47576140dbfb80cee7592.nq.gz
    └── 7a7e3d649548ad02031ca9083a25bcf973f7e920.nq.gz

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

[python-hyper/hpack](https://github.com/python-hyper/hpack)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
