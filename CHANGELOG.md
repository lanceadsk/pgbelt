# Changelog

## [0.6.1](https://github.com/Autodesk/pgbelt/compare/v0.6.0...v0.6.1) (2024-01-22)


### Bug Fixes

* pglogical teardown will now always revoke all from all tables from pglogical role ([#362](https://github.com/Autodesk/pgbelt/issues/362)) ([89e892c](https://github.com/Autodesk/pgbelt/commit/89e892c323ffda4bfbedd4d4a04ec612202cbe81))

## [0.6.0](https://github.com/Autodesk/pgbelt/compare/v0.5.4...v0.6.0) (2023-11-20)


### Features

* refactor Teardown Command due to DROP EXTENSION woes ([#326](https://github.com/Autodesk/pgbelt/issues/326)) ([5de6300](https://github.com/Autodesk/pgbelt/commit/5de6300d597f3e3f45dd03b83c286fcc07b1ced0))

## [0.5.4](https://github.com/Autodesk/pgbelt/compare/v0.5.3...v0.5.4) (2023-11-09)


### Bug Fixes

* bump pydantic from 1.10.13 to 2.4.2 ([#299](https://github.com/Autodesk/pgbelt/issues/299)) ([8597fcc](https://github.com/Autodesk/pgbelt/commit/8597fccca106606dd1513839bc23c170383f3f2b))

## [0.5.3](https://github.com/Autodesk/pgbelt/compare/v0.5.2...v0.5.3) (2023-11-09)


### Bug Fixes

* grant pglogical schema usage [#278](https://github.com/Autodesk/pgbelt/issues/278) ([#318](https://github.com/Autodesk/pgbelt/issues/318)) ([0de9290](https://github.com/Autodesk/pgbelt/commit/0de929074db26e5ca3d47ab9adfbf9bc3d055f0f))

## [0.5.2](https://github.com/Autodesk/pgbelt/compare/v0.5.1...v0.5.2) (2023-10-26)


### Bug Fixes

* remote.py error handling needs to shore up plugin error ([#311](https://github.com/Autodesk/pgbelt/issues/311)) ([b47b07f](https://github.com/Autodesk/pgbelt/commit/b47b07f6705b1c8548b67d17b69e5a29e2de5178))

## [0.5.1](https://github.com/Autodesk/pgbelt/compare/v0.5.0...v0.5.1) (2023-10-06)


### Bug Fixes

* index commands need to surface as CLI commands too ([#275](https://github.com/Autodesk/pgbelt/issues/275)) ([a8d6fae](https://github.com/Autodesk/pgbelt/commit/a8d6faef753d434a6883aac5797c2b0cb952e86a))

## [0.5.0](https://github.com/Autodesk/pgbelt/compare/v0.4.0...v0.5.0) (2023-10-06)


### Features

* stripping indexes and adding them later, and testing ([#273](https://github.com/Autodesk/pgbelt/issues/273)) ([c730e78](https://github.com/Autodesk/pgbelt/commit/c730e7852fdf40001633fd074b5aac4128a48af2))


### Bug Fixes

* precheck parameter value guidelines updated for [#267](https://github.com/Autodesk/pgbelt/issues/267) ([#268](https://github.com/Autodesk/pgbelt/issues/268)) ([e423929](https://github.com/Autodesk/pgbelt/commit/e42392993da1500ef564c3f6cc287f89531651e0))

## [0.4.0](https://github.com/Autodesk/pgbelt/compare/v0.3.0...v0.4.0) (2023-07-10)


### Features

* ability to not write logs to disk if needed ([#255](https://github.com/Autodesk/pgbelt/issues/255)) ([69469c0](https://github.com/Autodesk/pgbelt/commit/69469c0c16f1891992e7d15f4725369de3162cd7))

## [0.3.0](https://github.com/Autodesk/pgbelt/compare/v0.2.4...v0.3.0) (2023-06-29)


### Features

* check-connectivity command ([#253](https://github.com/Autodesk/pgbelt/issues/253)) ([6ebfff7](https://github.com/Autodesk/pgbelt/commit/6ebfff7a80573a1a33f1c54096fe300786e205c3))

## [0.2.4](https://github.com/Autodesk/pgbelt/compare/v0.2.3...v0.2.4) (2023-06-15)


### Bug Fixes

* allowing backwards compatibility down to python 3.9 ([#247](https://github.com/Autodesk/pgbelt/issues/247)) ([78b2fd8](https://github.com/Autodesk/pgbelt/commit/78b2fd8d05368f23ecd6c1ece223893bb424731c))

## [0.2.3](https://github.com/Autodesk/pgbelt/compare/v0.2.2...v0.2.3) (2023-05-04)


### Bug Fixes

* double quotes on table names ([#228](https://github.com/Autodesk/pgbelt/issues/228)) ([893773a](https://github.com/Autodesk/pgbelt/commit/893773aa113b719f32e4e5486e585c584499cd9e))

## [0.2.2](https://github.com/Autodesk/pgbelt/compare/v0.2.1...v0.2.2) (2023-05-02)


### Bug Fixes

* undo bump of virtualenv, back to 20.21.0 ([#223](https://github.com/Autodesk/pgbelt/issues/223)) ([01bfe6f](https://github.com/Autodesk/pgbelt/commit/01bfe6fc167df009d451ac83666f1075a4a0ae05))

## [0.2.1](https://github.com/Autodesk/pgbelt/compare/v0.2.0...v0.2.1) (2023-05-02)


### Bug Fixes

* typer doesn't support union types from python 3.11 ([#220](https://github.com/Autodesk/pgbelt/issues/220)) ([0315390](https://github.com/Autodesk/pgbelt/commit/03153909bcdf4e621b3e7c66aa5a99e55c9ceea4))

## [0.2.0](https://github.com/Autodesk/pgbelt/compare/v0.1.2...v0.2.0) (2023-04-28)


### Features

* update to python 3.11 ([#191](https://github.com/Autodesk/pgbelt/issues/191)) ([3c44681](https://github.com/Autodesk/pgbelt/commit/3c44681bfda3679bff10022eb9bfcb56fdd9e50a))


### Bug Fixes

* incorrect precheck command in quickstart.md ([#172](https://github.com/Autodesk/pgbelt/issues/172)) ([36ce96f](https://github.com/Autodesk/pgbelt/commit/36ce96feb6f5c98bcb3c7a0648a25e4f3b9ce655))
* no need to find and replace owners in schema ([#215](https://github.com/Autodesk/pgbelt/issues/215)) ([dfe1324](https://github.com/Autodesk/pgbelt/commit/dfe1324a56f57e75fa44dfe7196e104c34988695))

## [0.1.2](https://github.com/Autodesk/pgbelt/compare/v0.1.1...v0.1.2) (2022-10-03)

### Bug Fixes

- the analyze function should be run as root of a database for safest and least restriction [#87](https://github.com/Autodesk/pgbelt/issues/87) ([#90](https://github.com/Autodesk/pgbelt/issues/90)) ([81c5fde](https://github.com/Autodesk/pgbelt/commit/81c5fde8d1db4be797389a0ff361c00ee3329ab2))
- validator supposed to check 100 rows, not 1 ([#93](https://github.com/Autodesk/pgbelt/issues/93)) ([48122dc](https://github.com/Autodesk/pgbelt/commit/48122dca57b51b3f8114380840e510d70c75eaae))

## [0.1.1](https://github.com/Autodesk/pgbelt/compare/v0.1.0...v0.1.1) (2022-09-30)

### Documentation

- update README and quickstart now that pgbelt is on pypi ([#79](https://github.com/Autodesk/pgbelt/issues/79)) ([2a2d4c9](https://github.com/Autodesk/pgbelt/commit/2a2d4c91aaa8e961c2958df2f6150982b8b66c77))

## 0.1.0 (2022-09-02)

### Features

- convert to poetry ([07f9a10](https://github.com/Autodesk/pgbelt/commit/07f9a102aed7392e91dc7bffddb41e2bdf69eb52))
- fresh upload of pgbelt with GHA CI ([4df9896](https://github.com/Autodesk/pgbelt/commit/4df98960d662a14c99bb2c60ec80ba3c0317b22b))

### Bug Fixes

- ci move to poetry too ([979c988](https://github.com/Autodesk/pgbelt/commit/979c988666dea0705cecc19fdd7cf941f17f2d6b))
- dev setup in Makefile also installs precommit ([c27cb09](https://github.com/Autodesk/pgbelt/commit/c27cb09615b7a448f31ca07fb6cdab6fe8a10f0f))
- flake8 baited, placing ignore, it broke pydantic ([#17](https://github.com/Autodesk/pgbelt/issues/17)) ([560207d](https://github.com/Autodesk/pgbelt/commit/560207df79276ceece0d4df00221e748f2718648))
- need code of conduct for open-sourcing ([#58](https://github.com/Autodesk/pgbelt/issues/58)) ([4aede91](https://github.com/Autodesk/pgbelt/commit/4aede91a9c4344d3fcaa1972bc6b00cdf70f5ce6))
- pre-commit fixed and run ([d3e188b](https://github.com/Autodesk/pgbelt/commit/d3e188bc2b9641614e8e63a5011adecf4db511e2))
- pre-commit fixes and flake8 config ([#15](https://github.com/Autodesk/pgbelt/issues/15)) ([958afd0](https://github.com/Autodesk/pgbelt/commit/958afd04b5f542704b15809274d039d0accc3cbe))
- remove rando .git file ([#5](https://github.com/Autodesk/pgbelt/issues/5)) ([16d38fd](https://github.com/Autodesk/pgbelt/commit/16d38fd2a7c607552191444d69d0f02212aecfc9))
- remove random .git files ([35213a5](https://github.com/Autodesk/pgbelt/commit/35213a518ce4f3450f462aceb6d139b6379f4cc1))
- update black and fix ci poetry ([5a7a88b](https://github.com/Autodesk/pgbelt/commit/5a7a88beb4cac34a7c1e65f686f8cd0fd1f6ac50))
