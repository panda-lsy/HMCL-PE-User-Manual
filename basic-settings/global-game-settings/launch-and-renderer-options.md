---
description: You can use this to modify the way the game starts.
---

# 🎮 Launch & Renderer Options

{% hint style="warning" %}
**If you are using 32bit version provided by**[ **LegacyGamerHD**](https://github.com/LegacyGamerHD)**, please use PojavLauncherRenderer to Launch, or your game will crash.**
{% endhint %}

Open the [Global game settings screen](./), find this:

![](../../.gitbook/assets/Screenshot\_2022-08-15-14-13-39-32\_d17cc25ab2657fb.jpg)

### Game launch

You can launch the game via Boat or PojavLauncher.

#### Advantages and disadvantages of the two startup methods (WIP)

| Launcher        | Advantages        | Disadvantages         |
| --------------- | ----------------- | --------------------- |
| Boat            | More FPS          | Can't Launch Sodium   |
| PojavLauncher   | Can Launch Sodium | Less FPS              |

### Renderer

You have two ways to render the game.

#### Holy GL4ES(OpenGL 2.1/3.2)

This renderer is more stable(Manual writer's test conclusions, for reference only)

#### VirGLRenderer(OpenGL4.3)

This renderer will give your game a higher FPS(Manual writer's test conclusions, for reference only)

### FAQ

#### Q:When I use the VirGLRenderer, the game screen turns white during startup and the colors become confusing.

A:You need to change the [Resolution](resolution.md).



#### Q:When I opened the game, the screen and the item bar were rendered very unclear

![](../../.gitbook/assets/Screenshot\_2022-08-14-13-38-22-46\_d17cc25ab2657fbd260b0454040eb4aa.jpg)

A1:Turn on Fast render and turn back it off

A2:Just use resourcepacks

{% hint style="danger" %}
There is no accurate answer to this question yet, if you have tried everything to no avail, please go to Github and submit [Issue](https://github.com/Tungstend/HMCL-PE/issues).
{% endhint %}
