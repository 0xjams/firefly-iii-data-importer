# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## 0.3.0 - 2021-12-11

### Added
- [Issue 5342](https://github.com/firefly-iii/firefly-iii/issues/5342) Can import "external URL" field.
- Will now send report messages over mail if you want.

### Fixed
- Remove TODO's from README file.
- Respect date range when importing.
- Nordigen will pre-select country + bank
- Nordigen will recycle requisition
- Mapping works for Spectre + Nordigen
- Better secret management for Nordigen + Spectre
- [Issue 5351](https://github.com/firefly-iii/firefly-iii/issues/5351) Fix URL's
- Fix duplicate detection.
- Fix issue with transfers being imported as deposits.
- New debit indicator thanks to @reeperbahnause

## 0.2.0 - 2021-12-04

### Added
- There is a `/debug` page if you need it.
- Auto-import works over the command line.
- Importing works over the command line.
- Full documentation in place.

### Changed
- More consistent layout

### Fixed
- [Issue 5336](https://github.com/firefly-iii/firefly-iii/issues/5336) Undefined array key "Liabilities
- [Issue 5337](https://github.com/firefly-iii/firefly-iii/issues/5337) Config download fails
- [Issue 5338](https://github.com/firefly-iii/firefly-iii/issues/5338) APISubmitter not found in RoutineManager
- [Issue 5339](https://github.com/firefly-iii/firefly-iii/issues/5339) fails to read CSV delimiter correctly
- [Issue 5343](https://github.com/firefly-iii/firefly-iii/issues/5343) Missing config variable
- [Issue 5344](https://github.com/firefly-iii/firefly-iii/issues/5344) Protocol mismatch
- [Issue 5345](https://github.com/firefly-iii/firefly-iii/issues/5345) Some transactions are said to have the same source and destination

## 0.1.0 - 2021-11-27

First release of the data importer.

## 0.0.0 - 2021-xx-xx

### Added
- Initial release.

### Changed
- Initial release.

### Deprecated
- Initial release.

### Removed
- Initial release.

### Fixed
- Initial release.

### Security
- Initial release.
