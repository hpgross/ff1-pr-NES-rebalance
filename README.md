# ff1-pr-NES-rebalance

A NES Rebalance Mod for FF1 Pixel Remaster

The goal of this mod is to document the formulas used for both the Pixel Remaster and the NES releases, and to make a modification to make the former similar to the latter. In situations where game balance is off, I would consider Final Fantasy Restored as a guide towards what the goal should be.

The main things this mod updates are the exp tables to match the old growth rates, and the growth curves to give spell charges at lower levels since you level up much more slowly. It also puts HP levels back to the NES levels.

Note: Going forward this mod will require Magicite; the Memoria version is deprecated.

Installation instructions:

1. Download BepInEx Loader: <https://github.com/BepInEx/BepInEx/releases/download/v6.0.0-pre.2/BepInEx-Unity.IL2CPP-win-x64-6.0.0-pre.2.zip> and Magicite: <https://github.com/Silvris/Magicite/releases/tag/v2.2.0>
2. Extract to the root of your game install.
3. Run your game + close it.
4. Navigate to:  InstallDir\FINAL FANTASY_Data\StreamingAssets, create a Magicite folder and paste the contents of the Magicite folder inside.
5. Launch the game again and the changes will be applied automatically

If you only want the character stat changes, and want to leave bosses as they were, do not include monster.csv. If you don't want the item price/healing changes, do not include item.csv, armor.csv, ability.csv, or weapon.csv.

Current plans:

COMPLETED

- Original EXP/stat growths
- Monster stats
- Prices of items and magic restored to original values
- Potions only heal 30 HP, and hi-potions only heal 100 HP

TO DO

- PRIORITY Change descriptions for Potion/Hi-Potion to reflect new healing rates
- Attack/magic calculations closer to the original
- Make Blind/Sleep worthwhile
- Optionally disable sale of all healing items but Potion, Antidote, Gold Needle
- Re-add monster scripts for their AI
- Change ressurection prices at churches
- Optionally change items in chests back to original contents

Credits:

randyrobbinsmusic for the item price changes
brazilrules for updating the mod for Magicite usage
gvdn for identifying a bug SE introduced in 1.20 and developing a fix