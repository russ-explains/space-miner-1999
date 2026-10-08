# Changelog

## v1.4.2 — 2026-10-08
### Fixed
- Corrected the normal new-game reset so the asteroid-flight section now genuinely starts at **55% fuel**, rather than the previous 100%.


## v1.4.1 — 2026-10-08
### Changed
- The opening asteroid-flight section now starts with the ship's fuel at **55%**, just over half full.
- Later flight sections continue using the ship's remaining fuel rather than resetting it.

## v1.4.0 — 2026-10-08
### Changed
- Landing landscapes are now progressively harder from planet to planet.
- Planet 1 keeps a relatively gentle surface.
- Planet 2 now has **medium peaks** and increased asteroid traffic.
- Planet 3 introduces **high peaks**, with later planets becoming progressively taller and tighter.
- Landing pads remain deliberately flatter so the increased terrain difficulty is challenging without making successful landings arbitrary.
- Asteroid counts and maximum sizes increase with each planet.

## v1.3.0 — 2026-10-08
### Changed
- Lowered the miner's on-screen position so his feet now line up with the green aliens' feet on the same platform surface.
- Adjusted alien collision detection to use the miner's corrected visual position.
- Alien contact now requires a close horizontal and vertical overlap, while still costing **one hull point** through the existing damage system.

## v1.2.9 — 2026-10-08
### Changed
- Made the mining-surface holes much more visually obvious with darker, deeper-looking openings and stronger highlighted rims.
- Widened some of the holes so they are easier to recognise as hazards.
- Falling through a hole continues to use the existing hull-damage system, costing **one hull point** rather than an entire life.

## v1.2.8 — 2026-10-08
### Changed
- Increased jetpack lift from **0.24** to **0.34** per frame for a more definite upward thrust.
- Reduced jetpack fuel consumption by **30%**, from 0.63 to 0.441 per frame.
- Added a small visible backpack/jetpack to the miner.
- Added animated jet propulsion beneath the backpack while the jetpack is firing.

## v1.2.7 — 2026-10-08
### Changed
- Tightened mining-planet enemy hit detection so alien and saucer-bomb hits require a much closer visual contact.
- Corrected green alien positioning so their feet sit directly on their platform surface instead of appearing to float.
- Removed **W** as the jetpack control.
- Mining now uses a single **Up Arrow** control: tap once to jump, release, then tap Up again while airborne to engage the jetpack; hold Up to continue burning jetpack fuel.
- Jetpack fuel only drains while the jetpack is actively engaged.

## v1.2.6 — 2026-10-08
### Changed
- Section 4 lava now rises approximately **20% faster**, increasing the pressure of the escape sequence.

## v1.2.5 — 2026-10-08
### Changed
- Colliding with a green alien now removes **one hull point**, using the existing temporary invulnerability system.
- Green aliens now occasionally make a short, fast dash of roughly **three alien lengths**, giving them a more deliberate movement pattern that has to be judged and shot.

## v1.2.4 — 2026-10-08
### Changed
- Oxygen now drains at approximately **double the previous rate**, making oxygen collection and route planning much more urgent.
- The Section 4 lava starts **much closer to the miner** when the escape begins.
- The lava begins advancing sooner and rises slightly faster, creating a stronger forced-race feeling during the cavern escape.

## v1.2.3 — 2026-10-08
### Changed
- Oxygen now drains approximately **30% faster** during mining.
- Jetpack fuel consumption while holding **W** is approximately **30% lower**, giving the miner more lift per unit of fuel.
- Collecting all 3 ship-fuel canisters still fills the jetpack to maximum, but **does not automatically activate the jetpack or launch the miner**.
- After finding all 3 F canisters, the player can choose whether and when to use the fully charged jetpack.
- Flying-saucer bombs now have enough lifetime to travel all the way down the mining area, making the saucer a continuing ground-level threat.
- Saucer/enemy hits, falling through cracks, falling off-screen, and spike/pit impacts all use the hull-damage system and can ultimately cost a life.

## v1.2.2 — 2026-10-08
### Changed
- Increased starting jetpack fuel so the miner has more breathing room when reaching the upper platforms.
- Jetpack fuel now slowly regenerates while the miner is exploring, preventing the miner from becoming permanently stranded.
- Once all 3 ship-fuel canisters are collected, jetpack fuel immediately becomes full and remains full.
- With all 3 ship-fuel canisters collected, the jetpack provides continuous lift without needing the jump key.
- Falling through the bottom of the mining screen now causes hull damage, using the same damage system as mining-pit impacts.
- The mining exit now requires all **3 F canisters**.

## v1.2.1 — 2026-10-08
### Fixed
- Corrected Section 3 controls: **Arrow Up = jump**, **Space = fire**, **W = jetpack**.
- Reduced the mining jump height slightly.
- Mining now starts with a small amount of jetpack fuel, enough to reach the first couple of upper platform levels.

### Added
- Added distinct **J** jetpack-fuel pickups and **F** ship-fuel canisters.
- Added a limited **ship-fuel objective**: collect both F canisters before returning to the ship to begin take-off.
- Added additional oxygen pickups so oxygen remains a limited resource that must be managed while exploring.
- Mining HUD now shows ship-fuel progress alongside the oxygen and jetpack gauges.

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
