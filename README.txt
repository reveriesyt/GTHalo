GTHalo v0.0.1 pre-alpha
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

Note: This pre-release only has collision in the Legion Square area of LS.

Uninstall: delete GTHalo_GTA.asi and GTHalo.ini from the GTA folder, then delete the GTHalo
folder and this folder.
