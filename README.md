# Repolex Knowledge Graph of GREsau/schemars

RDF knowledge graph data for [GREsau/schemars](https://github.com/GREsau/schemars), parsed by [repolex](https://repolex.ai).

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
rlex download GREsau/schemars
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ed6186319d5ebf1959a03f558df375d2bb5c44a6
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ed6186319d5ebf1959a03f558df375d2bb5c44a6.nq.gz
│   └── repolex
│       └── ed6186319d5ebf1959a03f558df375d2bb5c44a6
│           └── chunk-001.nq.gz
└── blob
    ├── 02658a7783b60a6ff1c01beb3baeaf2fb8889ceb.nq.gz
    ├── 02f3795e99504f3b199cbc66fce3ffcf204dc8b6.nq.gz
    ├── 03b341be36e1a691d8ed3457232afd9f7af1c6c6.nq.gz
    ├── 03f91c6e1c8a09755c343c95cdebb64e9afa7eea.nq.gz
    ├── 075caeeeb5874c93a10a3639e0503bdb841c24d0.nq.gz
    ├── 075df0e4a04e3e0a035cc064cba768df4cded1fe.nq.gz
    ├── 086d50b704b0b8e646afa4bc423ad33549a6a7ba.nq.gz
    ├── 08c312371c6d659146df255952f24f71c03ddd6b.nq.gz
    ├── 0999c83854fff0248076d170193ebd713c1358c0.nq.gz
    ├── 0a66d93b0b757d182777d243ee258fd387d6d48b.nq.gz
    ├── 0afa5eb18adaac836067a0b6c0bb4245a8a879dd.nq.gz
    ├── 0c5fed71038a956714e84c661503604f881bc21b.nq.gz
    ├── 0c7ef943d5365ad48bdcff47c57ea7ff17d1dabc.nq.gz
    ├── 0df7e3dfcf268eb3360a989392938d1cd2c925bb.nq.gz
    ├── 0ef2d7ab6b0302ce4974ceb30845a390c6786c13.nq.gz
    ├── 153ecc066e3996ac9c4f70f31057958b4bf476dd.nq.gz
    ├── 15d31b1e86bc3f50214777144e74dfc9efae1b15.nq.gz
    ├── 177737a1f5655cba359e4c1b5c4cf73db5259d69.nq.gz
    ├── 198ba4c0ae6e0f9a0aff27567b86dcd2f01383aa.nq.gz
    ├── 1cfcf819985bf236364fc8f19b37f514b47e3b09.nq.gz
    ├── 1d126d5a09f31affd2152d689b8da695a1aa4ab3.nq.gz
    ├── 214a758d64d2d9f1d144f4ce903764208a3bab3b.nq.gz
    ├── 21c3bdcf5de317806eda1a20694e540483abfa65.nq.gz
    ├── 22b3fd9f941d11d2a0287bc63cdf3c7ff4622860.nq.gz
    ├── 23b67caf879e986d46f8de6ae0e4d136d101bc4e.nq.gz
    ├── 24de317b0536420410ab692bfc77030d74c553c6.nq.gz
    ├── 2753d24e45006573cfee49305be8b9d441a792ee.nq.gz
    ├── 27b7e55b2caa6cb3b69552eea3bb0730e4572612.nq.gz
    ├── 2a5de96f63bcbe37b1c9e73c0cb3773c7415dcde.nq.gz
    ├── 2e5a5744d5b05ef91b6cee89a4b8c32d17f472ed.nq.gz
    ├── 2e856607816d3b59f31b2c17896805ad8a795dc3.nq.gz
    ├── 2ed5df808d07fd628ade899f26efe9632f91f1a0.nq.gz
    ├── 300a19c17a098152a8ffcc73177f29a558b3c296.nq.gz
    ├── 307a0d1c0819bef23300c02f4cb48f7396761d0c.nq.gz
    ├── 30852e0bda8d5898dedb10eafec9b9577ee916f6.nq.gz
    ├── 31c4de0da2ae3346c446fe38fd4b4dc5931385bc.nq.gz
    ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
    ├── 32f4edda6023144f4a32604ea2bad280da0b9279.nq.gz
    ├── 335daf3c25fb75baefc2b72aa03df35f9691226c.nq.gz
    ├── 35dc261b29d676a90e910bcc638cd097017b5e1b.nq.gz
    ├── 3814504d1e707abbf46630b67576d17b66bc973e.nq.gz
    ├── 38bf6a17305ebc859f8dd771d331a6fb401980c7.nq.gz
    ├── 3ad4a18dcdf090eaf0026302d740b8b928f77e81.nq.gz
    ├── 3b0df974862727a365bd6d10b394482d4863485b.nq.gz
    ├── 3b10e0d2dbdb43941102124a1f85593e0ded69ef.nq.gz
    ├── 3f0afa071b28d7f949329d612442c8c90ecfc2e4.nq.gz
    ├── 3f8a9ea8447ad2346bb56dc7f1f6a1406370aac0.nq.gz
    ├── 427a666eb96738ceccb3cc7fd15bf3846bf94874.nq.gz
    ├── 44a27080096f8e6977e6422254d9e862e03538a6.nq.gz
    ├── 45198ff244567602963179a26710132cccd54856.nq.gz
    ├── 45c7a7990292fa7b5e80e5355db00cec722bb706.nq.gz
    ├── 45e7b13acdfcc884f9ff301645ec6ab76e0de852.nq.gz
    ├── 4932fbed2f158f2672f4a1a5af7f4dd076b1e492.nq.gz
    ├── 499e6701bbfd61683299a3b590a832154c4d9be2.nq.gz
    ├── 4afe228fcccda3e5727932ae9d09c88bdda3bfb8.nq.gz
    ├── 4b8c5426c80a5206b720191de085f752d5515a27.nq.gz
    ├── 4c473d1c62e754238aef8b26ab053b4841b1d68e.nq.gz
    ├── 4ca11c766212786f656bcb0dba392d6dea0faebb.nq.gz
    ├── 507811fd1f06e205454bbf03e81f0864af097661.nq.gz
    ├── 50cf7b9435e4f63e80e101abebe462088495c821.nq.gz
    ├── 51e75100f4561f1e3202600c5a64a35bf4a7e816.nq.gz
    ├── 535e71c40b34cb5c2c0772bde2a216093961cdde.nq.gz
    ├── 53c78fa6e18fb4d3d494d872cf00a99d6626c22e.nq.gz
    ├── 53f27387984e1c169172a596485bec1b8d6ba316.nq.gz
    ├── 55dd6767e1f7b4944b53639fea60e3f89425d22b.nq.gz
    ├── 58db8b92eac0643567193ea1df2c75a01d8717bb.nq.gz
    ├── 590b7990d463b5042fb58bae376898dce86decd2.nq.gz
    ├── 59913492635e8c2bccfe509378b494f7ac28e520.nq.gz
    ├── 5e7112684af455284afbddb3a0b289ee21b8db69.nq.gz
    ├── 5e8018fe66933af023b058077c3941ef7980cd3d.nq.gz
    ├── 60e91c513dc55696858ec14c5a0b1deb5c7fdd50.nq.gz
    ├── 631c462c835b56f11c1511156297fa5741a8c292.nq.gz
    ├── 637b719e599feccb98140f37af6a707a6445dede.nq.gz
    ├── 638fb6c01ab33f6d47f3db875c3c05f71dc8e085.nq.gz
    ├── 6570accf93dcb149651a8d02338807f942d0ddcc.nq.gz
    ├── 65ec8d3a9272d5fb01a3ff87e08a400acb22f05e.nq.gz
    ├── 66f4a491fa594aef4a3aeafe8c5908f01d472fbf.nq.gz
    ├── 68afabf4523e94352d83a7c14ce1bb705e65a9aa.nq.gz
    ├── 693699042b1a8ccf697636d3cd34b200f3a8278b.nq.gz
    ├── 69f6d742d771dac1bbbc17b618c068d67b603cfd.nq.gz
    ├── 6aa73e93729f3efacfcf3bf6dee0abc9a26b48a3.nq.gz
    ├── 6c035dd6716ed88242613e507aedb969b7b6ed4b.nq.gz
    ├── 6df51ccad589bdf8444f63a6023484b647dc7bec.nq.gz
    ├── 70fa4a2b4ca5aec56dececd7b0634cfac4452f14.nq.gz
    ├── 7306cd92d363883f0ec6bd29b369bbea5a5996ae.nq.gz
    ├── 7342ad9e200c0820d8c6f22577e9d46ae9b2ec49.nq.gz
    ├── 7482be0fe8dc9a93dfa507fa75be592509e541f0.nq.gz
    ├── 75a0d5face5e7984858de8a97df82fc4cf5d4fb4.nq.gz
    ├── 77055dfb5040a7bee8847f35a412845d1d56b95d.nq.gz
    ├── 79070ac471b463d498742c885024fec85f684815.nq.gz
    ├── 79536e2fc1f983877e1bb447a7c1ed6d613a8fd4.nq.gz
    ├── 7a049c8b627dff935354a8e1ff51495d87eaaae9.nq.gz
    ├── 7b18ed276eee3382966352a916de8b5ad5f95f87.nq.gz
    ├── 7b6e217f79b41fdbd911d5179df0038e051da3b8.nq.gz
    ├── 7bdc95954f8da15487cdde71a65377a842623c2e.nq.gz
    ├── 7df9249a815b0023ba133f61fda8ab36d19e83c0.nq.gz
    ├── 7f1c08aed66babdf7682ee1b74b7b96abd24a005.nq.gz
    ├── 7f84eba373cd5c319e85a0adf5377ca23727653f.nq.gz
    ├── 81457c7f6dded565c658b84df07732b04a3460c3.nq.gz
    ├── 8308eb1416fc81abf0fd3d41065bd89055419404.nq.gz
    ├── 837dfae689fbdf4f82e8c3016200f997699bcc8c.nq.gz
    ├── 857f637ed01cc909285bafc708e6ae79d78d6460.nq.gz
    ├── 8634a2391d825347cdb3ad510be4608eec949f9c.nq.gz
    ├── 870c2f95ec1b73c28947189210eb41dadff72f06.nq.gz
    ├── 882c89c362db6078ef74ba747786cfa695bdebfe.nq.gz
    ├── 88685242ef286feb290d948830573767dfe9d325.nq.gz
    ├── 89229255887cfeeb8d04cf495c9676633979915b.nq.gz
    ├── 897e415a4418e0ee17712f6faa8e859e4bedfce3.nq.gz
    ├── 8f1a5b53781d25c8a746bac5a0e0fde45b2b72d8.nq.gz
    ├── 918de83ed3f044ce06850cd254882d8a3eaea95a.nq.gz
    ├── 92a34f30e5bcab04a4a12d855983d95e025109a0.nq.gz
    ├── 92c3370005ede49c63c49a995b4eb5ab1de2b833.nq.gz
    ├── 92c54397148ff8c02089ac12cec71f78fa168a32.nq.gz
    ├── 936e7406a297cd9e09fe63664301fdbabaae69a0.nq.gz
    ├── 951e0952508ff7339d597652edb7eb7e67dc8110.nq.gz
    ├── 9533cbaf8bb74772b74775467ff67b34ef5d2b87.nq.gz
    ├── 9d50961323c3959fd7783cafd391c783eb064e94.nq.gz
    ├── a0ff606458ba44d593a20d6288f4b5983f803df3.nq.gz
    ├── a2159dbb67473c731470ecdfc62ee6b824642232.nq.gz
    ├── a3163065045cf997e028f22452fd230eab956816.nq.gz
    ├── a34c5ff401c562e5c7a1dc2d7e7dfb381963daa8.nq.gz
    ├── a61d4b5be47bb7d975d073baced9fda6c4f03a35.nq.gz
    ├── a7016b2d604eb0f3b2dbe3c01ce2bf3783742cae.nq.gz
    ├── a8ed79d0e1c1c7579dee4ab72ca0b4b42d43cfaa.nq.gz
    ├── acf59b1e6de08a03ad9193f4271e5ab5a35d811e.nq.gz
    ├── ad71e7804713c9023aaac40abbe75700e21f54b2.nq.gz
    ├── ae67b8437403f999483695b1119488f9bccdfa18.nq.gz
    ├── b08296519953bd095e3d42046f68d2a5ee1bc749.nq.gz
    ├── b124ae77da16a396919cefcfcc8f006edbee3b7d.nq.gz
    ├── b2753109ec8dc29f45be12b2eacf8340a094f13b.nq.gz
    ├── b2d67097b13ba16aad1e351d05e4f41445608197.nq.gz
    ├── b5ead75483930c620905d961c25b1a0a52c059ea.nq.gz
    ├── b60e5def8fab607ef615e584f023d8ec59b7b02f.nq.gz
    ├── b66531944d59f9452b2bf3899aa8d211ae507aa6.nq.gz
    ├── b685cdc86c4f72a524d145e9b90e8e4687738c10.nq.gz
    ├── b69ea9a6d060c868f780b99d2eef47e99ddc11f6.nq.gz
    ├── b6d2a35b6fc9a13580b47da1483518420d816f0b.nq.gz
    ├── b7295f736fa7344ba0fdd2a36ecb376fe532a392.nq.gz
    ├── b7e38d77cb178b0a3f53e54614477f9e71523c5f.nq.gz
    ├── b8d0fb41dd50f4158e96d73fbfec9eb67a1d0159.nq.gz
    ├── bbacfea437b1b4bc2e285226b472fcf3c3023e8f.nq.gz
    ├── bd4a0d851a56bf2780b8fda01bc340fdd56cc530.nq.gz
    ├── beba6f39ce45ab8b90389fd96b42ce821fb3194d.nq.gz
    ├── c3faa4f13abfd8a4e30769300daf8c7449c3ef29.nq.gz
    ├── c42d4224fd95bbd6e3f4f6da65f90440a6cdfb95.nq.gz
    ├── c4921c5419bdfa4417306a22932a10f8c4bb53d8.nq.gz
    ├── c4e7fee7f0481dd4dcfcfb76c674727b81160eff.nq.gz
    ├── c60cc2a63d2b88f1bda6848f8c8bc21076b6af02.nq.gz
    ├── c6ef7d54f300da8071dcde8d15133a21889870cb.nq.gz
    ├── c86bf7f5308218d27c2543d8005e2a59c3a62310.nq.gz
    ├── c8c1412f6e976ef5dbd7f4f89412f501fa639e0f.nq.gz
    ├── ccbedc4cbaa74896a598b602389fecf7911d2539.nq.gz
    ├── d195723d40081963dfd7f51c0e466edc0497c633.nq.gz
    ├── d2bdb532ebd14456c2e8e50148aac8121299e5eb.nq.gz
    ├── d4ec5b021c3922a7f1341796b2369070f456ce1f.nq.gz
    ├── d784d5247f4356e0207f7b257ac0a9881a2bf9f3.nq.gz
    ├── d7a1540520dad9b5e6d4acbb065f59b5ec032468.nq.gz
    ├── d7d21798fcbb45fecea0ba28a14bee6ec003d268.nq.gz
    ├── d99ff5a9c9de95d915e15a22468a9ecfbd2eb937.nq.gz
    ├── da5a847430c0557b36a979150b12b54950387360.nq.gz
    ├── db01d8d70e391f0092463c6391148d048f9e48eb.nq.gz
    ├── dc1dd7cd06b0a735339ac81b8b5e2e5d1146d081.nq.gz
    ├── e2af3a9bd2617fce1e0b455362d8cfb25e597e5e.nq.gz
    ├── e336db8f958bf455380358eb8daa134d3e4f8986.nq.gz
    ├── e439f5014dce89bd353a50b3a4afee7dc8575596.nq.gz
    ├── e44b4f24cd426355e4ad495b85d32c732466126b.nq.gz
    ├── e6eff2e974987b321317e3b84bc15e2dbc95d84a.nq.gz
    ├── e7932d29f1f47cc0164e40f07b3cbf699982787d.nq.gz
    ├── e871e761ff3a6ec7c12d62565fb00dcec6225915.nq.gz
    ├── ea0950498cec24d27acfcc736e9bcaa0f070ef01.nq.gz
    ├── ea2c2335ea9a6a07d0f65bfa4f583766ca22ec41.nq.gz
    ├── ea5b60640b01f74e295037aa8a6b7d4ea278a739.nq.gz
    ├── ea877bba62eef2a4a89fdc571ae699ac29fa11a6.nq.gz
    ├── eb3e8cac853cad8aa2e72ae8c3d3c3994ec1c7f0.nq.gz
    ├── ec563491c5f409308df9ea50af24da66088ee64b.nq.gz
    ├── ecc46353d8a2b7c3256a304390a3f5fc8d6bc64d.nq.gz
    ├── ee0adb69d516b15b70879c8edb07c6840db220b6.nq.gz
    ├── eea2f926790c72f77cd8200be00e411a19f21e4e.nq.gz
    ├── eef772417a2c7cafefb63fff88ad54f491aee5d8.nq.gz
    ├── efe245cde8a03231ba345a9883f8888abab4da49.nq.gz
    ├── f14cbe350ae0f8073ee92e97f19c46b96f6c497b.nq.gz
    ├── f24c96c15f80a490996411376afe650610b2696e.nq.gz
    ├── f2d75e694d3e60b46b8dc832ff2993d2468ef1b5.nq.gz
    ├── f2e972dd875ff4c1f09f03d2e1f3fb00421573bb.nq.gz
    ├── f5f41562d20e4e92a1cd04ffb7d50a02d11e0867.nq.gz
    ├── f679e0d895ae794cb1720c8c5b6a80dd13236d49.nq.gz
    ├── f687fe40ecf802e4045da7126e6a614a254e7873.nq.gz
    ├── f7ec81fb2f072e2bee217b3723add399151dfd1c.nq.gz
    ├── f80088cb9155edca521b7a69e5e7d32a73d8ae2e.nq.gz
    ├── f84fe228d0c0b32b88b1d641277cef534ef0a313.nq.gz
    ├── f959ca8671b474d36a44b4ebc219e1f8bd92e466.nq.gz
    ├── f9a8841924a568b5d49d510bc42f7c16263be6eb.nq.gz
    ├── fa36983435f131ee8a3d009ff41532d38bffe3ce.nq.gz
    ├── fc72777c0aa44d3e0783d6024961285c7a610385.nq.gz
    ├── fd7f74ff32bec0e3d8bac7bcfa4c5ec310cdfe97.nq.gz
    ├── fe3bf83843f72059bd0f3e2df81b72d78ac8132b.nq.gz
    └── fef0fe37ad660b18219924d870caee00580cb41a.nq.gz

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

[GREsau/schemars](https://github.com/GREsau/schemars)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
