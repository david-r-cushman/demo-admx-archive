# Changelog

All notable changes to this archive tooling baseline are documented in this
file.

This project uses [Semantic Versioning](https://semver.org/) for its archive
tooling: scripts, tests, workflows, documentation, and AI guidance. It does
not version vendor distributions stored under `versions/`.

## Unreleased

### Added

- Added contribution and security policies plus a public bug-report form for
  the template's community-health baseline.

- Added a self-authored, fictional demonstration-artifact policy.

### Changed

- Identified this derived archive as the Example Vendor demonstration of the
  vendor-admx-archive template.

- Made the README relationship to the reusable template explicit with a
  reciprocal link.

- Explained the archive's operational-continuity purpose and its boundary from
  Intune, Group Policy, Active Directory, and deployment-state recovery.

- Corrected the generated registration-splat variable name in documentation
  and comment-based help.

- Renamed the GitHub Actions workflow to Pester Tests and added its status
  badge to the README.

### Fixed

- Preserved self-authored ADMX and ADML bytes as distributed so inspection
  copies remain byte-for-byte comparable with the demonstration ZIP archives
  on every supported checkout platform.

## 0.1.0 - 2026-11-17

### Added

- Initial vendor-neutral archive tooling baseline, including integrity-focused
  registration and verification scripts, Pester coverage, Ubuntu CI,
  documentation, and AI operating instructions.
