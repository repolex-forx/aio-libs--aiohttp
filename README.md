# Repolex Knowledge Graph of aio-libs/aiohttp

RDF knowledge graph data for [aio-libs/aiohttp](https://github.com/aio-libs/aiohttp), parsed by [repolex](https://repolex.ai).

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
lexq download aio-libs/aiohttp
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0ed22240769d11dc382ca1430538f8be180316df
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0ed22240769d11dc382ca1430538f8be180316df.nq.gz
│   └── repolex
│       └── 0ed22240769d11dc382ca1430538f8be180316df
│           └── chunk-001.nq.gz
└── blob
    ├── 0293ccaa860ea1a5d7c24a3eb028c3b9372f00c2.nq.gz
    ├── 032ecc8b7aad6cdf4821bcf724be7bedf7018bf8.nq.gz
    ├── 0350e215fc43a734ecbc5163812aa5fe723d1bb0.nq.gz
    ├── 03b8b6b0e366aad9ccaf8128418f325e2dfe70aa.nq.gz
    ├── 041d5d4a2e0bba470d18648f95c3b80e046b7014.nq.gz
    ├── 05084efddb986db7b1a457fec858a02b36aadef3.nq.gz
    ├── 0599080d0a9561eaccfb0a43732e7fc9c3df2cca.nq.gz
    ├── 07f8566881a8be3032b2c323890aa591894c201a.nq.gz
    ├── 082f66b2803aa6903bce5b6a284959bda396e498.nq.gz
    ├── 0a6b199b3695b22417f745653804e9c1a17d3df6.nq.gz
    ├── 0a8cc1afc745192dfa57f46c89ba37af5361aa66.nq.gz
    ├── 0ac58e94f9288ff934ad1dd08405c74834fc0bdc.nq.gz
    ├── 0ac68c469769eada405f086447bee740bc37c54b.nq.gz
    ├── 0b625d06dcdd3ad65a91a939ea0588002d070271.nq.gz
    ├── 0bf631be702be14cd294c44d68b636f187a5f29a.nq.gz
    ├── 0c252678e4a9ecf67c4f0df7a733243584c5030c.nq.gz
    ├── 0d334099e26e9ad59a8eac05217d37522980a07d.nq.gz
    ├── 0d68ae2b7e4af13a14edd0bc6f2951fcb935a9bc.nq.gz
    ├── 0d7b62c0bdd1c6504a9094c3cd6e2dc5b2e9d408.nq.gz
    ├── 0db6b1470698e1f5c2543453c936fdbdbdd0bac0.nq.gz
    ├── 0defbd3875069db78e4ed742d52d65c9d5a05c6d.nq.gz
    ├── 0e7b3dccad043bb7ecb89d783d7214fc97749eec.nq.gz
    ├── 0ecf1d76af8029a503e51aa3f8782b1092307178.nq.gz
    ├── 0eef1d06cc150ef6c844eee94d4d7267c199f4a5.nq.gz
    ├── 0f9fc0092361f02b5666e4bf9e544c9a23085883.nq.gz
    ├── 0fde37aae4b5c3c80a1cc5179fa4a44929b1ad8d.nq.gz
    ├── 1155f2539dd12f6e2f41f9786d8a017325b50737.nq.gz
    ├── 115a9007028434bbe2579ccc48a0cf2340a67cb0.nq.gz
    ├── 1160c4120f6e1a459a927d2af816c0bab0d34c48.nq.gz
    ├── 11fccb199bafca784e6fe9f552d129761fb26509.nq.gz
    ├── 126817cda9d45dc5da8b7f42f590dac62d6924f6.nq.gz
    ├── 14cd018737dc4c835f8d9e6ecab7afd236650ffe.nq.gz
    ├── 157800870e8725473748d1f09b4a30014c0fcb30.nq.gz
    ├── 169774857bd08c2a93d42f0a8c1247e185e7c9c8.nq.gz
    ├── 175ce49fe059e898527ef2ab10d73c6cb7c8a29b.nq.gz
    ├── 1793f2137b559a3893f0c718a8eb2b767c318fe6.nq.gz
    ├── 19d2173b26bd8d89d10d9b6337580415811a37a5.nq.gz
    ├── 1a14a6bf5e723ccd3d050b110d689525a96bb8e2.nq.gz
    ├── 1a3d06f7d2a727e779c382d87cf71b95617cd9e9.nq.gz
    ├── 1a7aac9b6f3ec5993f6aebc64d2b178eb280388e.nq.gz
    ├── 1ab709e3cf77a37346e501ea699fbd4113fa8122.nq.gz
    ├── 1abd3e84e4aae6259f1650e94a95626fecccb30f.nq.gz
    ├── 1acb123c4b2859dfd8cbb244907d2a18c6f5211a.nq.gz
    ├── 1c73d676d200f355a0ccc25a69a43bf85f0f6f82.nq.gz
    ├── 1ca7db60140d0f7a5ba4c89ee68ab08ba9f6cdfc.nq.gz
    ├── 1d98fd78280d9f0043f81ef8222aaa68a3a06350.nq.gz
    ├── 1d9eecacb5b5929861262739198fe02b3cab655d.nq.gz
    ├── 1df3087b91f9b957edabb91aa5b537999d6b2fc8.nq.gz
    ├── 1e257f5ac72acd623da7e0e9285d720b3f5d1988.nq.gz
    ├── 1ea21f63eea2f6f7f6330e02c3c0f61264da97f7.nq.gz
    ├── 1ea3dec8a9fab78f2f1cfed657bf813a966635c0.nq.gz
    ├── 1ec94e8f54e13ad309de2315b5be94ea94a92244.nq.gz
    ├── 1f30dc88a10b55314b6132cbc5f5b457cd8e22d9.nq.gz
    ├── 1f90f99821bbf91f57dda54fa3141b854f2cd2ef.nq.gz
    ├── 1f9af26284153f602687b8812e77fa41db211848.nq.gz
    ├── 1fb8b9c2a57fa651c2f120b98585009074927989.nq.gz
    ├── 2031d2b173242fcd4eec11065fd4071d20466736.nq.gz
    ├── 20a74394fc0d45ddc4c1bc92dccaed7f4e932840.nq.gz
    ├── 212855a9aa6af864a4f8650a40649415e4f10439.nq.gz
    ├── 214726e26280e2508168c8187ea8a6623b78c64c.nq.gz
    ├── 22be2a07d272ceb7f4655ff8eeb632dfdb308f35.nq.gz
    ├── 22ef15c7ed9ead496f8d33d965c5f5bf0a6201fd.nq.gz
    ├── 23695df1ab2176c08b14568895d8cd1393c2eda6.nq.gz
    ├── 23a78c8b3212c69f16dbf415a070957334dec844.nq.gz
    ├── 24217f55df9f31b8d767a5983b6ce8e6d027166f.nq.gz
    ├── 243dc9a1f0f5b62491bef40455528e60f48bc9e4.nq.gz
    ├── 25d36c706e173fd771c287a71576e5b4e04e31ba.nq.gz
    ├── 25eca354d27afad688d4f0528448209c48cf77f4.nq.gz
    ├── 2615da0265cbd5bcef056ef0c3c393ce60a4f707.nq.gz
    ├── 26bf89bba28cc208ddade781808348f0db1bf500.nq.gz
    ├── 2705a02a7de0a1eb82fff5f30dcd7fc34b2363ec.nq.gz
    ├── 272fee26eb260f3b3c10b8c723e31841c5131253.nq.gz
    ├── 2738611b205c041de7ebe279acc9c685800175b7.nq.gz
    ├── 275b0a907aef8dbd2d1ef9786e4327e7f9a7e334.nq.gz
    ├── 27c4cdc9682c0b58a39ec535ce422efa3da4e21e.nq.gz
    ├── 28ea02dec5bc111f51fbfe5a956f9d75de4e5f5e.nq.gz
    ├── 296eba30adad970a4c3e7a1ea11f7535697774a1.nq.gz
    ├── 2978c4a7c98949b3e2e855f82c6eb70dbfdeeed6.nq.gz
    ├── 2a5e4af7f0d19e8036162363c09c45544a58c610.nq.gz
    ├── 2a74c5e70ae04c93b27bd457d19be37eff0c0629.nq.gz
    ├── 2aaea64739e61a6c8607ff9fc4ad2aba4a8e4256.nq.gz
    ├── 2b87a55c5c088796ea09a749b0153c3a3e44b569.nq.gz
    ├── 2d570169a5476d83c1d37100c0141932469a7658.nq.gz
    ├── 2d7cf0d3d49076a19d30fbca5a6772ae11cd8dad.nq.gz
    ├── 2e0c04f5a1811fe4cc5121fc0b16b78ff8f0b078.nq.gz
    ├── 2e7d25eb90db2ffc9a7c4243482951f687501e24.nq.gz
    ├── 2f3c57ce24a6fbc3c620d41eabf105755fd1e9ba.nq.gz
    ├── 2ff7a1d0aab65175254ba3138dfb8dac0a43b39c.nq.gz
    ├── 31c39d21ac5bf1269b4d68f6eeb0bf72b7948243.nq.gz
    ├── 3261d1cbe4d87ae907d00b46d4320e02e087a7e5.nq.gz
    ├── 331241d9bc0577f752d80b161cb0b4b33b8320c8.nq.gz
    ├── 3503186a86c77890bb44cedb4dc28fc6619d2d8a.nq.gz
    ├── 352f452a3212ff080c09e54747354f25a76ad126.nq.gz
    ├── 36bd32de0afec94f732f2f9528cbc2459767efeb.nq.gz
    ├── 37a6c37268ee30b182fd77d109688d35d5577c7f.nq.gz
    ├── 37d2941837e096bce241886b26b7f15b1fd4f61c.nq.gz
    ├── 37dae99e67378adbf66e7adb2fe8fefc6fc5fbc7.nq.gz
    ├── 3837ff354b0a6eee302ebe4ad628d404e8982499.nq.gz
    ├── 39649ca8412a1bda7959376b959bf80c85700b9f.nq.gz
    ├── 3c42f6abe30aa9895378cdf254f12e197cf6f6fa.nq.gz
    ├── 3c8b0d830ee63488b10dfb4d787996b000088dde.nq.gz
    ├── 3c990e82e41defeebefea070b9504129e0e3c313.nq.gz
    ├── 3cf8d1f7e1a33f2a1e022ec343d38c605a1346fc.nq.gz
    ├── 3cffa3c190c37f834e0756c396aff4b62336ad8c.nq.gz
    ├── 3d677aee8ba5dcac3abeb6d1501e464dfb147fff.nq.gz
    ├── 3e73ec137904a7637c80971f970cd7750228dbe1.nq.gz
    ├── 4032817a418e933c6da3b0c197187c96fb7f0fc1.nq.gz
    ├── 403aeffcea067ee7ee0ab6a50eefc3563ab3447a.nq.gz
    ├── 41cc5697d6ce8fbdfcd60920fef857ab4cf518e5.nq.gz
    ├── 4250baad4a19d57e57fb2bae342aacde0944e88e.nq.gz
    ├── 426242a8514d87f321c01146a283f9b6df27a7b5.nq.gz
    ├── 433c601e0cae738ad69b3d43e18436b5968cb6ab.nq.gz
    ├── 43dd2638b4ff4460d52ac9365400e1694aafb5ee.nq.gz
    ├── 43e025d046c92eab2be56e93d40b82522bffc5f4.nq.gz
    ├── 440c11673210689d7f557e589eec82e52f0b078a.nq.gz
    ├── 445368d977c52e122140b8a6e9e9c799a3edd294.nq.gz
    ├── 44c1484f91706532f096cd87eaeb42c895335a72.nq.gz
    ├── 44d131902fdd6c0eb3f8c7a2ca898eadd2cccaf2.nq.gz
    ├── 45baa95f8ae771cc3db950decab93e0f5f1551f7.nq.gz
    ├── 4691f241375127c86a4c159f09ead739e2ea6c17.nq.gz
    ├── 479bac08155c8ffdfe79956f0f819f4e65c43a32.nq.gz
    ├── 47fd5e1b22dde51ea362cd80d03598fcc7573d00.nq.gz
    ├── 48e10b80d1a1804eb93759e1aa650c921d0ff2ef.nq.gz
    ├── 4a7e73b51b68ea336a74daa55f9b90afbbfe46d2.nq.gz
    ├── 4c130def9235def5d5a94802639d03ae69f210ec.nq.gz
    ├── 4c4b961e4879a99e6a5e381d5ff6752b63765280.nq.gz
    ├── 4c66ff0394b4b746ea2b208594dfe35bf2bfc9dd.nq.gz
    ├── 4d063876ef666248406a01ee51041c226b815003.nq.gz
    ├── 4e33e3a39f44e9bd1ba6ac2ff8b21959b81645f0.nq.gz
    ├── 4e567ff3a116aaa70e455b8207af7547162ac807.nq.gz
    ├── 5035096ce8e110ff2fcb04f8d6a0e3dc5832605e.nq.gz
    ├── 5087cedf0f4dd3e0666e2935f9124079ed93d083.nq.gz
    ├── 51245f99f8c1d029f3847849ed040fff1218e1b8.nq.gz
    ├── 51655ef944565630ba0d503d84bc7c3feaafe9b9.nq.gz
    ├── 531e55e6be488ba1586f078680847b9d77b065ff.nq.gz
    ├── 54314d51bbfb13a82c7cb374ae4cbd1df7d06a4e.nq.gz
    ├── 54c82a16e7b289bcfbd66c13e13f0ae9ab84b68b.nq.gz
    ├── 55892dd8e773bb296332baa8fe24145ff2002032.nq.gz
    ├── 55f8653d6d6f67e08717afa860197c8471af1d78.nq.gz
    ├── 57fa794343ba5c9d033bd11b834cf3aca2ca6ed5.nq.gz
    ├── 588addc93d695d526cca708e3afb8dac24f42f55.nq.gz
    ├── 59608e15889868c7997702a6a3d6974158a6bea9.nq.gz
    ├── 59b5eeefb78218fd4971fba598bc9986f4440176.nq.gz
    ├── 5abb13712fca9a4fa59377a9f75afe21ad1a154f.nq.gz
    ├── 5abc3a896836e27ca8189356fe231ae87484ae90.nq.gz
    ├── 5ba6ea12a055714e8880015228993b258a8ccf37.nq.gz
    ├── 5cdd3e0337c884d8d25081289c29eb9794eec595.nq.gz
    ├── 5df154104d728384d8e01f13bb1617ee2b0cc3ea.nq.gz
    ├── 5e3f402c7ad1a0634a6912476b88013655936c8a.nq.gz
    ├── 5f8109c220f65cdcf9aff83c4ccda4b7c4f710cd.nq.gz
    ├── 5f8bf31d203df6a3b47afd1a1791c86842253c54.nq.gz
    ├── 6079cca111351347cd2789b1c8d12953bd083473.nq.gz
    ├── 631e7d0004d12ef64263019dc08bc68ea23e6b23.nq.gz
    ├── 63215831e41425b803f5ce4bce14c1b7b8e836da.nq.gz
    ├── 63965c14821742fe15dbe8a37fe5caab3128fdd8.nq.gz
    ├── 665f367c5decd9959582886de9ac2b9a0288ae81.nq.gz
    ├── 666937af4283563b86c9bc288cca20b667d4cf5c.nq.gz
    ├── 66acd1bc299e33e4ac18b092e058fb940566fbc7.nq.gz
    ├── 697d8c45a6f086b608d1b42c61f994a3f14433b1.nq.gz
    ├── 69fffe21379df8673d756aefa8e5aa0a82179088.nq.gz
    ├── 6b07710e43eaf208a9f4bc43eca431014f0e755f.nq.gz
    ├── 6bfc9e20f5081498ff88caec3c81f8b0e52fb149.nq.gz
    ├── 6ec0002666423b0a8e5f9b89d822e210aee8119d.nq.gz
    ├── 6ee7b3b3d1814bd2b4d0a4829ebc301026f91437.nq.gz
    ├── 7082a2d5b9047bfc09589f387053e24ea490bc54.nq.gz
    ├── 708971a376cb846560d6d1f5a534cfb2b807ebd2.nq.gz
    ├── 70e1010d42675fafcf8f06ee2fa4a56d90d564da.nq.gz
    ├── 70ee051a18a9232c578cb45f8fcab193c93c9757.nq.gz
    ├── 73a5d938556a019728b14cb2953b03f42b214b48.nq.gz
    ├── 747f59e4c54edda7d895a17c189910b9a1879a61.nq.gz
    ├── 74d613b96dc8fb2c483cf3a0cd152095286035f8.nq.gz
    ├── 753205972d430e0e9526a87c46f9d2b9ddde5b47.nq.gz
    ├── 75f971166aa4063943ec9c92aed81e04aac28046.nq.gz
    ├── 76df4a1719f9a71ea0af95b3d3a59c5177fd86c2.nq.gz
    ├── 7725a5ed485c193674436e090c87e8af9e686f96.nq.gz
    ├── 78fe3eeae3ce951e055c5d59804077be4a7796d9.nq.gz
    ├── 79b79829a351ea579c1210dd37fb0ca608a1a5ff.nq.gz
    ├── 7b01bf1f742cdc1c86a8f2d8942c4af1b90a7ac6.nq.gz
    ├── 7b0c024c273b04f0eae3d15aa98295d7dc0a8c41.nq.gz
    ├── 7b4ef1eb54ddbd576987d1c3924a59249d142e57.nq.gz
    ├── 7c4b5844de3393c68151ad5485e0d2f056e18164.nq.gz
    ├── 7cc6bbac04ac77b2b25f7e03a6cd04e684d31ad9.nq.gz
    ├── 7cec88717f60b2556500a9c27f32c33909ecca49.nq.gz
    ├── 7d31a2bb2436f4f3a660b02e47c5400384bc6ed5.nq.gz
    ├── 7e27fbf6a43548809a94271f4121667062414bd8.nq.gz
    ├── 7e633028d42090496966537211a10c285db750b6.nq.gz
    ├── 7ed385da02ed449c3f48a8c63025ef4083061ead.nq.gz
    ├── 814912b0f95669e785403c6561b5439a0d151190.nq.gz
    ├── 8177b1e5852ef2cb165835791d3a1d13b8fe0dff.nq.gz
    ├── 81ca25cd47125b0442bd674c0d64b4d488371340.nq.gz
    ├── 81d156c448c63ed531ee422fbbb56b4d876fef2d.nq.gz
    ├── 8255df02f363c18f5a24793edad4560590a5b57d.nq.gz
    ├── 85d7fb55a720aabe17c27262d1c395fb4b6cf39f.nq.gz
    ├── 860751805b1564e2765296544d6ed94dbe8d1d29.nq.gz
    ├── 879676ec00dc4d4ad53e3fce2e683c788c6aefbd.nq.gz
    ├── 87a87b27218b4151df60e09d06779446fa073f2d.nq.gz
    └── 87e6b84f1b2ed0e27cb36bd9a84fbaeffea4235b.nq.gz

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

[aio-libs/aiohttp](https://github.com/aio-libs/aiohttp)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
