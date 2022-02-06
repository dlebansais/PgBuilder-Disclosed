# PgBuilder

A tool to optimize gear for a character of the Project: Gorgon MMORPG. You can download the latest version (for client 357) [here](https://github.com/dlebansais/PgBuilder-Disclosed/releases/download/v1.1.357.1049/PgBuilder.exe).
There are also some [release notes](https://github.com/dlebansais/PgBuilder-Disclosed/blob/master/ReleaseNotes.md).

Please don't ignore the Bug Report section at the end!

## Purpose

This application can be used to simulate a build based on two skills, various gear items and their mods.

## Requirements

This tool no longer require [PgJsonParse](https://github.com/dlebansais/PgJsonParse/releases), but if you don't use it, icons will take some time to download.

## Skills and abilities

When you select a skill, all abilities on the corresponding line are replaced with default ones. Click on the ability you want to change the select another.

## Gear

At the bottom of the application Window, select a slot and for this slot:

+ You can select an item that you will equip, if you want to work with a specific item.
+ You can add mods with the corresponding button. Mods come from any of the selected skills, and in addition to them generic mods can be selected.

## Buffs

You can add up to 10 buffs with the `Add Buff` button (damage potions, for instance). Corresponding effects are taken into account when abilities are displayed.

## View mode

In small view mode (the default), pass the mouse over an ability and this will display it with all mods taken into account. The view should be similar, and most often equal to what you would see in game.

In large view mode, all abilities are displayed directly. This mode requires a pretty large screen.

## Saving and loading builds

In the top-right corner, use the `Save...` and `Load...` buttons to save and reload your builds in text files. For the name I suggest the two abbreviated skill names separated with a hyphen, followed by any suffix you like. For example `Psy-AH.txt`.

## Bug report

Before submitting a bug report, please check the know issue section at the end. Also make sure that you don't have a buff, like a Calligraphy buff, that would change the build result. To be sure of that you can simply un-equip everything, and the ability for which there is a bug should be displayed in game with only white text.

To submit the bug:

+ Make a screenshot in game of the ability. You can edit the screenshot to only keep the ability window.
+ Make a zip file with the screenshot file and the build text file for PgBuilder.
+ [Create a new issue](https://github.com/dlebansais/PgBuilder-Disclosed/issues/new) (login required) or send me an email, and attach the zip file.

### Know issues

+ Knife Fighting
  * Off-Hand/Neck
    - *Indirect Trauma and Poison damage +% when Knife-Fighting skill is active*: the result can differ by less than 0.5% due to what is probably a display bug in game.
