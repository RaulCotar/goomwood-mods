# My Gloomwood Mod Collection

## TODO for myself:
- add images/gifs for the holster
- finish 1 more mod
- restructure the other repos to simplify the release process
- talk about game balance and trade-offs?


This is a collection of mods meant to create a "Vanilla+" experience.
Each extension is kept separate so you can choose what suits your preferences and play style.
Feel free to leave feedback and ideas in the Steam discussion pages or create issues here on GitHub.
Pull requests with your own mods are also welcome if they follow similar installation instructions.

I'm keeping the source code private for now, but I'll reconsider this based on the feedback I get from the community and the developers.
My goal is not to ruin the fun for the players or cause trouble to the developers, so I'll take the mods down if that happens.


## Mods

### 0. [BepInEx](</0. BepInEx>)  ➠  [![](/dlicon.svg) BepInEx_win_x64_5.4.23.3.zip](<https://raw.githubusercontent.com/RaulCotar/gloomwood-mods/refs/heads/master/0. BepInEx/BepInEx_win_x64_5.4.23.3.zip>)
Core dependency. Read more in the installation instructions below.

### 1. [Quick Tonic](</1. Quick Tonic>)  ➠  [![](/dlicon.svg) quick_tonic_0.1.1.zip](<https://raw.githubusercontent.com/RaulCotar/gloomwood-mods/refs/heads/master/1. Quick Tonic/quick_tonic_0.1.1.zip>)
The doctor can now inject himself with the Vitalizing Tonic without opening his gentleman's case, just like he can eat food directly off a table.

### 2. [Gun Holster](</2. Holster>)  ➠  [![](/dlicon.svg) holster_1.0.0.zip](<https://raw.githubusercontent.com/RaulCotar/gloomwood-mods/refs/heads/master/2. Holster/holster_1.0.0.zip>)
The holster is a piece of equipment that, upon being picked up, grants the doctor an extra inventory slot that accepts either a revolver or a flare gun. It functions similarly to the gentleman's case Upgrade in the sense that it is not an item the doctor can pick up and carry/wear, but a permanent modifier.

### 3. Future ideas
- **A small new area/level:** maybe a 4 room house with a few enemies somewhere?
- **Custom difficulty settings:** alter individual settings like enemy healh and damage multiplier, enemy vision angle/range, item spawns, player health, etc.? The game code allows for some of this (not exposed through the difficulty settings in-game), but I'm not sure how codependent the settings are. Also, changing the experience this much is can of worms I might not be ready to open.


## Install a mod
It's really easy - just download the mod file and unzip it inside the game folder.  
No need to install, run or compile any programs :)

Currently, all mods depend on the [BepInEx](https://bepinex.com/) framework, so you need to install [0. BepInEx](</0. BepInEx>) first. This is done the same way as any other mod - download and unzip.

> [!IMPORTANT]
> **Windows users** can ignore this.
>
> **Linux users** (like myself) need to set the environment variable `WINEDLLOVERRIDES` to `"winhttp.dll=n,b"` before launching the game in order to make BepInEx work properly with Proton and Wine.
> 
> If you use **Steam** you can configure this in *Properties → General → Launch Options*: `WINEDLLOVERRIDES="winhttp.dll=n,b" %command%`


## Uninstall a mod
Since some mods may add data to save files, uninstalling them may require you to perform some actions in-game before you can safely delete the mod files. These may include exiting a custom location or dropping items from modded inventory slots.

Each mod has a file called `UNINSTALL.md` which contains the instructions you need to follow to prepare your save files and remove the mod.


## AI usage disclosure
I used LLMs to help me uncover how different game systems work and write the plugins. I'm not very happy with this, but I don't have enough time and experience with the game internals to do all this myself.  
All of the text you see in this repo and potentially in the game (e.g. notes) are written by hand by me.


## License
- A release of BepInEx is redistributed here under its original [LGPL 2.1 license](</0. BepInEx/LICENSE>).
- All other files are distributed under the [MIT license](/LICENSE).
