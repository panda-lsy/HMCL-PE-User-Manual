# Asking for Help

## Preparation

Before you can rule out problems caused by mods or games, you need to consider that there is a problem with the Java VM driver (launcher) or hardware.

## How to find the location of your minecraft folder?

### 1.Go to your game version list,Click on the minecraft version you have downloaded

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

### _**Repeat, the location of your minecraft folder. The following will be replaced with "\[minecraft-version]":**_

When you use version isolation, each of your minecraft version folders will be in `HMCLPE/.minecraft/versions/[your-version-name]`

If not_**,**_your minecraft version folders will be in

`HMCLPE/.minecraft`

### **Before seeking help, you need to have the following documents ready:**

* [ ] latest.log

Location:_**`[minecraft-version]/logs/latest.log`**_

* [ ] Lastest crash log

Location:_**`[minecraft-version]/crash-reports`**_

{% hint style="info" %}
Crash reports are generally named as

crash-year-month-day_hour.min.second-type.txt

Example: crash-2022-12-01_12.00.00-client.txt

The types include client (client side) and server (server side), client side is the game launched directly with a launcher (such as HMCL-PE), server side is the server launched with the opening service file.
{% endhint %}

* [ ] What you did before the crash, etc., some information about your playtime

Location:_**`Your Brain`**_

## Asking for Help

There are two ways asking for help:

### Committing [Issues](https://github.com/Tungstend/HMCL-PE-CN/issues) to GitHub

#### Format reference:

Copy this block of code, paste it into the input box, and click Preview to check if the formatting is correct before posting

{% code overflow="wrap" %}
````markup
<details>
<summary>Log file name</summary>

```
The contents of the log file, copy and paste it here with a text editor and delete the text of this line
```
</details>
````
{% endcode %}

Multiple documents to copy by yourself

{% code overflow="wrap" %}
````markup
<details>
<summary>Log file name ONE</summary>

```
The contents of the log file, copy and paste it here with a text editor and delete the text of this line
```
</details>
<details>
<summary>Log file name TWO</summary>

```
The contents of the log file, copy and paste it here with a text editor and delete the text of this line
```
</details>
<details>
<summary>Log file name THREE</summary>

```
The contents of the log file, copy and paste it here with a text editor and delete the text of this line
```
</details>
````
{% endcode %}

### Get help at Discord

You can upload your files in Discord's "Support:#on-game-crash-report."

You can also send files directly to #General for help. There are more people online there, but not all of them may be able to answer your questions.

#### This is a tutorial from the official Discord:

> #### Summary
>
> \* **Navigate to the help channel** which best suits the nature of your issue&#x20;
>
> \* **Open a thread** describing the issue with as much pertinent detail as possible e.g
>
> * Relevant information from your logs
> * When was the issue first observed,was there a time recently when the issue did not exist, what has changed since
> * What tutorials or help have you already tried
>
> \***When your issue has been solved**, **please post** :heavy\_check\_mark: **as the final message in the thread**, and archive the thread
>
> **\*Do not beg for help** - when someone who is familiar with your ssue is available to offer assistance they will do so. Do not ping members for assistance without their prior consent. Please be patient.
>
> **\*Do not cross post in seeking assistance**
>
> \*We do not represent Canonical, we cannot provide "official" support or log your bugs

#### What are threads and how do we use them?

You can click on the [links](../../asking-questions-by-third-party-software/discord/how-to-use-threads.md) to jump to the [official tutorials](../../asking-questions-by-third-party-software/discord/how-to-use-threads.md) included in the manual.

You can also get the tutorial in Discord under ["Support:#readme"](https://discord.com/channels/995291757799538688/1003984509412315166).

{% hint style="danger" %}
Note: Please do not copy the content of the file and paste it in Discord, this will not only lead to untidy content, but will also take up a lot of your chat space
{% endhint %}

_**``**_
