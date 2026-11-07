# Repolex Knowledge Graph of ansible-collections/amazon.cloud

RDF knowledge graph data for [ansible-collections/amazon.cloud](https://github.com/ansible-collections/amazon.cloud), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/amazon.cloud
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4765d82b8d58b8cea3bc37485f5105e5e197aa15
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4765d82b8d58b8cea3bc37485f5105e5e197aa15
│           └── chunk-001.nq.gz
├── blob
│   ├── 00877dca0337de7fa7d54bd720d9e93079334670.nq.gz
│   ├── 024f84beadc9e3a7934f60ec7ee9114d9b023ff6.nq.gz
│   ├── 02d2dac7322fd78744a442fb61b0a31d61407aee.nq.gz
│   ├── 0526d12f5d36b837d8e7f54bdc4a9a35d78a6a46.nq.gz
│   ├── 057a20113649162ec1e24e3a6ccb8692343ac234.nq.gz
│   ├── 0613062bd6643dfb33ec79307f36a5046c4c91a9.nq.gz
│   ├── 0a7b2de90a0fc3b1821602c36235b692689c7c2d.nq.gz
│   ├── 0a7be9078ea3a6f6708f424457cf47eb27b7de3b.nq.gz
│   ├── 0d8024899f4a9088d14377a769886caf14b0245f.nq.gz
│   ├── 0f761b9a5fa4efcafda80f2b4b92d34a366457e1.nq.gz
│   ├── 10e246bce4bb5aee26d8e87c97594b6e81f3e857.nq.gz
│   ├── 11f72db1786ef39c627a9d7eff0103518a99445b.nq.gz
│   ├── 1810d4bec988cb82a6ab1bb342da56eecd993613.nq.gz
│   ├── 183c8cf5f41a1aaf51b274fe549ba9ee21b0c01a.nq.gz
│   ├── 18bae2c07343f0fb1df4d89aa6fbba7d4d5882f2.nq.gz
│   ├── 19e18bf7a5066f3d5644672a4fa25c85d520d570.nq.gz
│   ├── 1bab0108475e19ed904c6845d9bd78cc1c1a77ec.nq.gz
│   ├── 1c2182452994ea367223c95acdb2c756e8eb26a2.nq.gz
│   ├── 1e1a5f2a2591cf8c91645f82791f4eb34fb2b1a2.nq.gz
│   ├── 1f136642a70c15a19ecf2591170ca98b7978332c.nq.gz
│   ├── 1f27da08ab4b9988ca8bd967963ecdbb1d411f14.nq.gz
│   ├── 1f7528f9d9f1f356a9f75e3c63828b99db3844de.nq.gz
│   ├── 20604473f5d993eb8b8286411fab248443f81084.nq.gz
│   ├── 2205d5c82ff31cd9b832a7ce494461f6b3f7a81b.nq.gz
│   ├── 226a7b5806a9cd9965ff5d51f44916541f1211f8.nq.gz
│   ├── 229037c8b22554bb7f6053ab4a34334b95c8fe43.nq.gz
│   ├── 241a58779b3cfb68073500984d0290cb98c95bf1.nq.gz
│   ├── 24849d8bee9fdab312e76ee5f32d2846d64b1387.nq.gz
│   ├── 28a448d8ec4ccb8d06c2770d064143f34a79ed05.nq.gz
│   ├── 2952d469863a50a990019f248e73dd577e93731a.nq.gz
│   ├── 2fad46e561b86dec8b11745b204381aa4a844c44.nq.gz
│   ├── 301900f1db1ab56c1127710195828865e0585d74.nq.gz
│   ├── 317c146db996510c00e6cff58cc836565e2d7e82.nq.gz
│   ├── 32cf5dda7edf769a8573da8700b51cd5c517248e.nq.gz
│   ├── 32d048342ba688de82ff4e568e7253afc5e472b9.nq.gz
│   ├── 32d4fb3587276e5eaa9c2b239ab417e68b72e4da.nq.gz
│   ├── 32f372d0f8dc609dc3aed502900a79677b27877e.nq.gz
│   ├── 336366eb2425fa10255638db841bbcf7473c5910.nq.gz
│   ├── 33777f4be77aa80f1fe952f7cf563f77a689e2da.nq.gz
│   ├── 3391bc97e62ff40c6eea91cbb9b84d07d4a11194.nq.gz
│   ├── 339ac72fab4f5f79b1166a4aa5c16711e45984ff.nq.gz
│   ├── 3452021e58a8bfe077572d1e053699cdccd95fa8.nq.gz
│   ├── 3466a3367e55b004688769c70cf6ec9c6b1470bc.nq.gz
│   ├── 34e847d8353cfe495f019e86228573c1a1a0cc07.nq.gz
│   ├── 39872d749f3f96e08f8df6b8be5b5f2f0d4f895f.nq.gz
│   ├── 405219117fd94d46d68e463a8954979224d5ec19.nq.gz
│   ├── 421756ad34d9597428dc03684e365e993b5e0df6.nq.gz
│   ├── 43c65bc3270e6df17664d7afef2a788566e44806.nq.gz
│   ├── 444eba269b312fe032f2db33c9dead0eaf91d4b5.nq.gz
│   ├── 44ca4837a0ae332a6cb1c3a28dbc637dc0527d7c.nq.gz
│   ├── 4606e000e014321a650311b733f160e98feed630.nq.gz
│   ├── 466c9bc73426402685f7af760b5f1d48b0f67b7f.nq.gz
│   ├── 4777195ae6db291fb079cfc10076af3b3f038d5f.nq.gz
│   ├── 4893143674d8c0abe431391b39a77ec7ac728a8e.nq.gz
│   ├── 4e3e4a0e1df15f7053e5cb90353d19412ee54b75.nq.gz
│   ├── 52b8dd657a9cf64d7ec90ff192dc71f62399ca33.nq.gz
│   ├── 546bc143beb8ea44f19eac155d477094507dd569.nq.gz
│   ├── 5478cd85c5832cf6b8ef3262afbcbfd193d1d664.nq.gz
│   ├── 548cd8884c6aaf746dc519d8ceb648971beb24f7.nq.gz
│   ├── 561ac14ba4da2003e17733ae9fff6ed4a35bd3fd.nq.gz
│   ├── 573c9a152c464e42ac4d57bbc49dd4916b4b937c.nq.gz
│   ├── 573ca6af64fcf0f5326dc034d8c620eb3307fa37.nq.gz
│   ├── 58cd99036c9a9202d3d5a9a6e524be681f1706a3.nq.gz
│   ├── 5c21acaf7909b85eab00abe9f5754348aca708a3.nq.gz
│   ├── 5ce9a91cc7bf855aaf08fcfb16379f87878c197e.nq.gz
│   ├── 614de39499b26bd9d5106712f91cd471cea59992.nq.gz
│   ├── 61f6ccd3244ef8f2a833178cc85129232e4c445e.nq.gz
│   ├── 6229583c39f361f429c78d293687fa99e0788183.nq.gz
│   ├── 62badcf63b864404b445ccf5c751c51a89e655f7.nq.gz
│   ├── 63cd5a51862c01fd64d6b8dc4176b8eac67ef126.nq.gz
│   ├── 6480db0190ce7522553d8cc620d4956d05b2d955.nq.gz
│   ├── 6493143a6d1a269a4a13698d734104dc9cc62ea8.nq.gz
│   ├── 68345c9eae581a9fe086b83fddf009fcb1120ac1.nq.gz
│   ├── 6956d1a8eb0cb1d69851ec578fefa9febb0ea050.nq.gz
│   ├── 6a1f083aea9a99554f1b77f586030e1ca3c8b7f9.nq.gz
│   ├── 6bb363591538c0fe5b789cbdc80ee7e709de237f.nq.gz
│   ├── 6cf9d365dff3ce1e21d1eae073be0a5930120694.nq.gz
│   ├── 71f6adc4e1f7297e2678acbdafc9892926645d5d.nq.gz
│   ├── 740c8115458b12e3a8f24220e718e0b33ef2e16d.nq.gz
│   ├── 7460f157654c4f05c27e9b207f30720324f86d4c.nq.gz
│   ├── 7606cfb06981684b12ec6984180aa3106774defc.nq.gz
│   ├── 774682d6da144873b754d62d6bef7efe57d88313.nq.gz
│   ├── 785baa4cb0f1d8ffec6bc930ae6811804a7fbc16.nq.gz
│   ├── 7a8ba1d6254e83ec62b2946a524209f4a16dc370.nq.gz
│   ├── 7cd83961b467511931eb43da2191c7698c786e89.nq.gz
│   ├── 80d2b231a172e058f8cb65c1789e424cd62bc7ab.nq.gz
│   ├── 81a9a38c3f12cde7bfc1fa9e5917ba76383fac24.nq.gz
│   ├── 82d6b2dc51e941911cde5951f4f190d8a6089773.nq.gz
│   ├── 8397b3b6ef2306ddc6391589038672d12d77bfb0.nq.gz
│   ├── 8585ee1049848a49edc6ea44e918ea63df77ba01.nq.gz
│   ├── 85f20a4fe3dce5d8b5317bccd375c2a354852110.nq.gz
│   ├── 88cdd0f35011a153c57f2daa93430f6886a36bef.nq.gz
│   ├── 897cda4f1c65500a09affb021d3545414af58dcf.nq.gz
│   ├── 8a306a40d317d84f74974f1e7d95392eb1fe006d.nq.gz
│   ├── 8a6e9c24c5cf08b3f50904d85db561892cc7bc80.nq.gz
│   ├── 8ad4374b15514604e2c66d7f3c367c8192335fd2.nq.gz
│   ├── 90e21ddb933aa24c3da11201f0570f6db5a2a2de.nq.gz
│   ├── 9156183e5844c11e2796a4e92e0d34301f079b26.nq.gz
│   ├── 92ab1bb44f5f257bb0303be94c1e923430e1ccf6.nq.gz
│   ├── 94eb47f44da998e84e316d0eeba85f28727f5f21.nq.gz
│   ├── 970204b963f49229cece9d4839e7110a4bf7fa98.nq.gz
│   ├── 986642c15264d31ff60c61237ffade23c3f894c5.nq.gz
│   ├── 992cef09c301e0b983ee122bca2b2f8a1363c91f.nq.gz
│   ├── 99ce82a1bda66170906b7a8d8976f5d2249363d2.nq.gz
│   ├── 9b724c20f81a2721c70865ba2ed40756bde88e7c.nq.gz
│   ├── 9c651fe3c6fdbfd50b0aba451a7283a36750a6b5.nq.gz
│   ├── 9e11042d7bd1401c231bcb177821aca8aa59e1b9.nq.gz
│   ├── 9ec9a18388a4af1d47665ec2c094e2a5113510e3.nq.gz
│   ├── 9ee6072a9b1efb57adef014a881ff262069b8987.nq.gz
│   ├── a00ec42a1d47a17849b6923a822e45901c2e333b.nq.gz
│   ├── a1534374b76652dd431957d822518a433ff8f09f.nq.gz
│   ├── a2d7420acbad7d22efa29f59350e68d43551db8a.nq.gz
│   ├── a3432b01d3b27fe8a4acdec5bf4a03e7cc5234a6.nq.gz
│   ├── a40db0bb0a3276e11a3c68f1baf9e716ed6a733d.nq.gz
│   ├── a92546480550f4c16bd425b89e0c87bc87a8e4bc.nq.gz
│   ├── a97a90cd5d482156b2ebba6ec5924369f41dd2ed.nq.gz
│   ├── aa50307a3f52205ed43a68befe725611316aa6a8.nq.gz
│   ├── ac7c3ac4abe676c2d3f32ae45fb5134a7b70b296.nq.gz
│   ├── acc79cdce195d8d56174f1415d4906c3bbf3fc6e.nq.gz
│   ├── accf877544aef7aeb1b988031867ac01fa30a241.nq.gz
│   ├── add8e4c1262545aebc3ef9e57272502882f86763.nq.gz
│   ├── b19b3f96b7e858ae92a6ce1f130e73083d5361ca.nq.gz
│   ├── b27b575f0cb4c247de503e2b79394f0a786c6975.nq.gz
│   ├── b49d7fd50eb253bdf204ff563cf30d80be2859de.nq.gz
│   ├── b547e8f2f9aa2ede40acbbbbf90a95d18f824c15.nq.gz
│   ├── b803d29dde4e89559da0ac4b891ca06d0c5ab30c.nq.gz
│   ├── bb4473cee562afd0cad032c3e8944bd97c24230f.nq.gz
│   ├── bb5260b1f452279303149759e64a00a77ad88f1b.nq.gz
│   ├── bc6a83d5715864b338d471e91493d86631628c80.nq.gz
│   ├── beb374a6c2b9f49787f0d5e0e6c4d3a51a08e301.nq.gz
│   ├── c216e984f40588ad42c844cca6853b65a07c4d5d.nq.gz
│   ├── c5938c6aadd215d0e8afb26cd6d3ade1b88389d7.nq.gz
│   ├── c5db1316e00d3498dbc2795012628315da3656d0.nq.gz
│   ├── c6a95aa3514e00fce651e0792d59d8d1fc668a4b.nq.gz
│   ├── c70a21509db3ac4b66e3bf5f18cf766702476060.nq.gz
│   ├── c776e483b4011a3053731b7cca89d49a33c57956.nq.gz
│   ├── ca6b93e90df968000a13880669370ea051e4086d.nq.gz
│   ├── caef802692e68f49672e1836af35bc264e9c43ec.nq.gz
│   ├── cb1ac4d7c81e0e7b7071bee36ac457dbb56a370b.nq.gz
│   ├── cb4d35cbf4f43c925fc5ea8e283dc3c25f53ab4e.nq.gz
│   ├── cf46c0ecb6218f672a67afc31dd783244f45c85a.nq.gz
│   ├── d110681bf6cb98f6ad5e4be062e79633ca600ea1.nq.gz
│   ├── d1534ec4b44545e7494c6284ae506fc5d10afa2e.nq.gz
│   ├── db0feddf1a635a3fb7264ba0de49a6e8db8a4a93.nq.gz
│   ├── dd5e0a1871255585fdb6cc7c3b34841251e0d752.nq.gz
│   ├── e20a226054ddc0c2254b47098fab4c7907f67bf0.nq.gz
│   ├── e30a1801b1ed5952f592cdb65945b3a6fa2618da.nq.gz
│   ├── e4f80f8383afb8b69ad2086f0a83af97a3910f07.nq.gz
│   ├── e66c37349a15b1e9591d92404af61cadc94ef8ad.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e781d89be77c58a36e2446fad77e1e9b4176f09f.nq.gz
│   ├── e8bf7679b17386eb27a6da5a7a8463e3700107b9.nq.gz
│   ├── ea0aa47736a246c58ce8e6f26a4e442bef69de00.nq.gz
│   ├── ea58cb957f4a6c4e5551ab17fd33352d5695bd66.nq.gz
│   ├── ec27d54047e7e6482227d6c821b8a454079191a6.nq.gz
│   ├── ed7e6a0176099ccfead2115b8210395faa802370.nq.gz
│   ├── f0e95ca637603e38e07ae467cd88e6bf4881a1fb.nq.gz
│   ├── f1468ee28a6b41e1d84147aac82e1a16db4097c7.nq.gz
│   ├── f1e0d7e304b7e449dd83f2fd53da89f54e755c8d.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f2eff4d6062731da96d9aaca69fdf3a87d36767d.nq.gz
│   ├── f480da71fab8f955657df101e19acb7854bcb213.nq.gz
│   ├── f7ef54265d52d38372b8cbfcaea4ada6fc7e8791.nq.gz
│   ├── f8df391b5f1e31ed488aa0b1879dd4b47f1e924c.nq.gz
│   ├── f90bd1ad861af4f092444b8667bbc662d345e7d9.nq.gz
│   ├── f916a03e2dc383c289f5f560eea1b76f34c8bd07.nq.gz
│   ├── fc148f56070ec08c38aa5c19567ed786d9ec2171.nq.gz
│   └── ffaac203a72bc201f6fe48765dee98ffe71de3e9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4765d82b8d58b8cea3bc37485f5105e5e197aa15.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 176 files
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

[ansible-collections/amazon.cloud](https://github.com/ansible-collections/amazon.cloud)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
