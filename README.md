# Repolex Knowledge Graph of colin-kiegel/rust-derive-builder

RDF knowledge graph data for [colin-kiegel/rust-derive-builder](https://github.com/colin-kiegel/rust-derive-builder), parsed by [repolex](https://repolex.ai).

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
lexq download colin-kiegel/rust-derive-builder
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 5705f00f23e3bd77c453a1c0bbd3de34b572b049
│   │   │   └── chunk-001.nq.gz
│   │   └── fc18dd236a6dc6b5b49970efdb1b78f40bb3b998
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 5705f00f23e3bd77c453a1c0bbd3de34b572b049.nq.gz
│   │   └── fc18dd236a6dc6b5b49970efdb1b78f40bb3b998.nq.gz
│   └── repolex
│       └── 5705f00f23e3bd77c453a1c0bbd3de34b572b049
│           └── chunk-001.nq.gz
└── blob
    ├── 0781330f9b33d1e93a00d47a54cd6e24ef131a57.nq.gz
    ├── 080d8377ef755f0de0210d794bcddaced65b1dc1.nq.gz
    ├── 089f752369a6acac7edf2a1d0fc10e845a40d288.nq.gz
    ├── 0bb986d663f7d078a238ba0705da892186cc9555.nq.gz
    ├── 0cf4b7ef64c707a37c75076c02284aecde9f74bb.nq.gz
    ├── 0d53cbac452faaafbfca36f38b9b8adfaf573d22.nq.gz
    ├── 0e0d0bd596a4f36b85cfb866411eb6fe9e04dc96.nq.gz
    ├── 1121a1ec19ec9ab5f20e3a10705ff7be0fd52379.nq.gz
    ├── 13f2a08e2f27bbc0d1e67e7267208c60560e141b.nq.gz
    ├── 154b937e06aee4bed839b53ee66902db497f4d3d.nq.gz
    ├── 1ce1d8d9475ffeea72361314ac2cc4e4b440b275.nq.gz
    ├── 1e5b0c0d55c83748b117a7026d6af69eb685dc03.nq.gz
    ├── 21ad7f6bb1529858d3d8c8a6644584342d6f6cd0.nq.gz
    ├── 230d53ebaacab8c0a9dc42e513757a8edd18ae3f.nq.gz
    ├── 235cd567b19f2a335ae85831f2275596516e4e7d.nq.gz
    ├── 27e62faf59d3146856153758e0fa47ef86e87b35.nq.gz
    ├── 28f6a01c0289fb5b2e4cfd2ceedd7640100c6071.nq.gz
    ├── 2b423c7c70497f9d0ca959e1d62ad0f7853c186f.nq.gz
    ├── 2b4f999e2113a0f6280ea606a1ff67aeb7bda3ba.nq.gz
    ├── 2ba7bcf80d998d8ede7d4aaebc49dc1d23903101.nq.gz
    ├── 2e0a83916c4b4b45630a5c24fc152fed5f1a471e.nq.gz
    ├── 2e9bedb85b1ec4ea4cd2ddd85221b5b3c7bfe52a.nq.gz
    ├── 2eeb354cbb10465cb24652fd5766bbcef4c55097.nq.gz
    ├── 2f30d16f62fcfb72bc170bec5f2713eafea21937.nq.gz
    ├── 311cd34474571a789df01079f17fe262323dda44.nq.gz
    ├── 3195e824fb54c0cf46b9c8ca0b0a2f1ed971cab7.nq.gz
    ├── 326b80aa9ff7756ff4299d14566096d7809db5f0.nq.gz
    ├── 35699b0b3ff42e9994db62d628abddad79cb1140.nq.gz
    ├── 35e5e8ecae988f7ecf35e0615a70a6bbc74a75d7.nq.gz
    ├── 36091c4190d71fb05fdfd2c328c7fe73c61113ab.nq.gz
    ├── 3894686d491a902815c3245200c077f22f1eea96.nq.gz
    ├── 3894b782ddc15657eac6964037a01a4162ab2c67.nq.gz
    ├── 392221fd104236d921f667052850073f4bc4710c.nq.gz
    ├── 3a3d38498b442003aeb2ac029d6823af19654f6f.nq.gz
    ├── 3b2cd570682c856da19db8bb443bab823a3cd1ae.nq.gz
    ├── 3c42cc49500e0095c1cb2a0b98e958ba1ec0c7eb.nq.gz
    ├── 3e1fb4eba59dd6dcfde8c8bdbcf1b75a7ad57604.nq.gz
    ├── 3f4d025c169337d09558ec4bbfb420604acb6711.nq.gz
    ├── 403e89c8176d49a9533ff6b37def9de2ff02a63a.nq.gz
    ├── 409809ac30ebebcab965567f0dc28623769490c0.nq.gz
    ├── 413201b0267252214ec8fe00196a33986f525302.nq.gz
    ├── 438273bf38ae44a6dda87edc4954b09b0cd5113c.nq.gz
    ├── 43fddbf5011e8977fcb0e44905a55e4c77df0e93.nq.gz
    ├── 44dd304cb8b81c4319cc69441d56e6eda1ce520e.nq.gz
    ├── 4521b0a73f90692d42c749b8d6203392e868c0da.nq.gz
    ├── 4565ad4ab289be5370e87a904888da3b98564d0e.nq.gz
    ├── 45fe1efbb0ca2571900a2eee31beb0bda4926cdc.nq.gz
    ├── 46a6fd8f376c12466c4801cb48ab5025bcf5691a.nq.gz
    ├── 4800464eca2b70495b88e992ebde83d4ca5a2afc.nq.gz
    ├── 48b7653f40ed716119cb7f81280fa563a0b673d1.nq.gz
    ├── 496c656d3169afffd4584bf3ea1e316d19d3c24a.nq.gz
    ├── 4b093d7d581e6965c51391ec8599c00bb192bfa6.nq.gz
    ├── 4ee0222d939d6842fbeab6e5e7012ad0cdfb4a0b.nq.gz
    ├── 5100c971508b3b48a5b96ac6d4c19224aea0f351.nq.gz
    ├── 514fb6ab013db7cc45df6d55f71701866ba31c73.nq.gz
    ├── 51e176fe2f9d63171d31c98bcd0915a1e7d77871.nq.gz
    ├── 52ac2608ad4d1042b6bb3f797f6558cf0f09f53b.nq.gz
    ├── 55150b408f2493e7ce302e746c735f1e92f97f0a.nq.gz
    ├── 595b8a75fe65d912e047ae8790531618966ef9b2.nq.gz
    ├── 5af714a4a16144cc76c6294d2a0629a7db3286e2.nq.gz
    ├── 5c43973ca93e16de339e01db6b56703cc887eb05.nq.gz
    ├── 5e2141b1b75237c6c70fe40bca1f98f34155ec49.nq.gz
    ├── 5fa9129ec2f361bdf4deb7eff7c115ad0c766b66.nq.gz
    ├── 602fc87a1ed342feb67fd6fa174829e13f121175.nq.gz
    ├── 6267bcc0f4b08d7be2294ab46a2aa568d9d96f95.nq.gz
    ├── 62ed7b6cc68161378317bd77b7df124e95b8fad5.nq.gz
    ├── 6684ac28c2d63a5bb8d41e3a459ca065fa2f896a.nq.gz
    ├── 68e38a417df578a3e79541030b745f5cee5d87e3.nq.gz
    ├── 697a1b72f964091e73f31f712b1a0af466fb2d12.nq.gz
    ├── 6a9b21853839715f2d17684fe541cb1e2448f815.nq.gz
    ├── 6b5964686eff1f7b07bd0177441c847b274cec5d.nq.gz
    ├── 6b761b23596c28e5ecbd2a9f0fc53d797564cf44.nq.gz
    ├── 6cb2f2dacca541a9158a5dcad493558b969105cc.nq.gz
    ├── 6cd7a77c9fd50c579d759df9ef1f5a4fc0da840c.nq.gz
    ├── 6cfc7335fa8884fd9a1738561859489d3aff51a4.nq.gz
    ├── 6d2e71ea8af945a9ea887bfbd0277c7730630c95.nq.gz
    ├── 6f6cd3017fc52a335bf789b2ed566ba8dbf1c4ef.nq.gz
    ├── 6fdf59b16f86a578fab22504d35f98bb7c9d7b4f.nq.gz
    ├── 705d8cf2ec9a54670e29c1608695ba691c25bc3c.nq.gz
    ├── 7118a1541414498fc5fd69b89499732b0738d8a0.nq.gz
    ├── 71de621db0f03ad1a835d32138e3f2a0e5b9bc03.nq.gz
    ├── 72824f28b9b671b2ce989d6baccd88658f62f9a2.nq.gz
    ├── 74c37efb5f3c356640f0601dbf4ab2f2ca31d9d2.nq.gz
    ├── 74f074df124c5b31c73bf44f32f4482f3bd03532.nq.gz
    ├── 7565efe6498ae3f287d913174c0eeca5ac94876d.nq.gz
    ├── 76219eb72e8524f15c21ec93b9b2592da49b5460.nq.gz
    ├── 768269451358f065ca674a3894d3ebccc9ccfdbf.nq.gz
    ├── 7a733adab19ec89f7500a5793212f00eae1c6f80.nq.gz
    ├── 7c89701b56993d6131f9a8087caff6e63dafcce4.nq.gz
    ├── 7f69ddb76d358a35124ea7dd73f9ed12038d4ec9.nq.gz
    ├── 80b08df60b20f3708c42f5db5a4576b1665fb74a.nq.gz
    ├── 81a5eaa23138e35c5846bbb99b9122172f0e9e79.nq.gz
    ├── 82810767417bf732ccc09dd97eff1207ce8de4c1.nq.gz
    ├── 8379340dfe6df5830e47242d09a397ceb9472251.nq.gz
    ├── 83a5f3e8b1cd0941196ab1e5b942ee8e5ba181e5.nq.gz
    ├── 84e091caae7174770ba56dae929a4eeff79740c1.nq.gz
    ├── 877764281f8d399de4e46410f7485e5721657625.nq.gz
    ├── 8798002193a18e1db62ffb8514d46c66b2426817.nq.gz
    ├── 88301dce5e0fefe5ea673dc7db7ae4277722ed19.nq.gz
    ├── 8887694e67fea4239b6317a86d4094ada8aedafa.nq.gz
    ├── 8bb4f189cd574c04c3fcdf26f5912f1e83266c47.nq.gz
    ├── 8c3d74056088ba1dbdeda2528aeed6af6631850f.nq.gz
    ├── 8cd1b493ce8914f3d4d81950bd09af8f0e908609.nq.gz
    ├── 8d0b2e06c88b4529ca7c223f1bc17eb73a892cce.nq.gz
    ├── 8d85a7268e029e36e55770ed8cb5f471b2757ef7.nq.gz
    ├── 8f71f43fee3f78649d238238cbde51e6d7055c82.nq.gz
    ├── 8fd6d215f12b552e504171db9258cc4907faa84f.nq.gz
    ├── 92a20a40c8152b014c529860e3d2ef252c2177f2.nq.gz
    ├── 95d988af41ef9ee94c8036e075656c8919837944.nq.gz
    ├── 963d368cf8ed72332f2e3dc4ce450a16130d4d99.nq.gz
    ├── 965b606f331b51d566b46025f9ff311a7aad0c12.nq.gz
    ├── 96a73a36e0ab7f9a5c4b07c4cd439e981a2c17a3.nq.gz
    ├── 999509348cd7116091f3ab046cc2ef8bba9107c7.nq.gz
    ├── 9c1fb539e1a48e2a8afebe9fbb24f6fd3bc12262.nq.gz
    ├── 9d9d6fdda2fba6c388c2e74ad003e6073ebdbed2.nq.gz
    ├── a00581b158cb88f6c097a4e11d5884deb6454d8c.nq.gz
    ├── a1a5ee8194c602895fb3ea03744d2bef72435a93.nq.gz
    ├── a4622ce4c5ed2ed9bdaba0926469bfad633495c0.nq.gz
    ├── a46893f5dc36f0e299ae669674dec21ae77f364f.nq.gz
    ├── a52eed8ac71d4d39119ea5c5833184ed799e4626.nq.gz
    ├── a8b2b953ee2a971a367f64641185770c3ee1ab0a.nq.gz
    ├── aa5db36a65c5732d67551c0d209580882e301e65.nq.gz
    ├── aac6f8ecffd366a0284d6f494e37fce223039b24.nq.gz
    ├── b0d4ba41ca736b8cdb450ee5d451911df3ad1e01.nq.gz
    ├── b16716ec598c4801a1ed4a507c040c8f9637f025.nq.gz
    ├── b1e19215d68b5e635756ac2cb8a209d27c443865.nq.gz
    ├── b23ad8ce462e1872ecb02455248b7a63811b59ca.nq.gz
    ├── b4454891ec5f8b98f97a21fb0b1ac4197705e7dd.nq.gz
    ├── b4daabb0a9e693f8b060da3e8733a03969161ea2.nq.gz
    ├── b502d20e830b61b3e381098c7246d9bf3ff1a935.nq.gz
    ├── b6b317a7870e1a956bdf1ef922c8f1d75763ebdf.nq.gz
    ├── b71c96267cae0ca8696083fd3fbf6ea7ad235bb4.nq.gz
    ├── b73852d88103dbc595a3eb2d5011975e801f5d45.nq.gz
    ├── b9737a91d867404fd927cab8193c9e56986f3893.nq.gz
    ├── b9b78dea20493076cdc9fe16052aaa0441b08259.nq.gz
    ├── baf690c2128fa1f414b0b6c79f5d44a70320afab.nq.gz
    ├── bc03dcbbc79f7e0b690d1b79c90ae04f500da4f5.nq.gz
    ├── bc1b63dea1ff52542e6b4d03a125b90efa08ab8c.nq.gz
    ├── bdd3537600be57aee8a5d405c5df3bfb2eb246bc.nq.gz
    ├── bf493d9e58d4b9d57b6f4f8199684c6b10dadf41.nq.gz
    ├── bfc015d44c7dd694eed056e548c25262aa0d86e2.nq.gz
    ├── c2441c108d368328862c7ffc8532cc1a0e811fe3.nq.gz
    ├── c4d3ba9fd059b49780951c90658f9ebc542ec4b5.nq.gz
    ├── c5209641b89cf2e82ded84fc828b7ee1628060aa.nq.gz
    ├── c61d636962e2561a154ca74f32a6be06f6992b60.nq.gz
    ├── c8c2ed8238e2848dc25ade3cc24a64aa7f4736ee.nq.gz
    ├── ca0bd9dd066fdc954e027a8af1ec5a6b309b5e92.nq.gz
    ├── cae6f7c3795533882a2a0ccbabab0dd09f6f0c56.nq.gz
    ├── cb86410e01486e2b67092714c21be47011dcb094.nq.gz
    ├── ccce3d4d85a27c7e75d2e170ce1c65cc8a79dad6.nq.gz
    ├── cd13e52d5cf8b27f13b36b0feb5e5804f30fea27.nq.gz
    ├── cde3d817b4e2d00369e62481570d5fbd1e2e9839.nq.gz
    ├── cf332eb94004288547dcfdf62eb8d8586980121f.nq.gz
    ├── d227dc1e5f2c903b69e9b44d7b4e89bb3d2309fe.nq.gz
    ├── d2e6b473beface05e921e32cd44c9c09d889f8b3.nq.gz
    ├── d31f87f23b1dd93b644d07df2bf3f603f2930b00.nq.gz
    ├── d39f7c55263645ac778ac2cb2ec574a2631f48a1.nq.gz
    ├── d3e2a24e17541cfc5e3d729ca454d64816e39a9e.nq.gz
    ├── d412f90107d48e6ef344f53a5d235a163754df0f.nq.gz
    ├── d502340c68a0bd620235835aa77f8a991836b436.nq.gz
    ├── d6a868dfc8ed880fab4e8ccd97799835aa990cb1.nq.gz
    ├── da0d8f62a836370266889fe32ee268d6f3e0044c.nq.gz
    ├── da5737d03a296b85f4e9e64b63ae6c522b68d07d.nq.gz
    ├── dbb4d62e6cc2c21b560bc2cedadc241b130bff77.nq.gz
    ├── dec2137fbe0c3c24dfe0a180e04f50ba83197ec7.nq.gz
    ├── df1319471b34c9da577e8e8bacaa8f1d67e116f2.nq.gz
    ├── e0ae21b9942cea01f86e7d53dff3eded144f1120.nq.gz
    ├── e1baf7315168bbe587d73832749371cfdb9a01c2.nq.gz
    ├── e1ddade84af75306a0ec2cd1390ea1bdf0a9172e.nq.gz
    ├── e2dac3c0b3149346c47578292c9604e653d45b31.nq.gz
    ├── e454fbe91863f31dfd5f8e32dd2964ada1e474b3.nq.gz
    ├── e5d5b9bd2a0884097ca01e70df02c906b9191ccf.nq.gz
    ├── e74211557494a10706edb8ea2d009618c51a754d.nq.gz
    ├── e8db1c09b534f6a71222e05b16774c3d64a555f6.nq.gz
    ├── e99616e6264adea9cc7809a6c81c6875ef81062c.nq.gz
    ├── ebe17b5382493e73a6fd6f655091eb6b3c718284.nq.gz
    ├── ed6706cd0426e7b77a5a9f34335eb811875fe9b4.nq.gz
    ├── ee6bace863dcc3a2fdf3a1002fb01380143053b9.nq.gz
    ├── ee98653317b6d8badc297028a953ca9cdefe5028.nq.gz
    ├── ef69ecd406cc4b2fbb419e957efcb4edcb14e734.nq.gz
    ├── efb9df0278838a0f736fa621ca91097454d2b8db.nq.gz
    ├── f052a173fc428e8a7882c4f085d29f1cc2f35bc7.nq.gz
    ├── f2b44689c5d24fbca84c2156e50fca4e86923f82.nq.gz
    ├── f346c68722d54f0c9ecad34adfa9fb31175482ca.nq.gz
    ├── f4be9d29160caa9a4666ee959e51fdc3faf467d8.nq.gz
    ├── f5119f55cc1e441be1d398b9b795f939ed0cc4c3.nq.gz
    ├── f55b86b0d1841b8036d8c22fc6c67e4f522322fc.nq.gz
    ├── f6a82f07a736d14634d100687c1f5e594d1526e1.nq.gz
    ├── f7b32ba14b81ddecec03e9df56a26796bb6a599c.nq.gz
    ├── f8c8ad203bb586aa7667f44e10bf73092651d5ed.nq.gz
    ├── fa5c0d0d6a9da44dae356b39bf06e310b9953ec9.nq.gz
    ├── fa8cf032307323e07ecf2767ebc26365651f6d63.nq.gz
    ├── fa936cae888515c1dc8773fb1a5c0af2c046b00c.nq.gz
    ├── fd55a5961e07cdb490d9d1cf13cbd6cfa5866ccb.nq.gz
    └── ff2f8affb3865af059016ccf731e4f5d5ba52971.nq.gz

9 directories, 200 files
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

[colin-kiegel/rust-derive-builder](https://github.com/colin-kiegel/rust-derive-builder)

---
*Parsed on 2026-05-10 by [repolex](https://repolex.ai)*
