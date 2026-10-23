# Change Log

All notable changes to this project will be documented in this file. The format is based on [Keep a Changelog](https://keepachangelog.com), and this project adheres to [Semantic Versioning](https://semver.org).

## [1.1.0] - 23-10-2026

### Added

- `Name.FamilyNamePrefix` mapping that extracts the family name prefix (e.g. `van`, `de`, `van der`) from `LastName`.
- `Name.FamilyNamePartner` and `Name.FamilyNamePartnerPrefix` mappings (fixed, empty).

### Changed

- `Name.FamilyName` is now a complex mapping that strips the prefix and the partner name (after `-`) from `LastName`.
- `GivenName` is now mapped to `Name.NickName` (required) instead of `Name.GivenName`.

### Deprecated

### Removed

- `Name.GivenName` mapping.

## [1.0.0] - 11-03-2026

This is the first official release of _HelloID-Conn-Prov-Target-SDB-Planning-API_.

### Added

### Changed

### Deprecated

### Removed
