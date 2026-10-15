# Repolex Knowledge Graph of scikit-hep/hist

RDF knowledge graph data for [scikit-hep/hist](https://github.com/scikit-hep/hist), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-hep/hist
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1151fee4d996fd4df8f4740b0d4dc60d2de90ba0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1151fee4d996fd4df8f4740b0d4dc60d2de90ba0
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a7b00c94e08b86c765d47689b6523148c46eec.nq.gz
│   ├── 0180349280530e0b5d8137c9c631040571dd124f.nq.gz
│   ├── 0288602772d3e2b3d87d0c453bfdf6079ee7ff78.nq.gz
│   ├── 030ab0196516fe7a773143408e6767f11156d150.nq.gz
│   ├── 0425bb464ba69874962ddc9568898a74dbf0d50b.nq.gz
│   ├── 084f59d408924bcd27ef478e58b3128d9885a2d8.nq.gz
│   ├── 08a378a5179c69f4d19508e4cc9562dbec10832b.nq.gz
│   ├── 09de1e9a373b7a16ca795b427bf044516961d4d8.nq.gz
│   ├── 0d465d2dbed2cfd3510311fa27095ba6a44292f9.nq.gz
│   ├── 0e349ca3dce45c9ff0a1b855c0075b757291580b.nq.gz
│   ├── 10c937a0dd91507345b8390ee013ec40cbfefe31.nq.gz
│   ├── 1432c5c64f238c1cbd53ad0e44d9543abdf3da4f.nq.gz
│   ├── 1607e5e9f4bd7703cec2bb87824b6d459a46fcdc.nq.gz
│   ├── 19872be06dca5d301e4c3862b587a085189665d3.nq.gz
│   ├── 1a09bf4b80046a1b8361e2c0a5d46bb3adc66867.nq.gz
│   ├── 1b770eb2ebfccf652b541ecf702e8e2893c065f0.nq.gz
│   ├── 1e15e8dde2284b9227fac7f4c6dc4117e827d199.nq.gz
│   ├── 1f96f8c06d2a2ac38fd0190efce5ad6cdb35d41c.nq.gz
│   ├── 2169e4ca13c8ceec2372660b34b6a35cc95db4ec.nq.gz
│   ├── 2420c3124c1061bc939c033ac40708e762041ebb.nq.gz
│   ├── 270982e8207d84cfabbe198a7df3326101701fc6.nq.gz
│   ├── 27dcb346a9ecda83defb4422b58bdd2f004db3fd.nq.gz
│   ├── 27e2d6b0f9cfb6ccc0708187b0bedbef59639751.nq.gz
│   ├── 29b599ac15e9bee33853c0ab924085e15c251000.nq.gz
│   ├── 2b93d8f2a383c6771a3c119754d306dd9f9b3f48.nq.gz
│   ├── 2bb47de1868be2ea4f3a149489221180f9e2132b.nq.gz
│   ├── 2bff6ae5a2473b29e77c9bfde92b946f89ec989b.nq.gz
│   ├── 2c0764f4deaefa281b0316aeff4b3c9b98693531.nq.gz
│   ├── 2ddfac96745b6503fa418b88b39cd4a3911e2262.nq.gz
│   ├── 33207b6f11357fe04026a19edcec28bb2a9c01b0.nq.gz
│   ├── 34647df4b2b6e111bd75bf6024927037c70a394a.nq.gz
│   ├── 360220872f7498a77ae5f98711ea4987eedc7c03.nq.gz
│   ├── 37afdbe4645532ac6ecac28a623497e0aaf42d57.nq.gz
│   ├── 3c1f4280ebbb6cd0e795725f7d9cadcdcafc7ec8.nq.gz
│   ├── 3cd07fdcf2ee0f59ed13ccba081a82c02ea39e7b.nq.gz
│   ├── 40bdf7e363eed505f409a4be08527f72c65ec8c9.nq.gz
│   ├── 411b3f1c4e2bb02705664aa98a2f3aeaa98eef1f.nq.gz
│   ├── 4272e392857b5a91d67d83959ae1a930b103bd5e.nq.gz
│   ├── 475bdf575a81209736ed8d75456f9fbbeb66c82e.nq.gz
│   ├── 487c970e1519a4844536a05d92bb393759c940cf.nq.gz
│   ├── 49fb4b05926ba39da735021fb1abd38cf26a513c.nq.gz
│   ├── 4bff9ac2744d35546eda97c9fe18f6f09915f88e.nq.gz
│   ├── 4d3eb18e2748aa13968a58c51ec6462349d38d12.nq.gz
│   ├── 4f67de1e8727ba9b574fa395dc0065326b9611f6.nq.gz
│   ├── 507a136620d408e65f7a28f9c4251a74dc58b959.nq.gz
│   ├── 536ff242c272c2f61014af15862b35de69cf7172.nq.gz
│   ├── 54c0aed10ddb2238ab0ef0de9b0066363face8fd.nq.gz
│   ├── 55e2da2a5937e9534d2752a8afb20d3d1a11ab4a.nq.gz
│   ├── 598acbedc28b2a1f48a310d2b20d968ea60c4009.nq.gz
│   ├── 5a472242462708916894ab566032d434b340f791.nq.gz
│   ├── 5bb2b22f78faec68eeed9a623c15cad2747c9eba.nq.gz
│   ├── 5c5cb9b4dc01de6b06f3d0e08219a38e21f5822a.nq.gz
│   ├── 5eff8d4a2bedde7b7b1b7bdd66e9742586b74cf9.nq.gz
│   ├── 5f475bca5b1539b33cfeecf5ca74f7b8c870984f.nq.gz
│   ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
│   ├── 6055ed81daa5f9d6ab7d18dfec1da3125a2d202c.nq.gz
│   ├── 6069ceee5d7606c6058fa82b08fa11f09406bf7b.nq.gz
│   ├── 60fc1b799aeca61fc9371b641690c2751ccc378b.nq.gz
│   ├── 617496e154b2ebd3beb8092b8343e46db5bd12d5.nq.gz
│   ├── 65b830b9d40c12e93613c86f725ed7b957c9c4e5.nq.gz
│   ├── 665dcbb83dca175d4a110df33623bd8c5bd10410.nq.gz
│   ├── 6b23436cc5cb6a6bb833c4e8bcb9145d77ae8a5b.nq.gz
│   ├── 6bba5e6021fdaa9fcfca46b2d8638cf032909c6a.nq.gz
│   ├── 6c18a68dee3be249e5e9ea6bd2837fd16cf3791b.nq.gz
│   ├── 6c94189ad571b48ef7f08dfeee92a23121303669.nq.gz
│   ├── 6cb882ee46e30dc5c1fbc1f7b35f4665b831b5f8.nq.gz
│   ├── 6d2745df67ff8149383e4e46dc449419891a21cd.nq.gz
│   ├── 6ee1acf77a82377b424c2f8b42e99f3ac5f36e51.nq.gz
│   ├── 71ef7cd4fa21ad38922e74f9d7a50308ef060c2b.nq.gz
│   ├── 7212c54eaf5ba8660a112cbd59390d0cd52950e2.nq.gz
│   ├── 722812a5c953929371e1963ae77425b5bf866014.nq.gz
│   ├── 72c30570b5df8f25a3bbe39f2f7aca64a826d635.nq.gz
│   ├── 757ffe3cd5cf910923674410b5321e1f43a78208.nq.gz
│   ├── 761d8005465870fa4db9b790a90f4feadc04b46f.nq.gz
│   ├── 774182cbc2e103b2134f46cdc0635d1e0b3d851c.nq.gz
│   ├── 779e80250b5f5e2341a2ff6901c8efdc974be29b.nq.gz
│   ├── 794ebfdeef3048c4345b9d7f05de0fb98d7707e8.nq.gz
│   ├── 797795a3c23cfb04458bbb7e4020e726caeeec13.nq.gz
│   ├── 7b06ea19caa07ebf623490751e01ce19dd9c6895.nq.gz
│   ├── 7c0032ed731797c498bf1d01abbc37d3fa399cb9.nq.gz
│   ├── 7c0c529f577b2ebf2bec03e85e8b0c52e1f44a92.nq.gz
│   ├── 7dff7895e5c14505fd2e80ffb8f6d6b6671a5e41.nq.gz
│   ├── 7f354e2b838746ad533bea5e007a83fc372785f5.nq.gz
│   ├── 83920de79cb746293f3aa7f1badcfb7d366dac74.nq.gz
│   ├── 87e6bee6ca87f10ca8315925d7de715781db6bba.nq.gz
│   ├── 893bed7200ac9f7d7b5f886b9fe2f3db1ede1d6d.nq.gz
│   ├── 8949a043cb13c1b89b51df14f3235301973e4d52.nq.gz
│   ├── 8b13673c14657c63f5a23c7b514f9fca0725174f.nq.gz
│   ├── 8cba65c069c10bca6b0e61c71acaae66039662ef.nq.gz
│   ├── 8f82c00f1b525b51fd132f7078a1f1dbde966779.nq.gz
│   ├── 8fb235d7045be0330d94bcb3abd2ac43badaa197.nq.gz
│   ├── 90eef97abafa211971c366883e3ec162d4bc18c3.nq.gz
│   ├── 916e0119d72d8f307b1a29ec2c242705f4cc6043.nq.gz
│   ├── 99703659fcaf298bc2de90d7bb532029e80d3100.nq.gz
│   ├── 9c70573d363b345291f0e166f8cfbd4aac0cbce8.nq.gz
│   ├── 9f621efbb483a24e3f18bb357c1fad980c1dece4.nq.gz
│   ├── a08a079f2b8333705fe29ce17dfcf96d7c60de49.nq.gz
│   ├── a187b4de392476d5ff89c6de51ce4e942a140293.nq.gz
│   ├── a36c339f8953e0210e6de0cefcdba33c74680629.nq.gz
│   ├── a556c49ae6967d20921975ca0709ec0bbddc107f.nq.gz
│   ├── a5ff07e4dc0b74c42e37afb256c740989e942513.nq.gz
│   ├── a866db483bafeb05a3e682828e36a23eae2554f5.nq.gz
│   ├── a9dee8b0babb6367b08556ce1fbc36c5240577fa.nq.gz
│   ├── aaf198403091c194fa0e1eda9e10a1398257b0da.nq.gz
│   ├── ab06cee62c54fc0a77145aed4ed54d0371fdd730.nq.gz
│   ├── ac258e1d8271c8af7532ce769165906ce795b0a8.nq.gz
│   ├── ac4148bd8482da6df3bc36e02a68b47f1afec28d.nq.gz
│   ├── b0a4e764886defcacaf121c7f617af643aae3bcc.nq.gz
│   ├── b6fd9cff22ae33942db54082f22a8681d788732b.nq.gz
│   ├── b81c15a7c4de3ca8aa7dc8799dccdac3981a60da.nq.gz
│   ├── bb158448249228c6a96cf84070ad01cbfe346c64.nq.gz
│   ├── bd22b9018bcc079fc739a5ebeb3ccdf1559eea1e.nq.gz
│   ├── bfa09c9cd5f9cce49c0bab2abe8de381c0d553e3.nq.gz
│   ├── c0a0231385d854f549ddd7d54dfa80049cd0e693.nq.gz
│   ├── c22ba86bca8fb57dab4f238aefd3d9e49e33469d.nq.gz
│   ├── c34d3e4968f2184adca907ec2f57ff0e9f92c49a.nq.gz
│   ├── c3919452a9bc8bc5a01278f3791437b31ab40fe0.nq.gz
│   ├── c419706dc21bbd2a8bd41cd1e70027fa5780561c.nq.gz
│   ├── c4b08074714f1ccc2ac3132b826073eb31608e40.nq.gz
│   ├── c67351b83e6bef6fbf74f8b43d4db1c67af60893.nq.gz
│   ├── c955fabaa742dd15dc94350dc06f8c12c1e5b09e.nq.gz
│   ├── cb3e3f3eaaaa226dcf7b5d064d10bd4c135427bc.nq.gz
│   ├── cb749810a10683f84bf0bd3e7ee68f7983242c7c.nq.gz
│   ├── cbeb47192906baa3235927b3e7210c9e9ad5beff.nq.gz
│   ├── ce621c752e66ef515a8e266afa725ff1b1771965.nq.gz
│   ├── d039baed88e164ddea8b86503abd797af61ed099.nq.gz
│   ├── d1df54c77fb8be47c551c7b1ae9655ae352010c4.nq.gz
│   ├── d78ed0cc783f22e101fd3761e075cbd46276d113.nq.gz
│   ├── da207769a619ba8a386f833732097f261be34a7a.nq.gz
│   ├── dd531b90687c9aa0e1fa122a6f0ba0b39ba23f58.nq.gz
│   ├── dda4619d56aab426403aedd8f483d7b3a6e64f37.nq.gz
│   ├── e05cbc61b5044df61be06a862ab86b67ffce598d.nq.gz
│   ├── e1171aa26b312e8890863c25a549a1b42b413af1.nq.gz
│   ├── e2d624cb040e8da54f612fc99b61ed5d1030eb5b.nq.gz
│   ├── e52e16d2361b93500f4cc07397b0eeb8f4074828.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e73ef2625cd7064df10a99cc679f104205642af5.nq.gz
│   ├── e811e3a2b756e62f33c6f02523ba0b6286c3a7fd.nq.gz
│   ├── e8e6e8a65a1b635682154a73659cd75c73d1fffc.nq.gz
│   ├── e92533ec796ea783a55731d9b99d0378e58e8214.nq.gz
│   ├── e9832b9d217b548fd1759e3579e2e13069957158.nq.gz
│   ├── ea1e38a6c0108f6c651b028209153ab40ae814fd.nq.gz
│   ├── ecf5e8708befb4f97ed368abb167aa4f26f17f7f.nq.gz
│   ├── ed88099027f775942fa65dce2314f1ae9675cb36.nq.gz
│   ├── eef0aa765c112331f1b07f01cf8f685f7160e36a.nq.gz
│   ├── f45933704ab2b02f646c961a79d29f080fb43462.nq.gz
│   ├── f6f68828de4e54ee15e9cf43d2caa2f7da260a51.nq.gz
│   ├── f715c87e0552dea572459b6c28972add3bac73fd.nq.gz
│   ├── f767a04ac271fd3ae562fef9e6d71b58f55ad4b3.nq.gz
│   ├── f912752c7155ac5d7e45ca86a053387ada5898d9.nq.gz
│   └── fad1df15cc42207a940c71d08a121ad889d25b6c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1151fee4d996fd4df8f4740b0d4dc60d2de90ba0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 159 files
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

[scikit-hep/hist](https://github.com/scikit-hep/hist)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
