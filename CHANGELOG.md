# PSS-DSL syntax changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.4] - 2024-07-12

### Added
- added PSS.tmPreferences to be able to use CTRL+/ for commenting in code
- added some PSS 2.1 keywords
- added matching target/solve qualifier for native PSS functions
- added annotations

### Fixed
- matches enum extensions
- improved matching of constraints
- improved valid_scalar_type regexp

## [1.0.3] - 2023-03-30

### Changed
- minor fixes

### Added
- added compile-if and pools scope
- added typedef

## [1.0.2] - 2023-02-17

### Changed
- fix for extended structs matching
- exec target language match extended to support schemes
- improved function-declaration/function-call matching

### Added
- match function-calls inside of function-call-parameters scope
- added some PSS 2.1 keywords

## [1.0.1] - 2023-01-06
### Changed
- reduced meta-scope keyword.other.* -> keyword.other

### Added
- added .gitattributes

## [1.0.0] - 2023-01-05
### Added
- Initial release
