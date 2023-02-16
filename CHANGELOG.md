# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## 1.0.0 (2023-02-16)


### ⚠ BREAKING CHANGES

* Removed authUrl added automatic auth url retrieval.
* removal of Node 8 support
* Some API has changed
* API is now different
* It is no longer necessary to include the openshift-config-loader separate.  By default, just calling the rest client will do the default config loading.

### Features

*  Pass a valid auth token. ([#248](https://www.github.com/lholmquist/openshift-rest-client/issues/248)) ([558bcdb](https://www.github.com/lholmquist/openshift-rest-client/commit/558bcdbf2dfc3cf3f7df6b534da11afa28bd5ed9))
* **package:** upgrade kubernetes-client from 8.3.6 to 9.0.0 ([#234](https://www.github.com/lholmquist/openshift-rest-client/issues/234)) ([60e801b](https://www.github.com/lholmquist/openshift-rest-client/commit/60e801b068bf934e08f3dcc343ecabe0e71b5c22))
* add api for connecting to the Secrets endpoint ([831f786](https://www.github.com/lholmquist/openshift-rest-client/commit/831f786c628fd9f3b63abca5e79de0799630b5fb)), closes [#31](https://www.github.com/lholmquist/openshift-rest-client/issues/31)
* add basic authentication option when the token is not provided in user config  ([#92](https://www.github.com/lholmquist/openshift-rest-client/issues/92)) ([f5778b9](https://www.github.com/lholmquist/openshift-rest-client/commit/f5778b9140a8e7c4896ad75ff1f4d0071efe37e8)), closes [#89](https://www.github.com/lholmquist/openshift-rest-client/issues/89)
* add build configs remove method ([b873ea1](https://www.github.com/lholmquist/openshift-rest-client/commit/b873ea15ebae6824ec6a1abd798a2d20fddd939c))
* add findAll and remove for builds ([0ee1ee8](https://www.github.com/lholmquist/openshift-rest-client/commit/0ee1ee89f94d37b6caa801f690a9806053158870))
* add image streams remove method ([5a88bc8](https://www.github.com/lholmquist/openshift-rest-client/commit/5a88bc8d32e37290892a03d9d651ea82f8300ba1))
* Add ServiceInstance resource ([#96](https://www.github.com/lholmquist/openshift-rest-client/issues/96)) ([6f9b197](https://www.github.com/lholmquist/openshift-rest-client/commit/6f9b1977391949b8ce3869ff152af41daf96bb3f))
* Add StatefulSet resource ([#93](https://www.github.com/lholmquist/openshift-rest-client/issues/93)) ([e154ef6](https://www.github.com/lholmquist/openshift-rest-client/commit/e154ef68879fbfbf64faaa956020a8908cae88e0))
* add the service instance endpoint ([#125](https://www.github.com/lholmquist/openshift-rest-client/issues/125)) ([d0d9374](https://www.github.com/lholmquist/openshift-rest-client/commit/d0d937405a8a08ba8eac7c4dd452e0641ad6805b)), closes [#121](https://www.github.com/lholmquist/openshift-rest-client/issues/121)
* add v1beta1 api endpoints ([#70](https://www.github.com/lholmquist/openshift-rest-client/issues/70)) ([cb8da7a](https://www.github.com/lholmquist/openshift-rest-client/commit/cb8da7a4563e32a6fb75f7b81447e709acd7a612))
* adding in a ca prop for request. fixes [#24](https://www.github.com/lholmquist/openshift-rest-client/issues/24) ([b682944](https://www.github.com/lholmquist/openshift-rest-client/commit/b682944efb0786752911d7e41ca0f798d21c9bbe))
* can now pass query string params using the qs property ([#39](https://www.github.com/lholmquist/openshift-rest-client/issues/39)) ([bbd74ac](https://www.github.com/lholmquist/openshift-rest-client/commit/bbd74ac1312878f2f5178874a713039375f8bbc0))
* include the openshift-config-lodaer. ([2e21e0e](https://www.github.com/lholmquist/openshift-rest-client/commit/2e21e0ec9c90bd5cf7e65396189a91584ee11666)), closes [#54](https://www.github.com/lholmquist/openshift-rest-client/issues/54)
* load config from a file location. ([#190](https://www.github.com/lholmquist/openshift-rest-client/issues/190)) ([811a67f](https://www.github.com/lholmquist/openshift-rest-client/commit/811a67f634d700154e5cbedb80c7406b8c7ce987)), closes [#189](https://www.github.com/lholmquist/openshift-rest-client/issues/189)
* Load from cluster spec ([#218](https://www.github.com/lholmquist/openshift-rest-client/issues/218)) ([52324a7](https://www.github.com/lholmquist/openshift-rest-client/commit/52324a7dcfc30062a6fb7f56862b4b770e228b77))
* return the kubeconfig on the client ([#186](https://www.github.com/lholmquist/openshift-rest-client/issues/186)) ([898f2ae](https://www.github.com/lholmquist/openshift-rest-client/commit/898f2aedc853fa96a1819ac0eae393b7091b89c8))
* **auth:** add optional auth url param to client settings ([#167](https://www.github.com/lholmquist/openshift-rest-client/issues/167)) ([11df861](https://www.github.com/lholmquist/openshift-rest-client/commit/11df8612c1db9bc633d952e74be72b32e3511d27))
* Refactor of the library ([#113](https://www.github.com/lholmquist/openshift-rest-client/issues/113)) ([aa8a6e3](https://www.github.com/lholmquist/openshift-rest-client/commit/aa8a6e3743e12608079050ec309a1b895d34993f)), closes [#71](https://www.github.com/lholmquist/openshift-rest-client/issues/71)
* use a username/password combo to login ([#118](https://www.github.com/lholmquist/openshift-rest-client/issues/118)) ([f1098f1](https://www.github.com/lholmquist/openshift-rest-client/commit/f1098f10a382ce615c26a8ae919bcb86e5488432)), closes [#117](https://www.github.com/lholmquist/openshift-rest-client/issues/117)
* **build-configs:** Adding instantiate method to buildconfigs ([#60](https://www.github.com/lholmquist/openshift-rest-client/issues/60)) ([7c86990](https://www.github.com/lholmquist/openshift-rest-client/commit/7c869901bd9e85e831ec8845da05de7b246b6cb1))
* **configMaps:** add GET method for ConfigMap ([45f983a](https://www.github.com/lholmquist/openshift-rest-client/commit/45f983ac4a223ea0cfef2ba2892df3accbb70aa9)), closes [#35](https://www.github.com/lholmquist/openshift-rest-client/issues/35)
* **events:** events findAll/find & tests ([14577a2](https://www.github.com/lholmquist/openshift-rest-client/commit/14577a2d375fbc14aea8a229369422cdfb97cd6e))
* **imagestreamtags:** add resource ([#90](https://www.github.com/lholmquist/openshift-rest-client/issues/90)) ([fbbf390](https://www.github.com/lholmquist/openshift-rest-client/commit/fbbf39060c5885c5493f327f062957fa77cc39e2))
* **ingress:** Expose the Ingress api. ([#77](https://www.github.com/lholmquist/openshift-rest-client/issues/77)) ([c80b457](https://www.github.com/lholmquist/openshift-rest-client/commit/c80b4578e619e21ca97b802298aa1be20c7f0377)), closes [#73](https://www.github.com/lholmquist/openshift-rest-client/issues/73)
* **PVC:** add persistent volume claims methods and tests ([306d2b5](https://www.github.com/lholmquist/openshift-rest-client/commit/306d2b5167e0cef3d3bfb313af5a9c7ddc1239d6))


### Bug Fixes

* error message when not logged in ([#51](https://www.github.com/lholmquist/openshift-rest-client/issues/51)) ([329d226](https://www.github.com/lholmquist/openshift-rest-client/commit/329d2264a101f33ab16e4d1b51d811a0a6bae4cb))
* no cluster url should return a rejected Promise ([fa2a549](https://www.github.com/lholmquist/openshift-rest-client/commit/fa2a549a7bc29abf4639b9537c9af5f9b490056f))
* Pass in an normal object as a Config ([#223](https://www.github.com/lholmquist/openshift-rest-client/issues/223)) ([acffb3d](https://www.github.com/lholmquist/openshift-rest-client/commit/acffb3d2d0d0e0fa50225b36a7bcf0532a52fa8d)), closes [#222](https://www.github.com/lholmquist/openshift-rest-client/issues/222)
* pin the kubernetese-client version to 8.3.6 ([#208](https://www.github.com/lholmquist/openshift-rest-client/issues/208)) ([d9dfbcb](https://www.github.com/lholmquist/openshift-rest-client/commit/d9dfbcbe71d6c8348b675fa0e4ab4c242774d9bf))
* remove warnings about deprecations ([#171](https://www.github.com/lholmquist/openshift-rest-client/issues/171)) ([9f7b379](https://www.github.com/lholmquist/openshift-rest-client/commit/9f7b3798813eadd584b685e71f2b657c1cb010be))
* Removed authUrl added automatic auth url retrieval. ([8db3420](https://www.github.com/lholmquist/openshift-rest-client/commit/8db342036063b2dd7ba73e4e2f207f704036d4a5))
* Throw an error when there's no CLUSTER URL ([#108](https://www.github.com/lholmquist/openshift-rest-client/issues/108)) ([65093a3](https://www.github.com/lholmquist/openshift-rest-client/commit/65093a379c0ea792136e7ab5fca63665b8f35d7e))
* travis-ci should use npm install instead of npm ci ([#74](https://www.github.com/lholmquist/openshift-rest-client/issues/74)) ([5d7b59b](https://www.github.com/lholmquist/openshift-rest-client/commit/5d7b59b1643ced2076e431444b0ffe5a6740e88b))
* update request for nsp issue ([b68686d](https://www.github.com/lholmquist/openshift-rest-client/commit/b68686d1f784c8547bc2949c636cd0858702be40))
* upgrade coveralls from 3.0.6 to 3.0.9 ([#200](https://www.github.com/lholmquist/openshift-rest-client/issues/200)) ([c4d0fcd](https://www.github.com/lholmquist/openshift-rest-client/commit/c4d0fcd07fc2d894b28f41493a5f4ce2c8247c79))
* upgrade documentation from 12.1.2 to 12.1.4 ([#202](https://www.github.com/lholmquist/openshift-rest-client/issues/202)) ([60e418e](https://www.github.com/lholmquist/openshift-rest-client/commit/60e418ed6ee6589de370324c024e6677d15614aa))
* upgrade documentation from 13.0.2 to 13.1.0 ([#242](https://www.github.com/lholmquist/openshift-rest-client/issues/242)) ([b9cc5c1](https://www.github.com/lholmquist/openshift-rest-client/commit/b9cc5c152e8b8d5b2f77d2b661991747cd884cd5))
* upgrade eslint from 6.5.0 to 6.8.0 ([#199](https://www.github.com/lholmquist/openshift-rest-client/issues/199)) ([baebe7a](https://www.github.com/lholmquist/openshift-rest-client/commit/baebe7ae49c87982b5af7115e34af3d80aea8596))
* upgrade eslint-plugin-import from 2.22.0 to 2.22.1 ([#239](https://www.github.com/lholmquist/openshift-rest-client/issues/239)) ([4e5a37e](https://www.github.com/lholmquist/openshift-rest-client/commit/4e5a37e3f7a1203b66ec8965ccbe6e56710c3570))
* upgrade eslint-plugin-node from 11.0.0 to 11.1.0 ([#210](https://www.github.com/lholmquist/openshift-rest-client/issues/210)) ([308cf54](https://www.github.com/lholmquist/openshift-rest-client/commit/308cf54da06a14b64d81e1186cf93acc2049ca3f))
* upgrade eslint-plugin-standard from 4.0.1 to 4.0.2 ([#241](https://www.github.com/lholmquist/openshift-rest-client/issues/241)) ([1f12885](https://www.github.com/lholmquist/openshift-rest-client/commit/1f12885f9758bec7882175b4e7ab5ba942ccba34))
* upgrade eslint-plugin-standard from 4.0.2 to 4.1.0 ([#244](https://www.github.com/lholmquist/openshift-rest-client/issues/244)) ([65de536](https://www.github.com/lholmquist/openshift-rest-client/commit/65de536f1acf4f8fc2321c01d459679db9346e6b))
* upgrade kubernetes-client from 8.3.4 to 8.3.6 ([#203](https://www.github.com/lholmquist/openshift-rest-client/issues/203)) ([2dfa271](https://www.github.com/lholmquist/openshift-rest-client/commit/2dfa27148b3fed680f5458567c3670c9f96c511f))
* upgrade nock from 12.0.0 to 12.0.2 ([#201](https://www.github.com/lholmquist/openshift-rest-client/issues/201)) ([7597d6f](https://www.github.com/lholmquist/openshift-rest-client/commit/7597d6fb5142a798c4436e8021c88b858236fb57))
* upgrade request from 2.88.0 to 2.88.2 ([#204](https://www.github.com/lholmquist/openshift-rest-client/issues/204)) ([007a6b4](https://www.github.com/lholmquist/openshift-rest-client/commit/007a6b488f0d21f61f839ddf654fe61b5aae4a1a))
* upgrade standard-version from 8.0.1 to 8.0.2 ([#236](https://www.github.com/lholmquist/openshift-rest-client/issues/236)) ([ab29702](https://www.github.com/lholmquist/openshift-rest-client/commit/ab29702c1e9754b0b321a8e45ca5ac8ab9672ed3))
* upgrade tape from 4.13.0 to 4.13.2 ([#205](https://www.github.com/lholmquist/openshift-rest-client/issues/205)) ([5ab6a48](https://www.github.com/lholmquist/openshift-rest-client/commit/5ab6a4882f66f9aefb4df544d1bd7c7003835d10))
* **auth:** Throw some reasonable error message in basic authentication when we can't obtain an access token. ([#174](https://www.github.com/lholmquist/openshift-rest-client/issues/174)) ([53614e2](https://www.github.com/lholmquist/openshift-rest-client/commit/53614e29a31c37f7084bff382b8c57909a0c7641))
* **common-request.js:** print some meaningful error message in case of unsuccessful authentication ([#99](https://www.github.com/lholmquist/openshift-rest-client/issues/99)) ([8d6ad07](https://www.github.com/lholmquist/openshift-rest-client/commit/8d6ad07cdf77e23657d5d2a2fdcf0dd8a768ec51))
* **package:** add hoek directly as a dependecy to fix the security issue - https://nodesecurity.io/advisories/566 ([#57](https://www.github.com/lholmquist/openshift-rest-client/issues/57)) ([c81fdb5](https://www.github.com/lholmquist/openshift-rest-client/commit/c81fdb505e852d1c0b574982242c1f741e9b059f)), closes [#56](https://www.github.com/lholmquist/openshift-rest-client/issues/56)
* **package:** update dependecies to fix sshpk security issue, https://nodesecurity.io/advisories/606 ([#65](https://www.github.com/lholmquist/openshift-rest-client/issues/65)) ([5cde946](https://www.github.com/lholmquist/openshift-rest-client/commit/5cde94693efebf7cc0a107348653456bffcf597c)), closes [#64](https://www.github.com/lholmquist/openshift-rest-client/issues/64)
* **tests:** missing PVC test ([f10cdc8](https://www.github.com/lholmquist/openshift-rest-client/commit/f10cdc8115ce92591479a780890745f44f6dca61))
* use body.message for error string ([#47](https://www.github.com/lholmquist/openshift-rest-client/issues/47)) ([81c9e5c](https://www.github.com/lholmquist/openshift-rest-client/commit/81c9e5c3b7212b060a9f813f4ad7f6c555cc895b))


### Reverts

* Revert "Update openshift-config-loader to the latest version 🚀 (#33)" ([1aeb14a](https://www.github.com/lholmquist/openshift-rest-client/commit/1aeb14a85f5918849112a8a7c32af39052d11ce1)), closes [#33](https://www.github.com/lholmquist/openshift-rest-client/issues/33)


### Miscellaneous Chores

* engine parameter targets node 10+ ([#194](https://www.github.com/lholmquist/openshift-rest-client/issues/194)) ([ab0bab4](https://www.github.com/lholmquist/openshift-rest-client/commit/ab0bab46e705a1eac9279d7f87ffff4f09961875))

## [5.0.0](https://github.com/nodeshift/openshift-rest-client/compare/v4.1.1...v5.0.0) (2021-01-05)


### ⚠ BREAKING CHANGES

* Removed authUrl added automatic auth url retrieval.

### Features

* **package:** upgrade kubernetes-client from 8.3.6 to 9.0.0 ([#234](https://github.com/nodeshift/openshift-rest-client/issues/234)) ([60e801b](https://github.com/nodeshift/openshift-rest-client/commit/60e801b068bf934e08f3dcc343ecabe0e71b5c22))


### Bug Fixes

* Removed authUrl added automatic auth url retrieval. ([8db3420](https://github.com/nodeshift/openshift-rest-client/commit/8db342036063b2dd7ba73e4e2f207f704036d4a5))
* upgrade documentation from 13.0.2 to 13.1.0 ([#242](https://github.com/nodeshift/openshift-rest-client/issues/242)) ([b9cc5c1](https://github.com/nodeshift/openshift-rest-client/commit/b9cc5c152e8b8d5b2f77d2b661991747cd884cd5))
* upgrade eslint-plugin-import from 2.22.0 to 2.22.1 ([#239](https://github.com/nodeshift/openshift-rest-client/issues/239)) ([4e5a37e](https://github.com/nodeshift/openshift-rest-client/commit/4e5a37e3f7a1203b66ec8965ccbe6e56710c3570))
* upgrade eslint-plugin-standard from 4.0.1 to 4.0.2 ([#241](https://github.com/nodeshift/openshift-rest-client/issues/241)) ([1f12885](https://github.com/nodeshift/openshift-rest-client/commit/1f12885f9758bec7882175b4e7ab5ba942ccba34))
* upgrade eslint-plugin-standard from 4.0.2 to 4.1.0 ([#244](https://github.com/nodeshift/openshift-rest-client/issues/244)) ([65de536](https://github.com/nodeshift/openshift-rest-client/commit/65de536f1acf4f8fc2321c01d459679db9346e6b))
* upgrade standard-version from 8.0.1 to 8.0.2 ([#236](https://github.com/nodeshift/openshift-rest-client/issues/236)) ([ab29702](https://github.com/nodeshift/openshift-rest-client/commit/ab29702c1e9754b0b321a8e45ca5ac8ab9672ed3))

### [4.1.1](https://github.com/nodeshift/openshift-rest-client/compare/v4.1.0...v4.1.1) (2020-05-30)


### Bug Fixes

* Pass in an normal object as a Config ([#223](https://github.com/nodeshift/openshift-rest-client/issues/223)) ([acffb3d](https://github.com/nodeshift/openshift-rest-client/commit/acffb3d2d0d0e0fa50225b36a7bcf0532a52fa8d)), closes [#222](https://github.com/nodeshift/openshift-rest-client/issues/222)

## [4.1.0](https://github.com/nodeshift/openshift-rest-client/compare/v4.0.1...v4.1.0) (2020-05-22)


### Features

* Load from cluster spec ([#218](https://github.com/nodeshift/openshift-rest-client/issues/218)) ([52324a7](https://github.com/nodeshift/openshift-rest-client/commit/52324a7dcfc30062a6fb7f56862b4b770e228b77))


### Bug Fixes

* upgrade eslint-plugin-node from 11.0.0 to 11.1.0 ([#210](https://github.com/nodeshift/openshift-rest-client/issues/210)) ([308cf54](https://github.com/nodeshift/openshift-rest-client/commit/308cf54da06a14b64d81e1186cf93acc2049ca3f))

### [4.0.1](https://github.com/nodeshift/openshift-rest-client/compare/v4.0.0...v4.0.1) (2020-04-13)


### Bug Fixes

* pin the kubernetese-client version to 8.3.6 ([#208](https://github.com/nodeshift/openshift-rest-client/issues/208)) ([d9dfbcb](https://github.com/nodeshift/openshift-rest-client/commit/d9dfbcbe71d6c8348b675fa0e4ab4c242774d9bf))
* upgrade coveralls from 3.0.6 to 3.0.9 ([#200](https://github.com/nodeshift/openshift-rest-client/issues/200)) ([c4d0fcd](https://github.com/nodeshift/openshift-rest-client/commit/c4d0fcd07fc2d894b28f41493a5f4ce2c8247c79))
* upgrade documentation from 12.1.2 to 12.1.4 ([#202](https://github.com/nodeshift/openshift-rest-client/issues/202)) ([60e418e](https://github.com/nodeshift/openshift-rest-client/commit/60e418ed6ee6589de370324c024e6677d15614aa))
* upgrade eslint from 6.5.0 to 6.8.0 ([#199](https://github.com/nodeshift/openshift-rest-client/issues/199)) ([baebe7a](https://github.com/nodeshift/openshift-rest-client/commit/baebe7ae49c87982b5af7115e34af3d80aea8596))
* upgrade kubernetes-client from 8.3.4 to 8.3.6 ([#203](https://github.com/nodeshift/openshift-rest-client/issues/203)) ([2dfa271](https://github.com/nodeshift/openshift-rest-client/commit/2dfa27148b3fed680f5458567c3670c9f96c511f))
* upgrade nock from 12.0.0 to 12.0.2 ([#201](https://github.com/nodeshift/openshift-rest-client/issues/201)) ([7597d6f](https://github.com/nodeshift/openshift-rest-client/commit/7597d6fb5142a798c4436e8021c88b858236fb57))
* upgrade request from 2.88.0 to 2.88.2 ([#204](https://github.com/nodeshift/openshift-rest-client/issues/204)) ([007a6b4](https://github.com/nodeshift/openshift-rest-client/commit/007a6b488f0d21f61f839ddf654fe61b5aae4a1a))
* upgrade tape from 4.13.0 to 4.13.2 ([#205](https://github.com/nodeshift/openshift-rest-client/issues/205)) ([5ab6a48](https://github.com/nodeshift/openshift-rest-client/commit/5ab6a4882f66f9aefb4df544d1bd7c7003835d10))

## [4.0.0](https://github.com/nodeshift/openshift-rest-client/compare/v3.2.0...v4.0.0) (2020-02-17)


### ⚠ BREAKING CHANGES

* removal of Node 8 support

* engine parameter targets node 10+ ([#194](https://github.com/nodeshift/openshift-rest-client/issues/194)) ([ab0bab4](https://github.com/nodeshift/openshift-rest-client/commit/ab0bab46e705a1eac9279d7f87ffff4f09961875))

## [3.2.0](https://github.com/nodeshift/openshift-rest-client/compare/v3.1.0...v3.2.0) (2020-01-21)


### Features

* load config from a file location. ([#190](https://github.com/nodeshift/openshift-rest-client/issues/190)) ([811a67f](https://github.com/nodeshift/openshift-rest-client/commit/811a67f)), closes [#189](https://github.com/nodeshift/openshift-rest-client/issues/189)

## [3.1.0](https://github.com/nodeshift/openshift-rest-client/compare/v3.0.1...v3.1.0) (2020-01-14)


### Features

* return the kubeconfig on the client ([#186](https://github.com/nodeshift/openshift-rest-client/issues/186)) ([898f2ae](https://github.com/nodeshift/openshift-rest-client/commit/898f2ae))

### [3.0.1](https://github.com/nodeshift/openshift-rest-client/compare/v3.0.0...v3.0.1) (2019-11-19)


### Bug Fixes

* **auth:** Throw some reasonable error message in basic authentication when we can't obtain an access token. ([#174](https://github.com/nodeshift/openshift-rest-client/issues/174)) ([53614e2](https://github.com/nodeshift/openshift-rest-client/commit/53614e2))

## [3.0.0](https://github.com/nodeshift/openshift-rest-client/compare/v2.3.0...v3.0.0) (2019-10-30)


### ⚠ BREAKING CHANGES

* Some API has changed

* This commit updates the client to remove deprecation warnings caused by the kubernetes-clients.  There are some changes to getting external configs.

### Bug Fixes

* remove warnings about deprecations ([#171](https://github.com/nodeshift/openshift-rest-client/issues/171)) ([9f7b379](https://github.com/nodeshift/openshift-rest-client/commit/9f7b379))

## [2.3.0](https://github.com/nodeshift/openshift-rest-client/compare/v2.2.2...v2.3.0) (2019-09-30)


### Features

* **auth:** add optional auth url param to client settings ([#167](https://github.com/nodeshift/openshift-rest-client/issues/167)) ([11df861](https://github.com/nodeshift/openshift-rest-client/commit/11df861))

### [2.2.2](https://github.com/nodeshift/openshift-rest-client/compare/v2.2.1...v2.2.2) (2019-09-11)

### [2.2.1](https://github.com/nodeshift/openshift-rest-client/compare/v2.2.0...v2.2.1) (2019-09-09)

# [2.2.0](https://github.com/nodeshift/openshift-rest-client/compare/v2.1.0...v2.2.0) (2019-04-24)


### Features

* add the service instance endpoint ([#125](https://github.com/nodeshift/openshift-rest-client/issues/125)) ([d0d9374](https://github.com/nodeshift/openshift-rest-client/commit/d0d9374)), closes [#121](https://github.com/nodeshift/openshift-rest-client/issues/121)



# [2.1.0](https://github.com/nodeshift/openshift-rest-client/compare/v2.0.1...v2.1.0) (2019-04-05)


### Features

* use a username/password combo to login ([#118](https://github.com/nodeshift/openshift-rest-client/issues/118)) ([f1098f1](https://github.com/nodeshift/openshift-rest-client/commit/f1098f1)), closes [#117](https://github.com/nodeshift/openshift-rest-client/issues/117)



## [2.0.1](https://github.com/nodeshift/openshift-rest-client/compare/v2.0.0...v2.0.1) (2019-04-01)



# [2.0.0](https://github.com/nodeshift/openshift-rest-client/compare/v1.6.4...v2.0.0) (2019-03-14)


### Features

* Refactor of the library ([#113](https://github.com/nodeshift/openshift-rest-client/issues/113)) ([aa8a6e3](https://github.com/nodeshift/openshift-rest-client/commit/aa8a6e3)), closes [#71](https://github.com/nodeshift/openshift-rest-client/issues/71)


### BREAKING CHANGES

* API is now different

* The API is now generated based on the Openshift Open api spec

* Using the [kubernetes-client](https://github.com/godaddy/kubernetes-client) under the hood

* The api is fluent, for example, client.apis['build.openshift.io'].v1.namespace('default').builds.get()

* Not a drop in replacement for version 1.x



<a name="1.6.4"></a>
## [1.6.4](https://github.com/nodeshift/openshift-rest-client/compare/v1.6.3...v1.6.4) (2019-01-23)


### Bug Fixes

* no cluster url should return a rejected Promise ([fa2a549](https://github.com/nodeshift/openshift-rest-client/commit/fa2a549))
* Throw an error when there's no CLUSTER URL ([#108](https://github.com/nodeshift/openshift-rest-client/issues/108)) ([65093a3](https://github.com/nodeshift/openshift-rest-client/commit/65093a3))



<a name="1.6.3"></a>
## [1.6.3](https://github.com/nodeshift/openshift-rest-client/compare/v1.6.2...v1.6.3) (2019-01-15)



<a name="1.6.2"></a>
## [1.6.2](https://github.com/nodeshift/openshift-rest-client/compare/v1.6.1...v1.6.2) (2018-12-12)



<a name="1.6.1"></a>
## [1.6.1](https://github.com/nodeshift/openshift-rest-client/compare/v1.6.0...v1.6.1) (2018-12-07)


### Bug Fixes

* **common-request.js:** print some meaningful error message in case of unsuccessful authentication ([#99](https://github.com/nodeshift/openshift-rest-client/issues/99)) ([8d6ad07](https://github.com/nodeshift/openshift-rest-client/commit/8d6ad07))



<a name="1.6.0"></a>
# [1.6.0](https://github.com/nodeshift/openshift-rest-client/compare/v1.5.0...v1.6.0) (2018-11-29)


### Features

* add basic authentication option when the token is not provided in user config  ([#92](https://github.com/nodeshift/openshift-rest-client/issues/92)) ([f5778b9](https://github.com/nodeshift/openshift-rest-client/commit/f5778b9)), closes [#89](https://github.com/nodeshift/openshift-rest-client/issues/89)
* Add ServiceInstance resource ([#96](https://github.com/nodeshift/openshift-rest-client/issues/96)) ([6f9b197](https://github.com/nodeshift/openshift-rest-client/commit/6f9b197))
* Add StatefulSet resource ([#93](https://github.com/nodeshift/openshift-rest-client/issues/93)) ([e154ef6](https://github.com/nodeshift/openshift-rest-client/commit/e154ef6))



<a name="1.5.0"></a>
# [1.5.0](https://github.com/nodeshift/openshift-rest-client/compare/v1.4.0...v1.5.0) (2018-10-30)


### Features

* **imagestreamtags:** add resource ([#90](https://github.com/nodeshift/openshift-rest-client/issues/90)) ([fbbf390](https://github.com/nodeshift/openshift-rest-client/commit/fbbf390))



<a name="1.4.0"></a>
# [1.4.0](https://github.com/nodeshift/openshift-rest-client/compare/v1.3.0...v1.4.0) (2018-06-05)


### Bug Fixes

* travis-ci should use npm install instead of npm ci ([#74](https://github.com/nodeshift/openshift-rest-client/issues/74)) ([5d7b59b](https://github.com/nodeshift/openshift-rest-client/commit/5d7b59b))


### Features

* **ingress:** Expose the Ingress api. ([#77](https://github.com/nodeshift/openshift-rest-client/issues/77)) ([c80b457](https://github.com/nodeshift/openshift-rest-client/commit/c80b457)), closes [#73](https://github.com/nodeshift/openshift-rest-client/issues/73)



<a name="1.3.0"></a>
# [1.3.0](https://github.com/nodeshift/openshift-rest-client/compare/v1.2.0...v1.3.0) (2018-05-24)


### Features

* add v1beta1 api endpoints ([#70](https://github.com/nodeshift/openshift-rest-client/issues/70)) ([cb8da7a](https://github.com/nodeshift/openshift-rest-client/commit/cb8da7a))



<a name="1.2.0"></a>
# [1.2.0](https://github.com/nodeshift/openshift-rest-client/compare/v1.1.2...v1.2.0) (2018-05-22)


### Bug Fixes

* **tests:** missing PVC test ([f10cdc8](https://github.com/nodeshift/openshift-rest-client/commit/f10cdc8))


### Features

* **events:** events findAll/find & tests ([14577a2](https://github.com/nodeshift/openshift-rest-client/commit/14577a2))
* **PVC:** add persistent volume claims methods and tests ([306d2b5](https://github.com/nodeshift/openshift-rest-client/commit/306d2b5))



<a name="1.1.2"></a>
## [1.1.2](https://github.com/nodeshift/openshift-rest-client/compare/v1.1.1...v1.1.2) (2018-05-21)



<a name="1.1.1"></a>
## [1.1.1](https://github.com/nodeshift/openshift-rest-client/compare/v1.1.0...v1.1.1) (2018-05-14)


### Bug Fixes

* **package:** update dependecies to fix sshpk security issue, https://nodesecurity.io/advisories/606 ([#65](https://github.com/nodeshift/openshift-rest-client/issues/65)) ([5cde946](https://github.com/nodeshift/openshift-rest-client/commit/5cde946)), closes [#64](https://github.com/nodeshift/openshift-rest-client/issues/64)



<a name="1.1.0"></a>
# [1.1.0](https://github.com/nodeshift/openshift-rest-client/compare/v1.0.1...v1.1.0) (2018-03-20)


### Features

* **build-configs:** Adding instantiate method to buildconfigs ([#60](https://github.com/nodeshift/openshift-rest-client/issues/60)) ([7c86990](https://github.com/nodeshift/openshift-rest-client/commit/7c86990))



<a name="1.0.1"></a>
## [1.0.1](https://github.com/nodeshift/openshift-rest-client/compare/v1.0.0...v1.0.1) (2018-02-19)


### Bug Fixes

* **package:** add hoek directly as a dependecy to fix the security issue - https://nodesecurity.io/advisories/566 ([#57](https://github.com/nodeshift/openshift-rest-client/issues/57)) ([c81fdb5](https://github.com/nodeshift/openshift-rest-client/commit/c81fdb5)), closes [#56](https://github.com/nodeshift/openshift-rest-client/issues/56)



<a name="1.0.0"></a>
# [1.0.0](https://github.com/nodeshift/openshift-rest-client/compare/v0.11.0...v1.0.0) (2018-02-12)


### Features

* include the openshift-config-lodaer. ([2e21e0e](https://github.com/nodeshift/openshift-rest-client/commit/2e21e0e)), closes [#54](https://github.com/nodeshift/openshift-rest-client/issues/54)


### BREAKING CHANGES

* It is no longer necessary to include the openshift-config-loader separate.  By default, just calling the rest client will do the default config loading.
If a user needs to pass a config into the client, use the settings object.  ex:  settings.config = {...}
