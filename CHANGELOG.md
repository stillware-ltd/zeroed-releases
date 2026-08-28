# Changelog

All notable user-facing changes to Zeroed are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Downloads and SHA256 checksums for each release live on the corresponding
[GitHub release page](https://github.com/stillware-ltd/zeroed-releases/releases).

## [1.3.0] — 2026-08-28

### Added
- Statement import: OFX/QFX/QIF support, hardened PDF/CSV parsing, duplicate detection across re-imports.
- Reconciliation: credit-card support, comma decimals, finish-with-adjustment for statements that don't quite match.
- Goals: one-tap starter goals, goal editing from the Budget screen, debt payoff planner improvements.
- macOS build (notarized `.dmg`, Apple Silicon & Intel) joins Windows and Android downloads.

### Changed
- Net worth: tracked assets/liabilities (loans, property) now valued correctly everywhere.
- The 34-day trial now unlocks every feature.
- Budget file format migrated (one-way) — update all devices to 1.3.0 together.

## [1.0.10] — 2026-04-17

### Added
- Sideloaded Android support — APK installs fall back to Paddle licensing when Google Play billing is unavailable.
- Founder's Seat pricing tier — $19 for the first 100 customers.

### Changed
- Activation cap raised from 3 to 5 devices per license (desktop + sideloaded Android).
- Checkout discount code updated from `OFFER40` to `FOUNDER`.

[1.3.0]: https://github.com/stillware-ltd/zeroed-releases/releases/tag/v1.3.0
[1.0.10]: https://github.com/stillware-ltd/zeroed-releases/releases/tag/v1.0.10
