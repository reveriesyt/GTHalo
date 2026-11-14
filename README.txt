Download: https://github.com/reveriesyt/GTHalo/releases

GTHalo v0.0.3 pre-alpha
=======================
Halo: Reach player simulation inside GTA V Enhanced's Los Santos. Forge AI build with the
Legion Square map, AI squads, vehicles and capital ships. Pre-alpha: expect bugs and crashes.

Requirements
------------
- Halo Reach Editing Kit (HREK, Steam), current build (reach_tag_test.exe).
- Grand Theft Auto V Enhanced, Story Mode, BattlEye off.
- ScriptHookV for GTA V Enhanced, plus an ASI loader (dinput8.dll), in the GTA folder.
- About 45 GB of free disk space for GTHalo's private copy of the tag test.

How to play
-----------
1. Run GTHalo.exe.
2. First run only: pick your HREK folder, your GTA V Enhanced folder, and where to create
   the GTHalo folder. These are saved in GTHalo.cfg and asked again only if a folder
   can no longer be found.
3. First run only: GTHalo copies your tag test into <chosen>\GTHalo\ReachTagTest and applies
   its tag edits there. This takes a while. Your HREK install is never modified.
4. GTHalo installs GTHalo_GTA.asi and GTHalo.ini into your GTA folder. Close GTA first if
   asked. Previous files are backed up to <chosen>\GTHalo\backup.
5. Choose whether the UNSC Marines fight GTA NPCs this session (they always stay on your side).
6. The launcher starts the Reach tag test. Then start GTA V Enhanced Story Mode, focus GTA
   and press F5 when the launcher says so.

Controls
------------
F5 - Enable/disable Reach in GTA
F8 - Enable/disable HUD
F9 - Enable/disable Reach AI processing (handy for setting up battles)
B - Forge Mode/Player Mode
E - Forge Menu Open
Space - Forge Menu Select
F - Forge Menu Back/Exit

Notes & Known Bugs
------------
- This pre-release only has collision in the Legion Square area of LS.
- Frame Gen is not yet supported, please disable it or your Reach character will not load correctly.

Changes in v0.0.3
-----------------
- Lighting now matches GTA in every weather: Reach AI, vehicles and Forge objects take GTA's own sun, time of day and weather, and fade into GTA's fog and haze using GTA's own depth. Every GTA weather is handled: extra sunny, clear, neutral, clouds, overcast, clearing, smog, foggy, rain, thunder, snow, light snow, blizzard, Christmas and the Halloween weathers, plus the transitions between them. Rain darkens and softens them, fog and thunder swallow them at distance, and clear skies keep them crisp, just like the GTA world around them. They sit in the scene like GTA's own objects instead of standing out. Also fixed the bright-white NPC bug; lighting refreshes as time and weather change.
- Bigger playable area: Reach collision, AI navigation and AI squads now cover a 3x3 grid of Los Santos city cells around Legion, streamed in and out as you move.
- New AI navigation: generated navmesh and cover points across all cells. AI advance on their enemies and take cover instead of standing still, and no longer get stuck on the roads around the plaza.
- AI vehicles: ground vehicles drive and fight. Phantoms, Pelicans, Falcons and Banshees fly with Reach's own flight AI, avoiding buildings and the ground. Banshees make strafing runs and drop bombs.
- GTA vehicles hit Reach units: GTA cars push and damage Reach AI, vehicles and the player. Reach vehicles get invisible GTA stand-ins so traffic collides with them.
- Explosions: Reach explosion visuals are back and are hidden correctly behind GTA geometry. GTA's own explosion is now invisible and silent but keeps its physics and damage.
- Capital ships no longer break AI: placing the Long Night of Solace (or any capital ship) used to stop every AI from pathing a little later. Fixed.
- Pillar of Autumn: new Forge → Capital Ships entry, at lore scale (1,171 m).
- Weapons: AI weapon ranges now apply as intended. Phantom chin guns and Wraith mortars are tuned, and aircraft crews spot targets from further away.
- Keys: F10 clears all Forge AI and the vehicles they crewed. Reach's Start menu moved to F11. F8 toggles the Reach HUD.

Known issues: saved Forge map variants from earlier versions may place the wrong objects. AI do not path across cell borders yet. Expect bugs and crashes.

Updating from v0.0.21: extract this release, then copy GTHalo.cfg from your old folder into the new one (or pick the same folders again) and run GTHalo.exe. Your existing GTHalo folder is reused; only the changed tags are copied.

See README.txt for requirements and setup.

Updating from an earlier version: copy GTHalo.cfg from the old folder into this one (or pick
the same folders again). Your existing GTHalo folder is reused; only changed tags are copied.
An existing GTHalo.ini in the GTA folder keeps your settings; fixed_map is set to 1.

Uninstall: delete GTHalo_GTA.asi and GTHalo.ini from the GTA folder, then delete the GTHalo
folder and this folder.

