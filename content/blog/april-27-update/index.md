---
title: April 27
date: "2023-04-27T23:33:42.186Z"
description: "Continuing yesterday's activities and adding suggestions from Dr. Tang."
---

I'll come back to Android in a bit. I want to work out some of the core functionality issues first.

I made adjustments to the minimap:
- There's now a transparent background on the minimap, like you'll see in many games
- Labels have been added to most of the rooms on the minimap


I rebuilt the WebGL version of the game with the changes. I got this error when building for WebGL:  `RuntimeError: call_indirect to a null table entry (evaluating 'dynCall_viii')` Doing a clean build seemed to resolve the issue. I'd like to be able to build both the iOS and WebGL versions at the same time (at least I believe that I'd like such). _I believe that I was actually a few builds behind on updating the Unity Play build due to tunnel vision with the iOS issues._ 

I may be able to acquire a dedicated iOS device between now and the weekend.

I'm now looking into the interaction goals.



### TODO 
- [ ] an in-game menu system to click and navigate throughout the game world, rather than using typical controls.
- [X] Apple Developer account configuration
- [ ] Add a ceiling and lighting
- [ ] deploy game to iPad/iPhone
- [ ] deploy game to Android tablet
- [ ] add music and sound effects
- [ ] a startup menu