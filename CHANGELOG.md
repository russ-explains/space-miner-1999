## v1.9.65 — 2026-10-19
- The grappling hook can now strike floating asteroids during cavern descent, splitting larger rocks into smaller moving chunks that can be broken apart again.
- Hook targeting now considers both reachable worms and cavern asteroids.

## v1.9.64 — 2026-10-19
- Players now start each new run with **one shield charge**; the **U** testing cheat still grants three.

## v1.9.63 — 2026-10-19
- Restored the **1–4** gameplay test shortcuts: each key jumps to its corresponding section, and pressing the same key again advances to that section on the next planet, through the fifth planet.

## v1.9.62 — 2026-10-19
- Restored the **U** gameplay test cheat: fully refuels the ship, grants maximum hull, laser and thrust upgrades, three shields, full jetpack fuel and oxygen, 99 banked gems, extra lives, and the grappling hook.

## v1.9.61 — 2026-10-19
- Integrated Tim's updated game script, including bubbling/steaming lava pools on the mining surface and the space-worm hazards in the cavern descent.
- Extended the cavern worms much farther into the passage, leaving only a narrow gap to manoeuvre through.

## v1.9.58 — 2026-10-11
- Reduced the score threshold for earning a free extra ship from **50,000 points to 25,000 points**.
- Updated the on-screen mission briefing and the displayed extra-ship rule to match the new threshold.

## v1.9.57 — 2026-10-11
- Removed the temporary gameplay test cheats: number keys **1–4** can no longer jump between sections or planets, and **U** no longer grants test upgrades/resources.
- Normal controls, the **C** CRT toggle, and the **P** pause key remain available.

## v1.9.56 — 2026-10-11
- Enlarged the astronaut's jetpack backpack so it reads more clearly during mining.
- The backpack swaps sides when the astronaut turns left or right.
- Reworked the jet exhaust to emerge directly from the backpack nozzle, with a longer tapered flame and bright inner core.

## v1.9.55 — 2026-10-11
- Guaranteed a flat cavern floor shelf around each landing pad, with the shelf wider than the pad by a responsive safety margin.
- Made the mountain outline sample the same shelf-aware profile used by collision, so the wider floor is visible and stays free of solid mountain terrain.

## v1.9.54 — 2026-10-11
- Made the jagged cavern mountains solid terrain: the lander can no longer pass through them.
- Mountain impacts remove one HULL point and bounce the lander back above the ridge; existing invulnerability prevents repeated damage from one contact.
- Added more uneven peaks and shoulders throughout the cavern, with clear low shelves at both landing pads.
- Positioned the small x3 pad in a low gap between two right-side ridges to make the approach more challenging without placing the pad inside a mountain.

## v1.9.53 — 2026-10-11
- Made the x3 bonus landing pad on vertical cavern planets smaller, matching the approximate proportions of Planet 1's bonus pad.
- Moved the x3 pad further to the right to make its approach more exposed and challenging.
- Reworked cavern mountain silhouettes into several uneven, jagged ridges with multiple peaks and shoulders, including a more rugged approach near the bonus pad.

## v1.9.52 — 2026-10-11
- Changed floating-asteroid collisions during cavern landings to remove one HULL point instead of instantly destroying the lander.
- Added a small knockback to separate the lander from the asteroid; invulnerability frames prevent a single overlap from repeatedly draining HULL.
- Confirmed cavern wall impacts also use one-HULL damage, as introduced in v1.9.51.

## v1.9.51 — 2026-10-11
- Changed landing-cavern wall collisions from instant destruction to a one-HULL-point impact, with existing invulnerability frames preventing repeated damage from a single contact.
- Kept wall impacts physically bounded with a gentle rebound so the lander is pushed back into the cavern.

## v1.9.50 — 2026-10-11
- Removed the flashing **READY** sign after the first mining planet's instructions; the rules remain available without that extra prompt.
- Hard-capped hull at **3** across the HUD/game state, damage recovery, repair upgrade and **U** testing cheat.
- Added tall rocky mountain shapes to the large landing caverns on Planets 2–5, rising to around 70% of the screen height while keeping both landing pads clear.
- Restyled the later-planet landing pads to match Planet 1's flat pad, support legs, and blinking end markers; the x3 bonus marker remains.

## v1.9.49
- Re-enabled test shortcuts during gameplay: **1** = asteroid flight, **2** = landing, **3** = mining, **4** = cavern escape.
- Repeating the current section shortcut advances to the next planet, stopping at the final planet.
- Re-enabled **U** to grant full fuel, upgraded hull/laser/thrust, three shields, full jetpack fuel, and a large gem bank for testing.

## v1.9.48
- Expanded the bottom landing cavern on Planets 2–5 to at least a full screen in height, with a wide open chamber and both landing pads at the bottom so players can choose where to land.
- Increased starting fuel for the opening asteroid level by another 20 points, from 41.4 to 61.4.
- Changed the free extra-life threshold to 50,000 points and updated the mission briefing to match.

## v1.9.47
- Added drifting, rotating asteroids throughout the vertical landing caverns; collisions can destroy the lander.
- Asteroid count and size increase on each successive planet, while the bottom landing chamber remains clear of spawned asteroids.

## v1.9.46
- Fixed Planet 1 mining instructions so the guide is visible immediately when the level loads, before gameplay begins; the first control input starts its four-second dismissal timer.
- Widened the bottom of vertical landing caverns into a broad landing chamber with small floor ridges and two reachable landing pads, including the x3 bonus pad.
- Adjusted landing detection to recognise either pad at its own height.

## v1.9.45
- Changed landing sections on Planets 2–5 into vertically scrolling cavern descents, with a landing pad at the bottom and moving rock hazards.
- Increased cavern depth, corridor difficulty and landing precision requirements on each later planet; Planet 1 keeps its original horizontal lander.

## v1.9.44
- Restored the mining mission guide on Planet 1 only; it stays visible indefinitely until the player presses a control, then remains visible for another four seconds before the READY countdown.
- Later mining planets no longer show the introductory guide.

## v1.9.43
- Increased blue fuel-ring pickups on the first asteroid level by 35%, from 7.5 to 10.125 fuel units. Later levels are unchanged.

## v1.9.42
- Fixed the information screen keyboard handling so ENTER reaches the menu handler and closes the briefing as intended.

## v1.9.41
- Added a “PRESS ENTER FOR MORE INFO” prompt to the title screen.
- Added an in-game mission briefing covering the gameplay loop, survival resources, upgrades, controls, planets, extra-life scoring and high-score saving.

## v1.9.40
- Removed the on-screen mobile control buttons.
- Moved the lives icons and fuel, hull, jetpack and oxygen HUD indicators inward from the screen edges for easier visibility.

## v1.9.39
- Doubled the mining jetpack flame size and repositioned both exhausts to emerge from beneath the backpack on the miner's back.

## v1.9.38
- Halved the mining saucer's downward firing frequency on Planet 1 only, from every 75 frames to every 150 frames. Later planets are unchanged.

## v1.9.37
- The victory screen now displays the final score, then automatically returns to the main intro screen after eight seconds so the high-score table is visible.

## v1.9.36
- Mining mission instructions now remain on screen until the player presses a control; dismissing them starts a brief flashing READY! countdown before gameplay begins.

## v1.9.35
- Stopped ship-fuel consumption during the final approach once the planet becomes visible, so players can thrust towards it without losing precious fuel.

## v1.9.34
- Added a two-second mining-level briefing with illustrated F, J and O crates and their purposes.
- Stacked collected F fuel crates beside the parked ship and kept the collected count visible in the HUD.
- Added a jetpack ceiling below the flying saucer on mining levels.

## v1.9.33
- Fixed the final-planet flow so collecting the three ship-fuel pickups and reaching the ship no longer ends the game as a win.
- On planet 5, players must now launch into the rising-lava cavern and escape successfully before the victory screen appears.

## v1.9.32
- Moved shield activation from S to the DOWN ARROW key.
- Increased each shield activation from 2 seconds to 3 seconds and updated the on-screen labels.

## v1.9.31
- Corrected laser and thruster upgrades to cost 2 gems each, matching the displayed prices.
- Restricted launching from the upgrade screen to the ENTER key; Arrow Right and clicking/tapping the launch area no longer skip the upgrade screen.
- Updated the on-screen instructions to make the launch key clear.

## v1.9.30
- Improved the planetary jetpack with a stronger initial hop and stronger sustained lift.
- Reduced jetpack fuel consumption slightly so players can stay airborne longer.

## v1.9.29
- Disabled debug cheat shortcuts: number keys 1–4, T/L/U upgrade cheats, and I to open the upgrade screen mid-stage.
- Removed the upgrade-screen test instructions and test-upgrade display.

## v1.9.28
- Saucer bombs now detonate immediately when they touch the ship, as well as when their fuse expires.
- The explosion removes one hull point if it reaches the ship, unless the active 2-second shield protects it.

## v1.9.27
- Made the active 2-second shield block all hull/suit damage, including saucer bullets, saucer bombs, enemy fire, and collision impacts.

## v1.9.26
- Changed saucer bomb blasts so they split large asteroids down by one size tier instead of destroying asteroids outright; smaller fragments are left alone.

## v1.9.25
- Added gentle landing-pad attraction while the 2-second collision shield is active, helping guide the ship towards the nearest pad during descent without taking over steering.

## v1.9.24
- Increased starting ship fuel from 36 to 41.4 units (15% more).
- Slowed mining-planet oxygen drain by 30% on level 1, 20% on level 2, and 10% on level 3 and every level thereafter.

## v1.9.23
- Enabled T, L and U ship-upgrade test controls directly on the upgrade screen, so players can cycle thrusters, cycle lasers, or max all upgrades while previewing the result.
- The upgrade screen ship preview now uses the player's current upgrade combination, and the test keys are listed on screen.

## v1.9.22
- Reworked player ship visuals so laser and thruster upgrades combine instead of overriding one another.
- Added distinct classic arcade silhouettes for five thruster tiers, from the slim interceptor through twin-engine, broad freighter, swept-wing and heavy gunship designs.
- Laser tiers now add progressively larger red weapon details on top of whichever hull matches the current thruster level. The original ship remains unchanged before any upgrade.

## v1.9.21
- Added subtle workshop ambience to the upgrade screen: quiet distant drill-like noise and a soft periodic hammering sound, using the existing Web Audio system.
- Workshop ambience stops when leaving the upgrade screen and does not add a separate game-loop timer.

## v1.9.20
- Made the supplied triangular ship design appear whenever the player has any laser upgrade, unless the maximum-upgrade Level 2 design takes priority.
- Kept the slim twin-thruster design for thruster upgrades when no laser upgrade has been purchased.

## v1.9.19
- Added the I key as a test shortcut to open the normal between-level upgrade screen during gameplay.

## v1.9.18
- Made the ship shown on the planet surface use the player's current ship design, including the twin-thruster and maximum-upgrade variants.

## v1.9.17
- Added test controls during gameplay: press T to increase thruster level up to maximum, and L to increase laser level up to maximum. Ship artwork updates immediately as levels change.

## v1.9.16
- Added a slimmer version of the original ship with two small rear engines when the player buys the first thruster upgrade.
- Preserved the original ship before upgrades, the triangular Level 1 design for laser-only upgrades, and the Level 2 design for maximum laser and thruster upgrades.

## v1.9.15
- Added the Level 2 maximum-upgrade ship design when both laser and thruster upgrades are maxed: red wing laser emitters, twin engine nozzles, and matching twin/triple thrust effects.
- The original ship remains unchanged before upgrades, and the simpler triangular Level 1 design remains in use until both upgrade types reach maximum.

## v1.9.14
- Kept the existing player ship unchanged until the first laser or thruster upgrade is purchased.
- After either upgrade, the player ship switches to the simple triangular white wireframe design; non-player ships and previews keep their existing drawing.

## v1.9.13
- Replaced the mining-pit flame effect with a lightweight red/yellow astronaut colour flash that alternates briefly and returns to the normal suit colour after one second.

## v1.9.12
- Added a brief burst of tiny flickering pixel flames around the astronaut when a red mining pit hit causes damage; the effect lasts about one second.

## v1.9.11
- Reduced the laser/gun upgrade and thruster upgrade costs from 3 gems to 2 gems each.

## v1.9.10
- Restricted gem-bearing ore to safe ground gaps between consecutive mining pits, so no gem asteroid spawns before the first pit or beyond the last pit.

## v1.9.9
- Animated the victory-screen black-and-white starfield with a continuous diagonal scroll, evoking classic ZX Spectrum-era arcade games.

## v1.9.8
- Moved gem-bearing yellow ore rocks into safe ground gaps between mining pits so they no longer spawn inside pit openings.
- Strengthened pit-contact detection to cover both rim impacts and falling into the opening; pit impacts remove one hull point even during normal hit-invulnerability, while an active collision shield still blocks damage.
- The astronaut is moved clear after pit contact to prevent repeated damage from a single fall.

## v1.9.7
- Changed planetary mining pits to have bright red rims and red inner highlights so they stand out clearly.
- Pit contact now removes one hull point even during ordinary hit-invulnerability; an active collision shield still blocks the damage and moves the astronaut clear of the pit.

## v1.9.6
- Simplified the victory screen to **CONGRATS YOU MADE IT** over a classic arcade starfield.
- Replaced the victory artwork and score display with **PRESS ANY KEY TO PLAY AGAIN**.

## v1.9.5
- Corrected planetary pit damage so an active collision shield protects the astronaut from black-pit impacts, just as it protects against other collisions.

## v1.9.4
- Contact with the visible black pit openings on planetary mining surfaces now costs one hull point.
- The astronaut is moved safely to the near edge after pit contact to prevent falling through the level; pit damage is not blocked by the collision shield.

## v1.9.3
- Increased the **EXTRA LIFE +1** upgrade cost to **6 gems**.
- The purchased extra-life upgrade can now be bought only once per game; after purchase, the upgrade displays **USED** and stays unavailable until a new run starts.

## v1.9.2
- Added a visible upgrade gem to the small **x3 bonus landing pad**.
- Successfully landing on that pad collects the gem and adds it to the player's unbanked gems; merely passing over it does not collect it.

## v1.9.1
- An active 2-second shield now assists a landing when the ship touches down inside a landing pad, even if its angle or touchdown speed is outside the normal safe limits.
- Shield-assisted landings award the standard 500-point base (multiplied by any bonus-pad multiplier) and show a brief message; the shield does not make rough-ground landings safe.

## v1.9.0
- Laser shots now change colour as the weapon is upgraded: **Level 1 white**, **Level 2 yellow**, **Level 3 orange**, **Level 4 red**.
- Applied the colour progression to both asteroid-flight and mining gameplay; enemy shots keep their existing colour.

## v1.8.9
- After a successful escape, players now begin the next asteroid field with at least **50% fuel**.
- If fuel is already above half a tank, it is left unchanged; the rule uses the ship's current maximum fuel capacity.

## v1.8.8
- Raised mining platforms progressively on each planet after level 1, by an additional **28px per level**.
- Restyled platforms with thicker, jagged rocky undersides and asteroid-like surface details while keeping the top landing/walking edge flat.

## v1.8.7
- Increased the **EXTRA LIFE +1** upgrade cost from **4 gems to 5 gems**.

## v1.8.6
- Increased starting fuel for a new game from **30 to 36** (**20% more**).
- Applied the same starting-fuel increase to the first-stage test shortcut.

## v1.8.5
- Made landings more forgiving: landing pads are slightly wider, and the safe landing zone extends closer to each pad edge.
- Relaxed safe touchdown limits for vertical speed, sideways speed, and ship angle a little.

## v1.8.4
- Increased starting lives from **3 to 4**, including when starting a new run or restarting.

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
