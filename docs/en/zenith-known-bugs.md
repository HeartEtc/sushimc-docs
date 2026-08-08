# Known Issues

> Some known issues during gameplay — refer to these to help you avoid the pitfalls.

## Memory Issues

Due to poor memory optimization in the [Cataclysm](https://www.mcmod.cn/class/5214.html) and [Sable](https://www.mcmod.cn/class/26344.html) mods, the client experiences significant memory pressure during gameplay. We recommend allocating as much memory as possible (at least 6 GB recommended).


## NBT Loss

Special equipment provided by the [Incendium](https://www.mcmod.cn/class/4064.html) datapack is implemented by adding special NBT entries to vanilla equipment. Incendium's compatibility with Cataclysm on the server is poor, which may cause Incendium-generated loot equipment to lose its NBT entries and degrade into ordinary vanilla equipment. There is currently no known solution.


## Rope Lag

The Rope provided by the Sable mod causes slight lag on both the client and server when pulling physical structures, which is especially noticeable in large quantities. We recommend minimizing rope usage; for decoration, consider the chain connections from the [Bits n' Bobs](https://www.mcmod.cn/class/23660.html) mod.


## Fall to death with a jetpack

After equipping a jetpack from [Create:Jetpacks](https://www.mcmod.cn/class/7338.html) mod and re-joining the server, you can fall to death even holding shift while falling. To solve this, turn off and on your jetpack, or take it off from your armor slot and equip it again.
