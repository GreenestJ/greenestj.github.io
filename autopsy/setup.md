##### Path: [root](https://greenj.net):/[autopsy](https://greenj.net/autopsy)/[setup](https://greenj.net/autopsy/setup)

# How to setup the modpack

###### Mod Packs take longer to boot on first launch than any time afterwards

## Table of Contents
1. ### [Importing](#import)
    * ### [MultiMC](#import-multimc)
    * ### [CurseForge](#import-curse)
    * ### [Other](#import-other)
2. ### [Dedicating Ram](#ram)
    * ### [MultiMC](#ram-multimc)
    * ### [CurseForge](#ram-curse)
    * ### [Other](#ram-other)
3. ### [Customizing](#custom)
4. ### [Errors](#error)

# How to import the mod pack {#import}

I recommend using [MultiMC](https://multimc.org/#Download) as a launcher I find it more stable but an okay alternative is [CurseForge](https://download.curseforge.com/)

**File Size Discrepancy and possible bugs:** MultiMC exports the file as a zip so all the mods are still in the zip. CurseForge exports a list of mods which it then looks to to download from. MultiMCs Verision is more relaiable but way larger file size. If there are any mods missing in curse's version its because curse didn't export the list properly. To get around this download the multimc pack, create an instance in curse, extract the the zip, and drop the mods and configs directly into curses instance folder.


## MultiMC {#import-multimc}

1\. [Download The MultiMC Version Of The Modpack](https://mega.nz/file/29AWAZLR#JfiC1ImpaxA5nLGx3K3hyvJuSUPZkGeZr0JSNyH6tWQ) **DO NOT UNZIP**

2\. Launch MultiMC

3\. In the top left click on add instance

4\. Choose import from zip

5\. Click browse and find the zip in your files

5\.1\. I recommend making a group for the pack by typing a group name in the group field but this is not necessary if you don't plan to use MultiMC a lot.

6\. Click Ok and the mod pack will start importing. While importing the program will stop responding it is working fine it just works like that for some reason so wait for it to respond again.

7\. Mod Packs almost ready to go all thats left is dedicating ram which is below


## CurseForge {#import-curse}

1\. [Download The Curse Version Of The Modpack](https://mega.nz/file/j4J2QJQK#3SXaMsBuoJQ0CGRSimP2-tK4VTinj2WUEq0O6uIqhqQ) **DO NOT UNZIP**

2\. Click create custom profile

3\. At the top below Create Profile it says `or Import a previously created profile` click on import

4\. Select the mod pack

5\. It should auto install (I don't use Curse anymore so I'm not sure) and be ready except ram dedication which is below

## Other Launchers {#import-other}

For other launchers use the curseforge release and search up or look around the program for how to import

# How to Dedicate Ram {#ram}

***WARNING:*** Dedicating too much ram can cause its own issues as explained [here](https://vazkii.net/blog_archive/#blog/ram-explanation). The best method to figure out how much ram is needed is to experiment by dedicating a base line and increasing it by 512 MB/0.5 GB if it crashes or is laggy. 
Keep in mind a CPU can also cause issue due to how minecraft was designed that no amount of ram can fix (same reason why servers can't hold 100+ people)

## MultiMC {#ram-multimc}

1\. Click on the mod pack to have it selected.

2\. On the right side click on Edit Instance

3\. Click on Settings

4\. Check the memory box to allow custom values

5\. Set the minimum and maximum ram to what you want (1 Gigabyte is 1024 Megabytes)

6\. It's ready you can just close the setting windows it auto saves and launch the pack

## CurseForge {#ram-curse}

1\. Click on the pack and be in its menu

2\. Click on the 3 dots next to play then profile options

3\. Uncheck use system memory and adjust the bar to whatever you want (The Min and Max ram is set the same \| 1 GB is 1024 MB)

4\. Click Done and you're ready to use the pack

## Other Launchers {#ram-other}

For other launchers look it up

# How To Customize {#custom}

~~The mod pack has optional client side mods that a mod handles controlling if your computer is stronger you can activate certain ones or disable certain ones if your computer isn't strong~~

The mod that was gonna be used to handle client side mods was incompatible (breaks due to blood magic) so I decided against having certain client side mods as they just add unnecessary strain to everyone no matter the setup. You can still manually add client side mods but do so at your own risk of running minecraft worse.

## Errors {#error}

Before you report anything try reimporting the pack, changing to another launcher than what you used (MultiMC -> Curse \| Curse -> MultiMC), and reinstalling the pack from mega and importing again. If none of those work contact Me (GreenJ) or Mr. Danger (who will relay it). 
If you use MultiMC click edit instance before launching and it shows a log. In top right theres an upload button that gives a link please send the paste.ee link. 
If you use CurseForge. Don't. (I will try to help but MultiMC runs more reliably so try using that before asking for support.)