# Changelog — gregMod.MoreServers

Format: [Keep a Changelog](https://keepachangelog.com/de/1.0.0/). Version: see [`VERSION`](VERSION).

## [1.0.13] — 2026-09-24

### Changed

- English strings throughout.

## [Unreleased]

### Added

- Unified open-source layout (README, docs, badges) following the gregCore template.

### Fixed

- Boxes/modules vanishing on relog: `sfpsBoxedPrefab` is now extended with
  custom box templates alongside `sfpPrefabs`, and new
  `GetSfpPrefab`/`GetSfpBoxPrefab` prefixes serve custom IDs on demand so
  save/load can resolve boxType/prefabID 1000+ (same fix as MoreModules).
- Loaded bulk boxes regain their 32 slots: the expansion scan now also runs
  after `LoadSFPsFromSave`, not just after purchase.
- Stable save IDs (`ModuleDefinition.SaveId`, 1000+): catalog order no longer
  affects persisted IDs; duplicates/invalid IDs are rejected at setup.
- Sibling handling re-evaluates on every Awake (no restart latch) and now
  also yields to active RealisticModules (1000+ legacy-alias overlap).

## [0.1.0] — 2026-09-22

- Initial standardized baseline.
