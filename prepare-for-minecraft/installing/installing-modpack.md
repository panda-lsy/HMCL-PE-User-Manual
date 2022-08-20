# Installing Modpack

{% hint style="danger" %}
**HMCL-PE currently does not have the ability to install Curseforge's Modpack with one click or download Modpack from link, please be patient for the new version.**
{% endhint %}

With that in mind, you still have a way to download and install Modpacks.

{% hint style="info" %}
Next, we will use the installation of RL-Craft as an example to install a Modpack
{% endhint %}

## First,Use HMCL-PE to download a vanilla minecraft with Modloader

### **1.**Check the minecraft version and the modloader used

**You will need to refer to MODPACK for the minecraft version to download.**

**Minecraft version:** the version of Minecraft used in the Modpack

**Modloader Version:**If it is a Forge modpack and the author does not specify the Forge version, please download the latest Forge version in the corresponding minecraft version.(The same is true if it is a Fabric.)

![Click Recent Files to get the Modpack information, but do not go to download it.](<../../.gitbook/assets/image (8) (1).png>)

![Click Recent Files to get the Modpack information, but do not go to download it.](<../../.gitbook/assets/image (7) (2).png>)

### 2.Back to HMCLPE,Go to the download page

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-00-31-30\_d17cc25ab2657fb.jpg)

### 3.Find and go to the download page of the corresponding version of minecraft

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-00-45-11\_d17cc25ab2657fb.jpg)

### 4.Download the corresponding latest version of Modloader

If Modpack's Modloader is Fabric, then download Fabric.

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-01-08-24\_d17cc25ab2657fb.jpg)

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-01-11-11\_d17cc25ab2657fb.jpg)

### 5.Download, then succeed!

{% hint style="info" %}
You can change the version name to make it more recognizable.

Recommend:ModpackName+ModpackVersion

Example:RLCraftv2.9.1c

Note:Don't have spaces in the name, it will cause startup error.(s p a c e)
{% endhint %}

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-01-22-49\_d17cc25ab2657fb.jpg)

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-01-40-41\_d17cc25ab2657fb.jpg)

## Second,Find the game folder where you will be installing the Modpack

### 1.Go to your game version list,Click on the vanilla minecraft you have downloaded

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-12-39-65\_d17cc25ab2657fb.jpg)

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-13-42-33\_d17cc25ab2657fb.jpg)

### 2.Turn on your version settings

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-14-05-37\_d17cc25ab2657fb.jpg)

### 3.Turn on version isolation to make it easy to find the target folder.

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-14-24-89\_d17cc25ab2657fb.jpg)

{% hint style="info" %}
Version isolation is great feature, it allows you to install multiple minecraft versions in one .minecraft folder and they don't affect each other, which solves a lot of unnecessary troubles.
{% endhint %}

### 4.The destination folder where you will drag the Modpack files is here

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-14-35-42\_d17cc25ab2657fb.jpg)

## Third, download Modpack(Full files)

### Method ONE:Download client by Computer Or I have Modpack Full files

#### Download client

Install Curseforge's Modpack using the PC version of the launcher, and then transfer the files to your phone.

The launcher for the Curseforge integration package is currently known to install

* [MultiMC](https://multimc.org/)
* [Plain Craft Launcher 2](https://afdian.net/p/e5c821a4b1ab11eb879b52540025c377)
* [Hello Minecraft! Launcher](https://hmcl.huangyuhui.net/)
* And many more

Once you get the version file, just zip it up, transfer it to your phone and unzip it again.

Then, please look at ["I have Modpack Full files"](installing-modpack.md#i-have-modpack-full-files) section

#### I have Modpack Full files

You have to unzip your file the phone.

Then, you can jump to the next section

### Method TWO:Download Server side(No computer required)

On Curseforge, the server side is usually several times the size of the client side.This is because the mods are placed on the server side in advance.

You just need to unzip the downloaded server package and drag the folder into minecraft's version folder.(This will be mentioned in the next section.)

{% hint style="warning" %}
Attention:

1.The server side of some Modpack is very small, because the author edited the .bat file and needs to download the module resources online on the computer.

2.The server-side MOD may be different from the client-side MOD, which will not affect the content of your game, but may affect the play._Because Modpack authors may remove mods that have no effect on the server side, but play a supporting role on the client side when making the server side._
{% endhint %}

Click to download.

![](<../../.gitbook/assets/image (4) (1).png>)

Then,You have to unzip your file the phone.

## Finally, move the unzipped Modpack file to the working dictionary.

### 1.If you are using an off-the-shelf Modpack, you will need to select the following folder (If you are using the server side,you can skip to the next step without doing this)

* config(Modpack authors change the game mechanics of the mod by modifying the Config file, which can cause the changed file to be different from the initial one.)
* mods
* resourcepacks
* resources(Resource Loader Mod's resource file, usually used for language localization, and modifying the mod's resources.)
* scripts(CraftTweaker Mod's recipe modification file)
* saves
* servers.dat(Server list file)
* kubejs

**But there is no need to move the `versions` folder**

### **2.**Moving files

Open the Modpack folder you unzipped and copy the files inside.

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-49-48-45\_846b44643ec609f.jpg)

Find the working dictionary of HMCL-PE

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-50-22-11\_846b44643ec609f.jpg)

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-50-31-96\_846b44643ec609f.jpg)

Open the working dictionary and paste the copied Modpack file into this folder.

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-50-41-68\_846b44643ec609f.jpg)

### 3.Success！



![](../../.gitbook/assets/Screenshot\_2022-08-16-15-53-42-24\_846b44643ec609f.jpg)

## Final check

You can check if the installation was successful with this section.

#### 1.Open your Minecraft version management interface

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-58-52-18\_d17cc25ab2657fb.jpg)

#### 2.Open MODS management interface

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-59-04-34\_d17cc25ab2657fb.jpg)

If MODS is detected, you have succeeded

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-59-13-14\_d17cc25ab2657fb.jpg)

## Start the game and have fun!

![](../../.gitbook/assets/Screenshot\_2022-08-16-15-59-23-06\_d17cc25ab2657fb.jpg)

{% hint style="success" %}
**This tutorial will be rewritten when HMCL-PE is updated with the Import Modpack feature.**
{% endhint %}

