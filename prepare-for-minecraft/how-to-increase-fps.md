---
description: This will teach you how to increase the FPS of minecraft.
---

# How to increase FPS

Most of the content is from the [**Minecraft Wiki**](https://minecraft.fandom.com/wiki/Tutorials/Improving\_frame\_rate).

## Introduction

Frame rate (also known as FPS) is the frequency at which a video device produces a unique continuous image called a frame. Frames are still images that, when combined together, become streamed media, which is the basis for all moving media. The frame rate usually indicates the number of frames per second (FPS).

Low FPS will result in an erratic gaming experience, in extreme cases only showing one frame for a few seconds. Difficult calculations (like lighting many quantities of TNT or spawning a swarm of creatures in Minecraft) will temporarily reduce the FPS or even stop the game screen completely for a few seconds.

## How to check your FPS?

Note that the FPS displayed may not be accurate as the game needs to render all information in the debug screen, so turning off the display will increase it.

Press F3 to display the debug screen, FPS will be displayed underneath the version number in the top left.&#x20;

{% hint style="info" %}
Note: Turning on the debug screen will load the system more, resulting in a lower FPS than when the debug screen is not displayed.
{% endhint %}



## Modifications to the game

### Add Optifine to your game

****[**OptiFine**](https://optifine.net/) (commonly known as the most well-known optimization mod) can improve FPS **considerably** and has been described as a "**boon for low-profile machines**" (see the [**Official website**](https://optifine.net/) for details about what it does and see below the text to learn about how to install). For example, you can customise the amount of various particle effects, and there is a special section for "performance" in the "video settings" with features such as "slow block loading" and "fast rendering". "Fast Render" and other features that might be useful. If you are using Fabric, you will need to include the [**OptiFabric Mod**](https://www.curseforge.com/minecraft/mc-mods/optifabric) **** in the mods directory along with the .jar file from the [**Optifine installer**](installing/install-optifine.md#mod-loader-installation-using-hmcl-pe-1).

**How to download(Skip to tutorials):**[**Click**](download/download-optifine.md)****

**How to Install(Skip to tutorials):**[**Click**](installing/install-optifine.md)****

{% hint style="danger" %}
****[**OptiFine**](https://optifine.net/)  (and [**OptiFabric**](https://www.curseforge.com/minecraft/mc-mods/optifabric)) have huge compatibility issues in a Fabric environment. The Mods described in this article are recommended as they can largely replace [**OptiFine**](https://optifine.net/) and offer better compatibility and better performance.
{% endhint %}

### Try adding the optimised mods recommended in this manual

****[**Click to Jump**](../mod-helper/optimization-mods.md)****

### **C**onfigure the game options menu

To increase the frame rate, most recommendations are to configure the game options menu, which can be accessed via Esc.

#### 1.Render range

Reduce the rendering distance. Too high a rendering distance is obviously bad for the frame rate. For an average PC, 12 to 16 blocks is more than adequate, and if it still lags, 6 to 8 blocks is acceptable, but distant scenery may not be visible; too close a distance (e.g. 2 blocks) will make the game "unplayable".

#### 2.Reduce Graphics from _Fabulous!_ to Fancy or Fast.

Adjust the image quality from excellent or high quality to smooth. This will make the foliage opaque.

{% hint style="info" %}
If you think this doesn't look good you can install OptiFine and adjust the foliage to "Smart"
{% endhint %}

#### 3.Turn off smoothing of lighting and clouds.&#x20;

Turning off smooth lighting will result in the light intensity being calculated for the entire square and the square will most likely not shadow the surrounding area.

#### 4.Reduce your FOV.

&#x20;This is generally not recommended as it can lead to strange images, and if you must do this it is best to reduce the mouse sensitivity accordingly.

#### 5.Turn off V-Sync.

&#x20;Within the maximum frame rate, turn off vertical sync, noting that this may cause horizontal screen tearing when turning the view rapidly.

#### 6.Set Particles to Minimal.

This works better when there is a large column of bubbles underwater.&#x20;

{% hint style="danger" %}
Warning: this will cause the water/lava droplets to be invisible and easy to get drenched in lava unsuspectingly.
{% endhint %}

#### 7.Turn off perspective shake

This will make your screen look smoother. It will also increase your frame rate.

#### 8.Reduce the Mipmap level or set to Off.&#x20;

This will reduce the clarity of distant views.

#### 9.Adjust Fullscreen Options

Set fullscreen to off, this will allow Minecraft to do less loading on the screen and allow the game to run faster. However, if the computer has a better graphics card, when in fullscreen mode this will allow the GPU to spend more time on Minecraft and use less time on other software. It is recommended to test these 2 methods at the same time to see which is more effective.

#### 10.Disable biome smoothing.

#### 11.Stay away from crowds in multiplayer games.

#### 12.In multiplayer games, press Tab.&#x20;

This will show the players online. The more players online, the greater the latency, so this is an issue. Note that this is caused more by network latency than by FPS

#### 13.Tip about Joining a multiplayer game

Joining a multiplayer game created by someone else or joining a server will be smoother than playing a single player world on your own, with cube state updates and calculations such as creature generation and pathfinding being handed over to the multiplayer initiator or server.

### Outside of Minecraft

The following may be effective in increasing frame rates on low profile machines. Please choose according to your needs.

* If you wish, try to close some other software, such as browsers or something that takes up a lot of memory or GPU.
* Allocate more memory to Minecraft.
* Turn down the screen [resolution](../basic-settings/global-game-settings/resolution.md). (Play Minecraft in a window half the size of your screen)





****
