# [TF2] Gamemode Manager
Gamemode and Map Chooser, RTV for NativeVotes.


AlliedModders link

## Installation
Download latest realese

Install .smx plugin into your plugins folder

``tf\addons\sourcemod\plugins``

Install .cfg file into:

``tf\cfg\sourcemod``

if you want to use plugin's full functions 

create next folders:

you will keep maplists there:

``tf\cfg\sourcemod\gamemode_manager``

you will create exec .cfg files there:

``tf\cfg\sourcemod\gamemode_manager\loader``

for Map configs (1.3) plugin

``tf\cfg\sourcemod\map-cfg``

if you want to load plugins on specific gamemodes:

tf\addons\sourcemod\plugins\disabled

you must use disabled folder, it will be used for plugin loading

* storing plugins in disabled folder will prevent auto-loading them on mapchange

## Setup

realese archive will come with examples only

you must configurate plugin by yourself

edit config file: gamemode_manager.cfg

create example_maps.txt in gamemode_manager

create exec file: exapmle_load.cfg in gamemode_manager

## REQUIRED DEPENDENCIES
nativevotes.smx

nativevotes_mapchooser.smx

## OPTIONAL DEPENDENCIES
(must have)

"Map configs" (1.3) by Berni

https://forums.alliedmods.net/showthread.php?t=69506

## Config ConVars

``sm_gmvote_timeleft 8`` when to start vote, when mp_timelimit set non-zero (def 8)

## Commands
check gamemode_manager.sp for commands
``sm_gmvote`` 

start Gamemode Vote then Start Map Vote

## For Compiling

sourcemod.inc

sdktools.inc

nativevotes.inc
