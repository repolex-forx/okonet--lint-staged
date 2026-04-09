# Repolex Knowledge Graph of okonet/lint-staged

RDF knowledge graph data for [okonet/lint-staged](https://github.com/okonet/lint-staged), parsed by [repolex](https://repolex.ai).

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
lexq download okonet/lint-staged
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 445f9dd042b88528c798b2e25c21c9adbc69a732
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 445f9dd042b88528c798b2e25c21c9adbc69a732.nq.gz
│   └── repolex
│       └── 445f9dd042b88528c798b2e25c21c9adbc69a732
│           └── chunk-001.nq.gz
├── blob
│   ├── 00695cf4f6f38869e31ccec9b5098427c9d93e23.nq.gz
│   ├── 009f4a32d835c803e2b1bed884e3ff3e295fb8da.nq.gz
│   ├── 04563b8ef41a725d616919d2c7c88f8d45a4cf16.nq.gz
│   ├── 04fb83a8e3c9fa84c92397b087b094a62688e4c3.nq.gz
│   ├── 0500728fc27cdb5b3eeacfea7e93a5453d4aeb9d.nq.gz
│   ├── 0e51b7f8d853baafd01b213fdfe4926414d84d54.nq.gz
│   ├── 123bd0ac0c6127054eca934e42e75c618ad1ce45.nq.gz
│   ├── 14990d1b886cdd43b9f6fbe2d97f47a6baa643f0.nq.gz
│   ├── 14ecb3e3712a09e7365ba6a5b7a6f0e42618ee89.nq.gz
│   ├── 1eb0748a29cc7bfe53015b70450351b10e0f4be6.nq.gz
│   ├── 1f5b04a8e36b8c61c5392e3cac03b6376457b668.nq.gz
│   ├── 21b5d1c40e0b044bd946906f99365e3cac1478d5.nq.gz
│   ├── 227fc84e30d76672e070fd629f98dcfcb5c16fc0.nq.gz
│   ├── 22b50d8920f4720559f30a548aeb80603222e161.nq.gz
│   ├── 2857df2b9c5ae7943a5c7520d3ef5f58c853069c.nq.gz
│   ├── 29ea39816e87a980f776ba30fa85dbe9ac27b283.nq.gz
│   ├── 2a949fbbcf25c33242dfb6842edb5af67342edf6.nq.gz
│   ├── 2c3625f80639d025d7aaca0fba4d6139b318c928.nq.gz
│   ├── 2eecc6de30e9d92d96a260e4badaf9dbe81cd96d.nq.gz
│   ├── 2f66f159def60575bbe37e29ed1365017e51b600.nq.gz
│   ├── 2fdc9b346293312918a07e0522478e97b257d9fc.nq.gz
│   ├── 352c6fd1def4264f6c0a2c330485e44a75fe81c6.nq.gz
│   ├── 368965fe766483e274fed7e733704e3bc74255fb.nq.gz
│   ├── 376472f69edb29451de119d83b0f666447254cde.nq.gz
│   ├── 388c0686e208eac88c893a26122ac8c9135aa94d.nq.gz
│   ├── 391046b3414f21f52a78e9536d2ae36fe2c190a6.nq.gz
│   ├── 395f4c18474b6dcbf1c3e37f7453c28b75e010de.nq.gz
│   ├── 3a1595835162712f8be65a5ac43c3b5dbd65990a.nq.gz
│   ├── 3a32d6a9cd65c7ecb6b3cbccfce5a15c96530435.nq.gz
│   ├── 3bcf3b239c89d088ebd2c7cdcf5997a357028585.nq.gz
│   ├── 3c9e4eceb70888728f83642dede9f981902c63e7.nq.gz
│   ├── 3d4e8e1e33ed22d038227636b82c63f6248396de.nq.gz
│   ├── 3d740170a6fac7a22e803697dfac67daa64bb995.nq.gz
│   ├── 3ff5a6a04a4e58db90f57ad713c1736fbcee6f4b.nq.gz
│   ├── 41379f281d9b480f7a635a49f2fd938bc00f81f7.nq.gz
│   ├── 42f2a4034e4e9a3a8c0fb31fbefd50e3ec1ac998.nq.gz
│   ├── 4393da836eed595fe136747cfeb23a028714af3c.nq.gz
│   ├── 43e6f4a78940b986b160faa4f7b5f890cf618e92.nq.gz
│   ├── 44b10d8fa9c56cdbb21781a47a203a02f6bdaa5b.nq.gz
│   ├── 4686a018d7d99753f3982ad0feb83d93db29bb46.nq.gz
│   ├── 46f1807dcdd83058904fa4cd0dc3709ea6bf6122.nq.gz
│   ├── 47a157340ae3e1f74a9ad135b93cd53143efd8d9.nq.gz
│   ├── 49ed8c303971f557fa504e6f0c959e15607c73aa.nq.gz
│   ├── 4bffa216f2edc96dc97bc879b419ffe2ef5be6df.nq.gz
│   ├── 4e7679a8977f3fa4ba0179594e9d34dce73f8614.nq.gz
│   ├── 4eea01dfd73184e16ae8ec56b1af8474c678877b.nq.gz
│   ├── 4f2abb12221138c8a5dcbb0e5189d7621569041c.nq.gz
│   ├── 4faa8c2f9ccc7a872bceb092880cabb6205bb543.nq.gz
│   ├── 50e2d47dd1be81030e2c508ab552e5adf21c7c1e.nq.gz
│   ├── 515d44533af27731465968509f6f8c1bb4529c5d.nq.gz
│   ├── 517c0cc45aeab31ecb46992cd8ff6de228d78114.nq.gz
│   ├── 51b2d7fbe612fee8d88b6a687ddcc0672a10f5f5.nq.gz
│   ├── 53422dae0715989d20c09b995f22342374ecd277.nq.gz
│   ├── 55eed701e7e438e5f30c1bc9cea2a4e61a53a1a6.nq.gz
│   ├── 562c57a7fc6ea4d001793627701607a386aa30ad.nq.gz
│   ├── 59c75ed866244c6eb3f1eccf40615196e2f4c768.nq.gz
│   ├── 5c3a7b34f9fc67783acfcdf31c57184a8b87e45b.nq.gz
│   ├── 5cd3cc5d21c39550dba3561aebc66da0ff11004f.nq.gz
│   ├── 5fa327cf747a39ed0f16294bc98544708a8ef6b2.nq.gz
│   ├── 624c29b21f86cdea05e0ee5c75b9b2de118277e5.nq.gz
│   ├── 6313b56c57848efce05faa7aa7e901ccfc2886ea.nq.gz
│   ├── 63218581265b62930c2b723d69c398bccd8e3ed0.nq.gz
│   ├── 637117d51d057becab8bdffcca1ff31bdc386f85.nq.gz
│   ├── 6553c6d178720ca47cb520b6f2085811d47ed65e.nq.gz
│   ├── 67429d3210f79400bdf37d10be05d21f956cf234.nq.gz
│   ├── 6c94198669e811ff6f04a25d705fdb4169750475.nq.gz
│   ├── 6d619e3352a56556954b7467524c88b04e1aafc6.nq.gz
│   ├── 6ed977d19460efa0182a957b372d640c41d2d7ae.nq.gz
│   ├── 6f470c43644b55bdcaf12d050e096e0b852ddd34.nq.gz
│   ├── 6f6901dec2de8e7be88d04bead6ee82a4738a5ff.nq.gz
│   ├── 6fcb5cad796c702dacead1bdaf7e2eacd76a534b.nq.gz
│   ├── 70de967a3c2c16b9b8511d6fa7fec49b2088d154.nq.gz
│   ├── 726c0273a3f381bdc0b3494baf31d02a0ba88bbe.nq.gz
│   ├── 73363561ecd31fa0463cba006ae3098f61925625.nq.gz
│   ├── 759c62fa7441ecc3c5fa0146e6929cbded6cd6d5.nq.gz
│   ├── 75ce5fb796df7d270ecd171e051de10a9866a0d1.nq.gz
│   ├── 75eeacee48759ef90249df5524639d61bce10918.nq.gz
│   ├── 762a224b5e8cb6d3e2bc564e5e48ee9ef2ded7f8.nq.gz
│   ├── 768801d9c1291dadea0d822a0f82f90143228200.nq.gz
│   ├── 77ffe8f2423bb24ed80e2e23b57847a69c137195.nq.gz
│   ├── 784f5eb22a7503bf5045414008074d722aa731f2.nq.gz
│   ├── 79d3b30012e474ba511284dbfe8c0e3b64e14bb4.nq.gz
│   ├── 7baa608f2eae59b3c091ea113bb4e38548764fa2.nq.gz
│   ├── 7c4710c132cbe8d1a772e84df0a1197867890a2f.nq.gz
│   ├── 7c58952f69c30b5d17c4e7c8dd280af9598daa56.nq.gz
│   ├── 7d75639fc7e984aada9c4339092002ce1be9b65b.nq.gz
│   ├── 7f7235215681697f2d9cb788f61873f7872ee29e.nq.gz
│   ├── 80aa5e8f2d2a6b58b6e618fae9caa5f8dd78c913.nq.gz
│   ├── 81750b96f9d83b395f285233d54ec0c9df9ab93d.nq.gz
│   ├── 82bab3eee35ea6530ddbb40bc1beebde6a7ceac1.nq.gz
│   ├── 82bdf706a86bf72d172f110e5ba1b0df952c6dd6.nq.gz
│   ├── 85079e9fb69cc628288b8cb76e675f196d9ff5b0.nq.gz
│   ├── 8646a68e4765ebf4339c8ffa184d242f8729059e.nq.gz
│   ├── 892f4ac3d8700cd587dd8f2fa0deaeb0a1069bc4.nq.gz
│   ├── 8b3eba6cd64539c267030f63509fc0822f8d953d.nq.gz
│   ├── 8d4a598093387a8919f3a6a28d030bfe76f047df.nq.gz
│   ├── 900088b03ea319f3f7ad45d128e3c112f49e9aa7.nq.gz
│   ├── 908d5fda4950f7d3faeb568d773104c479d201e5.nq.gz
│   ├── 913d27d975dc3e35ae58beb9e51cc018c4bfd97d.nq.gz
│   ├── 932017d9b59ef0dbc5d345a87f7e367d22c51836.nq.gz
│   ├── 9327f480e3020b8252e20543a01e26cf7515c528.nq.gz
│   ├── 94887b3f2d1a2b4f230bf1eba882988dd67d7522.nq.gz
│   ├── 97c6a0d9fe7eea374254b2ca94fc4bb84fcb4918.nq.gz
│   ├── 993f8d81cac48132b5ae2ebdc8ca452c7217caad.nq.gz
│   ├── 99538e46e79fc0e368cc9c62176a79e9154c26a9.nq.gz
│   ├── 9c71c854935a62530357e766f54a3806e343ce42.nq.gz
│   ├── 9de55315caee4206c973a27dce494961e65dfd50.nq.gz
│   ├── 9edef5589c16fab72a5557dbff87f5b22fe5f8fc.nq.gz
│   ├── 9ef07c672227c5b0e4b41830e4ca5adf78898984.nq.gz
│   ├── a1ae553496fee32070d3b5fd05da059381a59581.nq.gz
│   ├── a45fd52cc5891570d6299fab38643103c3955474.nq.gz
│   ├── a4cb1338bf560bcbbb6a5d56eca2f6eef082df48.nq.gz
│   ├── a5c9672aeef5dc7611971a378cc87f09a64dcf86.nq.gz
│   ├── a6c0ae06af407906714117f12b7ebec727b5d656.nq.gz
│   ├── a6c5c7965ed7dbe3e83d3a91c2052d35107e8bba.nq.gz
│   ├── a6e041ce65989c3bf5f734d33c12c1417ff18a82.nq.gz
│   ├── a7fbce4de42aca1815667f3cc081f0ea50761873.nq.gz
│   ├── a9dd147d4787b2700ce75c5eb8213aa3c45d8105.nq.gz
│   ├── aaa8f94222e6003f912fcf4035b18f7a10aa1bbf.nq.gz
│   ├── abdf3860925c88929baf6b97c9d295b6949c90e4.nq.gz
│   ├── ad226ff1cae0a056895a302d7f1b080ae773bb5a.nq.gz
│   ├── b2a60bde450c92e0514bba6dc7bf477b076ba898.nq.gz
│   ├── b412efc2480f2fb813936962eb835100ee1414dd.nq.gz
│   ├── b64729438914c46d02377e6894cdf6876b8adc76.nq.gz
│   ├── ba021eb46ae5da25f60bdfb56c7a9633e465eba8.nq.gz
│   ├── bb628789ed5fe9809d1ab9c073fec2ff51db6997.nq.gz
│   ├── bef576ce1dee9be9e66f487f502e3748140a4421.nq.gz
│   ├── c06bdfbe9bbef6325ec0ad4447f5c6700cb6085c.nq.gz
│   ├── c3a05deeed47a615b7ea3453e928fa9cd84f7c76.nq.gz
│   ├── c4dafccfd49799790c9a457dfc48eba303c3b0a2.nq.gz
│   ├── c718f9baee3f265aadf99a1b9db16d607936a9fc.nq.gz
│   ├── cb4ab0bde520aff5a75f1c6ab7438ba15188915f.nq.gz
│   ├── cbf03e47f797b856d4018ce30191e33deef77b1d.nq.gz
│   ├── cd365dd8d5651306f326fe24ccbef798b86f0d40.nq.gz
│   ├── d38bd93a023228346cec02b9eef182fd10c587e6.nq.gz
│   ├── d5603cfd25bdb2d74e4dfd116a73ce0994a189b2.nq.gz
│   ├── d9880fa612edb9d705402853091d831dfb97f55e.nq.gz
│   ├── da30e6f639d31307ebf503691aa991bb93948f8a.nq.gz
│   ├── dbf501de650d61f0ce285a714787bdb1f1317259.nq.gz
│   ├── dd4c6b5364286d653c862cbc6b992042c577178d.nq.gz
│   ├── df0c84c0ebbe58d6610909843ac71f14ec7feaed.nq.gz
│   ├── df7963d08079897bcc2cef87010ca89dec17c30b.nq.gz
│   ├── e0c402d141c283f1b62b41291827e50659acdc50.nq.gz
│   ├── e10af23bb7d4df938101068ddef0d86d3f7c6533.nq.gz
│   ├── e31987bebc662687061b648a135b02ee8a05e492.nq.gz
│   ├── e3a4845d63ff2c06b917b6cbc4fd35aead7a9bb5.nq.gz
│   ├── e49e7cea4985054a0108cf162e2d886b1feda2aa.nq.gz
│   ├── e4fa61c44d77e126f85deb9a3c908ac05cc88a1a.nq.gz
│   ├── e5355abcfb2ee7218a1b3122112b1b84e6250c06.nq.gz
│   ├── e5b6d8d6a67ad0dca8f20117fbfc72e076882d00.nq.gz
│   ├── e90cddd5d27fc0c1e81b3dcfb71f37ad5f982af5.nq.gz
│   ├── ea6bb48b800e4101c228f3aa73288739afa71c12.nq.gz
│   ├── eac5da6e042d655a0c4bce1c45e197ce36d1dc44.nq.gz
│   ├── ebb288a56cbf9164c8f72155e2203ce673ad0c05.nq.gz
│   ├── ec9066fc51449deec724edc0a328d5ae524a829c.nq.gz
│   ├── ec985e16d30af47b57218bad9ad364657086c477.nq.gz
│   ├── f251022748bc73c5a1895bb567550911002a4432.nq.gz
│   ├── f528c959d6c0fd78233832e95dbdbb02729dda38.nq.gz
│   ├── f5f1c9d4dad813ce942db14189fb4b3147fe2c2e.nq.gz
│   ├── f83fda7ff0bbaef1d3996a0e14666d51baa5b78b.nq.gz
│   ├── f9bbd3efabd8a78a6898a1a332818d122575b4d2.nq.gz
│   ├── fd3222903ec5e7e452faf5828679a919460d6c81.nq.gz
│   └── fe7464483953a5d79449445150a8703901cdf5b9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 445f9dd042b88528c798b2e25c21c9adbc69a732.nq.gz
├── filetree
│   └── 445f9dd042b88528c798b2e25c21c9adbc69a732.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 173 files
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

[okonet/lint-staged](https://github.com/okonet/lint-staged)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
