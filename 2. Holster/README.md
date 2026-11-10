# Gun Holster  ➠  [![](/dlicon.svg) holster_1.0.0.zip](<https://raw.githubusercontent.com/RaulCotar/gloomwood-mods/refs/heads/master/2. Holster/holster_1.0.0.zip>)

## Synopsis
The holster is a piece of equipment that, upon being picked up, grants the doctor an extra inventory slot that accepts either a revolver or a flare gun. It's like the melee slot but for handguns. Any weapons in the slot can be reloaded/unloaded as usual.

The holster functions similarly to the Gentleman's Case Upgrade in the sense that it is not an item the doctor can pick up and carry/wear, but a permanent modifier.

## How to get it
Currently there is only one holster in the game and it can be found by exploring the word.

<details>
<summary><strong>Location hint: (spoiler)</strong></summary>
A high place at the bottom of the world.
</details>

<details>
<summary><strong>Location picture: (spoiler)</strong></summary>
todo
</details>

## Technical details
It's a pickup called `item_pistolholster_upgrade`. You can `spawn` or `give` it with console commands. Under the hood it is a modified version of the suitcase upgrade that modifies the player state to add a modified version of the melee inventory grid.
