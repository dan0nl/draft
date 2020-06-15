# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.5.0] - 2020-06-15
### Added
- new component _Block Storage_ (kind: `bst`)
- new component _Object Storage_ (kind: `ost`)
- new component _File Storage_ (kind: `fst`)
- new component _RDBMS_ (kind: `rdb`)
- new component _No SQL_ (kind: `doc`)
- new component _Caching_ (kind: `mem`)
- new commandline flag `--impl=[aws,gcp,azure]` to auto fill components implementations according to the specified provider

### Changed
- autogenerated id prefix now is equal to the _kind_ value (see [./README.md](README.md)) **breaking change** 
  - modified YAML schema
- connection info  (see [./README.md](README.md)) **breaking change** 
  - modified YAML schema

### Removed
- generic html component

## [0.4.0] - 2020-06-11
### Added
- This CHANGELOG file
- Test cases
- New commandline flag `-bottom-top` to set bottom top layout
- New component kind: [`container-service`](./examples/cos.yml)
- New component kind: [`waf`](./examples/waf.yml)
- New example [./examples/system-view.yml](./examples/system-view.yml)