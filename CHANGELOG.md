# Changelog

## [0.11.2](https://github.com/saltstack-formulas/dhcpd-formula/compare/v0.11.1...v0.11.2) (2020-09-24)


### Bug Fixes

* **dhcpd.conf:** fix bug 50 ([e015cda](https://github.com/saltstack-formulas/dhcpd-formula/commit/e015cdac5944cba0d821da31108ca26fe43a2da5)), closes [#50](https://github.com/saltstack-formulas/dhcpd-formula/issues/50)


### Continuous Integration

* **gemfile.lock:** add to repo with updated `Gemfile` [skip ci] ([e3d3bb3](https://github.com/saltstack-formulas/dhcpd-formula/commit/e3d3bb3b93f5686f3a32d411106de39d5b71fe9e))
* **kitchen:** use `saltimages` Docker Hub where available [skip ci] ([6e5d4fe](https://github.com/saltstack-formulas/dhcpd-formula/commit/6e5d4fe5ff331fea4fe6b63bbfe0db71d01523f5))
* **kitchen+travis:** add new platforms [skip ci] ([2e3f86e](https://github.com/saltstack-formulas/dhcpd-formula/commit/2e3f86ee12a0c1bab6c598f21109eaadc4ef790e))
* **kitchen+travis:** adjust matrix to add `3000.2` & remove `2018.3` [skip ci] ([1eac3c9](https://github.com/saltstack-formulas/dhcpd-formula/commit/1eac3c9c4d8a352f0a8c2d9b68faeafae47acc71))
* **kitchen+travis:** adjust matrix to add `3000.3` [skip ci] ([4fa9cb5](https://github.com/saltstack-formulas/dhcpd-formula/commit/4fa9cb54eeb4de109da50bf24766dca81a6cce23))
* **kitchen+travis:** remove `master-py2-arch-base-latest` [skip ci] ([aa2f881](https://github.com/saltstack-formulas/dhcpd-formula/commit/aa2f8818fab95889e1365f331bb71468c212bf45))
* **travis:** add notifications => zulip [skip ci] ([1726c5a](https://github.com/saltstack-formulas/dhcpd-formula/commit/1726c5a2c4a0ca2beb52b57795f6aa9cd8f3ca25))
* **workflows/commitlint:** add to repo [skip ci] ([9572bd8](https://github.com/saltstack-formulas/dhcpd-formula/commit/9572bd82e3659354eca0d6061f1af566a2cbad23))

## [0.11.1](https://github.com/saltstack-formulas/dhcpd-formula/compare/v0.11.0...v0.11.1) (2020-04-09)


### Bug Fixes

* **fedora:** install `dhcp-server` ([b91a3b1](https://github.com/saltstack-formulas/dhcpd-formula/commit/b91a3b1feb1d5e524eed26c6e5be014f1bd33435))
* **pillar.example:** remove spurious whitespaces found in `yaml_dump` ([d578996](https://github.com/saltstack-formulas/dhcpd-formula/commit/d57899643ea6be24b364bb5361034c120ee07ecd))
* **rubocop:** fix remaining violations ([106f9cb](https://github.com/saltstack-formulas/dhcpd-formula/commit/106f9cb36d8710b48c327541616347c7f94bea76))


### Continuous Integration

* **kitchen+travis:** adjust matrix to add `3000.1` & remove `2017.7` ([6bacfb3](https://github.com/saltstack-formulas/dhcpd-formula/commit/6bacfb326610ab3afc399e7aaf3c109ef66dfd75))


### Tests

* fix `arch` conditional and make `case` more Rubyish ([0b5bab2](https://github.com/saltstack-formulas/dhcpd-formula/commit/0b5bab25c02c63506b9b3701aeff72b587c354ac))

# [0.11.0](https://github.com/saltstack-formulas/dhcpd-formula/compare/v0.10.4...v0.11.0) (2020-04-09)


### Features

* **ldap:** add ldap backend support ([241f267](https://github.com/saltstack-formulas/dhcpd-formula/commit/241f2677631311991527381c87a10fb1926cf3c1))


### Tests

* fix tests for PR 44 ([5128b1f](https://github.com/saltstack-formulas/dhcpd-formula/commit/5128b1ff45dc88e51ad7221cd0dbc03a817159fa))

## [0.10.4](https://github.com/saltstack-formulas/dhcpd-formula/compare/v0.10.3...v0.10.4) (2020-04-06)


### Bug Fixes

* **map.jinja:** ensure whole pillar is merged in ([4baed92](https://github.com/saltstack-formulas/dhcpd-formula/commit/4baed92e8768e6e7cbd6537c9359d5a28e838387))


### Code Refactoring

* **tpls:** refactor templates ([9648e0d](https://github.com/saltstack-formulas/dhcpd-formula/commit/9648e0d0872db66e26ca11d6a0d860d6afff79ab))


### Tests

* **config_spec:** update according to refactored `map.jinja` ([880b281](https://github.com/saltstack-formulas/dhcpd-formula/commit/880b2815ee8102904b6586ded0d1e81412458575))
* **yaml_dump_spec:** update according to refactored `map.jinja` ([174e8d2](https://github.com/saltstack-formulas/dhcpd-formula/commit/174e8d22299d3dc464e2b5e0bf11fd280b51c27e))

## [0.10.3](https://github.com/saltstack-formulas/dhcpd-formula/compare/v0.10.2...v0.10.3) (2020-04-06)


### Tests

* **config_spec:** fix existing tests (repeating same control twice) ([3c7cd44](https://github.com/saltstack-formulas/dhcpd-formula/commit/3c7cd4483a1b012c33e0b0b53f16d3982f8d7e22))
* **config_spec:** update with file contents to test ([0ae0a66](https://github.com/saltstack-formulas/dhcpd-formula/commit/0ae0a660e8a02481495178e5996b9a0503613a7e))
* **config_spec:** workaround spurious whitespace issues on CentOS ([f4e12c5](https://github.com/saltstack-formulas/dhcpd-formula/commit/f4e12c58b74d428421e80b77b2a1e92eb128b166))

## [0.10.2](https://github.com/saltstack-formulas/dhcpd-formula/compare/v0.10.1...v0.10.2) (2020-04-06)


### Code Refactoring

* **map:** use `map.jinja` ng ([0ebe742](https://github.com/saltstack-formulas/dhcpd-formula/commit/0ebe7422d82f96484529581dc86dc2867c7348dc))


### Tests

* **yaml_dump_spec:** update ([a57912d](https://github.com/saltstack-formulas/dhcpd-formula/commit/a57912d18a6aa1b94a1455e8d692861f0cc0eb58))

## [0.10.1](https://github.com/saltstack-formulas/dhcpd-formula/compare/v0.10.0...v0.10.1) (2020-04-06)


### Tests

* **yaml_dump:** add functionality, initial tests & add to Kitchen ([76d43f5](https://github.com/saltstack-formulas/dhcpd-formula/commit/76d43f57595d595883b766c4bded8401d3fd0175))

# [0.10.0](https://github.com/saltstack-formulas/dhcpd-formula/compare/v0.9.0...v0.10.0) (2020-02-27)


### Continuous Integration

* **kitchen:** avoid using bootstrap for `master` instances [skip ci] ([fc755da](https://github.com/saltstack-formulas/dhcpd-formula/commit/fc755da7657b4161d31389c9db72a383f6751dcc))
* **travis:** use `major.minor` for `semantic-release` version [skip ci] ([9780bc3](https://github.com/saltstack-formulas/dhcpd-formula/commit/9780bc33e621ac3595681bfc31ba65990a5c7afe))


### Features

* **map.jinja:** add Red Hat styled service configuration ([ebf6e50](https://github.com/saltstack-formulas/dhcpd-formula/commit/ebf6e5060fb82628c58ba99c010c90d746584338))

# [0.9.0](https://github.com/saltstack-formulas/dhcpd-formula/compare/v0.8.1...v0.9.0) (2019-12-16)


### Bug Fixes

* **release.config.js:** use full commit hash in commit link [skip ci] ([1c516f5](https://github.com/saltstack-formulas/dhcpd-formula/commit/1c516f57e848f0bcb9fe03cb82284a4c3c6bb41c))


### Continuous Integration

* **gemfile:** restrict `train` gem version until upstream fix [skip ci] ([f838b4d](https://github.com/saltstack-formulas/dhcpd-formula/commit/f838b4d4733452d36d62cfe4ef9b7ee57752a01f))
* **kitchen:** use `debian-10-master-py3` instead of `develop` [skip ci] ([7ca8c7a](https://github.com/saltstack-formulas/dhcpd-formula/commit/7ca8c7a1913fbbf01712a2ce4d5c3d1443f3b6b8))
* **kitchen:** use `develop` image until `master` is ready (`amazonlinux`) [skip ci] ([e009040](https://github.com/saltstack-formulas/dhcpd-formula/commit/e009040d28afe4e1bd07156580a18723b9cbb1d5))
* **kitchen+travis:** upgrade matrix after `2019.2.2` release [skip ci] ([d7591f0](https://github.com/saltstack-formulas/dhcpd-formula/commit/d7591f0dcb5d677294685bb7f1acb26245abba5d))
* **travis:** apply changes from build config validation [skip ci] ([df6ce3e](https://github.com/saltstack-formulas/dhcpd-formula/commit/df6ce3e5d343d07a9ccd33501059edd6359e6343))
* **travis:** opt-in to `dpl v2` to complete build config validation [skip ci] ([7fb1a93](https://github.com/saltstack-formulas/dhcpd-formula/commit/7fb1a936230e2732d23a9edae11fc4f96fd0daac))
* **travis:** quote pathspecs used with `git ls-files` [skip ci] ([67c340d](https://github.com/saltstack-formulas/dhcpd-formula/commit/67c340d3099c78ee7c0079cde9fb5609fbb54bc6))
* **travis:** run `shellcheck` during lint job [skip ci] ([4a192fe](https://github.com/saltstack-formulas/dhcpd-formula/commit/4a192fe586bf55e4bb680c51e60828260c2d889d))
* **travis:** update `salt-lint` config for `v0.0.10` [skip ci] ([14eecc2](https://github.com/saltstack-formulas/dhcpd-formula/commit/14eecc2114e42f8c97dc66f49250b3bbbae655d5))
* **travis:** use build config validation (beta) [skip ci] ([8068a89](https://github.com/saltstack-formulas/dhcpd-formula/commit/8068a890085582ab499dd7972f6e560a18c39330))
* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([8ed2593](https://github.com/saltstack-formulas/dhcpd-formula/commit/8ed2593917824945b0be96c8120fa564981ef0b5))


### Documentation

* **contributing:** remove to use org-level file instead [skip ci] ([77da7be](https://github.com/saltstack-formulas/dhcpd-formula/commit/77da7bed48d9b352b9b47f73a2d267220839fb69))
* **readme:** update link to `CONTRIBUTING` [skip ci] ([d40fd74](https://github.com/saltstack-formulas/dhcpd-formula/commit/d40fd748d8a4b69a1ee03bf5b5b74938e26d6dfc))


### Features

* **map.jinja:** add Gentoo support ([934bcf4](https://github.com/saltstack-formulas/dhcpd-formula/commit/934bcf4459529a3c2112402746208555c2f1858e))


### Performance Improvements

* **travis:** improve `salt-lint` invocation [skip ci] ([42a525d](https://github.com/saltstack-formulas/dhcpd-formula/commit/42a525ddb48107365467bdf952d190bcc67825be))

## [0.8.1](https://github.com/saltstack-formulas/dhcpd-formula/compare/v0.8.0...v0.8.1) (2019-10-09)


### Continuous Integration

* **kitchen:** change `log_level` to `debug` instead of `info` ([](https://github.com/saltstack-formulas/dhcpd-formula/commit/3e11354))
* **kitchen:** install required packages to bootstrapped `opensuse` [skip ci] ([](https://github.com/saltstack-formulas/dhcpd-formula/commit/5ec2e57))
* **kitchen:** use bootstrapped `opensuse` images until `2019.2.2` [skip ci] ([](https://github.com/saltstack-formulas/dhcpd-formula/commit/f914fe3))
* **kitchen+travis:** replace EOL pre-salted images ([](https://github.com/saltstack-formulas/dhcpd-formula/commit/c33b06b))
* **platform:** add `arch-base-latest` (commented out for now) [skip ci] ([](https://github.com/saltstack-formulas/dhcpd-formula/commit/99c7477))
* **yamllint:** add rule `empty-values` & use new `yaml-files` setting ([](https://github.com/saltstack-formulas/dhcpd-formula/commit/0688273))
* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([](https://github.com/saltstack-formulas/dhcpd-formula/commit/d7c9254))
* use `dist: bionic` & apply `opensuse-leap-15` SCP error workaround ([](https://github.com/saltstack-formulas/dhcpd-formula/commit/5dc28e1))


### Tests

* **inspec:** add remaining platforms [skip ci] ([](https://github.com/saltstack-formulas/dhcpd-formula/commit/483d70d))

# [0.8.0](https://github.com/saltstack-formulas/dhcpd-formula/compare/v0.7.1...v0.8.0) (2019-08-10)


### Features

* **yamllint:** include for this repo and apply rules throughout ([d70c724](https://github.com/saltstack-formulas/dhcpd-formula/commit/d70c724))

## [0.7.1](https://github.com/saltstack-formulas/dhcpd-formula/compare/v0.7.0...v0.7.1) (2019-07-31)


### Code Refactoring

* **indent:** use filter block to indent included files ([451667f](https://github.com/saltstack-formulas/dhcpd-formula/commit/451667f))

# [0.7.0](https://github.com/saltstack-formulas/dhcpd-formula/compare/v0.6.0...v0.7.0) (2019-07-31)


### Continuous Integration

* **travis:** initialize kitchen infrastructure ([472a1c4](https://github.com/saltstack-formulas/dhcpd-formula/commit/472a1c4))


### Documentation

* **readme:** move under doc/ and add contributing documentation ([523e19a](https://github.com/saltstack-formulas/dhcpd-formula/commit/523e19a))


### Features

* **semantic-release:** implement an automated changelog ([b5ad74e](https://github.com/saltstack-formulas/dhcpd-formula/commit/b5ad74e))


### Tests

* **config:** the daemon configuration file must exist ([840c225](https://github.com/saltstack-formulas/dhcpd-formula/commit/840c225))
* **packages:** we have only one installed package ([9b9fa1e](https://github.com/saltstack-formulas/dhcpd-formula/commit/9b9fa1e))
* **service:** the service configuration file must exist ([eb3c948](https://github.com/saltstack-formulas/dhcpd-formula/commit/eb3c948))
* **service:** the service must be installed but disabled ([174c2e7](https://github.com/saltstack-formulas/dhcpd-formula/commit/174c2e7))
