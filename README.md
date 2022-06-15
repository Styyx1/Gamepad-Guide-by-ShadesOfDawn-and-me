# Gamepad Support and Setup Guide - V3.0

## Acknowledgements

This guide would not exist if not for the many hours of work put in by several individuals across different discord servers.

Original version created by ShadesofDawn. Updated version maintained by Styyx and ShadesofDawn. Information originally compiled by *Gamepad Helpers Team* from Sovn’s Skyrim and The Animonculory. Reformatted by Althro for greater markdown support.

## Abstract

The following guide is designed to bring controller functionality to your chosen modlist. It aims to offer an experience where you do not need a keyboard and mouse and is universal for DualShock/Sense and Xbox.

Please treat this guide as a mini modlist and read all the information contained in it. Please direct any questions or issues to us (Styyx and ShadesofDawn) in The Animonculory Server. Do not report issues to the curators of the your chosen modlist or the authors of the mods in this guide.

## Installation process

Before beginning, you need to make sure that your control layout is not changed from default. To do this, complete the following:
1.	Navigate to your Skyrim Directory (\steamapps\common\SkyrimSpecialEdition)
2.	Look for a file named `ControlMap_Custom.txt`. If it is present, delete it. If it is not, move on to the rest of the guide.

### Required Mods & Files

We utilise three mods to manage and control the game via the gamepad and add additional functionality. These are as follows: 

1. [The Ultimate Control Scheme [TUCS]](https://www.nexusmods.com/skyrimspecialedition/mods/29381?tab=files) -  The basis for controller compatibility, tucs opens up additional hotkeys on your controller. **Note:** TUCS does change the button layouts significantly so it will take a little time to get used to.

2. [iEquip](https://www.nexusmods.com/skyrimspecialedition/mods/27008?tab=files) acts as your HUD so you can see what is equipped quickly at a glance without referencing the quick menu or your inventory. It also adds the ability to hotkey potions. **WARNING!** This mod has two different versions. Ensure you select the **correct version** for the lists you play. Version means SE or AE. **SE = Skyrim 1.5.97; AE = Skyrim 1.6.xxx**

3. [Serio’s Cycle Hotkeys](https://www.nexusmods.com/skyrimspecialedition/mods/27184?tab=files) is the primary hotkey mod that allows you to control shouts, powers, spells, and equipment via the hotkeys introduced with TUCS.

If the list you are using does not include these mods, download and install all that you are missing. **WARNING! Do not ask the list author for support as you have now modified the list. Direct all questions/issues to the maintainers of this guide.**

Once you have downloaded/activated the mods listed above, download the [patched control layout for TUCS](https://github.com/chri3i/Gamepad-Guide-by-ShadesOfDawn-and-me/raw/main/The%20Ultimate%20Control%20Scheme%20-%20Recharging%20Enabled.7z) and install it as a seperate mod after TUCS in Mod Organizer 2 left pane. Nothing should be overwriting the mods. If somethings is, move it lower in priority on the left hand side.

## Mod Configuration Menu (MCM) Configuration

**Before continuing this part, ensure that any pre-existing MCM menus that are present in your list of choice have been completed. Do not complete any Hotkey options that are listed as they are made with keyboard in mind.**

### Serios Hotkeys

Set the mod to use `Default hotkeys` and the `HotKey Setter Button` to the **left D-Pad**. Your setup should look the same as the picture below.

![Serio's Cycle Hotkeys MCM setup](https://i.imgur.com/141QCug.png)

### iEquip

If you installed the pre-made profile, go to profiles, select the pre-made preset and load it. 

Else, Complete the following:

- Set the `Cycle Shouts/Powers` to `UP` on the D-Pad.
- Set `Cycle Consumables` to `DOWN` on the D-Pad.
- Disable Poisons
- Set `Consumables` to `RIGHT` on the D-Pad.

Your MCM should look the same as the pictures given below.

![iEquip Picture One](https://i.imgur.com/9MfuPs3.png)

![iEquip Picture Two](https://i.imgur.com/N7VJIAI.png)

If you wish to adjust the hud layout, you will need to enter the edit mode. There are presets present for you to load, however you can create your own. The mode comes with tooltips to help in the creation.

### SkyUI

Under `Controls` change Previous Column to `<--` and Next Column to `-->`.

## Making it Work

There are a few things to bear in mind with this setup. 

- You will not be able to use keyboard hotkeys with your controller connected.
- Should you disconnect your controller, your game may encounter errors such as the controller not working or the game crashing. Therefore, either use a cable or make sure your controller is charged.

### Setting up Serio's

***Note**: Once this is setup, you cannot use the D-Pad to navigate dialogue or inventory/spell menus. You will need to use the left joystick.*

To set up a cycle in Serio's, complete the following.

- Equip what you wish to save as a hotkey preset. You have the option to save all at once or just one slot at a time, however you must have it equipped. This can also be done from inside the inventory window.
- Press the `setter key`. This will open a menu prompting you to select a hotkey. 1 to 4, in order, will be `LB + X/Y/B/A` or `LB + Square/Triangle/O/X` and 5-8., in order, will be `RB + X/Y/B/A` or `RB + Square/Triangle/O/X`. Select 1 and press `B` or `O` to exit our of the menu and enter the Cycle creation window.
- Scroll down to `Cycle 1` and press `B` or `O`.
- A third window will then open to store your equipment. You can select all, or select one at a time. Once you have saved what you wish to, press `B` or `O` to finish. 
- Repeat the process for however many setups you wihs to have.

You can change cycles in previously setup hotkeys and have up to 8 different cycles. 

### iEquip

As mentioned before, the HUD display from iEquip can be customized to suit what you want. The default key to change this is `K` which loads the menu. A configuration file is included as part of the package we provice here if you wish to use it.

### Engarde.

**This doesn't work when the modlist also has the mod 'Auto Input Switch'**

To get the dodge function working with gamepads, a program which mimics the `WASD` keys is required. It is recommended to use [Antimicro](https://antimicro.en.softonic.com/) as it is a free program and one we have tested to make sure it works. The Antimico setup should look similar to the picture below.

![Antimicro setup](https://i.imgur.com/ngnq45z.png)

## An Example of a setup

Given below is an example of the hotkey setup that ShadesofDawn uses on his spellsword type character with an xbox controller. Note that this is just an example and your own setup may be quite different to this.

### iEquip D-Pad Hotkeys

- `UP` - Shouts
- `Down` - Consumables including potions and food/water
- `Right` - Use consumable

### Serio’s

- `Left Bumper + X` - Melee set.
- `Left Bumper + A` - Ranged weapon.
- `Left Bumper + Y` - Offensive Magic.  Single Cast in the left hand on a single press, Duel Cast on a double press.
- `Left Bumper + B` - Healing Magic. Single Cast/Duel Cast like the offensive spell.
- `Right Bumper + X` - Additional Offensive Magic - Single Cast.
- `Right Bumper + A` - Additional Defensive Magic.
- `Right Bumper + Y` - Combat Powers and Form Change Powers.
- `Right Bumper + B` - Survival/Utility Powers.

## FAQ and Troubleshooting

**How do I use my shouts/tween menu/quick save?**  

LB + RB = Shout and Right Bumper + Start is the tween menu.  Quick Save is LB + Back.

**I am unable to Shout no matter what I do!** 

Delete the ControlMap_Custom.txt file.

**Can I change the Hotkeys?**

Short Answer: Yes.

Long Answer: Good luck. All the buttons are presented in what we think is Hex code but it could be something different. We have yet to find a reliable source as to what each code for the buttons are. You can go into the TUCS file and edit to your heart’s content but be careful and know you may need some trial and error.

**Can I use Gamepad ++ Instead?**

Short Answer: Yes.

Long Answer: Whilst it may have more features, GP++ is not as lightweight as the mods listed here. We did try GP++, however we found the setup given above to work better.

**Can I use a PS5 controller?**

Both Althro & Styyx use one. Milage may vary but it works.

**The game does not recognize my controller at all!**

Activate the controller functionality in Settings > Gameplay

**My game crashes when I open the HUD editor for iEquip!**

This is likely due to a soft conflict with another mod. To avoid the crash, enter the MCM menu for iEquip and turn time dilation down to zero. You can then edit your HUD freely. Keep in mind, that time will continue to progress and the world will not freeze so only do this in a safe location such as an inn or in your player home of choice.


## Controller Layout

### Xbox controller

- `Start` --> Journal
- `Back` --> Wait
- `LB+Back` --> Quicksave
- `RB+Start` --> Tween Menu (Menu where you have access to inventory, map, magic, levelup menu)
- `LB+RB` --> Shout/Power (the order matters, hold down LB first)
- `LB` --> unassigned on it's own (can be used for Dual wield Parrying for example; do not use it for a function that would interrupt your combat as the key is also       needed for 
shouting)
- `LS` --> Favorites Menu (only works if you allready assigned items as your favorites in the item/magic menu)
- `RS` --> Switch POV (1st person view to 3rd person view and vice versa)
- `A` --> Activate
- `B` --> Sneak
- `X` --> Ready weapon/sheath weapon
- `Y` --> Jump

### DualShock/DualSense Controller
- `Options` --> Journal
- `Share` --> Wait
- `L1+Share` --> Quicksave
- `R1+options` --> Tween Menu (Menu where you have access to inventory, map, magic, levelup menu)
- `L1+R1` --> Shout/Power (the order matters, hold down LB first)
- `L1` --> unassigned on it's own (can be used for Dual wield Parrying for example; do not use it for a function that would interrupt your combat as the key is also       needed for 
shouting)
- `LS` --> Favorites Menu (only works if you allready assigned items as your favorites in the item/magic menu)
- `RS` --> Switch POV (1st person view to 3rd person view and vice versa)
- `X` --> Activate
- `Circle` --> Sneak
- `Square` --> Ready weapon/sheath weapon
- `Triangle` --> Jump

## Change Log

You can find the change logs [here](https://github.com/chri3i/Gamepad-Guide-by-ShadesOfDawn-and-me/blob/main/Changelog.md)
