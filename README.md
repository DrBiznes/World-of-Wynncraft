[![World of Wynncraft Banner][1]][2]

[1]: https://github.com/user-attachments/assets/f984d7eb-7981-4470-bb45-9429ba1deea1
[2]:  https://modrinth.com/modpack/world-of-wynncraft "Redirect to Modrinth Page"


**Please read the installation section at the bottom!**

This modpack is very close to how I dreamed Wynncraft would one day look back in 2013. Distant Horizons allows for unlimited render distance, Rethinking Voxels provides ray-traced lighting, the wonderful Wynntils and WynnVentory add all the features vanilla Wynncraft lacks.

## What's Up

Yeah, we got raytracing in this bad mama jama, and there are a few other things too, bra.
 
### Wynncraft RTX

Since it doesn't make use of the RT cores in Nvidia graphics cards Rethinking Voxels is technically compatible with AMD and integrated graphics cards as well, however, mac users and those with low-end computers should switch to BSL which I've also included with a custom preset.


 ![rtxpreview](https://github.com/user-attachments/assets/4c1e6f68-7bbe-4dd3-82d6-a488838417be)

### Dynamic Weather

Using the [Wynncraft dynamic weather engine](https://modrinth.com/mod/wynncraft-dynamic-weather) mod created by Quikjay for use in his modpack (which you should also check out)! "Rain or thunder can randomly occur throughout the map, and areas such as Nemract, Pirate Cove, the Dernal Jungle, and others experience more frequent weather conditions. Traverse through snowstorms in Nesaak, sandstorms in Almuj, and other weather hazards! Coupled perfectly with the [Particle Rain](https://modrinth.com/mod/particle-rain) mod with custom settings."

![WynnWeather4](https://github.com/user-attachments/assets/ab469bc7-1b67-4001-87b4-7a564c8ca17d)


### Custom Main Menu, Options, Pause, and Loading Screen

All my most used tings now at your fingertips. Oh, and it looks pretty too.

![menupreview3](https://github.com/user-attachments/assets/94c11140-ea9c-48e9-8e68-4d6463965333)
![menupreview2](https://github.com/user-attachments/assets/f98af648-02c9-4949-b7fc-969050618ed6)


### WynnVentory + Wynntils

Everyone already knows about the great and numerous features Wynntils adds, but one thing that has always been missing is the ability to see trade market prices in tooltips. WynnVentory adds just that, and while it is still early in development it already supports most items, and ingredients are coming soon!

![8f7a670ab8d390b9d6262c010d2eb37ea2254ad9](https://github.com/user-attachments/assets/d6c1999e-5c14-4226-a686-bfc6aa8dde68)


### Some stuff you may want to know

- Distant Horizons set to 80 chunks to preserve the feeling of multiple continents
- Visually based around [WynnEdits Dark Theme](https://modrinth.com/resourcepack/wynnedits-dark-theme)
- Shoulder Surfing Reloaded and [DSTC](https://modrinth.com/mod/dont-surf-through-cutscenes!) installed but disabled by default, enable it in the Modrinth launcher or by renaming the .jar file
- Wynntils config included but knowing y'all sweats you probably gunna import your own

This modpack is far from finished and I will be continuously updating it as more mods port to 1.21, check out a list of mods I'm waiting on [here.](https://modrinth.com/collection/gs97WiAb)

## Installation

**"WAH WAH MY RENDER DISTANCE IS SO SMALL"** Does this sound like the voice in your head? Well, due to filesize limitations on Modrinth, the Distant Horizons LODs files are hosted on the [GitHub releases page.](https://github.com/elijahjibben/wynncraft-rekindled-modpack/releases) For instructions to install it, please review the installation guide.

<details>
<summary>Installation Guide</summary>

# Method 1: Modrinth/Prism/ATLauncher download
There are two ways to download the modpack, although it may seem ironic downloading Manually (Method 2) is easier in my opinion

## Modrinth hosted download
1. Download the [Modrinth App](https://modrinth.com/app) or your preferred modpack launcher and sign in with your Microsoft/Minecraft account.
2. Press the Browse button and search for "World of Wynncraft"
3. Install the modpack.
4. Navigate to the modpack's [GitHub Releases](https://github.com/bob10234/World-of-Wynncraft/releases) page.
5. Download the file "Distant_Horizons_server_data.zip". This allows you to stop crying and start smiling.
6. Navigate to the Modrinth App's Library panel, and select World of Wynncraft then click the Folder button next to Play to open the modpacks folder.
7. Drag the Zip file you downloaded into the modpack folder.
8. Right-click on the Zip file and hit Extract All. After it's done make sure there is a folder named "Distant_Horizons_server_data" in your modpack folder.
9. Delete the Zip file.

# Method 2: Manual Installation

## Github hosted download
1. Navigate to the modpack's [GitHub Releases](https://github.com/bob10234/World-of-Wynncraft/releases) page.
2. Download the file titled World.of.Wynncraft.0.X.mrpack It should be around 1.3 Gigabytes.
1. Download the [Modrinth App](https://modrinth.com/app) or your preferred modpack launcher and sign in with your Microsoft/Minecraft account.
2. Add an instance, in the Modrinth app use the plus button on the bottom left. For other launchers, I got no clue sorry!!
3. Select From File and drag the .mrpack file you just downloaded onto the window.
4. This version comes with the Distant Horizons LODs pre-installed.

# Addons: Voices of Wynn (Optional)
1. You wanna hear the Seaskipper yappin at you, I understand.
2. If you are interested, [download the latest version](https://www.curseforge.com/minecraft/mc-mods/voices-of-wynn/files) and place the .jar in the mods folder inside the modpack folder.

# Configurations
1. Wynncraft Settings:
If you are using my Wynntils config and not importing your own, I recommend typing the following commands once you join a world.
```
/toggle beacon
```
```
/toggle queststartbeacon
```

2. Keybinds and Video Settings:
I recomend you change what buttons cast each spell in the Wynncraft Spell Caster section in the Keybinds menu.
I've set the render distance at 12 chunks with DH at 80 chunks, the shader pack is tuned for this specifically so you might need to mess with shader pack settings if you edit the video settings.
The modpack is best played in fullscreen, but it can be played in windowed mode as long as you make the window large enough to accommodate the custom menus.
</details>

<details>
<summary>Common Issues</summary>
  
**Crashing**
1. Minecraft 1.21 is the first version to use Java 21. If you experience a crash, make sure you are using Java 21.

**Known Bugs**
1. The modpack is best played in fullscreen, but it can be played in windowed as long as you make the window large enough to accommodate the custom menus.
2. Tooltips sometimes clip into each other: This is an issue with WynnVentory but the developer is actively working on fixing this issue.
3. Wynntils Item Predictions are broken: This is the fault of Legendary Tooltips, Iceberg, and Prism. Turn these mods off to fix this feature of Wynntils.
4. Resource Loading occasionally fails. Just re-enable every resourcepack and make sure WynnEdits is above World of Wynn Resourcepack

**Support**

If you need further support contact me on the Wynncraft discord @Jamino or submit an issue to the [GitHub issue page](https://github.com/bob10234/World-of-Wynncraft/issues)

</details>

## Modlist and Credits
You can view the modlist with links to all the mods for any version uploaded on the [Modrinth project page](https://modrinth.com/modpack/world-of-wynncraft/versions)
The [Alagard Font](https://www.dafont.com/alagard.font) by Hewett Tsoi was used with permission from the author.

## License and Affiliation
This modpack is licensed under the LGPL-3.0 license. This modpack is not affiliated with Wynncraft.
