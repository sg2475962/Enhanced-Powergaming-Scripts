# Changelog

## Version 5.3

September XX, 2021

### Changed 

- BG:EE, BGII: EE, and EET
  - Corrected harmless warning if IWDIfication is installed.
  - Updated Skald battlesong to not sing if another action is in progress
  - Spell Revisions - Updated Luck to cast on all party members

## Version 5.2

September 12, 2021

### Changed 

- All Games
  - Added Russian translation courtesy of Ulpian
- BGII: EE and EET
  - Updated Spell Revisions to cast Free Action and Neutralize Poison during Pre-Buffing

## Version 5.1

September 9, 2021

### Changed 

- BGII: EE and EET
  - Corrected issue with aid spell for spell revisions

## Version 5.0.1

September 9, 2021

### Changed 

- Corrected mistake I made during upload which impacted Project Infinity's use of this mod.

## Version 5.0

September 8, 2021

### Changed 

- All Games
  - Added Detectable Spells
  - Optimized Breach and combat dispelling for non-SCS games
  - Updated Purge Invisibility and Detect Invisibility to NOT cast if enemy has Sanctuary active
  - Added Cleric Chant to pre-buffing
  - Added Wizard Protection from Electricity
- BGII: EE and EET
  - Fixed issue with Spell Revisions Cleric Break Enchantment
  - Updated SR Aid to cast on all party members
- IWD: EE
  - Added Enhanced AI Scripts for IWD: EE

## Version 4.3

July 13, 2021

### Changed 

- All Games
  - Added Shaman class support to the mo-core scripts
- BGII: EE and EET
  - Added use of the following items: Cloak of the Dark Moon and Shield of Fyrus Khal

## Version 4.2

July 7, 2021

### Changed 

- All Games
  - Updated Improved Haste to also cast for Clerics and Druids
  - Updated Protection from Magic Energy to be cast on all party members
  - Added Spirit Armor, Cleric Protection from Fire, and Wizard Protection from Fire, Cold, and Acid to non-Spell Revisions scripts
  - Added Healing Touch into Spell Revisions scripts
  - Girdle of Fortitude will now cast when in the inventory of the player instead of requiring to be equipped

## Version 4.1

July 2, 2021

### Changed 

- BGII: EE and EET
  - Updated Simulacrums to assign enemy scripts if cast by an enemy

## Version 4.0

July 2, 2021

### Changed 

- All Games
  - Added Detect Illusions.
  - Improved Haste will only be cast if the character has fighter, thief, or bard levels. This prevents a pure class mage casting IH on themselves since there is little benefit.
  - Infinity Auto Packager support
- BG: EE
  - Added Enhanced AI Scripts for BG: EE
  - Supports IWD Spells (IWDIfication or SCS version) and SCS mods
- BGII: EE and EET
  - Added Hardiness to combat castings.
  - Add AI Script Component for Simulacrum.
  - Resolved a bug that could cause an issue when restoring original items/spells from SR and IR.
  - Resolved a bug with Khelben's Warding Whip spell tracking.

## Version 3.1

June 24, 2021

### Changed 

- Updated Resist Fear and Belt of Minor Invulnerability to NOT be cast during pre-buffing in Athkatla if Cowled Wizards will appear
- Added Army of One (DSotSC Spell) to pre-buffing and situational casting
- Updated issue with Negative Plane Protection not being tracked correctly causing it to be continually cast on a single character
- Added metadata and labels to better work with Project Infinity

## Version 3.0

June 19, 2021

### Changed 

- Various bug fixes and optimizations
- Items that will be used by the scripts were added: Headband of the Devout, Girdle of Fortitude, Ring of Spell Turning, Cloak of the Stars, Cowl of the Stars, and the Belt of Minor Invulnerability
- Additional spells and abilities added

## Version 3.0_beta

May 24, 2021

### Changed 

- Dynamically creates scripts on installation based on mods installed allowing for over 1.5 MILLION different scripts that can be created!
- Support for the following mods: Spell Revisions, SCS, DSotSC, Song & Silence, IWD Spells, Tome & Blood, and Faith & Powers (only compatible with F&P sphere system).
- Multiple new spells for vanilla and mods added.
- Updated spell tracking for existing spells to optimize existing scripts.

## Version 2.4

April 29, 2021

### Changed

- Updated spell tracking for both Minor Globe of Invulnerability and Globe of Invulnerability so they are now tracked separately. This allows for better spell determination on what can be cast on or against a player.
- Added Black Blade of Disaster for pre-buffing and in-combat casting for non-SR versions of the scripts.
- Added BETA for enhanced ai scripts for summoned celestials.

## Version 2.3

April 7, 2021

### Changed

- Combined Cleric/Ranger and FMC into a single script called Divine.
- Changed Inquisitor script to Paladin script and added compatibility for all Paladin kits.
- Removed Initialize Base Components Component and wrapped it into the main component for simpler install.

## Version 2.2

April 6, 2021

### Changed

- Scripts no longer require SCS as a prerequisite

## Version 2.1

April 5, 2021

### Changed

- Updated to use G3 mod packaging that now includes:
  - Linux version
  - macOS version
  - .exe for Windows version

## Version 2.0

April 5, 2021

### Changed

- Initial release for G3
