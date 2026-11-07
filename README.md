# Repolex Knowledge Graph of allenai/SERA

RDF knowledge graph data for [allenai/SERA](https://github.com/allenai/SERA), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/SERA
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1ca8673bd527b164dc9eb89841c96416ec8ce1a7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1ca8673bd527b164dc9eb89841c96416ec8ce1a7
│           └── chunk-001.nq.gz
└── blob
    ├── 00577d26e4f59b28f67775e1cb4337b71198cd99.nq.gz
    ├── 0095a3bb09179654d4c559057cdcd1cee4ff7e6e.nq.gz
    ├── 01f880e3a865e9c3a6a303716a33035eafc81b87.nq.gz
    ├── 0226cb5e79331c48c3c4613867b27d398657cc56.nq.gz
    ├── 03ff2b07e8285420f2fadf403989f1ed2844fbd3.nq.gz
    ├── 046a90a0eb69f363cdbdc9eb6c947ebc79278f71.nq.gz
    ├── 053f09ea5811b18de2cf016c2c8c419e1849fb1c.nq.gz
    ├── 071182be079712403c5467536ac2b20a61fe6fb5.nq.gz
    ├── 088b140b38e9678da165427a94237770603b9928.nq.gz
    ├── 08f8c3e3989f2fb810abfecd6279f15f80905844.nq.gz
    ├── 0b2cc577b5797f3247d59850acc7536326b82943.nq.gz
    ├── 0d4f24ddd78c4f540d815563efaafdb4573384e8.nq.gz
    ├── 0f97a59d012fd571ee7dccc88b6b55340a1ace79.nq.gz
    ├── 11a642bbd98db4ca7ae6b5ef4aab95479ff519d7.nq.gz
    ├── 11e4c60a07cd75c036bfebd82efd08a9bc09d9ce.nq.gz
    ├── 1269e772dd843a938e67691a1647dec5a2d5a040.nq.gz
    ├── 1279e2e68113d28798c893fb6bfbc627bb6dcaf7.nq.gz
    ├── 1484d6cc4e33bc27b19892d2bb54718976707072.nq.gz
    ├── 155bd9ef5d64fb5f3a30cccc6f305031ba51af70.nq.gz
    ├── 1674bf6f0cbb2ddc1844eca85e096671963f994d.nq.gz
    ├── 16e708d8a6fb3b06fde71ce2cbe6f7563026eb2e.nq.gz
    ├── 17ff0d9d5eb2ce39fcab161c498b012dd2fa99a2.nq.gz
    ├── 1912b13e0036040a8dcaaaa3219940c22d72a8e0.nq.gz
    ├── 19a9fffdf3952488321cac1cb8b7f7e92feabce1.nq.gz
    ├── 1a35efafc503eba0d9521f1bed6fea59800a9631.nq.gz
    ├── 1ae0c6657657d9d7b65a4bcbc2ee2ef29b135903.nq.gz
    ├── 1cae613497dd10df7a97cb486a84cd50d64ae344.nq.gz
    ├── 1db8f4e5cc2ac2db3f1328f7d95bdffd33e7d5f1.nq.gz
    ├── 1f375c80a19a154c9f7a3be35387b545d123675c.nq.gz
    ├── 204c5efbb445b2ff799620c492cd00f7d3e44bf2.nq.gz
    ├── 216378cde4ab82797eef297f1c4b3cce2571ee4c.nq.gz
    ├── 2179108bda23095880d24802f32a1fa154204426.nq.gz
    ├── 238c408765e8b784e3a9600b31961e7231d73aa9.nq.gz
    ├── 2391d5c0a8be2a090af2cc74a92a7153895bc64e.nq.gz
    ├── 23a72556a999610735b0c40bbd0206151b5e8470.nq.gz
    ├── 2423a0a7eea8dbfe78fe8b9e64cb16bcfb51d33d.nq.gz
    ├── 25c8add55899ae057f4105580c5cd6e2fd7af963.nq.gz
    ├── 26fd0456b6bc96351bcf336eda72f7e67539ab3f.nq.gz
    ├── 273676647ce1f128b458e9ed0ece9fddafbf8f9a.nq.gz
    ├── 2761fb65032aa0df440cff1c8da6053f3b3e5498.nq.gz
    ├── 284b276df6a05fdd3f20fd4635331306ab3789bb.nq.gz
    ├── 28a5d4ea0f93237822e27c311635f39172ed042f.nq.gz
    ├── 29aba4ae9393d03b711abab10c0f0fd100982e60.nq.gz
    ├── 2a91056d4dda1801ba039ab282951984e1fe13b8.nq.gz
    ├── 2b419242da064d9dfec93fde65115ddadeffe6b9.nq.gz
    ├── 2b88f8bbb5c91ce62135a6e262d029287ab66136.nq.gz
    ├── 2b9c782a0a2b6ec6959bf4d956e206bf03ae2d04.nq.gz
    ├── 2c8a1334181981ae1650a906d23a3d6b941083c6.nq.gz
    ├── 2caa3373a704d7f125ab5f2d405641a83c3c4705.nq.gz
    ├── 2d04464ef1c7f0b034e0549d477e428ee2a6d81e.nq.gz
    ├── 2d5798def6a274ba26bebc5bf1862a50d7fe72cf.nq.gz
    ├── 2d733f09ef806a6464d2d841d2db30d224760c73.nq.gz
    ├── 2e0b7ea84091bb85df8b9374c835ac43e415668c.nq.gz
    ├── 31b4050fb53ac620b83c669fa7ad57ca499ce31b.nq.gz
    ├── 321b59a79f871ba19cbf338254acc058a6ac0134.nq.gz
    ├── 324cdebc7c38a0aa0c482ca1ec0faec8041221dc.nq.gz
    ├── 32caf2a600a7476f80d2a8efa6b3373c842988ac.nq.gz
    ├── 344f79b025d6580f138e164d472bbe4b590a7b6d.nq.gz
    ├── 36184dafab8e28079e8e4f95c99323d3d0565d25.nq.gz
    ├── 36a424dfcc757ca46f9d52ef9e9a565004d2ec79.nq.gz
    ├── 3780c3de1ef136bf5000ee6a0f85c25a91229b45.nq.gz
    ├── 39344fc1f8c77d5ec43539d0c8e655f4b5d7d6f6.nq.gz
    ├── 39481a0be5b440486113e9f504fea9f1da23a724.nq.gz
    ├── 3a31bc813ac0a7e2106dc44a3e66dc25cc358c30.nq.gz
    ├── 3b1b3e66e76d9811f730500238385426ebf69e1d.nq.gz
    ├── 3c3d7187b632a6450391f4ee034f243700ed7c41.nq.gz
    ├── 3c4ea6a385d7ab103c14b5f5e9135431809b8119.nq.gz
    ├── 3d65eac7ea406c299b0b9bc19441cbdea9ced194.nq.gz
    ├── 3de03918403ec94304a249779812233993477b8e.nq.gz
    ├── 3e3f07cdf38b14373f23833a837197c53675866e.nq.gz
    ├── 3eb6c951cefe7e73855c2afa3ebe26df15bf1a90.nq.gz
    ├── 45c70c4c7390ca1cfec0d32857d970c7eb1f9517.nq.gz
    ├── 47889ecbc9e4707be0ab1ca068c1990e2f6445b3.nq.gz
    ├── 47ee6ffc66e7cf20cd494f96b06ce632b799de19.nq.gz
    ├── 4931f42057f03f427aebd529da2f09aa33a7306f.nq.gz
    ├── 4aa6e3ab3850499e292d5f9bba9835d5ef2c6c75.nq.gz
    ├── 4b20bde9ff9240ce8cc578e480f4d9aa8555bab4.nq.gz
    ├── 4e17e9e948855b258b9d1d714c47e5b74cb96dc2.nq.gz
    ├── 51acb2fcf7bdcf28b1a631e5e4d58f4c28dc5872.nq.gz
    ├── 543457467bf139f189957462748390d93d0e4ec6.nq.gz
    ├── 55533c76e17bd0c6cb49de7655a80dbcc185d999.nq.gz
    ├── 575e0715602285c8946a2dab63aa57907afd49fe.nq.gz
    ├── 5792511efcdb9954e898014f981edff19fffb02c.nq.gz
    ├── 58a7c47f2f8c3230a029a32234b306ea4050d2c5.nq.gz
    ├── 5a08a36efe186b213ee70f0a9bb04a904ae351be.nq.gz
    ├── 5b7b7bdd7948b56390701e657ba518b8c9ef6e2b.nq.gz
    ├── 5b8ecaf26f24988e8e86db32bfd61b22e6282746.nq.gz
    ├── 5c1382028327e972d9755c16345b11e4c045ef4a.nq.gz
    ├── 5c498afae93dc331a926127d2403aeed8918b624.nq.gz
    ├── 5c559d9180c54bd494a811dc05576b334231558d.nq.gz
    ├── 5c93bf830cf2f410b3aa8dc77616250789d874ea.nq.gz
    ├── 611fbcd0e97f22d3200b2eb142961de42b03474f.nq.gz
    ├── 64f8f7a98fa2089c763a194e53f51cf6e6c3f53b.nq.gz
    ├── 660b17f3fc7be75170fd8d2223b1bf3ab9f8701b.nq.gz
    ├── 66719acecfae3f33d3d7906b8b1665eea74e63f1.nq.gz
    ├── 6762fbeec0762b02c987aacd61dcb05fb594c490.nq.gz
    ├── 6828c7c6489ddfb65db196c1afcb3bafc6dc6314.nq.gz
    ├── 697b4ec2c741ed0662c669aeb4903bb9816d8f8f.nq.gz
    ├── 69e567526694082f875a49c0b37d4d7bf1eaaa2a.nq.gz
    ├── 6baa0835c8bd8ac6603597a848ddc42cc9d28323.nq.gz
    ├── 6c52c5ad87e1b50d8b450a8c81edd19e507259fe.nq.gz
    ├── 6e2ccca4da1a17eefb5979af72697c1029c71f82.nq.gz
    ├── 6e6777783a086bd7eaabc9463acf1db848bfc88b.nq.gz
    ├── 7115b449b246931f275478775b044c054ece6077.nq.gz
    ├── 711819bffe56e1d709a3ac4e3d2f340629501654.nq.gz
    ├── 719e8b21a023b68c3c71a82db2897e1d5d913d4a.nq.gz
    ├── 7473a934c7b58a98919adbfee36c0b0c0a1bf88d.nq.gz
    ├── 7505701a56d2d7fc342d5e0957faeb11437a7f9d.nq.gz
    ├── 7562e076860a46539c98d9dff69df740d67dae8c.nq.gz
    ├── 7656c88e9674083a151140c1192cf2149bc054cd.nq.gz
    ├── 78785708e6b4382a95420a36f1d5b3ceaef3b352.nq.gz
    ├── 7a3a9ee933d2169f7ebe81949ffa14ff0cc63d8d.nq.gz
    ├── 7bc5456e78699b04c3e1e2d0ba7a19b16d014d08.nq.gz
    ├── 7ce66c66f97c1c02bd1293224171326107e55098.nq.gz
    ├── 7d1146421f417a568f9886855b1e265b9d35c2c9.nq.gz
    ├── 7da1adb87b98e7e6bbc2adb585460ca9e8c66d27.nq.gz
    ├── 7eca31c6188eb3bc6fc4d07ae5ee0d6a4c1b9039.nq.gz
    ├── 81d99416d534cabceb200dc9f8039fe8d3fcb76b.nq.gz
    ├── 81f1e5a13e5a039cfc0b2d0d8711e5df14f529d4.nq.gz
    ├── 82987f56864581972e02141add2f563ef6aed969.nq.gz
    ├── 82a00258fea8a438a687459fea1f50357fc1583d.nq.gz
    ├── 83f8b284b81f35fecaa2f547c92778585e62ae76.nq.gz
    ├── 84fa443e26aa27dc7da44fb6d4f0b60ad1220d96.nq.gz
    ├── 856b53a8f5a468a1ccb2e68da4e1f27a416c79ab.nq.gz
    ├── 87d73f94a51287acdcb2cc554a99972057223ad2.nq.gz
    ├── 88da74627352c9d23c5db2602b37cc9ab79efc18.nq.gz
    ├── 89790db1fb154951538ef19836a4e485836cf065.nq.gz
    ├── 89b494574685239884e4f6289243f1fbde1f45ad.nq.gz
    ├── 8c2f37bed495b4fcddd54849116439d24965e7f4.nq.gz
    ├── 8c4d989ba8cd6e3c0c5512d665d9e368bfb8b121.nq.gz
    ├── 8eb9af5db8488d58b8dd116df99074b54b42c0f7.nq.gz
    ├── 90352bce5e8794cc722438b8e1a904028a7e806d.nq.gz
    ├── 90effb4622f2c5643b83838e79260918cfa5526b.nq.gz
    ├── 9365477b61ceae45735cd7f64494053a3563ed2c.nq.gz
    ├── 94042b712123230ed1e8ab21e89290de4051b663.nq.gz
    ├── 99240b9296a965333119f1e797e7dd7e9a7d0b40.nq.gz
    ├── 9940807dd8f581fc37353d9cef83f70127eb21fb.nq.gz
    ├── 99e74489b859e21fcaa68e93089035c3d81a73c8.nq.gz
    ├── 9b616d0af8108cece33bb1e719c6a537008839e6.nq.gz
    ├── 9b8f91db8657595362157ad8e32dee0d3e0f7e02.nq.gz
    ├── 9d91992cb39ecf0bb586814e2cfff94128139101.nq.gz
    ├── 9da12cc7e5b5e0910fcc5dd88f63d1827cec1b04.nq.gz
    ├── 9e0ef75c6664eea1caea113b411e21dcf3c01d66.nq.gz
    ├── 9ec1584bdf96ea935823fa53b12f33ce1b2f332a.nq.gz
    ├── 9feef813e445548a789a0e5abca36915c106e2c9.nq.gz
    ├── 9ff85feb97d2fef6890b228d088ea7e1b6a8beba.nq.gz
    ├── a0590eac07463b22c2cd82282a4f1b8401e3c318.nq.gz
    ├── a178d34eac088aa5dfc1ad5d0873420c7e28fa60.nq.gz
    ├── a4f946ddbb543431218dc2c287cb4b5056e776fb.nq.gz
    ├── a5a0accefeb6ad188653c123b8ec3ca1cd20d03a.nq.gz
    ├── a6539395cfe99c69fcece63a27418d5c3b42a8f8.nq.gz
    ├── a66eb86e8bfc72a4e35055cfabf706cee9ab2819.nq.gz
    ├── ac3519645bac9e5d1a780d98107843fa7e51dd47.nq.gz
    ├── ad13a430882ac814b87c3834808646635afdf7e0.nq.gz
    ├── ad883bdad310f837f5be44563af7aab887442705.nq.gz
    ├── ad9541fbfa1d2906d2188504046f2734e0b5d868.nq.gz
    ├── adb4a368f0f6116b75083163b0c871a24c1afbeb.nq.gz
    ├── ae056bf9caa12478f3c4a9d5f971b9c8f54ce92d.nq.gz
    ├── ae904111cd49a33735654f12b75683585dc0c515.nq.gz
    ├── af3ca129af2921f646f84e8b5f06c41d144d461a.nq.gz
    ├── af540554d0032cc6b7376a0004606b8625c90879.nq.gz
    ├── b430dd65eac8e3a547a89d0d61dc1b2845db6546.nq.gz
    ├── b4c9b079ad8dc97729085d8c8251b3fe65abe2c4.nq.gz
    ├── b53b246a63008d6753672f1bc27dfea2a96c2256.nq.gz
    ├── b8f074d644ecd031f9442516f5fec4c1d8b1e8a5.nq.gz
    ├── b924cdd2474775062830000bc3143897e5275612.nq.gz
    ├── b9a22764780586331c34fe1cce44bc0ad4ea656c.nq.gz
    ├── b9b5c34117a72a47e07fc6404d9fdc20c3c4c0c3.nq.gz
    ├── b9b70527dedc4327d6eb1a8291c85205ed76f61b.nq.gz
    ├── ba5d870aa6fce4fb5c54bf4b650078973545c8ae.nq.gz
    ├── ba6ca1448ebe75b96dcc02639c35c1b28c67e7e3.nq.gz
    ├── ba850ff8474b22495210d5d13fac052af992caad.nq.gz
    ├── bb76b62aff647ad174ef9a16de82f628d8a2616a.nq.gz
    ├── bbf8b426d7ed7d27ab3dfb28623398b0cb0b8bfb.nq.gz
    ├── bcb2abbedd97c9e6b707cee0508705120b8ecd9e.nq.gz
    ├── bcf481b4601425da13fb4a79ca770830c58c1bce.nq.gz
    ├── bf1fd27ce87f1371790bb1305a14a4654bd73b3c.nq.gz
    ├── bfad273e3d9f9a14c9127e07db0f76148e07cd23.nq.gz
    ├── c24ee30e9fa24e0abf142bdc0ccbda70f67cd295.nq.gz
    ├── c34ce11a33b0e48a6ca56be835fb9a1c5ccf052e.nq.gz
    ├── c437a7cfbba2df79597c65567f5294af48dd98cd.nq.gz
    ├── c9f93f10f5ffd9720b6044dcee3a9e5115df4eda.nq.gz
    ├── cc4df87695c14b4df1708b8c633035707c10334d.nq.gz
    ├── cd2bf2162b441a7aeeea609409fd2c87baebacab.nq.gz
    ├── ce22bae12089f44776d7be41d208130e5c2814d8.nq.gz
    ├── d170dc97e804c5b71876ed651a50027be5ea1695.nq.gz
    ├── d2500426dea9ca78fa29c1e862186f53b627fa29.nq.gz
    ├── d4ada480478a8f679787a4f53c517e289ccdafaa.nq.gz
    ├── d4c32ca1794b4f4d7a414df89d74d70800bcb3ab.nq.gz
    ├── d504bbfc735d3ddc4de4ec26e64bf3287337683d.nq.gz
    ├── d651d6955eb27be90269bdbb394f9659f4af338e.nq.gz
    ├── d94ba7dc617e76d0508ad3c3b56d179cbb9d1799.nq.gz
    ├── d9a401005a9b60f9feef8fd7ad5c7ae8488e3ae0.nq.gz
    ├── d9a5f67c1649553fdb111732b51a9c00fc8a6c00.nq.gz
    ├── d9f467256ecac6b7867114d0e0d7850f935cd66c.nq.gz
    ├── da91a3ef16b0132bf5ea07445ecbe4c09cb0714f.nq.gz
    ├── dabd51d3869a8953ac7b73bf854b123655b5a860.nq.gz
    └── db57bb6b094c8d48acf7974936d4fcea132a0fb7.nq.gz

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

[allenai/SERA](https://github.com/allenai/SERA)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
