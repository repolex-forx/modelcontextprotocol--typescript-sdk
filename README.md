# Repolex Knowledge Graph of modelcontextprotocol/typescript-sdk

RDF knowledge graph data for [modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/typescript-sdk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1e608caeb5130b2ad0fa067c84b26a038c1c6e36
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1e608caeb5130b2ad0fa067c84b26a038c1c6e36
│           └── chunk-001.nq.gz
└── blob
    ├── 00e595a5e75f3ba5ce8ba0be07c5608732ada3db.nq.gz
    ├── 00ec29340005749af1717c8eced3ff9446c8e034.nq.gz
    ├── 014caf8aa35fc651283c58c4b886a7fc72f4fa5a.nq.gz
    ├── 01ce37ee278f9735a7dd6d72043f2779d69397f4.nq.gz
    ├── 02354e6e806939597b2fee5ba1b5673edddb2ea6.nq.gz
    ├── 02f65efd6050a78e333952dcd289e8de8f5a9a1c.nq.gz
    ├── 02fbf06c7bd537565e2dd96d99d57d8b75285ac0.nq.gz
    ├── 03108494298bfbaac759ec13a9b6d92425c5ee40.nq.gz
    ├── 03d6319d985cc0b0bc529e4040d0f988a8681da7.nq.gz
    ├── 03f0933d94e47c30e52abbf1dae3f6d383dc7a79.nq.gz
    ├── 04c231e4c13cbb287e0181fdbbbb64d20f432eb4.nq.gz
    ├── 04e17a74da94cdef8544ea31d1cba483787f95ca.nq.gz
    ├── 0514c0c4771443ccff6b7a20bd2b3ed1c843d5e7.nq.gz
    ├── 0544030d451b09c19dd025873695c717384f4a2d.nq.gz
    ├── 0617562fd034eb5fcb651f0c458371f6692331cf.nq.gz
    ├── 0673fee9c227044f94b817f2805fd8dca316c2d7.nq.gz
    ├── 06a5045ecdae2838461a413abca9fe8e5210da92.nq.gz
    ├── 0752fac0991574492b2ee60e5e8183b442e47bf8.nq.gz
    ├── 07cf1643692ddbd598fd1e4181a5a5b33b51fd65.nq.gz
    ├── 0836b4394a6d73de945f84d90b921fa2ec821ed9.nq.gz
    ├── 083aa5612325fce280e024d5f42472eec12dd413.nq.gz
    ├── 08fc368032b6974fca7c2cb175ac626db1923d75.nq.gz
    ├── 091674e101f8b1e2d383555f603f0d0255ca37c9.nq.gz
    ├── 09971d67e007c69f53bf8c3c0052f22cb9bdfeb3.nq.gz
    ├── 0aa3fd168f6792c5cee52f62ea5fb5082b0ef255.nq.gz
    ├── 0ae10e6d08e2d3bda79bea862be21dcbeca9acf1.nq.gz
    ├── 0af8b409e7cf48fdf79e463683944e07f04c9527.nq.gz
    ├── 0b1ea3dec65d02fb2c4a209111b590e0e9fcf646.nq.gz
    ├── 0b5b6e86eaf9acaeff7c540140de82890b76633f.nq.gz
    ├── 0c4285056f9b1a5c15e63b976f6d5921089b402e.nq.gz
    ├── 0c42974d9d05bd88ceecb015a67fb33b8508f91a.nq.gz
    ├── 0c593e9b448207e7bdca5dbb5b22212d6e676d8f.nq.gz
    ├── 0c9412ca18ff8698095be2de4e022b61804c0c5c.nq.gz
    ├── 0d5faabbe1deed4c5d196871f7ce79738e344ef7.nq.gz
    ├── 0d9c6e9cbe5a95f91b16c94cefd1b31c6d704e57.nq.gz
    ├── 0d9fc16c4d96438dcad4229ccee47c132bb0f61e.nq.gz
    ├── 0e0ca435493b84f30408b5a5625c0f1e3806b5a6.nq.gz
    ├── 0ec766cd142f70742df6a6042ad871509832bb66.nq.gz
    ├── 1168c8be9b41bf07f648358abc0f0cc039f27426.nq.gz
    ├── 12cb203f2344825e9a8b4e9c92bd3ac533accea8.nq.gz
    ├── 13699fdd3427fcaa660a8fd7ac7c9c907e80e992.nq.gz
    ├── 13c2bb5efcaf453e47cd0701b4683b7e63360cc2.nq.gz
    ├── 1559a434d5e897389ddf17207277d237dc0d7eae.nq.gz
    ├── 157b3a3d295faedfc6a08bb08ce210d5e611bed6.nq.gz
    ├── 158bfed00e7312efd6cc8a8b6c15f32bba3f4b55.nq.gz
    ├── 16cb51e1dcb645572b6eb7ab454f3cf57699f826.nq.gz
    ├── 16eed5361b8a686afe26906f9cf0e6f7d10dcdb6.nq.gz
    ├── 1782ac8502eb86477b86c65faee82470e38e968b.nq.gz
    ├── 179a1643eb0ac8def5c15f39b3c4e4be8f58571a.nq.gz
    ├── 17c0b4b612b787e605c344707c52b0850c9b3d41.nq.gz
    ├── 18bfd7b3bc0ecfc3e0a326cd1f35ad59c380d629.nq.gz
    ├── 18e7d9745c561f3faea1636a2f1c1411967b52f8.nq.gz
    ├── 19bb362d1765cf804d3264a0552c1edb7970ad9c.nq.gz
    ├── 1a6984926c020feb2b4483c3df1da50378fbc119.nq.gz
    ├── 1a8c9666de11074ad1a1f85c3350d41a22a0582a.nq.gz
    ├── 1aad441dc31e55b1e2b53fb7ade0346ee96ab6ae.nq.gz
    ├── 1ac1e65321d05e7aa5c5499e744fa7fc9b9d930b.nq.gz
    ├── 1c3271219d7c37faa2cffac55482afdb042d118a.nq.gz
    ├── 1c455d11e2788bfbe6c42418076fa827dd62a596.nq.gz
    ├── 1c4e60514e4ee9f5ae0b33f7e7883429982a1828.nq.gz
    ├── 1cabf8ed9b356a5b6aeaa13c90f5e1988a1b10cb.nq.gz
    ├── 1d5c7b4c6ca31db92eda9f052e80ba4466d0df6f.nq.gz
    ├── 1d74b5b7ded35136c3eab31fa517f18540bdd9a1.nq.gz
    ├── 1eb2d8fdb048399cebf78475ea065d326f201e4f.nq.gz
    ├── 1eb78739741807c5fb9eebf5a19d0d7c909e2075.nq.gz
    ├── 1f4ef6f4a693ffb2a73bb31b64ab65d533cc18d9.nq.gz
    ├── 1fcbd3f6e502b093ec95c58cf77d8ef68d975a27.nq.gz
    ├── 2012fa59eacd77cfd80f57c0dbc3130fa9357b74.nq.gz
    ├── 2066a8aff367be8031342c71a08b8a170013761f.nq.gz
    ├── 20bc1de86567e3152c10d49664ba6ae1d03d2848.nq.gz
    ├── 212ad7f958366647c3771273fef7b90ff414c532.nq.gz
    ├── 215d15bf39e342c80fb9e80a7388b5e7dff652ac.nq.gz
    ├── 218528f42f60ee3843128d094e365efdeb1443cc.nq.gz
    ├── 219c6ad57f6714723f6f93970a54e0aacd63f747.nq.gz
    ├── 225a53c2d72d5c7e321492c7a84f7e6d1db91ed4.nq.gz
    ├── 2284c163a16cf7b7f2fd1375e1196ccc34ede08d.nq.gz
    ├── 22e91d010fc1031783f897057b2c29fd245af7e7.nq.gz
    ├── 236ed22d1b0889c43beb2997f20ba49c2cc05672.nq.gz
    ├── 242d55937e9dc2eeb65de0a7fda5b25db4c013f2.nq.gz
    ├── 246d5a049cb61b684c5d37fb2fb7ba150ece2ef0.nq.gz
    ├── 2484ae19b0e63b9089a3ef78009051bf4f599fc8.nq.gz
    ├── 24bde32bdeec0d033f47800a95f90dcd65a3524e.nq.gz
    ├── 2543a4b745167a10383f83d399235b8bbc226b0e.nq.gz
    ├── 256955b6931fe12e8751993c2d43d1f96b389586.nq.gz
    ├── 257d6974c21b1a6453f84af56d53861cf905fc2a.nq.gz
    ├── 25df11871c2c657c49fbd4c6a2a2801d11079dde.nq.gz
    ├── 26631c76f7d2797241f86b86b783322cef9d6d05.nq.gz
    ├── 26cfebf656887715a2a4ec59fbd3e685ffb9774f.nq.gz
    ├── 271ad203748d9abdbb871f8ced4d4063f0e166ea.nq.gz
    ├── 27492389d8ae3245ebd146540b026722a7242052.nq.gz
    ├── 285c569e16a9d8fae6ff4df0dce96ba7d88f20a4.nq.gz
    ├── 28940bed2d0cb7e85c56f53ef951d54860e5db80.nq.gz
    ├── 28aff03b50f98fce197e86ca784679a1f1228f5e.nq.gz
    ├── 295515a89a80b2ce233931656bfa192f7c2c865e.nq.gz
    ├── 29f2ead844f993e36fc352604acf174ac92dff59.nq.gz
    ├── 2a5aca1267b9ea1cadc735dfd8bc463ae711eb77.nq.gz
    ├── 2aa3d31601832142b743283d3ed3c94dcd333ae9.nq.gz
    ├── 2abdb6f71870f238a119dd34f356472d27d07c3a.nq.gz
    ├── 2b75c8fe449923fac278b3adea03b6fbfa56bfde.nq.gz
    ├── 2baa75d9483b39256e01b5109fb5647e34ec362c.nq.gz
    ├── 2d4ec5d138a8f5be96e8ec5adef9892aa9c4d6c8.nq.gz
    ├── 2d6c251fde2a9658c9e72d447db27d5414d8bd4e.nq.gz
    ├── 2d7d8d7560d3b2707e607f6344cfac800d45ce40.nq.gz
    ├── 2daca7df322eb93c0ebb20ef24e5c7c42d1ef3af.nq.gz
    ├── 2df6a8e1074c76abb5e623f34ad7118189c0b51c.nq.gz
    ├── 2e5172027421107201317dc4618ff1dd9cdadd84.nq.gz
    ├── 2e6e11ff3b0338511901c0b0619d4432e7c62ebb.nq.gz
    ├── 2e709a749a50890ca9e292344d05bcc40440a976.nq.gz
    ├── 2e994770f42fceacf803820a613080b4746ab5bc.nq.gz
    ├── 2eaa9b7bd1b783ab24c5f659f23357cefc4faa61.nq.gz
    ├── 2f60fb7c64ed3807866ef8fbc5037c635bccd20e.nq.gz
    ├── 2f6a55a9f9101277b6ed4fd1d9bc4c7f76ca8656.nq.gz
    ├── 3000b6137dd055d33402f8ac9860060a12136290.nq.gz
    ├── 317c96abcadec9559b2e9b874c35db90557a2e98.nq.gz
    ├── 31dbd901e14d87e327d0f9e4cba82e07dfb5cce4.nq.gz
    ├── 3242c0ab7df59f57f165f991caa73b104f63275b.nq.gz
    ├── 32605dd7e717deebe57303725385587325d37c3e.nq.gz
    ├── 326a9450042082ab4c01f1ac7d2ecab5d53c3c0a.nq.gz
    ├── 3277edef27862968ad35ab163822f2d8f0f7fb8d.nq.gz
    ├── 32f6a6c7a4492fca2de60eb0f39777f57c9ff06c.nq.gz
    ├── 3319051f76a58e0d8a741cb10fb6cae638b66d63.nq.gz
    ├── 334036cdb347a6d481a247936be2d3ee528c9936.nq.gz
    ├── 33b06c1d81f71105b3ff47e38c904eb38c8a1897.nq.gz
    ├── 3538fd02bd5c8f00c95b3a52888c90af29a6fb07.nq.gz
    ├── 35a18a8fbd87df059804dda2008ef4f0d53ae825.nq.gz
    ├── 35dc55a164ec7bc8e40074e1e869e0984c25f8ed.nq.gz
    ├── 364955615a0d01024f3b614879116a53f50a4082.nq.gz
    ├── 368ced27f5d6f69d7fe6414782069e22b1a2d17f.nq.gz
    ├── 36fb5964c6b0f612fa094065b9fd37c63d67b2f8.nq.gz
    ├── 376c3e784a01f633d27300bcb3da03b6694b733b.nq.gz
    ├── 38e97f4d52a70e25bdc8f396ec85f86d1345ca19.nq.gz
    ├── 38f030fdd6cdb2dbeec0012009189967310b325e.nq.gz
    ├── 39b177e8f3fb60edc78c7eeda97c3afb2ecc011f.nq.gz
    ├── 3bc5eeb2ee302489a463dab42aa96e03dcc7be72.nq.gz
    ├── 3c05e221b9e3f2e6ff7e5e7d5b3f701658fd1ebd.nq.gz
    ├── 3c670fdb8d6a321ff2608702f8324102f4d54415.nq.gz
    ├── 3d95fd23c51a3ad9cefb4145b0e9852408fa609d.nq.gz
    ├── 3dbbf79b03d0c27280b31987cf13f27ed4b7a672.nq.gz
    ├── 3e2f0ced3dc9024afc8daba3b409dbcf1a2cb176.nq.gz
    ├── 3eb218de8d991eed0bbe6523e8616c902272252c.nq.gz
    ├── 3efbe5a54b3d9366cdad86bf9effeb54721bbb48.nq.gz
    ├── 3fac46af2f5d4fca8b0ad5be009485aafe4d569c.nq.gz
    ├── 3fb96d308129b74c9de4ae882939b83bfdd4ee87.nq.gz
    ├── 3fd1693fe6bb0e89c9c1c7a96c050c90c5c1d013.nq.gz
    ├── 3ff02f090913c007e0c92a2cae603f918f0d6122.nq.gz
    ├── 402e72933bcad633df43c914a772b635a5fc55fc.nq.gz
    ├── 40f4fa30eeaf5dd6b27f3b36d72cd000202d45cc.nq.gz
    ├── 413c8d23d421891343e3660e0d00018cbc49fa1e.nq.gz
    ├── 41895c6a97bb327477ff30494480ca534fde6a39.nq.gz
    ├── 4267ad98d551bd8605d98edc48dd70e3c587a052.nq.gz
    ├── 42784290556206e8ca5544c7af96dd7d1ff4153d.nq.gz
    ├── 427b245a89f74c006d83118413a90bdbbdb79091.nq.gz
    ├── 44976b8256ccac238b3149b2f3f958f14a1d4fca.nq.gz
    ├── 44dd429d8107153f78277bb1702a525449e805c5.nq.gz
    ├── 44edaa331f6a05e8d340a3839871a44df0f6d458.nq.gz
    ├── 454d9c0f4a0861301d294193b2565508fbecff1c.nq.gz
    ├── 4561d8fb11d542a2960e470b9bdc41684df54955.nq.gz
    ├── 4611a367c9a534614da4d42bf038a2f33afe1c99.nq.gz
    ├── 4630c27669712bf1eb433659ff1853d96838959f.nq.gz
    ├── 463fea5099ca2f20aede4810fd533d7f7dba53ca.nq.gz
    ├── 4698196c9ab69805c1f3d3f40a657e40a3cbfc4b.nq.gz
    ├── 46ac5b347a2a47ef7835df6f9a38119a577c0aec.nq.gz
    ├── 46f26b98d704bd96b65b00d7cf039c2918581a65.nq.gz
    ├── 483eb0c3ce773fe0bddb518e011be1d0784b0334.nq.gz
    ├── 4895359ab37f3b30754502a953a819bb575cb052.nq.gz
    ├── 48aef0eb1183e964eaf6578c7b99f170782ca6df.nq.gz
    ├── 48ed63173330762e0b918c7e297b8b0707426457.nq.gz
    ├── 493cc3b57426c4e9cab8b449e5ebbdbd285c8c90.nq.gz
    ├── 496fca320055c8fd0cddabd825bfaf2c923947f2.nq.gz
    ├── 49e0dadb943e1f89f225a99dcdc9428d9707362b.nq.gz
    ├── 4a93985763241755401a10678395303de4e720ba.nq.gz
    ├── 4abcde078dc9117e1cfa5541bd1ec030cfc44634.nq.gz
    ├── 4abf9fb74d4644e6612d75c0413ccd675c864550.nq.gz
    ├── 4bfb84cd55d2524b0a3445ca41780c7d3d670c3f.nq.gz
    ├── 4c699e8868748252a64638e4dd0b88bd609708e9.nq.gz
    ├── 4ee9673b53f8c6644597df68bf4ba1b6f43e1ac4.nq.gz
    ├── 4ef836c63666d9e80fc23e06891c2b4eebe45024.nq.gz
    ├── 4f925f9da735c9d9fd77864e095723fba8b27147.nq.gz
    ├── 4ff54781e867e1d4c0aa139b9c508f5eb2761cb9.nq.gz
    ├── 50127764641594fed9924b601d7c9b2c39523e6c.nq.gz
    ├── 507c3e7cad4a49e159d996a2d5b977b700502e7d.nq.gz
    ├── 50e9460dce06318e18bdb5cfedd7a967a4364eed.nq.gz
    ├── 5288d0b8d979a19378210c6c8592c7c1c8e86ddd.nq.gz
    ├── 52a17e27790763302293acdf5e105c0406977632.nq.gz
    ├── 544175dae925556a23e1eda792278daadaf2a1c2.nq.gz
    ├── 55123e68f66248db42c247a2058fb9de26b293ab.nq.gz
    ├── 55c346ac85ea3af6406ec87a404b333135cfa9d0.nq.gz
    ├── 56fd572e6aee410b7f0e79eae772f75a60f497f9.nq.gz
    ├── 5751fc802095bc213e62f4926de73054f469963d.nq.gz
    ├── 579e61d854feed02b4c6dbea2e8bdd61d7ef921f.nq.gz
    ├── 580cd8bc86fc708fdbf68334fb923f4898817dcf.nq.gz
    ├── 586d69dc34dd46d5203704eeddeae51c61de1833.nq.gz
    ├── 588a096d5f0cb9705aeecb60489914a9d7fe0a92.nq.gz
    ├── 58a542340be0fe86671f751a58c07596b1bc1a39.nq.gz
    ├── 5bc882e8e3efdb592acf7a98eb3c88d0c7116896.nq.gz
    ├── 5bdc229298f4532dbb58f97c3b9eb6c886abefd8.nq.gz
    ├── 5c770eb308e97020e490509583d867c9f5bd0b48.nq.gz
    └── 5c8a0393fa6c568a7d2c316790649b834aecb1f6.nq.gz

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

[modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
