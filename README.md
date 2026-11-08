# Repolex Knowledge Graph of canonical/multipass

RDF knowledge graph data for [canonical/multipass](https://github.com/canonical/multipass), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/multipass
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 382a0eef82f2028cb5e3475a48304f73a6f19b7a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 382a0eef82f2028cb5e3475a48304f73a6f19b7a
│           └── chunk-001.nq.gz
└── blob
    ├── 000c1cba2d305f032756ba5a944133f775295801.nq.gz
    ├── 00293421ac32650b44bd3b15949e89a5e7c3d05a.nq.gz
    ├── 00334bf60ed35164d277cfe5313f217b9d66d60c.nq.gz
    ├── 00eea9e143bb8e65cdd926803789fddb2fa45d5f.nq.gz
    ├── 00fa23ba8daff5643854dd007207a9af24d274a8.nq.gz
    ├── 016f44ca754cd650f439fd34b03d704c001ec8d4.nq.gz
    ├── 01beef21d42b064dde5281ddcbe901d857488241.nq.gz
    ├── 01d1f82bcbb5b178f4f5d8b69bda1a642832392f.nq.gz
    ├── 01e53f8ec20cc379ea5347e37c66272e231e9741.nq.gz
    ├── 036cef64f4f41ed9ef6bd3969e73696b1699ebd9.nq.gz
    ├── 0407d4f35e0b76268cd6f60b59ab6c31cbe9685f.nq.gz
    ├── 04478d979bfe65987c505d995f91c6b532bf196d.nq.gz
    ├── 04747a830ec88066955cc0545fe5b8a2a991fb37.nq.gz
    ├── 04f08905577c9b7c5fa9846973c829642145eb9c.nq.gz
    ├── 04f385df7add0be743adecd020a13202398522b0.nq.gz
    ├── 0524d5c71af637af4abd109df3a94d3df08e83ed.nq.gz
    ├── 05fcbcfc80228aeee0ce326017d4e3aa59558b44.nq.gz
    ├── 0636d06c1cf9f88e48301b3312bb21d16d0eb360.nq.gz
    ├── 064d73c52dadc73858dacf773f8afdd86b723ac9.nq.gz
    ├── 0656a0acbe6fb8478a0a8b7a2d5466a1ec071b6a.nq.gz
    ├── 07147d636129b3048545ff09371cf03e718cebca.nq.gz
    ├── 0858f3b78980c89c211772e406699e61472a6898.nq.gz
    ├── 0897a834ea25365772c7e2d2dc59a5564b62ca8a.nq.gz
    ├── 08deb38a0c5838bf08947a799ee29bd161ed2f09.nq.gz
    ├── 0a4a29ea8248fc5c459e80927f70b882eda468bd.nq.gz
    ├── 0c728a91f15e0b45428d7dd5505ed8a8823c2630.nq.gz
    ├── 0d179a633e4447717134047207a5ebea9b9be6c8.nq.gz
    ├── 0e5cbae54da19808777692dc36f5ffedd9a1d67a.nq.gz
    ├── 0e982de2a7107d6cb3a5034adbe41e0907f2ac28.nq.gz
    ├── 0f39206fd3a605a169165a522178c0edc02e5460.nq.gz
    ├── 1230eb725c2f4ff11b1ba09ee8ff66a065ebe530.nq.gz
    ├── 1234de16fdf3c6e576d40cdded87c1c8c91925c5.nq.gz
    ├── 133d828fdf5e0d7ecfd19cb7aae05649855cb23c.nq.gz
    ├── 13d81ca4c2c6ee0acb6315447aa5d4b045844c71.nq.gz
    ├── 13e7966f86cfc653d298ad695e22f304209ed9ef.nq.gz
    ├── 13eb60420e49f58d0023da6014b6040493fbb600.nq.gz
    ├── 158f9d10cd137886eb06a3f89b2fb8a8dfcbc557.nq.gz
    ├── 159d45fad8d0c507e9cdb893f1921c0c28de36a5.nq.gz
    ├── 15d8d668a26507364b4540c87c248a125ba5642c.nq.gz
    ├── 1611518ca2e16b2f9e70d0cac8dc55039ab3f9b5.nq.gz
    ├── 1631aad87e4bc779d76f80833c13042869f9cc2e.nq.gz
    ├── 1641990ab9868f04964bebccd07ab4c621ec5338.nq.gz
    ├── 16455168b4a3a3e735c85fda6fa06a0ca55f1e8d.nq.gz
    ├── 16acfe664bac746ddec5b323803cc8ec8e9dbf14.nq.gz
    ├── 170d9e51cbdfc084afaa289006068f7e90d91a58.nq.gz
    ├── 17c7e11cb136559800361cb94008f45e845a476c.nq.gz
    ├── 18605b46ae61ce2218ff39ba2952e77425c5ca98.nq.gz
    ├── 1890bf1d436b81cd101916f85793f06da9d46e49.nq.gz
    ├── 189ffd0dbea9cd70f03932758057a1e1d906ccdd.nq.gz
    ├── 196761c836269caa6294de495f96eed1b5010969.nq.gz
    ├── 1a45c6b715cd157c9da16331a877fe316785a60c.nq.gz
    ├── 1a4ad0cd918206963902636b2bcd0e37f0a261f9.nq.gz
    ├── 1a77267f4838bee725471d54102f1698836302ce.nq.gz
    ├── 1af0cdcd81a4f1570424cb7e32604682c9062cfd.nq.gz
    ├── 1d9433b6a3a2fa493ccd6e816a80901c62f022f5.nq.gz
    ├── 1dc8500b2dc687d46a04ab7d86653afa7e65ebf5.nq.gz
    ├── 1eb66c3bb49057edd019009b9095898106ccfb1f.nq.gz
    ├── 1f08da6fb3d0f62651c1759fdf28119a5e11d850.nq.gz
    ├── 1f0eb246def0f1b5159c34e3b3c34f37517069ee.nq.gz
    ├── 1f4bec7450edca5d1f62fd01df19ace42628ddba.nq.gz
    ├── 1ffc958f52d737063d3d36ed749f9ea99628d2f8.nq.gz
    ├── 20238573112d5ff5aee71ac3393826180daea75c.nq.gz
    ├── 2155eabbfd7a9b7dee17fd6b72b408a84bafebd4.nq.gz
    ├── 22e953d4ccc00b028fc348d4b7ed6e09cc163aad.nq.gz
    ├── 233759fd4bf6fbba765819d6c0244d8d6aeeba0c.nq.gz
    ├── 2357b9f634da18cca11627fdff43082e5b74451a.nq.gz
    ├── 247612a545e6db1eca09138eab6abcaca57427de.nq.gz
    ├── 24ef1b3959c9ac32cbb3e2048c7b9b0d11a32de1.nq.gz
    ├── 2501a848aedd5b85acf4e253f428470d87216b7f.nq.gz
    ├── 25439168d1e266a5f918bd86280890040cd48273.nq.gz
    ├── 258931f5dae103afc330ad6a8a7dbe2f0238da78.nq.gz
    ├── 265df71fb6daf0ffd0aa2f4e724e15b29594c131.nq.gz
    ├── 26b9b2b81c7e37983c8bb6c454cf711f47466f56.nq.gz
    ├── 27ae4a7e1627da4e93c4e3bca974a21291074d21.nq.gz
    ├── 27baf1fc7f9787668f4e23a5aeb3465e63c23bd0.nq.gz
    ├── 28bbaec69af82028454d3825f60e0c2334fc96c5.nq.gz
    ├── 28ef4a34edc2931571c813476bc03bb66f14b0e1.nq.gz
    ├── 28fff9810566b38223a79ce72f4249c79d587658.nq.gz
    ├── 2a83a343127e2d1b0b5dfbfa1d4978fef8edab2a.nq.gz
    ├── 2a931171aae883486a5a8656edb687ad2dd846af.nq.gz
    ├── 2b342fd797ba353f0d60dd8680e600997f1a6444.nq.gz
    ├── 2be3696e4a652f5f26953ca40dbb9d4d26a64668.nq.gz
    ├── 2c1bf0df99011511f6a02b37460564639ecf3fd0.nq.gz
    ├── 2c44fbe21f6410f34dff1acdedf425c52a46c5d8.nq.gz
    ├── 2c82daa24c9fb8b36ae2b9405155ae685b3112ab.nq.gz
    ├── 2cfae6878586515bd6cf47207e54e67d18390a6d.nq.gz
    ├── 2d34ffb15532c9e4ade23a8245fcba557aa4dc0c.nq.gz
    ├── 2d568f0fee30ff19f7b199c646c6bd2f048b7b83.nq.gz
    ├── 2e05d487cb2686fd412d4a1cfe2ea507012f99d0.nq.gz
    ├── 2e48e20ce3f3a7220e45e8a0497275ed32865123.nq.gz
    ├── 2ea9f2bd0abf4f8e810ff83f208ec6ef061f47a0.nq.gz
    ├── 2f595b29c5e6464e1cef298d21763baa0e5fe085.nq.gz
    ├── 2f82172ea5ccdad92f7d2baddd0d93754716a3fd.nq.gz
    ├── 2fc315aee09bb4983a0e6574489b87cd0af2ae1b.nq.gz
    ├── 2fda26f17febe89d947314a4ff98017d9333836c.nq.gz
    ├── 310774d4bad3955526d34ca54fe645e05f4401ca.nq.gz
    ├── 311e8e0a037817115f7f5e1bf0b3f35df27e3cec.nq.gz
    ├── 315929e687f67615c1376ebe1664363320b3fdd4.nq.gz
    ├── 31a1fbd1368fcd69352797611a87090c31f67fa2.nq.gz
    ├── 32546ebcb73b53aee47513c439d8a51caff302b7.nq.gz
    ├── 3294e40cb9af1e46443050e901928b6f92f3ff89.nq.gz
    ├── 347071e7df3b337472a602a12b27410ce78a6086.nq.gz
    ├── 351dcf5b054c682345a29f4f0a5d7ceae8ff2033.nq.gz
    ├── 35235b871c04d3c6e15ecd8d517d0277a673a95d.nq.gz
    ├── 35a399dba76fe5815c2a74638989f9c3d57ea037.nq.gz
    ├── 36167ed62397447cf3e4e527b386ab7258ddb800.nq.gz
    ├── 361f124c55a2a0f0442e4d99471c6c54911f9dbe.nq.gz
    ├── 36b0fd9464f45b33f482e64bea579787e142affa.nq.gz
    ├── 36c9b8a41478d758bb14c0248b2553324c8a731b.nq.gz
    ├── 36fc0cfeb8661eb61148eea913fe17ba0c47cf1c.nq.gz
    ├── 377666d533df783e0058445855d1258ed429ad1e.nq.gz
    ├── 37873c288e70d3950014a8b33f49c57271f62caa.nq.gz
    ├── 38596d1e5202e0317be39e9f35756ad2e37bb05e.nq.gz
    ├── 3879d54755798567f0f318d63340508d5668eb96.nq.gz
    ├── 39462d86a8cfd86b36c2d4b7445ab077d1f5ffad.nq.gz
    ├── 39f84ee27ad36ebde6a394da6b8df43328f5d003.nq.gz
    ├── 3a22b8ed82477c70cb607c735df31fac62a43c3a.nq.gz
    ├── 3ad444c26e02cf1edd0f3b89f1ddf28beeb0e532.nq.gz
    ├── 3b0466973a6b9050e966a172ebfe48eb5746f98a.nq.gz
    ├── 3b419fd3332bc466dea61532c0f50a6bd0454656.nq.gz
    ├── 3ba9f7ff65410c4330a552066886aa5c899f457d.nq.gz
    ├── 3bc876e4ad0b531720e58c855613e6dca89bd59d.nq.gz
    ├── 3bf558b199af549034e34413b97f2e6d16969558.nq.gz
    ├── 3df227f32629844eb3ac68a20f9ea4f7563944b3.nq.gz
    ├── 3e2f0420704b00f86476549bae8bc239f01d8705.nq.gz
    ├── 3f1523ea3c76c3ca9b0fdb31b566c45524085e84.nq.gz
    ├── 3fa22b159668bcbd666fb3de5a3c3b47bcb2bf83.nq.gz
    ├── 3fc416bd513a23f0b7a2e096313db3ca97eb1ae0.nq.gz
    ├── 3fedfdceb4b141d3f5c8e1184fb8cb8fbb7fa192.nq.gz
    ├── 4071bb2caccd7f7034d7ede53ac88dd4a16293af.nq.gz
    ├── 40d7ce2099d1a98f01d5bae300aa9b7c6209aa25.nq.gz
    ├── 4149e29d65359a2ad89a11624f1c0ba1353c5cd5.nq.gz
    ├── 417421c1e8eed362862dfc23d85225cbdaaf529c.nq.gz
    ├── 4267ca46182bb31e081cd8327f4de4588b29f8aa.nq.gz
    ├── 42bcbf4780b187e80025b7917058bcb882012aa1.nq.gz
    ├── 43b6dad6089fc88b00af7a2502b548f0258fed66.nq.gz
    ├── 43c09bc325a69e58344837aca1ea35b22b835534.nq.gz
    ├── 43e4e50e6bff0f5510457c834f5b998ab1dc26e0.nq.gz
    ├── 4426923c4715c9990fb1216b106d5401cfc0e668.nq.gz
    ├── 4440f599513e820eca837a065893f8664c06fce7.nq.gz
    ├── 4525507b595c8382437d7e82ba9479878d061f47.nq.gz
    ├── 452a348f3ba0bc8ff427c3ea0323e9a502dc19c0.nq.gz
    ├── 45b711f8fb89768c18bb82eb35d9173204299f04.nq.gz
    ├── 45c708ac4b8cd3a50cdfa9641df8f3081e0b2434.nq.gz
    ├── 461e3debb25a417cd1c0ab6b4093dba1a81012eb.nq.gz
    ├── 475efcb877a049c5e677dac1a232fcdcc09a469a.nq.gz
    ├── 47c5ebe923d146804797f70749c483e5b48258fe.nq.gz
    ├── 48704ee5136e4c5830c48304cc16276fde4ca8c5.nq.gz
    ├── 48bc12af510d7393a8f193fa0f4b7247e43fdc1d.nq.gz
    ├── 4962f1fccf36cd500e3237ef659b16ac7cac4a95.nq.gz
    ├── 49de43575b9f8b366c0a6582591dddfcf7b85973.nq.gz
    ├── 49f71055c782e8667e2f92fa1b147482a8b5b350.nq.gz
    ├── 4d3400a26a1b17e52c4750fb0b99ba7e870fb428.nq.gz
    ├── 4e9e95133fb3221193003cf3c3bb3166d7f7fa88.nq.gz
    ├── 4f4d1bd0003d38e8d994ead27a7a841e746707d2.nq.gz
    ├── 5019661f9fd1bb9e0bed8480f1e58dce6d004c7b.nq.gz
    ├── 50bf9c38d04e42b7d5beec91a67f83d856ba8ca6.nq.gz
    ├── 517e942922a74266a6df826a335c7a23d5b2f280.nq.gz
    ├── 51c599f6a284697168c49ba063c6f542d969f59a.nq.gz
    ├── 52531e446bab835d06e44f7d11ea3fe418a978ec.nq.gz
    ├── 5256250b33b439c137aadeaf50f7c57c498b16ff.nq.gz
    ├── 529c8cb3438756486ddbd20a8fe5051af84fe23f.nq.gz
    ├── 5341e5d715e9e5a978d1d15e79f27c395ca6461e.nq.gz
    ├── 5466742ba04214ce92f7df9e9bb85286e5ddf910.nq.gz
    ├── 546f823423c3abc9fe8d8bf31af232b4eec96437.nq.gz
    ├── 547ed438d32457b9eab562a235dfb9a6d101b032.nq.gz
    ├── 54a92b33d8d45972bddfbfeba90192b652892339.nq.gz
    ├── 5502659f93556cfeab97f963df70edc53c87a006.nq.gz
    ├── 570f6cfbadd3fe5ba1aba2e1ac6948accf63bf97.nq.gz
    ├── 57ae4aa02e4f131c7441b732b9a67ca390c6b8ff.nq.gz
    ├── 57c5c617c047e728cb1947dbe2ee13eba25c4547.nq.gz
    ├── 58c18eba9ff2116e02dc5d63ec7fd85e9126c5ae.nq.gz
    ├── 58ca2bba3a1133522149219677693abebb2f8f18.nq.gz
    ├── 59803c25d47e0ea8c7aaba49a7cb67c7d9e32531.nq.gz
    ├── 59966719508d9dd1a8c0eaeeec2ed723b372dadc.nq.gz
    ├── 5aa223bac36f144d138bf99704825a2984de5276.nq.gz
    ├── 5c8ee9ce7f8265bd351a12b1e8466d01bfe5b636.nq.gz
    ├── 5cc84a4349ad846b56d05fd95d91d12c2ad0b8a6.nq.gz
    ├── 5d0c8b5854692a8ecfec6a6a41f66da4a90f4a17.nq.gz
    ├── 5d2834f2845367cbe8a7e54add50996850468f35.nq.gz
    ├── 5d4492ea551c29009a066745292c40bc7ffb25a6.nq.gz
    ├── 5dc39c4e896c56b2fde6d0f286f768b2244fff78.nq.gz
    ├── 5df278b7f0783c656335ed4ec622f2b01d0395a7.nq.gz
    ├── 5e0063bab8bd47d4ab3e12eab9658f668cafd81a.nq.gz
    ├── 5e5e99dd7af5645af93a0a3787d6a33dcadd6211.nq.gz
    ├── 5e9fc03940839eba6a2eeb440a019a1f744f7229.nq.gz
    ├── 5ecc154bdca6702b71e509d108aede2f39592eff.nq.gz
    ├── 5ed325eef6d96be55e1c05b9c0cd6414974432b1.nq.gz
    ├── 5fe3295eed4f24764dbc3e31d510152b95378a8d.nq.gz
    ├── 607242e8e102f03d0f12482006b61200d25c942b.nq.gz
    ├── 611af79527770845718225f207b31dbe88145c15.nq.gz
    ├── 6121b29089a3beef4ce6e0ce0faf043609a0baa6.nq.gz
    ├── 614f39a1849e3732ace1e3ca8011c696f7bb4642.nq.gz
    ├── 61a9ca987b0a366c76d50a799ac5a095eadaf30e.nq.gz
    ├── 61dd5dcf3a845ed2a2bc839af38f9a259cba0e70.nq.gz
    ├── 61ec2d4f5903f224416e2478965c51a0a0815988.nq.gz
    ├── 62165b9ab5e1c0079f3060a73f15a8f8deba50cd.nq.gz
    └── 6265269778dadb278cd346d8728abd328c05f423.nq.gz

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

[canonical/multipass](https://github.com/canonical/multipass)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
