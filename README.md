# Repolex Knowledge Graph of block/blip

RDF knowledge graph data for [block/blip](https://github.com/block/blip), parsed by [repolex](https://repolex.ai).

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
rlex download block/blip
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7e793f93645792a354d7a608b43d35935b017fca
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7e793f93645792a354d7a608b43d35935b017fca.nq.gz
│   └── repolex
│       └── 7e793f93645792a354d7a608b43d35935b017fca
│           └── chunk-001.nq.gz
└── blob
    ├── 005e6b8f9af9f345ecf9316e82457761828e4874.nq.gz
    ├── 014b92f7fc9d4343424a0f576f53c7ec7fa438fd.nq.gz
    ├── 02ab072142bdcdecbd97a20d1bf15b29e4639445.nq.gz
    ├── 02f95baf1d9079ad5c61b22ab9764ed8920292fe.nq.gz
    ├── 0385e917bba5a18a0b2bab1d4f4acb874e09b6a9.nq.gz
    ├── 038fd6e9660a26f5f5259c7275f4a68ddeb1bfe5.nq.gz
    ├── 039d2cbd895552120c3ac1ee86a0fcdb01153977.nq.gz
    ├── 04eb697149e8e11e279e9d674641bdfb38def968.nq.gz
    ├── 052ea550db37ef243a4d76e1754f5638ad0c2bb3.nq.gz
    ├── 0596a00f0629ed23332ec791a43d1490c7625aeb.nq.gz
    ├── 05f5bd236e9bf556f59c1f748bdaa26d054414ed.nq.gz
    ├── 060d4672daa7953bebb964b12bd8cda9fa01835b.nq.gz
    ├── 0617ae2c617cc49af08174b7ec484d5c4d8f4719.nq.gz
    ├── 0743c23a67efadb23e267ba0cfe46166f260df17.nq.gz
    ├── 0746ecfb84ad76a8ad9f6a7a7b45ddd27ffd3108.nq.gz
    ├── 081c4d61da27a1b3d2a3f09a5d42e2b1dc8e2411.nq.gz
    ├── 09661601f01c3396df0f36b9469dca37ef457522.nq.gz
    ├── 09d433a302c3e0152eaf269f3cd9ba0251feb6d0.nq.gz
    ├── 0a1071fb2a56c0b237cfc55cf0ddb05533881f2c.nq.gz
    ├── 0a118ce038bd6af8c4832e022b257b8c031fca35.nq.gz
    ├── 0acaaff03d4bb7606de02a827aeee338e5a86910.nq.gz
    ├── 0ad46204593e3316a4f50c0fe0dd29319026cfa6.nq.gz
    ├── 0ae390d74c9f665cf8b1e5ea5483395da7513444.nq.gz
    ├── 0b11a487a6db4ffe2fc57a56264e18046eb2de49.nq.gz
    ├── 0c168348d4063dacf52b586dc8a3b8ae2f43355b.nq.gz
    ├── 0c30c2226e5967e7b9eb1164b2e19fa783bd1158.nq.gz
    ├── 0e7da821eee0dd05a0a6f0b16c2c1345dc573a84.nq.gz
    ├── 0ec217719dceb757851325c1bd5016509e6f7c41.nq.gz
    ├── 0ed0b89b5dbcf0404483fc19008672ea5a4136f1.nq.gz
    ├── 0ef174cfdde9a9ba5313c7e24a4dd862bf4f471e.nq.gz
    ├── 0f0e2bbda095fe33a7a64661ebfafc3673644528.nq.gz
    ├── 0ff8a6156e393721e2aa815e7ac8d635c2aa1417.nq.gz
    ├── 100b4bd2d01832d96a592d9efff8b82c1a632a43.nq.gz
    ├── 10c8ff15705a53529803bbe80583300653af34cf.nq.gz
    ├── 11230fd5eff117876f1d08d3952c11fc34acb032.nq.gz
    ├── 142bf3b0b7c0be290b1610dc47e87f6348e53bdc.nq.gz
    ├── 145ed9f7b5dd49124c0690788f8a32a5d8feb3b8.nq.gz
    ├── 15bd7a54e75cc2114ccaf85c2e7c2f18ebff76c5.nq.gz
    ├── 16db34d40bc650fefec0f2a00de9833738e5ea94.nq.gz
    ├── 180d7159967cb297b8def4c1f433ad2ad4043c1d.nq.gz
    ├── 18388f7a2ed1cecd794d7bf8b7a594785992707a.nq.gz
    ├── 199d5b5c156e50e07aae3d6937291ffd5e314ed6.nq.gz
    ├── 1a5582a2e62ef5255512d7d16c78a5cad9cb8ed6.nq.gz
    ├── 1ae854f68d89073731fc1a36861963565649eb59.nq.gz
    ├── 1b231c3eb3daeae893599d776924bf9d7d34cb6e.nq.gz
    ├── 1c8f01d97042d39c3a29fd37a93a408c67188246.nq.gz
    ├── 1cffefb3505880d65a46ee1f1439b7664a21a556.nq.gz
    ├── 1d331782118ebd1ffed4d4e4eb73f2ab6fd0a58d.nq.gz
    ├── 1e36da9e5d646bdfd8762f7e177928de9ba4ef91.nq.gz
    ├── 1ff6550d39379225496e3c720ea3e23b18272007.nq.gz
    ├── 1ff741a5a643783b6e20b469d811a4a24a7e2602.nq.gz
    ├── 1ffcb212c9686126646c17cd2f655f545c1713d9.nq.gz
    ├── 215c143fd7805a5c2b222bd7892a1a2b09610020.nq.gz
    ├── 21f5812968c42392a3eaea9b0c6320870b6b8b38.nq.gz
    ├── 2432419f28936aff53ddfa2a732d027e6a6648fd.nq.gz
    ├── 2456bd867688ddc6c8adecb9df50678bff9fd652.nq.gz
    ├── 2483886080fab27f0c725d607131bbe1a6236ddb.nq.gz
    ├── 249a28662218a7a17ad8bd1fe072169ecb666a49.nq.gz
    ├── 256edf7e67948baca261e0158b4e5a2b27da671c.nq.gz
    ├── 2611b180cf9f35d1917b3aef6cfbd0dd0ca5441b.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 2637f40c30f16e39540283118339dab416524e3f.nq.gz
    ├── 271c8489dca1dea5556bfdff1035676875ccc674.nq.gz
    ├── 27706e023b71b04b1f1696b39554c52b66e121a7.nq.gz
    ├── 281bb978bdd38c700c0ecfdb27dee5860d0c895d.nq.gz
    ├── 28d1467b03270881ca33636d62ab094d813b54ae.nq.gz
    ├── 290b16fd39c2eb7c6afa7203ea8783f4aaa04059.nq.gz
    ├── 2913445f6883d5ec5e0b1b918a77d57516bba130.nq.gz
    ├── 29657023adc09956249f6295746c8ce4469b50d3.nq.gz
    ├── 299748ce5bfcccf89225c185218b263ec9f62925.nq.gz
    ├── 2a44958fda319175a5e44ef7f9d722ed99963156.nq.gz
    ├── 2a843f4abeeeb0293f976ad3545b3269581af2ae.nq.gz
    ├── 2bf4a2800f34e73ede2d9e33d970e49eb9fd19a1.nq.gz
    ├── 2cbe867cb93baa381be9e948427eb668a4e259ad.nq.gz
    ├── 2f0b2b3a13f90cecadc36355ae6240d50b8c31e9.nq.gz
    ├── 2f63058a4e7292c0c792b4c74b87c5e56ca8c54c.nq.gz
    ├── 31977312abd5786da7461a6d9f4296d2970c88b5.nq.gz
    ├── 31b84829b42edae20d0148eeec0d922dad2108c4.nq.gz
    ├── 31c0be32c64a25711cceaf1e66bb708aa61e8a6f.nq.gz
    ├── 31dfeef36d37a4142c2172fd62fe6a39369fca73.nq.gz
    ├── 321a014fb256de1dec6d4179f9a98c063b581a80.nq.gz
    ├── 322770778d83f415f7007c36ceb2b390b6af3ccb.nq.gz
    ├── 329c599b1c5acaedaad3f2eb06a8a30eaaa2fc10.nq.gz
    ├── 32f79205b221977c368f675146fb9c8da125f59f.nq.gz
    ├── 331a526b316341081607b10f374c1c9525a0b5ae.nq.gz
    ├── 349c06dc609f896392fd5bc8b364d3bc3efc9330.nq.gz
    ├── 34d68b60a7a8c1773f9aeb54cd93d77f3a3e0aef.nq.gz
    ├── 34e222ef479614fcd0887dde080e5e505e911db4.nq.gz
    ├── 35067bf91eb6a6e6c97693a857cd26ba2a8563f6.nq.gz
    ├── 360fbc586741c6f9925169e0045e14aa5e539bf1.nq.gz
    ├── 3675e7bdd9ffacc1eab86a59ded084cce9354d43.nq.gz
    ├── 3718f6bf8855bf14b86189bc827e11d3bc343bc8.nq.gz
    ├── 37953576f3a0b3bbc4f3868b1f2753aaaf9f569e.nq.gz
    ├── 3812eb46b8fb206606e8a499a59c33d22267b986.nq.gz
    ├── 38287b087bea37aa833267de4cd37616450939fe.nq.gz
    ├── 395f28beac23c7b0f7f3a1e714bd8dac253dd3bc.nq.gz
    ├── 39602873d6f722cc1f0180d44da749a95347fe3c.nq.gz
    ├── 3a089fddc0480f32124859b865a6690d86eee03d.nq.gz
    ├── 3a09f01dbd9b775add8d98164c8aa83dceb72d6f.nq.gz
    ├── 3a6c919bc0ce8d13ae9de233fb88789d6e46d0fa.nq.gz
    ├── 3e5a10ca0dadab1877b1c841ae1d4425b702f1f8.nq.gz
    ├── 3e941cb3615a5c63281b41a8c8af6afbb6a33076.nq.gz
    ├── 3f2fabdd2831f5217d00d3ba5a4c7796237f3bcc.nq.gz
    ├── 3f4bb063748877e99d5c2c91c878a834ac9dab2f.nq.gz
    ├── 3fa3827375974b4bd246762ef986428341d584d0.nq.gz
    ├── 3fd227293d695bcc978af25d042f8c9681e20c67.nq.gz
    ├── 417e033a677a086836edba5f0971ebbb186f47bf.nq.gz
    ├── 4298ea11b47a756c2d51964197bbf5b836649051.nq.gz
    ├── 44971101ec962b7154badb3179ba341132290856.nq.gz
    ├── 45c150536e5f3888554c294f27539c5d41072467.nq.gz
    ├── 47707a5dc8e49e5e9c248f90a5b1f4b66b3c24e1.nq.gz
    ├── 493f7e987587912f3a072b7a94c13a634fa1a80f.nq.gz
    ├── 4a410335203c8e8c79003ecd90e7224f91347b39.nq.gz
    ├── 4be2686c676a5fe45857b900a0f309262f1cf794.nq.gz
    ├── 4c0ce0f73e7999382993fa2363cf7b8e8331168b.nq.gz
    ├── 4ce50fc69154a7372f660f61196a31beb71af69e.nq.gz
    ├── 4d0e2edff28aabd9a135ab675014cc03baea570e.nq.gz
    ├── 4de7057e4ff9b48641fe5258eb49b3634a9cabdb.nq.gz
    ├── 4ede40efaf643b2d0ed892ab6930a144a62c4770.nq.gz
    ├── 4f3cfd2917bb461b3fdb7f0f0d1d195d22268b64.nq.gz
    ├── 4fab1e5c34b7a7289778eb6de5f4823d7af6856b.nq.gz
    ├── 5023fa89e0795c7cfa7415f44cca10ed80185e36.nq.gz
    ├── 506e7b4e115c5de7355f3d5bb782786793cca638.nq.gz
    ├── 50c224b7d882b0a776b57a3cd5d33f45865ced52.nq.gz
    ├── 512949ee7e848c16ab22c1b157bad93f579dfdaa.nq.gz
    ├── 5161813c47f1658aa139076455984ad0779f53b9.nq.gz
    ├── 547625d8c75a16c2daddfe87d16454b632afb8c2.nq.gz
    ├── 5501d37c7dc72b5efccc64d60937e3f9adfe9c26.nq.gz
    ├── 554dfc3c06e591fa321d74ac06f31fc678b700fc.nq.gz
    ├── 55dd408028882d3f104e1e5bbee0fb04708876c1.nq.gz
    ├── 56423ae5d422cba9bc4cf96453ec15fd982a4f31.nq.gz
    ├── 57084a1e98e4cd127286a76d3ce074b8cca3f597.nq.gz
    ├── 57f77ba0b84f9f57804cf6c3e4a944f7e373c55e.nq.gz
    ├── 580777ca68fa22b0682148d95d984804a3e71069.nq.gz
    ├── 584a98cdd1c0dc0ed78d5d6f9d9fcb7f05f16d37.nq.gz
    ├── 586ac8f4cbfad5c80e77b58688afb3ca16cddbea.nq.gz
    ├── 589a79c3da1c5dea2fb054433b4de30bdccdc425.nq.gz
    ├── 589eeec96c9af5fdc71e289a0770b2943601dbf7.nq.gz
    ├── 58bc406fe4f7d141c17b71cb8edae84829e4c64e.nq.gz
    ├── 5923a3e60db91e677fd476c8dfb111a754eeda37.nq.gz
    ├── 5931794de4a2a485fa70099bf2659b145976d043.nq.gz
    ├── 59c2e5dad1e712165b2a4803132f440b5a7d65fa.nq.gz
    ├── 5ad4135e29a5f10cc7eea345d2e236f05f76b95b.nq.gz
    ├── 5d6c3ddb023c2098e96e25b57401b744256ab84c.nq.gz
    ├── 5f49f16f7b5053d7329a1a69ecec0b31dac75308.nq.gz
    ├── 5f86b838390862ea7491d0eeacd69a6a9d7eacc7.nq.gz
    ├── 5fe99d0b3a22c22f0e79758cb7bd11dbdc57f22d.nq.gz
    ├── 60678ac60badad51363e208f299875608941ac88.nq.gz
    ├── 62467ed89964e6b69e90ca9470852a7715b43a1a.nq.gz
    ├── 6251502789caace4e2c4c7add7c4a2065d078911.nq.gz
    ├── 62993136b34fd9ef46246804b1f5d0f5ac6937fa.nq.gz
    ├── 62eebf227ed4bb1eb5dcee6837983509154649a5.nq.gz
    ├── 6318cc084f1889f61e425b0285f162d09725387b.nq.gz
    ├── 63465d4bbdb96baa70604bda0c91e9075cc065fe.nq.gz
    ├── 63dd2347a8d4b9a7cb87bdb3a3c41ccee00479a8.nq.gz
    ├── 63df3b46c164d3027c7487195f5fae264bf30e8a.nq.gz
    ├── 63ecb790498751386667578f8b038cab8308831f.nq.gz
    ├── 6454182e10cdfb337a30e9884815c30a40fd7b74.nq.gz
    ├── 64aebb70cc60b73f1b8ed3951989ced388c1cb8a.nq.gz
    ├── 657f70aa36f786d07c51d5bc34d94ac6d5a2fe28.nq.gz
    ├── 6779f9696d3a83eb43bb34ffc6bd589218b7b991.nq.gz
    ├── 67807b0bd4f867853271f5917fb3adf377f93f53.nq.gz
    ├── 67d3cf47303dee08f3c1df0cc47020b3417d5267.nq.gz
    ├── 67dd8a75fd3d95a350c4187624bbb26d098f7d63.nq.gz
    ├── 680c13085076a2f6c5a7e695935ec3f21cddb65f.nq.gz
    ├── 6846f0ffe20d8eeae21ed4de8db437c73934311a.nq.gz
    ├── 686c494424e02f1c71c2994c4640d8c1d37c218e.nq.gz
    ├── 686de26f3f98cf220ebabf1c41980d58fb5de060.nq.gz
    ├── 69a530ed3042456b95ae8ec3e8b94bbb0ccdde58.nq.gz
    ├── 6a1fceb2f7ce2e593ee5cafa5fd1677a810890fb.nq.gz
    ├── 6a46de6a19dcfa03a8ae95778ddc2d4a4653b2e7.nq.gz
    ├── 6a5ccb82a897ed2fe2ff045d7695b407aab63657.nq.gz
    ├── 6b1342c2f125825ee1967d00c5e863ba5e4597e4.nq.gz
    ├── 6c228f33483ac83ab95bfeeed5b16190d7e55dbf.nq.gz
    ├── 6d0b897c412996e3b1924e33fe9d8368ac4a40c7.nq.gz
    ├── 6f43b594b6c1d863a0e3f93b001f8dd503316464.nq.gz
    ├── 6ff2411268b1c3646e7ade321a9b1b5ac4063f84.nq.gz
    ├── 7147aac7dabfe8bf3951cfdd90d621e7379c7e69.nq.gz
    ├── 71dd8ed3051f7f9fcd94a4282f26de22beb00e66.nq.gz
    ├── 725b9fbe1a3bdf883807d7e8e234d3238c649c9b.nq.gz
    ├── 735f6948d63c8cc7f8233735bb9c8d843c83d804.nq.gz
    ├── 73927ba31082991956a2f20bd9427282de49ac94.nq.gz
    ├── 74731f6236de27bf07d6d806c9d1867d9e5371a8.nq.gz
    ├── 75344a1f98e37e2c631e178065854c3a81fb842f.nq.gz
    ├── 7552f26de9033ded3eed1707c2d73040ee05c2ed.nq.gz
    ├── 7571b82910a04b73abb69e632305c5076e091491.nq.gz
    ├── 7629f0ab2d4c15faaab3872cd36781bb39d59a76.nq.gz
    ├── 76bec15b9d0baa53bc638fa4c724b52ea25f34ca.nq.gz
    ├── 771f1af705f5cef5f578b3a1e7d8eff66f9b76b0.nq.gz
    ├── 785272e0b134eac1cdd81e5e96909e8604aa4d09.nq.gz
    ├── 78aff26d309e30b0a35a206817ff430a35189d80.nq.gz
    ├── 790d43d322646356413a09d2219357a39a594b5b.nq.gz
    ├── 796cb17b55771e8282b4554a86f145a6193f39a5.nq.gz
    ├── 79960c5f07a13f0071f9dcef4e8fa854912c964a.nq.gz
    ├── 7a337b2fb913890a79ab4bfe752d4e55be48b754.nq.gz
    ├── 7a9867f6ee4e32b07244ab72038e5f977f8f506d.nq.gz
    └── 7b8a5d980a590d2ab9d5165cc21e510d2a1a0303.nq.gz

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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[block/blip](https://github.com/block/blip)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
