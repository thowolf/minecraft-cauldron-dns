# Minecraft DNSTechpack on Cauldron

These are docker images for Minecraft DNSTechpack running on an
[Minecraft Cauldron container](https://registry.hub.docker.com/webhippie/minecraft-cauldron/)


## Usage

```
docker run -v /minecraft/merge -v /minecraft/world -v /minecraft/logs --name minecraft-dns-data busybox true
docker run -p 25565:25565 -d --volumes-from minecraft-dns-data --name minecraft-dns webhippie/minecraft-cauldron-dns:latest start

# Execute this for further available commands
docker exec -ti minecraft-dns manage help
```


## Mods

* Server
  * [AE2Stuff 0.1.6.14](http://minecraft.curseforge.com/mc-mods/225194-ae2-stuff)
  * [AppleCore 1.1.0](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2222837)
  * [AppliedEnergistics2 rv2-beta-8](http://ae2.ae-mod.info/Downloads/)
  * [Aroma1997Core 1.0.2.9](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1287828)
  * [Aroma1997sDimensionalWorld 1.0.2.16](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1287828)
  * [Atum 0.6.34](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1288464)
  * [Backpacks 2.0.0](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1286124)
  * [BDLib 1.6.5.52](http://bdew.net/2014/07/15/bdlib-update-for-1-7-210/)
  * [BetterStorage 0.12.0.124](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/wip-mods/1442380)
  * [BiblioCraft 1.9.2](http://www.bibliocraftmod.com/)
  * [BiblioWoodsBiomesO'Plenty 1.9](http://www.bibliocraftmod.com/?page_id=50#bibliowoods)
  * [BiblioWoodsForestry 1.7](http://www.bibliocraftmod.com/?page_id=50#bibliowoods)
  * [BiblioWoodsNatura 1.5](http://www.bibliocraftmod.com/?page_id=50#bibliowoods)
  * [BigReactors 0.4.0rc11](http://big-reactors.com/)
  * [Binnie'sMods 2.0-dev5](http://minecraft.curseforge.com/mc-mods/223525)
  * [BiomesOPlenty 2.1.0.1057](http://goo.gl/zMK2S)
  * [BloodMagic 1.3.0a-1](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290532)
  * [BrainCore 0.3.1](http://minecraft.curseforge.com/mc-mods/223346-braincore)
  * [BuildCraft 6.3.4](http://www.mod-buildcraft.com/)
  * [BuildcraftAdditions 2.0.2](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2091746)
  * [Carpenter'sBlocks 3.3.3](http://mineshopper.github.io/carpentersblocks/)
  * [Chisel2 2.3.5.31](http://minecraft.curseforge.com/mc-mods/225236-chisel-2)
  * [CodeChickenCore 1.0.4.29](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1279956)
  * [CoFHCore 3.0.0B9-40](http://teamcofh.com/)
  * [CoFHLib 1.0.0B8-34](http://teamcofh.com/)
  * [CompactMachines 1.13](http://www.curse.com/mc-mods/minecraft/224218-compact-machines)
  * [ComputerCraft 1.65](http://www.computercraft.info/)
  * [DimensionalAnchors 59.0.2](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1281065)
  * [EasyCrafting 2.0.1.16](http://www.curse.com/mc-mods/minecraft/224295-easycrafting)
  * [EnchantingPlus 3.0.1](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1286469)
  * [EnderIO 2.2.6.322](http://enderio.com/)
  * [EnderStorage 1.4.5.27](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1279956)
  * [ExtendedAutomation 0.3](http://minecraft.curseforge.com/mc-mods/223347-extended-automation)
  * [ExtraCells 2.2.46b72](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1289077)
  * [ExtraUtilities 1.2.0](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/wip-mods/1443963)
  * [Factorization 0.8.88.7](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1284592)
  * [FastCraft 1.16](http://forum.industrial-craft.net/index.php?page=Thread&threadID=10820)
  * [Forestry 3.4.0.7](http://jenkins.ic2.player.to/job/Forestry/)
  * [Gendustry 1.4.4.54](http://bdew.net/gendustry/)
  * [Gyth 1.0.0](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2319607)
  * [Hats 4.0.1](http://ichun.us/mods/hats/)
  * [HatStand 4.0.0](http://ichun.us/mods/hats/hat-stand/)
  * [HungerOverhaul 1.7.10-beta5](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2222904)
  * [iChunUtil 4.1.2](http://ichun.us/mods/ichunutil/)
  * [IguanasTinkerTweaks 2.1.2](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2176855)
  * [ImmibisCore 59.0.5](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1281065)
  * [InfiniTubes 59.0.3](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1281065)
  * [InventoryTweaks 1.59-dev-153](http://minecraft.curseforge.com/mc-mods/223094-inventory-tweaks)
  * [IronChests 6.0.62.742](http://files.minecraftforge.net/IronChests2/)
  * [JABBA 1.1.4](http://www.mobiusstrip.eu/)
  * [LuckyBlock 5.1.0](http://www.minecraftforum.net/forums/t/1292247)
  * [MalisisCore 0.10.5](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2076338)
  * [MalisisDoors 1.4.3](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2076338)
  * [Mantle 0.3.2](http://minecraft.curseforge.com/mc-mods/74924-mantle)
  * [Mekanism 7.1.1.145](http://aidancbrady.com/mekanism/)
  * [MekanismGenerators 7.1.1.145](http://aidancbrady.com/mekanism/)
  * [MekanismTools 7.1.1.145](http://aidancbrady.com/mekanism/)
  * [MineFactoryReloaded 2.8.0RC6-5](http://minecraft.curseforge.com/mc-mods/66672-minefactory-reloaded)
  * [MineTweaker 3.0.7](http://minetweaker3.powerofbytes.com/)
  * [MobiusCore 1.2.3](http://minecraft.curseforge.com/mc-mods/76734)
  * [Morph 0.9.1](http://ichun.us/mods/morph/)
  * [Morpheus 1.5.19](http://minecraft.curseforge.com/mc-mods/69118-morpheus)
  * [More Swords Mod 3.0.0e](http://minecraft.curseforge.com/mc-mods/59903)
  * [Mystcraft 0.11.0.00](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1280070)
  * [Natura 2.2.0.1](http://minecraft.curseforge.com/mc-mods/74120-natura)
  * [NEIAddons 1.12.3.12](http://bdew.net/neiaddons/)
  * [NEIPLUGINS 1.1.0.9](https://bitbucket.org/mistaqur/nei_plugins/wiki/Home)
  * [NetherOres 2.3.0RC4-4](http://minecraft.curseforge.com/mc-mods/66675-netherores)
  * [NotEnoughItems 1.0.4.83](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1279956)
  * [ObsidiPlates 3.0.0.18](http://forum.feed-the-beast.com/threads/myrathis-mod-compendium.18505/)
  * [OpenBlocks 1.3-snapshot-549](http://openmods.info/)
  * [OpenEye 0.6](http://openeye.openmods.info/download)
  * [OpenModsLib 0.6-snapshot-304](http://openmods.info/)
  * [OpenPeripheralAddons 0.2.0-snapshot-145](http://openmods.info/)
  * [OpenPeripheralCore 0.5.0-snapshot-191](http://openmods.info/)
  * [OpenPeripheralIntegration 0.1.0-snapshot-35](http://openmods.info/)
  * [Pam'sHarvestCraft 1.7.10g](http://minecraft.curseforge.com/mc-mods/221857-pams-harvestcraft)
  * [PneumaticCraft 1.5.4-56](http://www.curse.com/mc-mods/minecraft/224125-pneumaticcraft)
  * [PowerConverters 3.0.2.38](http://goo.gl/TKD1gk)
  * [PressurePipes 1.0.2.50](http://bdew.net/pressure/)
  * [ProjectBlue 1.1.2](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2260994)
  * [ProjectE 0.2d-dev14](https://github.com/MozeIntel/ProjectE)
  * [ProjectRedBase 4.5.8.59](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290357)
  * [ProjectRedCompat 4.5.8.59](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290357)
  * [ProjectRedIntegration 4.5.8.59](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290357)
  * [ProjectRedLighting 4.5.8.59](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290357)
  * [ProjectRedMechanical 4.5.8.59](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290357)
  * [ProjectRedWorld 4.5.8.59](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290357)
  * [QuarryPlus 2.0.0](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1288467)
  * [Railcraft 9.4.0.0-DNS](http://www.railcraft.info/releases/)
  * [RandomThings 2.2.0](http://minecraft.curseforge.com/mc-mods/59816-random-things)
  * [RealisticWorldGen 1.3.01](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1281910)
  * [RedstoneArsenal 1.1.0RC1-19](http://teamcofh.com/)
  * [RemoteIO 1.8.1.B84](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1292285)
  * [TheSpiceofLife 1.2.3](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2091809)
  * [SuperCraftingFrame 1.7.10.1](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290201)
  * [Thaumcraft 4.2.1.4](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1292130)
  * [ThaumicTinkerer 2.5-1.7.10-158](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1289299)
  * [ThermalExpansion 4.0.0B8-23](http://teamcofh.com/)
  * [ThermalFoundation 1.0.0RC1-13](http://teamcofh.com/)
  * [TinkersConstruct 1.8.2a](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2218638)
  * [Tinkers'Mechworks 0.2.9](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/wip-mods/1446244)
  * [Translocators 1.1.1.14](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1279956)
  * [TreeCapitator 2.0.4](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1281180)
  * [Tubes 2.0.5](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1292474)
  * [TubeStuff 59.0.1](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1281065)
  * [TwilightForest 2.3.2](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1276258)
  * [usefulDNS 2.2.8](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1291674)
  * [Waila 1.5.8a](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1289765)
  * [Wawla 1.1.1](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2169830)
  * [Witchery 0.20.6](https://sites.google.com/site/witcherymod/home)
  * [WR-CBE 1.4.1.9](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1279956)
* Client
  * [Xaero's Minimap 1.3.6](http://www.planetminecraft.com/mod/xaeros-minimap/)


## Versions

* [latest](https://github.com/dockhippie/minecraft-cauldron-dns/tree/master)
  available as ```webhippie/minecraft-cauldron-dns:latest``` at
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
   bash              Start a shell on container
   commands          List all available sub commands
   config            Update server config
   console           Start interactive console
   deop              Deop a specific player
   mcrcon            Execute a remote command
   op                Op a specific player
   pid               Return the process id of the server
   prepare           Prepare environment
   reload            Reload the server
   running           Check if the server is running
   save-all          Save the current world state
   save-off          Disable the autosave feature
   save-on           Enable the autosave feature
   say               Say something on the server
   start             Start the server
   stop              Stop the server
   weather-clear     Set the weather to clear
   weather-rain      Set the weather to rain
   weather-thunder   Set the weather to thunder
   whitelist         Whitelist on the server
   whitelist-add     Add player to whitelist
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
