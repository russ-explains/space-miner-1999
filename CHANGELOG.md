# Changelog

## v1.2.0 — 2026-10-08
### Changed
- Mining pits are now integrated into the planet surface as deep dips in the terrain.
- Falling into a mining pit costs one hull/shield point rather than an entire life.
- Mining jump is now **Space**, kept separate from the jetpack.
- Mining jetpack is now **W**, with its own separate fuel supply and HUD gauge.
- Mining jet fuel is displayed as **JET** rather than PACK.
- Ship bullets now have a much longer lifetime and can travel down to the mining surface.
- Added keyboard test shortcuts:
  - **1** = flight
  - **2** = lunar landing
  - **3** = mining
  - **4** = cavern escape
- Added an on-screen mining control reminder for Space/W.

All notable changes to Space Miner 1999 are recorded here.

## v1.1.2 — 2026-10-08
### Fixed
- Fixed a JavaScript parsing error introduced during the pause-system update.
- Restored the **P** key pause/unpause handler.
- Pausing now freezes gameplay updates and stops the thrust sound.
- Added the clear **PAUSED / PRESS P TO CONTINUE** overlay.

### Notes
- This release fixes the broken v1.1.1 build.

## v1.1.1 — 2026-10-08
### Added
- Added a pause system using **P**.
- Added a **PAUSED / PRESS P TO CONTINUE** overlay.
- Intended to freeze movement, enemies, oxygen, fuel, timers and gameplay while paused.

### Notes
- This release contained a script-parsing error and was superseded by v1.1.2.

## v1.1.0 — 2026-10-08
### Added
- Redesigned the mining level around limited oxygen and backpack fuel.
- Added upper platforms that can be reached using the jetpack.
- Added oxygen and backpack-fuel pickups on upper platforms.
- Added holes in the planet surface to jump across.
- Added aliens patrolling the upper platforms.
- Added a flying saucer that attacks the miner.
- Removed ship-fuel pickups from the mining level; mining now focuses on gems and survival resources.
- Added O2 and PACK indicators to the mining HUD.

## Versioning
- Patch (v1.1.x): bug fixes and small changes.
- Minor (v1.x.0): new gameplay/features.
- Major (v2.0.0): major overhaul.
- Every update must increment the version number and add an entry to this changelog.