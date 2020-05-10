# PgBuilder

A tool to optimize gear for a character of the Project: Gorgorn MMORPG. You can download the latest version (334) [here](https://github.com/dlebansais/PgBuilder-Disclosed/releases).
There are also some [Release notes](https://github.com/dlebansais/PgBuilder-Disclosed/blob/master/ReleaseNotes.md).

## Requirements

This tool can only work with a cache file prepared with the [PgJsonParse](https://github.com/dlebansais/PgJsonParse/releases) application. If you haven't used it already, please follow these steps:

+ Download the .exe file linked above, and run it.
+ Select version 334 (this should be the latest version) and download it.
+ During download, make sure the "Load version fast" check box is checked, this will create the cache file.
+ Once the cache has been created, PgBuilder can be run, and it will locate the cache file automatically.

## Purpose

This application can be used to simulate a build based on two skills, various gear items and theirs mods.

## Skills and abilities

When you select a skill, all abilities on the corresponding line are replaced with default ones. Click on the ability you want to change the select another.

## Gear

At the bottom of the application Window, select a slot and for this slot:

+ You can select an item that you will equip, if you want to work with a specific item.
+ You can add mods with the corresponding button. Mods come from any of the selected skills, and in addition to them generic mods can be selected.

## View mode

In the swmall view mode (the default), pass the mouse over an ability and this will display it with all mods taken into account. The view should be similar, and most often equal to what you would see in game.

In the large view mode, all abilities are displayed directly. This mode requires a pretty large screen.

## Saving and loading builds

In the top-right corner, use the `Save...` and `Load...` buttons to save and reload your builds in text files. For the name I suggest the two skill abbreviated names separated with a hyphen, followed by any suffix you like. For example `Psy-AH.txt`.

## Bug report

Before submitting a bug report, please check the know issue section at the end. Also make sure that you don't have a buff, like a Calligraphy buff, that would change the build result. To be sure of that you can simply un-equip everything, and the ability for which there is a bug should be displayed in game with only white text.

To submit the bug:

+ Make a screenshot in game of the ability. You can edit the screenshot to only keep the ability window.
+ Make a zip file with the screenshot file and the build text file for PgBuilder.
+ [Create a new issue](https://github.com/dlebansais/PgJsonParse/issues) and attach the zip file.
