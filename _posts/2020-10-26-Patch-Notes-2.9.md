---
layout: post
title: Patch Notes 2.9
---


# Patch notes for 2.9 - Patron Bonuses & More

As usual with every update, much of the game content might still be cached in your browser. Should it stop working completely, or if some _really_ weird bugs appear all the time, try your best to hard-refresh (Ctrl/Cmd + F5 on desktops, or sometimes a right-click on the refresh-button in the browser) a couple of times. If it doesn't work; I suggest trying again later.

Should there be issues that needs reporting, it will be reported on Discord, I'm sure. 

## What's new:

**Implemented Patreon-authentication to receive in-game bonuses for your support! <3**

**Patron-specific stuff:**

+ Existing and new [Patrons](https://patreon.com/dogeminer){:target="_blank"} of Dogeminer can authenticate with Patreon for a special Patron-only fortune/badge, as well as some decent buffs!
    - Big thanks to **[Chipp](https://github.com/chippi){:target="_blank"}** who whipped up the authentication & API-integration through Patreon with NodeJS & more
    - As a Patron, simply use one of the _"Login to Patreon"_ buttons ingame and allow Dogeminer to see your username and pledge
    - One of these buttons is under Settings (can't miss it), the other one shows up if you click the new "Patron Status Indicator" next to the inventory (below DogeDiamonds on mobile)
    - _Need to have at least one item in the pickaxe or fortune inventory for the last button to show - it might hide itself for no good reason too... working on that!_
    - _**NOTE:** This is the first version of this implementation, if it is unstable or problematic, it might be disabled temporarily for a quick-fix_
+ _The Patron fortune gives +100 Patronage (new stat) as well as +15% each of Loot, Luck & Wow_
    - _The fortune does **not** disappear from the inventory should the patronage end (you only lose it from a wipe or complete reset)_
+ _The buffs / bonuses that authenticated Patrons also receive is:_
    - **+100 Patronage**
    - **-5% helper cost**
    - **+5% helper DPS** _(multiplicative, unlike similar stats for items)_
    - **+5% DPS on Pickaxes** _(multiplicative, unlike similar stats for items)_
    - **+5 DogeDiamonds per mission**
    - _Patrons are also able to open the **Mystery Box**, even if ad blocking was detected - because the box knows you're a really good Doge!_
    - _Some of these won't be updated/seen in every spot yet, e.g. the new DPS helper upgrades doesn't take the +5% into account yet (and a few more I bet)_
+ _All the stats and buffs are subject to change, should they be under-/overpowered - best way to test it is to do it live!_
    - _Side-note: The Patron fortune is good early on, but gets pretty weak mid- to lategame. The plan is that it will gradually improve itself as you progress through the game to solve this little issue - as for the +patronage stat, which does nothing at the moment.... it will do something! A good idea could be to reduce the Mystery Box timer by the amount in seconds (100 in this case), so about 1½ minute, seems good? (Thanks for the ideas regarding this, uzoqe!)_
+ Added helper names submitted by [Patrons](https://patreon.com/dogeminer){:target="_blank"} (via the Name-A-Shibe tier(s))

**Further changes & stuff:**

+ Added **Download Save** button under Settings _(so you don't have to go to the front page for that precious backup!)_
+ Music has been turned on by default for new players
    - _It became apparent that many players had no idea the game has music, even though there's a nice hint about it_
    - _The music hint now asks if you want to turn off the music instead of turning it on..._
+ Added a **skip button** to the _mission conversation_ on the _DogeTalkie_!
    - _The button shows up if the mission has been completed at least once_  
+ Improved DogeDiamond calculations, plus slightly upped the maximum for the D.I.A. mission
+ Kitten helpers are no longer _slaves_, we realized only Cate would see them as such
    - _Instead of uploading cute pics for dogecoin, they've started streaming instead. Gotta keep up with the times!_
    - _Catching a Cate thief no longer **enslaves** their kittens. Instead the kittens are **rescued!**_
    - _They also do podcasts..._
    - _Most of the Kitten names and descriptions (+their upgrades) were edited_
+ Added a new stat: **Space Rocket Cost**
    - Reduces cost of helpers that are _Space Rockets_
    - Other rockets do not count
    - Stacks both with itself _(if duplicate(s) are found in the Mystery Box)_ as well as with the Patron helper cost reduction buff
    - Can currently be found only on one fortune _(it'll make sense)_ and currently always has a **5%** reduction
    - The _Space Rocket Cost_ stat is not able to be added to Super Fortunes _(for good reason)_, sorry
+ Changed a bunch strings/texts here and there
+ Added another feature that is yet to be used: sounds for pickaxes are now easier to set per-pickaxe in the data
    - _This will allow for the more unique / different pickaxes to sound more special when used in a future patch_
+ Slight position improvements to settings on all layouts
    - _Yes, the mobile version of settings still stinks_
+ **Still washing your hands I hope?**
    - We live in a society!
+ Added code to easily set the _reason_ for why helpers are locked
    - _Only a couple helpers have a reason set for now (the rest get the default)_
    - _Will add the rest of the locked reasons in an upcoming patch now that it's easy yay_
    - _Will also be making it so locked helpers are completely hidden instead of partly, as per a few users request (in another patch too)_
+ Moved the loading spinner _(The bobbing Doge-head...)_ away from the html-pages, now loaded as an svg-object
    - _Removed completely from landing page to improve speed_
    - _This will slightly speed up game loading thanks to caching_
+ Possibly resolved an issue where the wrong location is loaded _(if this works it's a small miracle)_
    - This will be the 7th iteration of the bug-fix _(it's a matrix reference ya youngsters, get off my lawn!!)_
    - This is unrelated, but I think Search Doges are a bit lazy. Maybe we should consider training them harder.
+ Hopefully didn't break ad loading when I attempted to improve the code and delayed their loading
+ Changed the one-time email alert sign-up CTA for the Steam release
    - _Now it's just an email field with a button. Much simple, less odd_
+ **Super Shibes** get names and aren't just "Super Shibe" no more - as requested!
    - _Currently hired, unnamed Super Shibes might not have names assigned... new ones do though!_ 
    - _They use a **new feature in the code**, which makes it easy for me to change/edit which array of names to grab from, wohoo!_
    - _The Super Shibes aren't using the same names as the others heh_ 
+ Little bit of spring cleaning of unused old code, the usual...
+ Changed the "loading text" (before the game has finished loading) around a bit, but not too much
+ Some performance improvements here and there, as well as performance un-improvements, most likely
+ The bug I swallowed should be fully digested by now
+ Disabled some annoying alerts when loading of certain 3rd party scripts fail / are blocked
    - If there's a script error, it probably won't show up as it used to, _if_ it used to...
+ _Slightly_ improved orientation-change handling on mobile devices
+ Fixed closing the social stuff (sidebar) via swiping down in tablet and mobile layouts
    - _Why did it decide to stop working? Guess correctly and win a dogecoin!_
    - _My guess is Unicorns, they're always up to no good_
+ Updated Mystery Box popup-frame texts when it detects ad blocking _(and not patreon authenticated)_ to be more detailed
+ Improved background swaps, it was acting a little weird
+ Removed one-time email alert sign-up from sidebar
    - Mostly reduce loading times and remove a thirty party script
    - There's now a link to back to the front page for this instead
+ _I think cloud save checks have been improved - or they've broken down (temporarily if so), we'll test it live!_ 
+ Added a simple cookie & privacy policy information bottom-bar to the front page for players connecting from within the EU
    - _No one likes this_
    - _... No one at all_
+ All tooltips in inventories broke from a library update, had to spend a day fixing that, so much fun
+ Updated analytics to the latest version (GA 4)
    - Nothing that you care about, I just hope that it still works!
+ Probably a dozen of other small things. As usual... probably not much that is of interest anyway. Maybe something. Idk.

# Happy Halloween!

A minor halloween theme has been added!

Next year it will run through the entirety of October, but this year we'll have it for the Halloween weekend as well as a week or two into November.

There's only ~8 Halloween-specific items to find, no event or anything like that; mostly aesthetics things this time around. There were a few more ideas I wanted to add but time got cut short, lets just call it the 2020 edition, heh.

__I hope I didn't break the game for anyone. Let me know if so. Stay safe!__

**Please report bugs in the _[#bug_reporting](https://dogeminer2.com/discord){:target="_blank"}_ channel on [Discord](https://dogeminer2.com/discord){:target="_blank"}** found under the _"Feedback & Ideas"_ category, **but before you do, try a refresh (F5)** - your browser might have loaded cached files from before. Thank you <3


//**[rkn](https://twitter.com/rkn_dev){:target="_blank"}**
