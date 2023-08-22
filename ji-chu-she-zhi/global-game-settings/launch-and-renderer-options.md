---
description: 你可以在这里设置游戏如何启动。
---

# 🎮 启动选项

打开[全局游戏设置界面](./)，找到如下图所示选项：

![](../../.gitbook/assets/Screenshot\_2022-08-15-14-13-39-32\_d17cc25ab2657fb.jpg)

### 游戏启动方式

你可以使用Boat 或者 PojavLauncher来启动游戏。

#### 两种启动方式的优劣？(WIP)

| 启动器        | 优点                       | 缺点 |
| ------------- | -------------------------- | ---- |
| Boat          | （这是官方比较推荐的方式） |      |
| PojavLauncher |                            |      |

### 渲染方式

你有两种方法来渲染游戏。(以下结果由手册作者测试得出，仅供参考)

#### Holy GL4ES(OpenGL 2.1/3.2)

这个渲染器可能会更稳定……

#### VirGLRenderer(OpenGL4.3)

这个渲染器可能会提供更高的帧率……

### FAQ

#### Q:我在选用VirGLRenderer后，游戏的启动界面整个变白了，还出现很多乱七八糟的颜色。

A:你需要更改一下[游戏分辨率](resolution.md)。



#### Q:当我启动游戏后，整个屏幕和物品栏被渲染得很不清楚。

![](../../.gitbook/assets/Screenshot\_2022-08-14-13-38-22-46\_d17cc25ab2657fbd260b0454040eb4aa.jpg)

A1:启用快速渲染（Fast render）再关掉它。

A2:使用资源包（Resource packs）。

{% hint style="danger" %}
对于这个问题还没有准确的答案。如果它们对你没有帮助，请到Github提交[Issue](https://github.com/Tungstend/HMCL-PE/issues)。
{% endhint %}
