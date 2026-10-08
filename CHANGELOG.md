## v1.8.3
- Added an **EXTRA LIFE +1** upgrade for **4 gems**.
- Buying it immediately adds one life and displays an **EXTRA LIFE!** message.
- Adjusted upgrade spacing to fit the additional option.

## v1.8.2
- Updated the shield upgrade label to explicitly say **“(PRESS S)”** so players know how to activate it.

## v1.8.1
- Players can now buy and carry up to **3 collision shields**.
- Each shield still lasts **2 seconds** when activated with **S**, and one charge is consumed per activation.
- The upgrade screen shows the current shield count and the maximum of 3.
- The **U** testing shortcut grants 3 shields.

## v1.8.0
- Kept exactly **one oxygen pickup per mining level**.
- Positioned the blue box with the white **“O”** beside the third **F** ship-fuel pickup for easier discovery.

## v1.7.9
- Removed the oversized expanding pink saucer-bomb blast graphic from asteroid flight.
- Bomb detonations now use a smaller burst of particles instead.
- Tightened ship damage to a **34px radius** around the detonation, matching the small explosion effect.
- Asteroids can still be destroyed within the larger blast area.

## v1.7.8
- Made the mining oxygen tank clearly visible as a **small blue box with a white “O”**.
- Kept exactly **one oxygen tank per mining level**.
- Moved its position slightly further right, to about **82% across the mining map**.

## v1.7.7
- Doubled the saucer bomb blast radius from **408px to 816px**.
- Added a large visible expanding blast effect to match the full damage radius.
- The ship is now damaged anywhere inside that same **816px explosion radius**.

## v1.7.6
- Changed the mining oxygen supply to **one oxygen tank per mining level**.
- The single oxygen tank is now positioned towards the **right-hand side of the map** on every mining level.

## v1.7.5
- Added a temporary **U-key test cheat** for gameplay testing.
- Press **U** on any gameplay level to grant all current upgrades at their maximum levels: full fuel tank, full hull, maximum laser, maximum thrust, and a ready collision shield.
- Added a **TEST UPGRADES** panel on the right side of the gameplay screen showing the active test upgrades.
- This is intentionally a temporary development/testing feature and is marked for removal later.

## v1.7.4
- Added a new **2-gem Collision Shield** upgrade on the ship-upgrade screen.
- The shield is a one-use item that can be saved across planets and used on any gameplay section.
- Press **S** to activate it; the shield lasts **2 seconds** and blocks collision/impact damage during that time.
- Collision protection covers asteroid impacts, saucer/alien impacts, mining-pit falls and cavern impacts, but does not block enemy/projectile damage.
- Added a visible shield effect and HUD status showing when it is ready or active.

## v1.7.3
- Mining falls into holes now cause immediate hull damage as soon as the astronaut passes below the planet's normal surface level.
- Removed the old deep-pit delay, so the astronaut no longer has to fall far down the hole before taking damage.
- Existing bottom-of-screen fall damage remains as a safety net.

## v1.7.2
- From Planet 3 onwards, roughly half of the mining aliens are now tougher two-hit variants.
- Tough aliens have a slightly different, bulkier appearance.
- After the first shot, their upper body is removed, leaving the legs/body base visible; a second shot destroys them.
- Planets 1–2 keep the original one-hit aliens.

## v1.7.1
- Removed alien jumping and dashing from the mining section.
- Aliens now simply patrol left and right along their platforms and turn around at the edges.
- Alien collisions, health, and shooting behaviour remain unchanged.

## v1.7.0
- Mining/jetpack falls now trigger hull damage as soon as the astronaut drops just beyond the bottom of the screen.
- Uses the existing fall-damage system, removing one hull point just like an alien impact and resetting the astronaut safely back onto the surface.

## v1.6.9
- Doubled the saucer bomb flight/fuse duration from 60 to 120 frames, giving the homing bombs roughly twice the travel distance.
- Tripled the bomb blast radius from 136px to 408px.
- Tripled the visual detonation burst size from 28 to 84.

## v1.6.8
- Made escape-cavern side impacts almost non-bouncy on all planets.
- Side collisions now clamp the ship back inside the cavern and retain only 5% of its horizontal velocity, with virtually no vertical rebound.
- The ship receives only a very small corrective push away from the wall, keeping it controllable after an impact.

## v1.6.7
- Restored normal saucer bullets to their original straight-line aimed behaviour.
- Changed only the Planet 3–5 saucer bombs to gently curve towards the player.
- Doubled the bombs' fuse/travel lifetime from 60 to 120 frames, giving them roughly twice the travel range.
- Kept the large 136px bomb blast radius unchanged.

## v1.6.6
- Further dampened escape-section collision rebound on all planets, reducing the retained vertical bounce from 22% to 10%.
- Keeps spike and cavern-side impacts much more controllable, allowing the player to correct their trajectory immediately after a collision.

## v1.6.5
- Asteroid-flight enemy shots now gently curve towards the player instead of travelling in a perfectly straight line.
- Doubled their lifetime from 220 to 440 frames, giving them roughly twice the previous travel range.
- The homing is deliberately gentle so the shots remain dodgeable.

## v1.6.4
- Damped the escape-section collision rebound from 55% of the previous upward velocity to 22%.
- This reduces the bounce-back by about 60%, giving the player substantially more control after hitting cavern sides or spikes.

## v1.6.3
- Increased fuel gained from blue fuel blobs in the asteroid-flight section by 25%, from 6 to 7.5 fuel.
- Other fuel sources and sections are unchanged.

## v1.6.2
- Fixed the Level 5 escape completion so the final **CONGRATULATIONS!** victory screen is shown when testing Level 5 with the shortcut.
- Final Planet 5 completion now uses the same victory path as a normal run.

## v1.6.1
- Increased oxygen drain in the Mining section from 0.048 to 0.060 per frame (25% faster).
- Asteroid flight, landing, and cavern escape/lava sections are unchanged.

## v1.6.0
- Added a dedicated **Level 5 victory scene** after completing the final escape.
- Displays **CONGRATULATIONS!** and **PLANET 5 — MISSION COMPLETE!**
- Added a large rocket ship beside the astronaut, approximately eight times his height.
- Added a waving astronaut and a small friendly robot companion.
- Kept the existing score and restart behaviour on the victory screen.

## v1.5.7
- Planet 3–5 saucers now fire their original aimed shots **as well as** dropping pulsing mines.
- Increased the mine explosion radius from 34 to 136 pixels (4×).
- Mine explosions can now destroy asteroids caught in the blast and award their normal asteroid score.
- Planets 1–2 retain their original saucer-shot behaviour.

## v1.5.6
- Added a gentle lava catch-up mechanic to the escape section.
- If the lava drops too far below the visible screen, it receives a small boost to keep it close to the bottom edge.
- This keeps the lava visible often enough to create tension without making it suddenly jump onto the player.

## v1.5.5
- Increased lava flow speed by 15% on Planets 4 and 5 in the cavern escape section.
- Planet 4–5 lava remains slower than the original late-planet speed to account for the narrower passages.

## v1.5.4
- Fixed Planet 3–5 saucer bombs not being visible: the bomb drawing was happening during the update phase and was then cleared by the main flight render.
- Saucer bombs are now clearly **pink and pulsing** and remain on screen during their one-second fuse.
- Bomb spawning and explosion behaviour remain unchanged.

## v1.5.3
- Slowed the rising lava significantly on Planets 4 and 5 in the cavern escape section to give more time to navigate the narrower passages.
- Planets 1–3 keep their existing lava speed.

# Changelog

## v1.5.2 — 2026-10-08
### Fixed
- Lowered the mining-section gun's bullet path so shots line up better with the aliens.
- The adjustment affects the mining gun only; firing speed and damage remain unchanged.

## v1.5.1 — 2026-10-08
### Added
- On Planets **3–5**, the flying saucer now drops small pulsing bombs.
- Each bomb has an approximately **1-second fuse** before exploding.
- Explosions have a small blast radius and can damage the ship if it is nearby.
- Planets 1–2 retain the existing saucer projectile behaviour.

## v1.5.0 — 2026-10-08
### Changed
- Increased asteroid-flight difficulty progressively across all five planets.
- Planet 2 and later now have denser asteroid fields.
- Planet 3 and later now use substantially larger asteroids, with size increasing further on later planets.
- Asteroid density and size now scale progressively through Planets 1–5.

## v1.4.6 — 2026-10-08
### Changed
- The normal game now starts the opening asteroid-flight section at **30% fuel**.
- The **1** shortcut also starts the opening asteroid-flight section at **30% fuel**.
- Fuel continues normally into later sections without being reset.

## v1.4.5 — 2026-10-08
### Changed
- Pressing **2** again while already in the landing section now advances to the next planet's landing test.
- Pressing **4** again while already in the cavern escape section now advances to the next planet's cavern escape test.
- All four section shortcuts now support quick planet-to-planet testing.

## v1.4.4 — 2026-10-08
### Changed
- Pressing **1** again while already in asteroid flight now advances to the next planet's flight section.
- Pressing **3** again while already mining now advances to the next planet's mining section.
- These shortcut advances preserve the current run resources rather than resetting the ship's fuel.
- The shortcuts stop advancing once the final planet is reached.

## v1.4.3 — 2026-10-08
### Changed
- The **1** level-1 test shortcut now starts at **30% fuel**.
- This only affects the level-1 shortcut; normal new games still start at 55% fuel.
- Fuel continues normally through later sections without being reset.

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
