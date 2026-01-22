# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- **Institutional Governance**: Added SECURITY.md, CONTRIBUTING.md, and comprehensive README.
- **Simulation Dashboard**: Added `scripts/master_dashboard.cjs` for 180-day financial projections.
- **Synthetic Logic**: Refined `SyntheticLivestockPool` for O(1) batch processing.

### Changed
- **Documentation**: Overhauled `docs/` structure to separate On-Chain vs. Off-Chain architecture.
- **Configuration**: Updated Hardhat config for robust Fuji testnet deployments.

## [1.0.0] - 2026-01-20
### Initial Release
- Deployment of MasterController, ValuationRegistry, and LivestockVault.
- Integration with Chainlink Functions for weight and price data.
