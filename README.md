# YomeiriEnglishPatch
The English translation patch for Nisekoi: Yomeiri!?

# About
This is an **unofficial** patch for Nisekoi: Yomeiri!? to translate it into English.

# Installation

This is a romhack of the orignal game for the PlayStation Vita. To play it, you will either need a PlayStation Vita (with the original game, physical or digital should work) or Vita3K (a PS Vita emulator, found here: https://vita3k.org/)

## To play in Vita3K:

  Get Vita3K from here: https://vita3k.org/
  
  Install the game in Vita3k. IF YOU ARE USING VITA3K, I highly recommend you use the pre-patched version of the game (also linked in the releases tab).
  
  If you are not using the pre-patched version, apply the patches to the game's data files (the one's in Vita3K's data directory) as directed above.
  
## To play on PS Vita (Using RePatch):

  Apply the patches to all.apk and fs.apk. IF YOU ARE ON A PS VITA, pre-patched versions of all.apk and fs.apk are linked in the releases tab (find the link to the rePatch version)
  
  Follow this guide to set up RePatch: https://github.com/TheRadziu/NoNpDRM-modding/wiki#using-repatch-plugin-to-mod-encrypted-games1.
  
   (NOTE: The game's ID is PCSG00397. Name your rePatch folder this.)
   
  Copy the modified .apk files to the rePatch folder.

# Manually applying the patch

  I highly recommend you do not do this unless the pre-patched and rePatch versions get taken down.

  To install this patch, you will need an **unencrypted** dump of the original game. If you have an encrypted dump (e.g. a NoNpDrm dump), put it in a .zip or a .vpk and install it into Vita3K. Then find Vita3k's data directory and navigate to ux0/app/PCSG00397. The decrypted game will be found here.

  This patch has been distributed as two xdelta binary patches. Grab them from the Releases tab and get the patching tool here: https://www.romhacking.net/utilities/704/.

  In the game folder, navigate to the "pack" subdirectory and back up all.apk and fs.apk (which hold most of the game's data.)

  Use the patcher you downloaded to apply all.xdelta to all.apk, and fs.xdelta to fs.apk. If need be, rename the patched files back to "all.apk" and "fs.apk".

  **PLEASE NOTE:** the patch can only be applied to the *original* apk files. In other words, **you cannot apply the binary patches to a file that was already patched**. To upgrade to a newer version of the patch, copy your backups of the unpatched files into the game's */pack/* folder and patch *those*.

  (Video tutorial here: https://youtu.be/p1iYJlALdYI)

# Freqently Asked Questions

  * **Q: I don't know (or maybe don't care) what any of this means. What's the easiest way to just jump right in and play?**
    * A: If you have a PC:
        * Download Vita3K (https://vita3k.org/)
        * Download the prepatched version of the game (https://drive.google.com/file/d/1QHU5NH2vfhWjR9ozkkj7ftP1xqkc-HA9/view?usp=drive_link)
        * Run Vita3K and do the first time setup (it will walk you through it)
        * Once you get to the application list, go to the top left corner and click where it says "File", then again where it says "Install .zip, .vpk"
        * Navigate to the prepatched .zip you downloaded earlier and click it
        * Wait for the installation to finish
        * Once it does, you may need to close and re-open Vita3K to refresh it.
        * And that's it! The game will show up in the list under its Japanese name, but it should be pretty easy to find it.
    * If you have a PS Vita:
        * Make sure your Vita can run custom plugins and has firmware 3.60-3.68.
        * Make sure you have the game card inserted, if you have it. Otherwise, make sure the digital version of the game is installed (not found here)
        * Install the rePatch plugin onto your PS Vita.
        * Follow these instructions to set up: https://github.com/dots-tb/rePatch-reDux0/wiki/Usage-(GENERAL)
          *  The Title ID is PCSG00397
          *  The "decrypted content" you need can be found here: https://drive.google.com/file/d/10DOIOn-i0FNL2yKOVt5vaXMyxa8AgATF/view?usp=drive_link
          *  Extract the file you just downloaded and move it to the folder you need (most likely ux0:rePatch/PCSG00397)
        * Launch the game from the home screen as usual
  * **Q: What's the difference between the patch versions you provide here?**
    * The **Pre-patched Version** is the entire game, as a digital file, already patched into English. It only seems to work in Vita3K for some reason.
    * The **rePatch Version** is only the two data files patched into English, and requires the original game to be of any use. It is, as the name suggests, intended for use with the rePatch plugin.
    * The binary patches are for manually patching the game into English. You will not need these, unless the other two versions get taken down.
  * **Q: How do I save my game?**
    * A: The game can be saved once you finish the prologue. This means you need to be on the map screen. Press the wrench icon and tap Save.
  * **Q: What are the controls?**
    * A: On PS Vita, you can use the controls outlined in the manual.
    * On Vita3K, ENTER pauses the game, X hides/shows the dialogue box (and acts as a cancel button), C advances dialogue and selects buttons, and Z enables auto-advancing of dialogue. WASD to move your character in stealth segments and navigate some menus.
  * **Q: Where can I buy the original game?**
    * A: The game is no longer officially sold. You can generally find physical copies on eBay.
  * **Q: Where can I find a dump of the game?**
    * A: If you're not using the pre-patched version, it's up to you to dig up a dump yourself.
  * **Q: Can I play this in iPhone/iOS?**
    * A: Unfortunately, no. Vita3K only supports Windows, Linux, MacOS, and decently-powerful Android phones.
  * **Q: This isn't working on my Android phone!**
    * A: This is probably a problem with Vita3K, since the Android builds are still in the earlier stages.
  * **Q: How do I update the patch?**
    * A: If you're on Vita3K and using the pre-patched version, just install the new version over the old one.
    * If you're using the rePatch patch, you can install the new patch over the old one.
    * On the off-chance you're one of the psychopaths who uses the xdelta patches (manual patching), I should tell you that they only work on the original files and will not work if they have already been patched. Keep a backup of the original files and only patch copies of that backup, then put those copies in the rePatch folder or wherever.
  * **Q: I can't install the binary patches!**
    * A: Do not use them unless you have to (or really want to). If you *do* have to (or really want to), make sure the patches are being applied to an *unencrypted* dump of the game.
  * **Q: What does "encrypted" mean?**
    * A: When people dump their PS Vita games using NoNpDrm, the game files will be encrypted and the patcher cannot read them. If you have the license files (which are included in most game dumps), Vita3K can unencrypt them for you.
  * **Q: How do I check if a dump of the game is unencrypted?**
    * A: Open all.apk or fs.apk in a hex editor. The first 8 bytes should be ENDILTLE. If the first 8 bytes are not ENDILTLE, the game is encrypted.

# Progress
* Main Campaign
  * Chitoge Kirisaki route: 100% complete
  * Kosaki Onodera route: 100% complete
  * Seishiro Tsugumi route: 100% complete
  * Marika Tachibana route: 100% complete
  * Ruri Miyamoto route: 100% complete
  * ? Events: 100% complete
  * Miscellaneous Events: ~100% done
  * Raku Route: 100%
* Majikoi+ Mode: 40% complete
* Majikoi+ DLCs: 0% complete
* Minigames
  * Old Maid character descriptions: 100%
  * Old Maid victory phrases: 100%
  * Old Maid dialogue: 0% (game doesn't subtitle it)
  * Stealth Minigame level names: 80% (gets cut off in menus)
  * Stealth Minigame level descriptions: 100%
  * Stealth Minigame item names: 100%
  * Minigame UI: 100% (may look a little wonky in menus)
* Gallery
  * VA Comments: 0% (game doesn't subtitle them)
* Menus
  * Main Menu: 100%
  * Gallery: 100% (some things may be a little wonky)
  * In-game character descriptions: 100%
  * In-game item descriptions: 90% (translated, but some may be unreadable due to cropping)
  * In-game tutorials: 100%
  * Screen prompts and notifications: 100%
  * Manual: 100%
* Anagram puzzles: 100%

# Screenshots
![](screenshots/main_menu.png?raw=true "Main Menu")
![](screenshots/settings.png?raw=true "Sound Settings")
![](screenshots/understatement-of-the-century.png?raw=true "Understatement of the century")
![](screenshots/ss3.png?raw=true "From the Seishiro route")
![](screenshots/ss4.png?raw=true "From the Seishiro route")
![](screenshots/ss1.png?raw=true "From the Kosaki route")
![](screenshots/ss2.png?raw=true "From the Kosaki route")
![](screenshots/ss5.png?raw=true "From the Chitoge route")
![](screenshots/ss6.png?raw=true "From the Chitoge route")
![](screenshots/ss7.png?raw=true "From the Marika route")
![](screenshots/ss8.png?raw=true "From the Marika route")
![](screenshots/depression.png?raw=true "From the test scene")
