# Gamepad-Guide-by-ShadesOfDawn-and-me

Gamepad Support and Setup Guide

Version 2.2

Original Version Composed by ShadesofDawn

Maintained by Chri3i(chreieiiieieeeiie on Discord) and ShadesofDawn

Information Originally Compiled by Gamepad Helpers Team from Sovn’s Skyrim and Gamepad Helpers Team from Althro’s Animonculory

A Forward

This guide could not have been completed without hours of work put in by many people.
Both the original version on the QWEST! Discord and this updated version are the work of several individuals.
Thank you all for your hard work and valuable time in assisting with putting this together.

Also, to those users putting this guide into action in mod lists that do not officially support it, please treat this as a mini mod list.
That means direct all issues to us on Discord.
We can be found in Althro’s Animonculory.
Do not pester the creator of your mod list of choice or the creators of the mods contained within this guide as they will not be able to assist.

**For QWEST 3.8 all of the mods are already downloaded and installed**


Now, on with the guide.


Part 1: The Mods

To start, we want to make sure your control layout is untouched by anything else. Go to your Skyrim directory and look for a file called **ControlMap_Custom.txt** and delete it. This will ensure that nothing else will be modifying your controller configuration other than the mods we want doing so.  If you do not have this file do not be concerned.

This guide uses three mods to manage and control the game via gamepad with the goal of eliminating the need for keyboard commands in normal play.  The mods are as follows:

1. [The Ultimate Control Scheme](https://www.nexusmods.com/skyrimspecialedition/mods/29381?tab=files) - the basis for controller compatibility.  This opens up additional hotkeys on your controller.  It does change the button layouts significantly so it will take a little to get used to.

2. [iEquip](https://www.nexusmods.com/skyrimspecialedition/mods/27008?tab=files) - Acts as your HUD so you can see what is equipped quickly at a glance without referencing the quick menu or your inventory.  It also adds the ability to hotkey potions.

3. [Serio’s Cycle Hotkeys](https://www.nexusmods.com/skyrimspecialedition/mods/27184?tab=files) - This is the primary hotkey mod that allows you to control shouts, powers, spells, and equipment via the hotkeys introduced with TUCS.

If your mod list of choice does not come with built-in support for these mods, download and install all of the mods you are missing. **That being said if you add them to your mod list you void official support from the mod list authors.** You will then need to download the patched control layout for TUCS from [here](https://github.com/chri3i/Gamepad-Guide-by-ShadesOfDawn-and-me/raw/main/The%20Ultimate%20Control%20Scheme%20-%20Recharging%20Enabled.7z). Install it as a separate mod after TUCS.

Now, activate all of the mods.  You can leave them at the bottom of the load order in both the left and right panes of MO2 as nothing else should be touching the same things these are touching.


Part 2: The MCM

This section is going to be in addition to any instructions your mod list of choice has you set up.  Please complete all MCM instructions **except the hotkey options, as they are made with keyboard in mind most of the times** from your base mod list’s Read Me prior to continuing.

1. Serio’s Cycle Hotkeys
   
a. Set the mod to use Default Hotkeys

b. Set the Hot Key Setter button to the Left D-Pad

[Serio's Cycle Hotkeys MCM setup](https://imgur.com/141QCug)

2. iEquip

a. Set Cycle Shouts/Powers to Up on the D-Pad

b. Set Cycle Consumables to Down on the D-Pad

c. Disable Poisons

d. Set Use Consumables to Right on the D-Pad

[iEquip manual setup](https://imgur.com/a/RSojkPU)

At the top of this guide you also find an MCM setup that made this changes for you already, [Download it](https://github.com/chri3i/Gamepad-Guide-by-ShadesOfDawn-and-me/raw/main/iEquip_MCM.7z) and install it like you would with every other mod and activate it. it lets you load the settings like mentioned above

To adjust the HUD layout you need to enter edit mode. there you can load a preset if you want (there is a custom one included). The edit mode comes with neat tooltips so it's easy to find stuff. **for reference if the key is named NP5 then it requires you to press 5 on your Numpad**


3. SkyUI

Under Controls change Previous Column to <--

Also under Controls, change Next Column to -->


Part 3: Making it Work

Serio's can be an intimidating mod for those not used to it. However, without it, we would be much more limited in controller support than we are. This is a brief walkthrough on setting up a hotkey cycle for Serio's.

First, equip the items/spells/shouts you want to save as a hotkey preset. You can save all at once, or one slot at a time. However, what you want to hotkey must be equipped. Please note that this can be done from inside the Inventory window.   

Then activate the Setter Key we set up in the above section. This will pop open a menu prompting you to select a hotkey. 1 – 4 will be LB + X/Y/B/A in that order and 5 – 8 will be RB + X/Y/B/A, also in order. Select 1 for now. Again, this will be LB + X on your controller.

When you select the hotkey you want, you will have to "back out" of the menu with the B button. This will prompt the mod to open the next pop-up window.  This will let you set your first Cycle.

Scroll down to Cycle 1 and press the B Key.

This will open a third pop-up to store your equipment. You can select all, setting all equipped weapons/spells/powers to be equipped again when you press this hotkey or you can select items one at a time. Either way, once all of the items you want saved show (Stored) next to them, scroll to Accept and hit B again to finish.

You can do this for all 8 hotkeys to allow for a wide variety of options and equipment setups.   But you can also go back into a previously set up Hotkey and set a new cycle. This will allow you to cycle through a list of setups tied to a single hotkey. You could, for example, have one hotkey just for shouts and you would cycle through them as you press the hotkey repeatedly.

I would also like to draw attention to the use of the D-Pad for navigation of menus.  You will not be able to use it inside of your Inventory/Spell menus nor will you be able to use it in dialogue without setting off the hotkeys tied to the D-Pad.  Instead, use the left Joystick to navigate these parts of the game.

Please also keep in mind that while it is possible to use preset keyboard hotkeys for your Mod Specific hotkeys, you will not be able to set them or change them while the gamepad is plugged in (or turned on in the case of wireless gamepads).  Nor can you utilize the mouse at all except when the Command Console is opened.

It is also not recommended to change between controller and mouse and keyboard during standard play as this has been known to confuse Skyrim and cause the gamepad to stop functioning until the game is reset or in a worst-case scenario, a CTD.  If you know you are going to want to use the mouse and keyboard for something (Character Creation, for example) it is recommended to load into the game without the controller enabled, save when you are done with the mouse and keyboard, then exit the game and plugin/power on your controller and restart the game.  This is mandatory if you are using a headset plugged in through your gamepad as Skyrim will not recognize the change in audio device.

If you want to customize the HUD display from iEquip you can do so.  The default hotkey for the activation key is K then select the appropriate option from the menu that comes up.  From there, it is a matter of experimentation and moving elements around.  While this is entirely up to personal taste, we have included a configuration file for this as well on top of the page here.  Simply install it as a new mod and activate it.  Then load the preset from within the HUD Editor of iEquip.

Extra step if your mod list contains a mod called Engarde.

**This doesn't work when the modlist also has the mod 'Auto Input Switch'**

To make Engarde's dodge feature work with gamepads we need a program that mimics the WASD keys when using the left stick it can be done via Steam controller settings but i personally use [Antimicro](https://antimicro.en.softonic.com/) and the explaination of this guide will refer to antimicro as the used program.
to make it work all you have to do is download the program from the link above, install it and run it while playing the mod list. the setup needs to be done like [this](https://imgur.com/ngnq45z)

Part 4: An Example Set Up

To further assist you in learning to use Serio’s Cycle Hotkeys as well as iEquip’s hotkeys, we are including this section.  Below you will find the general layout of my own personal hotkey setup.  Keep in mind, this is with an eye towards playing a Spell Sword type of character and this is only one way to set things up.

iEquip Hotkeys
Shouts (Up on the D-Pad) - Here I keep a small selection of combat-related shouts such as the elemental breath weapons or ethereal form.
Consumable Cycling (Down on the D-Pad) Here are my potions by type, healing, stamina, and magika, as well as a selection of food and water.  Since Health is the most often needed at short notice, I keep it selected and only rotate to other options outside of combat.
Use Consumable (Right on the D-Pad) Nothing to set up there, just hit it when you need to use a consumable you have selected with Down on the D-Pad.
**Serio’s Cycle Hotkeys**

Left Bumper + X - My Melee set.  I generally only keep my primary set here.

Left Bumper + A - My Ranged set.  Again, I only keep a single bow here.

Left Bumper + Y - Offensive Magic.  Single Cast in the left hand on a single press, Duel Cast on a double press.  Like with the weapon sets, I generally stick to a single elemental spell here.

Left Bumper + B - Healing Magic. Single Cast/Duel Cast like the offensive spell.  My most powerful or quickest to use healing spell takes up this slot.  If I am using spells to heal companions, I will slot one in as an off-hand spell only in the third cycle.

Right Bumper + X - Additional Offensive Magic - Single Cast - Here I set up other spells that I may use regularly.  Direct Damage and Crowd Control spells go here.

Right Bumper + A - Additional Defensive Magic - These are my buffs that are used prior to combat.  

Right Bumper + Y - Combat Powers and Form Change Powers - Such as Vampire Lord or Werewolf go here so I can transform quickly as well as things that I might use only rarely such as the Dragon Form Shout or WhirlWind Sprint.

Right Bumper + B - Survival/Utility Powers - This is where I put things like Call Horse, Fill Waterskins, etc.





Part 5: FAQ and Troublshooting

1. How do I use my shouts/tween menu/quick save?  Short answer, LB + RB = Shout and Right Bumper + Start is the tween menu.  Quick Save is LB + Back.

Long Answer: You should be reading over the Nexus entries on all mods in the list at least once.  While Sovn has done an amazing job for us with QWEST! so we can utilize the modlist without the headache of building the list ourselves, you really need to familizarize yourself with any mods you are playing with.  This will help you avoid thinking something is a bug when in fact, it is a feature of one of the mods.  It’s just good practice.

2. I am unable to Shout no matter what I do!  A: Go delete the ControlMap_Custom.txt file as instructed to do so in Part 1.  We told you having this would break the controller support.

3. Can I change the Hotkeys?  Short Answer: Yes!



Long Answer: Good freaking luck.  I managed to edit TUCS settings to correct an issue that was blocking recharging enchanted weapons and staves.  All the buttons for the controller are presented in code, Hex I think but I could be wrong.  I’ve yet to find a reliable one to one mapping of what the codes are for each button.  You can go into the TUCS file and edit to your heart’s content but be careful and know you may need some trial and error.

4. Can I use Gamepad ++ Instead?  Short Answer: Yes!

Long Answer: Gamepad ++ has more features, but all of the features are enabled through scripting.  This results in script lag between you pressing a button and the action taking place.  In low script, low mod lists, this usually isn’t a huge issue.  However, in a list like QWEST! with many scripts running in the background on top of the vanilla ones, this could result in a level of script lag that can make the game unplayable.  This is the reason this guide was written with TUCS in mind.  Trust me, I love Gamepad ++ as well but during the early days of Sovn’s Lists, it proved too laggy.

Also, keep in mind, you would not be using Gamepad++ alongside this guide, you would be using it instead of this guide.

5. Can I use a PS5 controller?  A: I personally play with a PS5 controller.  Mileage may vary.

6. The game does not recognize my controller at all!  A: Did you remember to activate the controller functionality in Settings > Gameplay?  I don’t think you did.  Please go do so and it should be fixed.

7. My game crashes when I open the HUD editor for iEquip! A: This is likely due to a soft conflict with another mod. To avoid the crash, enter the MCM menu for iEquip and turn time dilation down to zero.  You can then edit your HUD freely.  Keep in mind, that time will continue to progress and the world will not freeze so only do this in a safe location such as an inn or in your player home of choice.


Part 6: Controller Layout

**XBox controller:**

Start --> Journal

Back --> Wait

LB+Back --> Quicksave

RB+Start --> Tween Menu (Menu where you have access to inventory, map, magic, levelup menu)

LB+RB --> Shout/Power (the order matters, hold down LB first)

LB --> unassigned on it's own (can be used for Dual wield Parrying for example; do not use it for a function that would interrupt your combat as the key is also       needed for 
shouting)

LS --> Favorites Menu (only works if you allready assigned items as your favorites in the item/magic menu)

RS --> Switch POV (1st person view to 3rd person view and vice versa)

A --> Activate

B --> Sneak

X --> Ready weapon/sheath weapon

Y --> Jump

**Playstation controller:**

Options --> Journal

Share --> Wait

L1+Share --> Quicksave

R1+options --> Tween Menu (Menu where you have access to inventory, map, magic, levelup menu)

L1+R1 --> Shout/Power (the order matters, hold down LB first)

L1 --> unassigned on it's own (can be used for Dual wield Parrying for example; do not use it for a function that would interrupt your combat as the key is also       needed for 
shouting)

LS --> Favorites Menu (only works if you allready assigned items as your favorites in the item/magic menu)

RS --> Switch POV (1st person view to 3rd person view and vice versa)

X --> Activate

Circle --> Sneak

Square --> Ready weapon/sheath weapon

Triangle --> Jump



Change Log

v1.0 
Official Release alongside Qwest update 1.1. 
Base DS4 Controller Model used can be found at Wikimedia Commons. Used under Creative Commons License. Button Labels and Controller Instructions not part of the original image. Original Image Created by: Tokyoship. 
Base Xbox One Controller Model used found at Clipart Max. Used under permissions given on Clipart Max. Button Labels and Controller Instructions are not part of the original image.

v1.1 
Guide updated by Althro for use with QWEST!

v1.2
Updated Part 1 with instructions to enable controller functionality in Skyrim’s in game settings. 
Added a FAQ based on the most common questions I’ve seen over the last 6 months in the Discord.  
Reformatted Change Log for ease of use.
Added Credits on the first page.

v2.0
New version of the guide.  Edited for generic use with any mod list.

v2.1
Many changes including the availability of the guide and the place where you can find us and the files needed. Links to the mod pages added

v2.2
Changed the specifics about QWEST! and included an exception for the mod 'Engarde'
