# Changelog

## [1.0.0](https://github.com/jchip/ts2mjs/compare/v3.0.0...v1.0.0) (2025-07-05)


### ⚠ BREAKING CHANGES

* Drop support for Node16 ([#122](https://github.com/jchip/ts2mjs/issues/122))
* Require Node 16+ ([#65](https://github.com/jchip/ts2mjs/issues/65))

### Features

* add --remove-source option to delete original files after conversion ([6cc7eef](https://github.com/jchip/ts2mjs/commit/6cc7eef5d7daa52b025d266a631e670f5e00cf7e))
* add --skip-ts option to avoid renaming *.ts files ([3a64548](https://github.com/jchip/ts2mjs/commit/3a64548ffa5055925c89ed346f7927db68a80b18))
* Add option `--exclude` ([#71](https://github.com/jchip/ts2mjs/issues/71)) ([0d66c08](https://github.com/jchip/ts2mjs/commit/0d66c086da16fdce562d6eaed8635ee9b7247032))
* Drop support for Node16 ([#122](https://github.com/jchip/ts2mjs/issues/122)) ([630bdc3](https://github.com/jchip/ts2mjs/commit/630bdc3cde664c6f94a2a219ded21cf2700a4681))
* Generate Source Maps ([#3](https://github.com/jchip/ts2mjs/issues/3)) ([226e9a8](https://github.com/jchip/ts2mjs/commit/226e9a8c28736901ec3765cc5aacb28669e8e30b))
* Support generating .cjs files ([#69](https://github.com/jchip/ts2mjs/issues/69)) ([73c88e9](https://github.com/jchip/ts2mjs/commit/73c88e9e5f6eef4ce007e53afe3f9b95c1e5e196))


### Bug Fixes

* Error on import outside of root ([#6](https://github.com/jchip/ts2mjs/issues/6)) ([d54787c](https://github.com/jchip/ts2mjs/commit/d54787c368536c85172ca7e8397d86331679db43))
* handle duplicate require imports by relaxing regex pattern ([ff99362](https://github.com/jchip/ts2mjs/commit/ff993625a2ee14a73387123ce803db041b18fafe))
* ignore .ts/.d.ts files - no .cts or .d.mts please ([489f55d](https://github.com/jchip/ts2mjs/commit/489f55d5905c1aee9aefa70279e4af06e2de2b18))
* Remove debug output ([#76](https://github.com/jchip/ts2mjs/issues/76)) ([c70b3a8](https://github.com/jchip/ts2mjs/commit/c70b3a85e7761c55523bd41becb6c28d78758010))
* Require Node 16+ ([#65](https://github.com/jchip/ts2mjs/issues/65)) ([201ce50](https://github.com/jchip/ts2mjs/commit/201ce50ddf02b721fd7c1255b9f80ecc9171661f))
* Skip files where the src and target are the same ([#13](https://github.com/jchip/ts2mjs/issues/13)) ([1f3ccca](https://github.com/jchip/ts2mjs/commit/1f3ccca067e550df5601fc5821ffb1de25251e2f))


### Miscellaneous Chores

* release 1.0.0 ([ecf4db3](https://github.com/jchip/ts2mjs/commit/ecf4db3dab534b5490fb3f9f5720669419e704db))

## [3.0.0](https://github.com/streetsidesoftware/ts2mjs/compare/v2.1.1...v3.0.0) (2024-03-03)


### ⚠ BREAKING CHANGES

* Drop support for Node16 ([#122](https://github.com/streetsidesoftware/ts2mjs/issues/122))

### Features

* Drop support for Node16 ([#122](https://github.com/streetsidesoftware/ts2mjs/issues/122)) ([630bdc3](https://github.com/streetsidesoftware/ts2mjs/commit/630bdc3cde664c6f94a2a219ded21cf2700a4681))

## [2.1.1](https://github.com/streetsidesoftware/ts2mjs/compare/v2.1.0...v2.1.1) (2023-08-28)


### Bug Fixes

* Remove debug output ([#76](https://github.com/streetsidesoftware/ts2mjs/issues/76)) ([c70b3a8](https://github.com/streetsidesoftware/ts2mjs/commit/c70b3a85e7761c55523bd41becb6c28d78758010))

## [2.1.0](https://github.com/streetsidesoftware/ts2mjs/compare/v2.0.0...v2.1.0) (2023-08-26)


### Features

* Add option `--exclude` ([#71](https://github.com/streetsidesoftware/ts2mjs/issues/71)) ([0d66c08](https://github.com/streetsidesoftware/ts2mjs/commit/0d66c086da16fdce562d6eaed8635ee9b7247032))
* Support generating .cjs files ([#69](https://github.com/streetsidesoftware/ts2mjs/issues/69)) ([73c88e9](https://github.com/streetsidesoftware/ts2mjs/commit/73c88e9e5f6eef4ce007e53afe3f9b95c1e5e196))

## [2.0.0](https://github.com/streetsidesoftware/ts2mjs/compare/v1.1.2...v2.0.0) (2023-08-21)


### ⚠ BREAKING CHANGES

* Require Node 16+ ([#65](https://github.com/streetsidesoftware/ts2mjs/issues/65))

### Bug Fixes

* Require Node 16+ ([#65](https://github.com/streetsidesoftware/ts2mjs/issues/65)) ([201ce50](https://github.com/streetsidesoftware/ts2mjs/commit/201ce50ddf02b721fd7c1255b9f80ecc9171661f))

## [1.1.2](https://github.com/streetsidesoftware/ts2mjs/compare/v1.1.1...v1.1.2) (2023-03-06)


### Bug Fixes

* Skip files where the src and target are the same ([#13](https://github.com/streetsidesoftware/ts2mjs/issues/13)) ([1f3ccca](https://github.com/streetsidesoftware/ts2mjs/commit/1f3ccca067e550df5601fc5821ffb1de25251e2f))

## [1.1.1](https://github.com/streetsidesoftware/ts2mjs/compare/v1.1.0...v1.1.1) (2023-02-19)


### Bug Fixes

* Error on import outside of root ([#6](https://github.com/streetsidesoftware/ts2mjs/issues/6)) ([d54787c](https://github.com/streetsidesoftware/ts2mjs/commit/d54787c368536c85172ca7e8397d86331679db43))

## [1.1.0](https://github.com/streetsidesoftware/ts2mjs/compare/v1.0.0...v1.1.0) (2023-02-19)


### Features

* Generate Source Maps ([#3](https://github.com/streetsidesoftware/ts2mjs/issues/3)) ([226e9a8](https://github.com/streetsidesoftware/ts2mjs/commit/226e9a8c28736901ec3765cc5aacb28669e8e30b))

## [1.0.0](https://github.com/streetsidesoftware/ts2mjs/compare/v1.0.1...v1.0.0) (2023-02-18)


### Miscellaneous Chores

* release 1.0.0 ([ecf4db3](https://github.com/streetsidesoftware/ts2mjs/commit/ecf4db3dab534b5490fb3f9f5720669419e704db))

## Changelog
