# Perk Remove

**BO7 Zombies mod for Kronos - Made by Kazuto**

Remove any perk you own by going back to its own perk machine. No refund, and you can buy it again normally.

![Perk Remove](https://github.com/PET3Ro/perk-remove/releases/download/v1/preview.png)

## Features

- Remove an owned perk at its own machine
- Prompt shows the perk name: **Press F to Remove Quick Revive** (Press **X** on controller)
- No refund - Essence is not given back
- Rebuy the perk normally at its usual price
- Eternal perks (Classic Perks) can't be removed
- Removed perks are not given back when you're revived
- Same range as drinking a perk
- Wunderfizz is not changed

## Supported modes

| Mode | Supported |
|---|---|
| Standard | Yes |
| Cursed | Yes |
| Mister Peeks Mayhem | Yes |
| Survival / other modes | No |

Works on every map that has perk machines in these modes.

## How to use

1. Buy a perk.
2. Go back to that perk's machine.
3. When the prompt says **Press F to Remove (perk name)**, press **F** (keyboard) or **X** (controller).
4. The perk is removed from your perk bar.

## Install

### Workshop (recommended)
Open the Kronos launcher, go to the **Workshop**, find **Perk Remove** and click **Install**.

### Manual
Download the files from the [latest release](https://github.com/PET3Ro/perk-remove/releases/latest) and put them here:

```
cod25\kronos\mods\perk_remove\mod.json
cod25\kronos\mods\perk_remove\scripts\zm_perk_remove.gsc
cod25\kronos\mods\perk_remove\lua\zm_perk_remove_post.lua
```

Then turn the mod on in the Mods menu.

> Using an older copy? Delete `zm_perk_remove.gsc` from `kronos\custom_scripts` and `zm_perk_remove_post.lua` from `kronos\Assets\Lua` so the mod isn't loaded twice.

## Compatibility

- Works with **Classic Perks** (by Taylor / @aspect.ofautumn)
- In co-op, the "Press F to Remove..." text line is drawn for the host only. Removing perks works for every player.

## Troubleshooting

- **Prompt says EQUIPPED, no Remove option** - check you're in Standard, Cursed or Mister Peeks Mayhem, and that the mod is enabled.
- **Text line in the wrong spot** - edit `PR_LEFT` / `PR_TOP` at the top of `zm_perk_remove_post.lua`.

## Credits

- **Kazuto** - mod author
- **MeowRaK** - help with the mod

This code was AI-assisted.
