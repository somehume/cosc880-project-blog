---
title: April 29
date: "2023-04-29T00:00:00.000Z"
description: "Repo cleanup, interaction, and final report."
---


## Repo cleanup
Recently I've been wanting to clean up my repository, as there is a bunch of of content from previous interations of the game and various tutorials that aren't being used by the current build of the game. I want to keep the content since I worked on it and it may prove to be useful in the future for something. I currently have 8 projects in my main branch. I initially thought that I'd clean it up by using a branch for each project. I'm now thinking to create a branch to store all tutorials, and another for archives of the earlier game dev attempts. The updated repo should be something like:
- `main` : currently released game build
- `tutorials` : follow along content for tutorials to help with adding features to the game or learning the dev environment
- `archive` : my old content
- `dev` : working branch

For the sake of sanity, I'll delete everything that shouldn't be in a branch except the final game, verify that the `dev` branch is doing what it should do, then go back and remove the game from the `archive` and `tutorials` branches.

### Main and Dev
- MedicalCenter

### Archive
Archive will include:
- The Doors
- HospitalCorridor

### Tutorials will include
- Level
- Maze
- Player
- FPS_Tutorial
- UnityEssentialsMicrogame

As I was in the process of cleaning up, I glanced at the sizes of the other projects. In total, the projects other than the actual game are under 700 MB. This doesn't save me much, but it is still less than what I needed for the final project. I'll look at trimming unused assets and packages from the final project at some point.

-I can only imagine that this would be very confusing for Unity Hub, if Unity Hub was a real boy._ Actually, it just removed the projects that weren't available. Either way, the `dev` branch is the last to commit, besides the `main` branch. I may actually just leave everything in `main`. I am curious about what'll happen when I do a pull request to main. That reminds me that I can now enable the protection features.

I may actually be able to get rid of some of these and still be able to sleep at night, but that isn't a part of the current task. I'll review that some time in the future.

### GPG Keys and GitHub (Side quest)
As a result of looking into securing my `main` branch, I just went down the rabbit hole of keysigning commits to update my GPG key on GitHub. 

## Interaction
My initial idea was to have a menu system to allow the player to select the next game objective. Now I'm thinking that adding a map in the lobby to trigger the menu might be a nice effect; it may also be less complicated.

It seems that I can use the NavMesh feature for automatic navigation as well as a wayfinding pointer. I need to try this in practice.

The interaction looks like it'll take some doing, so I'll start with the NavMesh.


 ## Simplify play area
 Dr. Tang mentioned that I may have too many rooms. To simplify, I can add some doors that cannot be opened. Perhaps I can add some sort of barrier, like caution tape, to prevent the player from reaching certain regions of the level.




## Final report and Presentation
I have just under 2 weeks before I present. I need to create my slide deck and write my final report.


### TODO 
- [ ] an in-game menu system to click and navigate throughout the game world, rather than exclusively using typical controls.
- [ ] Add a path guide to show the player where to go next.
- [ ] add interaction between player and game objects
- [X] Apple Developer account configuration
- [ ] Add a ceiling and lighting
- [ ] deploy game to iPad/iPhone
- [ ] deploy game to Android tablet
- [ ] add music and sound effects
- [ ] a startup menu
- [ ] add source documentation
- [ ] prepare slides
- [X] request paper
- [ ] cleanup repo


Latest WebGL Build: https://play.unity.com/mg/other/webgl-6ej

Advisor: [Dr. Ziying Tang](https://www.towson.edu/fcsm/departments/computerinfosci/facultystaff/ztang.html)
