# Solve the problem yourself(WIP)

#### Minecraft Mod players, sometimes due to encounter crash,They will angry.Then slowly research to find a solution to the crash or very easy, here I will lay some tips for your reference

## Check Modlist

For beginners, the first thing you can do is to start by looking at the bottom of the entire crash log, where there is a self-shaped table with all the modules that have been identified.

![](<../../.gitbook/assets/image (5).png>)

Here we note the column with LCHI or LCHE on the left, each letter carries its own meaning

| Letter                              | Meaning                                                                                           |
| ----------------------------------- | ------------------------------------------------------------------------------------------------- |
| <mark style="color:red;">'U'</mark> | Unloaded<mark style="color:red;">(Indicates that this mod was aborted while loading.)</mark>      |
| <mark style="color:red;">'E'</mark> | Errored<mark style="color:red;">(Indicates that an error occurred while loading this mod.)</mark> |
| 'D'                                 | Disabled(Indicates that this mod is a disabled mod.)                                              |
| 'L'                                 | Loaded                                                                                            |
| 'C'                                 | Constructed                                                                                       |
| 'H'                                 | Pre-initialized                                                                                   |
| 'I'                                 | Initialized                                                                                       |
| 'J'                                 | Post-initialized                                                                                  |
| 'A'                                 | Available                                                                                         |

## Deeper Analysis

![](<../../.gitbook/assets/image (1).png>)

Why is there also a place at the top that shows the mod where the error occurred, so if I look at it from the top will I get a more detailed answer?

Yes, if we look at the sentences following Description and Caused by above, we can roughly determine who(WHAT MOD) is behind it.

