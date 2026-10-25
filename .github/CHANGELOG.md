# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Calendar Versioning](https://calver.org/) (YYYY.0M.0D).

## [Unreleased]

## [2026.10.24] - 2026-10-24

### Changed

- Maintenance and version synchronization release.

## [2026.10.24] - 2026-10-24

### Changed

- Maintenance and version synchronization release.

## [2026.10.20] - 2026-10-20

### Added

- Governance & Consistency: Added repository consistency directives, Cursor rule `.cursor/rules/repository-consistency.mdc`, and complete `.github` community health standards.
- Tooling: Added `.vscode/PSScriptAnalyzerSettings.psd1` and `tools/Test-RepositoryConsistency.ps1`.
- Documentation: Added dedicated `Convert-WindowsImage.README.md`.

### Changed
- Coding Standards: Prohibited casting to [void] in addition to Out-Null; unneeded output must be discarded by assigning to $null = ....

- Script Implementation: Refactored `Convert-WindowsImage.ps1` to conform to PowerShell 7+ standards, parameter splatting, explicit parameter typing, and `$PSItem` pipeline variable usage.
- Standards: Standardized repository versioning to Calendar Versioning (YYYY.0M.0D) and configured OTBS code formatting.
- Licensing: Normalized repository licensing to standard `LICENSE.MD` (Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International).

### Removed

- Licensing: Removed deprecated legacy `LICENSE` and `LICENSE_MIT` files in favor of standard `LICENSE.MD`.

[2026.10.20]: https://github.com/STS-Consulting/STS/releases/tag/2026.10.20

[2026.10.24]: https://github.com/STS-Consulting/STS/compare/2026.10.20...2026.10.24

[unreleased]: https://github.com/STS-Consulting/STS/compare/2026.10.24...HEAD
[2026.10.24]: https://github.com/STS-Consulting/STS/compare/2026.10.20...2026.10.24
