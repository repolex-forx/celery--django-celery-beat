# Repolex Knowledge Graph of celery/django-celery-beat

RDF knowledge graph data for [celery/django-celery-beat](https://github.com/celery/django-celery-beat), parsed by [repolex](https://repolex.ai).

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
rlex download celery/django-celery-beat
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dfe16f2edc4108fef9308dd9571f590b7febe313
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dfe16f2edc4108fef9308dd9571f590b7febe313
│           └── chunk-001.nq.gz
├── blob
│   ├── 01850ea00cf3d1fc03b1bf02b933de6b064f1dd8.nq.gz
│   ├── 0990f91dfe5e5a9c2fc586e50448e36bd944c86d.nq.gz
│   ├── 0a1cbfcd3036e816246e94f34534e879c1958d0b.nq.gz
│   ├── 0a8d3da39da77ba53c53b7670594db00a1b1ffa9.nq.gz
│   ├── 0d28da61848d7f4ede9994f05c7866ac7b01b47b.nq.gz
│   ├── 0ea18774df4d69ecf8178d90bb513989f38c1f3e.nq.gz
│   ├── 0ee02ddc3ed7e9fc425281a73cf42bee704e4f91.nq.gz
│   ├── 0f56f52ed9e965af0d91102a6d15b9404e77f173.nq.gz
│   ├── 0faa3b3b246253f8887c4fd187f081b3abd28fe2.nq.gz
│   ├── 1174611a6d51c64b78c507e6a97a5109ec09bc78.nq.gz
│   ├── 15e8a2edf037da7593c1aec526406aade7f16665.nq.gz
│   ├── 17d6c868ea943c45c076b6a64d9132b8b6574399.nq.gz
│   ├── 17e084d4acb47ab046b364eb0220992f82533d0a.nq.gz
│   ├── 1ba9a0475e1abc0e3dfb8ba8d48ee4250882495d.nq.gz
│   ├── 1dac9169796b4ed0f617a83cfdc3494dfe895530.nq.gz
│   ├── 1dbb5f8d728c9af0d8d9a950a86dafc4980b759f.nq.gz
│   ├── 22fb1f902a9f8dced0c3180ed0187471396cbf8b.nq.gz
│   ├── 282787992ff17252b3498ceb46394b70ee5d9686.nq.gz
│   ├── 2983da2364a26b1ec208781afee4b1a8f48c8bf1.nq.gz
│   ├── 2c44d56ffe60d42253e2decba7f7d4b09110089f.nq.gz
│   ├── 327e97e5ecbd944112b82873bcc59dbd0b0d02b0.nq.gz
│   ├── 3427ba51e3644d31a996fd33f39933080e3a63a7.nq.gz
│   ├── 360c0515b3f18c94aec7b062014bd9e320ccda9c.nq.gz
│   ├── 36319198aca710d440ed292ff3be3667ad9d59ce.nq.gz
│   ├── 36881068d35ef0f00f766a2a9eebc9677cbde6c7.nq.gz
│   ├── 36d4d8e5cfd114b69a8279b7a35328fbab0c46e2.nq.gz
│   ├── 37cf5af59fe564a212aebd89acfd3309c29ea350.nq.gz
│   ├── 3c8ae4dda8b0e645a9ad42d060ace61c974ff249.nq.gz
│   ├── 3deb4a9d56bbc18bad87817188f0d46904130758.nq.gz
│   ├── 3f9ea1470bf190848e2ce1825d4f28a208be2ed2.nq.gz
│   ├── 40767e1b552666a25e78da34ab3557e5a0c928ab.nq.gz
│   ├── 409e9d8cf771995a0aaaa6fbe3bf325bebcbcab4.nq.gz
│   ├── 436ee6b5051faaea678de01134f95d0a6802382d.nq.gz
│   ├── 466eb3f0dcead6b0bd7cede4b1d62693845be0e8.nq.gz
│   ├── 4c031008d6da3a03813b93b24f9050e3f7decc78.nq.gz
│   ├── 4c7c664fc70dc30af5b1eeb06a9c22f16356d096.nq.gz
│   ├── 4e234c122c8ea97b1805fbf0c4ea58593628c371.nq.gz
│   ├── 52139a8db0ce7686f987352a21b0ad48068d859b.nq.gz
│   ├── 57aafdaa53e1b585275a0e085a225282601e9a99.nq.gz
│   ├── 597c46eb6da1598e95f1ec6c3d996e6b8f272107.nq.gz
│   ├── 5991cef4548a190a8ef7467079bee7e991fa9a2b.nq.gz
│   ├── 5b20da335b1980be7deed652749d4959d650f59b.nq.gz
│   ├── 626e6d586d0edfde0fdb54bd97a21305b25365a2.nq.gz
│   ├── 642cc610bfbb262c8d393e09023074ad4c3e42fe.nq.gz
│   ├── 64897c12898d12aaa8f93194bf2f6e876377c5b5.nq.gz
│   ├── 64ccd02fe69fc20b40953ff02d9794e99b8f7de3.nq.gz
│   ├── 6531028fe51a6a8dfe493c7dd4011c89b457bfe0.nq.gz
│   ├── 671a03615d154c12b85b54032226eea4d4d2213c.nq.gz
│   ├── 6795fc6b73deb49f773bc3a3091697b8eba6c11b.nq.gz
│   ├── 6f7fc3d40a4cef9e8251139c093d2e87b0b0a0b7.nq.gz
│   ├── 70c6ee8f6aea0e9e4c6d656c4b0bb2a23cf14adf.nq.gz
│   ├── 71c8fd3454da95083e086e195ca793d9dfdc4a28.nq.gz
│   ├── 778666eb5fdfe5a802e3183e7fe101db20fd1b4b.nq.gz
│   ├── 78725f74fa926b2c514f81df6c0d3e115a3025f3.nq.gz
│   ├── 79a886074726a2740da444e9a8d0aa0015ff2608.nq.gz
│   ├── 7e6b1d90b5946a40d03f0da9c2b70098547e822a.nq.gz
│   ├── 802033a17a04276eaadb369f5c206691f0660373.nq.gz
│   ├── 81f3b75d5e17461006c448975b989b1aa01206ca.nq.gz
│   ├── 82fd25243777a41afd171dc45634f72aab90b6ad.nq.gz
│   ├── 838320138f375add9671bf533ee762cf1a0defee.nq.gz
│   ├── 84b4fdf4d27b44f6fd8e7c68aec2ccbf82327060.nq.gz
│   ├── 8cab8a21e19a5ffe933cb7efeed6bf93d5c35bc2.nq.gz
│   ├── 8cfdcb496c96caf161b3f0adff2d00fc0c57da98.nq.gz
│   ├── 8deb970afdcd8b5ec64f9e0bccabdc69a0d1b751.nq.gz
│   ├── 8ec6ae368edc9cfee543fd24eb2e0074d6d2c2b8.nq.gz
│   ├── 8f7833b5c1b7064cd3ba4a68ae21b946083ec7e2.nq.gz
│   ├── 9270b3db2692e8f7b17b9540dfedea017c3afda9.nq.gz
│   ├── 93ebc8016be31156485b5e3a223ea6a81a9ad6fb.nq.gz
│   ├── 94ae3cd0d65cd5268290f84ec1d418a6adf065b9.nq.gz
│   ├── 95f543981fcacc0aaa83c1f0adb583b4ee37d77a.nq.gz
│   ├── 97b98e829e3431858b8b53746b6bf86906185719.nq.gz
│   ├── 99a734eb589602b77feb1b138d90fd9af2cce76a.nq.gz
│   ├── 9b73e2bd64675a0a6f68843255edf76f811f2f4e.nq.gz
│   ├── 9d308c7bd9c88097cfbabd28ca17d30c6428bd4f.nq.gz
│   ├── a4777961049b2122a2b6ea6f0ba6aa01cd79859b.nq.gz
│   ├── a4dece7ed80362afb2e97129addee6a967a4a59a.nq.gz
│   ├── a4eb00796ce970ab69ea58718eff0f4dac7ab204.nq.gz
│   ├── aa7d417bd4cda2b2ea98a4748d42ffdaf4f68125.nq.gz
│   ├── aab98bf11c9added0898c6b28c43c6dac54ccb7c.nq.gz
│   ├── ab88681e4715405a7e3b4fb331ea31dbb8e05872.nq.gz
│   ├── abf8f4f42f9d22d105658eb963e3e73d11e5689e.nq.gz
│   ├── ae948ddf51739a198719a8b6595d7affceca289b.nq.gz
│   ├── aed2c74a1333804c44594fa3d6e1980f40e3778a.nq.gz
│   ├── b0cb7fa044cf8dbcfb854e2ad52148833fae2820.nq.gz
│   ├── b2ad86f794fc9274317f8d8b28b222d605bf34f9.nq.gz
│   ├── b42757f419c92b260a6b0f7b5fe19cddc52c28f0.nq.gz
│   ├── b4abcff38815ea09fef75546fc9a38b4afbdc58a.nq.gz
│   ├── b763bf6c3e8afe80d87cf56a38469575cca3f19d.nq.gz
│   ├── b9a229c9bf414fa87b3f285853a884e1e3506fc8.nq.gz
│   ├── bbeeb1f5dc629c7c946e2fcc7817cd2e85a49557.nq.gz
│   ├── c48d882cc33b5a27afdc6afb27967a41abee8d26.nq.gz
│   ├── c7edab9332eb95a433daf353e8d510ca7a936760.nq.gz
│   ├── c9d14f29725a68a344c0a1252036c79fde3a92cd.nq.gz
│   ├── cba1ea63a0d2101e844d91809000cbd71fa565eb.nq.gz
│   ├── ccff6ea362c08ecf1d09b1513036fbb3b8e27295.nq.gz
│   ├── ce0bc56681f42280b303d542cbeebb04ff3f9f79.nq.gz
│   ├── d157fe81fc68f73f1ff2dbe8aae2942d2e33ff54.nq.gz
│   ├── d379de2805409070f2741d921cc1bca3d51fd552.nq.gz
│   ├── d3f3523975b818198cb3cbc5704c4fd7c263f3fe.nq.gz
│   ├── d6c01591b3f66a894239bdacd7d392c7074f7a97.nq.gz
│   ├── d6decfa0236a4e01f26a3fc664acffae6346fb3e.nq.gz
│   ├── d77e7e7730313dd05146f658e29d46fffd55594e.nq.gz
│   ├── d807a5dd7188c1a2223a6c1ee5c81574c86d8e37.nq.gz
│   ├── d8caadf762905969e6fbeef8c66230dbbcdb5d99.nq.gz
│   ├── dd75f7a10a89d4c6985c40bcfd6b45782fa747e0.nq.gz
│   ├── dfc73621fa8cf574f1b5cfd0410e2711ede5792c.nq.gz
│   ├── e08b5bb28711c99902e455274aafff13a15e1f84.nq.gz
│   ├── e39dad8e66ad80093b4a9824605c92092ab41540.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e75bc7196d0def594f874ed16c8b220b92a6d421.nq.gz
│   ├── e7fa7b614a7f8eb49cf6e9708d03a8a7055d131b.nq.gz
│   ├── e8ea77cd2f2676c3351e3e753bf08f3e0fba5c52.nq.gz
│   ├── eb9040d673370b79d1d4d7813b01dd9635d6d24b.nq.gz
│   ├── eea674c4bbcd5dfc3be7bda7b99b3d9444d2ce62.nq.gz
│   ├── f000ec87ff12b3801c79adbb4cd07bc7b274a850.nq.gz
│   ├── f00eee3b90c992ba31b7bb712d071caafcae4cc2.nq.gz
│   ├── f02df397e7b0c5b450bff1e2196bdee04826f376.nq.gz
│   ├── f2266f2473a4b983a918977e98c1cc55a4f1d855.nq.gz
│   ├── f392d067fd70efcd85412ba3f56e76be5c988476.nq.gz
│   ├── f630055042a7586a30a499c5b9fe71e25ac38076.nq.gz
│   ├── f7464569c27d71b7c93b7c403534f50749d1e6c6.nq.gz
│   ├── f7552e7032051abb494192993793fd859a7ec1f3.nq.gz
│   ├── fb7a38c95f03a8e5bbef9758ad405319b6c80ad8.nq.gz
│   └── fdbec19ca501466233f41245d04de1c2c0c582a7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dfe16f2edc4108fef9308dd9571f590b7febe313.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 132 files
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

[celery/django-celery-beat](https://github.com/celery/django-celery-beat)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
