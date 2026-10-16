# Repolex Knowledge Graph of glue-viz/glue-vispy-viewers

RDF knowledge graph data for [glue-viz/glue-vispy-viewers](https://github.com/glue-viz/glue-vispy-viewers), parsed by [repolex](https://repolex.ai).

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
rlex download glue-viz/glue-vispy-viewers
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9b2aa91361204b4b7fcdb618e8f884584c0d0269
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9b2aa91361204b4b7fcdb618e8f884584c0d0269
│           └── chunk-001.nq.gz
├── blob
│   ├── 042c58d07ea727e7e306f9c104742e64eef67567.nq.gz
│   ├── 07a775b34a0219b5b7e31785293b4b3ceb9556eb.nq.gz
│   ├── 0b054d8f16b5b473d1f65bcc9967e8ac8ea03032.nq.gz
│   ├── 0ca523a29667f426d7b1eadda2d714c09fbed297.nq.gz
│   ├── 0f0e514b29799c57c477be1f055464a3f6bb3ae6.nq.gz
│   ├── 1009ff595eb5166581d6aff6acb59ff5f6770a0a.nq.gz
│   ├── 10e3290b0335fb9b6e27fec7dcbf54de4c82b1a1.nq.gz
│   ├── 188d9e80db29207de94c57f6cd5ce1ecfe5468f4.nq.gz
│   ├── 18ba4977c88cddb9b4ffed142afb36fdd839aa76.nq.gz
│   ├── 1b02249b04b5b8091a45c7cbe57eb9d391e058ab.nq.gz
│   ├── 1e7b422c5fd491f559e23f94cdbf26ab41d7b09f.nq.gz
│   ├── 217d094f92c2a387c3f34b54fb1ac3a5c3d28d80.nq.gz
│   ├── 21844563b293c5dca01159169788b35342428412.nq.gz
│   ├── 24a2a9b3dcbff63e69f75de70666d859e3cc2bf5.nq.gz
│   ├── 25607b91232b02c21570bf0d64906afbed903c92.nq.gz
│   ├── 28cf95364250b8baf1a93c46ec0f72ebbaee2595.nq.gz
│   ├── 2c12ac025caa02a1246527c819e7cd547f8b53e5.nq.gz
│   ├── 30d80f06f11d1f476182b908ba42bb3010754ba6.nq.gz
│   ├── 323c4e52619fcd81cc6d8f833f450cb1472d7e1d.nq.gz
│   ├── 3652e1c245bfcb4bcd27b1575ad882e7be12697f.nq.gz
│   ├── 36d372e8bb022e79ff8450b46f6fc9abb3bbbcaf.nq.gz
│   ├── 3a46e3472812b3e314e9963dab6fb0650f33d358.nq.gz
│   ├── 3cd54f35a70d52e9c796e0326a696d8834b7efb2.nq.gz
│   ├── 3dcf0e05fd67e4d8c3094012b312f57f93112f1c.nq.gz
│   ├── 3e20e9e9c1bbd93f5e7d2929559a850bbf58423e.nq.gz
│   ├── 3ea08585f575b6d5c381aab34fdb4f225c07d03e.nq.gz
│   ├── 3eeec8fd46e8dc873e479554e821dd2e0e3864be.nq.gz
│   ├── 3fadb19095e0072ee355f9e0ae45d0327960a633.nq.gz
│   ├── 4125d9709b91395412efe4e50dc144be4bb68b2c.nq.gz
│   ├── 41b1f601088504e173061fdd2011b8ba2e36474e.nq.gz
│   ├── 4667569eea6973364109f31263506151b81e789e.nq.gz
│   ├── 48de3d605b111e5c5af0fa019f033fb738d0110e.nq.gz
│   ├── 49e09fb35302c1938dcc969c67013198d4a26522.nq.gz
│   ├── 4a21c75b48d78cfcf2b14fc67802bb7f0df75613.nq.gz
│   ├── 4b2ecbb7b96a51b929b34867a916eabe33e2fb11.nq.gz
│   ├── 4ba92177a468d865bdee09c1a43b6159cb653fb5.nq.gz
│   ├── 53c9ca0956bfda7a12d0198ba512649dbc3e698a.nq.gz
│   ├── 56ad008c1c80e538e7f2d071c658aed0e44d9fff.nq.gz
│   ├── 58469a77b0b244756431712005bde9b6c4589a5a.nq.gz
│   ├── 585f8b20b7db98c8157fd0fd5008dd128e7738fc.nq.gz
│   ├── 5ae47c8a2dde25b98733415de2ef40ac86956e4d.nq.gz
│   ├── 5ae779a2f51f6d10786952e0bf67666f7ae7fc52.nq.gz
│   ├── 5c614f77fd1c356bce0826ff33e32387b7fcfb33.nq.gz
│   ├── 5c8acf41900520f6e4eb3b2832f58090f307b648.nq.gz
│   ├── 5cf3f014e237c406a51c7573d2941f81e7db55af.nq.gz
│   ├── 5e4e1c474cad1c9884ac200894551a9840653107.nq.gz
│   ├── 5f64a0fa92c47d8cc1693d0f4ffe001bac3d6e27.nq.gz
│   ├── 61f6977be31efbc74e18ddd3dc67e07baba781d4.nq.gz
│   ├── 63c0b29071cf2dd71226594952418df22aa84b8d.nq.gz
│   ├── 65c42811347568a1fa1a078eb63b878619537d5a.nq.gz
│   ├── 6a363b28b25ba92c2c2dcffdba1dcd23ca3b4275.nq.gz
│   ├── 6ad3ec5b4eb37d5604e04653403742ec0678b7ad.nq.gz
│   ├── 6f94027a5031a48fe101ce313d95cdb238424014.nq.gz
│   ├── 7303b4fe7ae1bd2edfc2a0233d015bdf271cf178.nq.gz
│   ├── 761f3b120d2bda0dc4f5227a69f10b3d239a3951.nq.gz
│   ├── 7e7d1bed04708c521986887ab2b3bbfd7c704056.nq.gz
│   ├── 7e89c253a6e1c0dc1303efb918cfaf4acfdd3e9d.nq.gz
│   ├── 80062f081b890dca5206d5a8ecef180af26f62da.nq.gz
│   ├── 810871804e071c5b6d785b14e65fa0034dd21b90.nq.gz
│   ├── 81b1b6186984c16fb8319b5a451433d9645edb4d.nq.gz
│   ├── 827986c3cca4eb3aa0049937fbc09995268d9866.nq.gz
│   ├── 83d9a7f2b441ac37ec0ad2eaa61847d1ec27d9b1.nq.gz
│   ├── 8d445604a95ac6a51874b6a1cbc812920719839a.nq.gz
│   ├── 9023b42410c65afafe6c89134033f60b3a6b3a6a.nq.gz
│   ├── 93ef49735c083926e467aab890f751f8b0f504ff.nq.gz
│   ├── 96936b806a8b78e89959ea505406506a40960a1d.nq.gz
│   ├── 976d6bd09faaa712c8a25d0893b33c06c41f732a.nq.gz
│   ├── a142f3089d87e151c3d3d1f1dfe0ab366e1c6f7f.nq.gz
│   ├── a1a461c2b4e0a46be7ab4b9e1f6aa77dad725bdf.nq.gz
│   ├── a4639204b87f14757e7e7d24950b5dc8decd1820.nq.gz
│   ├── a80dd78facbd4c2a8730f5fe894312250fee5619.nq.gz
│   ├── a81e0ad024f4bb439149ab4c84fcc73fa29fae65.nq.gz
│   ├── aa1e6f6d6d9e3d296df551ab571e4069155b0b0d.nq.gz
│   ├── ac580793b8155a8eb3eb453e2cdf04225c825a18.nq.gz
│   ├── ad32ccd7e11da68739c239e632a4588be8ea7dc6.nq.gz
│   ├── ad3ddd9b0465d2ca5cdbfd0b2ed40bc770b14db1.nq.gz
│   ├── ae677f1b555bd0ce7c7730c02626769c3f9498a9.nq.gz
│   ├── afed9c22257d49e2521e4fa384a93b1a7c705e41.nq.gz
│   ├── b253660ac19f9550240e2f2f61be08627e274670.nq.gz
│   ├── b372063be8f6aec1f55fd2cb1c497f67fed535c7.nq.gz
│   ├── b435f58a9e38007beda001392c77973014496a61.nq.gz
│   ├── b976ba6f4085f0eb048a9790cd6f2a823bb1c9a5.nq.gz
│   ├── c2c13e474aac3790ab5c80f8bbe4a537b1a206a7.nq.gz
│   ├── c32c65de2e68d2e9384be506576bf911a07324f4.nq.gz
│   ├── c5fcc0d10bc3697148243a92c8b3ce16404a6970.nq.gz
│   ├── c6df0990e52ff07253dcd62ddb1c96b4649adcf3.nq.gz
│   ├── c99e0769e78bdf0b7b27ece355fa30a1a4c55081.nq.gz
│   ├── c9b94f50c59a131ab2b2cd7024aa7a9aad8ba817.nq.gz
│   ├── ca2349f0e7dfddf500e79dcb2f21948f6f9390fb.nq.gz
│   ├── ccf5be1f9c7b19c7c5fcd17d2666b7f9f4a202bc.nq.gz
│   ├── ccfb57c2b0b3345c9ec4e90eaff6e267fbbadce2.nq.gz
│   ├── cdec13a5db31a64e80daaab5567c2a736383870b.nq.gz
│   ├── d3c26cf57de855a7f815433026cb87ecc62830c8.nq.gz
│   ├── d4e2739865e41245e5b5c06c59cdb4de5ef95754.nq.gz
│   ├── d816d8b5488a4332b42dcd7ba33fbba46207072e.nq.gz
│   ├── da3e645dfb38a6c9559727bccba2ec24fbb7f6e6.nq.gz
│   ├── dc6ca23e2082df48c57d14661dc3dabf41677d16.nq.gz
│   ├── dd9a40a9f9ca41937186b430511872ccb806ac3f.nq.gz
│   ├── ddcf1b22460430e1add2566230b4247a82478580.nq.gz
│   ├── def35ef4875bd1134f7a97351b9a29c096a76583.nq.gz
│   ├── e47b0888677c0d48316481ac2c928a1ebae52864.nq.gz
│   ├── e66dfb12c4bf52a01be972622d37510338cc6135.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8821a9b94c971d3bc615a1edd68b9d76dd50bad.nq.gz
│   ├── ea3b06bd7ba958609639f3f0787e2aa31442b182.nq.gz
│   ├── ec540125e3f8cbd57c07ddc828716bda56b771ed.nq.gz
│   ├── ed732322ce3e29f9620e9b3dc50bda0e94c1e45b.nq.gz
│   ├── f6b8c5a6680c503c6bed83d64efaf317758c6598.nq.gz
│   ├── fb7ca307d5050b7c827cf076fd713ef8c69e8776.nq.gz
│   ├── fdbb0a825c49dddd609745d15f24f4f189683712.nq.gz
│   ├── fdeff7a7b083d3c74e321bf0b217303dc23da27d.nq.gz
│   └── fea92a5e8ee4dd9a5573b705f6a9bbcc2b38134f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9b2aa91361204b4b7fcdb618e8f884584c0d0269.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 120 files
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

[glue-viz/glue-vispy-viewers](https://github.com/glue-viz/glue-vispy-viewers)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
