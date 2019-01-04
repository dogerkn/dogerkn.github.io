---
layout: post
title: Titan & D.I.A. Update v2.4 - Patch Notes
---

# The Titan & D.I.A. Update Is Finally Here!

Aaand here's the patch notes _(including some unnecessary comments and ramblings)_:

+ **New location** - Titan, the mostly-made-out-of Dogecoin Moon of Saturn
+ **DIA mission** for rewards plus soft-resetting loot and location/helper progress, while keeping stats and diamonds. You need a Time Machine Mining Rig to do this, hints about how to unlock helpers that aren't unlocked by bases is on its way for the next patch (probably). Due to this, I'll give you a hint if you have not unlocked it before: getting the party started on Mars with enough Party Shibes will motivate some scientists (apparently)
    - _The mission rewards depends on how far you've come in the current timeline (loot, coins, helpers)_
+ **Lots** of new items to loot (or well, ~50 or so)
+ **Now when you break the rock**, you don't have to loot everything on the ground before the rock will respawn - up until there are 5 non-disappearing items to pick up (so dogebags/containers & dogediamonds, but not coins)
    - _Makes idle/background playing slightly better_
    - _And you don't have to stop and loot every click if got a powerful pickaxe against a weak rock! Wow_
+ Each locations Base now **upgrades** the **BONUS COIN** that appears randomly, both in stats and time. They become smaller for higher levels, so try not to miss them!
+ It has become **easier to farm DogeDiamonds** thanks to the rocks and clouds being easier to break as well as the D.I.A. mission. Diamonds are still only used for upgrades, but another alternative method of using diamonds is planned for another patch (special shop).
+ **Titans** final helper upgrade(s) features something new: **unlocking helper upgrades for almost all helpers in the game**. This currently comes in 2 "phases": one for 1-2 upgrades (per helper) and one for the ultimate upgrade (per helper)
+ Another **big note on upgrades**: after all upgrades have been found for a helper, the SearchDoges can now find **upgraded versions** of those upgrades (e.g. "Super Cool Upgrade **II**", "Super Cool Upgrade **III**" etc)
+ **Existing** late game helpers have been buffed and some may even be cheaper now! Yay!
+ Instead of just giving you coins, seemingly forever before you get a better container - the game will check if the current container has no items and go to a higher quality container, up until legendary quality _(this has changed how loot is distributed dramatically, and will likely be subject to some changes)_
+ One can now click (or tap) the DPS of a helper in the shop to see its base dps as well as its bonus DPS from stats
+ **Stacking / grouping helpers like on the phone layout** is now available for **tablet and PC layouts** too (check under the Settings/Gear icon). Note that if they have a green border, that means you can afford them, duh
+ **Optional FPS limiter setting** for those suffering from too many resources being used. Or you just have too much stuff. There's still optimizations that could be done in this regard, but it's a start!
+ In addition to the amazing benefits of successfully completing the D.I.A. mission, your **previous experience help the SearchDoges with finding upgrades a little faster (10%)** _every time_ the mission gets completed (up to a point)
+ **Doge** now also shows some expressions while wearing the Space Helmet (if you didn't notice before: good job me)
+ _Slightly_ better cloud saving: might work better / more reliably, but will still not work at all on some devices/browsers, sorry. This is usually due to how 3rd party javascripts are treated (not a problem for Chrome with Windows 10, unless your extension(s) are doing it)
    - **The only 3rd party that is used is Google** and _sometimes_ you can _fix this yourself_ if it doesn't work. I recommend googling something like _"turn on 3rd party scripts"_ + _your browser_ and _OS_ (worked well when tested with Firefox on Windows 10)
    - _For the best experience I recommend using **Chrome** (Windows, Android & probably Linux too) or **Safari** (iOS/OSX). Firefox is good but might need configuration to work with the Cloud Save API (Google it)_
    - _**Logging in with Google to use Cloud Saves is highly recommended** if you or your device does **any form of browser cleaning** (such as **CCleaner** for example). A lot of people lose their progress because they accidentally remove their save this way and weren't/couldn't use cloud saves. I know my cloud saving system isn't perfect, but it seemed the best solution I could implement in a reasonable time (I'm way more of a frontend developer than backend, the cloud saving is all frontend on the site + Googles own backend)._
    - _If using a **good browser and cloud saves still don't work** (should show up as an error, or secretly not work at all for some reason); disable guilty extensions or 3rd party script blocking. I've personally noted issues when installing privacy extensions, as well as most adblockers (this game has google ads only, and in my opinion, isn't obnoxious with the placement/usage)_
    - _About the permissions asked for: There are **two** major APIs being used, the **Drive API** is the main saving function and **no, the game cannot see nor alter anything you have on your Google Drive, except for Dogeminers separate data.** The second API (which is the that requires Google+ details) is the Play API. This API currently is not being utilized fully; it has been used to test Google Play features such as leaderboards (can be implemented to show you vs your friends - actually already in the game but you can't see it) and achievements (only one for testing, wow). You can't see the leaderboards nor the achievement in the game because it was mostly for testing (but might get implemented "soon"). It also shows me some anonymous statistics and whatnot, but nothing personal is ever saved by the game (or is even visible to me)!_
    - _(The plan at first was to use the Play API save feature, but it was removed for the web (of course) shortly before I released the game so the Drive API was my saviour there. Now the plan is to use it for leaderboards and achievements and/or more features it supports, but it hasn't been a priority and has mostly been for testing so far, let me know if you are extremely keen on having achievements or leaderboards and I'll do some form of poll to adjust this priority)_
+ Minor improvements to mobile UI; more to come on this front (has had a low priority - I feel a full overhaul of the UI is required, and will most likely be done in conjunction with my attempt at getting the game on mobile app stores)
+ Tons of fixes, size/position fixes that obscured important texts, might not be perfect but much improved
    - _While the full download has gotten larger (more items and helpers = larger spritesheets + larger codebase), hopefully loading times will stay short or become shorter with improved optimizations (coming). An increase to cache times will help a lot after the first visit_
+ **"Fast Travel"** setting is still in beta but has been improved - it is only recommended if you do not experience issues using it and/or if your patience is low, otherwise I suggest leaving it unchecked for now
    - _What it does: instead of having to refresh the page each time the location is changed, the page will only reload once every few location changes, if it is turned on (this frees up resources and resets the 'engine', which improves performance & reduces risk of nasty bugs)_
+ For the nerds: over 400 git commits so far since last release
    - _The last release was long ago, but still, not too shabby for a solo project, right?_
    - _But in reality, I do have friends who help me out with different things on occasion. For this update specifically I owe a big thanks to Chipp (webpack4 build - much faster than my old gulp pipeline - really, really needed this for remote work on my poor laptop), Elin (coaching & imagination-fountain), Micke 1 and Micke 2 (mostly annoying them in various ways). With previous versions, I also have a lot of more friends who have helped with various ideas, tests and whatnot who have not received proper recognition for their help (probably). You know who you are._
+ PS the _"Samsung Browser"_ or _"Samsung Internet"_ is not supported at all! Couldn't figure it out last time, not trying again.
+ This point is here to point out that there are more things that I simply didn't remember!
    - **Many** small things have been done/added/fixed/improved that I have either forgotten or never made a note of, this will most likely continue...
+ More **bugs**! Enjoy finding them! **ALSO: LET ME KNOW IF YOU DO!** Especially if game-breaking. _Please also add which browser you were using as well as the operating system, gotta love web development for multiple platforms. Reach me via twitter/fb/reddit or comment below._


## Upcoming improvements

Some of these are mentioned in the list above, but not all. These are the stuff I intend to do ASAP/very-soon (before any larger changes):

+ Hints/answers for locked helpers on how to unlock them
+ Making the timeline you are on stand out a bit more: it is an important increment to your progress and should be treated as such (current update shows a small text above the DogeDiamonds _(for now just imagine it's a huge flashy/not-flashy beautiful & fantastic & amazingly cool display_))
+ Fixing crucial bugs that (probably) have been introduced in this update (there were more code updates/changes than are visible, which means the chance of something bugging out is at an all-time high! Sell now! Edit: What)
+ Changes from **your** feedback on this update _or your feedback and ideas in general._ Please communicate via twitter/facebook/reddit or comment below and I'll see it for sure, if it seems good and doesn't take too much time, I'll most likely implement it! (A lot of big, time consuming stuff are already planned after this so...) 
+ Balance adjustments are always a strong possibility - no matter the patch
+ Reduction in loading times, improvements to general performance - the usual after-patch microfixes
+ I bet there's a browser or two that is supposed to be supported, but was not tested before release, so let me know

Shortly after THAT, or in the same patch (depending on work ethic and motivation), these are coming:

+ Brand new Settings window(!) - it'll pop up and cover a larger area, as well as split up the check-buttons and whatnot into sections.
    - _Design is already done, "just" requires implementation_
+ Separate FX and Music volume sliders for the new settings (I hope)
+ Other, forgotten things... _as usual_


And after that... lets take this following list with a big grain of salt, as these items might take a long time to do, or never be done at all:

+ A re-do of the inventory system. Displaying multiple rows and (possibly) showing all items in the game (including not-yet-looted, but grayed out or something)
+ Some big content plans that may or may not get done such as:
    - A "special/rare shop" / "traveling salesdoge" (internal name) for unique gear and more usage of DogeDiamonds _(very likely to become reality, DogeDiamonds would love to see more usage)_
    - A special event where you are taken hostage by Cate by its CateStar and have to fight off a hoard of Cates and its Kitten Army (lol?) before being rescued by your shibes or destroying the CateStar (or something else that is fun)! _(My favorite idea/plan but also one of the more time consuming ones, as it requires a lot of changes and additions to the current code-base, as usual...)_
    - More events and random encounters! (Perhaps I should start with an "event system" that can be reused...)
+ Getting the game on Steam (and others, like Epic Games' new store perhaps!)
    - This will depend on how well it will go to use Electron (or similar) for this purpose _(have tried a little basic stuff, seems to work fine, but there seems to be some issues with the Steam API and Electron missing a good library for some features such as the Steam Overlay (which I think is crucial that it works or you can't have the game on steam, maybe? probably?) ...hopefully these issues will have been solved nicely by then!)_
+ Getting the game on App Stores (Android & iOS) - probably Android first as I have a developer account there and it's free, whereas for iOS you pay a yearly fee (last I checked) and a lot more money to even get started (I think they require you to have an OSX device too, which I don't) - this is probably why iOS is usually last/released later for indie projects
    - Very likely to be a big challenge, don't know if the game will run well (or at all) with something like PhoneGap, or how much tweaking I will have to do (will have to get back to you on that one)
+ Translations for some languages (requires quite a bit of work to move all strings (currently ~90% of them are in one file, but the rest are spread out...))

And that's all for plans at the moment (that I could think of).

### If you have read all of the above...

Thank you for taking your time and sorry if you actually read all of it. Also, please excuse the delays with the update in general, I am the worst at guesstimating time and motivating myself (something you guys are really good at!).

If you **didn't read all of it**, you will burn in -- actually, no one blames you, _wise choice._

I can't think of anything else to add, I think I covered most of it. Now go play the game if you haven't already! Unless it's not working now... then try again (F5 F5 F5) and if it still doesn't work, let me know. But it should.

Please work. Please please please. Okay. Bye for now.