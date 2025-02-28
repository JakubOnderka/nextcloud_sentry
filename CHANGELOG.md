# Changelog
All notable changes to this project will be documented in this file.

## 4.0.1 – 2019-02-12
### Changed
- Update some dependencies
### Fixed
- Update vulnerable `lodash` dependency

## 4.0.0 – 2018-12-12
### Added
- Test command now includes breadcrumbs
- Nextcloud 16 support
### Changed
- Dropped Nextcloud 14 support
### Fixed
- JavaScript reports

## 3.4.1 – 2018-11-13
### Fixed
- Infinite recursion during an error report

## 3.4.0 – 2018-11-09
### Added
- Breadcrumb support
- Nextcloud 15 support
- Set username (loginname) if possible
### Fixed
- Loading of public DSN for custom app directories

## 3.3.0 – 2018-08-20
### Added
- Tagging of the affected app if it's known by the context
### Changed
- Updated Sentry's PHP library

## 3.2.0 – 2018-08-08
### Added
- Release version tagging for JavaScript reports

## 3.1.0 – 2018-08-07
### Added
- Test command `occ sentry:test` to test the configuration

## 3.0.0 – 2018-08-02
### Changed
- Dropped Nextcloud 13 support
- Requires php7.0+
- Updated Sentry library

## 2.0.1 - 2018-05-16
### Fixed
- JavaScript exception reporting on public pages

## 2.0.0 - 2018-05-15
### Added
- JavaScript exception reporting (see admin docs for configuration)

## 1.2.0 - 2018-05-14
### Changed
- Updated Sentry SDK

## 1.1.0 - 2017-12-12
### Added
- Configurable log level to filter out warnings
- Php7.2 support
- Admin documentation
### Fixed
- Better app description
