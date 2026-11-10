# Quick Tonic  ➠  [![](/dlicon.svg) quick_tonic_0.1.1.zip](<https://raw.githubusercontent.com/RaulCotar/gloomwood-mods/refs/heads/master/1. Quick Tonic/quick_tonic_0.1.1.zip>)

## Synopsis
This mod allows the doctor to inject himself with the Vitalizing Tonic without opening his case. just like he can eat food directly off a table.

The animation is still in place, and it forces the doctor to temporarily lower the items he holds in his hands (like the lantern and a weapon).

## Known bugs
- You can still pick up an item (like a box) while the injection animation is playing, and the item will be dropped automatically when the animation ends.

## Technical details
Sets `AllowQuickUse` for `item_medhypo` and calls `HideWeapons` when the syringe is drawn.
