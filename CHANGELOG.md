# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] 2019-05-29

### Changed
- Module ONLY accepts a _list of maps_ for the table_name, table_id, and schema. This enables the creation of multiple tables on a single dataset.
- Inspec attributes for testing in inspec.yml
- Examples for multiple tables per [Issue #5](https://github.com/terraform-google-modules/terraform-google-bigquery/issues/5)
- Testing with native inspec resources per [Issue #7](https://github.com/terraform-google-modules/terraform-google-bigquery/issues/7)
- Support for multiple tables per [Issue #6](https://github.com/terraform-google-modules/terraform-google-bigquery/issues/6)
- Examples to support google provider >2.5.0 per [Issue #8](https://github.com/terraform-google-modules/terraform-google-bigquery/issues/8)
- Upgraded Gemfile/Gemfile.lock for kitchen-terraform gems
- Module output for table name

[1.0.0]: https://github.com/terraform-google-modules/terraform-google-bigquery/compare/v1.0.0...HEAD

## [0.1.0] 2019-02-12

### Added

- This is the initial release of the Big Query module.

[0.1.0]: https://github.com/terraform-google-modules/terraform-google-bigquery/tree/v0.1.0/
