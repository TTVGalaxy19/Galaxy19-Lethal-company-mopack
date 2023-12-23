# LateGameUpgrades
***INSTALL THE DEPENDENCIES***  
***ALL CLIENTS NEED THIS MOD INSTALLED***  
to install just put the MoreShipUpgrades folder in your BepInEx plugins folder.

### *Everything about this mod can be changed via the extremely extensive config "com.malco.lethalcompany.moreshipupgrades.config"*  
The config is automatically synced from host to clients excluding changes to equipment (peeper, night vision goggles, portable teles)


Type `lategame` in the terminal to see mod info!  
Type `lategame store` or `lgu` to view current upgrade status and cost.  
Type `info <upgrade>` for dynamic info.

This adds 20 powerful ship upgrades to make lategame last longer and remedy having a bunch of money and nothing to spend it on.

If using V40 - downgrade to V2.1.0

## V 2.7.0
### **[ Changes & New ]**
- Lightning Rod
    - The closer you are to the ship, the more likely the lightning will target the ship instead of your metal object.
    - change `effective distance of lightning rod` in the cfg to tweak this.
- Fast Encryption
    - This is just the Pager if anyone remembers the pager upgrade with some minor tweaks.
    - I removed the pager when the transmitter came out but I like using this more so it's back in.
    - You need a signal translator purchased to use this, overrides the vanilla transmit so it instantly sends the message discretely to all clients and plays a sfx.
- Better Scanner Overhaul
    - The first of the complex upgrades
    - Also a bit of a nerf as scanning through walls instantly was very op
    - Level 1 - Increase scan distance
    - Level 2 - Unlocks 5 new commands
        - `scan enemies` provides a list of enemy types and their count (or just their count see cfg)
        - `scan scrap` returns the 5 most valuable scrap items in the dungeon and their coordinates
        - `scan player` returns a list of players and their coordinates sorted into dead and alive
        - `scan doors` if targeted player is inside, returns the 3 closest exits, if outside, returns the entrances
        - `scan hives` returns a list of hives, their price, and coordinates
    - Level 3 - scan scrap through walls and configurably enemies (off by default)
- Night Vision Refactor
    - The night vision system has been refactored and should be simpler to configure
    - `info nv headset batteries` also provides the exact time in seconds it will take each level to drain and regen
    - Added an option to increase the range and intensity of night vision on level up
        - You could now for example set up your night vision to be infinite but each upgrade increases how far you can see in the dark with it.
    - a new config should be generated as the config values operate in a much different range now (should happen automatically)
- Fixes including
    - Night Vision Only working for host (config serialization error)
    - Varius intern issues
    - load lgu command not using steam names

## Compatibility

### This mod changes and patches a lot so problems may arise.  
- Bigger Lobby and More Company are more or less compatible but credit desync can arise  
- LC Better Saves is currently incompatible  
- Door fix causes an issue with locksmith  
- Use common sense, EX: if you download a mod that changes the movement speed of the player every frame and the movement speed upgrade from my mod doesn't work that's why.


## Community

### Please post bugs, assets, or ideas [on this post](https://discord.com/channels/1168655651455639582/1178407269994594435) after joining [this modding discord.](https://discord.gg/hzEcKFSSDX)

Feel free to [create a pull request](https://github.com/Malcolm-Q/LC-LateGameUpgrades) and help with the mod.

Anyone who contributes in any way is greatly appreciated. People willing to contribute 3D models are needed.

## Credit
- GitHub Contributors
    - Dilly_The_Dillster
    - WhiteSpike - [git](https://github.com/WhiteSpike)
    - Croquetilla
- Graphics / Art / Models
    - Sad Amazon
    - Bobilka
    - Pixelated Engie - [twitter](https://twitter.com/PixelatedEngie)
- Beta Testers
    - Lann
    - Kapt
    - Rootbeer
    - Glitched
    - a glitched npc - [twitch](https://www.twitch.tv/a_glitched_npc)

## Upgrades & Items
***Everything is tweakable via the config***
* __Protein Powder - $500__
    * Increase damage dealt with shovels and signs.

* __Lightning Rod - $1000__
    * Redirects lightning to the ship.
    * The closer you (and your metal object) are to the ship, the more likely the ship will attract the lightning.

* __Fast Encryption - $300__
    * Upgrades the signal transmitter.
    * Must have signal transmitter purchased.
    * Instantly sends an unrestricted message to all clients chat when using transmit.

* __Interns - $1000__
    * Replaces your dead friend with a fresh intern (revives your friend).
    * Teleports to a random location in the facility.
    * $1k per use

* __Walkie GPS - $450__
    * Upgrades the walkie talkie to show your position and time.
    * Must be holding it.
    * Useful for fog or finding home.

*__Peeper - $500__
    * Looks at coil heads for you.

* __Locksmith - $640__
    * Makes noise when picking, makes a lot of noise when failing.
    * Just run into a locked door to start the minigame.
    * Strike the pins in the order they flash to unlock the door.

* __Portable Teleporter - $300__
    * An item that when used teleports you back to the ship.
    * Keeps items.
    * 90% chance to get destroyed on use.

* __Advanced Portable Teleporter - $1750__
    * Same as above.
    * 20% chance to get destroyed on use.

* __Beekeeper - $450__
    * Circuit bees do significantly less damage to you.

* __Bigger Lungs - $600__
    * Increased sprint duration.

* __Running Shoes - $650__
    * Increased movement speed.

* __Strong Legs - $300__
    * Jump higher.

* __Malware Broadcaster - $550__
    * Instead of disabling turrets and landmines; Destroy them.
    * Can enable alternate behaviours - Exploding hazards (default), destroying, or disabling for a longer period.

* __Light Footed - $350__
    * Enemies have to be closer to hear your footsteps.
    * Applies to both walking and running.

* __Night Vision - $380__
    * Press Left Alt to toggle night vision.
    * Has self regenerating batery.
    * Pick up and lmb to equip.
    * Lose on death (by default).

* __NV Headset Batteries - 300__
    * increases regen speed and decreases depletion speed of NV
    * Can also increase range and intensity of night vision light for alternate behaviour (if enabled in the config).

* __Discombobulator - $450__
    * Enter `initattack` into the terminal to stun enemies around the ship.
    * Enter `cooldown` to view cooldown (120 seconds).
    * Attracts enemies in a larger radius than loud horn.

* __Better Scanner - $650__
    * Level 1
        * Increase distance of Ship and Entrance pings drastically.
        * Increase distance of all other pings.
    * Level 2
        * Unlocks 5 new scan commands - scan player, scan enemies, scan scrap, scan hives, scan doors.
        * Type `info better scanner` for information on each.
    * Level 3
        * Allows you to scan scrap through walls.
        * Change the config if you also want to scan enemies through walls.

* __Back Muscles - $715__
    * Carryweight is drastically reduced.
    * % reduced increases each upgrade.
