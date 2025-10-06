# Heir Decider Stellaris Mod

## Table of Contents

- [Introduction](#introduction)
- [Launch](#launch)
- [Version](#version)
- [Features](#features)
- [Known Bugs](#known-bugs)
- [Version History](#version-history)

## Introduction

This repository stores code for a mod (modification) for the video game 'Stellaris.' In general, it is a 4x space strategy game. While you do not need to know more to attain a basic understanding of this mod, more information about the game can be found [here](https://www.paradoxinteractive.com/games/stellaris/about)

First, I'll introduce the problem this mod seeks to solve. In a game of stellaris, you get to design your empire, and one of the options you can choose is your empire's government type. One such type is imperial, and a unique property of it is that it has an heir, a leader that the game spawns of a random class whenever the empire finds itself without an heir.

The problem is the player has no control of the class of this leader. In Stellaris, there are three different leader classes: scientists, officials, and commanders. So, if the heir spawns as an undesireable leader class, there is currently nothing the player can do about this. Leaders cost resources to maintain, so not having control over the heir leader type is actually a significant problem for imperial empires. When this mod was first written, commanders didn't exist and admirals and generals existed instead. Generals were considered very bad to have, especially early in the game. The issue of 'rolling' a general is the main reason why I wrote this mod to begin with.

This mod solves this issue by giving the player choice over the type of leader their heir will be. I will go into more details of the solution in the features section.

## Launch

To actually use this mod, you must obviously have a copy of Stellaris. 

The easiest way to install this mod is through the steam workshop. You can access the steam workshop page [here](https://steamcommunity.com/sharedfiles/filedetails/?id=2977239553). This method only works if your copy was acquired through steam. 

Depending on your version, the steps you take may differ greatly, but in general, each version of the game has two directories: one for the .mod file, and one for the mod directory itself. You will need to move the .mod file and the heir_decider directory into the appropriate locations, then open the .mod file (any text editor will suffice) and edit the path field to the path of the mod directory. For more help and information, [the stellaris wiki](https://stellaris.paradoxwikis.com/Mods) is a great resource for learning more about mod installation and about stellaris modding in general.

## Version

The original mod was written for version 3.8.2 of Stellaris. As such, there is no guarantee that it will not break as vanilla files and directory structures may change between versions. I will keep this mod up to date and working for the foreseeable future, and the version status of the mod will be posted on [the steam workshop page](https://steamcommunity.com/sharedfiles/filedetails/?id=2977239553).

## Features

The mod is quite simple. For every empire, there is always a 'policies' menu. With this mod, there is now a new feature called 'Heir Leader Type'. The policy is a list of four radio buttons. Picking one will set a flag denoting what type of leader the next heir should be. Whenever a new heir is created, a new event will run that sets the leader type to that of the selected radio button.

## Version History

- v 1.0: This is the initial launch version of the mod.
- v 1.1: Updated version that fixes a few edgecase bugs. In particular, the mod is now compatible with Crusader Spirit and Heroic Tales civics. This version also adds another option to the policy to allow for no preference (vanilla behavior).
- v 1.1.1: Updated for version 3.8.3. Renamed a lot of files in the mod, too.
- v 1.1.2: Updated for version 3.8.4.
- v 1.1.3: Updated for version 3.9.
- v 1.2: Updated for version 3.12.*. This is the first version since the leader rework to scientist, officials, and commanders.
- v 1.2.1: Fixed an error in the localisation.
- v 1.2.2: Updated for version 4.0.x.