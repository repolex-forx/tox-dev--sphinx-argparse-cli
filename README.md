# Repolex Knowledge Graph of tox-dev/sphinx-argparse-cli

RDF knowledge graph data for [tox-dev/sphinx-argparse-cli](https://github.com/tox-dev/sphinx-argparse-cli), parsed by [repolex](https://repolex.ai).

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
rlex download tox-dev/sphinx-argparse-cli
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dbdc5c366d69a8cad5ffbb6f59cb22993599dd85
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dbdc5c366d69a8cad5ffbb6f59cb22993599dd85
│           └── chunk-001.nq.gz
├── blob
│   ├── 006e2998c8187b3ea9d043db9f03eb3603b919a3.nq.gz
│   ├── 02c1047d3d9e2a754fadb869f5fedbf81919f545.nq.gz
│   ├── 062bd759874188461dea5892230427c8560bb3b2.nq.gz
│   ├── 0f8f205e502674c1a6678b08093dbc4b93832243.nq.gz
│   ├── 1088584dde79d10bbf08360725e78dfe46750977.nq.gz
│   ├── 113d43abd6b15ade7fe2cf36edc035b55ba9e5b1.nq.gz
│   ├── 146350acd7b6b7271c4571fdd272df62da9fdbe7.nq.gz
│   ├── 170b1af0698ab9cb1a414594b6279833408fb9ee.nq.gz
│   ├── 19cfc5d74477928f51954acf8543fc6fb67a953f.nq.gz
│   ├── 1c481197d27e1e9640160843094c7fb2053e0453.nq.gz
│   ├── 2463495f8dc256f0a8e907713b43e18e6d117a65.nq.gz
│   ├── 267eaab0147a24207d2efe59cefb25db1bc288f1.nq.gz
│   ├── 26dc946b27483638c9c0646c689d8f185dfb7bba.nq.gz
│   ├── 272360ac92f6a6dea2d45d675de97f590a43678e.nq.gz
│   ├── 2c1ceb3ae0910893fa21268ff73cd550abb3900b.nq.gz
│   ├── 2f8e14ca753c0abac7660464ea946df2dab68e1b.nq.gz
│   ├── 2faaaa9f664f72d6a14fc76fb5872aa505bd452f.nq.gz
│   ├── 3097bdb9f1ee7a6c3cf8a39583d7cac792b4ce42.nq.gz
│   ├── 3227deb0168ce78ec9d0ab1426fe2d8bbf8ed0e9.nq.gz
│   ├── 35c55fc1691961fb3b569d86c815072c8de866e5.nq.gz
│   ├── 364982344fbd94d55705e1f27a9a87abaa255333.nq.gz
│   ├── 36d2fb8249e4c97be2f2bf87c3166c42826140dc.nq.gz
│   ├── 37d19b55bcd49d6089dec2a60eecee95879fd105.nq.gz
│   ├── 44eb40003ee355297a8cc429ac032dfe3b987c8d.nq.gz
│   ├── 453472320ad32b280746995bc428b5ff252478c3.nq.gz
│   ├── 50068d24fbcdef03fef9f46bfd78ab077883957a.nq.gz
│   ├── 51a0b159aa4ea7d0ec08b9b94dd8081d123073bc.nq.gz
│   ├── 53c2bc8daa0f9fc9d895dcaf30ab933c55ad8e5d.nq.gz
│   ├── 56bfdab7caee9510d7e23fc1bf5ecfb6c3737a3a.nq.gz
│   ├── 5744ef7258eee5cac974731f64144b261de6068c.nq.gz
│   ├── 576679d5ddffe61bbd61417fed94dd184ba6ec46.nq.gz
│   ├── 57c03b809dc44825a28eab940d9a04e9260caeca.nq.gz
│   ├── 59d91456d56fe7c0628932ce20e386df99680f63.nq.gz
│   ├── 59fa1bc01294b70afb798c61c67c1deae4b1d8c6.nq.gz
│   ├── 5a80656dc80ac7d78061b6c313a78a44e0a5d9c9.nq.gz
│   ├── 5b875dfb51b86c33de44062146b383a0af984dfc.nq.gz
│   ├── 5e0c26a5c0031ed1fdc52a25088a7e4c5730908b.nq.gz
│   ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
│   ├── 61823dcd26ac5ae8f27e98bcbc159a268dd21d8f.nq.gz
│   ├── 6219a3adbffb676d0ce185df3d7d8e554bb9b649.nq.gz
│   ├── 629a9011bbe15fa5d1e72b92b008ed5d3e73ed70.nq.gz
│   ├── 6582a914277074f0a7797617ca9e0b12881234ae.nq.gz
│   ├── 6613b23c1cc82a447036c9d65b24689b7011dcde.nq.gz
│   ├── 69d0cfd202c019ca1d5a92d59faf9a1380c61930.nq.gz
│   ├── 6a69bac6d190a01436756494ab1976c68886ef85.nq.gz
│   ├── 6cc8cf41552753ad1b9dd36af2f701e64102c3ef.nq.gz
│   ├── 708ad9ce026a66b83f595aec8ba77a96cac36c50.nq.gz
│   ├── 7144381901a1534c22ea772430b5fd9ad24e2405.nq.gz
│   ├── 74621bd741929ff2df5ab635722acaf333f3b8de.nq.gz
│   ├── 76d3e997553824e0c5983f6a2a61270524bd5441.nq.gz
│   ├── 77c44006637e9ce9ce43696f62db5ded672436e6.nq.gz
│   ├── 7b03f89ec091fffa37121d6ade103663848d3dd8.nq.gz
│   ├── 7ce6abd4ee80e155a775f8f36a3a05a49f18ef52.nq.gz
│   ├── 7ddfafce45836b5b229b745f619448c4bab9d68d.nq.gz
│   ├── 8895db4caa077d05288d7e3e9e87d0b0a9b21d4c.nq.gz
│   ├── 88dc1aa9244f1d0ac08fdaed721bcb5e6ac0ec17.nq.gz
│   ├── 89758b4cc2c38259462470b802e6d60d3375feb0.nq.gz
│   ├── 8bbad68a781f7c8d26ea491466388c6fe5abf1d6.nq.gz
│   ├── 8fefd09679770bbe4588e1b535f8b53837842214.nq.gz
│   ├── 91c54e7528d76d5f7ac7388f84c7df5dbce57d32.nq.gz
│   ├── 94e2186859c469f66d3430725ea66ae697094c55.nq.gz
│   ├── 9624f4bc76379c6bef722d0d9ed5b0eac8f1ad16.nq.gz
│   ├── 98ba589ad07d8c1e5770541e618acc9c33c5fc81.nq.gz
│   ├── 9f2a54a87679679d15d3a1f5f880ecf3bb30868a.nq.gz
│   ├── a274fea687a243c2c484252ce57879601acfeca8.nq.gz
│   ├── a38a9551687d09361c0ea21bf1de0dfd1bdca23a.nq.gz
│   ├── a495f5c45c9d1d4af119f1ba10c2237ff24f2c89.nq.gz
│   ├── a4cbed311fb57ca446cc0c29e5c965168423c1a3.nq.gz
│   ├── a63e3071d99db073e942f5063cc189b635edc9ac.nq.gz
│   ├── a7e1ec906839ae08ebb0691a4ab3196e71ea200a.nq.gz
│   ├── afb571644d8223240faf97b8bff00bdeda5ed584.nq.gz
│   ├── bfd24dd91890e7c8cec650fc6908ab06a5af203f.nq.gz
│   ├── c0fd26bfab64fab7b16f5ee8f66f2eadc728809d.nq.gz
│   ├── c204a1e133171fad2efd5546d9cc4602d8bc6634.nq.gz
│   ├── c2288cb7448f1124eaa14671906daac500c19d70.nq.gz
│   ├── c2db0ad386e49ca50f78429bafb1a269dae58d9d.nq.gz
│   ├── c374c651de837917ea3cc4f8a0aa15b2730ef25a.nq.gz
│   ├── c91a6cb0aeb963792f9ec361f58f620a98074e24.nq.gz
│   ├── d302fd2bb355928cc98e425c8e15c90120f87121.nq.gz
│   ├── db553b55754c630e552b4b225501ec86b5e89347.nq.gz
│   ├── dba29230f7997dcbefed78976138fcbe51aa16fc.nq.gz
│   ├── e0fbafa23d78f14e8af17ee91aa3340d53746d8c.nq.gz
│   ├── e2d0f6b28f8605dd8b32c0e336704914266cdaa4.nq.gz
│   ├── e42dde9c45e2c69e018e2fb9af18497833828602.nq.gz
│   ├── e508d3b6a5c930dc933166d8df41ba493b5dbf1e.nq.gz
│   ├── e6676139865b07becaff1b3502f68ed2a655b8e3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e70628b91297eecb29cdd8c972206931c50ee839.nq.gz
│   ├── e76cc6e45b6ed92c592a43e796e38d2da154930e.nq.gz
│   ├── e7a74169eba02ef67622dbb208f17e8c71fb48fc.nq.gz
│   ├── e9f26823be967b9305ef796755ea6a47017c8e2b.nq.gz
│   ├── ed089074b853227844be3e7f453bd3ed1488fb5a.nq.gz
│   ├── ed82427433c53b6ec452a8ae85a70cd1a20a5d9d.nq.gz
│   ├── f08a091c8f9ae7cea47a2253d6616e20b60d1baf.nq.gz
│   ├── f568d81d93fdae7e842b284892d3dc1607e30fb9.nq.gz
│   ├── f58562fa394fb4a00f8177e9d48050f16f170998.nq.gz
│   ├── fa7108196f20ec15eae76318d7b3cc121b8a6b9a.nq.gz
│   └── fa935b0329d063c4227d2a6ddd1d8e92bf64a2e6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dbdc5c366d69a8cad5ffbb6f59cb22993599dd85.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 106 files
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

[tox-dev/sphinx-argparse-cli](https://github.com/tox-dev/sphinx-argparse-cli)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
