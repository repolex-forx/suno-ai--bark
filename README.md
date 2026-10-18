# Repolex Knowledge Graph of suno-ai/bark

RDF knowledge graph data for [suno-ai/bark](https://github.com/suno-ai/bark), parsed by [repolex](https://repolex.ai).

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
rlex download suno-ai/bark
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f4f32d4cd480dfec1c245d258174bc9bde3c2148
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f4f32d4cd480dfec1c245d258174bc9bde3c2148
│           └── chunk-001.nq.gz
└── blob
    ├── 00d6c5108f35d87e7ee6f912968e4fe4a71bcbaf.nq.gz
    ├── 0119298a593d847b3a4ba189f8b3affdf76f89ad.nq.gz
    ├── 015b2e50b80113150e8816504f7fa651d1e19658.nq.gz
    ├── 02c352d24fa016d438054ce67627acc9f9670531.nq.gz
    ├── 034f9a8a0c3716bff7bb608327af51c6b53fabb8.nq.gz
    ├── 03b8f5fe2bb18070803c932e38eb2084e4978f3d.nq.gz
    ├── 0400ee475ff1777546066a2ad7be784ff27f45d0.nq.gz
    ├── 04917216e116937d5c726adddc25a7be70294e2d.nq.gz
    ├── 04d61487808c214c21f042ec4004444f0af749b2.nq.gz
    ├── 04fab128df4e14642de0c81a81d7b4ef9b093062.nq.gz
    ├── 04fdfaef11bf0cf6ee1d4f3d32cc6ff5f9186c27.nq.gz
    ├── 053ccc3883745ffbbfa18757c9aa0b4c750e64ab.nq.gz
    ├── 06ab86893dedba67e953fa8cf9fd801103ce4fe5.nq.gz
    ├── 0749da11c65223ebba14ad56ad3022eefa6a4710.nq.gz
    ├── 09755e71075c6abeed13f6431988d3afdd7a62a2.nq.gz
    ├── 09b86b13d3d0d14d5bf6e986777dc70425f22610.nq.gz
    ├── 09bfc6803d730fecf82aa178b79e5257d60336db.nq.gz
    ├── 09c60c3ddadc6590c59ba6bda705fde6b9e43e95.nq.gz
    ├── 0a10369ae442b890812c394dc783040595e73101.nq.gz
    ├── 0b775c51d2818ad0f1368bcabdd297d2499dec25.nq.gz
    ├── 0bd0db1dcde30fa2fb985620935d95f51f00b1b8.nq.gz
    ├── 0c973f56dd8beadd6fdaab33668ca3cef8c1a2bc.nq.gz
    ├── 0def7aa566975473468623de08a85497ff8b2331.nq.gz
    ├── 0e72810285befb7272657068880f06e0ca366de4.nq.gz
    ├── 0e7fb7a3a7fd1eabf52bd50c0f3e7966e64f3f9d.nq.gz
    ├── 0ff7d589f655ca2b22638e8cea0b78febe47085b.nq.gz
    ├── 115a523399f08acc93ecd204c68ff14c5188c004.nq.gz
    ├── 11877a1ed6dd4d8dc98ddf21dec02d59139dc61e.nq.gz
    ├── 11aac3a9d4e5b3e8f6c8251b275895142190a40e.nq.gz
    ├── 1205123c5ab04055772bbdaceb483fdeb8b367ce.nq.gz
    ├── 168840ab5e031e6cfbb1e09c668dcdc1a7b81e4b.nq.gz
    ├── 16d284bdc304b2d5adb79e424d3914e8e0880ce9.nq.gz
    ├── 16f4b43210f1ef52127c1c8a5c9a890f0c72f50e.nq.gz
    ├── 1868338a607ae526610734cac8688029f347f97b.nq.gz
    ├── 19a35c8868400483f0cfcaf9f84f4e35eff15539.nq.gz
    ├── 19c35279f131e42e3dc6d9a064f507f681d888f2.nq.gz
    ├── 1a5a545389b5750f05c7b5ff8936ef9c57847104.nq.gz
    ├── 1b92a37908e45b42195c080ea9b338267f3c0cdb.nq.gz
    ├── 1bf5c8d0e2b6e22cc6bdc2b9798c1ee0f0eb419d.nq.gz
    ├── 1c019161c1de4c9fdc5e5fa8a496bb2f184d7048.nq.gz
    ├── 1c3f19bb394d0e767a860060783ae0e4d3b6ee99.nq.gz
    ├── 1d02fd7eab13cc3c68223b7ba9753e9261ff4f36.nq.gz
    ├── 1d4eeda4c844627bb25e3800b41eeb845c19a49b.nq.gz
    ├── 1daabec95d379abd98dad9d8ab123ec527f85005.nq.gz
    ├── 1ee9aeebd398be0da8da5d0ce6db8f68e8990bce.nq.gz
    ├── 1fa0e6532c2ab9c6f4562a255f8d86b9f1f68ae9.nq.gz
    ├── 206953b1bbebb9f4b5650c16331fb09abc33d21c.nq.gz
    ├── 218920e8f6d0d6bd09e9830044314bb38d7f28b9.nq.gz
    ├── 2198310d4615ee76a8a39a8c7d15d0fb5bb96864.nq.gz
    ├── 21c8f0eca331e8efebca57746c96b70fe3261f1a.nq.gz
    ├── 252b02d93fe6fbe15bc4bb3ba5332237a0910fc3.nq.gz
    ├── 256c35773381611e38104ba3fdf47588c1399928.nq.gz
    ├── 26aef4dec4efc46dc0ed2fa97a02d0d052bed3c6.nq.gz
    ├── 270b0905c6c43dee3c04567495b0e73846e94a5a.nq.gz
    ├── 277ccc4299fca5364945d4318b4fcd09c1572d58.nq.gz
    ├── 28875e06cec1c9c4b4fb4b7b63b7f88d6a2ddf62.nq.gz
    ├── 289fbb973c58d2247ba494897380249384123398.nq.gz
    ├── 294c34d6e829cea0f91d0dd54de8cb90d39fa3c2.nq.gz
    ├── 2b1e2511ff2dfa3ac62626c637737e0fd70134f7.nq.gz
    ├── 2bc013eaa7af974162408149fb295ebe055aee9e.nq.gz
    ├── 2bdfc39cb32177c418c02114c9a8d92843cb71fd.nq.gz
    ├── 2befa5ab3541fa539fb3008d6f7bfd87cbed16b2.nq.gz
    ├── 2d74f31628e4ae977783e3b4aca9e79d48dd049a.nq.gz
    ├── 2e238f6ceb744763fa4edc4cdb13f59e0860e413.nq.gz
    ├── 2f016e7b501e5202801da13979c35e8b0e3af6df.nq.gz
    ├── 30b5a9499d8080870cf6b5d852dfef01ef087746.nq.gz
    ├── 311dc08cc543c4aa14c7a11471577b82731ae20d.nq.gz
    ├── 31969bb4168a3599a4e08ebf1d255a7ef6b81c31.nq.gz
    ├── 31e98c619f1b3ff76dc6c0fccdf95321b1306f80.nq.gz
    ├── 32047d114d1405b1ba0d3fe854f41432f1f15e60.nq.gz
    ├── 3245b43c132d0098da93fd22e4a5fd7089205bfb.nq.gz
    ├── 34b224a57b586e7f72682492095ca61c559ce480.nq.gz
    ├── 351a6935b5421059885ff99d59302ade340227f7.nq.gz
    ├── 3536913678148be54632bd621e5928c583a5efad.nq.gz
    ├── 381f175e52432f51fbb76e58589ad603ce4095f4.nq.gz
    ├── 38578beeca5c9d3c5e6dc0ad6291f4d3a7d4caa4.nq.gz
    ├── 3881e0d2b9d0091223db24bebd981f83658eab5a.nq.gz
    ├── 3ab57ab2a2d778575cacede5afd27857b9b2db4e.nq.gz
    ├── 3b086b30a7e0d584d8387cbef37abeb0f987542e.nq.gz
    ├── 3bb685e221d5389152c9fc5830f6667b8d39c905.nq.gz
    ├── 3bcbe4f42e14f35b6474cf2f6d52c735fccdc742.nq.gz
    ├── 3d1c4e93aef2f5dc41dfc1b3a92a7482b5dde284.nq.gz
    ├── 3e9100983953b0cd22f652dbe698e466a85c974d.nq.gz
    ├── 3eeedc2de50c55d100bd1d1fa94c4b917803ef4c.nq.gz
    ├── 3f2d224ab49e9f64aed769e421bf1b905e5683ef.nq.gz
    ├── 40715bbe66f9b5a4c4e87e7906fc0b7dff4fe9ed.nq.gz
    ├── 420a25dad2d55f5643905e73f2b0b2c8ac3381d4.nq.gz
    ├── 42d9690c4acfd5fb0ed37d29ade35ba08d740eed.nq.gz
    ├── 44d221818c567bcdcd48815ed9016bb6077ab555.nq.gz
    ├── 456453cd00fe3d2ce7214baa80790e954d0b5a41.nq.gz
    ├── 457b49e749f396c47c6b35f44955fd512d233d79.nq.gz
    ├── 46c86cddda32334cbd1626a17dbc38c702e13f48.nq.gz
    ├── 46d877f8b8f31f4a57997578a9ff3fe632112fa8.nq.gz
    ├── 47e4f753b28f462224cfd4b802a5102d3669491b.nq.gz
    ├── 48dbf19d4aad4c516df60e1cff2034901d83bcbd.nq.gz
    ├── 49a7f205f8439b8c431983d9b637dd3d290c618c.nq.gz
    ├── 49f268e80274dfabd421658436fd7720ac9a9c92.nq.gz
    ├── 4af14b5653f57cb9bc26c6e2ffeb903636ce684e.nq.gz
    ├── 4b9684dface3d084a41cd7496928111427bff829.nq.gz
    ├── 4c0b79fe96ec380489b500f78885c249a20587f0.nq.gz
    ├── 4cafccbafc79cf668801fe36c883a1a624f98913.nq.gz
    ├── 4d70146434b15ee4ad6e9e21cfdad43a5e46f140.nq.gz
    ├── 4e64e64c8ad7f53152a02fc0319df0bc08ac45fa.nq.gz
    ├── 4ea12b7744699f91c4a2650ccd4ef3ee8ea643e3.nq.gz
    ├── 4ec79c53611ba652a3820c5f9de2157e6e9ec0f9.nq.gz
    ├── 4f9974749e23f0e8f9cc0b2c2fbc9af4dfea3bf9.nq.gz
    ├── 50336bdbe7d1c0ee8ed1c6099606c58fe4b790b7.nq.gz
    ├── 512a231a7f071e8ef781011dee4b7c002c737f96.nq.gz
    ├── 512ff366f58013823a76e1d787324cb460d53373.nq.gz
    ├── 52dae0ee17675182f794a806c86aa6fb5c681930.nq.gz
    ├── 54f9870913576cb27436d9c7c29613aaed48e275.nq.gz
    ├── 55a8e82795b355e04230984888cf8198364480ca.nq.gz
    ├── 56afe3a96cf57ad3520aed2d20315b66a6fadd8a.nq.gz
    ├── 56b320bdd5b3bdea20edbab2426590c56cfcd477.nq.gz
    ├── 5770a701bf0b2ae45062b9940cba579eb05d7d42.nq.gz
    ├── 586d29fef5028fed8ee55e454eb21df4441c8c58.nq.gz
    ├── 59b110abdfac54cd448ba2ca33c98faad0aaaac8.nq.gz
    ├── 5b2605572d2cc82c7555d14de294a253f5d7c9ba.nq.gz
    ├── 5bc5c845c640b5f8d4924c267120298bb6651b56.nq.gz
    ├── 5c3f47a8e94842180ca764d032b6f5a8ed377c6b.nq.gz
    ├── 5e5077b90c7f758362a4ee5de40cbdd612add240.nq.gz
    ├── 5ead3a9b4c3591eb7957e603437a842cdd3629ac.nq.gz
    ├── 5f20543bb113820156509cdcb8e1c12f204a2a18.nq.gz
    ├── 60086b0f45cc6206b8a3450fbf21775115750e06.nq.gz
    ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
    ├── 6171e1d4006834c0f1d6d99f91c5329baebbc975.nq.gz
    ├── 64a8c615a42413c53b28c5a79ca309d66bac2d6c.nq.gz
    ├── 64c9d8c10f78ed3ab4aa625616959dbf73c49f2a.nq.gz
    ├── 654a8b8deb590802cf5256bc264777379b747bbe.nq.gz
    ├── 682aad2195cb97a9d372ca40ad587c9626c236db.nq.gz
    ├── 68a7df37f342443d46e44ef61feb78da0730ba42.nq.gz
    ├── 6a82e9a1541c1bdd4cc759f425d52d97b49287e6.nq.gz
    ├── 6b2742dc7523bceddbfe6c2f03fd937011f59ef5.nq.gz
    ├── 6b5a90bcd80f21c7116ae08d66522526fd5ae1b9.nq.gz
    ├── 6c1b234c8b0739f4890a4d8e69e4013055d4a2b2.nq.gz
    ├── 6c73ed3cb301e2d1c153e87405c6b482da4b9f02.nq.gz
    ├── 6d6be17e686dcdd98d447f5541b0693c912c3ff7.nq.gz
    ├── 6d6f51239c43f3e7741399035c13d6ead7b4ee5a.nq.gz
    ├── 6f733de3f2a735ae401e0e3d4cce1d903ece424a.nq.gz
    ├── 6fa2da19eef6ae80a69a329256e102df20485171.nq.gz
    ├── 7031a57bfcfc7492ce431e520177fe8f394cfe09.nq.gz
    ├── 7097600c86b35a34e8d500de8488a8fc81145625.nq.gz
    ├── 7216e42d113a9e3319214779aedaae9205e0df4d.nq.gz
    ├── 730698abc283e1d32a7e42487d1092fbb7dcbd55.nq.gz
    ├── 733ab922c034a3cd90699180bfd87da294ab018c.nq.gz
    ├── 74d4b464a354dab42dbc30e3c97c6734084d67db.nq.gz
    ├── 7510c4e2baf00ae9614f00048bee5bae3e06a9b8.nq.gz
    ├── 76a6f8d72942904bf742289b60a5b023e240690a.nq.gz
    ├── 76aa02ac542befa92526aba96e118308b71a4f8f.nq.gz
    ├── 78065865402bd616b56ebcb5441fb8498017c0f8.nq.gz
    ├── 7836e83fcc03151d20efad40bb0792de883b5baa.nq.gz
    ├── 7b646b7f03d060b52d0cd7063ee7aa955af65955.nq.gz
    ├── 7bf3bc5460ea9fde456725a0333e10a1476dc214.nq.gz
    ├── 7d2ef2ff1af93042551ffcb525d9229fd32234de.nq.gz
    ├── 7fae90cdf471ccaeedd70b50125cb841e1f7310c.nq.gz
    ├── 8037585aa7e0ae44732992ee8037cb5d467077fe.nq.gz
    ├── 80fcbd978e23e449b1df535d8240875c8e158643.nq.gz
    ├── 82888dd279734ac66f9d31a5c7cb24e62ded2d9a.nq.gz
    ├── 85ec6f4eb91b89ab7e0994e667abfaebbc076516.nq.gz
    ├── 862986ed8661e4122ac4ab30f741370556ed2022.nq.gz
    ├── 86cad7a76da0d0d342fa8250e364e40b77f68ecc.nq.gz
    ├── 8ab3c7e4e93d4899a87217edd3e5e1cb0371c658.nq.gz
    ├── 8ba83d9f0061f6c2e4a858f0bf02b396b11682e2.nq.gz
    ├── 8bb593d3be3e273da11b61befbda512a8e24b216.nq.gz
    ├── 8c3e56c79ea3a7c0e6cfee075aeb5f7fd14d538e.nq.gz
    ├── 8c593ef366e8a2e72a6dc3e3837647494aa97a32.nq.gz
    ├── 8ce81fc4e550c296dd6b2405ea08f489b42a9be5.nq.gz
    ├── 8f2c96e0795d572204d3469e07967e3517df80d6.nq.gz
    ├── 903460f1249623b8f3f81deaff7ee22555de30a0.nq.gz
    ├── 90510ffe031b9c420d818fb7571ac1e835da61f8.nq.gz
    ├── 9098a97edcc1a6e6a271d43618f84df6e943f561.nq.gz
    ├── 924af2271bd2b698b251cfd37ff05ab44bfb96f7.nq.gz
    ├── 96016df900d137afc6da4e32e39719692a5e8fcc.nq.gz
    ├── 981aa0587204aa1237fff1105eee843ead2ebb12.nq.gz
    ├── 9915e3438529c54169881e36e39f420bd45e926e.nq.gz
    ├── 9b8c2dbe978e3e09754d879a7ab6093175130a6a.nq.gz
    ├── 9c08f76976e6065e26b43100a5ea582a3bc0d25a.nq.gz
    ├── 9ccbd6e86ab8557d11f27381da0376658b62219e.nq.gz
    ├── 9d929baa89f58af80115094c6f2eac2e2345c27a.nq.gz
    ├── 9e4e401e944e8d87ae2e4fa3fc1a52816eabf289.nq.gz
    ├── a0417e896a0fa87692c8207b5b1db2ed1965cbc1.nq.gz
    ├── a134f395c11805e3f2042db9128b8f31bf848191.nq.gz
    ├── a1b1b842fce6d09d7953f95a3359bf4a3601a9b6.nq.gz
    ├── a33e3ba8aa51dfa0c79c197a70ee472e6d24784d.nq.gz
    ├── a486d791af81ce517c905633b444c798e60e5155.nq.gz
    ├── a5fdb00283323ca6e650cc2acdec58faefad3fbb.nq.gz
    ├── abd95d839ab4356bb1998550e41cc0e9e305c35d.nq.gz
    ├── abf79cbac3a66157699f94274f4b5c0cd0dfc790.nq.gz
    ├── ac035560488a341dfcd99e3cfcf69d58b8f9eb40.nq.gz
    ├── ac76151f6c76abb29c9aa5591afa4fa4678c9d30.nq.gz
    ├── ad62887c036fa67b997d360eefef31c5200c63fd.nq.gz
    ├── adbbdece213a5473d7a1c28db6a52d1fba892913.nq.gz
    ├── adc87744129f7d83f758f1061d8b2e01b2bc1897.nq.gz
    ├── adde4ecb23bd4ce69df0b7b88298b87590954cc2.nq.gz
    ├── b01ae915d015f80c164253ac79e5e97e9b6e04b5.nq.gz
    ├── b06af764da553b7d76e3e9fd11b9f8f39f81d4cb.nq.gz
    ├── b23695217b84c5ea57f34ce1e9ea8ed6f2e42d57.nq.gz
    └── b3c68574b86f3ffdc8677757b1fd2b3a0bc6d620.nq.gz

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

[suno-ai/bark](https://github.com/suno-ai/bark)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
