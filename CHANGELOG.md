# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Changed
- Docs for Facebook if using iOS 13 and Facebook pod 5.x #56

## [1.0.1] - 2019-09-19
### Added
- Add OpenID not supported to README
- Add CHANGELOG file to project

### Fixed
- web/pwa: `pkceCodeChallenge` was always `undefined` because promise was not awaited properly #53 (thx @nicksteenstra)

## [1.0.0] - 2019-06-26

### Added
- Add minimum cap version to installation notice

### Changed
- Upgrade to Capacitor 1.0.0 #43,#39

### Fixed
- Android: Fix plugin does not send resource url response to app after specific steps #28
- Android: Fix Java compiler error #36 (thx @Anthbs)
- Fix github security error by updating Jest lib


[Unreleased]: https://github.com/moberwasserlechner/capacitor-oauth2/compare/1.0.1...master
[1.0.1]: https://github.com/moberwasserlechner/capacitor-oauth2/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/moberwasserlechner/capacitor-oauth2/releases/tag/1.0.0
