# Repolex Knowledge Graph of block/spincycle

RDF knowledge graph data for [block/spincycle](https://github.com/block/spincycle), parsed by [repolex](https://repolex.ai).

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
rlex download block/spincycle
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f4799097e85f8bda1cdc8212f97400408499291e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── f4799097e85f8bda1cdc8212f97400408499291e.nq.gz
│   └── repolex
│       └── f4799097e85f8bda1cdc8212f97400408499291e
│           └── chunk-001.nq.gz
└── blob
    ├── 0048c29b027981e98428599764f29cea447ae1f0.nq.gz
    ├── 0060dcaa5270e0ab14028aa3f933de59f6f3bdfd.nq.gz
    ├── 00fcf2300491879d2be37df6c4fe2a6e1614a707.nq.gz
    ├── 029d6815387364b828bd354e8d6ecbdec067284a.nq.gz
    ├── 03a37415238cb10c7aa61ec93132814569f33d5c.nq.gz
    ├── 041efe6738eab2a59b3e7cf419fcfa2b839f1e82.nq.gz
    ├── 051e3bd4b5c7228ea8d10fcecbb4f772bf021af3.nq.gz
    ├── 053e7ef0a9bbb1f2778296891516a8e4a07b2bc6.nq.gz
    ├── 060cd6e565d0809991a856135e2d52243e3a685b.nq.gz
    ├── 070a0f89a643fc31341402bd4c6d5f103596a4d4.nq.gz
    ├── 084333ed9680d6f0d6ff12631c805e60b9164346.nq.gz
    ├── 091d1bff22cbd46324530126bbfc863d8df386a2.nq.gz
    ├── 09df191adfe6cee35f0b23bd0686a9eb0fa35a45.nq.gz
    ├── 0a6c3e5c89046ea68923a53cec7d7f5e7b2794fe.nq.gz
    ├── 0aebe728bc983a7964ee1449230cf8ae542a167f.nq.gz
    ├── 0bccc169abf906bacaa77815d9f6dd23e22969b2.nq.gz
    ├── 10261d34c68a58a77b2ae8005e26a7622ec6330b.nq.gz
    ├── 10b722039af3d0de3785045e6d48cd26fc943090.nq.gz
    ├── 114db225513bbaa958aac41a4cc61e7f44c72717.nq.gz
    ├── 118c89020c292af9193431536c11788bc59afab5.nq.gz
    ├── 12d08cf2a25032b29e2a45aefed27f25e70cc7a1.nq.gz
    ├── 131c325d102b8cea0352a0ae7288ad04d750c5b3.nq.gz
    ├── 160739463b8ecd3aa42f3e09c3c91445086b9b15.nq.gz
    ├── 16800803f8fd3e73c99759b90362dca8f80dfbf3.nq.gz
    ├── 19bdd2cd429940858b2108f248a071801b81356b.nq.gz
    ├── 1c60558b76f3b669774578ecb1f3517d273395ae.nq.gz
    ├── 1db458ea6dce6a7b3d708ab0482ddb303d0d4585.nq.gz
    ├── 1e72c4b6756740d5e421cc43f2afd6592059b9ce.nq.gz
    ├── 1f1be0b5e4630e6fa304a345ef8446661a2c2ec1.nq.gz
    ├── 1f8edc2d5d80c4e0da43516a25f95d28b09c2652.nq.gz
    ├── 1f8fa41c771e28f04bcfd19ec59ff08c575ead37.nq.gz
    ├── 221e60768e57ff1071985636a98b8bbbbcc63b70.nq.gz
    ├── 23345e07b7f01e919243f1af4dd0fbd6a63ff8fb.nq.gz
    ├── 244e4cde0fe28d1865a0522dcd2bcee187a80d27.nq.gz
    ├── 2512ae47fc33248abf1ac2d18ba5216db3f9d4b8.nq.gz
    ├── 25d2824cfc3557cdb81fbeefb876d0eb38062a46.nq.gz
    ├── 25d9dd58f8053706a9d906f005f2dd8e0514b525.nq.gz
    ├── 262bcf225996deb9bfc5d35e82025576be54c0a1.nq.gz
    ├── 288819dbc30492307c9cb855cd9312f5d4613f64.nq.gz
    ├── 2a00c3d27fd84870d7b41665d4aeb9a32ce2fc94.nq.gz
    ├── 2dbb86ca7bd67187de931c4416ace262c6f8b4c7.nq.gz
    ├── 2eb79b802084ae3ae09ebc6750e6d3bce0e2de21.nq.gz
    ├── 2f761650e9a7361937dfef66af17c3d0996abd9e.nq.gz
    ├── 2fdc74a1e0237996de73d84ad25e4d5c631aa5da.nq.gz
    ├── 30ff3e73be9798f0ae21518e5881a892eef5dd86.nq.gz
    ├── 322b6242583db31b7089576c74982377605512d9.nq.gz
    ├── 33af94e078d1cf4aba0c3b8bdc41ab86af4ffdb8.nq.gz
    ├── 33fe92bb0c17f552eb8c247598ca7e598b256174.nq.gz
    ├── 354940c0e68812af658933371a0cd234923bd634.nq.gz
    ├── 35c36d6a70dc0a19a431460f194383f05f39f0e0.nq.gz
    ├── 35fc18269ff0623f3139469fe895622e4db7c476.nq.gz
    ├── 376579aa6c5ba5dd7913049693f914fc15f44209.nq.gz
    ├── 38df299aea3e2b64eac3cadfdab9989672e1aa60.nq.gz
    ├── 3b021612ed838467ca709c04129310eeaff6c2b0.nq.gz
    ├── 3b8239dce30415e19a234724eb94157000597ce5.nq.gz
    ├── 3fa6ccbe7ce22f2641144b9c3d742456e23bf25f.nq.gz
    ├── 40565b4e4bc4d7e828c6289ca4c6e2068b109f1f.nq.gz
    ├── 40a7dd5eb1656ab93587effe075ff8ed05778414.nq.gz
    ├── 425fcc1a8f71bbb9dd89870361795980f8d7b67e.nq.gz
    ├── 42ed185c9cf65a486fbaa14e841f89d783a0b342.nq.gz
    ├── 44d30f5ce52edc69e60be8022d119bba31ac42ef.nq.gz
    ├── 45c150536e5f3888554c294f27539c5d41072467.nq.gz
    ├── 469b03f5eb2f2ed96287f1058ea24a827ca71e07.nq.gz
    ├── 49b7e37bf5a63aea2d7caa6a6a8f07d64a95cc16.nq.gz
    ├── 49c54e42bad7f6f278cad3812e814ba6f5982628.nq.gz
    ├── 4a28c989be2dd3598679c48da4bf0a6d797ae4e5.nq.gz
    ├── 4b892299092347e6f4851ab81d90bec213bf46f0.nq.gz
    ├── 4d2f906e2604c59a316534975cde71495e46f77e.nq.gz
    ├── 4d43f72e2bd04796b064d8b2c7273e10a123c9f3.nq.gz
    ├── 4d7e037e4ab64daf4abc242ee8a81aa9cfccc578.nq.gz
    ├── 4f7cf83f917bff587c2510837478d2a950b05ee4.nq.gz
    ├── 4f8141076de7467ed8d7fb9e04e895e2c69a5db4.nq.gz
    ├── 4fb2ed59852488ea2f4d8f21c991d04b16b5e48f.nq.gz
    ├── 532308a4490e4bcf09db5ab1c9250867afe17dc0.nq.gz
    ├── 571d56b53ac63776c7dde0b9065bf8f3ef4f8d0b.nq.gz
    ├── 58e09ea925dd2e0458cfb7dcba05bdc94ae8d2ed.nq.gz
    ├── 5e0f40070abafa828b38cd2697ba9f955759f4af.nq.gz
    ├── 5e894a468bcd63d8b07dffbfadd14ece75992b0e.nq.gz
    ├── 6029664f4df3e0dd48eca85b81d836a3d37eae12.nq.gz
    ├── 608701e035f9fc4c55b6fa67dd35b8d1dc14aa42.nq.gz
    ├── 609e06bb3d38e8ffa0c3ba1e52720d486a269c60.nq.gz
    ├── 60b8ea4a847a070f89211a05049a79be75615eee.nq.gz
    ├── 61b38ce8c35f3247ffa5b03e1793e888169c1892.nq.gz
    ├── 62e47c609f95c7bfd0178fc6e34a9e699eeb6d84.nq.gz
    ├── 62e7fdd931d064b1b89ec6402802c078dcce4fdd.nq.gz
    ├── 62f76f8dda496fc869e094b50ecfde2ec88feb12.nq.gz
    ├── 636d0ab8ab29991578dd22fd53e88ad521827769.nq.gz
    ├── 65b7968e1e6ac56e8a76a232d07134ab62a9f1f8.nq.gz
    ├── 68d7c4ca8a4b279fb4040c1df495ef572a87bab7.nq.gz
    ├── 6a6cf642ce5967693c5587eafc37092d04d00037.nq.gz
    ├── 6b08d327202130b4056d9d0c95b64a4437b1e96b.nq.gz
    ├── 6bb4cf49db71f1f5c8886b5c4d73ce2312d4ae34.nq.gz
    ├── 6cb1815d2ebff8fc95d87fb36a1967cadd1f9e6d.nq.gz
    ├── 6d6678959a7ee84303ed9bf9ccfc8303051d8149.nq.gz
    ├── 6e079d0cdfc6db493200a04288702bfca3269011.nq.gz
    ├── 6e7c686095d20e27e15a0852c11a89d53288eaf4.nq.gz
    ├── 6eac47f255d865a86e7b5396d5dc4a6984101b2c.nq.gz
    ├── 6fc9db95b6e6494c26c2bb6c2e5ef393f61d8b8b.nq.gz
    ├── 7113bddc9f0b1b93376286b15e7305c024298aeb.nq.gz
    ├── 726503d3448a8b4f80b4ee212189c233786404ac.nq.gz
    ├── 732a71ec58ed77076b7ace19efd8efed9029af97.nq.gz
    ├── 7422c0fd286aace132798a911343506dc87d08ad.nq.gz
    ├── 7483b46b76d7fe0e71a135c0d5e817ca8bc42386.nq.gz
    ├── 768347b61b1652b0481057b0a46b7b0520cb9516.nq.gz
    ├── 779d277955ac412828f22feca841a856eb03f61f.nq.gz
    ├── 787888a5bd721d77481f5a71a871aeb7a99c76e7.nq.gz
    ├── 7a7863bcbf86102c94d5e54404a53bcca404c927.nq.gz
    ├── 7b857da90340ecbc8dde085f4a8acbbb05d2e935.nq.gz
    ├── 7eb81d4b09e045ab10dd85e7e539ac6290caf72f.nq.gz
    ├── 80608cee206f92e17311b75b84bc457e89cd3603.nq.gz
    ├── 81961f8bb29631f446a9d79d4f945984fe584221.nq.gz
    ├── 82417ce42d39fd8d2a628230b8874d62cceac51b.nq.gz
    ├── 83abe63d62a9c45d635dba90d1cf6f8fb02a18a7.nq.gz
    ├── 8437b9ebc7371d21e4898d2e47945414181c48f4.nq.gz
    ├── 87211ddfca2da855bbaeaadf7169de934998282f.nq.gz
    ├── 88f87f27935a84ea187bbcee831297ba9f719253.nq.gz
    ├── 8921626d07ad2ef2a640639b2a2af8d5c9483682.nq.gz
    ├── 8b6b026df093d82e3e7872cfb3e204780af4ce1c.nq.gz
    ├── 91d7cc186b67ed9e3541208a4c216cb27c803905.nq.gz
    ├── 927ad318787c4211cfaac0cb76e0c4d47b90aabf.nq.gz
    ├── 9531a3a02fd55945fe53e75dba5ae511422da9e1.nq.gz
    ├── 961907f7df9bd07298ace33afb0c06bab47323b8.nq.gz
    ├── 9740e121924ee32b16f332514b378f9110ab95cc.nq.gz
    ├── 97e5836021c58cc5991967cc3274416328397478.nq.gz
    ├── 9809fe73fffa569318207ee63472a635229b045a.nq.gz
    ├── 98df1009f6c7b50aaadb7869b4b7f26b26a2d0a9.nq.gz
    ├── 991ba779ae31b762abbe29b2f9092adae0ae3a30.nq.gz
    ├── 9c90581e239367b387719f184c53ddd6466b6943.nq.gz
    ├── 9ca887ca721261a9f0307846ed8bcf51840d63a5.nq.gz
    ├── 9d9d6a2198f797fd6df41d2800765920f72d2544.nq.gz
    ├── 9db7ae62599a6c5abb3ba84a83f053035e3aa2f0.nq.gz
    ├── 9f0daaaad535b5bdbdef155beef4ab2b4ac1e72b.nq.gz
    ├── a0292ca0da7072b5026c27eb394d724f2ce1f66a.nq.gz
    ├── a2abcff730a44a8468da9f6e975ec8d85e3809e2.nq.gz
    ├── a3efe87a74cd59d1b54bfdb633cd113f33270e0d.nq.gz
    ├── a80067f4c4ca93af3645ed66f2c50981a14bbece.nq.gz
    ├── a940734dda3a672a5c9df00ea7f869e055a70365.nq.gz
    ├── a9bd0c194a81001413b479e42193f69135b4bc8d.nq.gz
    ├── aa457e6b08c6c3ae57ee61ab071622a5a19ed0b1.nq.gz
    ├── ab1d1be2b3d130e8e18051ea109d26b04b3d61e5.nq.gz
    ├── ac535580b09103a1931c071c39fa107dcd19ffcd.nq.gz
    ├── ad7db5ff8435f65538a1e0206f2abc8cf4d7e223.nq.gz
    ├── b00fd905a32091ce8f85c0850a83ab8ef499741f.nq.gz
    ├── b0ccb905bbd77bb87bf5b2fa28b6b5009ce87dfa.nq.gz
    ├── b3d4e41224d5cf68ff73e3fd677bb205dc4ea962.nq.gz
    ├── b405e814ac243f80cb40ae24fc83846828af496a.nq.gz
    ├── b49e0a79defd12223a81581cfd56cf6617fc1bb9.nq.gz
    ├── b5f28bfba3663a44d4d333774037e37a9f5a680e.nq.gz
    ├── b7b67b417a038b62de5be78480ab6be8b2e39137.nq.gz
    ├── b833a7ed9d44bb87e35fa3374dc68c7c31ed8a58.nq.gz
    ├── ba5e8101ade749a350a68e22cee10be45ef29f12.nq.gz
    ├── bb07c062f68d58198528d15b7a8bb569e851e1ba.nq.gz
    ├── bb30639da519aacffdc758c92b277259c7cf1b97.nq.gz
    ├── bb7a7d6f41513a610078b90ea279a654c41f18d2.nq.gz
    ├── bc43c67123fdf2bdea4a9a405ff980bdf0223dfa.nq.gz
    ├── bc9484a2ab580b6809f46e848c55eeb4c3e5b314.nq.gz
    ├── bf4e791f5ae2e2607af421cafdf9bec9ce04f66d.nq.gz
    ├── c0d7f2ad03eb7585096141371c2875a0f3048711.nq.gz
    ├── c47165473d38f1db02b5014aacb1c6b239512afe.nq.gz
    ├── c4800168b1d06a15b7c1a7470afd63ff411f0218.nq.gz
    ├── c50b126689034e3cd02886bf958c4fbfe1415604.nq.gz
    ├── c6cd70182c23a9c01c9840f68711254afb5ede85.nq.gz
    ├── c795a75d4ac39238a49e874f828d614c3c112e94.nq.gz
    ├── c796d2fcb0e6fa5d2e8fa17acf6112fb35867cb5.nq.gz
    ├── c88109bf899b2a5678c37eed0ccb30bc2686186f.nq.gz
    ├── c9b1b0ca8f9decfa957d4e1093ca10d61e4cfc40.nq.gz
    ├── c9bdcfa101a4dfae5946b7e3df08d06f766cb3f1.nq.gz
    ├── cb8554a124bb89922d3e4e2687b0d951ecd4d393.nq.gz
    ├── cbdeb9f34d79b6c0d54506b7354071a47e699d3e.nq.gz
    ├── cd27afce61ea66b58534d9fd86961c4a0d5dbc79.nq.gz
    ├── cd70bec377f45887bdc9fc6046ba6f4f5f546b8a.nq.gz
    ├── d0861fa51f940568554d2adce3a59daed34504e5.nq.gz
    ├── d0c17611e65b0490b0bffca200e2637d15f26e5c.nq.gz
    ├── d4cfb8d03da18d3d5b901d1f21a2d177b83b39fe.nq.gz
    ├── d5b37aa8b3e768cd84b2c2281c8e8ac7ad6d8e40.nq.gz
    ├── d6ef9cc8782692ae79c2db081ab0342b4449ce1b.nq.gz
    ├── d80b5b7822f042a7238b0642865311d51e990365.nq.gz
    ├── da2e7fae14dc494de9fb859ee526c2304e9e700d.nq.gz
    ├── dd4f7400a664957a0144a0740f567652aed213c6.nq.gz
    ├── de81341552196fac1a4ac8530ace1d77e6918828.nq.gz
    ├── dfff4e9d01a951bd9410ea0f9d42c92ad09fc8ff.nq.gz
    ├── e210494bb49e9ec878c1bd421dd96584edd6b1f2.nq.gz
    ├── e3b9c98367ac31f13e18632f79fa52b5df6b6535.nq.gz
    ├── e3cd60a8092f4b43bf4f76a645b1ff24e07a69d5.nq.gz
    ├── e5191916ac0c99a028ee025bc4acbd9fd9ffab30.nq.gz
    ├── e88fced870410d937d79af8f37e18d20c5b02888.nq.gz
    ├── ea0f76cd3728b79d7ecfbdd615bc8f5a4308c90a.nq.gz
    ├── eb48866694c876bca912b1f01b5e0abbb497448b.nq.gz
    ├── eb5ea2908de0fc760d0a48327783bc1254b51b52.nq.gz
    ├── eb7acd867dbb005f06e8ac6d740efb27efb21252.nq.gz
    ├── ecca35fe89a53fa59d264a1fa0ec47908f95d17a.nq.gz
    ├── efab95f2cd87b55b47f07b7cbb62dfb38b89eb27.nq.gz
    ├── f00a70dcf5c8d34310b331a4290c67803f155089.nq.gz
    ├── f1afcd7fd201f1cd62743c5e4f4d9ce273002bcc.nq.gz
    ├── f1b97e0ce79192f9a001a732c583f430851cd6dd.nq.gz
    ├── f2c1fd9fd03ec8e17c5844de7aae1531673dd42b.nq.gz
    └── f6b661764895f7c559c0e9216ec7fa3a5fdf1721.nq.gz

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

[block/spincycle](https://github.com/block/spincycle)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
