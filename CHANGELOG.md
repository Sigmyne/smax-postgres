# Changelog

All notable changes to the [Sigmyne/smax-postgres](https://github.com/Sigmyne/smax-postgres) library will be 
documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to 
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [1.0.1] - 2026-06-23

Maintenance release.

### Fixed

 - Fixed inverted parse of `use_hyper_tables` boolean config setting.

 - Storing arrays of string and character-arrays, did not advance the print position after the separator, causing 
   the strings to be truncated early before consecutive array elements.
 
 - Various fixes to minor issues spotted by Copilot.

### Changed

 - Use `snprintf()` instead of `sprintf()` when possible.
 
 - Use `strtok_r()` consistently.
 

## [1.0.0] - 2026-02-16

Initial public release.
