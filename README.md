# Repolex Knowledge Graph of xarray-contrib/xncml

RDF knowledge graph data for [xarray-contrib/xncml](https://github.com/xarray-contrib/xncml), parsed by [repolex](https://repolex.ai).

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
rlex download xarray-contrib/xncml
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── de521d9a300dfc4814f8adb5c91a8c4ab52231aa
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── de521d9a300dfc4814f8adb5c91a8c4ab52231aa
│           └── chunk-001.nq.gz
├── blob
│   ├── 00260acd44ccc0ca595abf771b592616407990e1.nq.gz
│   ├── 0086358db1eb971c0cfa8739c27518bbc18a5ff4.nq.gz
│   ├── 00a7b00c94e08b86c765d47689b6523148c46eec.nq.gz
│   ├── 047199edf283c504d5f9ee2d5bad4d7fee3bc5d0.nq.gz
│   ├── 048ddfcd9836d324a6e00f8fc97f778d5ccb172e.nq.gz
│   ├── 0528656ab8f981d9af47933af62a506667324ea6.nq.gz
│   ├── 0688462c3f88b07bcf843a2191461b91ecf219dd.nq.gz
│   ├── 0778828586cd75f78cbebf546f2918e34e97a745.nq.gz
│   ├── 09de2e5bcc7fb0ceec711f053e807d5be55ad4b3.nq.gz
│   ├── 0f23afafe126df2990b10d5f2695de4178eb6f83.nq.gz
│   ├── 0f774b353555bd5d6f034b83aa2993ea496ab07f.nq.gz
│   ├── 10d07bbb251c7b8851ccd2b4dd68bf2d77289ccf.nq.gz
│   ├── 116be847cb833e94a4da78b6a6409dc634297bd7.nq.gz
│   ├── 134971bade2728c02b1936400848851bfa36951c.nq.gz
│   ├── 1535452f69ec5094e5347959832819834e1480e1.nq.gz
│   ├── 17d52e0acd5db8fed30989a8eac5d4c9860e3519.nq.gz
│   ├── 1cae704d80049e231e774f84fad0aeaebbc0637d.nq.gz
│   ├── 20a2fbf49871aff6c3f3277f418ccc49fe1dbfbe.nq.gz
│   ├── 235c7354c659fbadc77df2280c80933935c3e352.nq.gz
│   ├── 248bcccdcda56dc554c35ee58972b0bbf28c49ce.nq.gz
│   ├── 256a44762837d54d0ec39581a6bfc969d2fd21a9.nq.gz
│   ├── 2968fe61ada24eae050e7d299db1fdf8b1862364.nq.gz
│   ├── 2986d392d05aee8541676c7308ea40f84c572a87.nq.gz
│   ├── 2bfd366b9320f7d61313f93841c287fe504afed6.nq.gz
│   ├── 2c9e80820047cdcc6d3eaacf40b347cbab3ad0ea.nq.gz
│   ├── 2f0086cfea8545a75d734360fb10cc77b54e3c25.nq.gz
│   ├── 30255c3fc1ca3c4883db7146688a57aa2c151b3a.nq.gz
│   ├── 31de668ee7b77421a65db4b78b30adc8410fd078.nq.gz
│   ├── 33f18d8653e7c14ab54ae17dde3fd1783c9ef9f5.nq.gz
│   ├── 340117e94b153b6d92f5b8822358974ce420ce73.nq.gz
│   ├── 3452ef1e8570af1cf8bf6b481f008d109aecb379.nq.gz
│   ├── 34e3c333602f88d3b52d5f0501fbad067cb2925d.nq.gz
│   ├── 36604762c57b770ca31963f21132b51a15190e45.nq.gz
│   ├── 36c90159d711d53d8ac26a3ad992836e001b63fe.nq.gz
│   ├── 39ba4e016d58b6c56818ddc39a233cd6f019e7a6.nq.gz
│   ├── 3a358c82287fee3007238518c159e87ed5a822c2.nq.gz
│   ├── 3cb9a0f5f267018f622e34c049f3e8e9fcaf4dba.nq.gz
│   ├── 3e3e91d22657e6bea04d0490fa9d544819ebbad7.nq.gz
│   ├── 3f5d07e50d4dce7474e125eebd8f46512c93b7a7.nq.gz
│   ├── 3fc90027d50f08b7c10262b0fc4384056cbe4577.nq.gz
│   ├── 40797f8a8d20d6083bf910b7056fd356d46466f8.nq.gz
│   ├── 4158ac8bce4d405452fe52eabdb37e04d7093201.nq.gz
│   ├── 43d721b2ec1779e68a112cca2fec50a01ae4c8e3.nq.gz
│   ├── 471c720fff8c5e95c189e883ee74ec48773b151b.nq.gz
│   ├── 4d416945611af94899b9978d1fe3adad7d327bb8.nq.gz
│   ├── 4db531cd71391f66df83b8c532d7bda07b620f8b.nq.gz
│   ├── 4e61558d6a11b2f0b802e0acc5f7080e5808b66f.nq.gz
│   ├── 4e7592416e9e812d4e9562ab3be14b64859a2751.nq.gz
│   ├── 50e9804bb265d4ec8b1ee5579a72c1344725430f.nq.gz
│   ├── 5106278b79b65c24d6b3b35776a9aa9564ff2bd6.nq.gz
│   ├── 5146e0946d06f9be6bde87b8d1f7519d0668c0ea.nq.gz
│   ├── 53f21ceaf3be07b21ba0af652c07418f8c7044f1.nq.gz
│   ├── 559411b42b720964440de2c64bfaff09cc6b0017.nq.gz
│   ├── 56247f0e17a8f8d00368d9d3bb48bdb99b1e64c2.nq.gz
│   ├── 5631aec9c6dd6dac2ec9ed0fbc836c337e06c1e9.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 56f63583f2c45c13c3ac0fe6051d9535086e7275.nq.gz
│   ├── 58f01ad5fb61200b772b9bf03920569ebc3b78d5.nq.gz
│   ├── 59633c0899ae7ad878290eda308a2ff789bb08bf.nq.gz
│   ├── 5b0e9d3eb0baf92af77ea8e32d2d0fe2d1d690af.nq.gz
│   ├── 5cd715f64ac42e9f342e5c0efa1c406e86f5aada.nq.gz
│   ├── 5ddce241b8390923cb97530e914b3530f6e9682d.nq.gz
│   ├── 5f680b4f012a0521a582352db3fe4fa16bb9fe4d.nq.gz
│   ├── 6464aac32b4ecee0682d4facc3203527be5424ee.nq.gz
│   ├── 65f517392446082adf32e2cf2081723310f359bd.nq.gz
│   ├── 65fbd1cc07c44704e9dd8b5125a32e1fd172f363.nq.gz
│   ├── 66b7a3e60543a322bea216c87d41695f88c657e8.nq.gz
│   ├── 67cdb64452f5f58a556b25cc5abb350372af0e10.nq.gz
│   ├── 685d6c4bba8f446941f39cf9ec22e97868d8d739.nq.gz
│   ├── 6ac321541d9b939be848e04d0df2052dfe4ab546.nq.gz
│   ├── 6b107e8a65ce2643210fdd7654298677f65208dd.nq.gz
│   ├── 6be2a85b1a1dcbb6e422580653c7f3f706d38152.nq.gz
│   ├── 6d52aa52ccde60ffa84d1bc7964ec54e1714dfab.nq.gz
│   ├── 6d5bb23e19b3794ee7217b45ba704becc254e13b.nq.gz
│   ├── 7021846220aecdc69d89b43f1be105103a5cb1ad.nq.gz
│   ├── 70b872582674be63c8b271e735f97e3fb0256605.nq.gz
│   ├── 7133526f800d0d074d1d53649ea855f70740c7dc.nq.gz
│   ├── 719351ad57a788d47a8498e8d1731376cd099881.nq.gz
│   ├── 72849f45be40b3c71913c02d4aa652aa6e88432b.nq.gz
│   ├── 72a33558153fb57def85612b021ec596ef2a51b9.nq.gz
│   ├── 742f113b82f2fada09466fd7241c03b378641087.nq.gz
│   ├── 7a01324afe568ded5065dafb2b97418de769b80d.nq.gz
│   ├── 801a1f7153db2d1e3ccffd2810c3964aef8b422d.nq.gz
│   ├── 85394b18aa47433c0b50ffe22a02d58c0c34eb02.nq.gz
│   ├── 85bab64a6ab8a4a8fe409864ed70d21559f6f3e3.nq.gz
│   ├── 86a88593998a994ac2892f53b1e8453a4258dd2a.nq.gz
│   ├── 8f989216e46d0a33b0831211dbc8b19c1da90bd0.nq.gz
│   ├── 947399bb3a13dc1f7d2ae8cf4335a9ec60a76f92.nq.gz
│   ├── 94a333c3eeef29b4e0ad4be8797af62c349aea60.nq.gz
│   ├── 97e7cde3babeb9e56dc9a54d49e1ff0f393858e4.nq.gz
│   ├── 989877a79095ca7ba764955885dddc2b92129f7b.nq.gz
│   ├── 9a53d0bee980bb02d3732d3734bc07529880104a.nq.gz
│   ├── 9ae9d6424070afd694563ba6ea159e63e295b061.nq.gz
│   ├── 9af5bb74f94a15c267c47392b5d42028631b2045.nq.gz
│   ├── 9b588282c9f4887ae1ca1b6a128722be5d0b7923.nq.gz
│   ├── 9c939b58339f6c31d017d055d00e675683eb1b61.nq.gz
│   ├── 9d57f4fdd306d71a228b03aa9abe7e80d5d0a9c5.nq.gz
│   ├── 9de2946f7633ebb8081dd17711e2597b2d703851.nq.gz
│   ├── a04894e147fb65b9917231532e53f79d76bc90e7.nq.gz
│   ├── a2491591058b8f2b26e253cb2939bd1f1e10e4db.nq.gz
│   ├── a3a20cc5ecb6be8c3be724c8a8bf1814926087ec.nq.gz
│   ├── a6be32e751d679ebd9139106f3602a5e18fd68aa.nq.gz
│   ├── a8394c5808f45f800fdabcca250910a43898bb10.nq.gz
│   ├── ab78d92e2ddf295f0fab6b17abcf1280de279a74.nq.gz
│   ├── acd275346a986319548bb8ea1ca01653ca6b1d83.nq.gz
│   ├── af861af2c47d4c14ce889b1cccb967d1dd3ff3f1.nq.gz
│   ├── afaf16de1630599935d34ca95ec67571d84415bf.nq.gz
│   ├── b144607b659503d03f3d176cb7dc16f03c38a253.nq.gz
│   ├── b1d321a862bd129f0cd8a4a742489f5ce98d60fe.nq.gz
│   ├── b7bc054454727a10cf1e57eed4604e0a637dbfa8.nq.gz
│   ├── bc00838f78b8aca234573eaa1c698e733291198e.nq.gz
│   ├── bc7570526cef773df447063ead96a1fcac4d249c.nq.gz
│   ├── bfaab66680559f2271074221f9bb2ddcdd4a0d0c.nq.gz
│   ├── c0c3896b605125218d714695f88b0f7985aac446.nq.gz
│   ├── c14bd8432d3205bd983ccd8b7e22096f8221c72c.nq.gz
│   ├── c24381fcbfa1bbbe82bf3c9c18c87cb4958b068d.nq.gz
│   ├── c4cf6eb48b641cf95720566bcdf31beb1b9dd9f6.nq.gz
│   ├── c50b7d82cc6613970582fea1c911ad845495ee0a.nq.gz
│   ├── c57ccde8416e8f1c048d6714cc2a3ef6c04e0e14.nq.gz
│   ├── c5b64a2afc1b6ac77ebd3224a4af80c0bb373016.nq.gz
│   ├── c697b3d634be684ecd2fbe1bf2c7e48d1a69c363.nq.gz
│   ├── c79f57650c273dff79d14badeeefaeb0411235ec.nq.gz
│   ├── cb03def72a2eec3f0220abd98158104901c26063.nq.gz
│   ├── ce0e618f26644a62e088e31e98acdee7d77cce7d.nq.gz
│   ├── ce25c395a89772aa37e2133082034a8be566c722.nq.gz
│   ├── d132fb7c8e516d7e9bdb3194983018828db844cf.nq.gz
│   ├── d22ef63bcec8c0fe0c0d2b87a0342cc581a6fdaf.nq.gz
│   ├── d26b9d1cf1cd4925a9b60a20ac6afc6460c6d1fe.nq.gz
│   ├── d481a59c967947911e78cc0b804b06412842cae0.nq.gz
│   ├── d78bfd23169aa5dcd6985777391280ee77498f5b.nq.gz
│   ├── d8137e1889b4ee652fa1c0d2b7a23b6e9cac17e6.nq.gz
│   ├── d8b7fa53363f3e610a1fa896d9a248ef3e300686.nq.gz
│   ├── da7e1b371bb8415da85bf8e25856c82683d71e29.nq.gz
│   ├── dcd6203575dffcffa22a8d2c4d7f4e76eb200f92.nq.gz
│   ├── df4c7891bef84b2d4a3d9be30b9f2c68873b3674.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e257e87262ea6ff346b15e250580a0b46003f9c3.nq.gz
│   ├── e32e6b5d79498f3d096e7109f04c846c1f861d17.nq.gz
│   ├── e4f46f0c0f946cf6d4566472a4718fb5a15ce506.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e5da32030aaebc574e86934b9109fb02bdb4a199.nq.gz
│   ├── e5e221cbac91211d795707eaa95e467e64eb8a12.nq.gz
│   ├── e5ef9caf4e30e40c86f968afb817927a1035c06e.nq.gz
│   ├── e8fc42b24b45f54ed0c6da4f61e9d9ed14535129.nq.gz
│   ├── eb79b77cfbb9ac8fc9ba94b8b53216b54577f26a.nq.gz
│   ├── ef59fc372119e9366d0546346ea9df3e70f9258b.nq.gz
│   ├── ef915654cb070add4908b79ba0400bd7f4686412.nq.gz
│   ├── f3c816506c0d3d617a51cd064f08956a6fbf9413.nq.gz
│   ├── f3c99a0aa1271a350a920aac2cedb1961fb1cb8e.nq.gz
│   ├── f4988f54502563723551569737c60d39cac953f0.nq.gz
│   ├── f4afafe966b7bb8c67af0b151a16390ea29a8bd6.nq.gz
│   ├── f4cdfce5bd56b0eb09c80bf574f80e2a6b62192a.nq.gz
│   ├── f63b2099152d19ce722f49f73d86f74c8cf574f8.nq.gz
│   ├── f63cd62dda722e4ab66b71b9511821f2d5078ad6.nq.gz
│   ├── f64d78fa9806e0cfdf00aa3987bb4f685c95fee1.nq.gz
│   ├── fd007066003dae6f594f83e5b83c1bf79d9363b6.nq.gz
│   └── ff82ca0db55e412e352b17d5326c7a75c53720b6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── de521d9a300dfc4814f8adb5c91a8c4ab52231aa.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 165 files
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

[xarray-contrib/xncml](https://github.com/xarray-contrib/xncml)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
