---
layout: post
title: Next Post Will Come When Testing Is Underway
---

## Since I am utterly useless at deadlines, the next blog post you will see here will come during the final testing phase.

Which, in short, means that the update to Dogeminer will be about 1-3 weeks from release from that post. Not this post. The next post. Ok? Good! This post will be long and rambly, so get your reading glasses out, because it's procastination time.

Honestly, at this size, this is more of an expansion than an update. I'd call it a DLC but that word makes me puke a little. (except if you're CD Project Red, Psyonix or any other game maker that doesn't charge money for DLCs. If it's not free, it's not "downloadable content" (what DLC _used to_ stand for) any more, its closer to _pay to download-content_, but the industry has misused this term a lot - as with many things and other industries, I'm sure).

Granted, expansions are usually something that cost too, but at least the word doesn't come with a nasty taste. _I think I will still call this an update for now, since it is running on the web anyway._

Due to my memory not being able to keep it all in, I am forgetting certain things that need to get done, constantly - which leads to miscalculated deadlines. Like oops, yeah, the switch to webpack (much better/faster than what I used to have) has increased both the landing page and play page sizes considerably than before (I had a lot of optimizations back then and webpack does things very differently), so they will need optimizing when the actual game is done. I didn't think of that before, you see. It won't be more than a day or two in effective work to fix, but it's just an example of multiple things I tend to forget when attempting to set a deadline.

That's not to say that me setting a deadline was a bad idea personally; it got me really working hard for weeks, until the deadline was missed and I derailed that train. **Not to worry, I'm back on the horse now.**

### What's left?! Tell us! We need to know!

Let's try to give you some actual information. I've made a bunch of new items, added 2-3 new upgrades for almost every helper in the game, which is about ~70-80 total upgrades (most are quite similar), as well as fixed a ton of bugs and whatnot. The upgrades are 100% ready for testing, _but I will need to make a few more **pickaxes** and **fortunes** before I am satisfied (currently at something like +20 new pickaxes and +20 new fortunes, maybe more)_, this should take about a couple of days to make, then another to test. Actually, none of the new items have been tested as I haven't put them into the loot system yet (prefer to wait and see what I have and place them where they should fit the most), but they usually work as expected and if there are bugs with these, they are at least easy and quick to repair.

There's some story elements and atleast one bonus event that I'm thinking of doing before release too (Mars needs some love, on average most players drop out halfway through Mars, not unexpected as that's when the game first becomes more idle and grinding is slow - which is a shame because there's much more content ahead - it's just not apparent enough - and reducing that grind will probably help).

This is all ignoring what's been added in the past; both a new location (Titan) and a completely new feature with the _Doge Intelligence Agency_ mission _(which is dogeminers "soft-ish reset" / prestige-like / ascension-like feature + major diamond income source early/mid game)_. You know what, I'll try to mention everything that's about to be released (keep in mind, **I will** forget some things).

#### This list should probably be the upcoming patch notes:    
    

+ **New location**, as usual it has 6 unique helpers, including a special guest appearance by fan favorite Elon (not adding last name because you all know who I mean) and a reappearance of the Time Travel T-Rex from the original game. This location is robotic themed, it'll be quite obvious.
+ **DIA mission** for rewards plus soft-resetting loot and location/helper progress, while keeping stats and diamonds. PS you need a Time Machine Mining Rig to do this, I think I'll add a hint for new players, as it doesn't unlock for purchase on Earth until you've progressed a bit into Mars (subject to change)
    - _The mission rewards get better the further you get, so doing it as soon as its available might not be optimal - or it might be, I haven't done the math lol._
+ **Tons** of new items to loot (or well, ~50 or so... I'm not an AAA company)
+ Each locations Base now upgrades the BONUS COIN that appears randomly, both in stats given (and bonus time), as well as in how they look. They become smaller for higher levels, so try not to miss them!
    - _Also added 1 extra second of stay time for the bonus coins to make them a little easier to get._
+ It has become **easier to farm Dogediamonds** (not just through the mission) thanks to the rocks and clouds being easier to break, and will increase slower in difficulty (or rather amount of coins inside each rock). Diamonds are still only used for upgrades (which you will probably want for the lategame upgrades), but another alternative method of using diamonds is planned (special shop)
    - _This is especially true for late game where an empty (of items) legendary container will have a 1/3 chance of giving you ~2-5 diamonds (2/3 chance of getting coins). With a good pickaxe or fancy upgrades, well, guess. Will be more fun to farm once the special shop comes around, but it'll take a while - like a year, if we go by previous update history and because I probably will be adding more than just that - but maybe I learned something this time around)_
+ Titan's final helper upgrades will help in **unlocking two new helper upgrades** (one at a time, depending on that specific helpers upgrade level)
    - _This will give almost every helper on every location a new upgrade (at first just a couple of upgrades, but the final upgrade of the final helper is the big one)_
    - _This is also a new feature; upgrades that are, by default, locked until a criteria is met_
+ Existing late game helpers have been buffed and some may even be cheaper
    - _They were expensive and weak on purpose because there wasn't any content after them, sorry if you farmed forever getting those Dogebility Drive upgrades (at least they will be powerful!)_
+ Instead of just giving you coins, seemingly forever before you get a better container - the game will detect that the current container has no items and go to a higher quality container with new items, up until legendary quality containers.
+ Slight improvements to mobile UI; much more to come (has had a very low priority - that will come in combination with putting it on app stores)
+ Click/tap the DPS of a helper in the shop to see its base dps as well as its bonus DPS from stats.
+ Tons of fixes, size/position fixes that obscured important texts, might not be perfect but much improved.
    - _While the full download has gotten larger (more items and helpers = larger spritesheets), hopefully loading times will stay short or become shorter with improved optimizations there. An increase to cache times will help a lot after the first visit._
+ Improvements to cloud saving, might make it work smoother and more reliably, but will still not work on all devices/browsers due to how they treat 3rd party stuff by default (even though the only 3rd party is Google here)
+ For the nerds: about ~350 commits to git so far since release. Damn.
+ This point is here to point out that there are more things that I simply didn't remember.
+ Introduced new bugs, can you catch them all? I bet you won't have to

#### So, estimations?

Short answer; not really. 3-4 weeks minimum for release, but that might as well become doubled.

I haven't even thought about testing on other devices, browsers or operating systems yet, which usually takes a few days up to a week for this game (if worked on every day and not too many issues discovered).

I can probably get more help here if I ask around, but this help is usually more comprehensive and fast when it comes from my friends, and I currently have a few friends willing to lend a hand, so that's great, especially since I don't own all popular devices (e.g. iPhone) but some friends do.

Which reminds me... I really need to add a credits scene or page.

All in due time; I'm planning on having one either after the game has been completed (all items found, helpers upgraded to max, mission(s) done + maybe some sort of ending location/sequence/mission to tie it up - you will still be able to continue to play for as long as you want afterwards - _no worries, your procrastination is my duty_).

This is also not to mention what I _haven't_ thought of, **not because I'm deliberately doing so**, but because I just _don't remember to think about it until it comes around._ Sotpid brain.

The tablet and phone modes could use a more user friendly shop UI navigation, in my opinion. I'm sure many agree. The phone mode might need a complete overhaul actually, but that's future stuff; most of people who play games on websites do so on computers, and many on tablets, but very few on phones - they prefer apps (even though you can technically add the site to your homescreen and play it much like an app would be played).

So, back to the topic, estimations? Eh, don't count on them. I'll give it about 2-3 weeks until test ready. Probably miscalculating that and it ends up being 3-6 weeks, just saying. Then I'd count on 2 more weeks for testing to be done (or 4, who knows, not me). It sounds like a lot, but you know the old adage, time flies when you're having... uh... school? no, that's not right... well. 

**Next post should be more fun, as testing will be underway and a release date _should_ be possible to set.**

Thanks for reading.