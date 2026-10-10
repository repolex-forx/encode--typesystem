# Repolex Knowledge Graph of encode/typesystem

RDF knowledge graph data for [encode/typesystem](https://github.com/encode/typesystem), parsed by [repolex](https://repolex.ai).

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
rlex download encode/typesystem
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7decd48f40de916edf18148a16516ad0a0483c4b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7decd48f40de916edf18148a16516ad0a0483c4b
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c016cd12a06e81812ba43f2a0a5b98f2fc99dc.nq.gz
│   ├── 08668dbd1ca3358288ba3263d22455b54491717c.nq.gz
│   ├── 0c1edb82b56e9233bbeebcb6028bbdc164c17b9e.nq.gz
│   ├── 0e0674592b02069f21879a41ca49866b33eb61cb.nq.gz
│   ├── 0fe00f21f3897afdd49005019dfcf9dff9dd4505.nq.gz
│   ├── 10b8059f2513cff7757db6765be11179c431ed22.nq.gz
│   ├── 13a6a113669f53da31e662bf31fa7408123b9263.nq.gz
│   ├── 17629779fbeabea738a101fba2b305990e096466.nq.gz
│   ├── 1b366f9bdc1407e1c0bf246ab14a3efc86d24da0.nq.gz
│   ├── 1bb4298ec547f5f6e84eb62d113e369296e10871.nq.gz
│   ├── 1c47d2cc2a5c9de1de2ceed00f1ae3819d579c4f.nq.gz
│   ├── 1d04a1675cab508877847c80c1286cbaa97c9db8.nq.gz
│   ├── 23ac668d2325b469c0051f82f3e93c9bfe41c495.nq.gz
│   ├── 25e7299731491bf95ab79d1cda9b332778c2ae1e.nq.gz
│   ├── 290cd981eacaf63b51fb2afcc12df1f1ae8f515e.nq.gz
│   ├── 2ad6e8e2700aa6665dcbfbd571c915ee2afe89c0.nq.gz
│   ├── 2d47d5a8b454deac28248335c26b34dcc9fab26e.nq.gz
│   ├── 30b52fd58581657ea7dafeccf7cbc5676e3df11f.nq.gz
│   ├── 35a72810ce3b1a69b7db80b7cc8443a0c3bd52ec.nq.gz
│   ├── 37a229c83f5cc49b8d5406db5d4114e87fda8f49.nq.gz
│   ├── 3b0fb49b8307c8ea5bb9588e1ea00f4ab8674fe8.nq.gz
│   ├── 3b3e3e6808ad6f53b9735113f307455934d31d5a.nq.gz
│   ├── 3b53a6b371a7b6b45ed28dd8eb352703bd58bd0b.nq.gz
│   ├── 3d0326681fe67b0ba0d1b150b267df84ac30c038.nq.gz
│   ├── 3f09158deef0a562dab603abda92e2a52806f357.nq.gz
│   ├── 40a06840d8696d90851e2c62eeaad5e64ce46a75.nq.gz
│   ├── 4611006e9b5ca5803ac0aec62a587a36fa06abb3.nq.gz
│   ├── 48c354207091d9e9406c3e40b63bb237f4530405.nq.gz
│   ├── 49a0726e01cee6d7a73d0eb270e87e9fdc658880.nq.gz
│   ├── 4ac3beb7a6248488589ae932e29b2d291ca1d55f.nq.gz
│   ├── 4d05a9e509eccc874e0d45092f063d2b688ec8d7.nq.gz
│   ├── 513731e4c8833fc804b94c065ce0041fb119251c.nq.gz
│   ├── 61293740df7057d27372f89bebd07b2b82614b35.nq.gz
│   ├── 65885a7208961207ed34c9659c21ac5ef0b90314.nq.gz
│   ├── 6d40f23f2622cc8accf0e1ed28e95f1f65365f22.nq.gz
│   ├── 70de9b5b1682f3249b59cd9efe6b004749d0b0f8.nq.gz
│   ├── 7165f4c36d4de3e71c5079b83b166f85ec1173ca.nq.gz
│   ├── 720a66392d6260c8535a6e5908f4c0d09412de79.nq.gz
│   ├── 72e3feca5242e6b66868a61e7ede905ec7016921.nq.gz
│   ├── 7605a7620cbd8a27785fab55f1b08ef1fc36a2b4.nq.gz
│   ├── 78ef8e9085dff1241d6de069b4b6670c294c1431.nq.gz
│   ├── 7be5ee5fa003302eb3245540807252cce7e0be25.nq.gz
│   ├── 7fbc61ff9be7321890b6e69ccb08994dc2dfb76c.nq.gz
│   ├── 80e552f73fc6cf180f2a5b914d28899c31fb0923.nq.gz
│   ├── 811d35b253c062fabc52a7ca2cf22946225e34a7.nq.gz
│   ├── 8150984ee573742702dad466dacbc2a66ba09443.nq.gz
│   ├── 8423690d9037df24fe6ea52600ce3034f598422f.nq.gz
│   ├── 848d0cec6c650b326954a225b58cceef7dcef560.nq.gz
│   ├── 87ee45e9793ae0a67fcb169d4950aa93e1615ed2.nq.gz
│   ├── 881e47ed6440722aaf12bf2c7b6161ee80e1bc4c.nq.gz
│   ├── 88df142fe5d8b403dd6e885ab2650c6f3383877b.nq.gz
│   ├── 8963b9f219aedbc1bfa78a0b4300764db95abe76.nq.gz
│   ├── 8d204dd6215d6d814513d98c0658ea32fe65f7bb.nq.gz
│   ├── 8fb9d7ad81827f54ae4a5628444f4a8a8195fa70.nq.gz
│   ├── 9338986661d6f3b7cb08a2eb45efeb1fabce28bd.nq.gz
│   ├── 96b00e36f85945ef4476d68a3533c62a10d560b9.nq.gz
│   ├── 97336f516109dc34c82eee2e7eb1652658c86c6c.nq.gz
│   ├── 97e3f0eea64258e37c02875a2b2b6f8606b794d9.nq.gz
│   ├── 98de0eda8dd0f25b914c0594b87b79ba5ee8516c.nq.gz
│   ├── 9c6d5dd9947e25ae8f313c055e51216212c14080.nq.gz
│   ├── a1c84647cc02054c4b50aadde6be108c649acef6.nq.gz
│   ├── a80cfec45a81d7456b4f5a01d69c8d508d88e921.nq.gz
│   ├── a899983d6b3ce134235364598ac431cda809c5a9.nq.gz
│   ├── abecc578be3cf1d92f15ca93e4fd13dcac77d811.nq.gz
│   ├── aef5065c70bca211c3e61845949984cfd8f04ddb.nq.gz
│   ├── b03135e6cdb620a2778e39f1e98a6305c21e1f0c.nq.gz
│   ├── b035816a86eb4d9a7a22986f3dba470a80016004.nq.gz
│   ├── b04217ef87d1ba1b4c66364a77f0988d851a61c2.nq.gz
│   ├── b290d6e1a8246a96c6c6740fef9453e77f4afb98.nq.gz
│   ├── b37e372ee2ab46444ddf491af3e56e9f19958dbc.nq.gz
│   ├── b38d7ecec63083a2429d60bd4c6dbc9e1c420725.nq.gz
│   ├── b7ae5a25fea53c5781884139f7ae4efb0508a4d4.nq.gz
│   ├── b7f9928af6c3ff564ea0cdad9fcad63d3c4dd20c.nq.gz
│   ├── b97ab32919f15efc4112289ef09e6d3e2777ae6c.nq.gz
│   ├── bc4295cab4f6b9a863de3b5695ba919a37ae0462.nq.gz
│   ├── bd1e95bc014dc571b71915a14568c83306cbf09c.nq.gz
│   ├── bd96907b9f703429e0cb66e2addaea7fc928e2ea.nq.gz
│   ├── c1adb6720a4fb65551e61ba63e22d69510d08c34.nq.gz
│   ├── c1f4ab99c9a485d4d8a9d9f97b4945899cbcd4b5.nq.gz
│   ├── c2336342e2cd67e9c3022ecaa4788bb909039e77.nq.gz
│   ├── c2d812af00fc93d58ec1d03c06b6a180d098c04b.nq.gz
│   ├── c8ad7197ff4c7fe6b1faa154289e262638c13568.nq.gz
│   ├── ca3b7618053f499c3f996e64ccd0efc4f15766a8.nq.gz
│   ├── ce775a2f5540d39d4b72e500c1b85e8c8a8b1a1c.nq.gz
│   ├── cf4e0ec1ea12cd14072c98f6054a26d4bd8f2b8b.nq.gz
│   ├── d4d46db24b26a4cc1330902b25e1e9e7208d8ca4.nq.gz
│   ├── dc3cd709d31dfa96cec7cba091b31c3c6cbfa4b0.nq.gz
│   ├── e2d15354deed7ac0173227446c495000de9a84e2.nq.gz
│   ├── e3071a81f305f5c359ea369af5d93189c0220eff.nq.gz
│   ├── e398602fabd637a27b81ee8774d582530f7af853.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e871360d1642bc3ac222718fa735b9daee6dd0fa.nq.gz
│   ├── e8c784808a3f33a53acd2336718992b2fe17aeb7.nq.gz
│   ├── e9677439bd49ab4e12030e85430e06e666519504.nq.gz
│   ├── ebc4b014da3ef4ce7dc76697a36da736251a3906.nq.gz
│   ├── ebfbacaab144055f252d40f633e70a9d5107f006.nq.gz
│   ├── ed5118815ee933dabd490e6de54d103e59100f08.nq.gz
│   ├── f127d66757365dbcf3f33eb96c848fa46b4e4c45.nq.gz
│   ├── f866514d44da17e423d4ec8d8610a902bbbed218.nq.gz
│   ├── fd1a4ee374d8c8e96b1508b3928befc1b4ff7d58.nq.gz
│   └── ffeac6b3814b15c6cab9c007f8ca31680fef5474.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7decd48f40de916edf18148a16516ad0a0483c4b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 109 files
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

[encode/typesystem](https://github.com/encode/typesystem)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
