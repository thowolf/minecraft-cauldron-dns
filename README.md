# Minecraft DNSTechpack on Cauldron

These are docker images for Minecraft DNSTechpack running on an
[Minecraft Cauldron container](https://registry.hub.docker.com/webhippie/minecraft-cauldron/).


## Usage

```
docker run -v /minecraft/merge -v /minecraft/world -v /minecraft/logs --name minecraft-dns-data busybox true
docker run -p 25565:25565 -d --volumes-from minecraft-dns-data --name minecraft-dns webhippie/minecraft-cauldron-dns:latest start

# Execute this for further available commands
docker exec -ti minecraft-dns manage help
```


## Mods

* Both
  * [AE2 Stuff 0.1.6.14](http://minecraft.curseforge.com/mc-mods/225194-ae2-stuff)
  * [Apple Core 1.1.0](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2222837)
  * [Applied Energistics 2 rv2-beta-8](http://ae2.ae-mod.info/Downloads/)
  * [Aroma1997 Core 1.0.2.9](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1287828)
  * [Aroma1997s Dimensional World 1.0.2.16](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1287828)
  * [Atum 0.6.34](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1288464)
  * [Backpacks 2.0.0](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1286124)
  * [BDLib 1.6.5.52](http://bdew.net/2014/07/15/bdlib-update-for-1-7-210/)
  * [Better Storage 0.12.0.124](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/wip-mods/1442380)
  * [Biblio Craft 1.10.0](http://www.bibliocraftmod.com/)
  * [BiblioWoods Biomes O' Plenty 1.9](http://www.bibliocraftmod.com/?page_id=50#bibliowoods)
  * [BiblioWoods Forestry 1.7](http://www.bibliocraftmod.com/?page_id=50#bibliowoods)
  * [BiblioWoods Natura 1.5](http://www.bibliocraftmod.com/?page_id=50#bibliowoods)
  * [Big Reactors 0.4.0rc11](http://big-reactors.com/)
  * [Binnie's Mods 2.0-dev5](http://minecraft.curseforge.com/mc-mods/223525)
  * [Biomes O' Plenty 2.1.0.1057](http://goo.gl/zMK2S)
  * [Blood Magic 1.3.0a-1](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290532)
  * [Brain Core 0.3.1](http://minecraft.curseforge.com/mc-mods/223346-braincore)
  * [Buildcraft 6.3.4](http://www.mod-buildcraft.com/)
  * [Buildcraft Additions 2.0.2](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2091746)
  * [Carpenter's Blocks 3.3.3](http://mineshopper.github.io/carpentersblocks/)
  * [Chisel 2 2.3.5.31](http://minecraft.curseforge.com/mc-mods/225236-chisel-2)
  * [Code Chicken Core 1.0.4.29](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1279956)
  * [CoFH Core 3.0.0RC5-207](http://teamcofh.com/)
  * [CoFH Lib 1.0.0B8-34](http://teamcofh.com/)
  * [Compact Machines 1.17](http://www.curse.com/mc-mods/minecraft/224218-compact-machines)
  * [Computercraft 1.65](http://www.computercraft.info/)
  * [Dimensional Anchors 59.0.2](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1281065)
  * [Easy Crafting 2.0.1.16](http://www.curse.com/mc-mods/minecraft/224295-easycrafting)
  * [Enchanting Plus 3.0.1](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1286469)
  * [Ender IO 2.2.6.322](http://enderio.com/)
  * [Ender Storage 1.4.5.27](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1279956)
  * [Extended Automation 0.3](http://minecraft.curseforge.com/mc-mods/223347-extended-automation)
  * [Extra Cells 2.2.46b72](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1289077)
  * [Extra Utilities 1.2.0](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/wip-mods/1443963)
  * [Factorization 0.8.88.7](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1284592)
  * [Fastcraft 1.19](http://forum.industrial-craft.net/index.php?page=Thread&threadID=10820)
  * [Forestry 3.4.0.7](http://jenkins.ic2.player.to/job/Forestry/)
  * [Gendustry 1.4.4.54](http://bdew.net/gendustry/)
  * [Gyth 1.0.0](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2319607)
  * [Hats 4.0.1](http://ichun.us/mods/hats/)
  * [Hat Stand 4.0.0](http://ichun.us/mods/hats/hat-stand/)
  * [Hunger Overhaul 1.7.10-beta5](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2222904)
  * [iChun Util 4.1.2](http://ichun.us/mods/ichunutil/)
  * [Iguanas Tinker Tweaks 2.1.2](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2176855)
  * [Immibis Core 59.0.5](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1281065)
  * [Infini Tubes 59.0.3](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1281065)
  * [Inventory Tweaks 1.59-dev-153](http://minecraft.curseforge.com/mc-mods/223094-inventory-tweaks)
  * [Iron Chests 6.0.62.742](http://files.minecraftforge.net/IronChests2/)
  * [JABBA 1.1.4](http://www.mobiusstrip.eu/)
  * [Lucky Block 5.1.0](http://www.minecraftforum.net/forums/t/1292247)
  * [Malisis Core 0.10.5](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2076338)
  * [Malisis Doors 1.4.3](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2076338)
  * [Mantle 0.3.2](http://minecraft.curseforge.com/mc-mods/74924-mantle)
  * [Mekanism 7.1.1.145](http://aidancbrady.com/mekanism/)
  * [Mekanism Generators 7.1.1.145](http://aidancbrady.com/mekanism/)
  * [Mekanism Tools 7.1.1.145](http://aidancbrady.com/mekanism/)
  * [Minefactory Reloaded 2.8.0RC8-86](http://minecraft.curseforge.com/mc-mods/66672-minefactory-reloaded)
  * [Mine Tweaker 3.0.7](http://minetweaker3.powerofbytes.com/)
  * [Mobius Core 1.2.3](http://minecraft.curseforge.com/mc-mods/76734)
  * [Morph 0.9.1](http://ichun.us/mods/morph/)
  * [Morpheus 1.5.19](http://minecraft.curseforge.com/mc-mods/69118-morpheus)
  * [More Swords Mod 3.0.0e](http://minecraft.curseforge.com/mc-mods/59903)
  * [Mystcraft 0.11.0.00](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1280070)
  * [Natura 2.2.0.1](http://minecraft.curseforge.com/mc-mods/74120-natura)
  * [NEI Addons 1.12.3.12](http://bdew.net/neiaddons/)
  * [NEI Plugins 1.1.0.9](https://bitbucket.org/mistaqur/nei_plugins/wiki/Home)
  * [Nether Ores 2.3.0RC4-4](http://minecraft.curseforge.com/mc-mods/66675-netherores)
  * [Not Enough Items 1.0.4.83](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1279956)
  * [Obsidi Plates 3.0.0.18](http://forum.feed-the-beast.com/threads/myrathis-mod-compendium.18505/)
  * [Open Blocks 1.3-snapshot-549](http://openmods.info/)
  * [Open Eye 0.6](http://openeye.openmods.info/download)
  * [Open ModsLib 0.6-snapshot-304](http://openmods.info/)
  * [Open Peripheral Addons 0.2.0-snapshot-145](http://openmods.info/)
  * [Open Peripheral Core 0.5.0-snapshot-191](http://openmods.info/)
  * [Open Peripheral Integration 0.1.0-snapshot-35](http://openmods.info/)
  * [Pam's HarvestCraft 1.7.10g](http://minecraft.curseforge.com/mc-mods/221857-pams-harvestcraft)
  * [Pneumatic Craft 1.5.4-56](http://www.curse.com/mc-mods/minecraft/224125-pneumaticcraft)
  * [Power Converters 3.0.2.38](http://goo.gl/TKD1gk)
  * [Pressure Pipes 1.0.2.50](http://bdew.net/pressure/)
  * [Project Blue 1.1.2](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2260994)
  * [Project E 1.3.0](https://github.com/sinkillerj/ProjectE)
  * [Project Red Base 4.5.14.66](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290357)
  * [Project Red Compat 4.5.14.66](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290357)
  * [Project Red Integration 4.5.14.66](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290357)
  * [Project Red Lighting 4.5.14.66](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290357)
  * [Project Red Mechanical 4.5.14.66](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290357)
  * [Project Red World 4.5.14.66](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290357)
  * [Quarry Plus 2.0.0](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1288467)
  * [Railcraft 9.4.0.0-DNS](http://www.railcraft.info/releases/)
  * [Random Things 2.2.0](http://minecraft.curseforge.com/mc-mods/59816-random-things)
  * [Realistic WorldGen 1.3.01](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1281910)
  * [Redstone Arsenal 1.1.0RC1-19](http://teamcofh.com/)
  * [Remote IO 1.8.1.B84](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1292285)
  * [The Spice of Life 1.2.3](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2091809)
  * [Super Crafting Frame 1.7.10.1](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290201)
  * [Thaumcraft 4.2.1.4](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1292130)
  * [Thaumic Tinkerer 2.5-1.7.10-158](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1289299)
  * [Thermal Expansion 4.0.0RC7-141](http://teamcofh.com/)
  * [Thermal Foundation 1.0.0RC7-62](http://teamcofh.com/)
  * [Tinkers Construct 1.8.2a](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2218638)
  * [Tinkers' Mechworks 0.2.9](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/wip-mods/1446244)
  * [Translocators 1.1.1.14](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1279956)
  * [Tree Capitator 2.0.4](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1281180)
  * [Tubes 2.0.5](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1292474)
  * [Tube Stuff 59.0.1](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1281065)
  * [Twilight Forest 2.3.2](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1276258)
  * [useful DNS 2.2.8](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1291674)
  * [Waila 1.5.8a](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1289765)
  * [Wawla 1.1.1](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2169830)
  * [Witchery 0.20.6](https://sites.google.com/site/witcherymod/home)
  * [WR-CBE 1.4.1.9](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1279956)
* Server
  * [Aroma Backup 0.0.0.5](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1287828)
* Client
  * [Xaero's Minimap 1.3.6](http://www.planetminecraft.com/mod/xaeros-minimap/)


## Versions

* [latest](https://github.com/dockhippie/minecraft-cauldron-dns/tree/master)
  available as ```webhippie/minecraft-cauldron-dns:latest``` at
  [Docker Hub](https://registry.hub.docker.com/u/webhippie/minecraft-cauldron-dns/)
* [1.0.0](https://github.com/dockhippie/minecraft-cauldron-dns/tree/master)
  available as ```webhippie/minecraft-cauldron-dns:1.0.0``` at
  [Docker Hub](https://registry.hub.docker.com/u/webhippie/minecraft-cauldron-dns/)


## Available environment variables

```bash
ENV SERVER_MAXHEAP 2048M
ENV SERVER_MINHEAP 512M
ENV SERVER_MAXPERM 128M
ENV SERVER_OPTS nogui
ENV SERVER_MOTD Minecraft
ENV SERVER_RCONPWD webhippie
```


## Available management commands

```bash
Usage: manage <command> [<args>]

Some useful manage commands are:
   commands          List all available sub commands
   console           Start interactive console
   deop              Deop a specific player
   op                Op a specific player
   save-all          Save the current world state
   save-off          Disable the autosave feature
   save-on           Enable the autosave feature
   say               Say something on the server
   weather-clear     Set the weather to clear
   weather-rain      Set the weather to rain
   weather-thunder   Set the weather to thunder
   whitelist-add     Add player to whitelist
   whitelist-list    Whitelist on the server
   whitelist-off     Disable the whitelist
   whitelist-on      Enable the whitelist
   whitelist-reload  Reload the whitelist
   whitelist-remove  Remove player from whitelist
```


## Contributing

Fork -> Patch -> Push -> Pull Request


## Authors

* [Thomas Boerger](https://github.com/tboerger)


## License

MIT


## Copyright

Copyright (c) 2015 Thomas Boerger <http://www.webhippie.de>
