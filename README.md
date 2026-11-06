# Repolex Knowledge Graph of sphinx-contrib/matlabdomain

RDF knowledge graph data for [sphinx-contrib/matlabdomain](https://github.com/sphinx-contrib/matlabdomain), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-contrib/matlabdomain
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b40265b8a1b7c92e0e74ee4a59b8843dba57ebaf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b40265b8a1b7c92e0e74ee4a59b8843dba57ebaf
│           └── chunk-001.nq.gz
└── blob
    ├── 007bf4aa881da59a1502a8723a0a4634a3e83946.nq.gz
    ├── 019cb94bdedd5cfa399957215931b54385493c16.nq.gz
    ├── 01d09eb1581395ffbc1c76cd9f86bbb7e5c58190.nq.gz
    ├── 03addf63a4e05fbbcfef34425366d947ae024aa9.nq.gz
    ├── 0693b482138bfd49f46f9da24a7c9ffdc242009f.nq.gz
    ├── 073fe0d249478bab6ca278cd32b3d23565205a74.nq.gz
    ├── 0751dfc67b54bba7b472f39e8f5344c7fe2e27f6.nq.gz
    ├── 0801d9aae182c39dac32de2047962049bcfcbaf6.nq.gz
    ├── 0a168577e016e8e67fb1d0600add9b0d5efd2fbf.nq.gz
    ├── 0ade298ea81de17f02358617fbf384c66c69d91a.nq.gz
    ├── 0bce52df18179537fa4b368de0bbbda51bb3776e.nq.gz
    ├── 0cbd8b71eb53c19395a15f81b60eb00a3422730c.nq.gz
    ├── 0cc80f92bdcdfb790357a2d26f6dfec3628d9a4d.nq.gz
    ├── 0d96f36c0079aaa389f2f8355d7c28685690ab06.nq.gz
    ├── 0d987655f1e05a105df5c992601421de3a2a8d0e.nq.gz
    ├── 0de1423d3875965aef5c5b1cbef41d24aa8d3ddd.nq.gz
    ├── 0e4d19ca3e85bf2b8324adf7d08acd93273425cf.nq.gz
    ├── 0ebaa028dcdc4a7b26d458db3adc0d0712f1f2e7.nq.gz
    ├── 0f379c3eaef2f8ff2fee4acad43882b5ebbe755e.nq.gz
    ├── 0fed58a34a54eededcd3df0d79f1cc95f768c363.nq.gz
    ├── 12251c7542e90f6fe6a9d289cc641f14f6d68594.nq.gz
    ├── 126f77078f6206c0109fbe1b28ae235dd230905d.nq.gz
    ├── 17e26374ae7c66a8fa2a0027865e9d9ac72e5ff7.nq.gz
    ├── 17ed7524ff280cee34e7f5323d9a631a6c453a48.nq.gz
    ├── 1883f01016a60114a45a579d63f8fa47b37f1403.nq.gz
    ├── 1a61a15b3a999af78a1bdc33c772619b0e131543.nq.gz
    ├── 1ca81b9c76f43cd657fc55e3ee425c1bbc5c8425.nq.gz
    ├── 1d9bada856a2a454d9643d73c6d1ab16f63cbf2f.nq.gz
    ├── 1fe7c011bd1f30dc5d05fefcfc72db1ccaf93c21.nq.gz
    ├── 2095efbca168c84a57cdc9c013d5cc524107c9c3.nq.gz
    ├── 231d16c66d938c12ebeb51b83bc20b814782f278.nq.gz
    ├── 2522ef8b759e6b07ff43b1822d56a7b102e75c78.nq.gz
    ├── 262b3a0a644a54683438c47d276a2f6882f8d848.nq.gz
    ├── 28a77136c444b1206cc69ff425e1969702522e60.nq.gz
    ├── 291e5425cc790554a972edc6b67b345835a41fc1.nq.gz
    ├── 2c8f00275a4cd15c903e9f0b116c75f30976b40e.nq.gz
    ├── 2f865e26b040c95a9b7e8782c84393ea1b06961f.nq.gz
    ├── 2ff56dcb61afa3236f64288c0fe92b9e8b5e2a9f.nq.gz
    ├── 30296851f231fa888c26658cc38589be5b6f748d.nq.gz
    ├── 3158b7819f3fed8004a5b00d182d34e999e61d6d.nq.gz
    ├── 35fb0d8d0e555aea94846ef822a9b8c8662a414d.nq.gz
    ├── 36eeffe5a3b07ba456cab52bc39385cbf4632637.nq.gz
    ├── 38fa773540bcfe1bda8e5e7ab485f0fe33b64690.nq.gz
    ├── 3bb901f82880804c715245ee2cac072ac47a2435.nq.gz
    ├── 3d1c1440a1d04d27c32698c36574d1da87aaee7a.nq.gz
    ├── 3d9994f0b70888d3ae11d5236d4532dcd1bc43aa.nq.gz
    ├── 3dd3bf6d86dcac15bb5845ff3223ac5732f9eb9c.nq.gz
    ├── 3e7bc0b2caf40977b2299e8b8b534282c583f73a.nq.gz
    ├── 3ec0720ae0a93bf8e1137d176c283bb93913385d.nq.gz
    ├── 3f6c3e5a5c09245c2bf95a12742d5934b6d87e56.nq.gz
    ├── 3f9c69ab3468f85fb97af27f5c2c27974a0d1a95.nq.gz
    ├── 40b0e75b4cea8e1b750791cd8429e9a6924303c1.nq.gz
    ├── 42a00da835557021c9c88392d751dc85f4bd2c96.nq.gz
    ├── 42fa53141eccc363263da280f73eea72ff7bafe0.nq.gz
    ├── 4303b0dfe227f9352e204f6d2d0c9649dadaa1f3.nq.gz
    ├── 4361689008d74b4f581ef8f20d0b3f336dd7f352.nq.gz
    ├── 43716a650ff6524fa424ab88055173321547f935.nq.gz
    ├── 4520ba90a0cb3aabb565104d4fd53ca9a4dd6826.nq.gz
    ├── 45458e6320e70d2c89d0e9c19092c5e206d2fae6.nq.gz
    ├── 45b62973296a4a09b6eea6ff03f480264f45fde7.nq.gz
    ├── 465d783ad57b3c491c8e04b72147efc2bc7d8caa.nq.gz
    ├── 4754cac35b2422f2f3280e449927fa3aa0ab3926.nq.gz
    ├── 477a99661c88d3eeb2f6822c35d948b1d4ac0e4f.nq.gz
    ├── 48eef4b2dd074373fe777f9333e884d62055a68c.nq.gz
    ├── 492c168c0c179fd0e42febbd1743cbb583e02f45.nq.gz
    ├── 4a4601ce0f56645c8adb0fc89280803f8727a4c3.nq.gz
    ├── 4a4d1d2f588ed7fa610c4d17893a7ef5a7a27b5d.nq.gz
    ├── 4b91509d4b5306e47b458081cdea4187860713cb.nq.gz
    ├── 4b9fa81ea97c2228c3a3c44b48026699199aba71.nq.gz
    ├── 4db01d5ed562888b2ff6e7b304a8e8f5866251fa.nq.gz
    ├── 4fbb89c6bc35ff35fce26c01caa4db60757d1bb5.nq.gz
    ├── 50e7b0fea6f372d62fb9d8e3cb252b1716fc8f1d.nq.gz
    ├── 51bb9f95eeca58ff3c2bbc82b72837f27eebac85.nq.gz
    ├── 526f9d5c6e80da1ac532db383cfeec9084822296.nq.gz
    ├── 54872c11cc0048b4d1106490c4afeda98dc4f019.nq.gz
    ├── 564c2b2219bdabf3c448d5e1926ecf17f946a78a.nq.gz
    ├── 56c035ec1fd0d8f97f977aa8b0aba2ff75f01531.nq.gz
    ├── 58695b538a93f3871d191794454140a1203655ab.nq.gz
    ├── 59278a6287c6b114cfe6a9b569f44102cb5cd2b7.nq.gz
    ├── 5934156dd5ddb2310112e9d72242e0c34e4ed63e.nq.gz
    ├── 59aa6efe3573952ab475fc2852aaf48884ea76b9.nq.gz
    ├── 5b191c08ca4cae25b80161df7a096c607e0761ed.nq.gz
    ├── 5f6016de0ba29c3d7c3eaa893b634525fb5930d2.nq.gz
    ├── 5f637ac5b73b557096de2416c9374f474fc0c3e0.nq.gz
    ├── 5fc5dd35f301d73f5002f2d51ed61dc6fc7d479f.nq.gz
    ├── 619ce7262a4d3a140d830b4e64fdaf37ed2d416c.nq.gz
    ├── 63c770776fb0e66f72d9df7d8c0687fcd6446ca1.nq.gz
    ├── 65c9e7cca094c14815416a6e2990fb616606090d.nq.gz
    ├── 665e5f7d1915cb33f699fb19350a7e06ef5c861b.nq.gz
    ├── 6787a3fb487ef6b0a66b75a1fcdd1c74ab7a2821.nq.gz
    ├── 697294a37629c2a2334abc6b6bbf3d9585bc2513.nq.gz
    ├── 69e75842f49f42de95c63fdbc8d5dab9d870a0c4.nq.gz
    ├── 69f218f888bb31ca9b63ac1148e8c11b37bb9d41.nq.gz
    ├── 69fa449dd96e2405945b2e4cff2fd0ab8b102097.nq.gz
    ├── 6a7b632691b02d247fcc776413b785d0867ea6a8.nq.gz
    ├── 6cd339d6bdbede799c44c1689ca56a55e4374145.nq.gz
    ├── 6d1428374999b9892625058e1e2e3b3da64f99b0.nq.gz
    ├── 6ee0cd7cc7e16e5457c6c316a738816620300446.nq.gz
    ├── 70a7f67d613e91546b27eef9d0755dde6a5c038f.nq.gz
    ├── 76987584b0c01344455a8236eb2ce3474ed50990.nq.gz
    ├── 781a013b26c23555635befc5202591f3bf1a088d.nq.gz
    ├── 7887771eb793f745ae6938322884ecdcbaed7774.nq.gz
    ├── 78cdff6dcfc544dfe6a0dd0ba4af982ef604b4ea.nq.gz
    ├── 7a07223e4c4a750bb64243054d0b85f0434ea7c1.nq.gz
    ├── 7a704f08d469c48197e99d7987138e324e9f60fe.nq.gz
    ├── 7bd441de4a8d0221e025b5e3242f2b13b853af52.nq.gz
    ├── 7cff6305d78f90db2c814bec82457931436912ec.nq.gz
    ├── 7d42ea4cc1ab6d727f92318584c1fbe9ec7f0fb0.nq.gz
    ├── 7d941703a219ba2a9a7b64ef27901380a2483360.nq.gz
    ├── 7deed02d035eb1398967aeeee213693aa8e6fb80.nq.gz
    ├── 7e185a60c08ef58af2abc38ee8e58f9d78faf992.nq.gz
    ├── 8081e671d54d643431ff87bd612cfbd4efb17e32.nq.gz
    ├── 80b1523ab4b2b1aaa24deb09e55aff72037cc137.nq.gz
    ├── 8238b877703b688da21874952048ce283193f391.nq.gz
    ├── 82ba673c226e4e63275758da4819a9329a71c1bd.nq.gz
    ├── 83857da9168b4cb56301f0734bbc1d6d0627bd48.nq.gz
    ├── 83d85ccbc67e0fd5bc6de3bc62631af9e328929f.nq.gz
    ├── 8622a32e5aa9749b552e53a04aaf57cfc60e3aab.nq.gz
    ├── 862f83fcb76a0b94b04f3ebb329be05101fa8659.nq.gz
    ├── 88d71165c7dbe12d6f64dba208b5216d7b05addd.nq.gz
    ├── 8939e10951167481ef35f19ec9f93b03c76bed8a.nq.gz
    ├── 8a5c552504a986ee6df799302764752990e0c673.nq.gz
    ├── 8cf46f7690a3b34d9a25f9cba7f1e4fde5f41349.nq.gz
    ├── 8f0371b59f61a97b20094c6056300ab589ea6d38.nq.gz
    ├── 90064a288a4ebee4e089c9ebf98c788df4c39ab8.nq.gz
    ├── 90e6fa1615cdbf80ebc6c5fa2d7ca77092f29e1b.nq.gz
    ├── 922152e96a04a242e6fc40f124261d74890617d8.nq.gz
    ├── 928b9903c562abdfed793691d95edb9e0ab9c997.nq.gz
    ├── 934bd6f6835b0dd83c076afc2dee5888a27581e9.nq.gz
    ├── 93ba9549d70da9b9b17c4e9dc929bc9f41d835b5.nq.gz
    ├── 954237b9b9f2b248bb1397a15c055c0af1cad03e.nq.gz
    ├── 97e3a8c726c5aaba571b52162156b9b706f23a1b.nq.gz
    ├── 9847ae8f38e7a119b4859cfbc7a0506c0fd0266d.nq.gz
    ├── 990d5e9ae823a189b71a038f3768c403a7961a17.nq.gz
    ├── 991504a37a3ec62140f9fa0883cdfa6b551c7a94.nq.gz
    ├── 9a7725aad23137459664630b2dfcb3ca21401289.nq.gz
    ├── 9aed90ef680033b629fbcf8a9082423951184789.nq.gz
    ├── 9bdfa856d27de8f2b9bb64e28344984c48694da1.nq.gz
    ├── 9cf01c4c59b56eab369469575e31d2e6631da736.nq.gz
    ├── 9de238023c7b5fb275fda888d6eac96c2e4229b4.nq.gz
    ├── a1ba18d982edc63c9bd2a14348f980f8d59eba00.nq.gz
    ├── a37371ac84c186db594d3a6de0fdb71925b3c6e3.nq.gz
    ├── a385e88edd1d2d3b6b90755d21fee3159071ca24.nq.gz
    ├── a46c3024a1a95db3103990227bb806647e10c746.nq.gz
    ├── a5f1062054de218f1af0b4e6a3a9ff0d0309ca33.nq.gz
    ├── a60ceb444ac8a1938b285a826f35c6105b164aec.nq.gz
    ├── a6a8edb95503d098d6d6663716f27510490af503.nq.gz
    ├── a7e746230974ba82394cc7385a6cbcd8f7cda7f2.nq.gz
    ├── aaec838d79016e40fca1c5f08df9dbc261b35a25.nq.gz
    ├── ab2c5aba69d262d16a47091dd99b99f9ea708249.nq.gz
    ├── ac105fa941ee46a9fe24db85b6684e331cfd9bae.nq.gz
    ├── ad160deffa71909b93ef5a50382601e588bb8385.nq.gz
    ├── b06f38fe69c288ba2a1c83dbef7145bbe16fca45.nq.gz
    ├── b07b12b53c1747c47c75a2fd514c444e8ebb35c8.nq.gz
    ├── b2037253d90217e934cce9f59ab12fddef7f51bc.nq.gz
    ├── b23733af5351f0568fd06a39dcae3fc1aba54440.nq.gz
    ├── b2660209634d5f24d990232c94f1bdfee25992d1.nq.gz
    ├── b27172a813db2d8ab2bb5390f585f562fcb58311.nq.gz
    ├── b38df9e0e7c50d0b6abf0eba5c0ff302b1a3f4a8.nq.gz
    ├── b434107551c492251291d57c35df7e1b3da57c8d.nq.gz
    ├── b449c4366f5cefe9a4c3bc197e2fa99252ebcef2.nq.gz
    ├── b4854a0d7658f7fa361b804056aa23a16e870b0e.nq.gz
    ├── b497a5776854f5d8642a42152589a03ea0a8a34d.nq.gz
    ├── b657d667bdaf5342694ff103b28f8e919c10b102.nq.gz
    ├── b8ddebbc1acb016df1ed823a5337bb5bb580c1e1.nq.gz
    ├── b8ed4f1228ac6812fe410f97542d1de64faa126f.nq.gz
    ├── baad19f41b63104eec0ea7cec5702156129dcccb.nq.gz
    ├── bbf4106659d036a550a01cf56e01718f6019775a.nq.gz
    ├── bc9293f4e5aa2e1a25e7ce00d9036bdc487b79b5.nq.gz
    ├── bd67867d66abefd0998977836c0739dceaf8eaca.nq.gz
    ├── be97017f0b8299d5cbcc7400226c9650f8a48703.nq.gz
    ├── bfdbe9ac05d69ac822cc31a082bef4a3b183e2e3.nq.gz
    ├── c04041e4b9e28ce2231e81fe629b031b74576fbd.nq.gz
    ├── c133cf55748a57399163c8bdbbcd959f08b65422.nq.gz
    ├── c1f7e45c50e19eb553db388af41eb70692900709.nq.gz
    ├── c250644d5d76558779d28d1841368abda4561857.nq.gz
    ├── c46d8d7c408e69024cbaf9fb05dda0e4ab01ee92.nq.gz
    ├── c70fa82b2cb3ed245ca5e13a8a8f9d4aa39e8804.nq.gz
    ├── c7126e6d9c25721573feb4895db4b1c5d362c014.nq.gz
    ├── c8d34ed8d27812637f3fe1a6362d1c1bf1f7234d.nq.gz
    ├── cb4ab4bdc798b9cd6ed96d86fb6a3deec2973e8d.nq.gz
    ├── cc46f7cc0db6e486d089576d3eca21592082347b.nq.gz
    ├── d3504e206edef7a625d62ecadefff2e014a6a498.nq.gz
    ├── d44c044dddb31040a2093daee4ba064a1f4f66fb.nq.gz
    ├── d45230cfb0b86bee5ef392584f6bce8170078d62.nq.gz
    ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
    ├── d531b2435689dd5ead7cfb829ff7e057115be1f9.nq.gz
    ├── d66a318e6ea712c246cd180c5597a4842e23d797.nq.gz
    ├── d7834e370463e62883ad6f18342e6e54e5eb6521.nq.gz
    ├── d8d898fbed2532edd28225d77670d57d7d69325a.nq.gz
    ├── d96f80342a4d7d7c7ad2bb4cd46e5fe19c03992e.nq.gz
    ├── d9c926baf6551a9f42c2817af649abc70a1749b1.nq.gz
    ├── da95b728e0e9bca6589c8a1b085fc9f719f40c0d.nq.gz
    ├── dadb4bf47b82d9f27d89bff45d67a297146e5c77.nq.gz
    ├── db3939296e78bdbf89bff6c4dfe476eb6c933ae4.nq.gz
    ├── dbc4cb683a492f05493bda248f84088dd401a89e.nq.gz
    ├── dc51d72d0218af71f1b278ece52faef82478559e.nq.gz
    └── ddcbf2818fe0148294dde7ba328f147c02c6dd41.nq.gz

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

[sphinx-contrib/matlabdomain](https://github.com/sphinx-contrib/matlabdomain)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
