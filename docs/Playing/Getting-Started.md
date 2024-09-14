# Getting Started

If you still have an issue after following this guide, feel free to ask for support in the [Return of Modding Discord](https://discord.gg/VjS57cszMq).

## Using r2modman on Windows

[This](https://lethal.wiki/installation/installing-r2modman) is a guide made for Lethal Company but it’s pretty good so just pretend it’s for RoRR.

## Using r2modman on Linux

- Run the game at least once, to make sure steam generates the wineprefix. Doesn't have to fully launch or anything, steam just has to try launching the executable.

- Put the version.dll in the game files or use r2modman. This is done in the same way as you would on Windows.

- Get `protontricks` on your system, and run `protontricks 1337520 dxvk`. Alternatively, if you know how to, run `winetricks dxvk` after setting it up to use the correct `wineprefix`.

- Set the launch options to `WINEDLLOVERRIDES="version=n,b" %command%`

![image](https://github.com/user-attachments/assets/c4fa39a9-96b8-492c-a0c5-c85b7d35c1f3)

- If the game doesn't launch after specifying the launch option, it might help to go into the game's properties and force it to use Proton Experimental in the compatibility tab.