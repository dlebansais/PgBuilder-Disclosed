# 2.0.447.1161
Update to client 447 (Jan 17th 2026).

# 2.0.439.1161
Enabling the check for update feature would crash the app. This has been fixed.

# 2.0.439.1160
+ Update to client 439 (Nov 13th 2025)
+ This is also a new version targeting .NET 8. You can download the full, self-contained file, or the short file but you might also have to install the .NET Runtime, link [here](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-8.0.22-windows-x64-installer).

# 1.1.435.1156
Update to client 435 (September 12, 2025).

# 1.1.430.1156
Update to client 430 (June 09, 2025).

# 1.1.426.1156
Update to client 426 (Apr 03, 2025).

# 1.1.421.1156
Update to client 421 (Feb 26, 2025).

# 1.1.411.1156
Update to client 411 (Aug 13, 2024).

# 1.1.409.1156
Update to client 409 (July 30, 2024).

# 1.1.406.1156
Update to client 406 (June 20, 2024).

# 1.1.404.1134
Update to client 404 (March 12, 2024).

# 1.1.399.1132
Update to client 399 (December 7, 2023).

Includes the new profile data : if a mod cannot appear on an item, there is a strikethrough mark on both the item and the mod.

# 1.1.397.1114
Update to client 397 (November 17, 2023).
Multiple bug fixes and (most likely) new bugs added...

# 1.1.394.1114
Update to client 394 (August 12, 2023).

The following skills have been reviewed, and many bugs fixed for them:

+ Animal Handling
+ Bard
+ Battle Chemistry
+ Cow
+ Deer
+ Druid
+ Spider
+ Sword

# 1.1.392.1106
Update to client 392 (July 20, 2023).

# 1.1.391.1103
Update to client 391 (July 6, 2023).

# 1.1.387.1061

Update to client 387 (June 10, 2023).

# 1.1.386.1061

Update to client 386, June 1 2023.

# 1.1.385.1061

Update to client 385 (April 11 2023).

# 1.1.382.1061

Update to client 382 (March 11 2023). Also include a fix for settings that were not preserved in some cases.

# 1.1.378.1060

Update to client 378 (Jan 17 2023).

# 1.1.374.1060

Update to client 374 (Nov 15 2022).

# 1.1.369.1060

Update to client 369 (October 10 2022).

# 1.1.367.1060

Update to client 367.

Also includes a couple fixes for Song of Discord, though the numbers probably don't match what's in game anyway. The song itself looks bugged.

# 1.1.365.1059

Update to client 365 and some glitch fix.

# 1.1.364.1059

This build includes:
+ The changes from game files version 364 (June 10 2022 rebalancing).
+ A revamp of the GUI to make it more compatible with browsers.
For people not using Windows this program can also be run from [the gorgonapps](https://gorgonapps.github.io/) site.

# 1.1.360.1050

Update to client 360 (Mar 16, 2022).

# 1.1.358.1049

Update to client 358 (Feb 9, 2022).

# 1.1.357.1049

Update to client 357 (Feb 2, 2022).

# 1.1.356.1049

Update to client 356 (Dec 24, 2021).

# 1.1.352.1048

Update to client 352 (Halloween) (Oct 16th, 2021).

# 1.1.351.1045

Update to client 351 (Oct 5th, 2021).

# 1.1.348.1043

Update to client 348 (June 30th, 2021).

# 1.1.342.1040

Update to client 342 (March 25th, 2021).

# 1.1.341.1039

There was a random crash when using basic attacks and the organic armor set that has been fixed.

# 1.1.341

Update to client 341.

# 1.0.0.1008

Update to client 340.

# 1.0.0.988

Update to client 339.

# 1.0.0.987

When selecting an ability with the left button mouse, the wrong ability would be replaced, depending on how the menu is displayed (to the left or to the right of the mouse). This has been fixed.

# 1.0.0.985

+ Update to client 338.
+ Added candle buffs.
+ Fixed a bug in the code checking for updates.

# 1.0.0.983

Update to client 337.

# 1.0.0.944

This release includes many improvements:

+ The loading time, from click to the window popping, has been improved.
+ Support for checking if a new release is available.
+ Better processing and more accurate information about client v336. Spirit Fox mods for instance.
+ Support for updating the taskbar shortcut, if any, with an icon from the game.
+ Several bug fixes. There remains a known issue with mods acting on a pet Basic Attack.

# 1.0.0.925

This version includes the v336 files (with Spirit Fox added).

# 1.0.0.895

This version includes changes made behind the scene.
Also include a fix in one of the Tough Hoof mods.

# 1.0.0.881

This version no longer depends on pgjsonparse. The trade-off is that it's slightly slower to load, but this will be optimized in the future.

Also include:
+ Mods that change damage type are now evaluated before other mods, not in the middle.

# 1.0.0.724

This version includes a new feature: one can add buffs and see how this affects abilities.
+ Limited to 8 buffs
+ Preliminary, I need to double-check that every buff is handled properly.

# 1.0.0.632

This version only works with cache file from version 335.

In addition to this update, it includes:
+ One can load more than one file at the same time. This is to make comparison easier between slightly different builds. Make sure you save any change before switching!
+ Icons everywhere
+ New way to select mods. You can reorder selected mods using drag & drop, but not drag a mod from the pool (yet).
+ Item view. This duplicates the bottom part of the application, but you can see all items at once.
+ Image capture: right-click an ability or an item (in the item view).
+ The item tooltip now displays mods.

# 1.0.0.292

+ Fixed some parsing issue with mods that modify the dot damage.
+ Fixed special values that have both a delta and a mod.
+ Improved the display of combat sub-skills.
+ Fixed abilities that damage armor.
+ Fixed a Rotskin mod.
+ Fixed ammo that sometimes don't show.
+ Fixed mods that apply damage after a delay.

# 1.0.0.265

+ Fixed random damage when the min is 1.
+ Added support for cloth enhancement damage.
+ Removed the special case for Fireball.
+ Improved support of mods that activate when hit.
+ Always select the last tier of a new mod.
+ Improved selection of mods.

# 1.0.0.214

+ Moved all values to float to avoid some rounding issues.
+ Included mods that directly damage health in the damage formula.
+ Removed basic attack lines with 0.
+ Fixed mods dealing random damage with a min > 1.
+ Added a damage formula that works only for Fireball and Frostball.
+ Parsing "however" the same as "but".
+ Fixed a couple mods that didn't parse right.

# 1.0.0.165

+ Updated the DoT formula.
+ Moved fairy character and lore level to the build file.
+ Fixed indirect fire damage that would increase even if the damage mod is not fire.
+ Improved display of special effects with very long preface text.
+ Fixed mods with 'but' in their text.
+ Fixed a crash  when pgjsonparse has not been ran before the builder.

# 1.0.0.115

+ First beta version for client 334.
