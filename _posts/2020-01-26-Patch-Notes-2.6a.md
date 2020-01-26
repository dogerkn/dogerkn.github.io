---
layout: post
title: Patch Notes 2.6
---


# Patch notes for 2.6 - Mystery Box

### Quick note - We've started an official Steam group for Dogeminer!

[Link to the group](https://steamcommunity.com/groups/dogeminergame){:target="_blank"}. Feel free to join and invite your friends! It's brand new, mind the paint.

Same rules as on Discord apply for now; behave and all shall be well. Kindness and wholesomeness goes a long way with us.

### Continuing...

The holiday theme is over (and has been for a while) and I think, for our first limited "theme", it went rather well. It was supposed to have more content; next time around there should be time to add more fun stuffs.

_PS. If you were wondering what Holiday Spirit does, it did nothing this time around, but for future holidays, expect it to do something (maybe a simple % increase, or reduced costs, or ... #game_suggestions on discord)._

Looking at doing a similar thing for Easter and Halloween (these holidays come to mind as pretty international). But that's a sidenote, here come the patch notes.

*TL;DR: The Mystery Box fortune has evolved into a feature that occasionally can be opened for any item on any location you've unlocked, and a little extra! In addition to the regular bug fixes and minor stuffs, all those copies of Super Fortunes and D.I.A. badges some of you have collected will now be merged into one of each the next time you decide to timetravel, saving space and resources!*


## Changes:

+ Find the Mystery Box fortune and if you're nice to it, it will show you its secrets! If you already have it, expect it to let you know somehow...
    - _The fortune has gained [Protected] status, perhaps it did not appreciate being tossed into Super Fortunes..._
    - _It magically finds items from any locations you've unlocked on your current timeline_
    - _It seems not to care whether or not you already own the item it finds... This new development have rendered the fortune counter helpless, and sparked wonder in many shibes..._
    - _It is rather judgy, and will only allow itself to be opened if it does not detect an ad-blocker(!)_
    - _It has a 20 minute timer, increasing with each opening, up to 25 minutes after ten. The first opening has no timer._
    - _The tenth opening of the box gives **twice** the rewards. Yes, that's two items! The counter will then reset_
    - _If the Mystery Box drops a new pickaxe, currently, it will only auto-equip if auto-looting is enabled. This will change with an auto-equip setting in the future, as auto-looting is only available after entering timeline 2_
+ The save system has changed its compression in order to fix an issue with Safari not being capable of doing what everyone else is doing
    - _Lets pray to the Dogegod (=dogegoD) that I implemented this change correctly and didn't break all the saves_
+ Duplicate fortunes from time-travel will now combine itself with others of the same type
+ Fixed the bug where DPS would not properly update in the shop after a bonus fades away. Same with upgrades.
+ Mars is still round
    - _Just give up, Flat Mars folk_
+ Added some special code before loading the game after loading the save, to reduce some _weirdness_ from _sometimes_ happening
+ Added a dozen or so fortunes, spread across the locations (it's not much, but I wasn't feeling like coding that day)
+ Holiday fortunes should no longer drop, properly this time. We'll say the holidays were simply extended due to lack of enough holiday spirit.
+ Certain bad kittens have been fired, for the good of all. _Doge bless their families._
+ Some weirdness is guaranteed to exist
+ Added new bugs for our good Shibe bug hunters to find!
    - _Think of it like being a monster hunter, but with less songs written about you_
+ Tossed a coin to some witches, did I do it right?
+ Reduced the time cloud saves wait for a load
    - _Should save some time on the first load when cloud saves are not being used, I've hopefully not broken it_
+ And whatever I forgot or didn't quickly find in my git history


_This goes without saying: If the game has completely broken for you, try refreshing the page first (preferably a forced refresh - hold Ctrl (or Cmd on Mac) and press F5 to force-download the assets - sorta hard if you're not on a Mac or PC, but it solves 9/10 cases)._

_If this does not work, let me know as soon as possible ([Discord](https://discord.gg/PBg9yb4){:target="_blank"} usually works the best/fastest, use the #bug_reporting channel once you've passed the anti-bot-spam counter-measures á reacting to the message in #hello-there)._

# Friendly reminder: If you want to be sure that you won't lose your progress, **make sure to download your save every now and then**

It's super easy, just click the download/upload button on the landing page and click download. Then forget about it (or place it somewhere you'll remember - otherwise just look in the download folder duh). The save is compressed, so it's small (sub 100kb pretty much guaranteed) and has a timestamp in the name to avoid duplicates.

# The usual suspects for losing a save:

Browser cleanup of some kind. The save is stored (if not cloud saved) in your browsers localStorage (like cookies, but for larger sizes and not for tracking etc). However, when an app cleans out your cookies, this usually includes your localStorage too.

Usually a 3rd party program will do this to clear out stuff that could slow down your PC or browser, or track you. Common tools known to do this are CCleaner, SpyBot S&D (_if you don't uncheck your browser cookies from being removed, after a search_) and perhaps a few anti-virus programs.

Always download your save to be safe, _then_ run whatever cleanup tool you have. If you lose your save and your PC isn't broken, it's on you.


## Faster update schedule

2020 is here, so to make sure the game makes it to Steam this year, weekly goals (among other priorities) are now a big thing, in order to increase the speed that things get done, simply put.

Since the focus will be on Steam this year, very soon the web version will see less updates as I/we slowly progress towards this. I'll be attempting to modularize the development to the extent that each platform should be able to receive some updates, without affecting others.

This is not to say that the web will be getting the same treatment as the Steam-version, but to make mobile app-versions easier to add to the mix - some time after the Steam release.

Steam 2020 Hype! Let's go!


//rkn