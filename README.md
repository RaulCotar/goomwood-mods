# My Gloomwood Mod Collection

## TODO for myself:
- add images/gifs for the holster
- finish 1 more mod
- restructure the other repos to simplify the release process


This is a collection of mods meant to create a "Vanilla+" experience.
Each extension is kept separate so you can choose what suits your preferences and play style.
Feel free to leave feedback and ideas in the Steam discussion pages or create issues here on GitHub.
Pull requests with your own mods are also welcome if they follow similar installation instructions.

I'm keeping the source code private for now, but I'll reconsider this based on the feedback I get from the community and the developers.
My goal is not to ruin the fun for the players or cause trouble to the developers, so I'll take the mods down if that happens.


## Mods

### 1. [Gun Holster](<./1. Holster>)  ➠  [󰥦 holster.zip](<https://raw.githubusercontent.com/RaulCotar/gloomwood-mods/refs/heads/master/1. Holster/holster.zip>)
The holster is a piece of equipment that, upon being picked up, grants the doctor an extra inventory slot that accepts either a revolver or a flare gun. It functions similarly to the Gentleman's Case Upgrade in the sense that it is not an item the doctor can pick up and carry/wear, but a permanent modifier.

### 2. Vitalizing Tonic Alt Interact
WIP - The doctor can inject Vitalizing Tonic syringes without having to open his gentleman's case, just like he can eat food.

### 3. Custom Difficulty Settings
WIP - what if you could alter individual settings like enemy healh, enemy vision angle/range, item spawns, player health, etc.?


## Install a mod
It's really easy - just download the mod file and unzip it inside the game folder.  
No need to install, run or compile any programs :)

Currently, all mods depend on the [BepInEx](https://bepinex.com/) framework, so you need to install [0. BepInEx](<./0. BepInEx>) first. This is done the same way as any other mod - download and unzip.

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
- A release of BepInEx is redistributed here under its original [LGPL 2.1 license](<./0. BepInEx/LICENSE>).
- All other files are distributed under the [MIT license](./LICENSE).
