CS:GO deathmatch plugin
=======================

Description
-----------

This plugin enables deathmatch style gameplay. It has the following components:
* Spawn Point Editor - Allows admins to add or modify spawn points for each map.
* Objectives Removal - Disables bomb sites, and removes C4 and hostages.
* Respawning - Respawns players when they die.
* Spawn Protection - Protects spawning players from enemy fire for a limited period of time.
* Gun Menu - Allows players to select primary and or secondary weapons.
* Weapon Removal - Removes weapons that are on the ground or dropped.
* Replenish Ammo - Gives players ammo to prevent them running out.

There are two key differences between this and other DM plugins:
1) Everything required for DM is packaged into a single plugin for ease of use.
2) By default, this DM plugin uses line of sight spawning, to prevent players from spawning directly infront of or behind enemies, giving both players a better chance, and significantly reducing spawn killing. Distance based spawning is also available.

Description
-----------
This plugin enables deathmatch style gameplay. It has the following components:
Spawn Point Editor - Allows admins to add or modify spawn points for each map.
Objectives Removal - Disables bomb sites, and removes C4 and hostages.
Respawning - Respawns players when they die.
Spawn Protection - Protects spawning players from enemy fire for a limited period of time.
Gun Menu - Allows players to select primary and or secondary weapons.
Weapon Removal - Removes weapons that are on the ground or dropped.
Replenish Ammo - Gives players ammo to prevent them running out.
There are two key differences between this and other DM plugins:
1) Everything required for DM is packaged into a single plugin for ease of use.
2) By default, this DM plugin uses line of sight spawning, to prevent players from spawning directly infront of or behind enemies, giving both players a better chance, and significantly reducing
spawn killing. Distance based spawning is also available.

Instructions
------------
Once installed, use dm_spawn_menu to add spawn points for each map.
Note: You must hit "Save Configuration" otherwise your spawn points will not be saved.

If using line of sight and or distance spawning, dm_stats can be used to view success and failure percentages for spawn point searches. Low success rates are a good indication that your settings need adjusting (dm_los_attempts and or dm_spawn_distance). When changing settings, be sure to reset the stats (dm_reset_stats) to properly see what effect the changes have.

A weapon limit of "-1" in the configuration file means unlimited.

Admin Commands
--------------
* dm_spawn_menu - Opens the spawn point menu.
* dm_respawn_all - Respawns all dead players.
* dm_stats - Displays spawn statistics.
* dm_reset_stats - Resets spawn statistics.

CVars
--------------------------------------------------
* na_dm_version - Deathmatch version.
* dm_enabled - (Default: 1) Enable deathmatch.
* dm_free_for_all - (Default: 0) Free for all mode.
* dm_remove_objectives - (Default: 1) Remove objectives (disables bomb sites, and removes c4 and hostages).
* dm_respawning - (Default: 1) Enable respawning.
* dm_respawn_time - (Default: 2.0) Respawn time.
* dm_gun_menu_mode - (Default: 1) Gun menu mode. 1) Enabled. 2) Disabled. 3) Random weapons every round.
* dm_los_spawning - (Default: 1) Enable line of sight spawning. If enabled, players will be spawned at a point where they cannot see enemies, and enemies cannot see them.
* dm_los_attempts - (Default: 10) Maximum number of attempts to find a suitable line of sight spawn point.
* dm_spawn_distance - (Default 0.0) Minimum distance from enemies at which a player can spawn.
* dm_sp_time - (Default: 1.0) Spawn protection time.
* dm_remove_weapons - (Default: 1) Remove ground weapons.
* dm_replenish_ammo - (Default: 1) Unlimited player ammo.
* dm_hp_start - (Default: 100) Spawn HP.
* dm_hp_max - (Default: 100) Maximum HP.
* dm_hp_kill - (Default: 5) HP per kill.
* dm_hp_hs - (Default: 10) HP per headshot kill.
* dm_hp_knife - (Default: 50) HP per knife kill.
* dm_hp_messages - (Default: 1) Display HP messages.
* dm_nade_messages - (Default: 1) Display grenade messages.
* dm_armour - (Default: 1) Give players armour.
* dm_zeus - (Default: 0) Give players a taser.
* dm_nades_incendiary - (Default: 0) Number of incendiary grenades to give each player.
* dm_nades_decoy - (Default: 0) Number of decoy grenades to give each player.
* dm_nades_flashbang - (Default: 0) Number of flashbang grenades to give each player.
* dm_nades_he - (Default: 0) Number of HE grenades to give each player.
* dm_nades_smoke - (Default: 0) Number of smoke grenades to give each player.

