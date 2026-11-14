Download: https://github.com/reveriesyt/GTHalo/releases

GTHalo v0.0.4 pre-alpha
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
F10 - Remove AI
B - Forge Mode/Player Mode
E - Forge Menu Open
Space - Forge Menu Select
F - Forge Menu Back/Exit

Notes & Known Bugs
------------
- This pre-release only has collision in the Legion Square area of LS.
- Frame Gen is not yet supported, please disable it or your Reach character will not load correctly.

Changes in v0.0.4
-----------------
- F7: play as your GTA character inside the Reach world. Press F5 to engage, then F7 to switch from the Spartan to your current GTA character. Reach keeps running: its world, AI, effects, lighting, fog and haze stay in GTA, still hidden correctly behind GTA geometry. You get full GTA controls with no Reach arms, weapon or HUD. Reach AI see you, chase you and shoot you with real GTA bullets, and your GTA weapons hurt them. Press F7 again to return to the Spartan where you left it. Set the key with world_key in GTHalo.ini.

- Hitboxes match Reach actors: every Reach AI’s GTA hitbox is sized to its real height and width. Grunts are short, while Elites, Brutes and Hunters get taller and wider cover, so shots land where you see them.

- Collision: you bump into Reach AI and Reach vehicles, including empty and Forge-placed vehicles. A Reach NPC stops blocking you the moment it dies.

- GTA explosions count as Reach explosions:

- GTA grenades, rockets and nearby car explosions damage Reach AI and vehicles the Reach way, without an extra Reach effect.
- GTA rockets and grenade-launcher rounds hit Reach vehicles.
- Reach vehicles take about half of a GTA blast’s damage.
- 'INS' (insert) key (cops ignore you): cops still respond and come to you, fight any Covenant they run into, and never aim at you.

- No more zone switching on Legion 3x3: all nine city cells load at startup as one zone. No hitches or reloads as you cross cell lines.

- Performance work: lighter AI diagnostics, smarter projectile checks, staggered bridge work and less render state churn.

Known issues:

In F7, GTA’s HUD draws under the Reach world.
While you’re in F7, the Spartan stays where you left it and Reach AI can still shoot it.
Reach’s hit effect plays at the actor’s centre, not the exact hit point.
AI still don’t path across cell borders.
Expect bugs and crashes.

Updating from v0.0.21: extract this release, then copy GTHalo.cfg from your old folder into the new one (or pick the same folders again) and run GTHalo.exe. Your existing GTHalo folder is reused; only the changed tags are copied.

See README.txt for requirements and setup.

Updating from an earlier version: copy GTHalo.cfg from the old folder into this one (or pick
the same folders again). Your existing GTHalo folder is reused; only changed tags are copied.
An existing GTHalo.ini in the GTA folder keeps your settings; fixed_map is set to 1.

Uninstall: delete GTHalo_GTA.asi and GTHalo.ini from the GTA folder, then delete the GTHalo
folder and this folder.

