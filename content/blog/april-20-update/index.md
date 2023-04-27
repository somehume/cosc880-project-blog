---
title: April 20 
date: "2023-04-20T23:33:42.186Z"
description: "Now to revisit iOS as a build target."
---

I began with continuing Unity's tutorial for publishing for iOS, as I previously got stuck on Step 2, which teaches the process to set up certificates in the Apple Developer Portal. I won't go into much detail about this, as the info is available on the linked pages.

[Unity Learn: Publishing for iOS](https://learn.unity.com/tutorial/publishing-for-ios#)

[Apple Developer: Create a Certificate Signing Request](https://developer.apple.com/help/account/create-certificates/create-a-certificate-signing-request)

### Apple Developer Requirements
If you follow the above two links, you'll see that a CSR needs to be generated, to download the certificate from Apple. Fortunately I'm a Mac user. I'm not sure if this would be possible from Windows.

After generating the certificate, I had to generate an App ID and an App Store Provisioning Profile.


### Unity Publishing Settings
There are also some changes to the Build Settings in the Unity Editor that need to match the information given to Apple during the process of generating the certificate, App ID and Provisioning Profile.

Following the instructions on Unity Learn, I ran into an issue with the Target SDK needing to be set to Device SDK due to my not currently having an iOS device that I can use for development. I hope to acquire one soon. I also forgot where this was set, so I spent an embarrising amount of time in Xcode attempting to change back to the simulator.

### TODO 
- [ ] an in-game menu system to click and navigate throughout the game world, rather than using typical controls.
- [X] Apple Developer account configuration
- [ ] load content onto iPad/iPhone
- [ ] add music and sound effects
- [ ] a startup menu

Latest WebGL Build: https://play.unity.com/mg/other/webgl-6ej

Advisor: [Dr. Ziying Tang](https://www.towson.edu/fcsm/departments/computerinfosci/facultystaff/ztang.html)
