# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
<!-- and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html). -->

## [1.3.4] - 2019-09-01
### Changed
- Log exception on error (pull request #6)
- Use Microsoft.CSharp from NuGet package when buliding .NET Standard. (pull request #7)

## [1.3.3] - 2018-30-07
### Changed
- Typo fix (pull request #5)

## [1.3.2] - 2018-21-06
### Changed
- Use relative url (pull request #3)

## [1.3.1] - 2018-04-13
### Changed
- In ApplicationHostnameStrategy, hostname is set as the in other library implementations (hostname environment variable, and if not set; Dns.GetHostName()).

## [1.3.0] - 2017-12-04
### Changed
- Better error handling during api server downtime etc.
- Improved object synchronization (multiple readers/single writer) for MetricsBucket / ToggleCollection
- Internal refactoring

## [1.2.2] - 2017-11-30
### Changed
- Changed IJsonSerializer interface.

## [1.2.1] - 2017-11-30
### Added
- Major internal refactorings
- More extension points for users of the library

### Changed
- UnleashConfig became UnleashSetting without fluent interface

## [1.1.2] - 2017-11-24
### Added
- First draft of the library


<!-- 
Types of changes:

Added - for new features.
Changed - for changes in existing functionality.
Deprecated - for soon-to-be removed features.
Removed - for now removed features.
Fixed - for any bug fixes.
Security - in case of vulnerabilities. 
-->