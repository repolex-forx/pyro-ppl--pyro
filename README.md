# Repolex Knowledge Graph of pyro-ppl/pyro

RDF knowledge graph data for [pyro-ppl/pyro](https://github.com/pyro-ppl/pyro), parsed by [repolex](https://repolex.ai).

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
rlex download pyro-ppl/pyro
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a31bc1784707268cd79df77ead4c7a47062f0193
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a31bc1784707268cd79df77ead4c7a47062f0193
│           └── chunk-001.nq.gz
└── blob
    ├── 0001884ebdff7af124b7d938e863ee6a0a589522.nq.gz
    ├── 016c785df110c2567d0f9f7a02405845ba3c702b.nq.gz
    ├── 01751827c0108e12c26da4b67cb297c3d7169d2f.nq.gz
    ├── 01ea3168556260c2bfca542ef1a3af8e67596000.nq.gz
    ├── 031bc03b06a3467dce24fb4bc868f235fded6dd7.nq.gz
    ├── 040273b78a63b6866750a903177ad4aff0ab88f9.nq.gz
    ├── 04772dc92699c9a1d8de75ce8adc704bb66c491e.nq.gz
    ├── 0478c2ea574d6fa53a00f437d1c5b1df4742bf90.nq.gz
    ├── 0561ba35e6f73c0e7bd42d223e274e11e14bc7a0.nq.gz
    ├── 058b1e17bcab65bb1bd34ccaf08a8776db789b19.nq.gz
    ├── 05d488ee4ac507b1a6ff444f6838144a5202ee1c.nq.gz
    ├── 0685fb621d43f2c1fb11d03d1ce24f7ddb6f1bff.nq.gz
    ├── 06dfcc5a378fc3315eee0736fca0b1f0ec39018b.nq.gz
    ├── 0736c0895b96a3f1df01ce5e400ea847f9c6e4d0.nq.gz
    ├── 0784f054ce1134d624fe38c86bd102cc99f75d20.nq.gz
    ├── 07de5a7f53df2a5b72f57fa7c4e4ca61264845ac.nq.gz
    ├── 081ea80e94dfb2b83ce52073098fedcaa513d1cc.nq.gz
    ├── 0865f26c1f04a7e8ff859f705e17ea3ec6343740.nq.gz
    ├── 08b60967f81da0ee06f2ad8d675533a7c0645f5c.nq.gz
    ├── 090bdae73ccd0dc25d773b54679fd234a8f0fb4d.nq.gz
    ├── 096de53108094c8d51bb0db229a4c176064b4140.nq.gz
    ├── 097132c85bd63457619785802a16a302fd4cd60d.nq.gz
    ├── 09d0c36d9a69ee015e37bac0ada0649e1270f0f5.nq.gz
    ├── 09dbe6872d1120e6b2310602163545a8bf72d12e.nq.gz
    ├── 0b0da1ecb9bf1a024efb04429ce82d7ac517dcb8.nq.gz
    ├── 0b1071b745b997df8b372b8f823a907395dc8a5a.nq.gz
    ├── 0b3749ec325dd371ee82fb3db2a112edf38a6395.nq.gz
    ├── 0c28b55a19a6200a40ae593b9d21edd8e118b11c.nq.gz
    ├── 0ce8fd8cdfb0c8159307bb173657dd246c723b2f.nq.gz
    ├── 0d796a8ae819ee4b80abcaeabf35af046d636c65.nq.gz
    ├── 0d8f2c07c4830e01468cf9d8f8401b1cef5eaf06.nq.gz
    ├── 0df914241d2070eb3fb9e5b5e31879bb31629fc7.nq.gz
    ├── 0e9b160860cc3bb3ca176e54fedd8a78117cb456.nq.gz
    ├── 0fc194423e250e6bee8e76a10290b31f5eb8b507.nq.gz
    ├── 10071c21a955d25fc916f2f0280022901e58910c.nq.gz
    ├── 10200fac2161f5950caba7d0ce13287f8456dae6.nq.gz
    ├── 10fdda1d5a958024b77c7018619f3692c2eb6f0f.nq.gz
    ├── 116279c3c6a0f7003392ca081e1011b2b120521b.nq.gz
    ├── 1166ec4c9c72a7b0188e4787a345814a20a7d1d4.nq.gz
    ├── 119a7251dcbab9638dbbfd104b73f3bba753747e.nq.gz
    ├── 12dfae7ccd18b414ebc2c79780c35baa10f395d9.nq.gz
    ├── 12ff6d6104c97de818f47eaa8629ac0a1f6cefdf.nq.gz
    ├── 1308491a17775757a30d1b8e531fbe0de5e3ae97.nq.gz
    ├── 1330676d81d33e10280af1667dbfd4189f22361f.nq.gz
    ├── 133158f4496802b0908dd1478682c49a4fa15a66.nq.gz
    ├── 137069b823873b8bcf42979bcf8e9371052d26a2.nq.gz
    ├── 14a09dd984552b709dd2b103189a8a7575094712.nq.gz
    ├── 14ac2681296713b82b09e5164809369136492497.nq.gz
    ├── 14be58bfb70d55a67a9de777159550ea8f3857a1.nq.gz
    ├── 14eb605c0b1200b395750449939ccfe885c74970.nq.gz
    ├── 162553a321227ad761c31b041129f611dc7032f9.nq.gz
    ├── 16947867f541ad326078a4c9c06d1b2213521f76.nq.gz
    ├── 16c32c6657d71c0b43fc82eb2e2eb607b19bd255.nq.gz
    ├── 173c0004f913fa26941461bd1f74920f97f5e6e6.nq.gz
    ├── 1824a1a28d748a76f0835b18de7558897f17c667.nq.gz
    ├── 1886b265a11686e87161d30e5e0ff29850dd0bcf.nq.gz
    ├── 193b5631c57d9b8337d668dbc6cc0242ab6e8bc1.nq.gz
    ├── 1a92e09a2a7f6473132e36b230e026f7731dc6e2.nq.gz
    ├── 1aa1bb17a32763689f1ef02f423846bdfd68f5d9.nq.gz
    ├── 1b15e0e01658345cf769305255c6fced22717367.nq.gz
    ├── 1bb680e65cddf8d94b8ae8411a4d11bd6425ea8d.nq.gz
    ├── 1c4ca6009f04ee89ac95f819d843f9ad21bed07f.nq.gz
    ├── 1d1c3d821ad01a247f8684d3d81fd826f1cf73d3.nq.gz
    ├── 1d2053b2b23ffe27c78497df0b31ba42f0de7226.nq.gz
    ├── 1d60e7b15f5eea4372ceb96f93321e66470c2676.nq.gz
    ├── 1df098dcada559af56685b31b6e5e083cdfd8ff4.nq.gz
    ├── 1e08413e48a2b4bf389add1cdbe5fadce7e8b54d.nq.gz
    ├── 1eaa8663c0e45c4f4fe727ff0d569c5f66ce6a48.nq.gz
    ├── 1f33b59666cb5365d47e602a6e01645b0f8148fa.nq.gz
    ├── 1f97d37c40112000587bdee2e40fbe9a0019cb37.nq.gz
    ├── 2071b23b0e08594ea6bc99ac71129ef992abf498.nq.gz
    ├── 20abc68dd04ba9fc07a3a05f8d038532e8522937.nq.gz
    ├── 210d9baf00c6b633b86f37c8f0ba1340cbf1df25.nq.gz
    ├── 21a57f5eced84cfccf654922db373941894a99a2.nq.gz
    ├── 22510f5f5234b05257457e31b734411823a0529f.nq.gz
    ├── 22c1c93ef810a58fe7f045773cba54e15e16cb91.nq.gz
    ├── 238deb176e5d0c4154eac4f82cc85c128d2694d6.nq.gz
    ├── 23d5b0e904a58495c30d7d31bb95852e2cf31b32.nq.gz
    ├── 24531e3e7ae51c95e88184b8c6e43f0a6aee0862.nq.gz
    ├── 24c45457d8ca6ad703766e457c1c6997cda3de89.nq.gz
    ├── 25526c2bad6f8744b5bba0e170cc586f08486706.nq.gz
    ├── 25dddd4dfca238f26ad86a4ecb3ef924c871b461.nq.gz
    ├── 25ee86d009ded037c0cc2696f15a9f213c600f7e.nq.gz
    ├── 261dd3f6827b12c557b9c5a1af02147e31cc0a5f.nq.gz
    ├── 26791f7ff9775322c7341cb499586773422760a4.nq.gz
    ├── 269519eff4f59d37d6c09ddb35304494bf0cd2e7.nq.gz
    ├── 26c75c2316d733d3ef3e2366cf67b5c4fc02b927.nq.gz
    ├── 2887bdc9dccbf7c5b34f455ab9193d9bfad0e689.nq.gz
    ├── 28ad9eebaa38512367e33ebf1d2da4b9a1555f20.nq.gz
    ├── 29789eca28fc3166563752adcd944886b832cba3.nq.gz
    ├── 2b5f594132ff6abd38dde1c830dcfcf4a694ff2e.nq.gz
    ├── 2b9c1a47e22f14735bcb73fd71cbc9914282a0fe.nq.gz
    ├── 2bafd8c22fa9514bc074a5cb8928f9fed474b926.nq.gz
    ├── 2bd2c0ddf9f53eeb6f1866e7ab3db651f16740c5.nq.gz
    ├── 2ca061752cc801eb3bb7796d880ff169892d63f3.nq.gz
    ├── 2da51e6a3e6902cabfb26857da12ddf012c762be.nq.gz
    ├── 2e9b2dee313b68bfe2609c076a93e3552dc5dc02.nq.gz
    ├── 2eeba0ccade3d4dc4c17ed2dd3abae05455b5665.nq.gz
    ├── 2f5f4429ff84691094a97769e008c13cfec26a87.nq.gz
    ├── 2fe90ad8b53c6e241665b1da26373d9074a5b29f.nq.gz
    ├── 30bc1a0ae522f8d36d22ab5f8669461b64f6ffb3.nq.gz
    ├── 30d65650d283d522daefc07637755d7419ebbe12.nq.gz
    ├── 30f3c0dd8f7172b453ed7499a5bc044648e4faf2.nq.gz
    ├── 311837bc8774d22537a00a836a2e571b6da9707f.nq.gz
    ├── 314a375a453117f66ac13e5c530ba111bdb59f29.nq.gz
    ├── 31e524a6513c449c888de1218866f581ad647b6a.nq.gz
    ├── 323a6225dc9a02e654a8a9148ab228588e8f2660.nq.gz
    ├── 338efa9e2ad5b1794821c7d0a9709135de06b40f.nq.gz
    ├── 33b8ec608006436df78d69921f5581543cc7dbee.nq.gz
    ├── 347a09819a8d813052a7bca70e056fc21b68ec66.nq.gz
    ├── 34febd054346c2ea44f977da460c4ae40156d916.nq.gz
    ├── 35cb5d9c790072253980eee428a12fe0ab182d95.nq.gz
    ├── 362ae2cf86adffd62515f01d2fc6633155055020.nq.gz
    ├── 365d05dd9ada46cbdde4c9655f0a68bcb8474354.nq.gz
    ├── 36748c6e6787c59f04a0db099e8a0dc1529d3fd1.nq.gz
    ├── 36cdb11aa3a60642408a7b85b5690cbec87b192c.nq.gz
    ├── 371da18fad77d2d0e014e73f8c9a9d4f167c542c.nq.gz
    ├── 380d9d641b223ccb176310438dac156cb16b7276.nq.gz
    ├── 3955746812d124a0c9579345b3be7f0a428ce550.nq.gz
    ├── 397ecc860f4f40ccc652077400f9ac8330fa2256.nq.gz
    ├── 398b39ed716b33c9344ae3812e4c341ff15fe0a3.nq.gz
    ├── 39bbf5a35214a78cabf86d6d9e1e2d58d3bc6a95.nq.gz
    ├── 3a07e86899a1eee6e130578f2889f2a733b28e06.nq.gz
    ├── 3adb9c2fb9c8f64e27cc38243ea2ec897c7ebfef.nq.gz
    ├── 3be1d6a292754f089fc03dfaa9a27e1f1155cc84.nq.gz
    ├── 3c1d2eda0f95550fa9d81c35b6b704b28ef48a40.nq.gz
    ├── 3c6cfa8cdc1a2dbb37c6dd3c8edce2b72393f12e.nq.gz
    ├── 3cc623bf66045e6c327f8df91e042d37eb00689f.nq.gz
    ├── 3d171bfc3c1aef7cae97606a2593c27026377a94.nq.gz
    ├── 3daeaa5b5b6f05d4c5c279a1fc930801b78d8cec.nq.gz
    ├── 3dca05ce3a724fb68011532ba04195bb0bbf749d.nq.gz
    ├── 3e801b53528775e2eb2ce49aee12890bbc2af2b2.nq.gz
    ├── 3e9649c804d1f786ad2386b30718ce0873ac7f2b.nq.gz
    ├── 3eb774acd5d84ccda70f1bc26d368ab64211f34a.nq.gz
    ├── 3fc2b4be9f9b9eb6241ba871b2bd153eff30b968.nq.gz
    ├── 4044ce650751548898ca4b10223f52b4206245dc.nq.gz
    ├── 4049390f22419e2acba2fd29b9bbfa180eef7602.nq.gz
    ├── 40498101e4794b408ec94cfa25437a7c56d4e92b.nq.gz
    ├── 405e9a265ff20aa90cef2297ff16fd4174085577.nq.gz
    ├── 416ecba73ea680a2ba7525092ada81d3a9067d8a.nq.gz
    ├── 4174473384ef370a1f536c9d8801d026a1e8c2eb.nq.gz
    ├── 4185e361c65477a2685a505f962acd70389295ab.nq.gz
    ├── 41d1b704f01c341dcf2bc3148bcc2fd002c61177.nq.gz
    ├── 4210f1dca6b3b99758459320ce3f0896eaf9c8bb.nq.gz
    ├── 443b527ce68dbf3fce7931292f87113101e07afb.nq.gz
    ├── 44bba9b8d85bf30bae86eca5ae5dc078321b8d25.nq.gz
    ├── 44e4d02a0e372184a315d272cebbb63030522462.nq.gz
    ├── 455ee355385f49ea50028f43aa8bf4d9adb84e0c.nq.gz
    ├── 4698cb922f39981e43ae100869bb6bd3065a4bd4.nq.gz
    ├── 4728ee63f85f74bfc09f3bb9513c3899984f4e8a.nq.gz
    ├── 4782d9b8e0aa9142f1c53a9a17d2b72489d43b3e.nq.gz
    ├── 478850affe255981b10e289f0e9f6004e41879ef.nq.gz
    ├── 47a31f090fc3e676becde0473313c77853393238.nq.gz
    ├── 47cffa9d3fc2d857dc1237edc93fe24beee7fd24.nq.gz
    ├── 4801d3dfa7309287aaac8c0a640127fb4821972d.nq.gz
    ├── 483fe89aa0a34c92c6e7afcf771dc8b1b8697a63.nq.gz
    ├── 48e96c725530182ce478cededafe2687b00f88c2.nq.gz
    ├── 49333e3e51567bc41ffadf83d1bb849344574083.nq.gz
    ├── 4a4f1a27789a4f797c3902a0494b284ab57b3005.nq.gz
    ├── 4a68ce262ec0119500c4d5fa5271c4db9d9476de.nq.gz
    ├── 4aa4e0f298bf58011ffd3282557bc4c8637d1809.nq.gz
    ├── 4b2f75d844428eee2ac0f68e95798db279f62752.nq.gz
    ├── 4b3b418aaa9137e5a54c79378fbab50c06178373.nq.gz
    ├── 4be6874b1a72abe59c818c39fc34893e5e92b2a3.nq.gz
    ├── 4c1b3068bfc4076dcb809be489d88ba490378fae.nq.gz
    ├── 4c3da325df910b08a1526f837ef86da7697333b0.nq.gz
    ├── 4d22515286535363fa95d29a02e82de6daf013fb.nq.gz
    ├── 4d4795ec23e0c3cd780c97d880002069755dbfcf.nq.gz
    ├── 4d573c3ed41acce5666123244351e9f92a5ae16a.nq.gz
    ├── 4f166e6c074ad381e2ae653f68590d6c2e69dcf4.nq.gz
    ├── 4f69646a09465a31901082d21387b1eaa4d28d85.nq.gz
    ├── 4fb550ea72f3d6acec3f6196ae4f1d07925a411b.nq.gz
    ├── 4fd3cce50aedd071ba1f8638641a82ed1fe79a41.nq.gz
    ├── 4fffb9572bc036a187351c12cbb0bc69211996b1.nq.gz
    ├── 500730d2635e8544d1fb81f08282d9511e627565.nq.gz
    ├── 50a5108fb0fb5c4d290cc3df9a5fc8ba1f3d35eb.nq.gz
    ├── 519fa6b251d68928dacd78e3605a97335d7a0f32.nq.gz
    ├── 52075578ccaed57eb3e3ad8df950c31be1c1fd22.nq.gz
    ├── 534289a8bb3760423a414b5d5fb81d4d4f368374.nq.gz
    ├── 535586a39592e32531045088e54692fce94c25bd.nq.gz
    ├── 54537ee9b3744892ce3c71a125024718205b54e1.nq.gz
    ├── 5464257d30c3285e901c3527895e34708372f075.nq.gz
    ├── 55ad644058a8345551d1aeb744909c54e5490d61.nq.gz
    ├── 587844617759de79dd07584e3fea8b97310f47d2.nq.gz
    ├── 5895174c2d136021ef7ec0d877fd0cdd1a289bb6.nq.gz
    ├── 58c68e865d8a43272475f827a414fc4fa1e3a9e3.nq.gz
    ├── 591888bbb90e0e074070cf79e23ab6ae16844a70.nq.gz
    ├── 5a12a923e0a80c505b3057940d54091dcde17c53.nq.gz
    ├── 5a131211791b4477b3632701ef8bc2f2c9f6aca7.nq.gz
    ├── 5b56e682673252c38219ed8ba361155583475c6f.nq.gz
    ├── 5c1108b1acd8b5d2745512f7762a3f276e7cd6c3.nq.gz
    ├── 5cb6d32c6073d4be6160bb3c882738cab92fd4d0.nq.gz
    ├── 5d1f38c89f40db7c31de99bdcd8c018aa8f83c4a.nq.gz
    ├── 5d5d05a14978d5f6211748ab5f17c1063f3d6587.nq.gz
    ├── 5e933709e46c761b143fafb9fb1a1784924746f2.nq.gz
    ├── 5ec337230818964a21b3bc2fe4bcff974fec6474.nq.gz
    ├── 5fefb606bb19d5334cfc03b4f04da1f053042806.nq.gz
    └── 5ff15e4bee2faf558459cbd0a8b54791f9722820.nq.gz

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

[pyro-ppl/pyro](https://github.com/pyro-ppl/pyro)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
