# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [8.1.0](https://github.com/Lumieducation/H5P-Nodejs-library/compare/v8.0.1...v8.1.0) (2021-06-05)


### Bug Fixes

* **deps:** update dependency i18next to v20.2.3 ([0bdc4e1](https://github.com/Lumieducation/H5P-Nodejs-library/commit/0bdc4e16eee8fb6c690dbf255e9328b2292f28ec))
* **deps:** update dependency i18next to v20.2.4 ([e04a9be](https://github.com/Lumieducation/H5P-Nodejs-library/commit/e04a9be805cec4db5d0bf2da3e9d8255f0fade6f))
* **deps:** update dependency i18next to v20.3.0 ([da4dd92](https://github.com/Lumieducation/H5P-Nodejs-library/commit/da4dd92d55aa03fbcc1d6bb08895738feb617df9))
* **deps:** update dependency i18next to v20.3.1 ([ab7e1d0](https://github.com/Lumieducation/H5P-Nodejs-library/commit/ab7e1d08dbf3e498713b6c99ed9d085b4dfd8d04))
* **deps:** update dependency i18next-http-middleware to v3.1.2 ([720b350](https://github.com/Lumieducation/H5P-Nodejs-library/commit/720b3504da4974263ad1a63ff40b9d5762920f36))
* **deps:** update dependency i18next-http-middleware to v3.1.3 ([9fd54b5](https://github.com/Lumieducation/H5P-Nodejs-library/commit/9fd54b5e0985e8229c41565fc8625b11fb28f62f))





## [8.0.1](https://github.com/Lumieducation/H5P-Nodejs-library/compare/v8.0.0...v8.0.1) (2021-05-11)

**Note:** Version bump only for package @lumieducation/h5p-examples





# [8.0.0](https://github.com/Lumieducation/H5P-Nodejs-library/compare/v7.5.2...v8.0.0) (2021-05-07)


### Bug Fixes

* **deps:** update dependency http-proxy-middleware to v1.3.0 ([8344b6c](https://github.com/Lumieducation/H5P-Nodejs-library/commit/8344b6ce54b2124a55bee6cbfdafa69f80bde107))
* **deps:** update dependency i18next to v20.2.2 ([9f62cd6](https://github.com/Lumieducation/H5P-Nodejs-library/commit/9f62cd66831b55432d196ea468235bd722409a02))


### Features

* **h5p-server:** core update ([#1366](https://github.com/Lumieducation/H5P-Nodejs-library/issues/1366)) ([75e1d96](https://github.com/Lumieducation/H5P-Nodejs-library/commit/75e1d96d8415e9485d33f4a690e71311ff7a5a4b))


### BREAKING CHANGES

* **h5p-server:** IH5PConfig type has new configuration values for the H5P Content Hub. Implementions need to extend their implementation accordingly and set default values. H5PAjaxEndpoint.postAjax has a new parameter for the query parameter "hubId". If implementations don't use the h5p-express package, you must change your code accordingly.





## [7.5.2](https://github.com/Lumieducation/H5P-Nodejs-library/compare/v7.5.1...v7.5.2) (2021-04-25)


### Bug Fixes

* **deps:** update dependency ajv to v8 ([#1248](https://github.com/Lumieducation/H5P-Nodejs-library/issues/1248)) ([90fcabd](https://github.com/Lumieducation/H5P-Nodejs-library/commit/90fcabda1cb756c4842de54a72095364183974fe))
* **deps:** update dependency i18next to v20.2.0 ([e8b7935](https://github.com/Lumieducation/H5P-Nodejs-library/commit/e8b79358fe682fda7bb95f0b78a294080995c453))
* **deps:** update dependency i18next to v20.2.1 ([01bb61d](https://github.com/Lumieducation/H5P-Nodejs-library/commit/01bb61db1427437ce3c654ee418519c758c1ece3))
* **deps:** update dependency i18next-http-middleware to v3.1.1 ([da158c5](https://github.com/Lumieducation/H5P-Nodejs-library/commit/da158c5b2df662cf129604caca682ae89288a481))





## [7.5.1](https://github.com/Lumieducation/H5P-Nodejs-library/compare/v7.5.0...v7.5.1) (2021-04-01)


### Bug Fixes

* **deps:** update dependency cache-manager to v3.4.2 ([0e84c95](https://github.com/Lumieducation/H5P-Nodejs-library/commit/0e84c95c88fcd063c2bb180e3e2421a8534bbaae))
* **deps:** update dependency cache-manager to v3.4.3 ([3321b47](https://github.com/Lumieducation/H5P-Nodejs-library/commit/3321b47c04a8ef3c43b4976da8ceae4f8f2cde56))
* **deps:** update dependency i18next-fs-backend to v1.1.1 ([308d2e3](https://github.com/Lumieducation/H5P-Nodejs-library/commit/308d2e3faa9f93583d7b2f634ee5c97e45df9586))





# [7.5.0](https://github.com/Lumieducation/H5P-Nodejs-library/compare/v7.3.1...v7.5.0) (2021-03-27)


### Bug Fixes

* **deps:** update dependency i18next to v20 ([#1215](https://github.com/Lumieducation/H5P-Nodejs-library/issues/1215)) ([5f6dd7d](https://github.com/Lumieducation/H5P-Nodejs-library/commit/5f6dd7df2dbf00d26f60a18e89156eb207c66b74))
* **deps:** update dependency i18next to v20.1.0 ([85c7b0b](https://github.com/Lumieducation/H5P-Nodejs-library/commit/85c7b0ba8985f315c99f6efdb76dbb74709b19e6))
* **deps:** update react monorepo to v17.0.2 ([333a447](https://github.com/Lumieducation/H5P-Nodejs-library/commit/333a447caf0ecb2dbee9ecd9116afd7b7064d56c))


### Features

* **h5p-server:** hub now localizable ([#1200](https://github.com/Lumieducation/H5P-Nodejs-library/issues/1200)) ([2d8505c](https://github.com/Lumieducation/H5P-Nodejs-library/commit/2d8505c55cf0c3bc95a60103f73d973cf92837cb))
* **h5p-server:** localization of library names ([#1205](https://github.com/Lumieducation/H5P-Nodejs-library/issues/1205)) ([977ec84](https://github.com/Lumieducation/H5P-Nodejs-library/commit/977ec844ee64f4c8f9af037e1f0bcd97ff84e42d))





# [7.4.0](https://github.com/Lumieducation/H5P-Nodejs-library/compare/v7.3.1...v7.4.0) (2021-03-21)


### Features

* **h5p-server:** hub now localizable ([#1200](https://github.com/Lumieducation/H5P-Nodejs-library/issues/1200)) ([494aaef](https://github.com/Lumieducation/H5P-Nodejs-library/commit/494aaef1e57763c5d5ad89868349f523207573a1))
* **h5p-server:** localization of library names ([#1205](https://github.com/Lumieducation/H5P-Nodejs-library/issues/1205)) ([dfbb892](https://github.com/Lumieducation/H5P-Nodejs-library/commit/dfbb89298688a4b7f9a1f6eae82dc52179d1c7b8))





## [7.3.1](https://github.com/Lumieducation/H5P-Nodejs-library/compare/v7.3.0...v7.3.1) (2021-03-14)

**Note:** Version bump only for package @lumieducation/h5p-examples





# [7.3.0](https://github.com/Lumieducation/H5P-Nodejs-library/compare/v7.2.0...v7.3.0) (2021-03-14)


### Bug Fixes

* **deps:** update dependency cache-manager to v3.4.1 ([07ede73](https://github.com/Lumieducation/H5P-Nodejs-library/commit/07ede73933209f0c17eb5b5bebb3d182828df903))
* **deps:** update dependency i18next to v19.9.2 ([2f4379c](https://github.com/Lumieducation/H5P-Nodejs-library/commit/2f4379c83a196f6eecc1edcbcaf1f23452ee33d8))
* **deps:** update dependency i18next-http-middleware to v3.1.0 ([c729354](https://github.com/Lumieducation/H5P-Nodejs-library/commit/c729354271808d01665582220d613fc400411812))


### Features

* **h5p-mongos3:** new MongoLibraryStorage class ([#1118](https://github.com/Lumieducation/H5P-Nodejs-library/issues/1118)) ([050360f](https://github.com/Lumieducation/H5P-Nodejs-library/commit/050360f7411339959624d35793373e6f4503ddb9))





# [7.2.0](https://github.com/Lumieducation/H5P-Nodejs-library/compare/v7.1.0...v7.2.0) (2021-03-04)


### Features

* **h5p-mongos3:** new MongoLibraryStorage class ([#1118](https://github.com/Lumieducation/H5P-Nodejs-library/issues/1118)) ([9527dfd](https://github.com/Lumieducation/H5P-Nodejs-library/commit/9527dfd70701c924a4dbfa2bc4bb7c4949df4da0))





# [7.1.0](https://github.com/Lumieducation/H5P-Nodejs-library/compare/v6.2.0...v7.1.0) (2021-02-25)


### Features

* **h5p-mongos3:** new mongo-s3 library storage class ([#1062](https://github.com/Lumieducation/H5P-Nodejs-library/issues/1062)) ([9fc3da7](https://github.com/Lumieducation/H5P-Nodejs-library/commit/9fc3da734f5e98dca8fbbf4879f60118b16fb415))
* **h5p-react:** added xAPI collector to player ([5802e6f](https://github.com/Lumieducation/H5P-Nodejs-library/commit/5802e6fa287c743a7be638f06404d13f5444dd19))





## [7.0.2](https://github.com/Lumieducation/H5P-Nodejs-library/compare/v7.0.1...v7.0.2) (2021-02-18)

**Note:** Version bump only for package @lumieducation/h5p-examples





## [7.0.1](https://github.com/Lumieducation/H5P-Nodejs-library/compare/v7.0.0...v7.0.1) (2021-02-18)

**Note:** Version bump only for package @lumieducation/h5p-examples





# [7.0.0](https://github.com/Lumieducation/H5P-Nodejs-library/compare/v6.2.0...v7.0.0) (2021-02-18)

**Note:** Version bump only for package @lumieducation/h5p-examples
