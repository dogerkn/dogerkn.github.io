---
layout: post
title: Patch Notes 2.4d
---

# Patch notes for version 2.4d (no auto-loot yet, it's next!)

This is a short post detailing the changes recently uploaded. **At the bottom of the post is a poll about the biggest change in this patch.** Use it to let me know if you liked or did not like this change (you can of course also contact me about it).

Before we get to the changes, have you seen [Dogeminerdev on instagram](https://www.instagram.com/dogeminerdev/){:target="_blank" title="Dogeminer on Instagram"}? Only those following the Facebook page could've gotten a notification about it as I have not advertised it anywhere yet - I'm still not sure it's going to work out or is a good idea, but at least it's not spammy: [There's only one post right now.](https://www.instagram.com/p/BsM1_rfBvWM/){:target="_blank" title="First dogeminer post on instagram"} Anyway, if instagram is your thing, go follow that awesome account and we'll see if magic happens.

## Changes:

+ Fixed helper damage not starting properly if changing location
+ Fixed an incorrect string one of the Mining Shibe upgrades
+ Changed the behaviour of *prestige* to not spiral out of control (hopefully)
    - _Might need changing again, need to test it on my personal guinea pigs first (that's you)_
    - _There were multiple changes here but I believe I got the big bad one_
+ Various *small* optimizations to performance, still much more needed for low-end machines - I've only done what I could do quickly so far
    - _There's at least one pretty big thing I can do about the performance according to the docs, but it might take a little time_
    - _Unless I've missed something that is doing more work than is required, I'm going to check the performance audits for this and get more into detail about what costs the most to perform_
+ **Big:** Changed the font on this amazing blog, among a few minor CSS changes for readability.
+ Reduced amount of DogeDiamonds that sometimes drop from containers *by very little*
+ Reduced the strength of +Wow (will also be reducing the effect it has on itself)
    - _This was done a couple of days ago but I didn't blog about it (wow)_
    - _This is probably the best stat in the game (one wow to rule them all), so it makes sense it should be weaker and take more time to really shine_
+ Fixed wrong value being shown for the D.I.A. badge during the chat the agent *(and also stopped it from receiving benefits from +wow (sometimes?). It was not on purpose)*
+ Did not fix NewsDoge sometimes going black (only seen this happen on phones so far, wth?)
+ Think I fixed the NewsDoge issue where he cancels his news reel just as he is about to speak (rude!)
+ **Actual big change:** removed +DPS from Super Fortunes (i.e. following time travel/prestige) \*loud gasp\*
    - _This will reduce your "free" income at the start of a new timeline or location_
    - _More importantly, it helps to balance the game by a lot!_
    - _It greatly reduces the prestige issue with getting too many items too fast (you end up just picking things up very fast, not great gameplay...)_
    - _It also increases the time it takes to get to the next location after time traveling, which was very unbalanced_
    - _For those of you who have been playing for a while now, you'll still be looting more than playing due to your sick stats, my advice: either wait for auto-loot **or** restart from scratch and help me check the new balance!_
    - _**There's a poll at the bottom of this post**, use it to **let me know what you think** of this change_

**The big thing** I really need to implement ASAP is **the auto-loot feature** (optional to use ofc), that *gets unlocked after the first prestige*. I've got it planned out and ready to get at it right away, _I don't like it when people get to play the new update and somehow the awesomeness is overshadowed by too much loot! Who'd a thunk? Somehow should have playtested this! How did this get past Q&A? ...Oh right..._

The root of the cause is that it gets boring to pick up containers quickly when you're so full of stats that *the only thing you have time to do* is *open boxes* because the rock is constantly being broken and your loot find is OP. It's cool, but not fun to play!

I've wanted and semi-planned an auto-loot feature before the _prestige_ even existed (I couldn't find out a good lore/not ugly implementation; I wanted a little dog to carry your burdens). But no worries, I'll make it simpler. Once auto-looting is active, items dropped from the rock that doesn't disappear by themselves _(in this case lootboxes & dogediamonds)_ will be picked up _(auto-opened too, without a pop-up in your face, in the case of lootboxes)_ and quickly fly straight into your inventory! Sounds neat, no?

## So I removed +DPS from your Super Fortunes

I want to make it clear on why I did that and also tell you that this decision was not taken lightly.

_I really don't like removing any hard-earned stats from following along (I still don't like leaving the pickaxes, but they'd be too strong, and we needed something to trade for dogediamonds)._

However, +DPS was the main perpetrator that was causing rocks to get destroyed like paper, faster than could can loot _(and it could happen as soon as the first or second prestige/timeline)_. It made a lot of sense to me, perhaps it should never have existed (boring!), but I didn't need to completely remove it - only from timetravel/prestige.

If you feel worried about a change such as this, stop! _And don't be so selfish!_ You'll find plenty of new +DPS gear with better stats the further you progress, until, of course, you time travel.

Maybe it's not a good idea, what do I know. Time will tell. Let me know if you think it is (and why), only you have the power to change this.

## Before you go, please answer this poll about the DPS time travel change

[**Click here to go to the strawpoll!**](https://www.strawpoll.me/17185959){:target="_blank" title="A poll about the +DPS stat"}

Stay classy, shibes diego.

