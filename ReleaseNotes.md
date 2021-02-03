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
