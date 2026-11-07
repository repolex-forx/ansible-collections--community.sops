# Repolex Knowledge Graph of ansible-collections/community.sops

RDF knowledge graph data for [ansible-collections/community.sops](https://github.com/ansible-collections/community.sops), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.sops
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3c2d6f9c8454123d77c515cd789198937fa73ffe
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3c2d6f9c8454123d77c515cd789198937fa73ffe
│           └── chunk-001.nq.gz
├── blob
│   ├── 002c8136e3c0a345ab89ce0e33d326368f1d3aaa.nq.gz
│   ├── 002f2b19a6b8481eed692cb3c51acdda549ae37b.nq.gz
│   ├── 00cd8f37a25d03f413172ef1af0dccb553aafb58.nq.gz
│   ├── 012065c8539f2bd3e61eecc74acf5a046956de40.nq.gz
│   ├── 02ad8294c0c8b40e01e7c0f7b4bd4acaff3cbd75.nq.gz
│   ├── 062ac5aae2d35f0c212076ff3a67af7ff1f1c27e.nq.gz
│   ├── 077b4bbc066584eeafdbecee05e8bd7836b4cc5e.nq.gz
│   ├── 07d08ebb06613d9b84ca82df232a0767e0f148f9.nq.gz
│   ├── 0abaec167757ea9ce77946ab583d74c50d3113b2.nq.gz
│   ├── 0b20c815f76c06ebf3ca846d92bd8e3d3a853a7e.nq.gz
│   ├── 0c1ab43f3d760f7f4f549f6ecdb7232ff47b95b8.nq.gz
│   ├── 0dedf6454268fbd436511f2a2be21599cfbe967b.nq.gz
│   ├── 0e7f213d9099cfe8389a841582d6a99a129907b3.nq.gz
│   ├── 100baf68907e8933f703d8f8444fbff3149f433c.nq.gz
│   ├── 102f9123609650745911b665df636ae8d053e77f.nq.gz
│   ├── 11b12e9048d65692d64f9aebaf5e792de568db74.nq.gz
│   ├── 12de052bf276fb8b5d6554b2de76fcebf622d3d5.nq.gz
│   ├── 18326389771a648858d4d6d5fcc2a61786729370.nq.gz
│   ├── 1a84562046cae04ecab0e8ac0c281a14c8794177.nq.gz
│   ├── 1c5b6204a636a72a795251f1e231f74cc7d38302.nq.gz
│   ├── 1d6cf8554ada641c9a963a6f986822bf4be2da9d.nq.gz
│   ├── 22808f35395beb0ee1e7afc00eb43f432fa8a686.nq.gz
│   ├── 24d14b1819b47cb7fd462c57c3ce73ffd027b020.nq.gz
│   ├── 27577c48829c60cc6871fde7208145f12ac5ec4d.nq.gz
│   ├── 284a5229e06d672b4d33e957b80947bbaf3f6196.nq.gz
│   ├── 28b22dcea223504c62c0c4e52092457f12c2d5dd.nq.gz
│   ├── 290ef77ac3335b57759d8824b396e7b0082ce774.nq.gz
│   ├── 29330432f3a64642e14dd9e0ca12b1f0d3310284.nq.gz
│   ├── 2a8cebeaaed10dddbc7789354c7530798bd3a494.nq.gz
│   ├── 2df127395d0467ee247e967a048a169b92e2cfb1.nq.gz
│   ├── 2fcd152f95cb8146ef0d4c0a1c9f97751b464c2a.nq.gz
│   ├── 31f5bc47fc26ef94cf7b01137f9b27ebdd5b0048.nq.gz
│   ├── 3224ebdc9741b83fc37b9c50bceee08e2c4584ab.nq.gz
│   ├── 3385456547750dc50e1cc9938801ab5bb070b39d.nq.gz
│   ├── 344e8b86561008abc7bc40a4ebe10fef99831d46.nq.gz
│   ├── 3660222c14dc9ae558666672a16c2245a664b586.nq.gz
│   ├── 38590f2e4ec486212f404e5f1405e69f7ec27db8.nq.gz
│   ├── 3a9daf6c43cae4f994485a3c5558101f1a063fce.nq.gz
│   ├── 3b9d1c521cf2027e727eb7c37b8a56af3891903f.nq.gz
│   ├── 3d399112a48a38745a1c1084a8ac6fc1d6e60c1e.nq.gz
│   ├── 3f3fff6363b0bdacc6bd2fda27a9dcaba5b0c109.nq.gz
│   ├── 41454ac7a55c1dffca14c4323b46023267c424a3.nq.gz
│   ├── 4214176de849628914a24a86bfb65ae6eca8bc37.nq.gz
│   ├── 43dc526b4526477dba1e5f732cbcfe0da213ac39.nq.gz
│   ├── 444680d8979985bab6843480bf4995f459b68d98.nq.gz
│   ├── 479a5d86781947b63a6e27e43c37981354894c54.nq.gz
│   ├── 4ae5adfe9be374ab04ef17e52fb4019ebd91986b.nq.gz
│   ├── 4b6fa33f537dafd59065b785c2c97480f418d29b.nq.gz
│   ├── 4b9f0b9d5c88300210ee9a5d63fd2914a389151a.nq.gz
│   ├── 4eb3588e88abd0ff3f1d724c2256b2fa6f0cc4d4.nq.gz
│   ├── 4fcc013bc703020b0506c2f2c525ee91be67371c.nq.gz
│   ├── 51e34a8db0a456902b7c2371e247990694053930.nq.gz
│   ├── 52a041a79facac206a13660c7a54b33d83b56e5c.nq.gz
│   ├── 52c886ab1cf6f8a71ee448e5a5b2f2693c42c3f0.nq.gz
│   ├── 538d071f61a05507a1e1ab4b926331a258feea23.nq.gz
│   ├── 55a71e360b35779aa4f83e104bb383a568bc0c65.nq.gz
│   ├── 5ae3291d5c2f8a1162af38eea212c3aa187e84f8.nq.gz
│   ├── 5ee19d4cf03641ae06e827b8ab4a875bbaf4a1fe.nq.gz
│   ├── 5ee7812edbb236187b2434d8d01342f71c10b922.nq.gz
│   ├── 5f1a9a9b10152c41face1b10a1f98e092c070a9c.nq.gz
│   ├── 602efc30709663a230d9f6d21a8c72c650a0455c.nq.gz
│   ├── 615f0d674f1c5dc23aee8d7cc726f8e83868b1d1.nq.gz
│   ├── 64b47f7d9e43dafdb315496b3c347ef9611362dd.nq.gz
│   ├── 65ac576b21da29eda43a44539707524dee3bad0d.nq.gz
│   ├── 66cb2bfa01669159e46d90c77d4034037ddb2043.nq.gz
│   ├── 676292c75f505be371a00fb536c8fb970b1b89df.nq.gz
│   ├── 6810e04e32878215c32b2039277d4b1809f4de4a.nq.gz
│   ├── 68aa9ec94954a5846237852393fd1b5dfe30922e.nq.gz
│   ├── 6baa8b397833817f094f7ca1e0fa798790c041d4.nq.gz
│   ├── 6d1ba661dfb39d2ad495c39b913cce82438d26a3.nq.gz
│   ├── 6e8b3667844f07e1b944e19609c32dfeb58a3c03.nq.gz
│   ├── 6ffd5ab028275bd054537ecae5eda453c4f0517a.nq.gz
│   ├── 70cf936c2fa6cffd5c133b4ff7caf52c3be38756.nq.gz
│   ├── 726c7055dcd3ffa5f7b42f74aaa9ccc25d8b4e08.nq.gz
│   ├── 728531beef0690ae462387f1a8fb019f7683025e.nq.gz
│   ├── 74f22ac2b41c4bb7bb44148b57511a0705fe6a6e.nq.gz
│   ├── 787af5764beae44d48313f6981794ada0fac8bab.nq.gz
│   ├── 787dfec723feee8b92686bff19589edcd6cbc320.nq.gz
│   ├── 7983ad497d1db0f3a29ca96dde2dab01fbe91ab0.nq.gz
│   ├── 79f041be99ba8a58db6f29d559be878771c3de8b.nq.gz
│   ├── 7e793f133899b241176932045b98406532c9739a.nq.gz
│   ├── 7f0932ba19e95e22296d2faeb3c4d4ddd15fb545.nq.gz
│   ├── 7f4f465249ddae8b86305dc0e7dd44fb5354c5d7.nq.gz
│   ├── 804cf3c94e372a801c387e65870d3ac017f426b4.nq.gz
│   ├── 814477e3b09c41feb37f650d7d1b24a6b9fb362b.nq.gz
│   ├── 82abea02f2ea47b0cfbc336dfad9805920ec9413.nq.gz
│   ├── 83d20d63949770b9a2ff55d5aead876d1dbaf551.nq.gz
│   ├── 83e6bea5c7ee976feead7d4439d74ce4c941733c.nq.gz
│   ├── 855df871b432c343833b72ab3c7e611d49acd3b6.nq.gz
│   ├── 8a64e3c27836c8138afdbcf95d0eb9c4c20fcc6c.nq.gz
│   ├── 8d9120d2e502ca1f8d8a7a1d10bd6583cdedc202.nq.gz
│   ├── 8d952baeb309666d4bfafe45956e2f265d8ec03a.nq.gz
│   ├── 8e9f04934f4accc2ad07ed62e41d8d519a65be9f.nq.gz
│   ├── 917af7ed5cfb18849fbb9415bdd75b510b514c3a.nq.gz
│   ├── 91aa389658ea6bfdbd8eac2883bca31d4e9e517b.nq.gz
│   ├── 91f136ce82eff34b3ca94f37da74f921431e53a6.nq.gz
│   ├── 920371fadf0078c6470891c62e46fe7313bef154.nq.gz
│   ├── 924f9a2c9a44c6a6d1e47b0d92cfb296528eb397.nq.gz
│   ├── 93cd4cd937b738253b0e35b7094476b8236acb9c.nq.gz
│   ├── 9493a6ee076ed1ccef2b8a8a9b839a2c786b7b91.nq.gz
│   ├── 95f3bbf0d46725d7f94442937f4474a2ed40be30.nq.gz
│   ├── 977ec388204e9b7eebc222ae9389efe4d2b45a1d.nq.gz
│   ├── 9bf8bd219619439c19e27f8893f79ad107431318.nq.gz
│   ├── 9ca64d742c8fdfe6818aae397763e09a7086fb86.nq.gz
│   ├── 9e109bfd269508526e1c17ecc67891608170eae7.nq.gz
│   ├── 9e8ef50bb1fce6fc34dce0ec45888b8722a3c923.nq.gz
│   ├── 9efa2991e72f777527327344d2720f1f2ae5ee01.nq.gz
│   ├── a3d5d91adcd978aee6277f9f6537bcf8478849ea.nq.gz
│   ├── a6054a7751392d6b06da7e2146948d621e91b3ca.nq.gz
│   ├── a704dbad3fa7b63ed87a7a6908968cf95e429cfc.nq.gz
│   ├── a85415457a004d2fd1959d6382419920993a6a07.nq.gz
│   ├── ac795ed491bfd55fb3ecd6d36f9b6ac6ab248b59.nq.gz
│   ├── ae4ddaa91971eb614429a373795a711b376136b5.nq.gz
│   ├── af344ef2d8e1cf2256a062f2b93ad8214c58d2da.nq.gz
│   ├── af602fa3ef7e2f006dec8c2dd4eff8b6483e0dd4.nq.gz
│   ├── b17c8017b1c6e5dbaccc58592f5bfb8af78d050b.nq.gz
│   ├── b21909fcef3492a1f7d3a13f433b9c2cc4771ba7.nq.gz
│   ├── b3d11e3424117def8207d81f241fa54a7adc7d93.nq.gz
│   ├── b49b1722c9ad1de7b43b3fb47f55e23afdd9f18d.nq.gz
│   ├── b519639d0fde6158c33c7d93014c255d72e6e2ad.nq.gz
│   ├── b532916562894b045072577b19178b14fecda36d.nq.gz
│   ├── b61752806d6fd8c10f7b2513bf33d7068bb0b9d0.nq.gz
│   ├── b72ad011fa964884a598983b8307e98139d9374b.nq.gz
│   ├── b7f89500ed785f4a428abda8ba83ea511807012b.nq.gz
│   ├── b84b49fa507fbec927c253f7b7afb52329a487d6.nq.gz
│   ├── ba51f599068bc5bfff160d124663b7ed9caf353e.nq.gz
│   ├── ba8fcac0bd9106f63b8162d205228218ecee4316.nq.gz
│   ├── bbd8c591de45199e55361ddedd7949184f283401.nq.gz
│   ├── bc3804f5559d1abf651b4336551d7a47345a56cc.nq.gz
│   ├── bffe0521fb6b398d894bd1a2ee958dfee34b26ec.nq.gz
│   ├── c8f115fa06aadcaa924e536e1a659feadb763fca.nq.gz
│   ├── c93c368107f744dfecf83f61c89115601cad90b6.nq.gz
│   ├── c9712afd6cc5d288d184ad9a3e1d497735b74111.nq.gz
│   ├── c9d871c6981dc11bceec8f9c43b6ba08bcaef9bb.nq.gz
│   ├── cc18c07b7c30fb269fdb771a1c84b0110c57c5aa.nq.gz
│   ├── cff1795085ef9916623e78533791668462a2c64e.nq.gz
│   ├── d1604e707e69bc5e3bd2335c27ce7e9e27863e12.nq.gz
│   ├── d1a6582180a227d8749cee95a9164ce202cb4318.nq.gz
│   ├── d2e8372af6c80bcb8afe9f4e84ea146559f05936.nq.gz
│   ├── d35533bf21a259406e700fad19cc6428a284a046.nq.gz
│   ├── d3a52a22427392190a021eb324cfd6be54cf31cd.nq.gz
│   ├── d6d7f7f2c80845fd75191f6b1fc488b89bf655b7.nq.gz
│   ├── d7bfc2ea21e348573e5a015a8d895af6543029a5.nq.gz
│   ├── dad222e7a53d2504a02d989862a1cd8adce1b216.nq.gz
│   ├── db3998d7fc72ead50d66fb410e7875bfe5df09b7.nq.gz
│   ├── db563575703a1f8cea600580b4089417bd2ccbf4.nq.gz
│   ├── dd5d2d1f48597bb5ef3b6ba5c65c3e84ca662515.nq.gz
│   ├── de8947d74e8be1ce7f67166e509629b0ff7e9850.nq.gz
│   ├── df2d8a258a8b2a0393b5e47233c8b1e0dccc1bbe.nq.gz
│   ├── e4448001fc4948ccf382e696b6fb211e5233d383.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8a8fd197b8dafb321df8622b0031fdaa01ae1e4.nq.gz
│   ├── ea678c94dcd7e3ce049487a10822d7aec672d50c.nq.gz
│   ├── eb14384c45c096c9c5d8fe92638b39bd2d9447a2.nq.gz
│   ├── eb17d0814bb25cc67d7a310b09ea29400a08f492.nq.gz
│   ├── eb3fa263df2c00665ece5bd1769fdad7ce7c5719.nq.gz
│   ├── ebb10c641ccbaa06dc32cf13b4385791a3aa62d6.nq.gz
│   ├── ecde47ca9b9fbc20560a56c572de75f7502c5bcc.nq.gz
│   ├── ed60fb31d4ba30fa8c11a0652b9593edd03fb9d0.nq.gz
│   ├── edff8c7685d5f4817c24b0ac7a99e0826bd2cf18.nq.gz
│   ├── ef1be3f63c261bd3bc531b36b9152cd5d567f009.nq.gz
│   ├── f05dbab32f2522532450ee00146eaea6105518a0.nq.gz
│   ├── f1c55b04f334ee064ea650fd14cbf837e928d38e.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f29b9f7e6ed3b18225427d6b89aefa66aa2f0614.nq.gz
│   ├── f42fdb63431c3b02a3b66334cbadfb531fe0f570.nq.gz
│   ├── f43ae7905038bf9cf54ae39753efaa7fc26b1b4e.nq.gz
│   ├── f471cc19a424dea45adbc6911b065061b75118c0.nq.gz
│   ├── f4976607a49894b79e749d7982fa03fc7f9a1f45.nq.gz
│   ├── f5455c6566213c4aa0c71565440e5fa3f3189d8c.nq.gz
│   ├── f654090d009dfbddc0a320997ccc1e5088577783.nq.gz
│   ├── f71b322d2aabd560774185ebb7c3fec99c47ef3e.nq.gz
│   ├── f7a1b14356895dda8e3092e78ca68165f141969c.nq.gz
│   ├── fa937d54ea73686f920ac62b5201f42562f4c233.nq.gz
│   ├── fd848bdcfb9193b7a251d83d060757d380358c8a.nq.gz
│   ├── ff27d84a663f30494c1fcc607fa2d0040519e1ab.nq.gz
│   └── ff95bb8217b6b64162a2911f958f8c367bebec4c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3c2d6f9c8454123d77c515cd789198937fa73ffe.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 185 files
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

[ansible-collections/community.sops](https://github.com/ansible-collections/community.sops)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
