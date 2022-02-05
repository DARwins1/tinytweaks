This README goes over all the changes that this mod makes. Remember that all these changes are cosmetic, and have no effect on actual gameplay (besides maybe making a weapon look cooler). The changes are categorized by which file(s) they apply to. The first section lists changes in weapons.json, the second section in research.json, and finally the changes to .pie files in the components folder.

=========
weapons.json changes (located in stats):

Rocket-MRL (Mini-Rocket Array): Changed the explosion effect and increased the visual size of the explosion.
"hitGfx": "FXMNExp.PIE",
"missGfx": "FXMNExp.PIE",
"effectSize": 50

Missile-MdArt (Seraph Missile Array): Changed the explosion effect and reduced the visual size of the explosion.
"hitGfx": "FXMNExp.PIE",
"missGfx": "FXMNExp.PIE",
"effectSize": 75

Missile-HvyArt (Archangel Missile Array): Changed the explosion effect.
"hitGfx": "FXMNExp.PIE",
"missGfx": "FXMNExp.PIE"

RailGun1Mk1 (Needle Gun): Changed the hit sound effect to a small explosion sound, rather than the rail gun firing sound.
"explosionWav": "smlexpl.ogg"

Cyb-Wpn-Rail1 (Needle Gunner Cyborg): Changed the hit sound effect to a small explosion sound, rather than the rail gun firing sound.
"explosionWav": "smlexpl.ogg"

Cyb-Hvywpn-RailGunner (Super Rail-Gunner): Changed the hit sound effect to a large explosion sound, rather than the rail gun firing sound.
"explosionWav": "lrgexpl.ogg"

Cyb-Hvywpn-Mcannon (Super Heavy-Gunner): Increased the visual size of the explosion to match the Medium Cannon.
"effectSize": 60

Cyb-Hvywpn-HPV (Super HVC Cyborg): Increased the visual size of the explosion to match the Hyper Velocity Cannon, and changed projectile model.
"effectSize": 50,
"flightGfx": "fxtracerh.pie"

Cyb-Hvywpn-Acannon (Super Auto-Cannon Cyborg): Increased the visual size of the explosion to match the Assault Cannon.
"effectSize": 50

Cannon4AUTOMk1 (Hyper Velocity Cannon): Changed projectile model.
"flightGfx": "fxtracerh.pie"

Cannon4AUTO-VTOL (VTOL Hyper Velocity Cannon): Changed projectile model.
"flightGfx": "fxtracerh.pie"

Bomb3-VTOL-LtINC (VTOL Phosphor Bomb Bay): Changed the explosion effect.
"hitGfx": "FXSFlms.PIE",
"missGfx": "FXSFlms.PIE"

Bomb4-VTOL-HvyINC (VTOL Thermite Bomb Bay): Changed the explosion effect.
"hitGfx": "FXSFlms.PIE",
"missGfx": "FXSFlms.PIE"

Bomb5-VTOL-Plasmite (VTOL Plasmite Bomb Bay): Reduced the visual size of the explosion a bit.
"effectSize": 300

Rocket-LtA-T (Lancer): Changed the explosion effect and the muzzle effect.
"hitGfx": "FXMPExp.PIE",
"missGfx": "FXMPExp.PIE",
"muzzleGfx": "FXLRocPd.PIE"

Rocket-VTOL-LtA-T (VTOL Lancer): Changed the explosion effect and the muzzle effect.
"hitGfx": "FXMPExp.PIE",
"missGfx": "FXMPExp.PIE",
"muzzleGfx": "FXLRocPd.PIE"

CyborgRocket (Cyborg Lancer): Changed the explosion effect and increased the visual explosion size to match the Lancer.
"hitGfx": "FXMPExp.PIE",
"missGfx": "FXMPExp.PIE",
"effectSize": 50

Rocket-HvyA-T (Tank Killer): Changed the explosion effect and the muzzle effect, and increased the visual explosion size.
"hitGfx": "FXMPExp.PIE",
"missGfx": "FXMPExp.PIE",
"muzzleGfx": "FXLRocPd.PIE",
"effectSize": 100

Rocket-VTOL-HvyA-T (VTOL Tank Killer): Changed the explosion effect and the muzzle effect, and increased the visual explosion size.
"hitGfx": "FXMPExp.PIE",
"missGfx": "FXMPExp.PIE",
"muzzleGfx": "FXLRocPd.PIE",
"effectSize": 125

Cyb-Hvywpn-TK (Super Tank-Killer Cyborg): Changed the explosion effect and increased the visual explosion size to match the Tank Killer.
"hitGfx": "FXMPExp.PIE",
"missGfx": "FXMPExp.PIE",
"effectSize": 100

Missile-A-T (Scourge Missile): Changed the explosion effect and the muzzle effect.
"hitGfx": "FXMExp.PIE",
"missGfx": "FXMExp.PIE",
"muzzleGfx": "FXLRocPd.PIE"

Missile-VTOL-AT (VTOL Scourge Missile): Changed the explosion effect and the muzzle effect.
"hitGfx": "FXMExp.PIE",
"missGfx": "FXMExp.PIE",
"muzzleGfx": "FXLRocPd.PIE"

Cyb-Wpn-Atmiss (Scourge Cyborg): Increased the visual explosion size to match the Scourge Missile.
"effectSize": 75

Cyb-Hvywpn-A-T (Super Scourge Cyborg): Increased the visual explosion size to match the Scourge Missile.
"effectSize": 75

RocketSuper (Heavy Rocket Bastion): Increased the visual explosion size and effect, and changed the muzzle effect.
"hitGfx": "FXMExp.PIE",
"missGfx": "FXMExp.PIE",
"effectSize": 150,
"muzzleGfx": "FXLRocPd.PIE"

BJeepMG (Scavenger Jeep MG): Use the same model and muzzle effects as the scav mounted MG.
"model": "bbaamuzzle.pie",
"mountModel": "bbaaturret.pie",
"muzzleGfx": "FXMgnVic.PIE"

BabaPitRocket (Scavenger Mini-Rocket Pod): Changed the explosion sound to match the Mini-Rocket Pod.
"explosionWav": "smlexpl.ogg"

BabaPitRocketAT (Scavenger Lancer): Changed the explosion effect and size, muzzle and projectile effects to more closely match the other launchers.
"hitGfx": "FXMPExp.PIE",
"missGfx": "FXMPExp.PIE",
"effectSize": 50,
"muzzleGfx": "FXLRocPd.PIE",
"flightGfx": "FXMPLME.PIE"

BabaRocket (Scavenger Jeep/Buggy Rocket Array): Changed the explosion effect and size.
"hitGfx": "FXMPExp.PIE",
"missGfx": "FXMPExp.PIE",
"effectSize": 30

=========
research.json changes (located in stats):

R-Defense-PlasmaCannon (Plasma Cannon Emplacement): Changed its research image to show the actual Plasma Cannon Emplacement instead of the Pulse Laser one.
"statID": "Emplacement-PlasmaCannon"

R-Wpn-Energy-Accuracy01 (Improved Laser Focusing): Changed its research image to show the Flashlight instead of the Pulse Laser.
"statID": "Laser3BEAMMk1"

R-Wpn-Energy-Damage01 (Hi-Energy Laser Emitter): Changed its research image to show the Flashlight instead of the Pulse Laser.
"statID": "Laser3BEAMMk1"

R-Wpn-Energy-Damage02 (Hi-Energy Laser Emitter Mk2): Changed its research image to show the Flashlight instead of the Pulse Laser.
"statID": "Laser3BEAMMk1"

R-Wpn-Energy-Damage03 (Hi-Energy Laser Emitter Mk3): Changed its research image to show the Flashlight instead of the Pulse Laser.
"statID": "Laser3BEAMMk1"

R-Wpn-Energy-ROF01 (Thermopole Energizer): Changed its research image to show the Flashlight instead of the Pulse Laser.
"statID": "Laser3BEAMMk1"

R-Wpn-Energy-ROF02 (Thermopole Energizer Mk2): Changed its research image to show the Flashlight instead of the Pulse Laser.
"statID": "Laser3BEAMMk1"

R-Wpn-Energy-ROF03 (Thermopole Energizer Mk3): Changed its research image to show the Flashlight instead of the Pulse Laser.
"statID": "Laser3BEAMMk1"

=========
.pie model changes (located in components/bodies and components/weapons):

gnmrckta.pie (Lancer / VTOL Lancer): Replaced the singular connector with one for each barrel.
CONNECTORS 2
	-18 -21 11
	18 -21 11

gnmrcktb.pie (Tank Killer / VTOL Tank Killer): Replaced the singular connector with one for each barrel.
CONNECTORS 2
	-22 -22 14
	22 -22 14

gnmmslat.pie (Scourge Missile / VTOL Scourge Missile): Replaced the singular connector with one for each barrel.
CONNECTORS 2
	-21 -22 15
	21 -22 15

gnwpfrkt.pie (Heavy Rocket Bastion): Replaced the singular connector with one for each barrel.
CONNECTORS 4
	-18 -43 62
	20 -43 62
	-18 -43 22
	20 -43 22

gnwpfmsl.pie (Missile Fortress): Replaced the singular connector with one for each barrel.
CONNECTORS 4
	-18 -42 63
	20 -42 63
	-18 -42 25
	20 -42 25

gnhaalas.pie (Stormbringer AA): Replaced the singular connector with one for each barrel.
CONNECTORS 2
	-7 -42 11
	7 -42 11

exjeep.pie (Scavenger Jeep): Added a connector for a mounted turret and removed the weird floating gun barrel.
CONNECTORS 1
	-0 15 5
>Removed a bunch of polygons and points, too much to list here.

scavchop.pie (Scavenger MG Helicopter Body): Made the underbelly turret actually appear.
CONNECTORS 6
	0 0 0
	0 0 0
	0 0 0
	0 0 0
	0 0 0
	-0 -20 12

hvychop.pie (Scavenger Rocket Helicopter Body): Made the underbelly turret actually appear.
CONNECTORS 6
	0 0 0
	0 0 0
	0 0 0
	0 0 0
	0 0 0
	0 -2 14
