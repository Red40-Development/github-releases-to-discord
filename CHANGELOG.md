# Changelog

## [1.12.1](https://github.com/Red40-Development/github-releases-to-discord/compare/release-please-action-v1.12.1...release-please-action-v1.12.1) (2026-08-24)


### ⚠ BREAKING CHANGES

* use github token

### Features

* add function to convert PR, issue, and changelog links to markdown format ([07c2e1c](https://github.com/Red40-Development/github-releases-to-discord/commit/07c2e1c3e60591d601b5d4b5bd4fc90e599867f8)), closes [#32](https://github.com/Red40-Development/github-releases-to-discord/issues/32)
* add manual dispatch support for GitHub Actions to test Discord webhook integration with optional release inputs. resolves [#52](https://github.com/Red40-Development/github-releases-to-discord/issues/52) ([e15eb81](https://github.com/Red40-Development/github-releases-to-discord/commit/e15eb81a91d940818d60143a1f57edb92ae0828c))
* added action ([1c119cd](https://github.com/Red40-Development/github-releases-to-discord/commit/1c119cd58075c88793119ece6edfed7b02d46ef7))
* added additional description formatting ([#23](https://github.com/Red40-Development/github-releases-to-discord/issues/23)) ([8ca9da2](https://github.com/Red40-Development/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))
* added clip description at last newline ([#25](https://github.com/Red40-Development/github-releases-to-discord/issues/25)) ([97a4813](https://github.com/Red40-Development/github-releases-to-discord/commit/97a481333d0b902f599b12f03b47c4a6cbfa5e52))
* added dependencies and removed `.idea` ([fd59991](https://github.com/Red40-Development/github-releases-to-discord/commit/fd59991cc10608712b6e30a81f3cf0358c7dcf9d))
* added max_description option ([8ca9da2](https://github.com/Red40-Development/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))
* added reduce_headings option ([8ca9da2](https://github.com/Red40-Development/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))
* added release-please ([ad3716d](https://github.com/Red40-Development/github-releases-to-discord/commit/ad3716d4380d5008666794374928b6a73734a371))
* changed default action colour ([79005b2](https://github.com/Red40-Development/github-releases-to-discord/commit/79005b23fefce850957d37ba17ebb796dc81f6a1))
* created test action ([d76d7aa](https://github.com/Red40-Development/github-releases-to-discord/commit/d76d7aafe49eadfc8d388bef38a8d3fb0230041b))
* description trimming ([8ca9da2](https://github.com/Red40-Development/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))
* enhance reduceHeadings function to handle indented and closed markdown headings and add tests for new functionality. resolves [#51](https://github.com/Red40-Development/github-releases-to-discord/issues/51) ([80aca15](https://github.com/Red40-Development/github-releases-to-discord/commit/80aca15d7235082187d6eee6054a69ceed9c45db))
* **index.js:** enhance sendWebhook function to handle rate limits with retries for improved reliability when sending requests to Discord ([feb5a40](https://github.com/Red40-Development/github-releases-to-discord/commit/feb5a402377bc3da9cb9ea788964ece4e56f48cd))
* renamed all `colour`&gt;`color` ([a0914f4](https://github.com/Red40-Development/github-releases-to-discord/commit/a0914f433a5c2a2626ca39637851235fd4f7adea))
* **tests:** add Jest configuration and comprehensive tests for utility functions in index.js to ensure functionality and reliability ([0559b87](https://github.com/Red40-Development/github-releases-to-discord/commit/0559b87ee8fad6482e7ed4431329fd22f6593a9a))
* **tests:** add test for handling release payload with null body and update formatDescription to handle undefined input. resolves [#53](https://github.com/Red40-Development/github-releases-to-discord/issues/53) ([60ef92f](https://github.com/Red40-Development/github-releases-to-discord/commit/60ef92f1479987b509687244b04859040cb0f43d))
* updated `action.yml` ([e49c674](https://github.com/Red40-Development/github-releases-to-discord/commit/e49c674890cd5309d63bf570a550ffa0361c9ebc))
* updated `package.json` ([aea0a60](https://github.com/Red40-Development/github-releases-to-discord/commit/aea0a60ccd2456ae24e6ce7f21c1622a1b3ee18f))
* updated action ([b612527](https://github.com/Red40-Development/github-releases-to-discord/commit/b6125273330075a9f4de3e58f2fc7f52d85d4691))
* updated action ([1493174](https://github.com/Red40-Development/github-releases-to-discord/commit/1493174a77435e53b6a8aea6afb4db0cbbf96d9f))
* updated action colour ([ac2e4a3](https://github.com/Red40-Development/github-releases-to-discord/commit/ac2e4a38e2cad7e65dac53a1b4591fd46d65130d))
* updated action description format ([6cf9efb](https://github.com/Red40-Development/github-releases-to-discord/commit/6cf9efb8f65526de47e335b56163eef55b6b9a1c))
* updated action description format ([9c4c902](https://github.com/Red40-Development/github-releases-to-discord/commit/9c4c90246562bad1531cf41d44d3c037fbf869ee))
* updated action description format ([c517936](https://github.com/Red40-Development/github-releases-to-discord/commit/c517936fefb0119c0055d4d537bad23e647edd44))
* updated action description format ([7effb69](https://github.com/Red40-Development/github-releases-to-discord/commit/7effb69a75fd35dc53ea6dad5f3fa60cbd523ee7))
* updated action description format ([9f49b0c](https://github.com/Red40-Development/github-releases-to-discord/commit/9f49b0c9ab5de966ccc4af94863fbddd73bac884))
* updated description ([4517d8d](https://github.com/Red40-Development/github-releases-to-discord/commit/4517d8d0ec09c575248503c50ed25f15677f8f3d))
* updated description format ([a1d7a74](https://github.com/Red40-Development/github-releases-to-discord/commit/a1d7a74af90fcf8c00d341c8c665ca796b18c689))
* updated release-please ([0cea8a4](https://github.com/Red40-Development/github-releases-to-discord/commit/0cea8a493d5e12b1dc7414ecbed678f4671dda37))
* use github token ([fd23ac4](https://github.com/Red40-Development/github-releases-to-discord/commit/fd23ac44696011398a2240a5dd8c9d25df86121c))
* **workflow:** add GitHub Actions workflow to automatically update SemVer tags on tag push events ([e768ce1](https://github.com/Red40-Development/github-releases-to-discord/commit/e768ce10237a6100cccd7e80b2e994e9a2609150))


### Bug Fixes

* correct conversion of standalone PR, issue, and changelog URLs to markdown format ([4786949](https://github.com/Red40-Development/github-releases-to-discord/commit/47869497ed80cf0d6188692d82d71dff7a55dffe)), closes [#38](https://github.com/Red40-Development/github-releases-to-discord/issues/38)
* fixed `fetch` import ([0e4e0d8](https://github.com/Red40-Development/github-releases-to-discord/commit/0e4e0d83ffff90cef7bfae09cee4eb03aa1623d7))
* fixed ReferenceError on require  vs import ([233db9c](https://github.com/Red40-Development/github-releases-to-discord/commit/233db9c33f9059cbe008e61acf7f321e671f352c))
* fixed version tag ([baa4c82](https://github.com/Red40-Development/github-releases-to-discord/commit/baa4c82901455b2fbc18187cfa8f74f2a171f033))
* improve [@mention](https://github.com/mention) parsing for GitHub usernames ([#33](https://github.com/Red40-Development/github-releases-to-discord/issues/33)) ([925765f](https://github.com/Red40-Development/github-releases-to-discord/commit/925765f099dcdc3b12316eaa6dc3c17506734b51))


### Documentation

* add contribution guidelines to README.md ([5fd64bf](https://github.com/Red40-Development/github-releases-to-discord/commit/5fd64bf266cea87ab4952ef9a4c6aaf099f266bc))
* update README output example ([6aa0dd9](https://github.com/Red40-Development/github-releases-to-discord/commit/6aa0dd988c547f3b3a73463bc6e69d944621c613))
* update README with details on markdown link conversion and other features ([9737dc9](https://github.com/Red40-Development/github-releases-to-discord/commit/9737dc900274be227db48f8e23c715aa00b4af59))
* update version reference in README.md ([93d02ce](https://github.com/Red40-Development/github-releases-to-discord/commit/93d02ce8714c5f3e201f5b379422e978b837774b))
* updated README.md ([613ba26](https://github.com/Red40-Development/github-releases-to-discord/commit/613ba269d7fe40e97040da19de58b0ae00b47aaf))


### Styles

* parse common Github URLs to more appropriate display ([8ca9da2](https://github.com/Red40-Development/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))
* reduce consecutive whitespace/newlines into a minimum of 2 to allow separation in paragraphs ([8ca9da2](https://github.com/Red40-Development/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))


### Miscellaneous

* **actions:** bump actions ([8d2de15](https://github.com/Red40-Development/github-releases-to-discord/commit/8d2de153f572cc7678d548cc7a5cbd6cf130b700))
* added test envs to .gitignore ([735cca9](https://github.com/Red40-Development/github-releases-to-discord/commit/735cca9de37b345e69b0c74ff761610eab6f1fd1))
* added updated dependencies ([067d2cb](https://github.com/Red40-Development/github-releases-to-discord/commit/067d2cb017f609a202547b5dbb457d91cfb6cf0c))
* created LICENSE ([7f6cee8](https://github.com/Red40-Development/github-releases-to-discord/commit/7f6cee8772f08ef7067eef02b172fff17ae0dfb6))
* created LICENSE ([6382bf4](https://github.com/Red40-Development/github-releases-to-discord/commit/6382bf4bfbca909512e9e01a3d67a2683bd9839d))
* **master:** release 1.0.0 ([6480681](https://github.com/Red40-Development/github-releases-to-discord/commit/6480681d4812e6a2bd2629136d2401906b354e69))
* **master:** release 1.0.0 ([1c39103](https://github.com/Red40-Development/github-releases-to-discord/commit/1c39103034c0052617950ebf4e059951a2e79077))
* **master:** release 1.1.0 ([0eef0fe](https://github.com/Red40-Development/github-releases-to-discord/commit/0eef0fe7415ee2d6eed5fef0db1a0bfb59b12683))
* **master:** release 1.1.0 ([8b5e4a4](https://github.com/Red40-Development/github-releases-to-discord/commit/8b5e4a482d65f7a06f8e0eed847dde95a77d3d21))
* **master:** release 1.10.0 ([21e5e6a](https://github.com/Red40-Development/github-releases-to-discord/commit/21e5e6a51408d1c3d30de46b5320b0fcc719fe90))
* **master:** release 1.10.0 ([d97f233](https://github.com/Red40-Development/github-releases-to-discord/commit/d97f233291434632cbca68da382db2ee26ab9b0b))
* **master:** release 1.10.1 ([f84f12e](https://github.com/Red40-Development/github-releases-to-discord/commit/f84f12e7b0739723c2f0ce9c466df81351037cf2))
* **master:** release 1.10.1 ([c642050](https://github.com/Red40-Development/github-releases-to-discord/commit/c64205076b3ec2f4b0b707f129864b61bf104770))
* **master:** release 1.11.0 ([5001ed0](https://github.com/Red40-Development/github-releases-to-discord/commit/5001ed03b73d9b36253b9a493d4d4ffcc4ed4884))
* **master:** release 1.11.0 ([f7e8576](https://github.com/Red40-Development/github-releases-to-discord/commit/f7e857616686cdeb3938cbe3f8553a5618bf4969))
* **master:** release 1.11.1 ([8ebec0c](https://github.com/Red40-Development/github-releases-to-discord/commit/8ebec0c4c4ce7a9e0a1449e9438b98c00843886e))
* **master:** release 1.11.1 ([8212a24](https://github.com/Red40-Development/github-releases-to-discord/commit/8212a24dfa4b8ae7e11e7373b40d1cabbc1c418c))
* **master:** release 1.12.0 ([a5abfa0](https://github.com/Red40-Development/github-releases-to-discord/commit/a5abfa09d33ad8f1d702fb8f3db29f5fcbff7db8))
* **master:** release 1.12.0 ([a49a534](https://github.com/Red40-Development/github-releases-to-discord/commit/a49a5347be43b08077136f4455121db53ab999cf))
* **master:** release 1.12.1 ([d019e5a](https://github.com/Red40-Development/github-releases-to-discord/commit/d019e5acd9670e9ce10b47c8c100594356d59bb4))
* **master:** release 1.12.1 ([9e0e0c9](https://github.com/Red40-Development/github-releases-to-discord/commit/9e0e0c94dafeea2f3b904ae4cebcc328a09a36a7))
* **master:** release 1.13.0 ([#19](https://github.com/Red40-Development/github-releases-to-discord/issues/19)) ([c811a53](https://github.com/Red40-Development/github-releases-to-discord/commit/c811a53b57a60f3589ba5b1ea0648ae8472d5fcf))
* **master:** release 1.13.1 ([#21](https://github.com/Red40-Development/github-releases-to-discord/issues/21)) ([1ce3bed](https://github.com/Red40-Development/github-releases-to-discord/commit/1ce3bed332e216a51d8e617a0f20ac6ec60f53a3))
* **master:** release 1.14.0 ([#24](https://github.com/Red40-Development/github-releases-to-discord/issues/24)) ([b7c2077](https://github.com/Red40-Development/github-releases-to-discord/commit/b7c20771bd14c1e6bab134c125650ca7948f14b0))
* **master:** release 1.15.0 ([#26](https://github.com/Red40-Development/github-releases-to-discord/issues/26)) ([7de2fd1](https://github.com/Red40-Development/github-releases-to-discord/commit/7de2fd1c2a654b7fdff3a6bd23f6ec401f0966f9))
* **master:** release 1.15.1 ([#31](https://github.com/Red40-Development/github-releases-to-discord/issues/31)) ([37afa88](https://github.com/Red40-Development/github-releases-to-discord/commit/37afa88c8c9302a9307244b5a0d4e782d528a4b5))
* **master:** release 1.15.2 ([#35](https://github.com/Red40-Development/github-releases-to-discord/issues/35)) ([60a5c60](https://github.com/Red40-Development/github-releases-to-discord/commit/60a5c60e642b8ccffe16e782025f2c98e83d9f62))
* **master:** release 1.15.3 ([#36](https://github.com/Red40-Development/github-releases-to-discord/issues/36)) ([f184bc5](https://github.com/Red40-Development/github-releases-to-discord/commit/f184bc59c7a047bf04277729953c79637d0c4cc4))
* **master:** release 1.16.0 ([#37](https://github.com/Red40-Development/github-releases-to-discord/issues/37)) ([26399c6](https://github.com/Red40-Development/github-releases-to-discord/commit/26399c645d5aed4951be2d569b493f11ed440a65))
* **master:** release 1.16.1 ([#39](https://github.com/Red40-Development/github-releases-to-discord/issues/39)) ([1e7bdfd](https://github.com/Red40-Development/github-releases-to-discord/commit/1e7bdfd17373d338e99a46dbbc14fa90b29a2fe8))
* **master:** release 1.16.2 ([#40](https://github.com/Red40-Development/github-releases-to-discord/issues/40)) ([6ac5abe](https://github.com/Red40-Development/github-releases-to-discord/commit/6ac5abea42b8cbac14316970819a8a535aab08ea))
* **master:** release 1.17.0 ([#47](https://github.com/Red40-Development/github-releases-to-discord/issues/47)) ([e1dc082](https://github.com/Red40-Development/github-releases-to-discord/commit/e1dc0826fec1552949489f53220dd075c274d1a1))
* **master:** release 1.18.0 ([#49](https://github.com/Red40-Development/github-releases-to-discord/issues/49)) ([de60879](https://github.com/Red40-Development/github-releases-to-discord/commit/de60879a8653d2f24c11500da3af63b6f4507c4c))
* **master:** release 1.19.0 ([#50](https://github.com/Red40-Development/github-releases-to-discord/issues/50)) ([b96a335](https://github.com/Red40-Development/github-releases-to-discord/commit/b96a33520f8ad5e6dcdecee6f1212bdf88b16550))
* **master:** release 1.2.0 ([92a3719](https://github.com/Red40-Development/github-releases-to-discord/commit/92a3719c6247fe4fb6f274666adcfe20a4fbf9ef))
* **master:** release 1.2.0 ([e246e5d](https://github.com/Red40-Development/github-releases-to-discord/commit/e246e5daae5ec8cbbf57105b59aa7d5cebfadba9))
* **master:** release 1.20.0 ([#54](https://github.com/Red40-Development/github-releases-to-discord/issues/54)) ([24d1668](https://github.com/Red40-Development/github-releases-to-discord/commit/24d166886aee4646d448c8a389ff9e1ebcab3682))
* **master:** release 1.3.0 ([41e4a2f](https://github.com/Red40-Development/github-releases-to-discord/commit/41e4a2f6dc6d274c571358703465065efcba62ad))
* **master:** release 1.3.0 ([50fb830](https://github.com/Red40-Development/github-releases-to-discord/commit/50fb8302d6b4d903d521d8e0c0bb5bfb9e739b22))
* **master:** release 1.4.0 ([a9859d2](https://github.com/Red40-Development/github-releases-to-discord/commit/a9859d2b262226ac5a8ca881dc24897192ab807b))
* **master:** release 1.4.0 ([7cc064f](https://github.com/Red40-Development/github-releases-to-discord/commit/7cc064fafc544ac74ea395d779a8db960d833afb))
* **master:** release 1.5.0 ([65d8ff1](https://github.com/Red40-Development/github-releases-to-discord/commit/65d8ff13e2fdc00950048a71b1c613040552b498))
* **master:** release 1.5.0 ([e114cc7](https://github.com/Red40-Development/github-releases-to-discord/commit/e114cc793e1ebceb7163a20c2f705792e886f508))
* **master:** release 1.6.0 ([3bbff89](https://github.com/Red40-Development/github-releases-to-discord/commit/3bbff89e48762dcce7ab08658648159c5b4070aa))
* **master:** release 1.6.0 ([4de8705](https://github.com/Red40-Development/github-releases-to-discord/commit/4de8705e813c78a88551bf7059ab5f7a557cef85))
* **master:** release 1.7.0 ([d3640c3](https://github.com/Red40-Development/github-releases-to-discord/commit/d3640c3c29fa3343fdde9e730e5c4a82d76c325e))
* **master:** release 1.7.0 ([1f9e824](https://github.com/Red40-Development/github-releases-to-discord/commit/1f9e8245189c21b363aa3e158ab163a8b111a32f))
* **master:** release 1.8.0 ([a85b6a9](https://github.com/Red40-Development/github-releases-to-discord/commit/a85b6a9dbbb0abf4ffbe811692f9f3d5e795f8c1))
* **master:** release 1.8.0 ([c7879f8](https://github.com/Red40-Development/github-releases-to-discord/commit/c7879f8c698daea5aeda5c5ccb976f81bb497ebe))
* **master:** release 1.9.0 ([b8a34e1](https://github.com/Red40-Development/github-releases-to-discord/commit/b8a34e1c2bca603ae98300d287e0e9dacb652385))
* **master:** release 1.9.0 ([95e1e39](https://github.com/Red40-Development/github-releases-to-discord/commit/95e1e3916ae15da0b41932bc4fdf5df7e96d18cc))
* **master:** release release-please-action 1.12.1 ([5dc1cf3](https://github.com/Red40-Development/github-releases-to-discord/commit/5dc1cf3dbd5eca814c84494605df4c2d2c12295e))
* **master:** release release-please-action 1.12.1 ([99d99bd](https://github.com/Red40-Development/github-releases-to-discord/commit/99d99bdeeaa5a7e9212a977d6d7858fc4c0b4482))
* **package:** update @actions/github dependency to version 6.0.1 and add Jest as a dev dependency with a test script ([0559b87](https://github.com/Red40-Development/github-releases-to-discord/commit/0559b87ee8fad6482e7ed4431329fd22f6593a9a))
* release 1.12.1 ([6aea64b](https://github.com/Red40-Development/github-releases-to-discord/commit/6aea64bf70aca011417fed5000ff080269024a93))
* remove unnecessary test file from .gitignore and add sample test release JSON for local testing ([82d906c](https://github.com/Red40-Development/github-releases-to-discord/commit/82d906cc6f29adbe413b3f26b55deafc3f08ceee))
* update .gitignore ([3449e38](https://github.com/Red40-Development/github-releases-to-discord/commit/3449e38629b0c40dde5af524e2fef220dab24ead))
* update package-lock.json ([5dc4108](https://github.com/Red40-Development/github-releases-to-discord/commit/5dc41089e63d18b5b191533c34cdddeab34a07e8))
* update README for clarity and conciseness, improve formatting, and add new sections for better user guidance ([82d906c](https://github.com/Red40-Development/github-releases-to-discord/commit/82d906cc6f29adbe413b3f26b55deafc3f08ceee))
* update README.md ([254bf79](https://github.com/Red40-Development/github-releases-to-discord/commit/254bf7919618aea9ce0a3db67901010a20426def))
* updated action info ([c240910](https://github.com/Red40-Development/github-releases-to-discord/commit/c240910f8922fb8492346613f67a84811a0fdbac))
* updated action info ([c888953](https://github.com/Red40-Development/github-releases-to-discord/commit/c8889535c4a02efec3e8a6b26e1ee17fcd36ac7b))
* updated action workflow ([6a018dd](https://github.com/Red40-Development/github-releases-to-discord/commit/6a018ddca14eaee72d66a567024b76fc9649a10c))
* updated dependencies ([24b80ab](https://github.com/Red40-Development/github-releases-to-discord/commit/24b80abb6f9c71123456a908af5d3b92ccc755af))
* updated README.md ([ba06d83](https://github.com/Red40-Development/github-releases-to-discord/commit/ba06d833522e55d3453ee27bea9a7f3655378359))
* updated README.md ([ce7fc4a](https://github.com/Red40-Development/github-releases-to-discord/commit/ce7fc4a3be811af077c4f43dd005851d65204fb1))
* updated README.md ([27e9acb](https://github.com/Red40-Development/github-releases-to-discord/commit/27e9acb517b59220bb9c33e744b7ab27f5deaeb0))
* updated README.md ([6df6464](https://github.com/Red40-Development/github-releases-to-discord/commit/6df64644c13ab75b8b577d5f0cc5f5ac756c0c4f))
* updated README.md ([8c4da10](https://github.com/Red40-Development/github-releases-to-discord/commit/8c4da1075945cb7eb0217f443833f140bbe528ae))
* updated README.md ([b44c370](https://github.com/Red40-Development/github-releases-to-discord/commit/b44c37055556a21b736a477819d3c3ca15e22d79))
* updated release-please action ([933f3cf](https://github.com/Red40-Development/github-releases-to-discord/commit/933f3cffcf2139fcd71dddbb8bc76bc7cfa09170))
* updated test action ([305fe92](https://github.com/Red40-Development/github-releases-to-discord/commit/305fe9299dddb3a514f2b1692773570862c34d46))
* updated workflow action ([90120c3](https://github.com/Red40-Development/github-releases-to-discord/commit/90120c3a9d8e88088017feb7b69b706cc0bd5b50))
* updated workflow actions ([234bc3b](https://github.com/Red40-Development/github-releases-to-discord/commit/234bc3b25f3435aac40cfd4c3b3722f9d4461754))


### Code Refactoring

* added JSDocs, created more descriptive functions ([e67e0f9](https://github.com/Red40-Development/github-releases-to-discord/commit/e67e0f90643e0c80780bd401964491bb7823a213))
* bump deps and node24 ([e830983](https://github.com/Red40-Development/github-releases-to-discord/commit/e8309830a14f71e1a9ec3aa4abb31e9042af7993))
* code cleanup ([5ca1453](https://github.com/Red40-Development/github-releases-to-discord/commit/5ca1453a69f962930450a9f77d4e20cc37e4110f))
* rename variables returned from getContext ([a809bb6](https://github.com/Red40-Development/github-releases-to-discord/commit/a809bb6f0e31e04ebf82faf6e6d4f69b9d56492b))
* rename variables returned from getContext ([998060b](https://github.com/Red40-Development/github-releases-to-discord/commit/998060befe69aa05ff5bf23b6501efa0f1fe5739))

## [1.12.1](https://github.com/Red40-Development/github-releases-to-discord/compare/release-please-action-v1.20.0...release-please-action-v1.12.1) (2026-08-24)


### ⚠ BREAKING CHANGES

* use github token

### Features

* add function to convert PR, issue, and changelog links to markdown format ([07c2e1c](https://github.com/Red40-Development/github-releases-to-discord/commit/07c2e1c3e60591d601b5d4b5bd4fc90e599867f8)), closes [#32](https://github.com/Red40-Development/github-releases-to-discord/issues/32)
* add manual dispatch support for GitHub Actions to test Discord webhook integration with optional release inputs. resolves [#52](https://github.com/Red40-Development/github-releases-to-discord/issues/52) ([e15eb81](https://github.com/Red40-Development/github-releases-to-discord/commit/e15eb81a91d940818d60143a1f57edb92ae0828c))
* added action ([1c119cd](https://github.com/Red40-Development/github-releases-to-discord/commit/1c119cd58075c88793119ece6edfed7b02d46ef7))
* added additional description formatting ([#23](https://github.com/Red40-Development/github-releases-to-discord/issues/23)) ([8ca9da2](https://github.com/Red40-Development/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))
* added clip description at last newline ([#25](https://github.com/Red40-Development/github-releases-to-discord/issues/25)) ([97a4813](https://github.com/Red40-Development/github-releases-to-discord/commit/97a481333d0b902f599b12f03b47c4a6cbfa5e52))
* added dependencies and removed `.idea` ([fd59991](https://github.com/Red40-Development/github-releases-to-discord/commit/fd59991cc10608712b6e30a81f3cf0358c7dcf9d))
* added max_description option ([8ca9da2](https://github.com/Red40-Development/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))
* added reduce_headings option ([8ca9da2](https://github.com/Red40-Development/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))
* added release-please ([ad3716d](https://github.com/Red40-Development/github-releases-to-discord/commit/ad3716d4380d5008666794374928b6a73734a371))
* changed default action colour ([79005b2](https://github.com/Red40-Development/github-releases-to-discord/commit/79005b23fefce850957d37ba17ebb796dc81f6a1))
* created test action ([d76d7aa](https://github.com/Red40-Development/github-releases-to-discord/commit/d76d7aafe49eadfc8d388bef38a8d3fb0230041b))
* description trimming ([8ca9da2](https://github.com/Red40-Development/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))
* enhance reduceHeadings function to handle indented and closed markdown headings and add tests for new functionality. resolves [#51](https://github.com/Red40-Development/github-releases-to-discord/issues/51) ([80aca15](https://github.com/Red40-Development/github-releases-to-discord/commit/80aca15d7235082187d6eee6054a69ceed9c45db))
* **index.js:** enhance sendWebhook function to handle rate limits with retries for improved reliability when sending requests to Discord ([feb5a40](https://github.com/Red40-Development/github-releases-to-discord/commit/feb5a402377bc3da9cb9ea788964ece4e56f48cd))
* renamed all `colour`&gt;`color` ([a0914f4](https://github.com/Red40-Development/github-releases-to-discord/commit/a0914f433a5c2a2626ca39637851235fd4f7adea))
* **tests:** add Jest configuration and comprehensive tests for utility functions in index.js to ensure functionality and reliability ([0559b87](https://github.com/Red40-Development/github-releases-to-discord/commit/0559b87ee8fad6482e7ed4431329fd22f6593a9a))
* **tests:** add test for handling release payload with null body and update formatDescription to handle undefined input. resolves [#53](https://github.com/Red40-Development/github-releases-to-discord/issues/53) ([60ef92f](https://github.com/Red40-Development/github-releases-to-discord/commit/60ef92f1479987b509687244b04859040cb0f43d))
* updated `action.yml` ([e49c674](https://github.com/Red40-Development/github-releases-to-discord/commit/e49c674890cd5309d63bf570a550ffa0361c9ebc))
* updated `package.json` ([aea0a60](https://github.com/Red40-Development/github-releases-to-discord/commit/aea0a60ccd2456ae24e6ce7f21c1622a1b3ee18f))
* updated action ([b612527](https://github.com/Red40-Development/github-releases-to-discord/commit/b6125273330075a9f4de3e58f2fc7f52d85d4691))
* updated action ([1493174](https://github.com/Red40-Development/github-releases-to-discord/commit/1493174a77435e53b6a8aea6afb4db0cbbf96d9f))
* updated action colour ([ac2e4a3](https://github.com/Red40-Development/github-releases-to-discord/commit/ac2e4a38e2cad7e65dac53a1b4591fd46d65130d))
* updated action description format ([6cf9efb](https://github.com/Red40-Development/github-releases-to-discord/commit/6cf9efb8f65526de47e335b56163eef55b6b9a1c))
* updated action description format ([9c4c902](https://github.com/Red40-Development/github-releases-to-discord/commit/9c4c90246562bad1531cf41d44d3c037fbf869ee))
* updated action description format ([c517936](https://github.com/Red40-Development/github-releases-to-discord/commit/c517936fefb0119c0055d4d537bad23e647edd44))
* updated action description format ([7effb69](https://github.com/Red40-Development/github-releases-to-discord/commit/7effb69a75fd35dc53ea6dad5f3fa60cbd523ee7))
* updated action description format ([9f49b0c](https://github.com/Red40-Development/github-releases-to-discord/commit/9f49b0c9ab5de966ccc4af94863fbddd73bac884))
* updated description ([4517d8d](https://github.com/Red40-Development/github-releases-to-discord/commit/4517d8d0ec09c575248503c50ed25f15677f8f3d))
* updated description format ([a1d7a74](https://github.com/Red40-Development/github-releases-to-discord/commit/a1d7a74af90fcf8c00d341c8c665ca796b18c689))
* updated release-please ([0cea8a4](https://github.com/Red40-Development/github-releases-to-discord/commit/0cea8a493d5e12b1dc7414ecbed678f4671dda37))
* use github token ([fd23ac4](https://github.com/Red40-Development/github-releases-to-discord/commit/fd23ac44696011398a2240a5dd8c9d25df86121c))
* **workflow:** add GitHub Actions workflow to automatically update SemVer tags on tag push events ([e768ce1](https://github.com/Red40-Development/github-releases-to-discord/commit/e768ce10237a6100cccd7e80b2e994e9a2609150))


### Bug Fixes

* correct conversion of standalone PR, issue, and changelog URLs to markdown format ([4786949](https://github.com/Red40-Development/github-releases-to-discord/commit/47869497ed80cf0d6188692d82d71dff7a55dffe)), closes [#38](https://github.com/Red40-Development/github-releases-to-discord/issues/38)
* fixed `fetch` import ([0e4e0d8](https://github.com/Red40-Development/github-releases-to-discord/commit/0e4e0d83ffff90cef7bfae09cee4eb03aa1623d7))
* fixed ReferenceError on require  vs import ([233db9c](https://github.com/Red40-Development/github-releases-to-discord/commit/233db9c33f9059cbe008e61acf7f321e671f352c))
* fixed version tag ([baa4c82](https://github.com/Red40-Development/github-releases-to-discord/commit/baa4c82901455b2fbc18187cfa8f74f2a171f033))
* improve [@mention](https://github.com/mention) parsing for GitHub usernames ([#33](https://github.com/Red40-Development/github-releases-to-discord/issues/33)) ([925765f](https://github.com/Red40-Development/github-releases-to-discord/commit/925765f099dcdc3b12316eaa6dc3c17506734b51))


### Documentation

* add contribution guidelines to README.md ([5fd64bf](https://github.com/Red40-Development/github-releases-to-discord/commit/5fd64bf266cea87ab4952ef9a4c6aaf099f266bc))
* update README output example ([6aa0dd9](https://github.com/Red40-Development/github-releases-to-discord/commit/6aa0dd988c547f3b3a73463bc6e69d944621c613))
* update README with details on markdown link conversion and other features ([9737dc9](https://github.com/Red40-Development/github-releases-to-discord/commit/9737dc900274be227db48f8e23c715aa00b4af59))
* update version reference in README.md ([93d02ce](https://github.com/Red40-Development/github-releases-to-discord/commit/93d02ce8714c5f3e201f5b379422e978b837774b))
* updated README.md ([613ba26](https://github.com/Red40-Development/github-releases-to-discord/commit/613ba269d7fe40e97040da19de58b0ae00b47aaf))


### Styles

* parse common Github URLs to more appropriate display ([8ca9da2](https://github.com/Red40-Development/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))
* reduce consecutive whitespace/newlines into a minimum of 2 to allow separation in paragraphs ([8ca9da2](https://github.com/Red40-Development/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))


### Miscellaneous

* **actions:** bump actions ([8d2de15](https://github.com/Red40-Development/github-releases-to-discord/commit/8d2de153f572cc7678d548cc7a5cbd6cf130b700))
* added test envs to .gitignore ([735cca9](https://github.com/Red40-Development/github-releases-to-discord/commit/735cca9de37b345e69b0c74ff761610eab6f1fd1))
* added updated dependencies ([067d2cb](https://github.com/Red40-Development/github-releases-to-discord/commit/067d2cb017f609a202547b5dbb457d91cfb6cf0c))
* created LICENSE ([7f6cee8](https://github.com/Red40-Development/github-releases-to-discord/commit/7f6cee8772f08ef7067eef02b172fff17ae0dfb6))
* created LICENSE ([6382bf4](https://github.com/Red40-Development/github-releases-to-discord/commit/6382bf4bfbca909512e9e01a3d67a2683bd9839d))
* **master:** release 1.0.0 ([6480681](https://github.com/Red40-Development/github-releases-to-discord/commit/6480681d4812e6a2bd2629136d2401906b354e69))
* **master:** release 1.0.0 ([1c39103](https://github.com/Red40-Development/github-releases-to-discord/commit/1c39103034c0052617950ebf4e059951a2e79077))
* **master:** release 1.1.0 ([0eef0fe](https://github.com/Red40-Development/github-releases-to-discord/commit/0eef0fe7415ee2d6eed5fef0db1a0bfb59b12683))
* **master:** release 1.1.0 ([8b5e4a4](https://github.com/Red40-Development/github-releases-to-discord/commit/8b5e4a482d65f7a06f8e0eed847dde95a77d3d21))
* **master:** release 1.10.0 ([21e5e6a](https://github.com/Red40-Development/github-releases-to-discord/commit/21e5e6a51408d1c3d30de46b5320b0fcc719fe90))
* **master:** release 1.10.0 ([d97f233](https://github.com/Red40-Development/github-releases-to-discord/commit/d97f233291434632cbca68da382db2ee26ab9b0b))
* **master:** release 1.10.1 ([f84f12e](https://github.com/Red40-Development/github-releases-to-discord/commit/f84f12e7b0739723c2f0ce9c466df81351037cf2))
* **master:** release 1.10.1 ([c642050](https://github.com/Red40-Development/github-releases-to-discord/commit/c64205076b3ec2f4b0b707f129864b61bf104770))
* **master:** release 1.11.0 ([5001ed0](https://github.com/Red40-Development/github-releases-to-discord/commit/5001ed03b73d9b36253b9a493d4d4ffcc4ed4884))
* **master:** release 1.11.0 ([f7e8576](https://github.com/Red40-Development/github-releases-to-discord/commit/f7e857616686cdeb3938cbe3f8553a5618bf4969))
* **master:** release 1.11.1 ([8ebec0c](https://github.com/Red40-Development/github-releases-to-discord/commit/8ebec0c4c4ce7a9e0a1449e9438b98c00843886e))
* **master:** release 1.11.1 ([8212a24](https://github.com/Red40-Development/github-releases-to-discord/commit/8212a24dfa4b8ae7e11e7373b40d1cabbc1c418c))
* **master:** release 1.12.0 ([a5abfa0](https://github.com/Red40-Development/github-releases-to-discord/commit/a5abfa09d33ad8f1d702fb8f3db29f5fcbff7db8))
* **master:** release 1.12.0 ([a49a534](https://github.com/Red40-Development/github-releases-to-discord/commit/a49a5347be43b08077136f4455121db53ab999cf))
* **master:** release 1.12.1 ([d019e5a](https://github.com/Red40-Development/github-releases-to-discord/commit/d019e5acd9670e9ce10b47c8c100594356d59bb4))
* **master:** release 1.12.1 ([9e0e0c9](https://github.com/Red40-Development/github-releases-to-discord/commit/9e0e0c94dafeea2f3b904ae4cebcc328a09a36a7))
* **master:** release 1.13.0 ([#19](https://github.com/Red40-Development/github-releases-to-discord/issues/19)) ([c811a53](https://github.com/Red40-Development/github-releases-to-discord/commit/c811a53b57a60f3589ba5b1ea0648ae8472d5fcf))
* **master:** release 1.13.1 ([#21](https://github.com/Red40-Development/github-releases-to-discord/issues/21)) ([1ce3bed](https://github.com/Red40-Development/github-releases-to-discord/commit/1ce3bed332e216a51d8e617a0f20ac6ec60f53a3))
* **master:** release 1.14.0 ([#24](https://github.com/Red40-Development/github-releases-to-discord/issues/24)) ([b7c2077](https://github.com/Red40-Development/github-releases-to-discord/commit/b7c20771bd14c1e6bab134c125650ca7948f14b0))
* **master:** release 1.15.0 ([#26](https://github.com/Red40-Development/github-releases-to-discord/issues/26)) ([7de2fd1](https://github.com/Red40-Development/github-releases-to-discord/commit/7de2fd1c2a654b7fdff3a6bd23f6ec401f0966f9))
* **master:** release 1.15.1 ([#31](https://github.com/Red40-Development/github-releases-to-discord/issues/31)) ([37afa88](https://github.com/Red40-Development/github-releases-to-discord/commit/37afa88c8c9302a9307244b5a0d4e782d528a4b5))
* **master:** release 1.15.2 ([#35](https://github.com/Red40-Development/github-releases-to-discord/issues/35)) ([60a5c60](https://github.com/Red40-Development/github-releases-to-discord/commit/60a5c60e642b8ccffe16e782025f2c98e83d9f62))
* **master:** release 1.15.3 ([#36](https://github.com/Red40-Development/github-releases-to-discord/issues/36)) ([f184bc5](https://github.com/Red40-Development/github-releases-to-discord/commit/f184bc59c7a047bf04277729953c79637d0c4cc4))
* **master:** release 1.16.0 ([#37](https://github.com/Red40-Development/github-releases-to-discord/issues/37)) ([26399c6](https://github.com/Red40-Development/github-releases-to-discord/commit/26399c645d5aed4951be2d569b493f11ed440a65))
* **master:** release 1.16.1 ([#39](https://github.com/Red40-Development/github-releases-to-discord/issues/39)) ([1e7bdfd](https://github.com/Red40-Development/github-releases-to-discord/commit/1e7bdfd17373d338e99a46dbbc14fa90b29a2fe8))
* **master:** release 1.16.2 ([#40](https://github.com/Red40-Development/github-releases-to-discord/issues/40)) ([6ac5abe](https://github.com/Red40-Development/github-releases-to-discord/commit/6ac5abea42b8cbac14316970819a8a535aab08ea))
* **master:** release 1.17.0 ([#47](https://github.com/Red40-Development/github-releases-to-discord/issues/47)) ([e1dc082](https://github.com/Red40-Development/github-releases-to-discord/commit/e1dc0826fec1552949489f53220dd075c274d1a1))
* **master:** release 1.18.0 ([#49](https://github.com/Red40-Development/github-releases-to-discord/issues/49)) ([de60879](https://github.com/Red40-Development/github-releases-to-discord/commit/de60879a8653d2f24c11500da3af63b6f4507c4c))
* **master:** release 1.19.0 ([#50](https://github.com/Red40-Development/github-releases-to-discord/issues/50)) ([b96a335](https://github.com/Red40-Development/github-releases-to-discord/commit/b96a33520f8ad5e6dcdecee6f1212bdf88b16550))
* **master:** release 1.2.0 ([92a3719](https://github.com/Red40-Development/github-releases-to-discord/commit/92a3719c6247fe4fb6f274666adcfe20a4fbf9ef))
* **master:** release 1.2.0 ([e246e5d](https://github.com/Red40-Development/github-releases-to-discord/commit/e246e5daae5ec8cbbf57105b59aa7d5cebfadba9))
* **master:** release 1.20.0 ([#54](https://github.com/Red40-Development/github-releases-to-discord/issues/54)) ([24d1668](https://github.com/Red40-Development/github-releases-to-discord/commit/24d166886aee4646d448c8a389ff9e1ebcab3682))
* **master:** release 1.3.0 ([41e4a2f](https://github.com/Red40-Development/github-releases-to-discord/commit/41e4a2f6dc6d274c571358703465065efcba62ad))
* **master:** release 1.3.0 ([50fb830](https://github.com/Red40-Development/github-releases-to-discord/commit/50fb8302d6b4d903d521d8e0c0bb5bfb9e739b22))
* **master:** release 1.4.0 ([a9859d2](https://github.com/Red40-Development/github-releases-to-discord/commit/a9859d2b262226ac5a8ca881dc24897192ab807b))
* **master:** release 1.4.0 ([7cc064f](https://github.com/Red40-Development/github-releases-to-discord/commit/7cc064fafc544ac74ea395d779a8db960d833afb))
* **master:** release 1.5.0 ([65d8ff1](https://github.com/Red40-Development/github-releases-to-discord/commit/65d8ff13e2fdc00950048a71b1c613040552b498))
* **master:** release 1.5.0 ([e114cc7](https://github.com/Red40-Development/github-releases-to-discord/commit/e114cc793e1ebceb7163a20c2f705792e886f508))
* **master:** release 1.6.0 ([3bbff89](https://github.com/Red40-Development/github-releases-to-discord/commit/3bbff89e48762dcce7ab08658648159c5b4070aa))
* **master:** release 1.6.0 ([4de8705](https://github.com/Red40-Development/github-releases-to-discord/commit/4de8705e813c78a88551bf7059ab5f7a557cef85))
* **master:** release 1.7.0 ([d3640c3](https://github.com/Red40-Development/github-releases-to-discord/commit/d3640c3c29fa3343fdde9e730e5c4a82d76c325e))
* **master:** release 1.7.0 ([1f9e824](https://github.com/Red40-Development/github-releases-to-discord/commit/1f9e8245189c21b363aa3e158ab163a8b111a32f))
* **master:** release 1.8.0 ([a85b6a9](https://github.com/Red40-Development/github-releases-to-discord/commit/a85b6a9dbbb0abf4ffbe811692f9f3d5e795f8c1))
* **master:** release 1.8.0 ([c7879f8](https://github.com/Red40-Development/github-releases-to-discord/commit/c7879f8c698daea5aeda5c5ccb976f81bb497ebe))
* **master:** release 1.9.0 ([b8a34e1](https://github.com/Red40-Development/github-releases-to-discord/commit/b8a34e1c2bca603ae98300d287e0e9dacb652385))
* **master:** release 1.9.0 ([95e1e39](https://github.com/Red40-Development/github-releases-to-discord/commit/95e1e3916ae15da0b41932bc4fdf5df7e96d18cc))
* **package:** update @actions/github dependency to version 6.0.1 and add Jest as a dev dependency with a test script ([0559b87](https://github.com/Red40-Development/github-releases-to-discord/commit/0559b87ee8fad6482e7ed4431329fd22f6593a9a))
* release 1.12.1 ([6aea64b](https://github.com/Red40-Development/github-releases-to-discord/commit/6aea64bf70aca011417fed5000ff080269024a93))
* remove unnecessary test file from .gitignore and add sample test release JSON for local testing ([82d906c](https://github.com/Red40-Development/github-releases-to-discord/commit/82d906cc6f29adbe413b3f26b55deafc3f08ceee))
* update .gitignore ([3449e38](https://github.com/Red40-Development/github-releases-to-discord/commit/3449e38629b0c40dde5af524e2fef220dab24ead))
* update package-lock.json ([5dc4108](https://github.com/Red40-Development/github-releases-to-discord/commit/5dc41089e63d18b5b191533c34cdddeab34a07e8))
* update README for clarity and conciseness, improve formatting, and add new sections for better user guidance ([82d906c](https://github.com/Red40-Development/github-releases-to-discord/commit/82d906cc6f29adbe413b3f26b55deafc3f08ceee))
* update README.md ([254bf79](https://github.com/Red40-Development/github-releases-to-discord/commit/254bf7919618aea9ce0a3db67901010a20426def))
* updated action info ([c240910](https://github.com/Red40-Development/github-releases-to-discord/commit/c240910f8922fb8492346613f67a84811a0fdbac))
* updated action info ([c888953](https://github.com/Red40-Development/github-releases-to-discord/commit/c8889535c4a02efec3e8a6b26e1ee17fcd36ac7b))
* updated action workflow ([6a018dd](https://github.com/Red40-Development/github-releases-to-discord/commit/6a018ddca14eaee72d66a567024b76fc9649a10c))
* updated dependencies ([24b80ab](https://github.com/Red40-Development/github-releases-to-discord/commit/24b80abb6f9c71123456a908af5d3b92ccc755af))
* updated README.md ([ba06d83](https://github.com/Red40-Development/github-releases-to-discord/commit/ba06d833522e55d3453ee27bea9a7f3655378359))
* updated README.md ([ce7fc4a](https://github.com/Red40-Development/github-releases-to-discord/commit/ce7fc4a3be811af077c4f43dd005851d65204fb1))
* updated README.md ([27e9acb](https://github.com/Red40-Development/github-releases-to-discord/commit/27e9acb517b59220bb9c33e744b7ab27f5deaeb0))
* updated README.md ([6df6464](https://github.com/Red40-Development/github-releases-to-discord/commit/6df64644c13ab75b8b577d5f0cc5f5ac756c0c4f))
* updated README.md ([8c4da10](https://github.com/Red40-Development/github-releases-to-discord/commit/8c4da1075945cb7eb0217f443833f140bbe528ae))
* updated README.md ([b44c370](https://github.com/Red40-Development/github-releases-to-discord/commit/b44c37055556a21b736a477819d3c3ca15e22d79))
* updated release-please action ([933f3cf](https://github.com/Red40-Development/github-releases-to-discord/commit/933f3cffcf2139fcd71dddbb8bc76bc7cfa09170))
* updated test action ([305fe92](https://github.com/Red40-Development/github-releases-to-discord/commit/305fe9299dddb3a514f2b1692773570862c34d46))
* updated workflow action ([90120c3](https://github.com/Red40-Development/github-releases-to-discord/commit/90120c3a9d8e88088017feb7b69b706cc0bd5b50))
* updated workflow actions ([234bc3b](https://github.com/Red40-Development/github-releases-to-discord/commit/234bc3b25f3435aac40cfd4c3b3722f9d4461754))


### Code Refactoring

* added JSDocs, created more descriptive functions ([e67e0f9](https://github.com/Red40-Development/github-releases-to-discord/commit/e67e0f90643e0c80780bd401964491bb7823a213))
* bump deps and node24 ([e830983](https://github.com/Red40-Development/github-releases-to-discord/commit/e8309830a14f71e1a9ec3aa4abb31e9042af7993))
* code cleanup ([5ca1453](https://github.com/Red40-Development/github-releases-to-discord/commit/5ca1453a69f962930450a9f77d4e20cc37e4110f))
* rename variables returned from getContext ([a809bb6](https://github.com/Red40-Development/github-releases-to-discord/commit/a809bb6f0e31e04ebf82faf6e6d4f69b9d56492b))
* rename variables returned from getContext ([998060b](https://github.com/Red40-Development/github-releases-to-discord/commit/998060befe69aa05ff5bf23b6501efa0f1fe5739))

## [1.20.0](https://github.com/SethCohen/github-releases-to-discord/compare/v1.19.0...v1.20.0) (2026-04-03)


### Features

* add manual dispatch support for GitHub Actions to test Discord webhook integration with optional release inputs. resolves [#52](https://github.com/SethCohen/github-releases-to-discord/issues/52) ([e15eb81](https://github.com/SethCohen/github-releases-to-discord/commit/e15eb81a91d940818d60143a1f57edb92ae0828c))
* enhance reduceHeadings function to handle indented and closed markdown headings and add tests for new functionality. resolves [#51](https://github.com/SethCohen/github-releases-to-discord/issues/51) ([80aca15](https://github.com/SethCohen/github-releases-to-discord/commit/80aca15d7235082187d6eee6054a69ceed9c45db))
* **tests:** add test for handling release payload with null body and update formatDescription to handle undefined input. resolves [#53](https://github.com/SethCohen/github-releases-to-discord/issues/53) ([60ef92f](https://github.com/SethCohen/github-releases-to-discord/commit/60ef92f1479987b509687244b04859040cb0f43d))

## [1.19.0](https://github.com/SethCohen/github-releases-to-discord/compare/v1.18.0...v1.19.0) (2025-06-17)


### Features

* **tests:** add Jest configuration and comprehensive tests for utility functions in index.js to ensure functionality and reliability ([0559b87](https://github.com/SethCohen/github-releases-to-discord/commit/0559b87ee8fad6482e7ed4431329fd22f6593a9a))


### Miscellaneous

* added updated dependencies ([067d2cb](https://github.com/SethCohen/github-releases-to-discord/commit/067d2cb017f609a202547b5dbb457d91cfb6cf0c))
* **package:** update @actions/github dependency to version 6.0.1 and add Jest as a dev dependency with a test script ([0559b87](https://github.com/SethCohen/github-releases-to-discord/commit/0559b87ee8fad6482e7ed4431329fd22f6593a9a))

## [1.18.0](https://github.com/SethCohen/github-releases-to-discord/compare/v1.17.0...v1.18.0) (2025-06-17)


### Features

* **index.js:** enhance sendWebhook function to handle rate limits with retries for improved reliability when sending requests to Discord ([feb5a40](https://github.com/SethCohen/github-releases-to-discord/commit/feb5a402377bc3da9cb9ea788964ece4e56f48cd))


### Miscellaneous

* remove unnecessary test file from .gitignore and add sample test release JSON for local testing ([82d906c](https://github.com/SethCohen/github-releases-to-discord/commit/82d906cc6f29adbe413b3f26b55deafc3f08ceee))
* update README for clarity and conciseness, improve formatting, and add new sections for better user guidance ([82d906c](https://github.com/SethCohen/github-releases-to-discord/commit/82d906cc6f29adbe413b3f26b55deafc3f08ceee))

## [1.17.0](https://github.com/SethCohen/github-releases-to-discord/compare/v1.16.2...v1.17.0) (2025-06-17)


### Features

* **workflow:** add GitHub Actions workflow to automatically update SemVer tags on tag push events ([e768ce1](https://github.com/SethCohen/github-releases-to-discord/commit/e768ce10237a6100cccd7e80b2e994e9a2609150))

## [1.16.2](https://github.com/SethCohen/github-releases-to-discord/compare/v1.16.1...v1.16.2) (2024-10-18)


### Documentation

* update README output example ([6aa0dd9](https://github.com/SethCohen/github-releases-to-discord/commit/6aa0dd988c547f3b3a73463bc6e69d944621c613))

## [1.16.1](https://github.com/SethCohen/github-releases-to-discord/compare/v1.16.0...v1.16.1) (2024-10-18)


### Bug Fixes

* correct conversion of standalone PR, issue, and changelog URLs to markdown format ([4786949](https://github.com/SethCohen/github-releases-to-discord/commit/47869497ed80cf0d6188692d82d71dff7a55dffe)), closes [#38](https://github.com/SethCohen/github-releases-to-discord/issues/38)


### Documentation

* update README with details on markdown link conversion and other features ([9737dc9](https://github.com/SethCohen/github-releases-to-discord/commit/9737dc900274be227db48f8e23c715aa00b4af59))

## [1.16.0](https://github.com/SethCohen/github-releases-to-discord/compare/v1.15.3...v1.16.0) (2024-10-18)


### Features

* add function to convert PR, issue, and changelog links to markdown format ([07c2e1c](https://github.com/SethCohen/github-releases-to-discord/commit/07c2e1c3e60591d601b5d4b5bd4fc90e599867f8)), closes [#32](https://github.com/SethCohen/github-releases-to-discord/issues/32)

## [1.15.3](https://github.com/SethCohen/github-releases-to-discord/compare/v1.15.2...v1.15.3) (2024-10-18)


### Documentation

* add contribution guidelines to README.md ([5fd64bf](https://github.com/SethCohen/github-releases-to-discord/commit/5fd64bf266cea87ab4952ef9a4c6aaf099f266bc))
* update version reference in README.md ([93d02ce](https://github.com/SethCohen/github-releases-to-discord/commit/93d02ce8714c5f3e201f5b379422e978b837774b))


### Miscellaneous

* update .gitignore ([3449e38](https://github.com/SethCohen/github-releases-to-discord/commit/3449e38629b0c40dde5af524e2fef220dab24ead))
* update package-lock.json ([5dc4108](https://github.com/SethCohen/github-releases-to-discord/commit/5dc41089e63d18b5b191533c34cdddeab34a07e8))

## [1.15.2](https://github.com/SethCohen/github-releases-to-discord/compare/v1.15.1...v1.15.2) (2024-10-18)


### Bug Fixes

* improve [@mention](https://github.com/mention) parsing for GitHub usernames ([#33](https://github.com/SethCohen/github-releases-to-discord/issues/33)) ([925765f](https://github.com/SethCohen/github-releases-to-discord/commit/925765f099dcdc3b12316eaa6dc3c17506734b51))

## [1.15.1](https://github.com/SethCohen/github-releases-to-discord/compare/v1.15.0...v1.15.1) (2024-10-04)


### Documentation

* updated README.md ([613ba26](https://github.com/SethCohen/github-releases-to-discord/commit/613ba269d7fe40e97040da19de58b0ae00b47aaf))


### Miscellaneous

* added test envs to .gitignore ([735cca9](https://github.com/SethCohen/github-releases-to-discord/commit/735cca9de37b345e69b0c74ff761610eab6f1fd1))
* updated test action ([305fe92](https://github.com/SethCohen/github-releases-to-discord/commit/305fe9299dddb3a514f2b1692773570862c34d46))


### Code Refactoring

* code cleanup ([5ca1453](https://github.com/SethCohen/github-releases-to-discord/commit/5ca1453a69f962930450a9f77d4e20cc37e4110f))

## [1.15.0](https://github.com/SethCohen/github-releases-to-discord/compare/v1.14.0...v1.15.0) (2023-12-14)


### Features

* added clip description at last newline ([#25](https://github.com/SethCohen/github-releases-to-discord/issues/25)) ([97a4813](https://github.com/SethCohen/github-releases-to-discord/commit/97a481333d0b902f599b12f03b47c4a6cbfa5e52))

## [1.14.0](https://github.com/SethCohen/github-releases-to-discord/compare/v1.13.1...v1.14.0) (2023-12-11)


### Features

* added additional description formatting ([#23](https://github.com/SethCohen/github-releases-to-discord/issues/23)) ([8ca9da2](https://github.com/SethCohen/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))
* added max_description option ([8ca9da2](https://github.com/SethCohen/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))
* added reduce_headings option ([8ca9da2](https://github.com/SethCohen/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))
* description trimming ([8ca9da2](https://github.com/SethCohen/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))


### Styles

* parse common Github URLs to more appropriate display ([8ca9da2](https://github.com/SethCohen/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))
* reduce consecutive whitespace/newlines into a minimum of 2 to allow separation in paragraphs ([8ca9da2](https://github.com/SethCohen/github-releases-to-discord/commit/8ca9da2ca8e3435ee9b0d387355c0fae255c16b0))


### Miscellaneous

* update README.md ([254bf79](https://github.com/SethCohen/github-releases-to-discord/commit/254bf7919618aea9ce0a3db67901010a20426def))

## [1.13.1](https://github.com/SethCohen/github-releases-to-discord/compare/v1.13.0...v1.13.1) (2023-09-23)


### Miscellaneous

* updated action info ([c240910](https://github.com/SethCohen/github-releases-to-discord/commit/c240910f8922fb8492346613f67a84811a0fdbac))
* updated action info ([c888953](https://github.com/SethCohen/github-releases-to-discord/commit/c8889535c4a02efec3e8a6b26e1ee17fcd36ac7b))
* updated dependencies ([24b80ab](https://github.com/SethCohen/github-releases-to-discord/commit/24b80abb6f9c71123456a908af5d3b92ccc755af))
* updated README.md ([ba06d83](https://github.com/SethCohen/github-releases-to-discord/commit/ba06d833522e55d3453ee27bea9a7f3655378359))
* updated README.md ([ce7fc4a](https://github.com/SethCohen/github-releases-to-discord/commit/ce7fc4a3be811af077c4f43dd005851d65204fb1))
* updated release-please action ([933f3cf](https://github.com/SethCohen/github-releases-to-discord/commit/933f3cffcf2139fcd71dddbb8bc76bc7cfa09170))

## [1.13.0](https://github.com/SethCohen/github-release-to-discord/compare/v1.12.1...v1.13.0) (2022-08-25)


### Features

* created test action ([d76d7aa](https://github.com/SethCohen/github-release-to-discord/commit/d76d7aafe49eadfc8d388bef38a8d3fb0230041b))

## [1.12.1](https://github.com/SethCohen/github-release-to-discord/compare/v1.12.0...v1.12.1) (2022-08-24)


### Miscellaneous Chores

* release 1.12.1 ([6aea64b](https://github.com/SethCohen/github-release-to-discord/commit/6aea64bf70aca011417fed5000ff080269024a93))

## [1.12.0](https://github.com/SethCohen/github-release-to-discord/compare/v1.11.1...v1.12.0) (2022-08-24)


### Features

* renamed all `colour`>`color` ([a0914f4](https://github.com/SethCohen/github-release-to-discord/commit/a0914f433a5c2a2626ca39637851235fd4f7adea))

## [1.11.1](https://github.com/SethCohen/github-release-to-discord/compare/v1.11.0...v1.11.1) (2022-08-24)


### Bug Fixes

* fixed ReferenceError on require  vs import ([233db9c](https://github.com/SethCohen/github-release-to-discord/commit/233db9c33f9059cbe008e61acf7f321e671f352c))

## [1.11.0](https://github.com/SethCohen/github-release-to-discord/compare/v1.10.1...v1.11.0) (2022-08-24)


### Features

* updated `action.yml` ([e49c674](https://github.com/SethCohen/github-release-to-discord/commit/e49c674890cd5309d63bf570a550ffa0361c9ebc))
* updated `package.json` ([aea0a60](https://github.com/SethCohen/github-release-to-discord/commit/aea0a60ccd2456ae24e6ce7f21c1622a1b3ee18f))


### Bug Fixes

* fixed version tag ([baa4c82](https://github.com/SethCohen/github-release-to-discord/commit/baa4c82901455b2fbc18187cfa8f74f2a171f033))

## [1.10.0](https://github.com/SethCohen/github-release-to-discord/compare/v1.9.0...v1.10.0) (2022-08-24)


### Features

* added dependencies and removed `.idea` ([fd59991](https://github.com/SethCohen/github-release-to-discord/commit/fd59991cc10608712b6e30a81f3cf0358c7dcf9d))

## [1.9.0](https://github.com/SethCohen/github-release-to-discord/compare/v1.8.0...v1.9.0) (2022-08-24)


### Features

* updated action description format ([6cf9efb](https://github.com/SethCohen/github-release-to-discord/commit/6cf9efb8f65526de47e335b56163eef55b6b9a1c))

## [1.8.0](https://github.com/SethCohen/github-release-to-discord/compare/v1.7.0...v1.8.0) (2022-08-24)


### Features

* updated action description format ([9c4c902](https://github.com/SethCohen/github-release-to-discord/commit/9c4c90246562bad1531cf41d44d3c037fbf869ee))

## [1.7.0](https://github.com/SethCohen/github-release-to-discord/compare/v1.6.0...v1.7.0) (2022-08-24)


### Features

* updated action description format ([c517936](https://github.com/SethCohen/github-release-to-discord/commit/c517936fefb0119c0055d4d537bad23e647edd44))

## [1.6.0](https://github.com/SethCohen/github-release-to-discord/compare/v1.5.0...v1.6.0) (2022-08-24)


### Features

* updated action description format ([7effb69](https://github.com/SethCohen/github-release-to-discord/commit/7effb69a75fd35dc53ea6dad5f3fa60cbd523ee7))

## [1.5.0](https://github.com/SethCohen/github-release-to-discord/compare/v1.4.0...v1.5.0) (2022-08-24)


### Features

* updated action description format ([9f49b0c](https://github.com/SethCohen/github-release-to-discord/commit/9f49b0c9ab5de966ccc4af94863fbddd73bac884))

## [1.4.0](https://github.com/SethCohen/github-release-to-discord/compare/v1.3.0...v1.4.0) (2022-08-24)


### Features

* updated action colour ([ac2e4a3](https://github.com/SethCohen/github-release-to-discord/commit/ac2e4a38e2cad7e65dac53a1b4591fd46d65130d))
* updated description ([4517d8d](https://github.com/SethCohen/github-release-to-discord/commit/4517d8d0ec09c575248503c50ed25f15677f8f3d))

## [1.3.0](https://github.com/SethCohen/github-release-to-discord/compare/v1.2.0...v1.3.0) (2022-08-24)


### Features

* changed default action colour ([79005b2](https://github.com/SethCohen/github-release-to-discord/commit/79005b23fefce850957d37ba17ebb796dc81f6a1))
* updated description format ([a1d7a74](https://github.com/SethCohen/github-release-to-discord/commit/a1d7a74af90fcf8c00d341c8c665ca796b18c689))

## [1.2.0](https://github.com/SethCohen/github-release-to-discord/compare/v1.1.0...v1.2.0) (2022-08-24)


### Features

* updated action ([b612527](https://github.com/SethCohen/github-release-to-discord/commit/b6125273330075a9f4de3e58f2fc7f52d85d4691))

## [1.1.0](https://github.com/SethCohen/github-release-to-discord/compare/v1.0.0...v1.1.0) (2022-08-24)


### Features

* updated release-please ([0cea8a4](https://github.com/SethCohen/github-release-to-discord/commit/0cea8a493d5e12b1dc7414ecbed678f4671dda37))

## 1.0.0 (2022-08-24)


### Features

* added action ([1c119cd](https://github.com/SethCohen/github-release-to-discord/commit/1c119cd58075c88793119ece6edfed7b02d46ef7))
* added release-please ([ad3716d](https://github.com/SethCohen/github-release-to-discord/commit/ad3716d4380d5008666794374928b6a73734a371))
* updated action ([1493174](https://github.com/SethCohen/github-release-to-discord/commit/1493174a77435e53b6a8aea6afb4db0cbbf96d9f))
