# Novus _Deceptus_
Novus _Deceptus_ is a hacked client for Terraria. Original code copyright ReLogic. Please note that this client _will not work_ unless you have bought and played (at least once) Terraria, as this is not a _cracked client_.


[Installation tutorial](https://github.com/NovusGames/Deceptus/blob/master/INSTALLATION.md)

[Planned Features](https://github.com/NovusGames/Deceptus/blob/master/PLANNED_FEATURES.md)



Current Features (BETA v0.0.0.1):



### Lighting
`/light` toggles light on/off.

`/light <brightness>` sets light brightness. `brightness` is an number from 0 (off) to 255 (full on).

`/light <r> <g> <b>` sets light red green blue component. `r, g, b` are all numbers from 0 (off) to 255 (full on).

`/disco` toggles disco lighting around you on/off.

### Block Mining
`/boxmine` toggles the function to press the `k` key to mine all blocks within 10 blocks of you. When on, press (and hold) `k` to mine at will.

`/boxmine square` switches the k-mine shape to a 10x10 block square. Default.

`/boxmine circle` switches the k-mine shape to a 10 block (diameter) circle.

`/boxmine front` switches the k-mine shape to the 3 blocks in front of you.

`/destroy_world yes` mines all blocks in the world (that are able to be mined, i.e. not full chests or the blocks under them) when the user clicks `Yes` to a confirmation that appears. This lags a lot, and when it's done we reccomend saving and reloading your world asap.

### Cheats
`/heal` heals the player of mana and health.

`/give <item ID>` gives the player an item with the id of `<item ID>`. `<item ID>` can be the item name (no spaces) or it's numeric ID.

`/god` toggles `godmode` on/off. See [godmode.md](https://github.com/NovusGames/Deceptus/blob/master/GODMODE.md) for list of things it does.

`/tp` teleports your player to your mouse.

`/addhome <home name>` adds* a home location for use with `/tphome`.

`/tphome <home name>` teleports you to the home defined by `<home name>`.



\* This is only saved per-session, due to the fact that the client does not edit save files to preserve files between hacked and vanilla Terraria.
