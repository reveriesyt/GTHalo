Download: https://github.com/reveriesyt/GTHalo/releases

GTHalo v0.0.21 pre-alpha
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

Changes in v0.0.2
-----------------
* Complete lighting and occlusion overhaul, re-tooled to use GTAs own lighting and depth buffer, with a fix for the white border "photoshop effect". GTA Time of Day and Weather effects also now apply to Reach AI, Objects, Scenery.

* Spawnable AI Noble Team, directly carried over from campaign.
* Some additional AI.
* Placeable Long Night of Solace Supercarrier scenery object, to lore scale (~28.96km in length).
* Pilotable Pelican, Phantom, Space Banshee.
* Reconfigured forge menu for easier navigation (AI, AI vehicles & ships have their own categories now, with fixed naming)

Updating from an earlier version: copy GTHalo.cfg from the old folder into this one (or pick
the same folders again). Your existing GTHalo folder is reused; only changed tags are copied.
An existing GTHalo.ini in the GTA folder keeps your settings; fixed_map is set to 1.

Uninstall: delete GTHalo_GTA.asi and GTHalo.ini from the GTA folder, then delete the GTHalo
folder and this folder.

