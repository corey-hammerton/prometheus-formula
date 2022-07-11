# Changelog

## [5.6.5](https://github.com/saltstack-formulas/prometheus-formula/compare/v5.6.4...v5.6.5) (2022-07-11)


### Bug Fixes

* **storage/install:** correct "owner" param to "user" ([8294f4f](https://github.com/saltstack-formulas/prometheus-formula/commit/8294f4fd30d696e0ed52954608cea2a3938603e6))


### Continuous Integration

* update `pre-commit` configuration inc. for pre-commit.ci [skip ci] ([7e63074](https://github.com/saltstack-formulas/prometheus-formula/commit/7e6307429582ede529f5d0a0947836d192113754))
* **kitchen+gitlab:** update for new pre-salted images [skip ci] ([f870697](https://github.com/saltstack-formulas/prometheus-formula/commit/f8706975574416d3783c5089dc11698bf9c1ef0c))


### Tests

* **system.rb:** add support for `mac_os_x` [skip ci] ([5c7c22e](https://github.com/saltstack-formulas/prometheus-formula/commit/5c7c22e4380b6bcf7fe10540873f69dd62d4ffd3))

## [5.6.4](https://github.com/saltstack-formulas/prometheus-formula/compare/v5.6.3...v5.6.4) (2022-02-26)


### Bug Fixes

* **pkgrepo:** remove gpgkey2 file.replace for idempotency ([e96c953](https://github.com/saltstack-formulas/prometheus-formula/commit/e96c9531f90148a703f0df1262149bb4b1c08caa))


### Continuous Integration

* update linters to latest versions [skip ci] ([7d5df46](https://github.com/saltstack-formulas/prometheus-formula/commit/7d5df46905c24d7695a4a1a7c8a5716102e5423d))


### Tests

* **system:** add `build_platform_codename` [skip ci] ([2396a13](https://github.com/saltstack-formulas/prometheus-formula/commit/2396a135b3aa5f2a288c018ac06e630443bb3dab))

## [5.6.3](https://github.com/saltstack-formulas/prometheus-formula/compare/v5.6.2...v5.6.3) (2022-02-06)


### Bug Fixes

* **archive:** make sure special commandline flags are accepted ([9529d5f](https://github.com/saltstack-formulas/prometheus-formula/commit/9529d5fcfe3bea44aa683bb3312fcb0eff41e192))


### Continuous Integration

* **gemfile:** allow rubygems proxy to be provided as an env var [skip ci] ([d1b7d8c](https://github.com/saltstack-formulas/prometheus-formula/commit/d1b7d8c2de74eed0d257a466aa78dc3f5da09af4))
* **kitchen+gitlab:** update for new pre-salted images [skip ci] ([5d39408](https://github.com/saltstack-formulas/prometheus-formula/commit/5d39408744dadcc331d1041e7bcb894bdfc35206))

## [5.6.2](https://github.com/saltstack-formulas/prometheus-formula/compare/v5.6.1...v5.6.2) (2021-12-13)


### Bug Fixes

* **groups:** groups should always be created as system groups ([711ebf7](https://github.com/saltstack-formulas/prometheus-formula/commit/711ebf7c1b153096dab3031bc9ea46d162d83bbf))

## [5.6.1](https://github.com/saltstack-formulas/prometheus-formula/compare/v5.6.0...v5.6.1) (2021-12-09)


### Bug Fixes

* **users:** users should always be created as system users ([ee20f82](https://github.com/saltstack-formulas/prometheus-formula/commit/ee20f821d663ea1b2b1da444e3b4e01a08349eb1))


### Continuous Integration

* **kitchen+ci:** update with `3004` pre-salted images/boxes [skip ci] ([4628d74](https://github.com/saltstack-formulas/prometheus-formula/commit/4628d741b82cc4a732bcbf6f4460cbf241bb50bb))
* **kitchen+ci:** update with latest `3003.2` pre-salted images [skip ci] ([cfb0949](https://github.com/saltstack-formulas/prometheus-formula/commit/cfb0949e82f769152b4dbbd64cf5ee5ef575d253))
* **kitchen+ci:** update with latest CVE pre-salted images [skip ci] ([9fda233](https://github.com/saltstack-formulas/prometheus-formula/commit/9fda2330ab4b72978ec9064091bc43e54020049b))

# [5.6.0](https://github.com/saltstack-formulas/prometheus-formula/compare/v5.5.2...v5.6.0) (2021-08-06)


### Bug Fixes

* **defaults:** use nologin instead of /bin/false ([1af0deb](https://github.com/saltstack-formulas/prometheus-formula/commit/1af0deb087b1d6b1109a838871933da97cb38474))
* **indempotency:** run reload onchanges only ([9166498](https://github.com/saltstack-formulas/prometheus-formula/commit/9166498fd8fe046c24220f95b7876a50f3a99d3a))


### Continuous Integration

* **gemfile+lock:** use `ssf` customised `inspec` repo [skip ci] ([3fafc21](https://github.com/saltstack-formulas/prometheus-formula/commit/3fafc2172e8ed77ee537a7935de988a0bc4c99de))
* add Debian 11 Bullseye & update `yamllint` configuration [skip ci] ([802970c](https://github.com/saltstack-formulas/prometheus-formula/commit/802970c47d95241acbf69338db24cd74959f3fd9))
* **kitchen:** move `provisioner` block & update `run_command` [skip ci] ([3203953](https://github.com/saltstack-formulas/prometheus-formula/commit/32039539bbe345314a1b65133dbadc0cccc40940))


### Features

* **config/users:** add support for `debian-11` [skip ci] ([0e65cc3](https://github.com/saltstack-formulas/prometheus-formula/commit/0e65cc345b316412fad4ce9966f99d86c9fa829c))

## [5.5.2](https://github.com/saltstack-formulas/prometheus-formula/compare/v5.5.1...v5.5.2) (2021-07-16)


### Bug Fixes

* **clientlibs/install:** ensure tar is available for Amazon Linux 2 ([7140ccf](https://github.com/saltstack-formulas/prometheus-formula/commit/7140ccf8a8150d3776c2dc241f67ad93fa1f5787))
* check for Amazon in osfamilymap for pkg repo ([338ab4d](https://github.com/saltstack-formulas/prometheus-formula/commit/338ab4ddb6d895e085a47b335f54451d9d406bc8)), closes [#65](https://github.com/saltstack-formulas/prometheus-formula/issues/65)
* update Gitlab CI -test amazonlinux correctly ([6745bf2](https://github.com/saltstack-formulas/prometheus-formula/commit/6745bf23d43f583c0e73d66776c68a669eb9d688)), closes [#65](https://github.com/saltstack-formulas/prometheus-formula/issues/65)

## [5.5.1](https://github.com/saltstack-formulas/prometheus-formula/compare/v5.5.0...v5.5.1) (2021-07-09)


### Bug Fixes

* added guidance and reverted incorrected changes from prior commits ([0ca247a](https://github.com/saltstack-formulas/prometheus-formula/commit/0ca247a37edd6dceb62d5524ce755c87c31ab599)), closes [#59](https://github.com/saltstack-formulas/prometheus-formula/issues/59)
* added guidance and reverted incorrected changes from prior commits ([a4dfb87](https://github.com/saltstack-formulas/prometheus-formula/commit/a4dfb87554b9a5d35fe5654698940380cc5fadee)), closes [#59](https://github.com/saltstack-formulas/prometheus-formula/issues/59)
* added handle for alternative argument opts header ([076869a](https://github.com/saltstack-formulas/prometheus-formula/commit/076869a8cdbde4ed1034d98f16cdeaa17906554e)), closes [#59](https://github.com/saltstack-formulas/prometheus-formula/issues/59)
* added handle for alternative argument opts header ([4de3ebd](https://github.com/saltstack-formulas/prometheus-formula/commit/4de3ebd24196c347ae1ebba88d754c9dd535cf74)), closes [#59](https://github.com/saltstack-formulas/prometheus-formula/issues/59)
* removed erroneus dash (-) ([ef8a3a9](https://github.com/saltstack-formulas/prometheus-formula/commit/ef8a3a9ad781bee86686465a13e27e301f0c5ea5)), closes [#59](https://github.com/saltstack-formulas/prometheus-formula/issues/59)
* removed erroneus dash (-) ([52845bb](https://github.com/saltstack-formulas/prometheus-formula/commit/52845bb534ba98947ee161e7fb745489b2ad57da)), closes [#59](https://github.com/saltstack-formulas/prometheus-formula/issues/59)
* revert to use of macro.jinja for arg handling ([f2261f9](https://github.com/saltstack-formulas/prometheus-formula/commit/f2261f9dc958792a16c13a6380386a1f7239f386))
* revert to use of macro.jinja for arg handling ([696bee0](https://github.com/saltstack-formulas/prometheus-formula/commit/696bee0522b9e37befbe76728c2d3211f25b8a68))
* rework to implement environment variables handling ([e52f804](https://github.com/saltstack-formulas/prometheus-formula/commit/e52f804bf454f8c57d8ed51e6566f60befd4d7c7)), closes [#59](https://github.com/saltstack-formulas/prometheus-formula/issues/59)
* rework to implement environment variables handling ([eea5b40](https://github.com/saltstack-formulas/prometheus-formula/commit/eea5b407fa6dee5cdcb7bd951b752beb1833176c)), closes [#59](https://github.com/saltstack-formulas/prometheus-formula/issues/59) [#59](https://github.com/saltstack-formulas/prometheus-formula/issues/59)
* switched test config entry that wasnt available for deb9 ([5c1d8b6](https://github.com/saltstack-formulas/prometheus-formula/commit/5c1d8b68707ebfbe948cf8f0c21c98504c751d5b))
* switched test config entry that wasnt available for deb9 ([4635ca7](https://github.com/saltstack-formulas/prometheus-formula/commit/4635ca70702a05bf5db24df54956c175d0cd3e18))


### Continuous Integration

* **3003.1:** update inc. AlmaLinux, Rocky & `rst-lint` [skip ci] ([5550397](https://github.com/saltstack-formulas/prometheus-formula/commit/55503974e4cc338590750b02ed964f0afdd44f11))
* **kitchen+gitlab:** remove Ubuntu 16.04 & Fedora 32 (EOL) [skip ci] ([fa96aab](https://github.com/saltstack-formulas/prometheus-formula/commit/fa96aabba76128ebca85b76631bf04ec8daaeb90))

# [5.5.0](https://github.com/saltstack-formulas/prometheus-formula/compare/v5.4.0...v5.5.0) (2021-05-28)


### Bug Fixes

* **clientlibs/install:** ensure `tar` is available for Oracle Linux 8 ([d30b42c](https://github.com/saltstack-formulas/prometheus-formula/commit/d30b42ced095dba6b10bab8c77b2e064cb150008))
* **node_exporter:** typo ([cc112e7](https://github.com/saltstack-formulas/prometheus-formula/commit/cc112e71b922ef74853b4f561d5b126056cf0d58)), closes [#57](https://github.com/saltstack-formulas/prometheus-formula/issues/57)
* **pillar:** fix `OverflowError: Range too big` -- `MAX_RANGE (100000)` ([c9cfdfd](https://github.com/saltstack-formulas/prometheus-formula/commit/c9cfdfd9e17615bdd52143eb5153b0f0f3ac0736)), closes [/gitlab.com/myii/prometheus-formula/-/jobs/1077740890#L779](https://github.com//gitlab.com/myii/prometheus-formula/-/jobs/1077740890/issues/L779)


### Continuous Integration

* add `arch-master` to matrix and update `.travis.yml` [skip ci] ([046b0ee](https://github.com/saltstack-formulas/prometheus-formula/commit/046b0ee23937b574f297503fd6f29dba4e225314))
* **gemfile+lock:** use `ssf` customised `kitchen-docker` repo [skip ci] ([05f66ac](https://github.com/saltstack-formulas/prometheus-formula/commit/05f66ac9bceef49c49f973d53036bc15ec98e730))
* **kitchen+ci:** use latest pre-salted images (after CVE) [skip ci] ([df0ec43](https://github.com/saltstack-formulas/prometheus-formula/commit/df0ec43f52f21746cef09d8fddadb92762132e1d))
* **kitchen+gitlab:** adjust matrix to add `3003` [skip ci] ([a9e26a7](https://github.com/saltstack-formulas/prometheus-formula/commit/a9e26a795df305270d75b9ba94967553f7767091))
* **kitchen+gitlab-ci:** use latest pre-salted images [skip ci] ([e283bfb](https://github.com/saltstack-formulas/prometheus-formula/commit/e283bfb188fcf66759b4c1b5bb7ac039319be592))


### Documentation

* remove files which aren't formula-specific [skip ci] ([1b2c50a](https://github.com/saltstack-formulas/prometheus-formula/commit/1b2c50ae37a6a53df40db7c39907c051ba3bbc51))
* **readme:** fix headings and contributing link [skip ci] ([bb7b816](https://github.com/saltstack-formulas/prometheus-formula/commit/bb7b816aac6d21b85d0dbb20ed894c7f6a8ca941))


### Features

* **archive:** allow command line arguments without values ([08ad2ca](https://github.com/saltstack-formulas/prometheus-formula/commit/08ad2caf4ccf51c3e162f0d9cbf737f21d2633d2))
* **config:** allow to manage extra files ([5f3dc6f](https://github.com/saltstack-formulas/prometheus-formula/commit/5f3dc6f11a42d66c13dd50b5a2115d36b1243f93))


### Tests

* standardise use of `share` suite & `_mapdata` state [skip ci] ([2b38c9e](https://github.com/saltstack-formulas/prometheus-formula/commit/2b38c9e4025c24309ca8c622119250b15c669e50))
* **pillar/repo:** avoid `alertmanager` config where newer than package ([83efb0b](https://github.com/saltstack-formulas/prometheus-formula/commit/83efb0b43418a5ba363dc755c2228b1561d7fa30))

# [5.4.0](https://github.com/saltstack-formulas/prometheus-formula/compare/v5.3.0...v5.4.0) (2021-02-10)


### Bug Fixes

* **clean:** include repo clean too ([782dd45](https://github.com/saltstack-formulas/prometheus-formula/commit/782dd4545247a6eaaab77d42788b6dbdc040597a))


### Continuous Integration

* **commitlint:** ensure `upstream/master` uses main repo URL [skip ci] ([e0f6a8b](https://github.com/saltstack-formulas/prometheus-formula/commit/e0f6a8baeb4e36e295c5355ff4e08e943b4a24b7))
* **gitlab-ci:** add `rubocop` linter (with `allow_failure`) [skip ci] ([7d80e4a](https://github.com/saltstack-formulas/prometheus-formula/commit/7d80e4afc1ffdaec29ec94a355d75e6f8b878672))
* **gitlab-ci:** use GitLab CI as Travis CI replacement ([4f290c2](https://github.com/saltstack-formulas/prometheus-formula/commit/4f290c2dde3125f9e648a2817912c8f594ed277a))
* **pre-commit:** update hook for `rubocop` [skip ci] ([60ec8e5](https://github.com/saltstack-formulas/prometheus-formula/commit/60ec8e514d3c33540089bacbe8edeaf8bfa05f0d))


### Documentation

* **archive:** update pillar.example with env var for mysqld_exporter ([1631137](https://github.com/saltstack-formulas/prometheus-formula/commit/1631137b1bad116f5d7d5b8a472b9c4f41b5f707))


### Features

* **archive:** managing env vars in systemd unit ([4e60b17](https://github.com/saltstack-formulas/prometheus-formula/commit/4e60b17741fb202fded2838e67cb8f870c98450f))


### Tests

* **archive:** add env vars tests ([018e759](https://github.com/saltstack-formulas/prometheus-formula/commit/018e7591839901536cc743141e45cbbd20f94a53))

# [5.3.0](https://github.com/saltstack-formulas/prometheus-formula/compare/v5.2.0...v5.3.0) (2020-11-17)


### Documentation

* **archive:** update pillar.example with unofficial exporter ([10c0b4a](https://github.com/saltstack-formulas/prometheus-formula/commit/10c0b4a030365da704f9d2e75857cdfbfa1fab74))


### Features

* **archive:** add support for non official exporters ([2ff6b90](https://github.com/saltstack-formulas/prometheus-formula/commit/2ff6b90cd8c7b50cb93c627d4624e41d37c7f96d))


### Tests

* **archive:** add unofficial exporter test ([43053a6](https://github.com/saltstack-formulas/prometheus-formula/commit/43053a6e5917b9800fe8d22fc173036956903a73))

# [5.2.0](https://github.com/saltstack-formulas/prometheus-formula/compare/v5.1.0...v5.2.0) (2020-11-12)


### Bug Fixes

* **state:** dangling servicename ([5457a9f](https://github.com/saltstack-formulas/prometheus-formula/commit/5457a9f2f21e26591d392ed5121aa5f5bcbf8fe0))
* **windows:** windows has no osarch grain ([468e420](https://github.com/saltstack-formulas/prometheus-formula/commit/468e420b3473551ffee81ae7e39cc03073ac639c))


### Features

* **archive:** use args pillar when using upstream from repo / archive ([7a08e8d](https://github.com/saltstack-formulas/prometheus-formula/commit/7a08e8db54ce48eaf2df97fa92876d4d9237c6c7))

# [5.1.0](https://github.com/saltstack-formulas/prometheus-formula/compare/v5.0.2...v5.1.0) (2020-11-12)


### Continuous Integration

* **pre-commit:** add to formula [skip ci] ([a639b78](https://github.com/saltstack-formulas/prometheus-formula/commit/a639b782cfdacb65f03e9c59485fe7a17fb3c794))
* **pre-commit:** enable/disable `rstcheck` as relevant [skip ci] ([5dd496c](https://github.com/saltstack-formulas/prometheus-formula/commit/5dd496c1c466f339108a8fe4e0ea2d27f6a0fe68))
* **pre-commit:** finalise `rstcheck` configuration [skip ci] ([d00473a](https://github.com/saltstack-formulas/prometheus-formula/commit/d00473a70c2e1f1ed79ff4d713e8539fedf9135a))


### Features

* **config:** defaults.yaml update archives versions and hashes ([bfff38b](https://github.com/saltstack-formulas/prometheus-formula/commit/bfff38b8b7338d515ed477d4ccbba3438f1bbbf4))


### Tests

* **archive:** update test according to defaults.yaml changes ([34a9805](https://github.com/saltstack-formulas/prometheus-formula/commit/34a980588603bc8a5720b8820754e96108cb505d))

## [5.0.2](https://github.com/saltstack-formulas/prometheus-formula/compare/v5.0.1...v5.0.2) (2020-08-31)


### Bug Fixes

* **archive:** add config file to service only if defined ([](https://github.com/saltstack-formulas/prometheus-formula/commit/a5b44c8))
* **archive:** service name needs to use pillar values ([](https://github.com/saltstack-formulas/prometheus-formula/commit/219250a))
* **debian:** add some valid defaults ([](https://github.com/saltstack-formulas/prometheus-formula/commit/844a77f))


### Tests

* **archive:** add tests to check service names ([](https://github.com/saltstack-formulas/prometheus-formula/commit/a5d4d03))
* **services:** fix path for debian family ([](https://github.com/saltstack-formulas/prometheus-formula/commit/7c1cdb8))

## [5.0.1](https://github.com/saltstack-formulas/prometheus-formula/compare/v5.0.0...v5.0.1) (2020-08-24)


### Bug Fixes

* **pillar:** fix service name in archive mode ([](https://github.com/saltstack-formulas/prometheus-formula/commit/b03a1cc))
* **service:** pick up the right service name in pillars ([](https://github.com/saltstack-formulas/prometheus-formula/commit/0169c89))
* **service:** service is not reloaded because of failing if ([](https://github.com/saltstack-formulas/prometheus-formula/commit/deb9cd2))
* **test:** add tests on node_exporter service ([](https://github.com/saltstack-formulas/prometheus-formula/commit/4e8c69f))
* **test:** add tests on prometheus-node-exporter ([](https://github.com/saltstack-formulas/prometheus-formula/commit/6010cc3))
* **test:** fix alertmanager service name in repo mode test ([](https://github.com/saltstack-formulas/prometheus-formula/commit/41da7cc))
* **test:** fix test pillars ([](https://github.com/saltstack-formulas/prometheus-formula/commit/910a06d))
* **test:** fix tests for RedHat OSes in repo mode ([](https://github.com/saltstack-formulas/prometheus-formula/commit/49e6fa5))
* **test:** test Salt 3001 with Debian 9 and 10 ([](https://github.com/saltstack-formulas/prometheus-formula/commit/890bfc1))


### Styles

* **test:** improve Ruby style ([](https://github.com/saltstack-formulas/prometheus-formula/commit/461ce4f))

# [5.0.0](https://github.com/saltstack-formulas/prometheus-formula/compare/v4.1.1...v5.0.0) (2020-08-24)


### Bug Fixes

* **defaults:** set clientlibs defaults to an empty list ([](https://github.com/saltstack-formulas/prometheus-formula/commit/cdd2e6d))


### BREAKING CHANGES

* **defaults:** The golang clientib is not required for
the regular use of this formula but, if you already expected it to be
installed by default, you'll need to update your pillars to do so.
Running this version of the formula over previous ones won't break the
minions, only skip clientlibs.

## [4.1.1](https://github.com/saltstack-formulas/prometheus-formula/compare/v4.1.0...v4.1.1) (2020-08-24)


### Bug Fixes

* **osfamilymap.yaml:** add gentoo exporters and remove loose go install ([](https://github.com/saltstack-formulas/prometheus-formula/commit/e0aecdb))

# [4.1.0](https://github.com/saltstack-formulas/prometheus-formula/compare/v4.0.2...v4.1.0) (2020-08-21)


### Continuous Integration

* **travis,kitchen:** update matrix ([](https://github.com/saltstack-formulas/prometheus-formula/commit/1eeda22))


### Documentation

* **pillar.example:** add some comments ([](https://github.com/saltstack-formulas/prometheus-formula/commit/68aaa34))


### Features

* **debian:** allow to install using OS packages ([](https://github.com/saltstack-formulas/prometheus-formula/commit/3014494))


### Tests

* **packages:** check when using repo or archives ([](https://github.com/saltstack-formulas/prometheus-formula/commit/c5ad857))

## [4.0.2](https://github.com/saltstack-formulas/prometheus-formula/compare/v4.0.1...v4.0.2) (2020-08-18)


### Bug Fixes

* **linux:** service.args is freebsd ([](https://github.com/saltstack-formulas/prometheus-formula/commit/ceb9863))
* **permissions:** correct basedir user/group ([](https://github.com/saltstack-formulas/prometheus-formula/commit/d65858a))

## [4.0.1](https://github.com/saltstack-formulas/prometheus-formula/compare/v4.0.0...v4.0.1) (2020-08-17)


### Bug Fixes

* **ubuntu:** pkgrepo cannot be used ([](https://github.com/saltstack-formulas/prometheus-formula/commit/fd2ff5f))

# [4.0.0](https://github.com/saltstack-formulas/prometheus-formula/compare/v3.3.0...v4.0.0) (2020-08-09)


### Bug Fixes

* **libtofs:** “files_switch” mess up the variable exported by “map.jinja” [skip ci] ([](https://github.com/saltstack-formulas/prometheus-formula/commit/5403088))
* **pr:** adopt pr comments ([](https://github.com/saltstack-formulas/prometheus-formula/commit/e4b924a))


### Code Refactoring

* **all:** align to template-formula; add clientlibs feature ([](https://github.com/saltstack-formulas/prometheus-formula/commit/ce5b771))


### Continuous Integration

* **gemfile.lock:** add to repo with updated `Gemfile` [skip ci] ([](https://github.com/saltstack-formulas/prometheus-formula/commit/da8f6a8))
* **kitchen:** avoid using bootstrap for `master` instances [skip ci] ([](https://github.com/saltstack-formulas/prometheus-formula/commit/f63a64d))
* **kitchen:** use `saltimages` Docker Hub where available [skip ci] ([](https://github.com/saltstack-formulas/prometheus-formula/commit/9b45ea4))
* **kitchen+travis:** remove `master-py2-arch-base-latest` [skip ci] ([](https://github.com/saltstack-formulas/prometheus-formula/commit/d978c50))
* **travis:** add notifications => zulip [skip ci] ([](https://github.com/saltstack-formulas/prometheus-formula/commit/4b5ec2f))
* **workflows/commitlint:** add to repo [skip ci] ([](https://github.com/saltstack-formulas/prometheus-formula/commit/b32d92a))


### Styles

* **libtofs.jinja:** use Black-inspired Jinja formatting [skip ci] ([](https://github.com/saltstack-formulas/prometheus-formula/commit/2660b19))


### BREAKING CHANGES

* **all:** The data dictionary is simplified and expanded.
Retest your states and update pillar data accordingly.
For developer convenience, clientlibs states were introduced.
See pillar.example, defaults.yaml, and docs/README.

# [3.3.0](https://github.com/saltstack-formulas/prometheus-formula/compare/v3.2.0...v3.3.0) (2019-12-22)


### Bug Fixes

* **pillar.example:** reset `use_upstream_archive` to get tests passing [skip ci] ([978ccc2](https://github.com/saltstack-formulas/prometheus-formula/commit/978ccc208045136dddea44dc59754872f688a9cb))
* test fix for bug 24 ([341fff3](https://github.com/saltstack-formulas/prometheus-formula/commit/341fff36ead5fce94c25c0ba8011a15d76f26de6))
* **release.config.js:** use full commit hash in commit link [skip ci] ([cab6e29](https://github.com/saltstack-formulas/prometheus-formula/commit/cab6e29d8b29c700035694c35b20e8250ecb2ef1))


### Continuous Integration

* **gemfile:** restrict `train` gem version until upstream fix [skip ci] ([a51e532](https://github.com/saltstack-formulas/prometheus-formula/commit/a51e532992b69571a1f5ffa486f98aed4ddf87e0))
* **kitchen:** use `debian-10-master-py3` instead of `develop` [skip ci] ([6ee835c](https://github.com/saltstack-formulas/prometheus-formula/commit/6ee835cab4a1dca30c9b7888587c68368c53dee1))
* **kitchen:** use `develop` image until `master` is ready (`amazonlinux`) [skip ci] ([42ee683](https://github.com/saltstack-formulas/prometheus-formula/commit/42ee683c44d1bc7035b9ce325e8ad7d0c35b45da))
* **kitchen+travis:** upgrade matrix after `2019.2.2` release [skip ci] ([044553e](https://github.com/saltstack-formulas/prometheus-formula/commit/044553ea8f51fc3af64fe3fd4b9fca8c3b58f2df))
* **travis:** apply changes from build config validation [skip ci] ([bf4022e](https://github.com/saltstack-formulas/prometheus-formula/commit/bf4022ec1ac489dc875c02e84a547a7a6c245cb8))
* **travis:** opt-in to `dpl v2` to complete build config validation [skip ci] ([0867508](https://github.com/saltstack-formulas/prometheus-formula/commit/086750884d14bc07ae466dd8247b99c01dbc1766))
* **travis:** quote pathspecs used with `git ls-files` [skip ci] ([d9c9386](https://github.com/saltstack-formulas/prometheus-formula/commit/d9c93860385303ae89025431da7a83d48c5a6adf))
* **travis:** run `shellcheck` during lint job [skip ci] ([7ea6967](https://github.com/saltstack-formulas/prometheus-formula/commit/7ea6967ca7d6c41f99ef4831715b894d9c7c751d))
* **travis:** update `salt-lint` config for `v0.0.10` [skip ci] ([1415c13](https://github.com/saltstack-formulas/prometheus-formula/commit/1415c137854f19e34e4a79d74f1bb2b25770ee0c))
* **travis:** use `major.minor` for `semantic-release` version [skip ci] ([9b4d5af](https://github.com/saltstack-formulas/prometheus-formula/commit/9b4d5aff64b0657303c7186c5f5a49d02039f35f))
* **travis:** use build config validation (beta) [skip ci] ([0d0af0d](https://github.com/saltstack-formulas/prometheus-formula/commit/0d0af0df317c67924d0b8dc75d9dbf8e7a3a9535))


### Features

* **osfamilymap.yaml:** add Gentoo support ([b87e8f4](https://github.com/saltstack-formulas/prometheus-formula/commit/b87e8f437c51c81bb7543ad27b49dea48ff36203))


### Performance Improvements

* **travis:** improve `salt-lint` invocation [skip ci] ([36ccdc4](https://github.com/saltstack-formulas/prometheus-formula/commit/36ccdc4416d58952865ef60e7b94d122f09c6cde))

# [3.2.0](https://github.com/saltstack-formulas/prometheus-formula/compare/v3.1.2...v3.2.0) (2019-10-17)


### Bug Fixes

* **args:** allow boolean arguments ([](https://github.com/saltstack-formulas/prometheus-formula/commit/39dacf0))
* **examples:** fixed pillar.example ([](https://github.com/saltstack-formulas/prometheus-formula/commit/464a186))
* **node_exporter:** allow standalone use of node_exporter ([](https://github.com/saltstack-formulas/prometheus-formula/commit/a0d8ad4))
* **package:** use correct node exporter package name in Debian ([](https://github.com/saltstack-formulas/prometheus-formula/commit/a4fd589))
* **readme:** removed already gone prometheus.exporters from README.rst ([](https://github.com/saltstack-formulas/prometheus-formula/commit/07d6209))


### Continuous Integration

* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([](https://github.com/saltstack-formulas/prometheus-formula/commit/9def915))


### Documentation

* **contributing:** remove to use org-level file instead [skip ci] ([](https://github.com/saltstack-formulas/prometheus-formula/commit/fabcc4a))
* **readme:** update link to `CONTRIBUTING` [skip ci] ([](https://github.com/saltstack-formulas/prometheus-formula/commit/da2a5aa))


### Features

* **freebsd:** support for FreeBSD ([](https://github.com/saltstack-formulas/prometheus-formula/commit/871da35))
* **textfile_collectors:** added IPMI textfile collector ([](https://github.com/saltstack-formulas/prometheus-formula/commit/d731309))
* **textfile_collectors:** added smartmon textfile collector ([](https://github.com/saltstack-formulas/prometheus-formula/commit/7b2f5ce))
* **textfile_collectors:** added support for textfile collectors ([](https://github.com/saltstack-formulas/prometheus-formula/commit/930552d))

## [3.1.2](https://github.com/saltstack-formulas/prometheus-formula/compare/v3.1.1...v3.1.2) (2019-10-10)


### Bug Fixes

* **clean.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/prometheus-formula/commit/8056339))
* **install.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/prometheus-formula/commit/51f5485))
* **install.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/prometheus-formula/commit/173bc4f))
* **install.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/prometheus-formula/commit/85c7fce))


### Continuous Integration

* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([](https://github.com/saltstack-formulas/prometheus-formula/commit/569328b))

## [3.1.1](https://github.com/saltstack-formulas/prometheus-formula/compare/v3.1.0...v3.1.1) (2019-10-07)


### Bug Fixes

* **config:** cope with aberrant service names ([0a33842](https://github.com/saltstack-formulas/prometheus-formula/commit/0a33842))


### Continuous Integration

* use `dist: bionic` & apply `opensuse-leap-15` SCP error workaround ([3dc6e12](https://github.com/saltstack-formulas/prometheus-formula/commit/3dc6e12))
* **kitchen:** change `log_level` to `debug` instead of `info` ([af666db](https://github.com/saltstack-formulas/prometheus-formula/commit/af666db))
* **kitchen:** install required packages to bootstrapped `opensuse` [skip ci] ([3332493](https://github.com/saltstack-formulas/prometheus-formula/commit/3332493))
* **kitchen:** use bootstrapped `opensuse` images until `2019.2.2` [skip ci] ([a624dd8](https://github.com/saltstack-formulas/prometheus-formula/commit/a624dd8))
* **kitchen+travis:** replace EOL pre-salted images ([0895d81](https://github.com/saltstack-formulas/prometheus-formula/commit/0895d81))
* **platform:** add `arch-base-latest` (commented out for now) [skip ci] ([6221888](https://github.com/saltstack-formulas/prometheus-formula/commit/6221888))
* **yamllint:** add rule `empty-values` & use new `yaml-files` setting ([1784b34](https://github.com/saltstack-formulas/prometheus-formula/commit/1784b34))

# [3.1.0](https://github.com/saltstack-formulas/prometheus-formula/compare/v3.0.1...v3.1.0) (2019-08-17)


### Continuous Integration

* **kitchen+travis:** modify matrix to include `develop` platform ([fc0f5b6](https://github.com/saltstack-formulas/prometheus-formula/commit/fc0f5b6))


### Features

* **yamllint:** include for this repo and apply rules throughout ([07dbfc8](https://github.com/saltstack-formulas/prometheus-formula/commit/07dbfc8))

## [3.0.1](https://github.com/saltstack-formulas/prometheus-formula/compare/v3.0.0...v3.0.1) (2019-06-28)


### Bug Fixes

* **alternatives:** fix requisite ([8c410d7](https://github.com/saltstack-formulas/prometheus-formula/commit/8c410d7))

# [3.0.0](https://github.com/saltstack-formulas/prometheus-formula/compare/v2.0.0...v3.0.0) (2019-06-23)


### Bug Fixes

* **example:** fix pillar.example formatting ([a13dd03](https://github.com/saltstack-formulas/prometheus-formula/commit/a13dd03))
* **repo:** use_upstream_repo corrections; separate users state ([eda47f7](https://github.com/saltstack-formulas/prometheus-formula/commit/eda47f7))
* **service:** ensure service file is removed on clean ([c735a6d](https://github.com/saltstack-formulas/prometheus-formula/commit/c735a6d))
* **suse:** bypass salt alternatives.install errors ([1a890e5](https://github.com/saltstack-formulas/prometheus-formula/commit/1a890e5))
* **systemd:** ensure systemd detects new service ([149dd81](https://github.com/saltstack-formulas/prometheus-formula/commit/149dd81))


### Features

* **archives:** support for archives file format ([1f86f4a](https://github.com/saltstack-formulas/prometheus-formula/commit/1f86f4a))
* **archives:** support for various prometheus archives ([3ec910e](https://github.com/saltstack-formulas/prometheus-formula/commit/3ec910e))
* **archives:** user managementX ([d43033a](https://github.com/saltstack-formulas/prometheus-formula/commit/d43033a))
* **linux:** alternatives support & updated unit tests ([36b3e62](https://github.com/saltstack-formulas/prometheus-formula/commit/36b3e62))


### Tests

* **centos:** verified on CentosOS ([731198d](https://github.com/saltstack-formulas/prometheus-formula/commit/731198d))
* **inspec:** expand unittests for archive format ([b074bd3](https://github.com/saltstack-formulas/prometheus-formula/commit/b074bd3))
* **inspec:** fix tests ([4092fb4](https://github.com/saltstack-formulas/prometheus-formula/commit/4092fb4))


### BREAKING CHANGES

* **repo:** The formula has been refactored to accomodate multiple packages,
archives, users, and repos. Update your pillars and top states
* **archives:** the parameter `pkg` is now a dictionary. References
 to `prometheus.pkg` should be changed to `prometheus.pkg.name`.

# [2.0.0](https://github.com/saltstack-formulas/prometheus-formula/compare/v1.2.0...v2.0.0) (2019-06-22)


### Features

* **repository:** add support for pkgrepo.managed ([907f9a6](https://github.com/saltstack-formulas/prometheus-formula/commit/907f9a6))


### BREAKING CHANGES

* **repository:** the variable 'pkg' was renamed 'pkg.name',
  update your pillars

# [1.2.0](https://github.com/saltstack-formulas/prometheus-formula/compare/v1.1.0...v1.2.0) (2019-06-05)


### Features

* **macos:** basic package and group handling ([e6a8b0c](https://github.com/saltstack-formulas/prometheus-formula/commit/e6a8b0c))

# [1.1.0](https://github.com/alxwr/prometheus-formula/compare/v1.0.0...v1.1.0) (2019-04-30)


### Bug Fixes

* **FreeBSD:** elegantly prevent service hang ([a7fad98](https://github.com/alxwr/prometheus-formula/commit/a7fad98)), closes [/github.com/saltstack/salt/issues/44848#issuecomment-487016414](https://github.com//github.com/saltstack/salt/issues/44848/issues/issuecomment-487016414)


### Features

* **args:** handle service arguments the same way ([94078fe](https://github.com/alxwr/prometheus-formula/commit/94078fe))
* **exporters:** added node_exporter ([34ada49](https://github.com/alxwr/prometheus-formula/commit/34ada49))

# 1.0.0 (2019-04-25)


### Continuous Integration

* **travis:** use structure of template-formula ([88d3f3e](https://github.com/alxwr/prometheus-formula/commit/88d3f3e))


### Features

* **prometheus:** basic setup based on template-formula ([b9b7cc0](https://github.com/alxwr/prometheus-formula/commit/b9b7cc0))
