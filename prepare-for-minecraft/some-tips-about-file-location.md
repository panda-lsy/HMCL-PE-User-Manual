# Some tips about file location

After downloading minecraft, you need to determine exactly where your version file has been downloaded to make it easier for you to make changes.

### Version Isolation

**To set up, please click** [**here**](../basic-settings/global-game-settings/working-directory.md)****

If you have version isolation enabled, your individual version folders will be

```
HMCLPE/.minecraft/versions/[your-version-name]
```

If not, all your game files will be stored to

```
HMCLPE/.minecraft
```

{% hint style="info" %}
Without version isolation enabled, storing and managing many minecraft versions would be a huge hassle. If you need to change versions, you will need to delete or backup all the old files inside the .minecraft folder. If you just overwrite the new files, there is a good chance that the game will not start(Reason: MOD conflict or MOD is not compatible with Minecraft/Forge/Fabric version).
{% endhint %}

### FAQ

Q:I'm sure there is a version of the game inside HMCLPE. But this folder is empty.

A:Because the folder in the HMCLPE folder is called ".minecraft".The folder name starting with "." is hidden by the phone system by default.You need to find a way to make it show.
