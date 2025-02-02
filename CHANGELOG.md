# Changelog

# [0.39.0](https://github.com/saltstack-formulas/apache-formula/compare/v0.38.2...v0.39.0) (2019-12-20)


### Continuous Integration

* **gemfile:** restrict `train` gem version until upstream fix [skip ci] ([13be6f9](https://github.com/saltstack-formulas/apache-formula/commit/13be6f9fac5aae55c48f74c784335c61d7fbaaf2))
* **travis:** apply changes from build config validation [skip ci] ([0aac479](https://github.com/saltstack-formulas/apache-formula/commit/0aac479c253f95b7fdcb1505476638c2d703bc77))
* **travis:** opt-in to `dpl v2` to complete build config validation ([19e90ea](https://github.com/saltstack-formulas/apache-formula/commit/19e90ea2d6ef91118ebf59817ef4c91ad876af54))
* **travis:** quote pathspecs used with `git ls-files` [skip ci] ([6608ddf](https://github.com/saltstack-formulas/apache-formula/commit/6608ddf8c5a361b93e6a44658ab1e306953566bf))
* **travis:** run `shellcheck` during lint job [skip ci] ([2ff6b2f](https://github.com/saltstack-formulas/apache-formula/commit/2ff6b2f17e1fd48b5f0a4156c2dbd90f07f27025))
* **travis:** use build config validation (beta) [skip ci] ([73160b2](https://github.com/saltstack-formulas/apache-formula/commit/73160b249124df6bbd36b113df71724c019a118f))


### Features

* **server-status:** allow remote servers to reach server-status page ([a3c0022](https://github.com/saltstack-formulas/apache-formula/commit/a3c0022d7988eee0ec43d939bced91dee9fec0e1))

## [0.38.2](https://github.com/saltstack-formulas/apache-formula/compare/v0.38.1...v0.38.2) (2019-11-07)


### Bug Fixes

* **apache/modules.sls:** fix duplicated ID ([57afd71](https://github.com/saltstack-formulas/apache-formula/commit/57afd71627eb554138c8d5ec9cc790d899ed80ff))

## [0.38.1](https://github.com/saltstack-formulas/apache-formula/compare/v0.38.0...v0.38.1) (2019-11-05)


### Bug Fixes

* **mod_perl2.sls:** fix a2enmod perl2 error ([fba8d21](https://github.com/saltstack-formulas/apache-formula/commit/fba8d217944c8b5a0abf19cdbae7d41d1ec5bf2e))
* **release.config.js:** use full commit hash in commit link [skip ci] ([dc5593c](https://github.com/saltstack-formulas/apache-formula/commit/dc5593cfdf775e065ea5f680f2ed2b6b7c80d8ed))


### Continuous Integration

* **kitchen:** use `debian-10-master-py3` instead of `develop` [skip ci] ([09d82a5](https://github.com/saltstack-formulas/apache-formula/commit/09d82a581caa09298d3d99ded215c5e45c5b619f))
* **kitchen:** use `develop` image until `master` is ready (`amazonlinux`) [skip ci] ([d0bf6f3](https://github.com/saltstack-formulas/apache-formula/commit/d0bf6f37969a9a97a6e368278e0f9eb40431f2f1))
* **kitchen+travis:** upgrade matrix after `2019.2.2` release [skip ci] ([fc0f869](https://github.com/saltstack-formulas/apache-formula/commit/fc0f869b78ef56369e1cfb6ff3d62179f703efa0))
* **travis:** update `salt-lint` config for `v0.0.10` [skip ci] ([2622d48](https://github.com/saltstack-formulas/apache-formula/commit/2622d48b4ccb01cd70555d46759d79d82d1db7bf))


### Performance Improvements

* **travis:** improve `salt-lint` invocation [skip ci] ([bf75770](https://github.com/saltstack-formulas/apache-formula/commit/bf7577022040a155de8b3ab4f557dd05484d278c))

# [0.38.0](https://github.com/saltstack-formulas/apache-formula/compare/v0.37.4...v0.38.0) (2019-10-20)


### Bug Fixes

* **apache-2.2.config.jinja:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/apache-formula/commit/f4045ef))
* **apache-2.4.config.jinja:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/apache-formula/commit/e2c1c2e))
* **flags.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/apache-formula/commit/a146c59))
* **init.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/apache-formula/commit/8465eb4))
* **map.jinja:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/apache-formula/commit/d011324))
* **mod_geoip.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/apache-formula/commit/e55ef9b))
* **modsecurity.conf.jinja:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/apache-formula/commit/2a79d05))
* **modules.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/apache-formula/commit/55d11f8))
* **server_status.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/apache-formula/commit/da9a592))
* **uninstall.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/apache-formula/commit/ed7dc7b))
* **vhosts/cleanup.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/apache-formula/commit/b0bbd0b))
* **vhosts/minimal.tmpl:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/apache-formula/commit/146dc67))
* **vhosts/proxy.tmpl:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/apache-formula/commit/e7c9fbb))
* **vhosts/redirect.tmpl:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/apache-formula/commit/0a41b19))
* **vhosts/standard.tmpl:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/apache-formula/commit/1bad58d))
* **yamllint:** fix all errors ([](https://github.com/saltstack-formulas/apache-formula/commit/97f6ead))


### Documentation

* **formula:** use standard structure ([](https://github.com/saltstack-formulas/apache-formula/commit/701929d))
* **readme:** move to `docs/` directory and modify accordingly ([](https://github.com/saltstack-formulas/apache-formula/commit/6933f0e))


### Features

* **semantic-release:** implement for this formula ([](https://github.com/saltstack-formulas/apache-formula/commit/34d1f7c))


### Tests

* **mod_security_spec:** convert from Serverspec to InSpec ([](https://github.com/saltstack-formulas/apache-formula/commit/68b971b))
