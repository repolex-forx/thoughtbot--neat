# Repolex Knowledge Graph of thoughtbot/neat

RDF knowledge graph data for [thoughtbot/neat](https://github.com/thoughtbot/neat), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download thoughtbot/neat
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 101eac6ca5951fcb15620dda7d7807283f1a92ae
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 101eac6ca5951fcb15620dda7d7807283f1a92ae.nq.gz
│   └── repolex
│       └── 101eac6ca5951fcb15620dda7d7807283f1a92ae
│           └── chunk-001.nq.gz
├── blob
│   ├── 01a99f96afd658b39eda86dfa5580c3086fd5773.nq.gz
│   ├── 05caec2fd0c3d5903008d1590594b099abc21d0d.nq.gz
│   ├── 05fd49d152d1048428a3f6677b8959a3bfee44af.nq.gz
│   ├── 07d492b21427a33b2e9ed471b4ff41eb4884332a.nq.gz
│   ├── 08dae1a00a523414e297db5e272d532091c1d550.nq.gz
│   ├── 0a0c3def90b7754636f9c5c99d4db780551592e0.nq.gz
│   ├── 0fbb9aced7b6a6cbb81608025ac465a64f218c92.nq.gz
│   ├── 1237a923fb1d9986751dd57de0bad7738339baf1.nq.gz
│   ├── 1557ec3525a6fa7e2640355de3879d0e0a7439f2.nq.gz
│   ├── 15ab422dc44aafb214ad340749fc607cb8d477f1.nq.gz
│   ├── 198a9e3220c5a1f60e859af8dbe2c88e8af624af.nq.gz
│   ├── 1a4516e3e62f40977f03b597fdcb4f580afd4140.nq.gz
│   ├── 1d5549a4a7066633b5b15dc62f5712b6c4faef44.nq.gz
│   ├── 1f920cad9afeba40c17a16950cef7ae2208e7801.nq.gz
│   ├── 207e32b1873ef3f1f327e05b3c2a557d75a0b342.nq.gz
│   ├── 20cde7938cb28731b278355c1623c894e730b92f.nq.gz
│   ├── 21da1e2fad2ea28e75efd46c6d86e6367c49d11f.nq.gz
│   ├── 23ca4599d9142fbf3b44c2c6cbfac0cfd8ba1e08.nq.gz
│   ├── 2598d49b87a8a6e28e59e0e127cb7cfc6aef65f0.nq.gz
│   ├── 2dca0eea12fab9c61a4514a4431c2b39bf3931d2.nq.gz
│   ├── 36050711d8adb7df75e12a024017935f8ba5547e.nq.gz
│   ├── 366249aa3167a37e6cb12972276d822ef4eaec70.nq.gz
│   ├── 37b3d06376fc835a854a4ef7b574828eb76a7015.nq.gz
│   ├── 3d1a7a3433863819fd76c3facd94644af615a225.nq.gz
│   ├── 41589af3f999dd1fa44fef7f5c81cbcc3a1ef3de.nq.gz
│   ├── 42e170789bf775bde40b8e643f490a7b58f10c59.nq.gz
│   ├── 42e52102da66a4b30587fec39210ffb64087a3fb.nq.gz
│   ├── 43d8a9bfdafe732dc8f0c158c237164e72057b02.nq.gz
│   ├── 45b63abf5ebb69c50888f35d995d7b012b2de61a.nq.gz
│   ├── 4aafd8eed510c3b76e5e78c454e2d57deba7ab9b.nq.gz
│   ├── 4d687d3d8f3f1d03989640eb09ae7d1313dae24c.nq.gz
│   ├── 4d76c0ab58feb1daa4404c2afd358aa97b82c3df.nq.gz
│   ├── 4db86c26547765b119ae5240de217cc97d8dd379.nq.gz
│   ├── 500787caa475e5da4c76e28c5e36ad821ccbacf5.nq.gz
│   ├── 5409711ff51b7dd741ecd935ddcf79ee1b8ac572.nq.gz
│   ├── 558d251badf2940a20dedf3ed0d9569cccaefea8.nq.gz
│   ├── 560d5f43b8e62bd57a493c5965aa218f19d50215.nq.gz
│   ├── 56bdcffb5f296a1efba171f92b378332ebe83aaa.nq.gz
│   ├── 5a24699fbe443edcdfc023cc38089db54e4b4ee4.nq.gz
│   ├── 5b084f21c6055c6e8ee6e4cd4be7e40ae72e6b07.nq.gz
│   ├── 5eaf338963525074022633b0cf16869f1b91ed94.nq.gz
│   ├── 6443bccc518fe02cadae9bf7edc1567edda7dbc6.nq.gz
│   ├── 7439d37c74dbce746499d3dec2298c5ddcf2084a.nq.gz
│   ├── 758f7e0243382b7b7aeab84c80a4c8a7530cefcd.nq.gz
│   ├── 75e96ff9bb2a65f6c90dafc2e659fb9bf0d88dee.nq.gz
│   ├── 7debcf8678e187b8525f443cc5bc712e8257f2ee.nq.gz
│   ├── 809b9d00b131fb58cacfe73a4443f41d224b1324.nq.gz
│   ├── 81372b19d1530b9ccb2d62b95f6d2738ad4495ee.nq.gz
│   ├── 819e4bf08a55dcbb3bdec8dcbb6d8957b82f1126.nq.gz
│   ├── 856f47acc10cce18de90b029207b513bdebdb0fb.nq.gz
│   ├── 8b73ac394a0778ae6a34d55884964ad143917d8e.nq.gz
│   ├── 8e016f57dfdace66c89ccb212b636991af3b145d.nq.gz
│   ├── 93e14264e3383e680c1fd99a87139b185c6cb9f1.nq.gz
│   ├── 950a205f0c63bd176311cd46ec95c05631a47e4f.nq.gz
│   ├── 971f06fc360b61c4cd709b745dea375380f4a3e5.nq.gz
│   ├── 994a9bc84b6c01a2a1d28b537ef75f52029cde5f.nq.gz
│   ├── 9bc4af4e5b6bf20f89be6241b3f6dd71da37dc9c.nq.gz
│   ├── 9eab54957434c87b5ef4b438bf474dd244239da9.nq.gz
│   ├── a34a39b95039503102b09c990cd498275122e87e.nq.gz
│   ├── a4ac2a8e70a6a1a4e88af815ac0209292345b0be.nq.gz
│   ├── a51e657f328e91baf307a98f47c53b0034f3f660.nq.gz
│   ├── b36a65bef0e79c257d500c503ca33dd22808b3e4.nq.gz
│   ├── b4e2a20bb6069d33479542fc863e7e36810e0f01.nq.gz
│   ├── bdd9858c49119a6663531818c3d7f39b70041d84.nq.gz
│   ├── c0c6e895918316dc892971faead439d5174504ed.nq.gz
│   ├── c22188232204725b19eea1766f4d6c7c0eadaac3.nq.gz
│   ├── c4828fa32245e14887f623c7f8fde86dee017268.nq.gz
│   ├── c6fcdb64d28b04b050e3698354424b5976671741.nq.gz
│   ├── c91517cca666b03e70c0d7481a0c3b2c5903d21f.nq.gz
│   ├── ca610b15472fdf20f93011f973bec6967a3a47ca.nq.gz
│   ├── cc0e1a1a328f8c0bb9312a677f8b4ea385d5b8ba.nq.gz
│   ├── d2a9cfe83b940572a1b2e536864b8fcf82f50ec1.nq.gz
│   ├── d7f9d46f8933851ae214a7d146a1644ecb012a0f.nq.gz
│   ├── dcf0509fe7ae9a803119b6530695f7cf85285d0f.nq.gz
│   ├── dffba5598f517b86f4350b4347f676c7c98fd797.nq.gz
│   ├── e1398b1ce269500fc0046ce4510fedcf892d62c9.nq.gz
│   ├── e1db68d83f3298c17cd0b79bb662efa0747bcd6c.nq.gz
│   ├── e20cd652314880b9cad27e6b2a49241c6e08ca2f.nq.gz
│   ├── e2a6fdce0cf64e45e3e5ec280e4ee2724da928e2.nq.gz
│   ├── e35b76576765d44eb8a6d7f35a8c515ecc25827f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e86119558945c2e42e4bc7a125c48c6a72f1ceaf.nq.gz
│   ├── e903e7a10ba64e63764c9e2abaf589e3baf671ea.nq.gz
│   ├── e9cc1b97486d1a9a8d77951bf08bee743135385a.nq.gz
│   ├── eb8b8f12e8c80e00501433420831cdbfcd2090fd.nq.gz
│   ├── ec88ceec7b2fb4892b116b19b62bff051c6134b7.nq.gz
│   ├── eee68fa18a75eef6b0557360ee026452b905cd4a.nq.gz
│   ├── f202f34ab24d8dd5a047313cc751a81b7d7b9872.nq.gz
│   ├── f27419a77549501b5dc9316582d74965ac0c5dbf.nq.gz
│   └── fbed5955bf682bd2f0b08134d5a75d2050b08983.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 101eac6ca5951fcb15620dda7d7807283f1a92ae.nq.gz
├── filetree
│   └── 101eac6ca5951fcb15620dda7d7807283f1a92ae.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 100 files
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

## Source repository

[thoughtbot/neat](https://github.com/thoughtbot/neat)

---
*Parsed on 2026-04-18 by [repolex](https://repolex.ai)*
