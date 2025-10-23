# CRBot

CRBot or "C.R.Bot" by Mike Malakhov.

## Release Chronology (reconstructed)

Version | Date (yyyymmdd)
--------| ---------------
v0.9    | 19980103 (?)
v0.91   | 19980104
v0.92   | 19980105 (?)
v0.93   | 19980111
v0.94   | 19980113
v0.95   | 19980114
v0.96   | 19980115
v0.97   | 19980124 (?)
v0.98   | 19980128
v0.99   | 19980130
v0.99a  | 19980208 (?)
v0.99b  | 19980213 (?)
v0.99c  | 19980214
v0.99d  | 19980302
v0.99e  | 19980304 (?)
v1.0    | 19980305 (?)
v1.01   | 19980306 (?)
v1.02   | 19980309 (?)
v1.03   | 19980315 (?)
v1.04   | ?
v1.05   | ?
v1.06   | ?
v1.07   | ?
v1.08   | ?
v1.09   | ?
v1.11   | ?


## Homepages

1. http://www.pobox.com/~ww/bot.html (not archived)
2. [http://www.hooked.net/~mim/bot.html](https://web.archive.org/web/19990202061818/) (archived)
	* [http://www.hooked.net/~mim/](https://web.archive.org/web/19981206040337/http://www.hooked.net:80/~mim/) (archived)
3. [http://planetquake.com/crbot/](https://web.archive.org/web/19990224100215/http://www.planetquake.com/crbot/) (archived)

Perhaps:

* [http://www.geocities.com/SiliconValley/Lab/8885/](https://web.archive.org/web/20010517033010/http://www.geocities.com:80/SiliconValley/Lab/8885/) (archived)


## v0.9

Released as `crbot09.zip`.

Mentioned on the CRBot homepage:

> 03 January, 1998:
>
> First public alpha release of the CRBot. AI is very simple right now, so don't blame me if bot will behave himself really stupid. But he can do a lot of things already: pick up weapons and powerups around, attack you with best weapon he has, chase you down, learn the level while playing.
> Don't expect too much from the first release, I'm going to add a lot of other features like jumping and ducking, human-like behavior, improved path-finding and roaming algorythm and so on. Currently bot doesn't know how to use rocket launcher, grenade launcher and BFG, I'm gonna fix it later.
> And last thing -- bot doesn't cheat, I tried to keep all his characteristics as close as possible to player abilities. Maybe firing accuracy is way too strong right now, I'm thinking to add skill levels so you can tweak it as you want.
>
> Enjoy, Mike.

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

**A copy of this release has not yet been acquired.**


## v0.91

Released as `crbot091.zip` and perhaps `crbot091.zip`.

Mentioned on the CRBot homepage:

> 04 January, 1998:
>
> Stupid problem with bot skin has been fixed. It was rendering all bots invisible leaving weapons floating lonely in the air. Funny, but no good.

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

A copy of this release was found with the filename `crbot09.zip`.

Content of `crbot09.zip`:

```text
-rw-rw-r--  0 0      0        1577  4 Jan  1998 CRBOT/README.TXT
-rw-rw-r--  0 0      0      367616  4 Jan  1998 CRBOT/GAMEX86.DLL
```

Readme header:

```text
Name of Mod : The C.R.Bot, for Quake II
File Name   : crbot09.zip
Version     : 0.91a
Date        : January 04, 1998
E-mail      : ww@pobox.com
Web Site    : http://www.pobox.com/~ww/bot.html
```

A day later, an updated version of this was released.

Content of `crbot091.zip`:

```text
-rw-rw-r--  0 0      0        1600  5 Jan  1998 CRBOT/README.TXT
-rw-rw-r--  0 0      0      367616  4 Jan  1998 CRBOT/GAMEX86.DLL
```

The MD5 hash of `GAMEX86.DLL` in the two releases is identical.

The only difference is some text in `README.TXT`.

## v0.92

Probably released as `crbot092.zip`.

Perhaps mentioned on the CRBot homepage:

> 05 January, 1998:
>
> Several people complained that bot is way too accurate. Now you can specify bot's skill level when creating one by typing "cmd addbot #", where # is a number from 1 to 10. Bots on 10th level don't miss, so beware.
 Added some more animations for bots to perform after killing their primary target.

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

**A copy of this release has not yet been acquired.**

## v0.93

Released as `crbot093.zip`.

Mentioned on the CRBot homepage:

> 10 January, 1998:
>
> Quite a few changes since last version, so propbably I'll mention just big ones.
> Now bots attack each other. Even more, I implemented teams, so you can have two or more groups of bots fighting against you and each other. To assign a bot to certain team you have to set "bot_team" variable to any number from 0 to 9 before creating the bot. Team 0 is special: bots in it are not considered to be in any team. And it's default setting.
> Bot knows how to use rocket launcher now. He is still quite awkward in doing and can kill himself once in a while, but at least it's something.
> Decision code completely rewritten and [hopefully] improved, bot now searches for things he really needs first. Roaming code is also rewritten, I hope I made it better, not worse...
> Bots are mentioned in scoreboard now. For some reason I can't display more than 16 lines in there, but it should be more than enough.
> You can change skin on the bot now. In order to do this you will have to set "bot_skin" variable to the name of desired skin -- "male/viper" or "male/cipher", for example. All bots share the same skin and you will have to create at least one bot after changing "bot_skin" in order for changes to take effect. There is one drawback though, I'm using last multiplayer slot for holding skin data, so if you've started the game with max_clients = 16, for example, then all bots will have the same skin as player #16, assuming he is in the game. And vise versa.
> In next version I hope to finally make bot jump and crouch. And maybe swim.

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

Mentioned on BluesNews:

> Sunday, January 11, 1998
>
> New C.R.Bot\
> Version 0.93 of the C.R.Bot has been released on the C.R.Bot page. Now bots attack each other, understand teamplay, and feature improved search and roaming code. In next version the author hopes to make the bot jump and crouch (and maybe swim).

-- https://www.bluesnews.com/archives/jan98-2.html

Links:

* http://www.hooked.net/~mim/bot.html

Mentioned on Telefragged:

> Latest News, January 11
>
> Quake 2 Bot -- News from Peter Tew -- Update by QuakeGod\
> The C.R.Bot is at version .93. This Quake 2 bot now features the bots attacking each other and also, teamplay is part of the game.

-- [http://www.telefragged.com/](https://web.archive.org/web/19980114104615/http://www.telefragged.com/) (archived)

Links:

* http://www.hooked.net/~mim/bot.html

Content of `crbot093.zip`:

```text
-rw-rw-r--  0 0      0        2631 11 Jan  1998 CRBOT/README.TXT
-rw-rw-r--  0 0      0      377344 10 Jan  1998 CRBOT/GAMEX86.DLL
```

Readme header:

```text
Name of Mod : The C.R.Bot, for Quake II
File Name   : crbot09.zip
Version     : 0.93
Date        : January 10, 1998
E-mail      : ww@pobox.com
Web Site    : http://www.pobox.com/~ww/bot.html
...
```

## v0.94

Released as `crbot094.zip`.

Mentioned on the CRBot homepage:

> 13 January, 1998:
>
> Couple of new things in v0.94 -- bot knows how to jump and how to use grenade launcher. Jumping is not very intelligent right know, I'm going to work more on it.

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

Mentioned on BluesNews:

> Wednesday, January 14, 1998
>
> C.R.Bot\
> Version 0.94 of the C.R.Bot has been released on the C.R.Bot homepage. Thanks Prophet.

-- https://www.bluesnews.com/archives/jan98-2.html

Links:

* http://www.hooked.net/~mim/bot.html

Contents of `crbot094.zip`:

```text
-rw-rw-r--  0 0      0        2631 13 Jan  1998 CRBOT/README.TXT
-rw-rw-r--  0 0      0      379904 13 Jan  1998 CRBOT/GAMEX86.DLL
```

Readme header:

```text
Name of Mod : The C.R.Bot, for Quake II
File Name   : crbot09.zip
Version     : 0.94
Date        : January 13, 1998
E-mail      : ww@pobox.com
Web Site    : http://www.pobox.com/~ww/bot.html
...
```

## v0.95

Released as `crbot095.zip`.

Mentioned on the CRBot homepage:

> 14 January, 1998:
>
> Yesterday was definitely a bad date to release new version of the bot. I have couple of reports about bot crashing the game. Hopefully I fixed the problem in this version.
> And a few new things. After introducing jumps bot started getting stuck in various places, had to add special check, hopefully no more bored bots just standing in strange places. Some improvements in building dynamic route network, but its rather technical stuff.
> Completely redone commands to control bot's creation. Now you can 'addbot', 'addbots' and 'killbot'. Please note -- no 'cmd' in front. First command is to add single bot and you can specify name (in quotes) and skill level. Second is to add a bunch of bots and third is to remove one bot from the game. More info in README.TXT. And one more thing: now all commands will be effective only on server, as many of you have requested.
> I'm also getting a lot of requests to make bots talk. So if you could possibly send me several funny lines which bot can say in different situations, I'll gladly add it in next version.

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

Mentioned on BluesNews:

> Thursday, January 15, 1998
>
> New C.R.Bot\
> Version 0.95 of the C.R.Bot is out on the C.R.Bot homepage, fixing some bugs that caused crashes in the previous release. Thanks Prophet.

-- https://www.bluesnews.com/archives/jan98-2.html

Links:

* http://www.hooked.net/~mim/bot.html

Contents of `crbot095.zip`:

```text
-rw-rw-r--  0 0      0        2902 14 Jan  1998 CRBOT/README.TXT
-rw-rw-r--  0 0      0      380416 14 Jan  1998 CRBOT/GAMEX86.DLL
```

Readme header:

```text
Name of Mod : The C.R.Bot, for Quake II
File Name   : crbot095.zip
Version     : 0.95
Date        : January 14, 1998
E-mail      : ww@pobox.com
Web Site    : http://www.pobox.com/~ww/bot.html
```

## v0.96

Released as `crbot096.zip`.

Mentioned on the CRBot homepage:

> 15 January, 1998:
>
> Yeah, finally I nailed down that problem with bot crashing the game. At least I hope so. :) The reason why it was happening was lava. I hate levels with a lot of lava (always end up in it) and I never tested my bot long enough on such levels. The good thing is at the same time as I was hunting that bug I found quite efficient way to help bots avoid lava.
> Finaly added all skins to model, so now you can have different skin on all bots ("bot_skin" is now a number and not skin's name). That's why archive is 4 times bigger -- had to include female and male models in it. And yes, now you can specify bot's gender by setting "bot_male" cvar to 0 for female model and to 1 for male.
> Still didn't get any response from id Software about "cprintf to a non-client" problem. Introduced new cvar named "obituary_msgs" which you can set to 0 if you don't want any "somebody killed by somebody" messages. I believe it can temorarily help to avoid that evil "cprintf to a non-client".
> One more thing: please, do not ask me to make Linux or Alpha port right now, I'm planning to do it eventually -- when I'll have some extra time and when I'll be sure that bot is stable enough. Currently it's still in beta stage.

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

Mentioned on BluesNews:

> Friday, January 16, 1998
>
> Newer C.R.Bot\
> Another new C.R.Bot, version 0.96 has been released on the C.R.Bot page (thanks Prophet), which has newly relocated to www.planetquake.com/crbot/.

-- https://www.bluesnews.com/archives/jan98-2.html

Links:

* http://www.planetquake.com/crbot/

Contents of `crbot096.zip`:

```text
-rw-rw-r--  0 0      0        3761 15 Jan  1998 CRBOT/README.TXT
-rw-rw-r--  0 0      0      381440 15 Jan  1998 CRBOT/GAMEX86.DLL
drwxrwxr-x  0 0      0           0 15 Jan  1998 CRBOT/BOTS/
drwxrwxr-x  0 0      0           0 15 Jan  1998 CRBOT/BOTS/FEMALE/
drwxrwxr-x  0 0      0           0 15 Jan  1998 CRBOT/BOTS/MALE/
-rw-rw-r--  0 0      0      276272 15 Jan  1998 CRBOT/BOTS/FEMALE/TRIS.MD2
-rw-rw-r--  0 0      0      279552 15 Jan  1998 CRBOT/BOTS/MALE/TRIS.MD2
```

Readme header:

```text
Name of Mod : The C.R.Bot, for Quake II
File Name   : crbot096.zip
Version     : 0.96
Date        : January 15, 1998
E-mail      : ww@pobox.com
Web Site    : http://www.pobox.com/~ww/bot.html
```


## v0.97

Released as `crbot097.zip`.

Mentioned on the CRBot homepage:

> 24 January, 1998:
>
> 2:10pm: Ok, found the bug. It was crashing the game if you did NOT have "+map <map_name>" in your command line (which I happend to have and that's why I wasn't aware of this crash). Fixed it, enjoy.
> 1:05pm: I have several reports about bot crashing the game even before it starts, before ID's logo. I'm looking into it right now and will post fix once I found what's the problem. Sorry about that.
>
> Ok, new version is out. A lot of changes and improvements, here what I can remember:
>
> * movement code completely rewritten, that means hopefully no more bots stuck in some strange places;
> * jumping fixed, added crouching and swimming;
> * bot now understands quad damage and invulnerability and tries to get them first, beware;
> * bot now fully understands teleports and elevators and will use them intentionally;
> * several AI bugs are found and fixed; one of them was actually preventing bot from chasing you properly;
> * support for deathmatch flag "unlimited ammo";
> * bot will say different phrases in certain situations, you can customise it by editing text files KILL.TXT, PAIN.TXT, DEATH.TXT, * FIGHT.TXT; read README.TXT for details;
> * improved bots teamplay: they will call for help within the team and will share information about enemies location; I'm thinking to make > * them exchange weapons as well;
> * now you can place extended command
> * "cmd addbot <name> <skill> <male/female> <skin_no> <team_no>"
> * into .CFG file and create predefined set of bots every time you're playing Quake2 by typing "exec bots.cfg"; example BOTS.CFG file is * included in archive;
> * and more...
>
> Things to do:
> * intelligent jumping;
> * rocket-jumping;
> * better lava avoidance;
> * performance improvements;
> * and more...

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

Links:

* http://asp.planetquake.com/dl/dl.asp?crbot/crbot097.zip

Mentioned on BluesNews:

> Saturday, January 24, 1998
>
> New C.R.Bot\
> Botmania continues, as version 0.97 of the C.R.Bot has been released on the CRBot official homepage, including a ton of changes.

-- https://www.bluesnews.com/archives/jan98-4.html

Links:

* http://www.planetquake.com/crbot/

**A copy of this release has not yet been acquired.**

## v0.98

Released as `crbot098.zip`.

Mentioned on the CRBot homepage:

> 28 January, 1998:
>
> Another intermediate version 0.98. Mainly I was focusing on improving bot's jumping ability and on tweaking how bot decides to use certain weapon based on circumstances. And a few other things:
>
> * menu system; use your "inventory" keys to navigate (usually it's "TAB", "[", "]" and "ENTER");
> * new skill level 0, bot will dynamically adjust his abilities to match player's skills if bot was created with skill level 0; the idea is that bot lowers its skill level every second time he kills any of human players and raises one level every second time he dies from human's hand;
> * new var for dedicated servers "restricted_mode", setting it to 1 will prevent creation of new bots from any client machine;
> * new command "cmd bot_stats" to display information about all bots in the game;
> * and more...

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

Mentioned on BluesNews:

> Wednesday, January 28, 1998
>
> Bot Fever\
> Version 0.98 of the C.R.Bot has been released on the C.R.Bot page. This info comes from the fine bot loving folks at the  Quake2 Bot Epidemic, where they also have some info on the S.A.B.I.N. project, a bot author collective.

-- https://www.bluesnews.com/archives/jan98-4.html

Links:

* http://www.planetquake.com/crbot/
* http://www.quake2.com/epidemic/
* http://www.planetquake.com/botshop/sabin/index.html

Content of `crbot098.zip`:

```text
-rw-rw-r--  0 0      0       10953 27 Jan  1998 CRBOT/README.TXT
-rw-rw-r--  0 0      0      394752 27 Jan  1998 CRBOT/GAMEX86.DLL
drwxrwxr-x  0 0      0           0 15 Jan  1998 CRBOT/BOTS/
drwxrwxr-x  0 0      0           0 15 Jan  1998 CRBOT/BOTS/FEMALE/
drwxrwxr-x  0 0      0           0 15 Jan  1998 CRBOT/BOTS/MALE/
-rw-rw-r--  0 0      0      276272 15 Jan  1998 CRBOT/BOTS/FEMALE/TRIS.MD2
-rw-rw-r--  0 0      0      279552 15 Jan  1998 CRBOT/BOTS/MALE/TRIS.MD2
-rw-rw-r--  0 0      0         214 24 Jan  1998 CRBOT/DEATH.TXT
-rw-rw-r--  0 0      0         963 24 Jan  1998 CRBOT/FIGHT.TXT
-rw-rw-r--  0 0      0         740 24 Jan  1998 CRBOT/KILL.TXT
-rw-rw-r--  0 0      0         411 24 Jan  1998 CRBOT/PAIN.TXT
-rw-rw-r--  0 0      0         533 27 Jan  1998 CRBOT/BOTS.CFG
```

Readme header:

```text
Name of Mod : The C.R.Bot, for Quake II
File Name   : crbot098.zip
Version     : 0.98
Date        : January 27, 1998
Author      : Mike Malakhov
E-mail      : crbot@planetquake.com
              ww@pobox.com
Web Site    : http://planetquake.com/crbot
              http://www.pobox.com/~ww/bot.html
Build time  : < 100 hours
```

## v0.99

Released as `crbot099.zip`.

Mentioned on the CRBot homepage:

> 30 January, 1998:
>
> Not many new features are in v0.99, it's more like bugfix for v0.97. Hopefully, I fixed problem with bots getting stuck under water and in lava. New things: bots will try to avoid rockets and blaster/hyperblaster projectiles (the higher skill level, the better they suppose to avoid it). New var "bot_chat" for turning on/off kill/pain/death messages from bots. Couple of tweaks in shooting accuracy and decision code. Jumping and lava avoidance code still needs work.
> Next version is going to be released after "point release" from ID Software, and will feature even more advanced teamplay. I'm thinking to implement basic orders which you will be able to give to bots in your team. Like "cover me", or "guard this area", or "attack my target". Should be fun playing against other teams of bots with human as a commander, mastering your strategic skills as well as tactic.
> About supporting custom skins and models. You see, the problem is that bot model should have all skins listed inside, unlike all player models. This means you can't use custom player model for bot without modifications. That's why I had to include male/female model in archive together with mod -- I modified them so all skins are referenced from inside of model. As for skins -- I'm going to support Millennium's skin pack in next release.
> Reminder: before sending me e-mails with questions and bug-reports read FAQ page before. And don't forget to visit other bot pages (links on left panel), they have a lot of useful information for you.

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

Mentioned on BluesNews:

> Friday, January 30, 1998
>
> New C.R.Bot\
> Version 0.99 of the C.R.Bot for Quake II has been released on the C.R.Bot page. The new release is described as bug fixes rather than new features, and word there is the next release will be held off until after the Point Release. Thanks Prophet.

-- https://www.bluesnews.com/archives/jan98-4.html

Links:

* http://www.planetquake.com/crbot/

Content of `crbot099.zip`:

```text
-rw-rw-r--  0 0      0       11063 30 Jan  1998 CRBOT/README.TXT
-rw-rw-r--  0 0      0      396800 29 Jan  1998 CRBOT/GAMEX86.DLL
-rw-rw-r--  0 0      0      276272 15 Jan  1998 CRBOT/BOTS/FEMALE/TRIS.MD2
-rw-rw-r--  0 0      0      279552 15 Jan  1998 CRBOT/BOTS/MALE/TRIS.MD2
-rw-rw-r--  0 0      0         214 24 Jan  1998 CRBOT/DEATH.TXT
-rw-rw-r--  0 0      0         963 24 Jan  1998 CRBOT/FIGHT.TXT
-rw-rw-r--  0 0      0         740 24 Jan  1998 CRBOT/KILL.TXT
-rw-rw-r--  0 0      0         411 24 Jan  1998 CRBOT/PAIN.TXT
-rw-rw-r--  0 0      0         569 29 Jan  1998 CRBOT/BOTS.CFG
```

Readme header:

```text
Name of Mod : The C.R.Bot, for Quake II
File Name   : crbot099.zip
Version     : 0.99
Date        : January 30, 1998
Author      : Mike Malakhov
E-mail      : crbot@planetquake.com
              ww@pobox.com
Web Site    : http://planetquake.com/crbot
              http://www.pobox.com/~ww/bot.html
Build time  : > 100 hours
```

## v0.99a

Released as `crbt099a.zip`.

Mentioned on the CRBot homepage:

> 08 February, 1998:
>
> Well, it seems like Quake2's point release is still in "Real Soon Now" stage, so I decided to release another version of the bot before it. Several fixes and couple of new things:
>
> * fixed bot infinitely trying to get stuff through window;
> * fixed bot spinning while roaming the level;
> * fixed bot getting stuck if "weapons stay" option was enabled;
> * bot will try to avoid hurting members of its own team;
> * the very first command you can use to control bots in your team: "cmd team_help" -- it will summon all bots in your team which are not engaged in melee already;
> * couple of AI tweaks.

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

Mentioned on BluesNews:

> Monday, February 9, 1998
>
> Bots: New C.R.Bot/Oak Preview\
> The new C.R.Bot, version 0.99a, has been released on the C.R.Bot page. Also, there in an exclusive preview of the Oak II Bot up on Quake2 Bot Epidemic.

-- https://www.bluesnews.com/archives/feb98-1.html

**A copy of this release has not yet been acquired.**

## v0.99b

Released as `crbt099b.zip`.

Mentioned on the CRBot homepage:

> 13 February, 1998:
>
> In new version 0.99b I tried to make bot's behavior even more human-like. To name a few improvements:
>
> * bot won't see you if you happend to be hiding in dark spot
> * bot now has limited field of view (based on skill level of course)
> * bot will try to sneak up on you; I need to figure out couple of things before this behavior will be really efficient though
> * bot is listening to footsteps and explosion sounds and will try to go in their general direction
> * bot will try to avoid grenades
>
> And couple of fixes:
>
> * hyperblaster and rocket launcher aiming was broken, fixed
> * you won't get a frag for killing your team-mate
> * I'm still receiving complaints about bot with railgun being way too accurate -- well, after some pondering I decided to decrease damage on railgun instead of degrading bot's accuracy any further, we'll see if it work; don't worry this won't affect damage from railgun used by you
>
> Happy Friday The 13th :-)

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

**A copy of this release has not yet been acquired.**

## v0.99c

Released as `crbt099c.zip`.

Mentioned on the CRBot homepage:

> 14 February, 1998:
>
> Oops, teamplay in v0.99b was broken (bots were trying to attack members of their own team), I'm uploading fixed version 0.99c right now, enjoy. Thanks khudson for early bug-report.
> Also, I forgot to mention yesterday that chaingun and hyperblaster handling code was fixed to include starting and stopping delays, so bots will be on par with normal player.
>
> If you ever wondered what other projects I'm doing besides CRBot, go check out this demo.

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

> Saturday, February 14, 1998
>
> New C.R. Bot (Updated)\
> Version 0.99c of the C.R.Bot has been released on the CRBot official homepage, fixing the teamplay problem in version 0.99b (thanks Plucky). The changes in 0.99b are bugfixes and several enhancements to make the bot act more human, including:
>
>> bot won't see you if you happen to be hiding in dark spot
>> bot now has limited field of view (based on skill level of course)
>> bot will try to sneak up on you; I need to figure out couple of things before this behavior will be really efficient though
>> bot is listening to footsteps and explosion sounds and will try to go in their general direction
>> bot will try to avoid grenades

-- https://www.bluesnews.com/archives/feb98-2.html

Content of `crbt099c.zip`:

```text
-rw-rw-r--  0 0      0       11209 14 Feb  1998 CRBOT/README.TXT
-rw-rw-r--  0 0      0      398848 14 Feb  1998 CRBOT/GAMEX86.DLL
-rw-rw-r--  0 0      0      276272 15 Jan  1998 CRBOT/BOTS/FEMALE/TRIS.MD2
-rw-rw-r--  0 0      0      279552 15 Jan  1998 CRBOT/BOTS/MALE/TRIS.MD2
-rw-rw-r--  0 0      0         214 24 Jan  1998 CRBOT/DEATH.TXT
-rw-rw-r--  0 0      0         963 24 Jan  1998 CRBOT/FIGHT.TXT
-rw-rw-r--  0 0      0         740 24 Jan  1998 CRBOT/KILL.TXT
-rw-rw-r--  0 0      0         411 24 Jan  1998 CRBOT/PAIN.TXT
-rw-rw-r--  0 0      0         569 29 Jan  1998 CRBOT/BOTS.CFG
```

Readme header:

```text
Name of Mod : The CRBot, for Quake II
File Name   : crbt099c.zip
Version     : 0.99c
Date        : February 14, 1998
Author      : Mike Malakhov
E-mail      : crbot@planetquake.com
              ww@pobox.com
Web Site    : http://planetquake.com/crbot
              http://www.pobox.com/~ww/bot.html
Build time  : ~120 hours
```


## v0.99d

Released as `crbt099d.zip`.

Mentioned on the CRBot homepage:

> 2 March, 1998:
>
> Ok, enough waiting. I decided to release new version of the bot compatible with Quake2 v3.13 using hack by -Byron, since I have no other choice -- looks like guys from ID Software just do not care to release new sources. This could be really unstable version because of that, but lets hope it won't.
> Biggest change from last version: bot is using client slots now. That means you can use any model and any skin for bot, and that bots will follow you through map changes. That also means you will have to update your .cfg files by using full name of the skin instead of just number for bot_skin variable. And instead of bot_male use bot_model, by default it's set to "male".
> Also I messed around with lava code again, tell me if I finally fixed that problem with bot getting stuck in lava sometimes. That's pretty much all for now.

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

Mentioned on BluesNews:

> Tuesday, March 3, 1998
>
> New C.R.Bot\
> Version 0.99d of the C.R.Bot has been released on the C.R.Bot page featuring the now famous "hacked" 3.13 support (courtesy of Wonko the Sane). Thanks Prophet.

-- https://www.bluesnews.com/archives/feb98-4.html

Links:

* http://planetquake.com/crbot/news.html
* http://quake.hype.com/mods/


Content of `crbt099d.zip`:

```text
-rw-rw-r--  0 0      0       10193  2 Mar  1998 CRBOT/README.TXT
-rw-rw-r--  0 0      0      400384  2 Mar  1998 CRBOT/GAMEX86.DLL
-rw-rw-r--  0 0      0         654  2 Mar  1998 CRBOT/DEATH.TXT
-rw-rw-r--  0 0      0        1877  2 Mar  1998 CRBOT/FIGHT.TXT
-rw-rw-r--  0 0      0        1566  2 Mar  1998 CRBOT/KILL.TXT
-rw-rw-r--  0 0      0        1077  2 Mar  1998 CRBOT/PAIN.TXT
-rw-rw-r--  0 0      0         765  2 Mar  1998 CRBOT/BOTS.CFG
```

Readme header:

```text
Name of Mod : The CRBot, for Quake II
File Name   : crbt099d.zip
Version     : 0.99d
Date        : March 2, 1998
Author      : Mike Malakhov
E-mail      : crbot@planetquake.com
              ww@pobox.com
Web Site    : http://planetquake.com/crbot
              http://www.pobox.com/~ww/bot.html
Build time  : ~130 hours
```

## v0.99e

Released as `crbt099e.zip`.

Perhaps mentioned on the CRBot homepage:

> 3 March, 1998:
>
> Well, apparently hack I used in making CRbot compatible with v3.12/v3.13 isn't working for all of you -- I have several reports about Quake2 crashing during level load. I guess we'll have to wait for proper sources, I just hope guys from ID do release them soon.

And:

> 4 March, 1998:
>
> Finally source code for Quake2 v3.14 has been released and now I can make proper conversion of CRbot! Absolutely no new changes from last version, I just want to make sure that bot is fully compatible with all changes in new patch. Write me if you notice anything wrong. Except one thing -- regardless of model type all bots are using male sounds. I'll fix it as soon as I figure out how to tell Quake server to use model-specific sounds.
> Almost forgot: commands addbot, addbots and killbot are server-only now and hence should be prefixed with sv instead of cmd. For instance, type "sv addbots 4..8 5" to create five bots with randomly selected skills from 4 to 8.

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

Mentioned on BluesNews:

> Wednesday, March 4, 1998
>
> Newer C.R.Bot\
> Version 0.99e of the C.R.Bot, still Quake II 3.13 compatible, via the "hack," has been released on the C.R.Bot Page fixing a crashing problem in version 0.99d.

-- https://www.bluesnews.com/archives/feb98-4.html

**A copy of this release has not yet been acquired.**

## v1.0

Released as `crbot10.zip`.

Mentioned on the CRBot homepage:

> 5 March, 1998:
>
> Looks like v1.0 is pretty stable and fully compartible with v3.13 and v3.14. I've got reports about two problems though. First one is that on some systems Quake2 somehow loses CRbot's .dll and you can't access bot's menu or use sv addbots/sv addbot commands, it just says "unknown server command" and nothing happens. Second problem is that sometimes scores are not updated correctly if your are playing with teams. I'm trying to reproduce these problems on my machine, but meanwhile if you know what exactly causes them (like you had the problem but eventually figure out how to avoid it) please e-mail me.

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

Mentioned on BluesNews:

> Thursday, March 5, 1998
>
> New C.R.Bot\
> A fully Quake II 3.14 compatible C.R.Bot version 1.0 has been released on the C.R.Bot Page

-- https://www.bluesnews.com/archives/feb98-4.html

**A copy of this release has not yet been acquired.**


## v1.01

Released as `crbot101.zip`.

Mentioned on the CRBot homepage:

> 6 March, 1998:
>
> It seems like problem with Quake2 "losing" CRbot's .dll is a bug in Quake2 itself. I managed to repeat it with all mods I have which are compatible with v3.14. It happens even with CTF from Zoid! So, if someone can remind me where to report bugs in Quake2? Anyway, I found a neat work-around for that bug, so get v1.01, it should work now. Not much new stuff besides bug-fixes -- messed around with swimming code a little bit and improved bot's menu: now you can choose model and skin name from there. Still can't figure out how to use model specific sounds (e-mail me please if you know the way), so please don't complain about male sounds for cyborg/female, etc. -- I know about it.

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

Mentioned on BluesNews:

> Sunday, March 8, 1998
>
> New C.R.Bot\
> Version 1.01 of the C.R.Bot is up on the C.R.Bot page, working around a bug that the author believes is actually a Quake II bug.

-- https://www.bluesnews.com/archives/march98-1.html

**A copy of this release has not yet been acquired.**


## v1.02

Released as `crbot102.zip`.

Mentioned on the CRBot homepage:

> 9 March, 1998:
>
> Advanced teamplay is here! In addition to cmd team_help command (which has been slightly improved too) now you can use cmd team_group. It will force all "spare" bots in the team to follow you in tight formation. To dismiss them use cmd team_free. Next I plan to add another two commands: cmd team_guard and cmd team_ambush.
> I've received a lot of e-mails asking about CTF support. Honestly speaking I'm not quite eager to implement it in near future. It's a lot of additional work, even without grappling hook support. So, maybe someday if I get bored I'll do it, just don't expect it in next couple of weeks -- I still have plenty of stuff to do with bot besides CTF support.

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

Mentioned on BluesNews:

> Monday, March 9, 1998
>
> C.R.Bot\
> The C.R.Bot du jour is version 1.02. Apparently the Quake II 3.14 bug he is working around is not a bug, but rather an additional check to ensure the CD is in the drive while you play. Thanks William Hooper.

-- https://www.bluesnews.com/archives/march98-1.html

**A copy of this release has not yet been acquired.**


## v1.03

Released as `crbot103.zip`.

Mentioned on the CRBot homepage:

> 15 March, 1998:
>
> Couple of things were broken in v1.03, so here goes bug-fixed v1.04. Also I forgot to mention that there's new var bot_menu. You can set it to 0 if you don't want bot menu. Useful for dedicated servers.
>
> New things in v1.03:
>
> * sounds are fixed; it was pretty tough problem actually and I had to rewrite couple of major routines;
> * cmd team_free is fixed; it also accepts bot name as a parameter now, in case if you want to dismiss just one bot from his duties;
> * improved swimming;
> * bots should use ladders now; needs a lot of improvement though;
> * two new commands to control your team: cmd team_guard and cmd team_patrol; if no bot name specified after the command then all bots happend to be in front of you will obey this order;
> * some AI tweaking...
>
> Support for visible weapons will be in next version, I just didn't have time for it.

-- [http://www.planetquake.com/crbot/old.html](https://web.archive.org/web/19990224220602fw/http://www.planetquake.com/crbot/old.html) (archived)

Mentioned on BluesNews:

> Sunday, March 15, 1998
>
> C.R.Bot\
> Version 1.03 of the C.R.Bot is available on the C.R.Bot homepage, not featuring visible weapons support, which is almost newsworthy in these days of increasingly universal support for Hentai's VWep mod. Never fear, VWep is promised for the next release.

-- https://www.bluesnews.com/archives/march98-2.html

**A copy of this release has not yet been acquired.**


