# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [1.3.1] - 2020-07-29
### Added
- SQS queue message filter.
- Added tags to SY IAM role and SQS queue.

## [1.3.0] - 2020-03-31
### Added
- Log4j XML for internal Circus Train instance.

## [1.2.1] - 2020-01-16
### Added
- A new argument `orphaned_data_strategy` to use for handling stale data during replication.

## [1.2.0] - 2019-08-29
### Added
- Support for Docker Auth.
- Ability to store credentials for Docker auth in AWS secrets manager.
- Cloudwatch dashboard.
- Cloudwatch alerts.
- SQS queue permissions.

### Changed
- `selected_tables` variable is now a list.

## [1.1.0] - 2019-02-08
### Added
- New variable for passing Circus Train common configurations to Shunting Yard. eg. Graphite.

## [1.0.0] - 2019-02-06
### Added
- First version of Shunting Yard Integration with Apiary.
