# Licensed To Kill (LTK)

Licensed To Kill (LTK) Action Quake2 bot by Connor Caple aka "RiEvEr" between 1999-2000 and later extended by Paril, Fredrick Andreas aka "Fred", and Connor Caple aka "RiEvEr" circa 2005-2007.

Based on the ACE bot.

## Release Chronology (reconstructed)

Version         | Date
--------------- | -----
v0.01 			| ?
v0.02 			| ?
v0.1 			| ?
v0.11 			| ?
v0.12 			| ?
v0.13 			| ?
v0.14 			| 19991002 (?)
v0.15 			| ?
v0.16 			| 19991016
v1.00 			| ?
v1.01 			| ?
v1.10 			| 19991129
v1.11 			| 20000125 (?)
v1.12 			| 20000217 (?)
v1.20 			| 20000224 (?)
v1.21 			| 20000227
v1.22 			| 20000229
v1.22 Linux 	| 20000306
v1.22 Source 	| ?
v1.22 CFG 		| ?
v0.5 			| ?
v0.5.1 			| 20050423 (?)
v1.23 			| 20060209
v1.24 			| 20060216 (?)
v1.25 			| 20060409
v2.0 			| 20070402

## Homepages

* [planetquake.com/maxtron/ltk](https://web.archive.org/web/20000816190517/http://www.planetquake.com/maxtron/ltk/) (archived)
	* https://web.archive.org/web/*/planetquake.com/maxtron/ltk*
* planetquake.com/ltk (not archived)
* [pondscum.co.uk/ltk](https://web.archive.org/web/20001012230127fw/http://www.pondscum.co.uk/index.html) (archived)
	* https://web.archive.org/web/*/http://www.pondscum.co.uk/*
* [botgod.org.uk](https://web.archive.org/web/20010723023311/http://www.botgod.org.uk/) (archived)
	* https://web.archive.org/web/*/http://www.botgod.org.uk/*

Extensions

* [actiongames.co.uk/tnn/ltk](https://web.archive.org/web/20020720113316/http://www.actiongames.co.uk:80/tnn/ltk/index.shtml) (archived)
	* https://web.archive.org/web/*/actiongames.co.uk/tnn/ltk*
* [franva.org](https://web.archive.org/web/20080517020422/http://www.franva.org/news.php)
* [moddb.com/mods/action-quake-2-bot](https://www.moddb.com/mods/action-quake-2-bot) (current)


## v0.01 Alpha

Probably released as `LTK001Alpha.zip`.

Mentioned in the changelog:

```text
0.01alpha	* Initial release of AQ2 source / ACEBot combo
```

## v0.02 Alpha

Released as `LTK002Alpha.zip`.

Mentioned in the changelog:

```text
0.02alpha	+ Individual weapon checks to allow switching to multiple weapons
			+ Working on firing through "windows" problem (not solved)
			- Changed route finding functions to detect windows
			* Better weapon usage justifies a second release.
```

## v0.1

Probably released as `LTK01Beta.zip`.

Mentioned in the changelog:

```text
0.10 beta	+ "ltk_skill" cvar added. Takes value from 0 to 10 (default 10) to modify aiming
			- Modified LTK aiming to take skill into account
			- Changed pickup code to look for dual pistols
			+ Weapon state is now checked before trying to fire so that reloads can happen
			+ Tactics changed to allow only forward movement if using knife
```

## v0.11

Probably released as `LTK011Beta.zip`.

Mentioned in the changelog:

```text
0.11 beta	- Changed all bprints to safe_bprints to prevent overflows
			! Updated all code to use the 1.52 Action Quake source
			+ Added new node storage structure with dynamic linking
			# Nodes are now created after changing to a new level at timelimit/fraglimit
			+ DOOR nodes are automatically created for rotating doors
			+ New debug command "shownode NN" added
			- Bots can now handle "rotating" doors correctly
			- Increased time of random door opening attempts until all the door code is in
			- Changed the ledge checking code to discourage leaping off buildings
			- Removed the main cause of the centipede effect for teamplay
			- altered MP5 code to check for reload correctly
			- Node tables are now *.LTK and are saved in "./terrain/" to match CGF.
			+ Simple weapon choice code included for longer range shots
```

## v0.12

Probably released as `LTK012Beta.zip`.

Mentioned in the changelog:

```text
0.12 beta	# Found the MP5 reload problem
			- Migrated the new MP5 code across all the special weapons to prevent reload problems
			+ Bots will now automatically "balance" teams if you don't specify one.
			+ Bots will now look for ammo if not at max clips.
			+ Ammo and Weapon nodes added to node tables
			+ Added LTK version information to compiled code. Use "ltkversion" to access.
			~ temporary change installed for centipede effect (bot delay time)
```

## v0.13

Released as `LTK013Beta.zip`.

Mentioned in the changelog:

```text
0.13 beta	- Bots now only see things in front of them.
			- Changed enemy selection to fight closest enemy
			# HC reloads fixed (ammo storage was different)
			+ All new path and optimisation code in place but not used yet!
			+ Bots react when shot in the back if not already under attack.
			- Bots do not break off combat if you're too close
```

## v0.14

Released as `LTK014Beta.zip`.

Mentioned in the changelog:

```text
0.14 beta	- New path and route system is now in place and working
			- Extra checks added to node creation code to make sure LOS exists
			- ** Node file version number updated to 2 - old files won't be used **
			+ More range breaks added for weapon selection
			+ LOS checks added for "hurt by enemy"
			- Items now just as likely to be selected as a long range goal
			+ Allowed bots to create their own nodes and links.
			+ pathList initialised on spawn to forestall errors.
			+ Bot "speech" added at spawn and respawn.
			- Bots now remember who killed tham after a respawn.
			# Node linking code altered to avoid more bad links
			+ Real random names added for bots (made up "on the fly").
			+ 'Sindarin' nameset added to standard name set.
			- Modified combat code to stop crouching etc., beyond a certain range.
```

Mentioned on BotEpidemic:

> LTK v0.14 Beta | October 02, 1999 - 04:49 BST | Ze0
>
> RiEvEr has released, over at the Licensed To Kill site, v0.14 Beta of the bot. Here is what's new:
>
>> - New path and route system is now in place and working
>> ** Node file version number updated to 2 - old files won't be used **
>> + More range breaks added for weapon selection
>> + LOS checks added for "hurt by enemy"
>> + Allowed bots to create their own nodes and links.
>> + Bot "speech" added at spawn and respawn.
>> - Bots now remember who killed tham after a respawn.
>> + Real random names added for bots (made up "on the fly").
>> + 'Sindarin' nameset added to standard name set.- Modified combat code to stop crouching etc., beyond a certain range.
>
> Pick up LTK v0.14 Beta here.

-- [http://www.botepidemic.com/](https://web.archive.org/web/19991003125855/http://www.botepidemic.com/)

Links:

* http://www.planetquake.com/maxtron/ltk/
* http://www.planetquake.com/dl/dl.asp?maxtron/LTK014Beta.zip

## v0.15

Released as `LTK015Beta.zip`.

Mentioned in the changelog:

```text
0.15 beta	- Re-enabled mode and damage prints.
			- Re-enabled user bot naming on spawn
			+ Bots can now init and load the route file if it exists.
			+ Special initial movement handling for TeamPlay games. (Anti-Centipede code)
			+ Random weapon and equipment choices for Teamplay now working.
			# Fixed Teamplay spawning bugs so teams now balance.
			# Stopped bots following or targetting spectators in Teamplay.
			- Bots now check if firing will harm a teammate.
			# Bots now disconnect correctly when removed.
```

Mentioned on BotEpidemic:

> New LTK Beta | October 11, 1999 - 07:26 BST | Cube
>
> RiEvEr has released version 0.15 of his Licensed to Kill bot, for Action Quake II. Apparently the main improvements are to the Teamplay areas of the bots and the worst "Centipede problem" should be gone now. You'll need to re-do all of your route-files though, as RiEvEr has changed the format (and old routes will not work anymore).

-- [http://www.botepidemic.com/](https://web.archive.org/web/19991012061238/http://www.botepidemic.com/)

Links:

* http://www.planetquake.com/maxtron/ltk/
* http://www.planetquake.com/dl/dl.asp?maxtron/LTK015Beta.zip

## v0.16

Released as `LTK016Beta.zip`.

Mentioned in the changelog:

```text
0.16 beta	# Fixed respawning in deathmatch games. (sorry!)
			- updated internal version number (forgot last time!)
			+ new CVAR "ltk_chat [0/1]" on by default, set to 0 to disable bot chat.
			+ New config file added to set bot names, skins, teams.
			+ Config files can now be set for individual levels.
			- Stopped bot route creation - too many bad links from them!
			- Changed jumping code to help them get over desks, ledges, etc.
			+ Weapon and Equipment selection added to config file for Teamplay.
			- Modified Wander code again (needs a complete rewrite!)
```

Contents of `LTK016Beta.zip`:

```text
-rw-rw-r--  0 0      0         456 16 Oct  1999 Quake2/action/bots/botdata.cfg
-rw-rw-r--  0 0      0         494 16 Oct  1999 Quake2/action/bots/asylum.cfg
-r--r--r--  0 0      0        8625 16 Oct  1999 Quake2/action/LTKBots.txt
-rw-rw-r--  0 0      0      385024 16 Oct  1999 Quake2/action/gamex86.dll
-r--r--r--  0 0      0        4492 16 Oct  1999 Quake2/action/history.txt
-rw-rw-r--  0 0      0        3950 12 Sep  1999 Quake2/action/acebot.txt
-rw-rw-r--  0 0      0      136146 16 Oct  1999 Quake2/action/terrain/asylum.ltk
```

Readme header:

```text
Licensed To Kill for Action Quake II
====================================

** Current version: 0.16 beta ** ( 16th October 1999)
[Changes to this document since 0.13 beta are marked with # ]
```

## v1.00

Released as `LTK100.zip`.

Mentioned in the changelog:

```text
1.00 rel.	# Fixed ladder node creation
			+ "ltk_showpath [0/1]" CVAR will display bot path selection information.
			+ New ladder detection function.
			- Distance checks added for ladder climbing.
			+ Special handling to reduce velocity at ladder mount point.
			+ Ledge handling code allows jumping up small obstacles.
			# Air Walking code found and removed.
			- Ladder climbing code refined and working.
			- Item selection weighting altered.
			# Route files with less than 100 nodes will not be saved. This is to prevent good
				route files being overwritten when the game glitches at load-time and quits.
			! ** Updated route file version to 3, old routes will not work! **
```

Mentioned on the LTK homepage:

> 29th November 1999 - LTK Version 1.10 with OpenGL FOG Support
>
> This release has William’s FOG code included. Full instructions are over on the CGF site. You will also find the current LTK source code included with the archive. I have a lot to do over the next couple of months on a commercial project so I may not be able to do a lot more to LTK until after that - this way you can get someone else to make any minor changes you may feel are necessary.
>
> I hope everyone still plays AQ2 after Q3A hits the streets, it would be a shame if everyone just moved on when the Q2 engine obviously still has a lot of life in it. Have fun with this one guys and don’t be surprised if I seem a little busy until  February!

-- [http://www.planetquake.com/maxtron/ltk/index.html](https://web.archive.org/web/20000823195935/http://www.planetquake.com/maxtron/ltk/index.html)

## v1.01

Released as `LTK101.zip`.

Mentioned in the changelog:

```text
1.01		+ Light Level is now used when looking for enemies. The light level is
				determined by the engine, not my code! Some weird values at times!
```

Mentioned on the LTK homepage:

> 25th Jan 2000 - LTK Version 1.11
>
> I’ve taken an hour out from my other work to put a “fix” in for the 180-degree-spin-attack that everyone complained about. I’m not sure that the new behaviour is that realistic since I have attempted to get the bots to turn and look for whoever shot them and this might result in them becoming easy targets. Drop into the mailing list and tell me what you think.

-- [http://www.planetquake.com/maxtron/ltk/index.html](https://web.archive.org/web/20000823195935/http://www.planetquake.com/maxtron/ltk/index.html)

## v1.10

Released as `LTK110.zip`.

Mentioned in the changelog:

```text
1.10		+ Added William's (CGF) fog support for OpenGL 3D cards.
			- Bot vision restricted by fog.
			# Code added to prevent anyone creating bad links upwards!
			- Altered maximum "drop" distance to 180 QU.
			- Increased maximum nodes in route file to 1200
```

Listed on the LTK downloads page:

> Licensed To Kill Version 1.10 Release ( 29th Nov 99)
>
> Includes the Source Code!

-- [http://planetquake.com/maxtron/ltk/html/downloads.html](https://web.archive.org/web/20000312044307/http://planetquake.com/maxtron/ltk/html/downloads.html)

Links:

* http://www.planetquake.com/dl/dl.asp?maxtron/LTK110.zip

Contents of `LTK110.zip`:

```text
-rw-rw-r--  0 0      0      520192 29 Nov  1999 Quake2/action/gamex86.dll
-rw-rw-r--  0 0      0         456 16 Oct  1999 Quake2/action/bots/botdata.cfg
-rw-rw-r--  0 0      0         494 16 Oct  1999 Quake2/action/bots/asylum.cfg
-rw-rw-r--  0 0      0         609  4 Sep  1999 Quake2/action/cgf/fog/urban.fog
-rw-rw-r--  0 0      0         609  8 Sep  1999 Quake2/action/cgf/fog/city.fog
-rw-rw-r--  0 0      0         717  5 Sep  1999 Quake2/action/cgf/fog/default.fog
-rw-rw-r--  0 0      0         609  4 Sep  1999 Quake2/action/cgf/fog/downtown.fog
-rw-rw-r--  0 0      0         611  4 Sep  1999 Quake2/action/cgf/fog/actcity2.fog
-rw-rw-r--  0 0      0     1139116 29 Nov  1999 Quake2/action/terrain/city.ltk
-r--r--r--  0 0      0        9004 29 Nov  1999 Quake2/AQ2/LTKBots.txt
-r--r--r--  0 0      0        5610 26 Nov  1999 Quake2/AQ2/history.txt
-rw-rw-r--  0 0      0       20608 19 Jul  1999 Quake2/AQ2/src/CHANGES
-rw-rw-r--  0 0      0       18681  4 Jun  1999 Quake2/AQ2/src/LICENSE.TXT
-rw-rw-r--  0 0      0        4671 19 Jul  1999 Quake2/AQ2/src/Makefile
-rw-rw-r--  0 0      0       11355 19 Jul  1999 Quake2/AQ2/src/README
-r--r--r--  0 0      0       30072 16 Sep  1999 Quake2/AQ2/src/a_cmds.c
-r--r--r--  0 0      0       36051 16 Sep  1999 Quake2/AQ2/src/a_game.c
-r--r--r--  0 0      0        1155 20 Jul  1999 Quake2/AQ2/src/a_game.h
-r--r--r--  0 0      0        5763 26 Jun  1999 Quake2/AQ2/src/a_items.c
-r--r--r--  0 0      0        4955 26 Jun  1999 Quake2/AQ2/src/a_menu.c
-r--r--r--  0 0      0         680 26 Jun  1999 Quake2/AQ2/src/a_menu.h
-r--r--r--  0 0      0       23601 16 Sep  1999 Quake2/AQ2/src/a_radio.c
-r--r--r--  0 0      0        1544 26 Jun  1999 Quake2/AQ2/src/a_radio.h
-r--r--r--  0 0      0       56203 26 Sep  1999 Quake2/AQ2/src/a_team.c
-r--r--r--  0 0      0        2686  4 Jul  1999 Quake2/AQ2/src/a_team.h
-r--r--r--  0 0      0       35179 26 Jun  1999 Quake2/AQ2/src/g_ai.c
-r--r--r--  0 0      0        9406  4 Jul  1999 Quake2/AQ2/src/g_chase.c
-r--r--r--  0 0      0       38619 16 Sep  1999 Quake2/AQ2/src/g_cmds.c
-r--r--r--  0 0      0       46067 16 Sep  1999 Quake2/AQ2/src/g_combat.c
-r--r--r--  0 0      0       68957 16 Sep  1999 Quake2/AQ2/src/g_func.c
-r--r--r--  0 0      0       90335 16 Sep  1999 Quake2/AQ2/src/g_items.c
-r--r--r--  0 0      0       52211  2 Nov  1999 Quake2/AQ2/src/g_local.h
-r--r--r--  0 0      0       12534 21 Oct  1999 Quake2/AQ2/src/g_main.c
-r--r--r--  0 0      0       57401 26 Jun  1999 Quake2/AQ2/src/g_misc.c
-r--r--r--  0 0      0       23708 26 Jun  1999 Quake2/AQ2/src/g_monster.c
-r--r--r--  0 0      0       36497 16 Sep  1999 Quake2/AQ2/src/g_phys.c
-r--r--r--  0 0      0       24510 31 Oct  1999 Quake2/AQ2/src/g_save.c
-r--r--r--  0 0      0       38922 31 Oct  1999 Quake2/AQ2/src/g_spawn.c
-r--r--r--  0 0      0       11048 16 Sep  1999 Quake2/AQ2/src/g_svcmds.c
-r--r--r--  0 0      0       25526 16 Sep  1999 Quake2/AQ2/src/g_target.c
-r--r--r--  0 0      0       17305 16 Sep  1999 Quake2/AQ2/src/g_trigger.c
-r--r--r--  0 0      0       13830 26 Jun  1999 Quake2/AQ2/src/g_turret.c
-r--r--r--  0 0      0       14751 16 Sep  1999 Quake2/AQ2/src/g_utils.c
-r--r--r--  0 0      0       62384 16 Sep  1999 Quake2/AQ2/src/g_weapon.c
-r--r--r--  0 0      0          22  6 Jan  1999 Quake2/AQ2/src/game.def
-r--r--r--  0 0      0        8810 26 Jun  1999 Quake2/AQ2/src/game.h
-r--r--r--  0 0      0       16792 26 Jun  1999 Quake2/AQ2/src/m_move.c
-r--r--r--  0 0      0        7359 26 Jun  1999 Quake2/AQ2/src/m_player.h
-r--r--r--  0 0      0      122932 22 Oct  1999 Quake2/AQ2/src/p_client.c
-r--r--r--  0 0      0       26980 26 Sep  1999 Quake2/AQ2/src/p_hud.c
-r--r--r--  0 0      0        2908 26 Jun  1999 Quake2/AQ2/src/p_trail.c
-r--r--r--  0 0      0       36846  1 Oct  1999 Quake2/AQ2/src/p_view.c
-r--r--r--  0 0      0      193272 16 Sep  1999 Quake2/AQ2/src/p_weapon.c
-r--r--r--  0 0      0       36925 26 Jun  1999 Quake2/AQ2/src/q_shared.c
-r--r--r--  0 0      0       49507 31 Oct  1999 Quake2/AQ2/src/q_shared.h
-rw-rw-r--  0 0      0        3950 15 Jun  1999 Quake2/AQ2/src/acebot.txt
-rw-rw-r--  0 0      0         720  2 Nov  1999 Quake2/AQ2/src/vssver.scc
-r--r--r--  0 0      0        3948  4 Jul  1999 Quake2/AQ2/src/a_doorkick.c
-r--r--r--  0 0      0       22319 26 Jun  1999 Quake2/AQ2/src/cgf_sfx_glass.c
-r--r--r--  0 0      0       10390 26 Jun  1999 Quake2/AQ2/src/cgf_sfx_glass.h
-r--r--r--  0 0      0       10660 26 Nov  1999 Quake2/AQ2/src/acesrc/acebot.h
-r--r--r--  0 0      0       21034  2 Nov  1999 Quake2/AQ2/src/acesrc/acebot_ai.c
-r--r--r--  0 0      0        5921  1 Oct  1999 Quake2/AQ2/src/acesrc/acebot_cmds.c
-r--r--r--  0 0      0       35121 22 Oct  1999 Quake2/AQ2/src/acesrc/acebot_items.c
-r--r--r--  0 0      0       29815 22 Oct  1999 Quake2/AQ2/src/acesrc/acebot_movement.c
-r--r--r--  0 0      0       35854  6 Nov  1999 Quake2/AQ2/src/acesrc/acebot_nodes.c
-r--r--r--  0 0      0       31626 16 Oct  1999 Quake2/AQ2/src/acesrc/acebot_spawn.c
-r--r--r--  0 0      0       10082 13 Sep  1999 Quake2/AQ2/src/acesrc/acebot_compress.c
-rw-rw-r--  0 0      0         400 26 Nov  1999 Quake2/AQ2/src/acesrc/vssver.scc
-r--r--r--  0 0      0        3476  1 Oct  1999 Quake2/AQ2/src/acesrc/botnav.h
-r--r--r--  0 0      0       12530 27 Sep  1999 Quake2/AQ2/src/acesrc/botnav.c
-r--r--r--  0 0      0         893 28 Sep  1999 Quake2/AQ2/src/acesrc/botchat.h
-r--r--r--  0 0      0        4519 30 Sep  1999 Quake2/AQ2/src/acesrc/botchat.c
-rw-rw-r--  0 0      0        1571 24 Sep  1999 Quake2/AQ2/src/acesrc/ltklist.c
-r--r--r--  0 0      0        6287 15 Oct  1999 Quake2/AQ2/src/acesrc/botscan.c
-r--r--r--  0 0      0        1249 14 Oct  1999 Quake2/AQ2/src/acesrc/botscan.h
-r--r--r--  0 0      0        1928 31 Oct  1999 Quake2/AQ2/src/acesrc/cgf_sfx_fog.h
-rw-rw-r--  0 0      0       12949 31 Oct  1999 Quake2/AQ2/src/acesrc/cgf_sfx_fog.c
-r--r--r--  0 0      0       12949 31 Oct  1999 Quake2/AQ2/src/acesrc/cgf_sfx_fog.cpp
-rw-rw-r--  0 0      0         629 13 Sep  1999 Quake2/AQ2/AQ2.dsw
-rw-rw-r--  0 0      0        8372  2 Nov  1999 Quake2/AQ2/AQ2.dsp
```

Readme header:

```text
Licensed To Kill for Action Quake II
====================================

** Current version: 1.10 ** ( November 1999)
```

## v1.11

Probably released `LTK111.zip`.

Mentioned in the changelog:

```text
1.11		- Altered code to prevent 180 degree spin attacks when shot in back.
```

## v1.12

Released as `LTK112dll.zip`.

Mentioned in the changelog:

```text
1.12(Rel)	- Further modification to help bot reactions to being shot in the back -
				this one seems to be working now.
			- CanMoveSafely() altered to return 'false' by default
			# Stopped jumping/crouching with sniper rifle.
			+ Added new CVAR 'ltk_routing' set this to 1 to create new route files,
				or update old ones.
			- Temporarily enabled bot route creation while this cvar is set.
			# Added jump checks with is_jumping to fix jump node creation.
			+ Taught bots to send radio messages to report in and when badly hurt.
			- Slight modification to door handling code when stuck. (needs more work)
			+ Basic Radio Gender handling added for bots.
			# Fixed ItemList to be in the right order!
```

Mentioned on the LTK homepage:

> 17th Feb 2000 - New DLL Available
>
> I’ve put a new dll (v1.12) up at http://www.botgod.org.uk/LTK112dll.zip It will not work on its own, you need a previous version of LTK to use it with! (v1.10 or 1.11). Go grab it, test it, report in ltkdiscuss.

-- [http://www.planetquake.com/maxtron/ltk/index.html](https://web.archive.org/web/20000823195935/http://www.planetquake.com/maxtron/ltk/index.html)

Links:

* http://www.botgod.org.uk/LTK112dll.zip

## v1.20

Released as `LTK120.zip`.

Mentioned in the changelog:

```text
1.20(Exp)	- 'radioteam treport' will now get a vocal response from bots
			# Door support greatly improved, old route files will not work!
			- debug mode is now 'sv botdebug on/off' not acedebug.
			+ New command 'sv shownodes on/off' will display only visible nodes.
			- Nodes displayed for only 1 minute during route creation.
			# Fixed 'ltk_routing' usage, wasn't initialising properly.
			- Updated routefile version to 4 - this forces creation of new routes.
			+ 'sv shownodes on/off' node visibility command
```

Mentioned on the LTK homepage:

> 24th Feb 2000 - New LTK Posted (v1.20)
>
> I’ve put the new version of LTK on http://www.botgod.org.uk/ since I can’t getaccess to my PQ uploads directory :( It will NOT use old route files so you’ll have to start again if you decide it is better than v1.12 (believe me, it’s better - way better!) I apologise for the routefiles problem but it was the only way I could fix door support and one or two other problems. This may be the ‘final’ version of LTK before a beta release of the ‘newbot’ I’m working on. This LTK is actually compiled inside the new bot dll and uses the route file format I have planned for the second bot.

-- [http://www.planetquake.com/maxtron/ltk/index.html](https://web.archive.org/web/20000823195935/http://www.planetquake.com/maxtron/ltk/index.html)

Mentioned on BotEpidemic:

> LTK v1.20 | February 25, 2000 - 7:32 GMT | Ze0
>
> RiEvEr has released a new version of his Action Quake 2 bot, Licensed To Kill. He notes that this version of the bot is NOT backwards compatibile with the old route system, so you will have to make new routes. You can grab a copy here.

-- [http://www.botepidemic.com/](https://web.archive.org/web/20000301065441/http://www.botepidemic.com/)

Links:

* http://www.planetquake.com/maxtron/ltk/
* http://www.botgod.org.uk/LTK120.zip

## v1.21

Released as `LTK121.zip`.

Mentioned in the changelog:

```text
1.21(Rel)	- Jump code changed to allow LTK to navigate better.
```

Mentioned on the LTK homepage:

> 27th Feb 2000 - LTK 1.21 on PondScum’s
>
> I ICQ’d the new LTK to PondScum (and Darren) so it could be posted for download. Pondscum told me it’s up on his site already so you can hop over there and grab it from http://www.pondscum.co.uk/

-- [http://www.planetquake.com/maxtron/ltk/index.html](https://web.archive.org/web/20000823195935/http://www.planetquake.com/maxtron/ltk/index.html)

Links:

* http://www.pondscum.co.uk/ltk/ltkpage.htm

Mentioned on BotEpidemic:

> LTK 1.21 | February 29, 2000 - 6:12 GMT | Ze0
>
> RiEvEr has release Version 1.21 of Licensed To Kill, his Action Quake 2 bot. The file can be found on http://www.pondscum.co.uk/ due to some FTP problems with PlanetQuake.

-- [http://www.botepidemic.com/](https://web.archive.org/web/20000301065441/http://www.botepidemic.com/)

Links:

* http://www.planetquake.com/ltk
* http://www.pondscum.co.uk/

Contents of `LTK121.zip`:

```text
-rw-rw-r--  0 0      0      532480 27 Feb  2000 Quake2/action/gamex86.dll
-rw-rw-r--  0 0      0         512 17 Feb  2000 Quake2/action/bots/BAKbotdata.cfg
-rw-rw-r--  0 0      0         494 16 Oct  1999 Quake2/action/bots/BAKasylum.cfg
-rw-rw-r--  0 0      0      704482 27 Feb  2000 Quake2/action/terrain/teamjungle.ltk
-rw-rw-r--  0 0      0      199596 27 Feb  2000 Quake2/action/terrain/asylum.ltk
-r--r--r--  0 0      0        7195 27 Feb  2000 Quake2/LTK2/history.txt
-r--r--r--  0 0      0        9320 27 Feb  2000 Quake2/LTK2/LTK2Bots.txt
```

Readme header:

```text
Licensed To Kill for Action Quake II
====================================

** Current version: 1.21 ** ( February 27th 2000)
```

## v1.22

Released as `LTK122.zip`.

Mentioned in the changelog:

```text
1.22		- Changed weapon selection code to detect if no weapon is available.
			+ Enabled knife throwing.
			+ Enabled kick attacks if no weapon available and close enough.
			# Stopped bots leaping off rooftops with knives!
			+ Knives are now seen as collectable items.
			- Increased sniper accuracy at lower skill levels.
			+ Corner collision detection and avoidance code added.
```

Mentioned on the LTK homepage:

> 1st March 2000 - LTK 1.22 Release is here (Yippee)
>
> Well - my PQ FTP access seems to be working today - go figure!? I’ve uploaded v1.22 of the bots - Improvements today are listed in the history file in the archive but since you never read it, here’s the information:
>
> - Changed weapon selection code to detect if no weapon is available.
> + Enabled knife throwing.
> + Enabled kick attacks if no weapon available and close enough.
> * Stopped bots leaping off rooftops with knives!
> + Knives are now seen as collectable items.
> - Increased sniper accuracy at lower skill levels.
> + Corner collision detection and avoidance code added.
>
> This should - hopefully - be the last change to the LTK bots so I can now concentrate on their replacements ;) Just in case PQ decides to stop playing with us on FTP again, I’ve also uploaded this file to http://www.botgod.org.uk!

-- [http://www.planetquake.com/maxtron/ltk/index.html](https://web.archive.org/web/20000823195935/http://www.planetquake.com/maxtron/ltk/index.html)

Links:

* http://www.planetquake.com/dl/dl.asp?maxtron/LTK122.zip
* http://www.botgod.org.uk/

Listed on the LTK downloads page:

> Licensed To Kill Version 1.22 Release ( 1st March 2000)

-- [http://planetquake.com/maxtron/ltk/html/downloads.html](https://web.archive.org/web/20000312044307/http://planetquake.com/maxtron/ltk/html/downloads.html)

Links:

* http://www.planetquake.com/dl/dl.asp?maxtron/LTK122.zip

Linked on BotEpidemic:

> LTK 1.22	02/03/2000

-- [http://www.botepidemic.com/](https://web.archive.org/web/20000309170015/http://www.botepidemic.com/)

Links:

* http://www.botgod.org.uk/LTK122.zip

Contents of `LTK122.zip`:

```text
-r--r--r--  0 0      0        9356 29 Feb  2000 Quake2/LTK2/LTK2Bots.txt
-rw-rw-r--  0 0      0         512 17 Feb  2000 Quake2/action/bots/BAKbotdata.cfg
-rw-rw-r--  0 0      0         494 16 Oct  1999 Quake2/action/bots/BAKasylum.cfg
-rw-rw-r--  0 0      0      704482 29 Feb  2000 Quake2/action/terrain/teamjungle.ltk
-rw-rw-r--  0 0      0      199596 29 Feb  2000 Quake2/action/terrain/asylum.ltk
-rw-rw-r--  0 0      0       18681  4 Jun  1999 Quake2/LTK2/src/LICENSE.TXT
-rw-rw-r--  0 0      0        3950 15 Jun  1999 Quake2/LTK2/src/acebot.txt
-rw-rw-r--  0 0      0       52736 29 Feb  2000 Quake2/LTK2/Licensed To Kill for Action Quake II.doc
-r--r--r--  0 0      0        7586 29 Feb  2000 Quake2/LTK2/history.txt
-rw-rw-r--  0 0      0      536576 29 Feb  2000 Quake2/action/gamex86.dll
```

Readme header:

```text
Licensed To Kill for Action Quake II
====================================

** Current version: 1.22 ** ( February 29th 2000)
```

## v1.22 Linux

Released as `ltk122linux.zip`

Mentioned on the LTK homepage:

> 6th March 2000 - Linux Port of LTK 1.22
>
> I’ve managed to compile LTK 1.22 under Linux and it seems to be working now. It wouldn’t have been possible without Richard Hess’ previous port of 1.10 which he kindly sent back to me. The problems turned out to be mainly related to SuSE Linux installing egcs instead of gcc as the default compiler.
>
> By the time this is posted I should have an archive of ltk1.22-linux ready for download. I will now continue development of the new bot in parallel so we have Linux and Win32 versions available at the same time. Linux doesn’t have the fog support yet. If I ever get any form of GL to work on my TNT under Linux then I’ll figure a way of porting it across.
>
> If anyone hyas successfully run SuSE Linux 6.2 in GL mode with a TNT card, please get in touch.

-- [http://www.planetquake.com/maxtron/ltk/index.html](https://web.archive.org/web/20000823195935/http://www.planetquake.com/maxtron/ltk/index.html)

Links:

* http://www.planetquake.com/dl/dl.asp?maxtron/ltk122linux.zip

Listed on the LTK downloads page:

> Licensed To Kill Version 1.22 Release [Linux] ( 6th March 2000)
>
> My own port (thanks to R.Hess for his help)

-- [http://planetquake.com/maxtron/ltk/html/downloads.html](https://web.archive.org/web/20000312044307/http://planetquake.com/maxtron/ltk/html/downloads.html)

Links:

* http://www.planetquake.com/dl/dl.asp?maxtron/ltk122linux.zip

Contents of `ltk122linux.zip`:

```text
-rwxr-xr-x  0 0      0      527680  6 Mar  2000 usr/local/games/quake2/action/gamei386.so
-rw-r--r--  0 0      0         512  6 Mar  2000 usr/local/games/quake2/action/bots/botdata.cfg
-rw-r--r--  0 0      0         494  6 Mar  2000 usr/local/games/quake2/action/bots/BAKasylum.cfg
-rw-r--r--  0 0      0      737658  6 Mar  2000 usr/local/games/quake2/action/terrain/teamjungle.ltk
```

## v1.22 Source

Released as `ltksrc.zip`.

Listed on the LTK Downloads page:

> LTK BOT SOURCE CODE !
>
> LTK SOURCE CODE v 1.22 (by REVIER)(NEW)

-- [http://www.pondscum.co.uk/files/files.htm#ltk](https://web.archive.org/web/20010414122017/http://www.pondscum.co.uk/files/files.htm#ltk)

Links:

* http://www.pondscum.co.uk/files/ltkbo/ltksrc.zip

## v1.22 CFG

Released as `ltkbotv1_2.zip`

Listed on the LTK Downloads page:

> LTK.CFG(For 1.22)NEW

-- [http://www.pondscum.co.uk/files/files.htm#ltk](https://web.archive.org/web/20010414122017/http://www.pondscum.co.uk/files/files.htm#ltk)

Links:

* http://www.pondscum.co.uk/files/ltkbo/ltkbotv1_2.zip

## v1.22 Alternate Source

I suspect the source code files were acquired and renamed and stored as part of Action games:

* [http://www.actiongames.co.uk/tnn/](https://web.archive.org/web/20010411042647/http://www.actiongames.co.uk/tnn/)

Listed here:

> Source Files
>
> LTK Source 1.22 (works best in MSVS 6.0) - 480 Kb\
> LTK Source 1.22 [Linux] - 430 Kb

-- [http://www.actiongames.co.uk/tnn/ltk/ltkdload.shtml](https://web.archive.org/web/20030706120323/http://www.actiongames.co.uk/tnn/ltk/ltkdload.shtml)

Links:

* http://files.actiongames.co.uk/tnn/ltk/source/ltk122src-proj.zip
* http://files.actiongames.co.uk/tnn/ltk/source/ltksrc_nix.zip

And here:

```text
[   ] ltk122src-proj.zip      07-Jul-2002 01:26   478k
[   ] ltksrc_nix.zip          07-Jul-2002 01:30   432k
```

-- [http://files.actiongames.co.uk/tnn/ltk/source/](https://web.archive.org/web/20050114071733/http://files.actiongames.co.uk:80/tnn/ltk/source/)

## v0.5

Probably released as `BotRelease0.5.zip`.

Mentioned on ModDB as part of the changelog:

> Version 0.5
>
> x) Rdeath sound removed (To annoying) sorry WereWolf
>
> x) First implentation of smart sellection of weapons,
> based on distance from target and weapon aviable and
> if more weapons was at hand.
>
> The bot in deathmatch does not work properly, this bug was not introduced by me but happened somewhere from Ltk to NewLtk by Josef Jahn. I am trying to track it down.
>
> Bots handle Actcity3 verry good, but the waypoint information has a few bugs in some places, rendering allot of falling accidents.
>
> Feel free to create some one, my time is limited.

-- https://www.moddb.com/mods/action-quake-2-bot/news/a-new-version-is-aviable

## v0.5.1

Released as `BotRelease0.5.1.zip`.

I suspect this is part of a rewrite branch of the project by "RiEvEr" mentioned in some of the changelogs.

Mentioned on ModDB:

> Posted by RiviEr on Apr 23rd, 2005
>
> Version 0.5.1
>
> x) A few more tweaks on the weapon usage again.
>
> x) Bots chat updated.
>
> x) Increased max number of waypoints from 1200 to 1500. Should be enough
> for the largest maps now.
>
> x) Tweaked the door handler, bots will not run SO long backwards
> as before.
>
> Teamjungle.ltk added

And:

> RiviEr - Apr 24 2005 - 2 comments\
> becouse mod db does not suport downloads yet, here is the link from my page. Playspoon.com

-- https://www.moddb.com/mods/action-quake-2-bot/news/a-new-version-is-aviable

Links:

* http://www.playspoon.com/Aq2_Bot/Files/BotRelease0.5.1.zip

## v1.23

Released as `LTK_1.23.exe`.

Changelog:

```text
1.23 9th Feb 2006

- Tweaked the distance bots walk backwards while opening the door.
- Rdeath removed and Im_hit from the radio.
- The bot's arent so agressive using the radio anymore.
- Improved the usage of weapons vs distance to target
- Bot's try to avoid hitting their teammates.
- Improved Jumping.
- Grenades implemented.
- Bots understand when to crouch.
- Changed some sounds
- Bots are able to walk trough the doors , when animated (opening) untill i can
  clean up the bot door handler code.
```

Contents of `LTK_1.23.exe` (I had to extract it manually):

```text
-rw-r--r--@ 1 jasonb  staff     494 16 Oct  1999 BAKasylum.cfg
-rw-r--r--@ 1 jasonb  staff     512 17 Feb  2000 BAKbotdata.cfg
drwxr-xr-x@ 4 jasonb  staff     128  9 Nov 08:25 LTK
drwxr-xr-x@ 6 jasonb  staff     192  9 Nov 08:25 NSIS Plugins Directory
-rw-r--r--@ 1 jasonb  staff  483328 14 Feb  2006 gamex86.dll
drwxr-xr-x@ 5 jasonb  staff     160  9 Nov 08:25 terrain

./LTK_1.23/LTK:
total 72
-rw-r--r--@ 1 jasonb  staff  19363 14 Feb  2006 LICENSE.TXT
-rw-r--r--@ 1 jasonb  staff  15644 14 Feb  2006 Readme.txt

./LTK_1.23/NSIS Plugins Directory:
total 384
-rw-r--r--@ 1 jasonb  staff   12800  9 Nov 08:25 InstallOptions.dll
-rw-r--r--@ 1 jasonb  staff   10240  9 Nov 08:25 System.dll
-rw-r--r--@ 1 jasonb  staff     211 25 Nov  2003 ioSpecial.ini
-rw-r--r--@ 1 jasonb  staff  159822 14 Feb  2006 modern-wizard.bmp

./LTK_1.23/terrain:
total 2424
-rw-r--r--@ 1 jasonb  staff  332892  9 Feb  2006 actcity3.ltk
-rw-r--r--@ 1 jasonb  staff  199596  1 Mar  2000 asylum.ltk
-rw-r--r--@ 1 jasonb  staff  704482  1 Mar  2000 teamjungle.ltk
```

Readme header:

```text
Author:  Fred (others bellow)
Version: 1.23
Website: www.franva.org
email:   fredrick.vamstad@gmail.com
```


## v1.24

Probably released as `LTK1.24.exe`.

Changelog:

```text
LTK 1.24 16 Feb 2006

- Various changes and balances (weapon, think states etc++)
- Added 4 game modes (Bots can play sniper war, mp5 war etc)
- Added a new navigation state.
- Changed a few nodes checks.
- Bot's can now handle doors allot better.
```

## v1.25

Released as `LTK1.25.exe`.

Mentioned on ModDB:

> LTK 1.25 30 March/Apr 2006
>
> - Bot's check their location from time to time, so they arent lost in their
own route table.
> - Bot's "fly" less, but still a issue.
> - Bot's use the scope again.
> - KnifeWar added as a game mode (beta).
> - Improved the grenades usage.
> - Optimized the code generation.
> - Matched the client and the bot rules against the gamemodes.
> - Bot's pic a more reasonable item for the gamemodes.
> - Added action male model to the deathmatch.

-- https://www.moddb.com/mods/action-quake-2-bot/downloads/ltk-125

Contents of `LTK_1.23.exe` (I had to extract it manually):

```text
-rw-r--r--@ 1 jasonb  staff     494 16 Oct  1999 BAKasylum.cfg
-rw-r--r--@ 1 jasonb  staff     512 17 Feb  2000 BAKbotdata.cfg
drwxr-xr-x@ 4 jasonb  staff     128  9 Nov 08:31 LTK
drwxr-xr-x@ 6 jasonb  staff     192  9 Nov 08:31 NSIS Plugins Directory
-rw-r--r--@ 1 jasonb  staff  557056  9 Apr  2006 gamex86.dll
drwxr-xr-x@ 7 jasonb  staff     224  9 Nov 08:31 terrain

./LTK1.25/LTK:
total 80
-rw-r--r--@ 1 jasonb  staff  19363 14 Feb  2006 LICENSE.TXT
-rw-r--r--@ 1 jasonb  staff  16851  9 Apr  2006 Readme.txt

./LTK1.25/NSIS Plugins Directory:
total 384
-rw-r--r--@ 1 jasonb  staff   12800  9 Nov 08:31 InstallOptions.dll
-rw-r--r--@ 1 jasonb  staff   10240  9 Nov 08:31 System.dll
-rw-r--r--@ 1 jasonb  staff     211 25 Nov  2003 ioSpecial.ini
-rw-r--r--@ 1 jasonb  staff  159822 14 Feb  2006 modern-wizard.bmp

./LTK1.25/terrain:
total 6152
-rw-r--r--@ 1 jasonb  staff   332892  9 Feb  2006 actcity3.ltk
-rw-r--r--@ 1 jasonb  staff   199596  1 Mar  2000 asylum.ltk
-rw-r--r--@ 1 jasonb  staff   279580 20 Feb  2006 rexro.ltk
-rw-r--r--@ 1 jasonb  staff   704482  1 Mar  2000 teamjungle.ltk
-rw-r--r--@ 1 jasonb  staff  1625538 16 Feb  2006 urban.ltk
```

Readme header:

```text
Author:  Fred (others bellow)
Version: 1.24
Website: www.franva.org
email:   fredrick.vamstad@gmail.com
```

Changelog:

```text
LTK 1.25 30 March/Apr 2006

- Bot's check their location from time to time, so they arent lost in their
  own route table.
- Bot's "fly" less, but still a issue.
- Bot's use the scope again.
- KnifeWar added as a game mode (beta).
- Improved the grenades usage.
- Optimized the code generation.
- Matched the client and the bot rules against the gamemodes.
- Bot's pic a more reasonable item for the gamemodes.
- Added action male model to the deathmatch.
```

## v2.0

Released as `LTK2.0.zip`.

Mentioned on the LTK 2.0 homepage:

> LTK 2.0\
> Action Quake LTK 2.0 Beta finaly released!

> After a full year of development we are happy to finaly release the beta version of the latest ltk version. So much has changed and some features are not completly tested, some are left out until final release.
>
> Every component has been improved, bot and client code.
>
> LTK 2.00 BETA March 2007
>
> New Features:
>
> - Action coop implemented with:
> - New models for ALL monsters to reflect aq2. (Paril)
> - Monsters use the aq2 weapons correctly, reload, knife, kick etc. (Paril)
> - uses CGF glass for more realism. (Fred)
> - New game rules for monsters, entities etc (Paril, Fred)

-- [http://www.franva.org/news.php](https://web.archive.org/web/20080517020422/http://www.franva.org/news.php)

Contents of `LTK2.0.zip`:

```text
-rw-rw-r--  0 0      0    22761967  2 Apr  2007 Setup.exe
```

Contents of `Setup.exe` (I had to manually extract it):

```text
drwxr-xr-x@ 33 jasonb  staff    1056  9 Nov 08:39 LTK
-rw-r--r--@  1 jasonb  staff  364544  2 Apr  2007 LTK Launcher.exe
drwxr-xr-x@  6 jasonb  staff     192  9 Nov 08:39 NSIS Plugins Directory
...
```

Readme header:

```text
Author:  Fred, Paril (others bellow)
Version: 2.0 BETA
Website: www.franva.org
email:   fredrick.vamstad@gmail.com
```

Changelog:

```text
LTK 2.00 BETA March 2007

- New Features
 - Action coop implemented with:
   - New models for ALL monsters to reflect aq2. (Paril)
   - Monsters use the aq2 weapons correctly, reload, knife, kick etc. (Paril)
   - uses CGF glass for more realism. (Fred)
   - New game rules for monsters, entities etc (Paril, Fred)

 - LTK Launcher (Fred)
   - Host manager, set time, round, maxclients, bots.
   - Can hold virtualy unlimited configuration profiles.
   - ++

 More features will be included in final.

- Changes
 - Tweaked the bots to increase general handling. (Fred)
 - + tons of tweaks (Fred)

- Bugs fixed
 - Handcannon reload is alot better. Instead of waiting for reload to finish to add
   two rounds, it adds the rounds while reloading (one at f78 and one at f79) so it looks
   real. (Paril)
 - Grenades can be picked up in deathmatch again. (Fred)


- Known issues
 - keys dont appear in coop (fixed for final)
 - Health icon when healing is floating.
 - Bots dont understand coop but can spawn (fixed for final)
 ```

