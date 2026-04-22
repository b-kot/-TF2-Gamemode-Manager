# [TF2] Gamemode Manager
Gamemode and Map Chooser, RTV.

plugin also can be user for map categories

Will be realesed soon...

Gamemodes attributes:

* weight (chance to appear in vote)
* players (min. players to appear in vote)
* maplist (gamemode specific maplist)
* gm_config (optional, rewrite map configs, map-configs plugin required)

Read full guide:

AlliedModders link here

Compiled with Sourcemod 1.13.0-7298, Metamod 1.12.0-1219

## Installation

Full Installation instructions will come with realese file

Download latest realese: link here

Install .smx plugin into plugins folder: ``tf\addons\sourcemod\plugins``

Install .cfg file into: ``tf\cfg\sourcemod``

Go to and download REQUIRED DEPENDENCIES and OPTIONAL DEPENDENCIES

create next folders:

you will keep maplists there:

  ``tf\cfg\sourcemod\gamemode_manager``

you will create exec .cfg files there:

  ``tf\cfg\sourcemod\gamemode_manager\loader``

for Map configs (1.3), create folder:

  ``tf\cfg\sourcemod\map-cfg``

if you want to load plugins on specific gamemodes

you must use ``disabled`` folder, it will be used for plugin loading

``tf\addons\sourcemod\plugins\disabled``

* storing plugins in ``disabled`` folder will prevent auto-loading them on mapchange

## Setup instructions

Full Setup instructions will come with realese file

realese archive will come with examples only

you must configurate plugin by yourself

edit config file: gamemode_manager.cfg

create example_maps.txt in gamemode_manager

create exec file: exapmle_load.cfg in gamemode_manager

## REQUIRED DEPENDENCIES
``nativevotes.smx``

``nativevotes_mapchooser.smx``

download sourcemod-nativevotes-updated, sapphonie's fork from powerlord's NativeVotes 

https://github.com/sapphonie/sourcemod-nativevotes-updated?ysclid=moadv8bdbp687227959

## OPTIONAL DEPENDENCIES (must have)

"Map configs" (1.3) by Berni

https://forums.alliedmods.net/showthread.php?t=69506

## Config ConVars

``sm_gmvote_timeleft 8``, when to start vote, when mp_timelimit set non-zero (def 8)

...

## Commands

``sm_gmvote``, start Gamemode Vote then Start Map Vote

...

## For Compiling

sourcemod.inc

sdktools.inc

nativevotes.inc
