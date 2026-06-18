# Changelog

## 2.1.0 (2026-05-13)

Full Changelog: [v2.0.3...v2.1.0](https://github.com/sudoping01/djelia-sdk/compare/v2.0.3...v2.1.0)

### Features

* **client:** add custom JSON encoder for extended type support ([97220f7](https://github.com/sudoping01/djelia-sdk/commit/97220f7b3a7fef3b3b2ad808d2f689ef2408b910))


### Bug Fixes

* **deps:** bump minimum typing-extensions version ([a84caeb](https://github.com/sudoping01/djelia-sdk/commit/a84caeb4f0fb073edbaf3c77a5e0cf5ee0360c1a))
* **pydantic:** do not pass `by_alias` unless set ([ccfce59](https://github.com/sudoping01/djelia-sdk/commit/ccfce59a0752487c34f635560b3e90cce04f1a32))


### Chores

* **ci:** skip uploading artifacts on stainless-internal branches ([ec86b3f](https://github.com/sudoping01/djelia-sdk/commit/ec86b3f6074e1ab152598559d12455727b24b18f))
* **ci:** upgrade `actions/github-script` ([aaaa61b](https://github.com/sudoping01/djelia-sdk/commit/aaaa61b5970d2a4bb7ab4a8fc2e421be6f1cdf81))
* format all `api.md` files ([bfc26a7](https://github.com/sudoping01/djelia-sdk/commit/bfc26a746fad8af7f138d8ff3d12478844fef478))
* **internal:** add request options to SSE classes ([4c802da](https://github.com/sudoping01/djelia-sdk/commit/4c802da6d63198e403ca7198168a3d6561b82bac))
* **internal:** bump dependencies ([2eddbac](https://github.com/sudoping01/djelia-sdk/commit/2eddbac65ceb003c4205571b40feba15b0b56888))
* **internal:** codegen related update ([565a980](https://github.com/sudoping01/djelia-sdk/commit/565a98025a926a6c581b4365cc5f5cb43bc1c4ac))
* **internal:** codegen related update ([a7003f0](https://github.com/sudoping01/djelia-sdk/commit/a7003f0cdea969c5c0774bd8b3169e6e7040c8e6))
* **internal:** codegen related update ([d72a3c5](https://github.com/sudoping01/djelia-sdk/commit/d72a3c56c4d129b5f2cb3bf38ed876aa185749b0))
* **internal:** codegen related update ([f14df2a](https://github.com/sudoping01/djelia-sdk/commit/f14df2a8ac330cd1ee93f2aebd8b3a72872000f9))
* **internal:** codegen related update ([223c4dc](https://github.com/sudoping01/djelia-sdk/commit/223c4dccaf368e3ee279b844694d4093cb4f99ed))
* **internal:** codegen related update ([2f33d16](https://github.com/sudoping01/djelia-sdk/commit/2f33d1694b9e3ccb8cb73161033487153c32a4c5))
* **internal:** codegen related update ([0e160c5](https://github.com/sudoping01/djelia-sdk/commit/0e160c565ed1cc45877b34b1a8d61221a9462433))
* **internal:** codegen related update ([d1e34c1](https://github.com/sudoping01/djelia-sdk/commit/d1e34c1a056ad064acf6eb7f7fa8aa222643e74b))
* **internal:** codegen related update ([6c01755](https://github.com/sudoping01/djelia-sdk/commit/6c01755d41690050aa8fe51d2f24022f981d439a))
* **internal:** codegen related update ([38f3846](https://github.com/sudoping01/djelia-sdk/commit/38f38467967f9400e5dd0a9084cc401f5255498f))
* **internal:** codegen related update ([1acfb9d](https://github.com/sudoping01/djelia-sdk/commit/1acfb9dc1418c870ad25e842a07ed145c265797b))
* **internal:** codegen related update ([e4a0eda](https://github.com/sudoping01/djelia-sdk/commit/e4a0edae541bdc0d0023bff20bc787941dcfd791))
* **internal:** codegen related update ([9f9b697](https://github.com/sudoping01/djelia-sdk/commit/9f9b697220e67977e1a5239c6cf94b3d5c4eb5c0))
* **internal:** codegen related update ([0b9cb53](https://github.com/sudoping01/djelia-sdk/commit/0b9cb53dda82e90d986d040b1238f8ee2043d5b8))
* **internal:** fix lint error on Python 3.14 ([22edd75](https://github.com/sudoping01/djelia-sdk/commit/22edd759ac97ecd1996e96acc10c4df94365b6ab))
* **internal:** make `test_proxy_environment_variables` more resilient ([406da45](https://github.com/sudoping01/djelia-sdk/commit/406da4539f675f37a115225b3972e99326989dbf))
* **internal:** make `test_proxy_environment_variables` more resilient to env ([b95f25f](https://github.com/sudoping01/djelia-sdk/commit/b95f25f707e9de893ac9e7c65d5b14c1599b712e))
* **internal:** remove mock server code ([ffe9474](https://github.com/sudoping01/djelia-sdk/commit/ffe9474df0cd69ddcd02b799c15124cda88c3a5f))
* **internal:** tweak CI branches ([1033a3f](https://github.com/sudoping01/djelia-sdk/commit/1033a3f691625c20ddc71fd1f2fbd4e0a8808dee))
* **internal:** update `actions/checkout` version ([5e13eb3](https://github.com/sudoping01/djelia-sdk/commit/5e13eb37e206310604362d899af7a3b91d3e9e51))
* update mock server docs ([183399c](https://github.com/sudoping01/djelia-sdk/commit/183399c2e8f037183f8bbcba70eb28a46954c95f))
* update placeholder string ([17b1b46](https://github.com/sudoping01/djelia-sdk/commit/17b1b46c6c974c3bb7a7b5e77f3ade73151dbc7b))

## 2.0.3 (2026-01-14)

Full Changelog: [v2.0.2...v2.0.3](https://github.com/sudoping01/djelia-sdk/compare/v2.0.2...v2.0.3)

### Bug Fixes

* **compat:** update signatures of `model_dump` and `model_dump_json` for Pydantic v1 ([900e486](https://github.com/sudoping01/djelia-sdk/commit/900e486a0c6934193a45bec3a41ed5db179e0ee6))
* ensure streams are always closed ([0761d50](https://github.com/sudoping01/djelia-sdk/commit/0761d500eff6941db4803ab0c8daae17931785fc))
* **types:** allow pyright to infer TypedDict types within SequenceNotStr ([720049f](https://github.com/sudoping01/djelia-sdk/commit/720049f542e32cddbe290ef50ec8852788c70607))
* use async_to_httpx_files in patch method ([c6d3791](https://github.com/sudoping01/djelia-sdk/commit/c6d37919a5c5e91c80a78830992590f09ecdaff0))


### Chores

* add Python 3.14 classifier and testing ([61f5055](https://github.com/sudoping01/djelia-sdk/commit/61f5055ef13750b7b8a1e02275046ca7c02ac2cb))
* **deps:** mypy 1.18.1 has a regression, pin to 1.17 ([95ddb07](https://github.com/sudoping01/djelia-sdk/commit/95ddb077f3608a78df9885ccab6a0b194659bb47))
* **docs:** use environment variables for authentication in code snippets ([40573d4](https://github.com/sudoping01/djelia-sdk/commit/40573d4fe7e7000bf270d96b61ca93d0643c9260))
* **internal:** add `--fix` argument to lint script ([5725078](https://github.com/sudoping01/djelia-sdk/commit/57250783c3d71fd90ccab30c2ef352f86d909523))
* **internal:** add missing files argument to base client ([5346cc8](https://github.com/sudoping01/djelia-sdk/commit/5346cc8b9970fe036f2175d759970171ebbef6f9))
* **internal:** codegen related update ([1cfa197](https://github.com/sudoping01/djelia-sdk/commit/1cfa197a11184c82e965a0b1ad23dfa5f429c77a))
* **internal:** codegen related update ([7f9de1a](https://github.com/sudoping01/djelia-sdk/commit/7f9de1af2a8413975e152162e8021409849eb194))
* speedup initial import ([4dfc9a4](https://github.com/sudoping01/djelia-sdk/commit/4dfc9a40fea37dfd26ea3cf39e300d8f85fd2236))
* update lockfile ([b71c7a4](https://github.com/sudoping01/djelia-sdk/commit/b71c7a4d03b4cafe2d1150313c34535668c93dd0))

## 2.0.2 (2025-11-11)

Full Changelog: [v2.0.1...v2.0.2](https://github.com/sudoping01/djelia-sdk/compare/v2.0.1...v2.0.2)

### Bug Fixes

* compat with Python 3.14 ([76d8281](https://github.com/sudoping01/djelia-sdk/commit/76d82814f7f766674dd6712de2fdfd0389ba533b))


### Chores

* **internal:** grammar fix (it's -&gt; its) ([1251812](https://github.com/sudoping01/djelia-sdk/commit/1251812b7734204145b2bd7b1e25faeddbb8fde8))
* **package:** drop Python 3.8 support ([b5b6a6d](https://github.com/sudoping01/djelia-sdk/commit/b5b6a6dfedd415633b02f4de3cd6a44fca1aa4fb))

## 2.0.1 (2025-10-31)

Full Changelog: [v2.0.0...v2.0.1](https://github.com/sudoping01/djelia-sdk/compare/v2.0.0...v2.0.1)

### Bug Fixes

* **ci:** ensure pip is always available ([#15](https://github.com/sudoping01/djelia-sdk/issues/15)) ([4fa33f4](https://github.com/sudoping01/djelia-sdk/commit/4fa33f48f5f48dd9ef695a8599fd910e61af7655))
* **ci:** remove publishing patch ([#17](https://github.com/sudoping01/djelia-sdk/issues/17)) ([587c49d](https://github.com/sudoping01/djelia-sdk/commit/587c49dbdab201b82ee2a2566798f28ac6e903fb))
* **package:** support direct resource imports ([61a81f4](https://github.com/sudoping01/djelia-sdk/commit/61a81f40574bffcf90ef43a7e42ae863b513c8d9))
* **perf:** optimize some hot paths ([8d82ee9](https://github.com/sudoping01/djelia-sdk/commit/8d82ee9d21c6381bd604b04f92ecf8ec85227d2b))
* **perf:** skip traversing types for NotGiven values ([31b6a6b](https://github.com/sudoping01/djelia-sdk/commit/31b6a6b3ae20a0af4b2df859e0aaf243964145e1))
* **pydantic v1:** more robust ModelField.annotation check ([3cbbb83](https://github.com/sudoping01/djelia-sdk/commit/3cbbb838b1cfb698c10de09b0dc01c5f4b458a53))


### Chores

* broadly detect json family of content-type headers ([6e3053b](https://github.com/sudoping01/djelia-sdk/commit/6e3053b9d1036bf134bc6b0aa8b8efbe538a84a7))
* **ci:** add timeout thresholds for CI jobs ([2836802](https://github.com/sudoping01/djelia-sdk/commit/2836802205d9d4b99367b16e7f1c4c9f047cd893))
* **ci:** only use depot for staging repos ([d2a70fd](https://github.com/sudoping01/djelia-sdk/commit/d2a70fdd16e50c681ce65617add326b63457ccfb))
* **client:** minor internal fixes ([ffa4e81](https://github.com/sudoping01/djelia-sdk/commit/ffa4e81710a77684000b826b2a8bef513b03aa9c))
* fix typos ([#18](https://github.com/sudoping01/djelia-sdk/issues/18)) ([b8a135e](https://github.com/sudoping01/djelia-sdk/commit/b8a135eacc1edb875ea425a0ce63dadb3502bca3))
* **internal:** avoid errors for isinstance checks on proxies ([0eae842](https://github.com/sudoping01/djelia-sdk/commit/0eae84271c3249583e6cb6e6fe382a0dc7bd1c5c))
* **internal:** base client updates ([7cf7146](https://github.com/sudoping01/djelia-sdk/commit/7cf71467cb8902387d59e3108d38e9a6db367cac))
* **internal:** bump pyright version ([78eff09](https://github.com/sudoping01/djelia-sdk/commit/78eff0951ea23486cd69c74a052ff4025da5a64f))
* **internal:** codegen related update ([f2398e3](https://github.com/sudoping01/djelia-sdk/commit/f2398e322ee5b8bc93f681e945eee01169b61f88))
* **internal:** codegen related update ([e500eb9](https://github.com/sudoping01/djelia-sdk/commit/e500eb9911bb8a08d8790908f16fa121dc02de6b))
* **internal:** codegen related update ([28eb30f](https://github.com/sudoping01/djelia-sdk/commit/28eb30f6b3ff36f0c4891ea8d58f834c8eb4c817))
* **internal:** codegen related update ([e222aa7](https://github.com/sudoping01/djelia-sdk/commit/e222aa755a66cb9485d82f63ab7a722a2646b6d6))
* **internal:** codegen related update ([d85d835](https://github.com/sudoping01/djelia-sdk/commit/d85d83590f656e37b4f579e6607f716079fd9f22))
* **internal:** codegen related update ([853aa8e](https://github.com/sudoping01/djelia-sdk/commit/853aa8eb72445084d9bf34b7c887f98890b2f940))
* **internal:** expand CI branch coverage ([cb138d5](https://github.com/sudoping01/djelia-sdk/commit/cb138d5cd55716828fda795dc50fcaa542acd7f0))
* **internal:** fix list file params ([e7cadc8](https://github.com/sudoping01/djelia-sdk/commit/e7cadc84be2c90f1242d600cef324d7ca8a460d1))
* **internal:** import reformatting ([232c8d6](https://github.com/sudoping01/djelia-sdk/commit/232c8d6d5f4aa92b35266cdd6da6445f97693721))
* **internal:** minor formatting changes ([16ecae5](https://github.com/sudoping01/djelia-sdk/commit/16ecae5b9e029f36d6389d2193653e389b4a8104))
* **internal:** reduce CI branch coverage ([9797d47](https://github.com/sudoping01/djelia-sdk/commit/9797d47b81a3809c3650b49a64ce08e7cba19678))
* **internal:** refactor retries to not use recursion ([39e1237](https://github.com/sudoping01/djelia-sdk/commit/39e123735133c45c1dfe67bfddb60d452be37772))
* **internal:** remove trailing character ([#19](https://github.com/sudoping01/djelia-sdk/issues/19)) ([d7cab9b](https://github.com/sudoping01/djelia-sdk/commit/d7cab9bc3b69e176911223bf51229ee59da28b41))
* **internal:** slight transform perf improvement ([#20](https://github.com/sudoping01/djelia-sdk/issues/20)) ([ba61667](https://github.com/sudoping01/djelia-sdk/commit/ba61667890d587ae3748123045fe3ad6e73ce82d))
* **internal:** update models test ([4a1c643](https://github.com/sudoping01/djelia-sdk/commit/4a1c64361c9361781667cfde23cbe654c99aa4ca))
* **internal:** update pyright settings ([72bb640](https://github.com/sudoping01/djelia-sdk/commit/72bb6409a1882f06f49c48fcdc706fb3c245d612))
* slight wording improvement in README ([#21](https://github.com/sudoping01/djelia-sdk/issues/21)) ([6a57c4d](https://github.com/sudoping01/djelia-sdk/commit/6a57c4d763e5ab93eba6a08d64f5addc862ba402))

## 2.0.0 (2025-03-15)

Full Changelog: [v1.0.0...v2.0.0](https://github.com/sudoping01/djelia-sdk/compare/v1.0.0...v2.0.0)

### Bug Fixes

* **types:** handle more discriminated union shapes ([#13](https://github.com/sudoping01/djelia-sdk/issues/13)) ([7eec71a](https://github.com/sudoping01/djelia-sdk/commit/7eec71ab44c5f5eeef402dc78ef19f19759d684c))


### Chores

* **internal:** bump rye to 0.44.0 ([#12](https://github.com/sudoping01/djelia-sdk/issues/12)) ([857af0c](https://github.com/sudoping01/djelia-sdk/commit/857af0c1136335820a2d035e2ec7f04cea583907))
* **internal:** codegen related update ([#11](https://github.com/sudoping01/djelia-sdk/issues/11)) ([b97a8fb](https://github.com/sudoping01/djelia-sdk/commit/b97a8fbf64a31ffe51b119f8612549822dc6ff28))
* **internal:** remove extra empty newlines ([#10](https://github.com/sudoping01/djelia-sdk/issues/10)) ([4886a59](https://github.com/sudoping01/djelia-sdk/commit/4886a59685a417c2877b27b29c2e5dc87d7caf2d))

## 1.0.0 (2025-03-04)

Full Changelog: [v0.0.1-alpha.1...v1.0.0](https://github.com/sudoping01/djelia-sdk/compare/v0.0.1-alpha.1...v1.0.0)

### Chores

* **internal:** remove unused http client options forwarding ([#5](https://github.com/sudoping01/djelia-sdk/issues/5)) ([97ae641](https://github.com/sudoping01/djelia-sdk/commit/97ae64152cae5bcc43292dfb3c1c82984c843189))

## 0.0.1-alpha.1 (2025-03-02)

Full Changelog: [v0.0.1-alpha.0...v0.0.1-alpha.1](https://github.com/sudoping01/djelia-sdk/compare/v0.0.1-alpha.0...v0.0.1-alpha.1)

### Chores

* go live ([#1](https://github.com/sudoping01/djelia-sdk/issues/1)) ([91e114f](https://github.com/sudoping01/djelia-sdk/commit/91e114faf946bda753ac0aa96228818a7ff11652))
* update SDK settings ([#3](https://github.com/sudoping01/djelia-sdk/issues/3)) ([720c389](https://github.com/sudoping01/djelia-sdk/commit/720c38966654198bd9abe8a5695c197bc63e7813))
