## Installation

### Singleplayer

- Install [Fabric](https://fabricmc.net/use/installer/)
- Download [fabric-api](https://www.curseforge.com/minecraft/mc-mods/fabric-api/files)
- Download [fabric-carpet](https://www.curseforge.com/minecraft/mc-mods/carpet/files)
- Download [Carpet Sky Additions](https://github.com/jsorrell/CarpetSkyAdditions/releases)
- Place fabric-carpet, fabric-api, and Carpet Sky Additions into `<minecraft-directory>/mods/`
- Start Minecraft and `Create New World`
- Set Allow Cheats to `ON` so you will be able to enable/disable mod features
- Enable the Datapack `carpetskyadditions/skyblock`
- Optionally enable the Datapack `carpetskyadditions/skyblock_acacia` for an Acacia Tree start
- Click on `More World Options...`
- Choose `World Type: SkyBlock`
- Create the World

### Multiplayer

The mod is only required server-side.

- Create a [Fabric Server](https://fabricmc.net/use/server/)
- Download [fabric-api](https://www.curseforge.com/minecraft/mc-mods/fabric-api/files)
- Download [fabric-carpet](https://www.curseforge.com/minecraft/mc-mods/carpet/files)
- Download [Carpet Sky Additions](https://github.com/jsorrell/CarpetSkyAdditions/releases)
- Start the server to generate a template `server.properties` file
- Shut down the server
- Delete `world` folder the server created
- Place fabric-carpet, fabric-api, and SkyBlock into `<server-directory>/mods/`
- Open `server.properties`
- Change `level-type=minecraft\:normal` to `level-type=carpetskyadditions\:skyblock`
- Start the server
- Run `datapack enable "carpetskyadditions/skyblock"` to enable the datapack
