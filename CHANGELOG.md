# Changelog

All notable changes to this project will be documented in this file.

The format is based on Keep a Changelog, and this project adheres to Semantic Versioning (X.Y.Z).

## [0.2.1] - 2025-11-10

## Added

- GPG-signed release workflow with protected `main`.
- `release.sh` (Phase 1) to bump version and push signed release branch.
- `release-tag.sh` (Phase 2) to create signed tag and trigger PyPI publish.
- `gpg-check.sh` helper and Makefile targets (`release-patch`, `release-minor`, `release-major`, `release-tag`, `gpg-check`).
- README/CONTRIBUTING documentation for release workflow.

## Changed

- Version bump automation and branch creation now resilient to existing branches.

## Fixed

- Prevent direct pushes to protected `main` during releases.

## [0.2.0] - 2025-11-09

## Added

- Initial CI/CD for publishing to PyPI on tag.
- README badges and PyPI alignment.
- Project structure stabilized.

## [0.1.2] - 2025-11-08

## Added

- First public release of `dns-benchmark-tool`.
- Core benchmarking functionality and CLI.

---
