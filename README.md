# X4 Foundation Quality of Life Changes
***

Repository of various small QoL changes for the game [X4 Foundation](https://www.egosoft.com/games/x4/info_en.php) by Egosoft.

#### _Please note:_**
1. **Don't** just download everything or a file from here! Make sure you check the Version below first. 
··· Like always in life we move on and so do I, which means **i'm not keeping this repo up-to-date forever!** 
··· If the Version doesn't match the current available game version do not use anything from here, or at least double check that it doesn't interfere with the game.
2. All files have comments in them *(<!-- Description comment -->)* that describe what the following lines do. If you don't like a change delete everything between two Description comments.
3. These are personal QoL changes of the game that i considered useful, it's not based on general wishes by the player base. If you don't like something see the point above.
4. Further down i also provide a list of Mods that i consider essential or at least very useful.

A "ready to go mod version" will be available in the Release section. And on the Nexus a bit later. See Install Instructions further down for detailed instructions on how to install the Mod.


***
## Made for Version: **1.50**

#### _List of Changes so far:_**

1. Slightly faster forward and strafe movement and slightly higher jump on stations. (parameters.xml)
2. Lootmagnet speed adjusted to prevent overshooting. (parameters.xml)
3. Closer camera distance. (parameters.xml) (Consider this Work in Progress)
4. Better docking behaviour. Flying close by a dockingbay doesn't auto-trigger the guiding lights and also cancels guiding lights earlier. (parameters.xml) _Note: Consider this Work in Progress_
5. Changed default behaviour on certain events for player owned ships. IE. The default reaction **of your fleet** is now to **Flee** when a pirate asks to drop cargo instead of **Attack**. (factions.xml)
··· Also abandoned ships will now be marked instead of ignored. (factions.xml)
6. Teladi now use their specified behaviour set defined in behaviours.xml. (factions.xml)
7. Khaak and Xenon are now aggressive and protective. This is an attempt to prevent them from trading with other factions. (factions.xml)
8. Locked faction relations for Khaak to be always everyones Nemesis. See above (factions.xml)
9. Locked faction relations for Xenon to be always everyones Nemesis. See above (factions.xml)
10. On your map screen you can now use Q and E to switch between Tabs. Needs to be assigned in Controls Menu. Ctrl + -> and Ctrl + <- are now to rotate the map or you can use right mouse for that. (inputmap.xml)
11. Added new Signal Leak SoundFX. (sound_library.xml & sfx\ambient\signalleak folder)
12. Added new Station-Store Music. (sound_library.xml & sfx\ambient\storemusic folder) _Note: Music is Subject to change_
13. Lowered sound volume and distance for M Class engine sounds (NPCs only for now). (sound_library.xml)
14. Increase volume for engine travel sound. (sound_library.xml)
15. Increased radar range for all ship classes. (defaults.xml)
16. You don't have to scan a station to 50%+ to get vital information. This was made because the current trading situation is rather unstable and seeing early if the economy is stalled is better. (infounlocklist.xml)
··· Remove 'infounlocklist.xml' if you consider it as cheating. I tried to keep it balanced you still need to scan stations to get all informations, just trading informations unlock earlier now.


***
## Useful Mods by other People.

1. [Improved Explore Command Behaviour](https://www.nexusmods.com/x4foundations/mods/89) by MegaJohnny
2. [TaterTrader](https://www.nexusmods.com/x4foundations/mods/151) by ludsoe
3. [Employee Training](https://www.nexusmods.com/x4foundations/mods/154) by Frekjan
4. [Scaleplate Use All](https://www.nexusmods.com/x4foundations/mods/121) by DragonHeart013
5. [Signal Leak Hunter](https://www.nexusmods.com/x4foundations/mods/51) by loktide
6. [Trade Receiver Satellites](https://www.nexusmods.com/x4foundations/mods/120) by albysmith
7. [Learning All The Things](https://www.nexusmods.com/x4foundations/mods/8) by iforgotmysocks


***
## Install Instructions

1. Browse to your x4 folder
2. Create a new folder named 'extensions' if you haven't already.
3. Unzip the folder 'X4QoL' into your extensions folder.

Folder structure should look like this afterwards.

X:\YourPathTo..\X4 Foundations\extensions\X4QoL\

### Uninstallation:
1. Delete the 'X4QoL' folder.
