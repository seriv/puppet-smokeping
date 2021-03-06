# Changelog

All notable changes to this project will be documented in this file.
Each new release typically also includes the latest modulesync defaults.
These should not affect the functionality of the module.

## [v3.0.0](https://github.com/voxpupuli/puppet-smokeping/tree/v3.0.0) (2017-11-11)

[Full Changelog](https://github.com/voxpupuli/puppet-smokeping/compare/v2.0.0...v3.0.0)

**Merged pull requests:**

- replace validate\_\* with datatypes in target [\#70](https://github.com/voxpupuli/puppet-smokeping/pull/70) ([bastelfreak](https://github.com/bastelfreak))
- Add basic unit testing [\#69](https://github.com/voxpupuli/puppet-smokeping/pull/69) ([bastelfreak](https://github.com/bastelfreak))
- purge trailing whitespace in README.md [\#68](https://github.com/voxpupuli/puppet-smokeping/pull/68) ([bastelfreak](https://github.com/bastelfreak))

## [v2.0.0](https://github.com/voxpupuli/puppet-zabbix/tree/v2.0.0) (2017-02-11)

This is the last release with Puppet3 support!
* Only include `/etc/smokeping/conf.d/Slaves` when mode is master
* Add support for managing firewall rules
* Add edgetrigger option to smokeping alerts
* Bump puppet minimum version_requirement to 3.8.7

## [1.7.1] - 2015-11-12
### Fixed
- Future parser compatibility. Thanks to @dvorak
- Slave configuration fixes. Thanks to @fetzerms
- Initial RedHat/CentOS support. Thanks to @jethrocarr
- Better Hiera support. Thanks to @vincentbernat
- Other small fixes

## [1.7.0] - 2015-02-19
### Added
- A proper Change Log file according to http://keepachangelog.com
- Allow leaving out of alerts parameter (empty array instead of false by default).

### Changed
- Replaced the deprecated Modulefile by a metadata.json
- Template variables use scope to be compatible to newer Puppet versions
- Use `fqdn` fact instead of `hostname` fact in config and slave manifest

### Fixed
- Slave parameter scope fixed


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*