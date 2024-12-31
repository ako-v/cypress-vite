# Changelog

## [1.6.0](https://github.com/ako-v/cypress-vite/compare/v1.5.0...v1.6.0) (2024-12-31)


### Features

* add caching ([df1c9a3](https://github.com/ako-v/cypress-vite/commit/df1c9a3520a768b3cae21fabdb67e32689f8f0b3))
* add cypress preprocessor ([ca20498](https://github.com/ako-v/cypress-vite/commit/ca204988801743631190e4ecd63f1ca65124cfaf))
* add debug support ([6d88a9a](https://github.com/ako-v/cypress-vite/commit/6d88a9a59cbfced7d048c18eac2ffa70b4ad4c85))
* add support for debugging ([f8f1678](https://github.com/ako-v/cypress-vite/commit/f8f16780b4aa82dc10712dca5ed113a11636d734))
* add support for debugging ([f8f1678](https://github.com/ako-v/cypress-vite/commit/f8f16780b4aa82dc10712dca5ed113a11636d734))
* add support for vite 3 ([#1](https://github.com/ako-v/cypress-vite/issues/1)) ([c683bed](https://github.com/ako-v/cypress-vite/commit/c683bedca45c041f47236a962ca052bf3089cfde))
* add support for Vite 4 and Cypress 12 ([#29](https://github.com/ako-v/cypress-vite/issues/29)) ([00dbb75](https://github.com/ako-v/cypress-vite/commit/00dbb75efdff30157f721f4f32ba5715c9c23b67))
* add support for vite^5.0.0 and cypress 13 ([#81](https://github.com/ako-v/cypress-vite/issues/81)) ([6027807](https://github.com/ako-v/cypress-vite/commit/6027807f0927372e1fdcfb36054e5b584310cc03))
* add user config support ([db71505](https://github.com/ako-v/cypress-vite/commit/db71505ba3d18493f5ad2913e564d3f90c490917))
* add watcher ([c85d76b](https://github.com/ako-v/cypress-vite/commit/c85d76b05c3d705146553f982dc4d4a21b73c247))
* allow user to specify full Vite config, not just `configFile` ([#53](https://github.com/ako-v/cypress-vite/issues/53)) ([293684f](https://github.com/ako-v/cypress-vite/commit/293684fc092692d247564aada08368ff6bf7de05))
* migrate to ES module syntax and update dependencies ([125302f](https://github.com/ako-v/cypress-vite/commit/125302f0a921fadb308e63e7cdd241e46f495b09))


### Bug Fixes

* add vite 3 to peerDependencies ([aa3ee7f](https://github.com/ako-v/cypress-vite/commit/aa3ee7f4ea9fa51652b07d1e86c4315c0d842318))
* ensure code is finished compiling before returning cached file ([#36](https://github.com/ako-v/cypress-vite/issues/36)) ([91ae5b8](https://github.com/ako-v/cypress-vite/commit/91ae5b8bd6f86008570f6e4db542a0ad30725187))
* fix dist bundle ([#47](https://github.com/ako-v/cypress-vite/issues/47)) ([ea7015a](https://github.com/ako-v/cypress-vite/commit/ea7015afc33b58e24066ceec6054cea3aa713e40))
* fix output config ([cfc2910](https://github.com/ako-v/cypress-vite/commit/cfc291066a19483d0961469ade137379fca18aff))
* fix the default export for cjs output ([#12](https://github.com/ako-v/cypress-vite/issues/12)) ([a1822a9](https://github.com/ako-v/cypress-vite/commit/a1822a9cd86dc641e4bf1b0e9c30c7d3179b7ad5)), closes [#10](https://github.com/ako-v/cypress-vite/issues/10)
* let vite handle resolving the config file ([#11](https://github.com/ako-v/cypress-vite/issues/11)) ([bbbadf9](https://github.com/ako-v/cypress-vite/commit/bbbadf9cf098ef87705f8642bdae7c2afc188ca8))
* override `ouput.manualChunks` using `false` ([#67](https://github.com/ako-v/cypress-vite/issues/67)) ([145627a](https://github.com/ako-v/cypress-vite/commit/145627ab09ed9e43089107126b5319d246eb97f2))
* override `rollupOptions.ouput.manualChunks` from the user config ([#58](https://github.com/ako-v/cypress-vite/issues/58)) ([c38600e](https://github.com/ako-v/cypress-vite/commit/c38600ec6a56af6e2c614e5532d430f352f3b130))
* use chokidar file watcher instead of Vite/Rollup watch ([#50](https://github.com/ako-v/cypress-vite/issues/50)) ([a2eec1d](https://github.com/ako-v/cypress-vite/commit/a2eec1d273cda0aa57eb5300804f42033a7e40dc))

## [1.5.0](https://github.com/mammadataei/cypress-vite/compare/v1.4.2...v1.5.0) (2023-11-22)


### Features

* add support for vite^5.0.0 and cypress 13 ([#81](https://github.com/mammadataei/cypress-vite/issues/81)) ([6027807](https://github.com/mammadataei/cypress-vite/commit/6027807f0927372e1fdcfb36054e5b584310cc03))

## [1.4.2](https://github.com/mammadataei/cypress-vite/compare/v1.4.1...v1.4.2) (2023-07-15)


### Bug Fixes

* override `ouput.manualChunks` using `false` ([#67](https://github.com/mammadataei/cypress-vite/issues/67)) ([145627a](https://github.com/mammadataei/cypress-vite/commit/145627ab09ed9e43089107126b5319d246eb97f2))

## [1.4.1](https://github.com/mammadataei/cypress-vite/compare/v1.4.0...v1.4.1) (2023-07-05)


### Bug Fixes

* override `rollupOptions.ouput.manualChunks` from the user config ([#58](https://github.com/mammadataei/cypress-vite/issues/58)) ([c38600e](https://github.com/mammadataei/cypress-vite/commit/c38600ec6a56af6e2c614e5532d430f352f3b130))

## [1.4.0](https://github.com/mammadataei/cypress-vite/compare/v1.3.2...v1.4.0) (2023-04-21)


### Features

* allow user to specify full Vite config, not just `configFile` ([#53](https://github.com/mammadataei/cypress-vite/issues/53)) ([293684f](https://github.com/mammadataei/cypress-vite/commit/293684fc092692d247564aada08368ff6bf7de05))


### Bug Fixes

* use chokidar file watcher instead of Vite/Rollup watch ([#50](https://github.com/mammadataei/cypress-vite/issues/50)) ([a2eec1d](https://github.com/mammadataei/cypress-vite/commit/a2eec1d273cda0aa57eb5300804f42033a7e40dc))

## [1.3.2](https://github.com/mammadataei/cypress-vite/compare/v1.3.1...v1.3.2) (2023-04-11)


### Bug Fixes

* fix dist bundle ([#47](https://github.com/mammadataei/cypress-vite/issues/47)) ([ea7015a](https://github.com/mammadataei/cypress-vite/commit/ea7015afc33b58e24066ceec6054cea3aa713e40))

## [1.3.1](https://github.com/mammadataei/cypress-vite/compare/v1.3.0...v1.3.1) (2023-03-02)


### Bug Fixes

* ensure code is finished compiling before returning cached file ([#36](https://github.com/mammadataei/cypress-vite/issues/36)) ([91ae5b8](https://github.com/mammadataei/cypress-vite/commit/91ae5b8bd6f86008570f6e4db542a0ad30725187))

## [1.3.0](https://github.com/mammadataei/cypress-vite/compare/v1.2.1...v1.3.0) (2022-12-24)


### Features

* add support for Vite 4 and Cypress 12 ([#29](https://github.com/mammadataei/cypress-vite/issues/29)) ([00dbb75](https://github.com/mammadataei/cypress-vite/commit/00dbb75efdff30157f721f4f32ba5715c9c23b67))
