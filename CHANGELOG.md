# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## 1.20.0 (2023-06-27)

### Features

- add classname `split-view-sash-dragging` for top-level container ([#536](https://github.com/cgrime01/allotment/issues/536)) ([a59c774](https://github.com/cgrime01/allotment/commit/a59c774eec366070614bd95033157839139b0263))
- add className prop to Allotment.Pane ([#108](https://github.com/cgrime01/allotment/issues/108)) ([9486638](https://github.com/cgrime01/allotment/commit/94866382d2580220a3502f8194c18eb93cd721ec))
- add defaultSizes prop and deprecate sizes prop ([#72](https://github.com/cgrime01/allotment/issues/72)) ([2ece9ce](https://github.com/cgrime01/allotment/commit/2ece9ce2f8142d1c28b5394743d73f920f4489e2))
- add imperative reset method ([#69](https://github.com/cgrime01/allotment/issues/69)) ([aceb88f](https://github.com/cgrime01/allotment/commit/aceb88f2de9e454dfce2ccd35bc4e23c8d8e3cb7))
- add layout priority prop ([#267](https://github.com/cgrime01/allotment/issues/267)) ([f8bb905](https://github.com/cgrime01/allotment/commit/f8bb905085faf85a738e8d4ac5e4899964ef358f))
- add onReset callback ([#154](https://github.com/cgrime01/allotment/issues/154)) ([904a8e6](https://github.com/cgrime01/allotment/commit/904a8e6acbf3692b4f2cb7fa102799872c70243d))
- add onVisibleChange callback ([#222](https://github.com/cgrime01/allotment/issues/222)) ([39f9bec](https://github.com/cgrime01/allotment/commit/39f9bec2627b7496ee6270fe3ff67e8a1f90e94e))
- add preferredSize prop ([#229](https://github.com/cgrime01/allotment/issues/229)) ([3be2144](https://github.com/cgrime01/allotment/commit/3be21441660475a5c71c604dbb11ac84630df913))
- add prop for setting proportionalLayout ([#179](https://github.com/cgrime01/allotment/issues/179)) ([4f8f68c](https://github.com/cgrime01/allotment/commit/4f8f68c3d2ae99108b97befc5ab787873c7e3f77))
- add resize method to component instance ([#121](https://github.com/cgrime01/allotment/issues/121)) ([d25bd91](https://github.com/cgrime01/allotment/commit/d25bd91bde05c33bdebf586868a38a03056d8d57))
- add split-view-separator-border class ([#406](https://github.com/cgrime01/allotment/issues/406)) ([8843ff4](https://github.com/cgrime01/allotment/commit/8843ff450e1021393f839882be5ff17cbe526d0e))
- add stable classnames to child elements ([#375](https://github.com/cgrime01/allotment/issues/375)) ([326f771](https://github.com/cgrime01/allotment/commit/326f771d9c4a3d7dba1fc4f1b1596d50f723a7cd))
- add support for onDragStart and onDragEnd callbacks ([#576](https://github.com/cgrime01/allotment/issues/576)) ([722e8af](https://github.com/cgrime01/allotment/commit/722e8af9e696d14390dad9d7ffd8b5614d7c58d6))
- add visible prop to Pane ([#137](https://github.com/cgrime01/allotment/issues/137)) ([3b0542c](https://github.com/cgrime01/allotment/commit/3b0542c24165c0cb054ee12a682c1b153a2de5ad))
- apply overflow hidden to panes ([#271](https://github.com/cgrime01/allotment/issues/271)) ([9d8d7c9](https://github.com/cgrime01/allotment/commit/9d8d7c918d1454a849c7c49968a1873259869246))
- avoid unmounting pane with same key which changes position ([#226](https://github.com/cgrime01/allotment/issues/226)) ([f7d077a](https://github.com/cgrime01/allotment/commit/f7d077a1d71d51139ce7386be0538dcdd29c08e1))
- basic functionality ([#1](https://github.com/cgrime01/allotment/issues/1)) ([36b4442](https://github.com/cgrime01/allotment/commit/36b44425f9ea8d6d18e2e74cabfbc9813c52c0fd))
- dynamic minSize and maxSize ([#227](https://github.com/cgrime01/allotment/issues/227)) ([d764ebe](https://github.com/cgrime01/allotment/commit/d764ebe241faead5bdecd9311135ff1f39a40935))
- enable sash size to be customised in code ([#101](https://github.com/cgrime01/allotment/issues/101)) ([f177e48](https://github.com/cgrime01/allotment/commit/f177e48bdf4e12533b8e5dcdd76cd94802c83710))
- increase sash size on touch devices ([#66](https://github.com/cgrime01/allotment/issues/66)) ([20ab7d9](https://github.com/cgrime01/allotment/commit/20ab7d93ab836af864a67531b3c5c1244e23a3b8))
- separator color which works better on light and dark backgrounds ([a769262](https://github.com/cgrime01/allotment/commit/a769262de79658cda4866edbafe4ffb8e5f0773a))
- set props on children ([#9](https://github.com/cgrime01/allotment/issues/9)) ([180ed52](https://github.com/cgrime01/allotment/commit/180ed52bced6d74860142092f27800728896d97e))
- support disabling separator ([#388](https://github.com/cgrime01/allotment/issues/388)) ([283d01d](https://github.com/cgrime01/allotment/commit/283d01d6d761bc346b3fe871cdda5e81382044bd))
- support setting initial sizes ([#14](https://github.com/cgrime01/allotment/issues/14)) ([b07415e](https://github.com/cgrime01/allotment/commit/b07415e0539ca28f123a143c88aa28de7ec80b75))
- use className prop on Allotment component ([8e1b6bd](https://github.com/cgrime01/allotment/commit/8e1b6bde537d03318bd441b9dfdb2816c20bfb2c))

### Bug Fixes

- allow changing order of panes ([cc38223](https://github.com/cgrime01/allotment/commit/cc38223e3f4315f61a50126630170c25ab8b5e1f))
- call cancel hover after pointer up ([#129](https://github.com/cgrime01/allotment/issues/129)) ([b9a6e5f](https://github.com/cgrime01/allotment/commit/b9a6e5f10f89298e9935f14c9d52f63ec8527e2c))
- center sash ([#12](https://github.com/cgrime01/allotment/issues/12)) ([d2b7486](https://github.com/cgrime01/allotment/commit/d2b74867dae30ae05f3f20f4d4a29cc8ebc7a9e7))
- defaultSizes needs to be used ([#77](https://github.com/cgrime01/allotment/issues/77)) ([cd2eae1](https://github.com/cgrime01/allotment/commit/cd2eae13116af91af00846e212452287cfb7c607))
- defaultSizes should not disable props on Allotment.Pane ([3837d87](https://github.com/cgrime01/allotment/commit/3837d87538089cea6c53635f9a657fcf75296b9e))
- **deps:** update dependency @svgr/webpack to v6.2.0 ([#135](https://github.com/cgrime01/allotment/issues/135)) ([40cbd8f](https://github.com/cgrime01/allotment/commit/40cbd8f0891b5fb63539a1df2ae43667868f87de))
- **deps:** update dependency @svgr/webpack to v6.2.1 ([#145](https://github.com/cgrime01/allotment/issues/145)) ([016d504](https://github.com/cgrime01/allotment/commit/016d504bcdcc505f705819c5ce349583700db185))
- **deps:** update dependency @svgr/webpack to v6.3.1 ([#368](https://github.com/cgrime01/allotment/issues/368)) ([1891e38](https://github.com/cgrime01/allotment/commit/1891e38ca850219910472815752c4bdebcd989e9))
- **deps:** update dependency @svgr/webpack to v6.4.0 ([#451](https://github.com/cgrime01/allotment/issues/451)) ([7a84e1d](https://github.com/cgrime01/allotment/commit/7a84e1dd80d5efa5f289ec7d33b5fe37927dcf7b))
- **deps:** update dependency @svgr/webpack to v6.5.0 ([#462](https://github.com/cgrime01/allotment/issues/462)) ([d4fb352](https://github.com/cgrime01/allotment/commit/d4fb352c1c8aefe082a8d1187e3abaeabada8fe0))
- **deps:** update dependency @svgr/webpack to v6.5.1 ([#477](https://github.com/cgrime01/allotment/issues/477)) ([abd8d19](https://github.com/cgrime01/allotment/commit/abd8d1906079cc05f56f15f1c98592a37147ed95))
- **deps:** update dependency @svgr/webpack to v7 ([#597](https://github.com/cgrime01/allotment/issues/597)) ([34310e3](https://github.com/cgrime01/allotment/commit/34310e3c7adca62083b0eb47c4aecfbb10d2e425))
- **deps:** update dependency @vscode/codicons to v0.0.32 ([#382](https://github.com/cgrime01/allotment/issues/382)) ([667e87d](https://github.com/cgrime01/allotment/commit/667e87da10167c03b0dd1b4a49b4ce6d3b3a156f))
- **deps:** update dependency @vscode/codicons to v0.0.33 ([#603](https://github.com/cgrime01/allotment/issues/603)) ([cdb0890](https://github.com/cgrime01/allotment/commit/cdb0890d417e45d28317c8d0d449ee754d389d8b))
- **deps:** update dependency eventemitter3 to v5 ([#501](https://github.com/cgrime01/allotment/issues/501)) ([f7114a1](https://github.com/cgrime01/allotment/commit/f7114a1736414de06e888158b7c292631973ac64))
- **deps:** update dependency prism-react-renderer to v1.3.1 ([#162](https://github.com/cgrime01/allotment/issues/162)) ([0842718](https://github.com/cgrime01/allotment/commit/0842718abe3917bfdfde28a7d322d3d082218c62))
- **deps:** update dependency prism-react-renderer to v1.3.3 ([#289](https://github.com/cgrime01/allotment/issues/289)) ([2cf01bc](https://github.com/cgrime01/allotment/commit/2cf01bc7ba0f9fd462c3ab5eeb788dd6590b932c))
- **deps:** update dependency prism-react-renderer to v1.3.5 ([#349](https://github.com/cgrime01/allotment/issues/349)) ([fe48689](https://github.com/cgrime01/allotment/commit/fe4868977239fb8e21583e38b74ac4bfd4a2dd07))
- **deps:** update dependency use-resize-observer to v9 ([#290](https://github.com/cgrime01/allotment/issues/290)) ([cfedecb](https://github.com/cgrime01/allotment/commit/cfedecb282ae16f024b6a621dd00effeb98b9f98))
- **deps:** update dependency xterm to v5 ([#436](https://github.com/cgrime01/allotment/issues/436)) ([eea5749](https://github.com/cgrime01/allotment/commit/eea57491ba33687b32416abe28e48c39720a4661))
- **deps:** update dependency xterm-addon-fit to v0.6.0 ([#435](https://github.com/cgrime01/allotment/issues/435)) ([16a83f1](https://github.com/cgrime01/allotment/commit/16a83f171d1028261a45e9ebead83028d0b52dda))
- **deps:** update docusaurus monorepo to v2.0.0-beta.15 ([#141](https://github.com/cgrime01/allotment/issues/141)) ([81373a4](https://github.com/cgrime01/allotment/commit/81373a4fbcabd8c2e3ca4ea95a2155648b5f845d))
- **deps:** update docusaurus monorepo to v2.0.0-beta.17 ([#186](https://github.com/cgrime01/allotment/issues/186)) ([e1efbcf](https://github.com/cgrime01/allotment/commit/e1efbcf27a8682f7928f67b7a750f113f55579de))
- **deps:** update docusaurus monorepo to v2.0.0-beta.18 ([#207](https://github.com/cgrime01/allotment/issues/207)) ([c5b4b3c](https://github.com/cgrime01/allotment/commit/c5b4b3c1d06c95d509647b871ea65ab4263f8aaa))
- **deps:** update docusaurus monorepo to v2.0.0-beta.19 ([#270](https://github.com/cgrime01/allotment/issues/270)) ([040e77f](https://github.com/cgrime01/allotment/commit/040e77fa6f6af3d63c1f231495ea50de59b92676))
- **deps:** update docusaurus monorepo to v2.0.0-beta.20 ([#273](https://github.com/cgrime01/allotment/issues/273)) ([33aa52a](https://github.com/cgrime01/allotment/commit/33aa52a54877c663234ca07199dc81a25de87843))
- **deps:** update docusaurus monorepo to v2.0.0-beta.21 ([#311](https://github.com/cgrime01/allotment/issues/311)) ([07b1b75](https://github.com/cgrime01/allotment/commit/07b1b75f1e9179b90a97d4264933c7a3a63105ad))
- **deps:** update docusaurus monorepo to v2.0.0-rc.1 ([#354](https://github.com/cgrime01/allotment/issues/354)) ([4158c5b](https://github.com/cgrime01/allotment/commit/4158c5b5fae9079305654ff991626c6f452ea8e7))
- **deps:** update docusaurus monorepo to v2.0.1 ([#379](https://github.com/cgrime01/allotment/issues/379)) ([586fb5e](https://github.com/cgrime01/allotment/commit/586fb5e0d29313f54a9f7d66674cdbc31f73f58d))
- **deps:** update docusaurus monorepo to v2.1.0 ([#418](https://github.com/cgrime01/allotment/issues/418)) ([d8770e1](https://github.com/cgrime01/allotment/commit/d8770e19a36b9141e336d97a1f349fea6d1d0d39))
- **deps:** update docusaurus monorepo to v2.2.0 ([#478](https://github.com/cgrime01/allotment/issues/478)) ([cc99635](https://github.com/cgrime01/allotment/commit/cc996352755e90fb343be797f573869a586ad072))
- **deps:** update docusaurus monorepo to v2.3.0 ([#542](https://github.com/cgrime01/allotment/issues/542)) ([b6d6726](https://github.com/cgrime01/allotment/commit/b6d67260bcc31586c31d75a546d0103f9a684322))
- **deps:** update docusaurus monorepo to v2.3.1 ([#547](https://github.com/cgrime01/allotment/issues/547)) ([a2c20d2](https://github.com/cgrime01/allotment/commit/a2c20d2fe1162f4d55f5b77eab7a104e9d89e990))
- **deps:** update docusaurus monorepo to v2.4.0 ([#593](https://github.com/cgrime01/allotment/issues/593)) ([fa63a3f](https://github.com/cgrime01/allotment/commit/fa63a3f4e12faa891f0cd4c5d3fd561c56b5f5a3))
- **deps:** update docusaurus monorepo to v2.4.1 ([#611](https://github.com/cgrime01/allotment/issues/611)) ([729d25b](https://github.com/cgrime01/allotment/commit/729d25beff64aea1d57fb96c335c6cd14f5ce9cf))
- **deps:** update react monorepo to v18 ([#214](https://github.com/cgrime01/allotment/issues/214)) ([3263b4b](https://github.com/cgrime01/allotment/commit/3263b4b2a5a24e9d97e8ff4a2db3f783240ee97a))
- distribute space evenly when adding a pane ([#58](https://github.com/cgrime01/allotment/issues/58)) ([6feb767](https://github.com/cgrime01/allotment/commit/6feb767cb8a289f5c167ae981b435e4c02f50215))
- enable pane content focus on mount ([#404](https://github.com/cgrime01/allotment/issues/404)) ([bfb34cd](https://github.com/cgrime01/allotment/commit/bfb34cd562c96c556871c1739c2eab822b470e84))
- export LayoutPriority as enum and not const enum ([#359](https://github.com/cgrime01/allotment/issues/359)) ([eb5403b](https://github.com/cgrime01/allotment/commit/eb5403b619be3c01fb96502d474e3cefbc508d41))
- export LayoutPriority enum ([#357](https://github.com/cgrime01/allotment/issues/357)) ([4b85d01](https://github.com/cgrime01/allotment/commit/4b85d01fcd7e46597d5d2a198fb9973f8d6efdfa))
- export LayoutPriority enum as value not type ([51eb90e](https://github.com/cgrime01/allotment/commit/51eb90e7fd9e8b79787d5a04143d91a327055f7a))
- handle preferredSize correctly if unit is px ([#552](https://github.com/cgrime01/allotment/issues/552)) ([c02f059](https://github.com/cgrime01/allotment/commit/c02f05909b5d9ff18a051beb352ef37ded04f514))
- initialize dimensions before first paint ([#526](https://github.com/cgrime01/allotment/issues/526)) ([2706777](https://github.com/cgrime01/allotment/commit/2706777f3a7e84b3f12ad8f9684681e1328041c3))
- onChange prop can now be updated ([#239](https://github.com/cgrime01/allotment/issues/239)) ([ea96c28](https://github.com/cgrime01/allotment/commit/ea96c28c3e99d149774d8e46359eddb439dcd504))
- preferredSize should work with defaultSizes ([5398f2f](https://github.com/cgrime01/allotment/commit/5398f2fe6fa466fe6ed05fb3e7ced61745b8ca51))
- remove requirement to use Allotment.Pane if using refs with children ([93a30bb](https://github.com/cgrime01/allotment/commit/93a30bb58c9d12b1a3b4a441f57613aea79e7923))
- replace remaining uses of sizes with defaultSizes ([cf5e2c1](https://github.com/cgrime01/allotment/commit/cf5e2c1dd77dd5a3edc4bd6f903acb824a90ed39))
- respect visible prop on initial render ([5daeeaf](https://github.com/cgrime01/allotment/commit/5daeeafdc50c810ade14f02492bb73ad343164fc))
- set css custom variables if touch device detected ([2eb8c38](https://github.com/cgrime01/allotment/commit/2eb8c387009f013bd0440b83f4a41a53277c76ff))
- set text-align to initial for sashes ([#307](https://github.com/cgrime01/allotment/issues/307)) ([aef12f9](https://github.com/cgrime01/allotment/commit/aef12f973e310c016bbf99a20f9193320d7bce79))
- support removing more than one pane at a time ([#320](https://github.com/cgrime01/allotment/issues/320)) ([8b3b444](https://github.com/cgrime01/allotment/commit/8b3b44497ea9a732c7c7f229701dbe197cc81c64))
- use custom onReset callback for programatic reset ([978c0be](https://github.com/cgrime01/allotment/commit/978c0be46b1427056b7ecc0101fe2090720354ad))
- visible prop not working as expected ([d06931b](https://github.com/cgrime01/allotment/commit/d06931b7ba37248f4c61f0768d3ba571141b4fdf))

## [1.19.0](https://github.com/johnwalley/allotment/compare/v1.18.1...v1.19.0) (2023-04-25)

### Features

- add support for onDragStart and onDragEnd callbacks ([#576](https://github.com/johnwalley/allotment/issues/576)) ([722e8af](https://github.com/johnwalley/allotment/commit/722e8af9e696d14390dad9d7ffd8b5614d7c58d6))

### [1.18.1](https://github.com/johnwalley/allotment/compare/v1.18.0...v1.18.1) (2023-02-12)

### Bug Fixes

- handle preferredSize correctly if unit is px ([#552](https://github.com/johnwalley/allotment/issues/552)) ([c02f059](https://github.com/johnwalley/allotment/commit/c02f05909b5d9ff18a051beb352ef37ded04f514))

## [1.18.0](https://github.com/johnwalley/allotment/compare/v1.17.0...v1.18.0) (2023-02-02)

### Features

- add classname `split-view-sash-dragging` for top-level container ([#536](https://github.com/johnwalley/allotment/issues/536)) ([a59c774](https://github.com/johnwalley/allotment/commit/a59c774eec366070614bd95033157839139b0263))

### Bug Fixes

- initialize dimensions before first paint ([#526](https://github.com/johnwalley/allotment/issues/526)) ([2706777](https://github.com/johnwalley/allotment/commit/2706777f3a7e84b3f12ad8f9684681e1328041c3))

### [1.17.1](https://github.com/johnwalley/allotment/compare/v1.17.0...v1.17.1) (2022-12-15)

### Bug Fixes

- enable pane content focus on mount ([#404](https://github.com/johnwalley/allotment/issues/404)) ([bfb34cd](https://github.com/johnwalley/allotment/commit/bfb34cd562c96c556871c1739c2eab822b470e84))

## [1.17.0](https://github.com/johnwalley/allotment/compare/v1.16.0...v1.17.0) (2022-08-24)

### Features

- add split-view-separator-border class ([#406](https://github.com/johnwalley/allotment/issues/406)) ([8843ff4](https://github.com/johnwalley/allotment/commit/8843ff450e1021393f839882be5ff17cbe526d0e))

## [1.16.0](https://github.com/johnwalley/allotment/compare/v1.15.0...v1.16.0) (2022-08-16)

### Features

- support disabling separator ([#388](https://github.com/johnwalley/allotment/issues/388)) ([283d01d](https://github.com/johnwalley/allotment/commit/283d01d6d761bc346b3fe871cdda5e81382044bd))

### Bug Fixes

- **deps:** update docusaurus monorepo to v2.0.1 ([#379](https://github.com/johnwalley/allotment/issues/379)) ([586fb5e](https://github.com/johnwalley/allotment/commit/586fb5e0d29313f54a9f7d66674cdbc31f73f58d))

## [1.15.0](https://github.com/johnwalley/allotment/compare/v1.14.4...v1.15.0) (2022-07-29)

### Features

- add stable classnames to child elements ([#375](https://github.com/johnwalley/allotment/issues/375)) ([326f771](https://github.com/johnwalley/allotment/commit/326f771d9c4a3d7dba1fc4f1b1596d50f723a7cd))

### Bug Fixes

- export LayoutPriority as enum and not const enum ([#359](https://github.com/johnwalley/allotment/issues/359)) ([eb5403b](https://github.com/johnwalley/allotment/commit/eb5403b619be3c01fb96502d474e3cefbc508d41))

### [1.14.5](https://github.com/johnwalley/allotment/compare/v1.14.4...v1.14.5) (2022-07-11)

### Bug Fixes

- export LayoutPriority as enum and not const enum ([#359](https://github.com/johnwalley/allotment/issues/359)) ([eb5403b](https://github.com/johnwalley/allotment/commit/eb5403b619be3c01fb96502d474e3cefbc508d41))

### [1.14.4](https://github.com/johnwalley/allotment/compare/v1.14.3...v1.14.4) (2022-07-11)

### Bug Fixes

- export LayoutPriority enum as value not type ([51eb90e](https://github.com/johnwalley/allotment/commit/51eb90e7fd9e8b79787d5a04143d91a327055f7a))

### [1.14.3](https://github.com/johnwalley/allotment/compare/v1.14.1...v1.14.3) (2022-07-11)

### Bug Fixes

- export LayoutPriority enum ([#357](https://github.com/johnwalley/allotment/issues/357)) ([4b85d01](https://github.com/johnwalley/allotment/commit/4b85d01fcd7e46597d5d2a198fb9973f8d6efdfa))
- support removing more than one pane at a time ([#320](https://github.com/johnwalley/allotment/issues/320)) ([8b3b444](https://github.com/johnwalley/allotment/commit/8b3b44497ea9a732c7c7f229701dbe197cc81c64))

### [1.14.2](https://github.com/johnwalley/allotment/compare/v1.14.1...v1.14.2) (2022-06-06)

### Bug Fixes

- support removing more than one pane at a time ([#320](https://github.com/johnwalley/allotment/issues/320)) ([8b3b444](https://github.com/johnwalley/allotment/commit/8b3b44497ea9a732c7c7f229701dbe197cc81c64))

### [1.14.1](https://github.com/johnwalley/allotment/compare/v1.14.0...v1.14.1) (2022-05-25)

### Bug Fixes

- set text-align to initial for sashes ([#307](https://github.com/johnwalley/allotment/issues/307)) ([aef12f9](https://github.com/johnwalley/allotment/commit/aef12f973e310c016bbf99a20f9193320d7bce79))

## [1.14.0](https://github.com/johnwalley/allotment/compare/v1.13.0...v1.14.0) (2022-05-20)

### Features

- apply overflow hidden to panes ([#271](https://github.com/johnwalley/allotment/issues/271)) ([9d8d7c9](https://github.com/johnwalley/allotment/commit/9d8d7c918d1454a849c7c49968a1873259869246))

## [1.13.0](https://github.com/johnwalley/allotment/compare/v1.12.1...v1.13.0) (2022-05-03)

### Features

- add layout priority prop ([#267](https://github.com/johnwalley/allotment/issues/267)) ([f8bb905](https://github.com/johnwalley/allotment/commit/f8bb905085faf85a738e8d4ac5e4899964ef358f))

### Bug Fixes

- onChange prop can now be updated ([#239](https://github.com/johnwalley/allotment/issues/239)) ([ea96c28](https://github.com/johnwalley/allotment/commit/ea96c28c3e99d149774d8e46359eddb439dcd504))

### [1.12.1](https://github.com/johnwalley/allotment/compare/v1.12.0...v1.12.1) (2022-04-11)

## [1.12.0](https://github.com/johnwalley/allotment/compare/v1.11.2...v1.12.0) (2022-04-11)

### Features

- add onVisibleChange callback ([#222](https://github.com/johnwalley/allotment/issues/222)) ([39f9bec](https://github.com/johnwalley/allotment/commit/39f9bec2627b7496ee6270fe3ff67e8a1f90e94e))
- add preferredSize prop ([#229](https://github.com/johnwalley/allotment/issues/229)) ([3be2144](https://github.com/johnwalley/allotment/commit/3be21441660475a5c71c604dbb11ac84630df913))
- avoid unmounting pane with same key which changes position ([#226](https://github.com/johnwalley/allotment/issues/226)) ([f7d077a](https://github.com/johnwalley/allotment/commit/f7d077a1d71d51139ce7386be0538dcdd29c08e1))
- dynamic minSize and maxSize ([#227](https://github.com/johnwalley/allotment/issues/227)) ([d764ebe](https://github.com/johnwalley/allotment/commit/d764ebe241faead5bdecd9311135ff1f39a40935))

### Bug Fixes

- preferredSize should work with defaultSizes ([5398f2f](https://github.com/johnwalley/allotment/commit/5398f2fe6fa466fe6ed05fb3e7ced61745b8ca51))
- use custom onReset callback for programatic reset ([978c0be](https://github.com/johnwalley/allotment/commit/978c0be46b1427056b7ecc0101fe2090720354ad))

### [1.11.2](https://github.com/johnwalley/allotment/compare/v1.11.1...v1.11.2) (2022-04-02)

### Bug Fixes

- defaultSizes should not disable props on Allotment.Pane ([3837d87](https://github.com/johnwalley/allotment/commit/3837d87538089cea6c53635f9a657fcf75296b9e))

### [1.11.1](https://github.com/johnwalley/allotment/compare/v1.11.0...v1.11.1) (2022-03-26)

### Bug Fixes

- visible prop not working as expected ([d06931b](https://github.com/johnwalley/allotment/commit/d06931b7ba37248f4c61f0768d3ba571141b4fdf))

## [1.11.0](https://github.com/johnwalley/allotment/compare/v1.10.0...v1.11.0) (2022-03-09)

### Features

- add prop for setting proportionalLayout ([#179](https://github.com/johnwalley/allotment/issues/179)) ([4f8f68c](https://github.com/johnwalley/allotment/commit/4f8f68c3d2ae99108b97befc5ab787873c7e3f77))

## [1.10.0](https://github.com/johnwalley/allotment/compare/v1.9.1...v1.10.0) (2022-02-20)

### Features

- use className prop on Allotment component ([8e1b6bd](https://github.com/johnwalley/allotment/commit/8e1b6bde537d03318bd441b9dfdb2816c20bfb2c))

### [1.9.1](https://github.com/johnwalley/allotment/compare/v1.9.0...v1.9.1) (2022-02-20)

### Bug Fixes

- respect visible prop on initial render ([5daeeaf](https://github.com/johnwalley/allotment/commit/5daeeafdc50c810ade14f02492bb73ad343164fc))

## [1.9.0](https://github.com/johnwalley/allotment/compare/v1.8.0...v1.9.0) (2022-02-10)

### Features

- add className prop to Allotment.Pane ([#108](https://github.com/johnwalley/allotment/issues/108)) ([9486638](https://github.com/johnwalley/allotment/commit/94866382d2580220a3502f8194c18eb93cd721ec))

## [1.8.0](https://github.com/johnwalley/allotment/compare/v1.7.0...v1.8.0) (2022-02-08)

### Features

- add onReset callback ([#154](https://github.com/johnwalley/allotment/issues/154)) ([904a8e6](https://github.com/johnwalley/allotment/commit/904a8e6acbf3692b4f2cb7fa102799872c70243d))
- add resize method to component instance ([#121](https://github.com/johnwalley/allotment/issues/121)) ([d25bd91](https://github.com/johnwalley/allotment/commit/d25bd91bde05c33bdebf586868a38a03056d8d57))
- add visible prop to Pane ([#137](https://github.com/johnwalley/allotment/issues/137)) ([3b0542c](https://github.com/johnwalley/allotment/commit/3b0542c24165c0cb054ee12a682c1b153a2de5ad))

## [1.7.0](https://github.com/johnwalley/allotment/compare/v1.6.0...v1.7.0) (2022-01-22)

### Features

- separator color which works better on light and dark backgrounds ([a769262](https://github.com/johnwalley/allotment/commit/a769262de79658cda4866edbafe4ffb8e5f0773a))

### Bug Fixes

- call cancel hover after pointer up ([#129](https://github.com/johnwalley/allotment/issues/129)) ([b9a6e5f](https://github.com/johnwalley/allotment/commit/b9a6e5f10f89298e9935f14c9d52f63ec8527e2c))

### [1.6.0](https://github.com/johnwalley/allotment/compare/v1.5.2...v1.6.0) (2022-01-16)

### Bug Fixes

- allow changing order of panes ([cc38223](https://github.com/johnwalley/allotment/commit/cc38223e3f4315f61a50126630170c25ab8b5e1f))

### [1.5.2](https://github.com/johnwalley/allotment/compare/v1.5.1...v1.5.2) (2022-01-15)

This release was published without any updates and should be skipped.

### [1.5.1](https://github.com/johnwalley/allotment/compare/v1.5.0...v1.5.1) (2022-01-02)

### Bug Fixes

- set css custom variables if touch device detected ([2eb8c38](https://github.com/johnwalley/allotment/commit/2eb8c387009f013bd0440b83f4a41a53277c76ff))

## [1.5.0](https://github.com/johnwalley/allotment/compare/v1.4.2...v1.5.0) (2021-12-26)

### Features

- enable sash size to be customised in code ([#101](https://github.com/johnwalley/allotment/issues/101)) ([f177e48](https://github.com/johnwalley/allotment/commit/f177e48bdf4e12533b8e5dcdd76cd94802c83710))

### [1.4.2](https://github.com/johnwalley/allotment/compare/v1.4.1...v1.4.2) (2021-12-24)

### Bug Fixes

- replace remaining uses of sizes with defaultSizes ([cf5e2c1](https://github.com/johnwalley/allotment/commit/cf5e2c1dd77dd5a3edc4bd6f903acb824a90ed39))

### [1.4.1](https://github.com/johnwalley/allotment/compare/v1.4.0...v1.4.1) (2021-12-05)

### Bug Fixes

- defaultSizes needs to be used ([#77](https://github.com/johnwalley/allotment/issues/77)) ([cd2eae1](https://github.com/johnwalley/allotment/commit/cd2eae13116af91af00846e212452287cfb7c607))

## [1.4.0](https://github.com/johnwalley/allotment/compare/v1.3.0...v1.4.0) (2021-12-05)

### Features

- increase sash size on touch devices ([#66](https://github.com/johnwalley/allotment/issues/66)) ([20ab7d9](https://github.com/johnwalley/allotment/commit/20ab7d93ab836af864a67531b3c5c1244e23a3b8))

## [1.3.0](https://github.com/johnwalley/allotment/compare/v1.2.0...v1.3.0) (2021-12-03)

### Features

- add defaultSizes prop and deprecate sizes prop ([#72](https://github.com/johnwalley/allotment/issues/72)) ([2ece9ce](https://github.com/johnwalley/allotment/commit/2ece9ce2f8142d1c28b5394743d73f920f4489e2))
- add imperative reset method ([#69](https://github.com/johnwalley/allotment/issues/69)) ([aceb88f](https://github.com/johnwalley/allotment/commit/aceb88f2de9e454dfce2ccd35bc4e23c8d8e3cb7))

### Bug Fixes

- distribute space evenly when adding a pane ([#58](https://github.com/johnwalley/allotment/issues/58)) ([6feb767](https://github.com/johnwalley/allotment/commit/6feb767cb8a289f5c167ae981b435e4c02f50215))

## [1.2.0](https://github.com/johnwalley/allotment/compare/v1.1.0...v1.2.0) (2021-10-03)

### Features

- support setting initial sizes ([#14](https://github.com/johnwalley/allotment/issues/14)) ([b07415e](https://github.com/johnwalley/allotment/commit/b07415e0539ca28f123a143c88aa28de7ec80b75))

## [1.1.0](https://github.com/johnwalley/allotment/compare/v1.0.1...v1.1.0) (2021-09-30)

### Features

- set props on children ([#9](https://github.com/johnwalley/allotment/issues/9)) ([180ed52](https://github.com/johnwalley/allotment/commit/180ed52bced6d74860142092f27800728896d97e))

### Bug Fixes

- center sash ([#12](https://github.com/johnwalley/allotment/issues/12)) ([d2b7486](https://github.com/johnwalley/allotment/commit/d2b74867dae30ae05f3f20f4d4a29cc8ebc7a9e7))

### [1.0.1](https://github.com/johnwalley/allotment/compare/v1.0.0...v1.0.1) (2021-09-24)

### Bug Fixes

- remove requirement to use Allotment.Pane if using refs with children ([93a30bb](https://github.com/johnwalley/allotment/commit/93a30bb58c9d12b1a3b4a441f57613aea79e7923))

## 1.0.0 (2021-09-23)

### Features

- basic functionality ([#1](https://github.com/johnwalley/allotment/issues/1)) ([36b4442](https://github.com/johnwalley/allotment/commit/36b44425f9ea8d6d18e2e74cabfbc9813c52c0fd))
