# Changelog

All notable changes to this project will be documented in this file.

## [0.2.5] - 2026-10-24

### Bug Fixes

- *(deps)* Upgrade duckdb to 2.0 and keep new files readable by 1.x (#18) by @debba in [#18](https://github.com/TabularisDB/tabularis-duckdb-plugin/pull/18)

### Documentation

- Update Tabularis logo URL to packages/web-ui/public by @debba
- Use Tabularis banner and add native support banner in README by @debba

### Miscellaneous

- Drop the stale rkyv advisory ignore (#17) by @debba in [#17](https://github.com/TabularisDB/tabularis-duckdb-plugin/pull/17)
## [0.2.4] - 2026-10-17

### Bug Fixes

- *(deps)* Upgrade duckdb to 1.5 to clear security advisories (#16) by @debba in [#16](https://github.com/TabularisDB/tabularis-duckdb-plugin/pull/16)

### Features

- *(manifest)* Declare in-memory database support (#15) by @debba in [#15](https://github.com/TabularisDB/tabularis-duckdb-plugin/pull/15)
## [0.2.3] - 2026-10-12

### Bug Fixes

- *(deps)* Update rand to 0.8.6 for RUSTSEC-2026-0097 by @debba in [#13](https://github.com/TabularisDB/tabularis-duckdb-plugin/pull/13)

### Miscellaneous

- Add CI and version suggestion workflows (#11) by @debba in [#11](https://github.com/TabularisDB/tabularis-duckdb-plugin/pull/11)
## [0.2.2] - 2026-10-11

### Bug Fixes

- *(query)* Serialize DuckDB DATE as ISO string (#10) by @vivekyarra in [#10](https://github.com/TabularisDB/tabularis-duckdb-plugin/pull/10)
- *(manifest)* Add stable id and human-readable display name by @debba

### Features

- Expose DuckDB metadata comments (#9) by @debba in [#9](https://github.com/TabularisDB/tabularis-duckdb-plugin/pull/9)
## [0.2.1] - 2026-08-06

### Bug Fixes

- *(manifest)* Satisfy the Tabularium driver-kind contract (#4) by @NewtTheWolf in [#4](https://github.com/TabularisDB/tabularis-duckdb-plugin/pull/4)
- *(ci)* Keep .tabularium when uploading the manifest artifact by @NewtTheWolf
- *(ci)* Pin the windows build to windows-2022 by @debba

### Documentation

- Fix Discord shields.io badge server id by @debba

### Features

- Migrate to the .tabularium manifest for the Tabularium registry by @NewtTheWolf
- Catalogue icon, per-version release notes, manifest asset fix by @debba

### Miscellaneous

- Switch Discord invite URL to discord.com/invite/K2hmhfHRSt by @debba
## [0.1.0] - 2026-02-23

### Documentation

- *(readme)* Add README for duckdb plugin by @debba

### Features

- *(duckdb)* Add duckdb plugin and CI release workflow by @debba

### Miscellaneous

- *(release)* Include manifest and platform in release packaging by @debba

### Build

- *(windows)* Add build script linking Rstrtmgr on Windows by @debba

