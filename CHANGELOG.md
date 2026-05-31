# Changelog

All notable changes to the [Sigmyne/smax-postgres](https://github.com/Sigmyne/smax-postgres) library will be 
documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to 
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.1-rc1] - 2026-05-31

Release candidate for upcoming maintenance release, expected around 15 July 2026.

### Fixed

 - Fixed inverted parse of `use_hyper_tables` boolean config setting.

### Changed

 - Use `snprintf()` instead of `sprintf()` when possible.
 
 - Use `strtok_r()` consistently.
 

## [1.0.0] - 2026-02-16

Initial public release.
