# Getting Started

If you still have an issue after following this guide, feel free to ask for support in the [Return of Modding Discord](https://discord.gg/VjS57cszMq).

## Installation with r2modman

[This](https://lethal.wiki/installation/installing-r2modman) is a guide made for Lethal Company but it’s pretty good so just pretend it’s for RoRR.

## Manual Installation

If you wish to install mods manually for whatever reason, you can do that too.

### Install ReturnOfModding

ReturnOfModding can be found [here](https://thunderstore.io/c/risk-of-rain-returns/p/ReturnOfModding/ReturnOfModding/).

Click on Manual Download and extract the .zip.

![image](https://github.com/user-attachments/assets/d2822eff-9ffd-4312-9fb9-4f59597721f2)

### Mod loader setup

Open the folder, and inside of `ReturnOfModdingPack`, there is a file called `version.dll`.

Navigate to the game directory location; this is usually found at:

`C:\Program Files (x86)\Steam\steamapps\common\Risk of Rain Returns`

This folder should contain the game executable `Risk of Rain Returns.exe`.

Place `version.dll` inside with it.

### First time launch

Launch the game once.

This will generate a folder called ReturnOfModding in the game directory.

![image](https://github.com/user-attachments/assets/b9b1107e-0592-4579-9d7c-97c6af6e2571)

### Installing mods

At this point, the setup is complete!

Download any mods (and their dependencies) you wish from [Thunderstore](https://thunderstore.io/c/risk-of-rain-returns/) (using Manual Download)
and extract them to the `ReturnOfModding/plugins` folder.

## Linux installation

- Run the game at least once, to make sure steam generates the wineprefix. Doesn't have to fully launch or anything, steam just has to try launching the executable.

- Put the version.dll in the game files or use r2modman. This is done in the same way as you would on Windows.

- Get `protontricks` on your system, and run `protontricks 1337520 dxvk`. Alternatively, if you know how to, run `winetricks dxvk` after setting it up to use the correct `wineprefix`.

- Set the launch options to `WINEDLLOVERRIDES="version=n,b" %command%`

![image](https://github.com/user-attachments/assets/c4fa39a9-96b8-492c-a0c5-c85b7d35c1f3)

- If the game doesn't launch after specifying the launch option, it might help to go into the game's properties and force it to use Proton Experimental in the compatibility tab.