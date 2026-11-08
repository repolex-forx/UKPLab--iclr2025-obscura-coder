# Repolex Knowledge Graph of UKPLab/iclr2025-obscura-coder

RDF knowledge graph data for [UKPLab/iclr2025-obscura-coder](https://github.com/UKPLab/iclr2025-obscura-coder), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/iclr2025-obscura-coder
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e7ae88a77eb5946e81838cfacf2929575c9ef4fa
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e7ae88a77eb5946e81838cfacf2929575c9ef4fa
│           └── chunk-001.nq.gz
├── blob
│   ├── 000e2ee1a4a771e0547acb4f1b233b6f39c51281.nq.gz
│   ├── 01abe1fe517d071931c769532c2755a2c518c8e5.nq.gz
│   ├── 0486b916fb178555ced775ff5409844214ecf6fe.nq.gz
│   ├── 06f60823516cf29e0854aa947adf801b21352621.nq.gz
│   ├── 0d9360dc35d158ea1ccd025d9520994762579eec.nq.gz
│   ├── 0fca8062f8258ff4c2405c9c72918e1d5b3489b6.nq.gz
│   ├── 108fb45f27460f5d32a62fad0a7acef41b4d5778.nq.gz
│   ├── 120c6893b8af8f69dddc51b2734ed561b78c6091.nq.gz
│   ├── 12160580e68bcd331000cf23985777ab10574508.nq.gz
│   ├── 12daac04c5dfadfe2dcad12b7a4581a3e6c76fd6.nq.gz
│   ├── 17e97dbc8c07632fd384ae353d67c68be5156edd.nq.gz
│   ├── 19a5f87e99175344f2213bf4900f03b9538c69d9.nq.gz
│   ├── 1caca48962a63703b5aaa7b680f5bd1ffa6b5753.nq.gz
│   ├── 1cb63304638b5e78f56268dccf1a10baca207a99.nq.gz
│   ├── 202ac4a63af4dfe02f91b20e63802cabfd1e2881.nq.gz
│   ├── 21c5767cf52cceb6410be4e3481c626526614d91.nq.gz
│   ├── 2273890b2fdaf45e226daa9df97e39b84f57453c.nq.gz
│   ├── 23228beb06e9cd6dd07537e02c74a566967ae6af.nq.gz
│   ├── 23c06518383572ac7a704849070c1183b9002f29.nq.gz
│   ├── 253838015b25035acfc45597bd660def01fb1576.nq.gz
│   ├── 2be6361cd5dac98c986cd21988aad5a2b659f987.nq.gz
│   ├── 2ca3ba64b51469b8462afeb15e2c3cfae48fa220.nq.gz
│   ├── 2dcf47c47f2c585e39ad6d41fafa3804987acbbb.nq.gz
│   ├── 2f87d9c2bdc6c7f5f4e8976491402e18ffcf9c72.nq.gz
│   ├── 33741b0df7dea6a4359289c79da9069f3fd3cc8d.nq.gz
│   ├── 35548f18ef44438f08678832595c06f0983b9665.nq.gz
│   ├── 36704b92398e875a8e4a7df5cb7301bf3d3d0213.nq.gz
│   ├── 399341b76d28138779d6d9f03127ae0e43c97101.nq.gz
│   ├── 3c0f919b12237e5203989bdcb2fd6baa90dd2810.nq.gz
│   ├── 42257e662ec801711b6c716e784027aedb25b24d.nq.gz
│   ├── 42f053c1334624d97fd43190d7a048beccbf95fb.nq.gz
│   ├── 459ef54b32971261260a65258ac8995080db41bf.nq.gz
│   ├── 470f2cf1f569fe9e5bc4cc06a3e76f86a0bde2af.nq.gz
│   ├── 474ae18a872dfac644bbb257b3a305a39b5b84ee.nq.gz
│   ├── 48579053c22379df6eafb2fc23a975616ae0a3fa.nq.gz
│   ├── 4cef27e61ea9ac6f982e68a89dcb12432298bb71.nq.gz
│   ├── 5000388b82d0b41b0cfacebe3909d82df3072b61.nq.gz
│   ├── 5167250194e670f90dd2e63eaf29999c6de6d6de.nq.gz
│   ├── 5275f334bf922757b53daec8f2b43ed47960916c.nq.gz
│   ├── 56393d6fe1bbf599b62a0eb2291900bb00337057.nq.gz
│   ├── 56c73a37c8b3da5524e3e08879edfa11f0508763.nq.gz
│   ├── 5990aca3f0d0ee0b3963161e298556541292b617.nq.gz
│   ├── 5ae7e4f11cce08ffea32c787aacecb1bd2cf02cd.nq.gz
│   ├── 5d42c03dcf05c43440a137ed3b1c56fce5764c4a.nq.gz
│   ├── 6bbb0551d4d62eb0565ffac412c5dd82df43c021.nq.gz
│   ├── 6de5439796a2e435911bff2149c965349ace4849.nq.gz
│   ├── 71fb36571097975ae6177d2781a9c0c8cdc504c6.nq.gz
│   ├── 7283debc59ad50e37914ba969f0979e59b6f7237.nq.gz
│   ├── 73b86e812a21db061130df16bd61ae209741a85f.nq.gz
│   ├── 7477e2ca3f59c532fda5b14e67f659f53821531a.nq.gz
│   ├── 75f249b8cdcb0a961041a79637a435c443c28848.nq.gz
│   ├── 77dc22b3debe10856151905c06a1941d222c8d30.nq.gz
│   ├── 77f13434f028c62917a97dc8c1e4c532c682bb6c.nq.gz
│   ├── 798e686b3211b7c2a552d4400875cde7477cd9e2.nq.gz
│   ├── 7e1bd27c16607e90fe55e4e32db4aa5a2216ca71.nq.gz
│   ├── 7e4682f455543898bdc1d91ed1188d3da2b2c68c.nq.gz
│   ├── 806c3bdbad35072c3abae520c1261f157726ec9f.nq.gz
│   ├── 81a07b2fe92eeba9ed76f925ccb8d3525350adc4.nq.gz
│   ├── 82f97bfe22bd0219b0302395e8290662523b8ac5.nq.gz
│   ├── 84e60e48342836f7477b3f4b82c6bf477d16fb9c.nq.gz
│   ├── 85653c93c53efe77cec0ff320966b45747f67f38.nq.gz
│   ├── 8590262b1b9737a3b24e7286ce1afcb460015105.nq.gz
│   ├── 871745cd3ce64d3860b701cba4fe397ecb69687b.nq.gz
│   ├── 88b61b5079d69d1d39ec8f04e2f848c0d16231f9.nq.gz
│   ├── 8a32ee34b1603953ed79a91dec01453f67fb93c4.nq.gz
│   ├── 8c1897b9e0b451b4faa6c187f79f75a448bf3acf.nq.gz
│   ├── 8cc986acf363130ae4a2329d8577931dc927e49e.nq.gz
│   ├── 8f8406111692f414e4e2a9d99ccc7837610e95e3.nq.gz
│   ├── 8fb9c9560a3352ec23f81fd3ef277f46b94f4e17.nq.gz
│   ├── 9077a18506fcbb898ec6e096c95458687be343ab.nq.gz
│   ├── 9468b98cbd6c4be810bce95b63f242eaf8b6e5f4.nq.gz
│   ├── 94a0ec8b1b1e4226fa0f4bd9e853902fff7f6769.nq.gz
│   ├── 993e5502517bdc149050163a5e2aa44d7f9709b5.nq.gz
│   ├── 9c7f42c5dcd9165fe5e2cacd2003c7d26fff248b.nq.gz
│   ├── 9ccc7363dcc9155dec920e64a9820737d3fff0e3.nq.gz
│   ├── a213225a374f2fab58c491024b907b067a4926d8.nq.gz
│   ├── a28907c645c6b677325d40a3c8ae3bd033cf5ae1.nq.gz
│   ├── a3077ee0490a325f83d046879e3f9ea1250a561c.nq.gz
│   ├── a51e3c579ec066630ce11c628e39be02befb9240.nq.gz
│   ├── a56ca06517dace5baa6237e963ffea8181a8f42e.nq.gz
│   ├── a5e23bd6e193aad4b5445f45e3f4c00073bdcaf6.nq.gz
│   ├── a79dfc0c775903e16dbeb2bb4cd027274cf9ac85.nq.gz
│   ├── a7efad52b712e82ed61226517e188af655df2568.nq.gz
│   ├── aa3ff242d06b5931dbfca9fb211b591d33ede7c7.nq.gz
│   ├── ab0ac8c1e693abbfee0096ecb70f98a68f22920e.nq.gz
│   ├── ac094a1884b8ac6e64867d2c9bd5685c6cfb54d2.nq.gz
│   ├── ac2994780902e89b4065526f16a8633eeced09f0.nq.gz
│   ├── ac680e3e31a7f833d7079b467da5d9e9073fa522.nq.gz
│   ├── ad1eec12bc1504a578da11297420db3c682a77de.nq.gz
│   ├── af33b434e31af27da85370aeac21abd0a5f1996e.nq.gz
│   ├── b2ab68aca8107f6f83f6b17710d1da7069f75c6a.nq.gz
│   ├── b77916808dfce320504d098befc608f34ce83eae.nq.gz
│   ├── b8ed60a65e641217eaa896770dd04a11dfe67919.nq.gz
│   ├── ba3f032a464884728841dcf8b9d52f104deedb91.nq.gz
│   ├── bccf7361c5c75113df23e3f13668cd685dfc8444.nq.gz
│   ├── bdf1e07436efc8f5b0cf71b83c8780611d7cc5c7.nq.gz
│   ├── bf2948d038d33c2cee75b2aec3d4a7ce069b22ab.nq.gz
│   ├── c2b2a8c27b9c06af64240aef5f5e1b1adff0c11c.nq.gz
│   ├── c56a32da364dbb3327ab264cc7160a672c6ad57f.nq.gz
│   ├── c6a444b10382a582d9cd2ef41e00dfee20591bb8.nq.gz
│   ├── c860a2b0d78652f5c158948ef30137332b743684.nq.gz
│   ├── cbbac04beaae9e56619a422bfa5cb45cf39c27fd.nq.gz
│   ├── cc98b6933cd0df2705fd39225f24282258cd3685.nq.gz
│   ├── cd21252bb95269915b53e78e362af3836743fc75.nq.gz
│   ├── cd5c05c018d58d088b8951b55d12fe1a69617145.nq.gz
│   ├── cdccd3049e4d2775238e877a00cfdc0c5b9b7bd3.nq.gz
│   ├── cec2b18ac9036b35f264735d63517a89e69a26e7.nq.gz
│   ├── d175cfb30bbd372b36a3dfc68600665312ac7713.nq.gz
│   ├── d1eb0c7199c2ba70559531093f62178a5d1579f4.nq.gz
│   ├── d2500eefa0db0a1dea258a71768c1d2bffb132ff.nq.gz
│   ├── d54b81ac941b1cfec4420794ad0e2305d83920c9.nq.gz
│   ├── d87ac4f27b5d6a7b3c443b855eea6627c65edd9b.nq.gz
│   ├── d933752511bdbfee3c6abaa519f1a62c3eddc266.nq.gz
│   ├── db36909bc3cf9b303cac839f37f13eeda0fb1a39.nq.gz
│   ├── db7d5ae2cd8aa31c0d4c9db9b6d9d5ec19c41644.nq.gz
│   ├── dc64c77c19158e0c4a35692012942d4aff4c5fe4.nq.gz
│   ├── de98cdd5edea68ef510ff9d8910e8c787438066c.nq.gz
│   ├── e4b1954983b832e010f61cd39a81f5a5ea325c61.nq.gz
│   ├── e5d3f3123d75f47b4f554ded6b70e39000097353.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7329e9a1c11ae23aaea7efdf83d1c9ff3f3f6f9.nq.gz
│   ├── e8426858e6602e76955c70b4b55fccd9fd12bcd7.nq.gz
│   ├── e8f67a114b05937d213ffdf7e90311b98f3d6e58.nq.gz
│   ├── e931bc2bbfcace44b52813a67bb451897c8585d0.nq.gz
│   ├── eb2fd3e6e13d59fd176ecc6d2bb4a7ba48ab6375.nq.gz
│   ├── ec1eb8bd11cee51769289596862f9672541b676c.nq.gz
│   ├── ed61886c9818d839c3dc585fe6f3da738c6ec9d2.nq.gz
│   ├── ee7c6d4ceab89c04381a36e3dbe3d15a9137d5c9.nq.gz
│   ├── ef54350b210cb22798d7af2556795759619947eb.nq.gz
│   ├── f3804f140bcd70c8a9630160d95531b034566907.nq.gz
│   ├── f45565188105e076b24af5fa6f566bf697b7331e.nq.gz
│   ├── f49a4e16e68b128803cc2dcea614603632b04eac.nq.gz
│   ├── fae157c8a4af2aa68067903debfc08e4880b18d1.nq.gz
│   ├── fbd79f9294b15741f6a01870d1872f821be97930.nq.gz
│   └── ff441da5b8fc7f53903c8aaf4e7ed25f991f7d3a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e7ae88a77eb5946e81838cfacf2929575c9ef4fa.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 143 files
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

[UKPLab/iclr2025-obscura-coder](https://github.com/UKPLab/iclr2025-obscura-coder)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
