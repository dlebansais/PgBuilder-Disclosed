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
