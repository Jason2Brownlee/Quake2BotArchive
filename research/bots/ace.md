# Ace Bot (Artificial Control Experiment)

Developed by Steve Yeager aka "Meat" in 1998.

## Release Chronology (reconstructed)

Version         | Date
--------------- | -----
0.02 			| ?
0.03 			| ?
0.04 			| 19980225 (?)
0.05 			| 19980302
0.06 			| 19980306 (?)
Ace+Oak 		| 19980312
0.06b 			| 19980315 (?)
0.07 			| 19980414 (?)
Ace+Eraser 	 	| 19980419 (?)
ACE II test		| 19990106 (?)
0.08 			| 19990304 (?)
0.08 src 		| 19990615 (?)

## Homepages

1. http://www.quake2.com/oak/ace.html (not archived)
	1. https://web.archive.org/web/*/http://quake2.com/oak/*
2. http://www.telefragged.com:80/oak/ace.html (not archived)
	1. https://web.archive.org/web/*/http://telefragged.com/oak/*
3. [http://www.telefragged.com/ace](https://web.archive.org/web/19980626081325/http://www.telefragged.com:80/ace/) (archived)
	1. https://web.archive.org/web/*/http://www.telefragged.com/ace*
4. [http://www.axionfx.com/ace/](https://web.archive.org/web/20000817072317/http://www.axionfx.com/ace/) (archived)


## v0.02

?

## v0.03

?

## v0.04

Released as `gamex86.zip`.

This might be v0.04 mentioned on BotEpidemic:

> Wednesday 25th Feb '98 GMT
>
> New Bot\
> John Crickett has told me of a new bot on the Oak II page (which is not the Oak II). The bot is called ACE (Artificial Control Experiment) and is done by Steve aka Meat.
> There is a preview version for you to download. And no, it isn't compatible with the point release. Only 3.10.
> Couple of things caught my eye on the page. One, using the "BotBrain" function the bot will take over the player movements, leaving you watching its progress. Two, Steve and John (Crickett) "have discussed plans to possibly combine and the Mighty Oak into one mod, so you would have a choice of spawning an ACE or an Oak and let'em rip."
Remember this is only a preview version, so there will be glitches.

-- [http://www.botepidemic.com/archive/21feb-27feb98.html](https://web.archive.org/web/19991006000158/http://www.botepidemic.com/archive/21feb-27feb98.html)

Links:

* http://www.quake2.com/oak
* http://www.quake2.com/oak/ace.html
* http://www.quake2.com/oak/gamex86.zip

## v0.05

Released as `gamex86.zip` and later `ace005.zip`.

Mentioned on BotEpidemic:

> Tuesday 3rd March '98 GMT
>
> ACE v0.05 Out!\
> Now compatible with 3.13 the new ACE also features:
>
> * Dynamic Pathing. (Bots dynamically path out a level)
> * Dynamic Learning. (Bots learn from their mistakes and get better)
> * "BotBrain". (Shows the bot's intelligence in action)
> * All the rest of the stuff bots should have, moving between levels, scoring, etc.
> * Skin/Sex Choice (Coming soon)
>
> Should be good. Here's the link to version 0.05.

-- [http://www.botepidemic.com/archive/28feb-4mar98.html](https://web.archive.org/web/19991006084314/http://www.botepidemic.com/archive/28feb-4mar98.html)

Links:

* http://www.quake2.com/oak/gamex86.zip

Contents of `ace005.zip`:

```text
-rw-rw-r--  0 0      0        5330  2 Mar  1998 ace/readme.txt
-rw-rw-r--  0 0      0      380416  2 Mar  1998 ace/gamex86.dll
```

Readme header:

```text
ACE (Artificial Control Experiment)
A Quake2 BOT
----------------------------------------------

Current Version:
----------------
Preview Version 0.05
```

Changelog:

```text
Major Changes:
--------------

Version 0.05 (released)
	- New updated "vision" code (almost correct, still needs tweaking)
	- Skill Levels added.
	- Stubbed out decision making logic "What to do next?" (simple for now)
	- Dynamic Learning (bots will get better the more they play a map)
	- Updated to 3.13 (used patch not ID src, come on ID release it already!)

Version 0.04 (never released)
	- Dynamic pathing.
	- Load/Save pathing information.

Version 0.03 (never released)
	- Node logic added.
	- Respawning after level changed fixed (delayed re-entry)

Version 0.02 (released)
	- First preview release
```

## v0.06

Released as `ace006.zip`.

Mentioned on BotEpidemic:

> Friday 6th March '98 EST
>
> ACE 006\
> Steve Y has released a new version of ACE. This version is 006 and has been merged with the 3.14 source as well as having basic swimming code and AI tweaks added. Also both the ACE and the Oak II Bot will be released in a combined mod, probably next week. Version 006 is here. The ACE page is here.
>
> -cube

-- [http://www.botepidemic.com/archive/5mar-8mar98.html](https://web.archive.org/web/19991118003630/http://www.botepidemic.com/archive/5mar-8mar98.html)

Links:

* http://www.quake2.com/oak/ace006.zip
* http://www.quake2.com/oak/ace.html

Reviewed on OGR:

* [Ace Bot v0.06](https://web.archive.org/web/19991003032228/http://ogr.com/specials/quake2bot/quake2_bots_8.shtml)

## Ace + Oak (AcenOak)

Released as `ACEOak01.zip`.

Mentioned on BotEpidemic:

> Thursday 12th March '98 GMT
>
> Oak & ACE\
> Have been combined. Go to the Oak page to learn more...
> More news later.

-- [http://www.botepidemic.com/archive/9mar-12mar98.html](https://web.archive.org/web/19991118004206/http://www.botepidemic.com/archive/9mar-12mar98.html)

Mentioned on Inside3d:

> News Update: 3/12/98, 4:25PM EST, by legion-
>
> ACE and Oak II have also been merged. If you like 1-on-1 battles, I strongly suggest you check out ACE bot. On the "The Edge", I found the bot to be quite difficult to beat. Although I won 20-4 at skill 3, it was quite stressful.

-- [http://www.inside3d.com/mar10-mar12.html](https://web.archive.org/web/19981203113251/http://www.inside3d.com/mar10-mar12.html)

Timestamp of `GAMEX86.DLL` was "1998-03-12".

Contents of `ACEOak01.zip` (repacked, invalidating the timestamps):

```text
drwx------  0 501    20          0  3 Nov 08:55 ACEnOak/
-rw-r--r--  0 501    20       6148  3 Nov 08:55 ACEnOak/.DS_Store
drwxrwxr-x  0 501    20          0  3 Nov 08:54 ACEnOak/MEMORY/
-rw-rw-r--  0 501    20        112  3 Nov 08:54 ACEnOak/BOTNAMES.CFG
-rw-rw-r--  0 501    20     445440  3 Nov 08:54 ACEnOak/GAMEX86.DLL
-rw-rw-r--  0 501    20       3693  3 Nov 08:54 ACEnOak/README.TXT
-rw-rw-r--  0 501    20     338744  3 Nov 08:54 ACEnOak/MEMORY/IKDM1.PTH
```

Readme header:

```text
Ace And Oak II Build Release Notes:
===================================

Version 	0.1

Author: 	John Crickett 			(Oak II)
		Steve Yeager 			(ACE)
Web Page: 	www.quake2.com/oak
		www.quake2.com/oak/ace.html
Email: 		oak@quake2.com
		stevey@jps.net
```

## v0.06b

Released as `ace006b.zip`.

Mentioned on BotEpidemic:

> Sunday 15th March '98 GMT
>
> ACE 0.06b\
> ACE 0.06b is out and I don't remember seeing this before, but I may have forgotten it. Anyway the release will probably be a bug fix so if you were having problems with it try downloading this version.

-- [http://www.botepidemic.com/archive/13mar-19mar98.html](https://web.archive.org/web/19991005164641/http://www.botepidemic.com/archive/13mar-19mar98.html)

Links:

* http://www.quake2.com/oak/ace006.zip (I think this is the wrong lonk)

## v0.07

Released as `acesetup.exe`.

Mentioned on BotEpidemic:

> Tuesday 14th April '98 GMT
>
> ACE 0.07 Released\
> Steve has released a new version of the ACE bot. 0.07 now contains support for CTF, ladders, teleporters, swimming and the grappling hook. There are also many more improvements to the bot. The bot is now in an .exe file as well making it easier to setup.
>
> Version 0.07 can be downloaded here.

-- [http://www.botepidemic.com/archive/9apr-16apr98.html](https://web.archive.org/web/19991118004930/http://www.botepidemic.com/archive/9apr-16apr98.html)

Links:

* http://www.telefragged.com/oak/ace.html
* http://www.telefragged.com/oak/files/acesetup.exe

Listed on Steve's Homepage:

> Version 007b Download now! (574k)
>
> This is the original ACE Bot that has been around for quite a while.
>
> It supports:
>
> * Easy to use setup program.
> * New "Autobot" frontend included.
> * Support for CTF, teleporters, ladders, swimming, and the grappling hook.
> * "BotBrain" (Shows the bot in action).Full Client Emulation.
> * Complex Level Navigation.
> * Support for CTF, Teamplay, and use of all Game Items.
> * Fuzzy logic decision making.
> * Built-in pathing editor.
> * Skill Levels

-- [http://www.axionfx.com/ace/](https://web.archive.org/web/20000817072317/http://www.axionfx.com/ace/)

Links:

* http://www.axionfx.com/ace/Downloads/acesetup.exe

Timestamps from inspecting the contents of `acesetup.exe` are all "1999-03-24".

Content of `acesetup.exe` (after extracting, this messes up the timestamps):

```text
drwxrwxr-x  0 discmaster discmaster  0  5 Nov 05:54 ./memory/
-rw-rw-r--  0 discmaster discmaster 39178  5 Nov 05:54 ./memory/q2ctf2.nod
-rw-rw-r--  0 discmaster discmaster  6377  5 Nov 05:54 ./memory/q2dm6.nod
-rw-rw-r--  0 discmaster discmaster 18598  5 Nov 05:54 ./memory/q2dm1.nod
-rw-rw-r--  0 discmaster discmaster 12267  5 Nov 05:54 ./memory/q2ctf3.nod
-rw-rw-r--  0 discmaster discmaster 15514  5 Nov 05:54 ./memory/q2ctf4.nod
-rw-rw-r--  0 discmaster discmaster  7453  5 Nov 05:54 ./memory/q2dm2.nod
-rw-rw-r--  0 discmaster discmaster  7445  5 Nov 05:54 ./memory/q2dm5.nod
-rw-rw-r--  0 discmaster discmaster 30921  5 Nov 05:54 ./memory/q2ctf1.nod
-rw-rw-r--  0 discmaster discmaster 10290  5 Nov 05:54 ./memory/q2dm4.nod
-rw-rw-r--  0 discmaster discmaster 11833  5 Nov 05:54 ./memory/fbdm4.nod
-rw-rw-r--  0 discmaster discmaster  3877  5 Nov 05:54 ./memory/q2dm3.nod
-rw-rw-r--  0 discmaster discmaster 12809  5 Nov 05:54 ./Readme.txt
-rw-rw-r--  0 discmaster discmaster  4565  5 Nov 05:54 ./autobot.txt
-rw-rw-r--  0 discmaster discmaster 352256  5 Nov 05:54 ./gamex86.dll
-rw-rw-r--  0 discmaster discmaster 514560  5 Nov 05:54 ./Autobot for Ace.exe
```

Readme header:

```text
ACE (Artificial Control Experiment)
A Quake2 BOT
----------------------------------------------

Current Version:
----------------
Version 007
```

## Ace + Eraser (AcenEraser)

Released as `ACEvsEraser.zip`.

Mentioned on BotEpidemic:

> Sunday 19th April '98 GMT
>
> ACEnEraser\
> Steve has released a beta test of ACE and Eraser in one mod. He has just put this together so it is recommended for experienced users only. You will require both Eraser 0.92 and ACE 007. All the commands for each bot are present. It would help if you had route-tables and node files (Eraser and ACE respectively) for the levels you play as this would make for a better game.
>
> Get a copy here.

-- [http://www.botepidemic.com/archive/17apr-22apr98.html](https://web.archive.org/web/19991005184431/http://www.botepidemic.com/archive/17apr-22apr98.html)

Mentioned on Inside3d:

> Latest News April 19th
>
> Flavasize - Cube of the Bot Epidemic mailed in about 'ACEnEraser', a bot combines the Eraser and ACE bot. It's a beta version, so only experienced users should give it a shot.

-- [http://www.inside3d.com/apr17-apr24.shtml](https://web.archive.org/web/19981206160612/http://www.inside3d.com/apr17-apr24.shtml)

Links:

* http://www.telefragged.com/oak/files/ACEvsEraser.zip

## New Homepage

Mentioned on BotEpidemic:

> Friday 24th April '98 GMT
>
> ACE Moves\
> Steve has moved the ACE site to http://www.telefragged.com/ace.

-- [http://www.botepidemic.com/archive/23apr-27apr98.html](https://web.archive.org/web/19991006005705/http://www.botepidemic.com/archive/23apr-27apr98.html)

## Ace II

Released as `acetest.zip`.

Mentioned on BotEpidemic:

> Wednesday 6th January '99
>
> ACE II News/Demo  update by cube\
>Yesterday 3ZB II, today ACE II. Steve Yeager sent this info on what he's been doing over the holidays:

>> ACE II
>>
>> - Built on 3.20 src.
>> - CTF support.
>> - Full client emulation.
>> - New navigation method, very fast and supports the 64 player maps with ease.
>> - New movement code.
>> - New goal decision logic.
>>
>> Basically, I took apart the original ACE source and rebuilt the parts that I thought really sucked. The navigation and movement code were complete rewritten to accommodate a new method I developed (which can be read about on BotAid). No more slowdowns on the larger maps, and the accuracy of the ACE bot's movement are vastly improved. I also simplified the goal selection and combat AI so they basically work as well as the original ACE, but will allow better functions to be dropped in to improve the bots abilities. Probably the best news is that I will be releasing the source code once the last few bugs are cleaned up. That's right the entire source, which should allow anyone who wants to add ACE bots to their mods very simple, or to create all new bots based on ACE. The ACE bot source hooks into the original id source with only about 15 simple id source code changes. As for a release date all I can say is "Real Soon Now".
>
> And if that wasn't enough Steve also sent along a demo for posting, which you can get hold of here.

-- [botepidemic.com/archives/6jan99-22jan99.shtml](https://web.archive.org/web/20000818034919/botepidemic.com/archives/6jan99-22jan99.shtml)

Links:

* http://www.telefragged.com/mirrors/mirrors.pl?be/acetest.zip

## v0.08

Released as `ace008_dll.zip`.

Listed on Steve's Homepage:

> Finally.....this may now be a little dated, but I got off my lazy ass to release it.... (Steve 6/10/99)
>
> Here you can download the latest ACE Bots.  If you want to know more about ACE or the other Q2 bots out there, there are much better sites than this that will tell you a heck of a lot more about Bots, for example Bot Epidemic or Bot Emporium.
>
> If you want to visit my main site, go here.
>
> On with the bots....

And:

> Version 008 (Base Bot) Download now
>
> This is a compiled version the new ACE Bot base code.  It is simply the main 3.2 dll zipped and currently does not contain a launcher or > setup program. For installation, read the readme.txt file included in the zip.
>
> I have completely rewritten many of the bot's internals including a brand spanking new pathing system.
>
> It supports:
>
> * 3.20 version of source.
> * Spectator mode.
> * Setup Program.
> * Autobot Launcher.
> * Support for CTF.
> * Client movement.
> * New pathing system.
> * Dynamic skill levels. (set starting skill, bots adjusts during play)
> * Source code available.

-- [http://www.axionfx.com/ace/](https://web.archive.org/web/20000817072317/http://www.axionfx.com/ace/)

Links:

* http://www.axionfx.com/ace/downloads/ace008_dll.zip

Reviewed on Randars:

> ACE Bot: (Final Version 008) The ACE Bot, by Steve Yeager, with only its second release, is already a major player in the Bot World. This superb Bot plays a little differently than the rest of the Bots due to its full client emulation (i.e., it plays like a real player), complex AI, and its ability to navigate difficult levels. The ACE also supports teamplay and Capture the Flag. This Bot even comes with built in commands to edit its own level pathing. Wow! This is one Bot to watch closely in future releases. It has the potential to be a top contender for the title "King of the Bots."
>
> Randar's Rating—FOUR STARS +
>
> Special Award: Best Real Player Emulation!

-- https://www.randars.com/bots/review.html

Contents of `ace008_dll.zip`:

```text
-rw-rw-r--  0 0      0      569396  5 Feb  1999 Quake2/Ace/gamex86.dll
-rw-rw-r--  0 0      0       98044  4 Mar  1999 Quake2/Ace/nav/q2dm1.nod
-rw-rw-r--  0 0      0        9156  5 Feb  1999 Quake2/Ace/nav/ikdm1.nod
-rw-rw-r--  0 0      0        2531  5 Jun  1999 Readme.txt
```

Readme header:

```text
ACE
A Quake2 BOT
----------------------------------------------

Current Version:
----------------
Version 008
```


## v0.08 Source

Released as `ace008_src.zip`.

Listed on Steve's Homepage:

> Version 008 (Base Bot Source) Download now
>
> This is the full source for the ACE Base Bot.  All of the relevant information is in the source and any bot constructed from this base code must mention that it was based on the ACE Base code. I think you will find it quite easy to add this source to any other mod out there. It was compiled under VC++ 6.0.
>
> This bot, like ACE 007, is one of the few out there to truly use client emulation, for which I credit the SABIN dudes for showing me the last pieces of the puzzle I needed to get it to work.  You'll find that by using client emulation and environmental sampling most of what was done to get the bot to work can be ported very easily to other 3d engines.  There is a simplified vision system for local navigation (roaming and obstacle avoidance) and a pathing system for level navigation. Most of the other internal AI routines have been simplified and may not provide the same level of intelligent decision making that the original ACE had, but serve to demonstrate just how good the base code actually is. Since the source has now been released, you are free to change the AI as you see fit.  Someday I may get around to releasing some of the test bots I wrote with things such as Neural Net AI, or GA AI.  Both of those AI systems are not really finished and more of an experiment to make each bot have a unique personality and not appear like the same old ordinary bot.
>
> NOTE: I will not answer any questions from newbie coders, such as "how do I compile? or what the heck is 'C'?" , but if you have any advanced questions please feel free to email me at syeager@axionfx.com.

-- [http://www.axionfx.com/ace/](https://web.archive.org/web/20000817072317/http://www.axionfx.com/ace/)

Links:

* http://www.axionfx.com/ace/downloads/ace008_src.zip

Contents of `ace008_src.zip`:

```text
drwxrwxr-x  0 0      0           0 11 Jan  1999 Temp/
drwxrwxr-x  0 0      0           0  4 Dec  1998 acesrc/
-rw-rw-r--  0 0      0        8865 11 Jan  1999 acesrc/acebot.h
-rw-rw-r--  0 0      0       12336 11 Jan  1999 acesrc/acebot_ai.c
-rw-rw-r--  0 0      0        6825 11 Jan  1999 acesrc/acebot_cmds.c
-rw-rw-r--  0 0      0       18807 11 Jan  1999 acesrc/acebot_items.c
-rw-rw-r--  0 0      0       19191 11 Jan  1999 acesrc/acebot_movement.c
-rw-rw-r--  0 0      0       23528 11 Jan  1999 acesrc/acebot_nodes.c
-rw-rw-r--  0 0      0       15109 11 Jan  1999 acesrc/acebot_spawn.c
-rw-rw-r--  0 0      0        9653 30 Dec  1998 acesrc/acebot_compress.c
-rw-rw-r--  0 0      0       29481  3 Jan  1999 g_local.h
-rw-rw-r--  0 0      0       16119 29 Apr  1998 game.001
-rw-rw-r--  0 0      0          22  4 Dec  1998 game.def
-rw-rw-r--  0 0      0       25711 11 Jan  1999 game.dsp
-rw-rw-r--  0 0      0         618 31 Dec  1998 game.dsw
-rw-rw-r--  0 0      0        6802  4 Dec  1998 game.h
-rw-rw-r--  0 0      0       54784 11 Jan  1999 game.opt
-rw-rw-r--  0 0      0        3756 11 Jan  1999 game.plg
-rw-rw-r--  0 0      0       24394  4 Dec  1998 g_ai.c
-rw-rw-r--  0 0      0        3570  4 Dec  1998 g_chase.c
-rw-rw-r--  0 0      0       19118 31 Dec  1998 g_cmds.c
-rw-rw-r--  0 0      0       14777  4 Dec  1998 g_combat.c
-rw-rw-r--  0 0      0       69984 31 Dec  1998 g_ctf.c
-rw-rw-r--  0 0      0        4781  5 Dec  1998 g_ctf.h
-rw-rw-r--  0 0      0       50818  4 Dec  1998 g_func.c
-rw-rw-r--  0 0      0       49591  4 Dec  1998 g_items.c
-rw-rw-r--  0 0      0        8792  2 Jan  1999 g_main.c
-rw-rw-r--  0 0      0       45165  4 Dec  1998 g_misc.c
-rw-rw-r--  0 0      0       17091  4 Dec  1998 g_monster.c
-rw-rw-r--  0 0      0       20870  4 Dec  1998 g_phys.c
-rw-rw-r--  0 0      0       18717  2 Jan  1999 g_save.c
-rw-rw-r--  0 0      0       23711  2 Jan  1999 g_spawn.c
-rw-rw-r--  0 0      0        6383  2 Jan  1999 g_svcmds.c
-rw-rw-r--  0 0      0       19877  4 Dec  1998 g_target.c
-rw-rw-r--  0 0      0       13223  4 Dec  1998 g_trigger.c
-rw-rw-r--  0 0      0       10961  4 Dec  1998 g_turret.c
-rw-rw-r--  0 0      0       10899  1 Jan  1999 g_utils.c
-rw-rw-r--  0 0      0       23056  4 Dec  1998 g_weapon.c
-rw-rw-r--  0 0      0       18681 25 Feb  1998 license.txt
-rw-rw-r--  0 0      0       13299  4 Dec  1998 m_actor.c
-rw-rw-r--  0 0      0       16845  4 Dec  1998 m_actor.h
-rw-rw-r--  0 0      0       11280  4 Dec  1998 m_berserk.c
-rw-rw-r--  0 0      0        8558  4 Dec  1998 m_berserk.h
-rw-rw-r--  0 0      0       15984  4 Dec  1998 m_boss2.c
-rw-rw-r--  0 0      0        6351  4 Dec  1998 m_boss2.h
-rw-rw-r--  0 0      0        1343  4 Dec  1998 m_boss3.c
-rw-rw-r--  0 0      0       17426  4 Dec  1998 m_boss31.c
-rw-rw-r--  0 0      0        6601  4 Dec  1998 m_boss31.h
-rw-rw-r--  0 0      0       21042  4 Dec  1998 m_boss32.c
-rw-rw-r--  0 0      0       17207  4 Dec  1998 m_boss32.h
-rw-rw-r--  0 0      0       14784  4 Dec  1998 m_brain.c
-rw-rw-r--  0 0      0        7786  4 Dec  1998 m_brain.h
-rw-rw-r--  0 0      0       15174  4 Dec  1998 m_chick.c
-rw-rw-r--  0 0      0       10093  4 Dec  1998 m_chick.h
-rw-rw-r--  0 0      0       12183  4 Dec  1998 m_flash.c
-rw-rw-r--  0 0      0        8975  4 Dec  1998 m_flipper.c
-rw-rw-r--  0 0      0        5618  4 Dec  1998 m_flipper.h
-rw-rw-r--  0 0      0       14975  4 Dec  1998 m_float.c
-rw-rw-r--  0 0      0        8696  4 Dec  1998 m_float.h
-rw-rw-r--  0 0      0       13962  4 Dec  1998 m_flyer.c
-rw-rw-r--  0 0      0        5432  4 Dec  1998 m_flyer.h
-rw-rw-r--  0 0      0        9212  4 Dec  1998 m_gladiator.c
-rw-rw-r--  0 0      0        3181  4 Dec  1998 m_gladiator.h
-rw-rw-r--  0 0      0       14274  4 Dec  1998 m_gunner.c
-rw-rw-r--  0 0      0        7323  4 Dec  1998 m_gunner.h
-rw-rw-r--  0 0      0       13501  4 Dec  1998 m_hover.c
-rw-rw-r--  0 0      0        7191  4 Dec  1998 m_hover.h
-rw-rw-r--  0 0      0       13940  4 Dec  1998 m_infantry.c
-rw-rw-r--  0 0      0        7264  4 Dec  1998 m_infantry.h
-rw-rw-r--  0 0      0       16605  4 Dec  1998 m_insane.c
-rw-rw-r--  0 0      0        9887  4 Dec  1998 m_insane.h
-rw-rw-r--  0 0      0       17543  4 Dec  1998 m_medic.c
-rw-rw-r--  0 0      0        8311  4 Dec  1998 m_medic.h
-rw-rw-r--  0 0      0       10801 19 Dec  1998 m_move.c
-rw-rw-r--  0 0      0       14420  4 Dec  1998 m_mutant.c
-rw-rw-r--  0 0      0        5232  4 Dec  1998 m_mutant.h
-rw-rw-r--  0 0      0       13071  4 Dec  1998 m_parasite.c
-rw-rw-r--  0 0      0        4278  4 Dec  1998 m_parasite.h
-rw-rw-r--  0 0      0        6945  4 Dec  1998 m_player.h
-rw-rw-r--  0 0      0        2162  4 Dec  1998 m_rider.h
-rw-rw-r--  0 0      0       29041  4 Dec  1998 m_soldier.c
-rw-rw-r--  0 0      0       16643  4 Dec  1998 m_soldier.h
-rw-rw-r--  0 0      0       15686  4 Dec  1998 m_supertank.c
-rw-rw-r--  0 0      0        8913  4 Dec  1998 m_supertank.h
-rw-rw-r--  0 0      0       19359  4 Dec  1998 m_tank.c
-rw-rw-r--  0 0      0       10302  4 Dec  1998 m_tank.h
-rw-rw-r--  0 0      0       46257  3 Jan  1999 p_client.c
-rw-rw-r--  0 0      0       12948  2 Jan  1999 p_hud.c
-rw-rw-r--  0 0      0        3375 30 Jan  1998 p_menu.c
-rw-rw-r--  0 0      0         545 18 Jan  1998 p_menu.h
-rw-rw-r--  0 0      0        2122  4 Dec  1998 p_trail.c
-rw-rw-r--  0 0      0       26633  4 Dec  1998 p_view.c
-rw-rw-r--  0 0      0       34994  4 Dec  1998 p_weapon.c
-rw-rw-r--  0 0      0       25492  4 Dec  1998 q_shared.c
-rw-rw-r--  0 0      0       33819  4 Dec  1998 q_shared.h
-rw-rw-r--  0 0      0        3950 15 Jun  1999 acebot.txt
-rw-rw-r--  0 0      0       97166  3 Jan  1999 q2dm1.nod
```

Readme header:

```text
///////////////////////////////////////////////////////////////////////
//
//  ACE - Quake II Bot Base Code
//
//  Version 1.0 - \/ \/ \/ \/ \/ READ BELOW \/ \/ \/ \/ \/
//
//  This file is Copyright(c), Steve Yeager 1998, All Rights Reserved
//
//
//	All other files are Copyright(c) Id Software, Inc.
//
//	Please see license.txt in the source directory for the copyright
//	information regarding those files belonging to Id Software, Inc.
//
//	Should you decide to release a modified version of ACE, you MUST
//	include the following text (minus the BEGIN and END lines) in the
//	documentation for your modification.
//
//	--- BEGIN ---
//
//	The ACE Bot is a product of Steve Yeager, and is available from
//	the ACE Bot homepage, at http://www.axionfx.com/ace.
//
//	This program is a modification of the ACE Bot, and is therefore
//	in NO WAY supported by Steve Yeager.
//
//	This program MUST NOT be sold in ANY form. If you have paid for
//	this product, you should contact Steve Yeager immediately, via
//	the ACE Bot homepage.
//
//	--- END ---
//
//	I, Steve Yeager, hold no responsibility for any harm caused by the
//	use of this source code, especially to small children and animals.
//      It is provided as-is with no implied warranty or support.
//
//      I also wish to thank and acknowledge the great work of others
//      that has helped me to develop this code.
//
//      John Cricket    - For ideas and swapping code.
//      Ryan Feltrin    - For ideas and swapping code.
//      SABIN           - For showing how to do true client based movement.
//      BotEpidemic     - For keeping us up to date.
//      Telefragged.com - For giving ACE a home.
//      Microsoft       - For giving us such a wonderful crash free OS.
//      id              - Need I say more.
//
//  And to all the other testers, pathers, and players and people
//  who I can't remember who the heck they were, but helped out.
//
///////////////////////////////////////////////////////////////////////
```


## References

* [ACE Bot Review](https://web.archive.org/web/20000818042015/http://www.botepidemic.com/reviews/acerev.shtml), BotEpidemic.
* [ACE Setup Guide](https://psewell.tripod.com/acehelp1.html)
