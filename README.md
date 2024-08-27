
![modpackbanner](https://github.com/user-attachments/assets/f984d7eb-7981-4470-bb45-9429ba1deea1)



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

I respect my time you should respect your own, all my most used tings now at our fingertips. Oh, and it looks pretty too.

![menupreview1](https://github.com/user-attachments/assets/1bd7019e-5abc-4a66-bf44-09e795473846)
![menupreview2](https://github.com/user-attachments/assets/f98af648-02c9-4949-b7fc-969050618ed6)


### Wynnventory + Wynntils

Everyone already knows about the great and numerous features Wynntils adds, but one thing that has always been missing is the ability to see trade market prices in tooltips. WynnVentory adds just that, and while it is still early in development it already supports most items, and ingredients are coming soon!

![8f7a670ab8d390b9d6262c010d2eb37ea2254ad9](https://github.com/user-attachments/assets/d6c1999e-5c14-4226-a686-bfc6aa8dde68)

### Optimization

Uhhhhh, it's raytracing what do you expect? I get double the frames when running BSL shaders compared to Rethinking Voxels so just switch shaderpacks if your computer starts smoking.

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

# Step One: Download the Modpack
There are three easy ways to download the modpack: The Modrinth app, Prism Launcher, Manually (Minecraft Launcher)

## Modrinth App
1. Download the [Modrinth App](https://modrinth.com/app) and sign in with your Microsoft/Minecraft account.
2. Press the Browse button and search for Wynncraft: Rekindled.
3. Install the modpack.
4. Navigate to the modpack's [GitHub Releases](https://github.com/elijahjibben/wynncraft-rekindled-modpack/releases) panel.
5. Download the file "bobby.zip". This allows you to increase your render distance beyond the server limit of 9 chunks.
6. Navigate to the Modrinth App's Library panel, and select Wynncraft: Rekindled -> Folder.
7. Follow Step Two to install the bobby configuration.

## Prism Launcher
1. Download [Prism Launcer](https://prismlauncher.org/) and sign in with your Microsoft/Minecraft account.
2. Press "Add Instance" in the top right corner.
3. Select the Modrinth panel, and search for "Wynncraft: Rekindled"
4. Make sure the latest version is selected  and press "Ok".
5. Navigate to the modpack's [GitHub Releases](https://github.com/elijahjibben/wynncraft-rekindled-modpack/releases) panel.
6. Download the file "bobby.zip". This allows you to increase your render distance beyond the server limit of 9 chunks.
7. In Prism, select the modpack then press folder.
8. Follow Step Two to install the bobby configuration.

## Manually (Minecraft Launcher)
1. Download the .zip version of the modpack from the [GitHub Releases](https://github.com/elijahjibben/wynncraft-rekindled-modpack/releases) panel.
2. Download the [Fabric Installer](https://fabricmc.net/use/installer/) and install for Minecraft 1.21, Loader Version 1.60.0.
3. Copy the .minecraft folder from the zip file to any location (Roaming recommended)
4. Rename the folder (.wynncraft recommended)
5. Open the Minecraft Launcher
6. Select Minecraft: Java Edition on the left panel
7. Select Installations -> New Installation
8. Select the custom game directory, and set version to the fabric-loader
9. Optional: Set Java arguments from -Xmx2G to higher to allocate more RAM
10. Optional: Download this pack icon to change the instance icon!\
[Rekindled Pack Icon](https://cdn.modrinth.com/data/cached_images/fd52f8703f66b28b37c2b1d782c1584ad4d90973.png)
11. Launch the game and follow Step Three.

# Step Two: Bobby Install
Extract the bobby file into the instance folder. Ensure the file is named:
```
.bobby
```
and contains a folder named:
```
play.wynncraft.com
```
It should look like this:\
![Bobby File Demonstration](https://cdn.modrinth.com/data/cached_images/471bf9ce4475b682f3028b6452bb3486396892de.gif)

# Step Three: Download Voices of Wynn (Optional)
1. Voices of Wynn is a very popular community mod which adds voice acting for every quest in the game.
2. If you are interested, [download the latest version](https://voicesofwynn.com/downloads) and place the mod in the mods folder.

# Step Four: Configurations
1. Bobby Update\
As soon as you are in a world, type the following command into chat:
```
/bobby upgrade
```
This command is required to make bobby register the chunks saved in the instance directory.\
2. Configure Keybinds and Settings\
Take a look through the keybinds menu! I recommend at least changing the "Cast 1-4 Spell" keybinds to suit your mouse/keyboard.\
Look at the Video Settings to suit your computer's performance.

</details>

<details>
<summary>Common Issues</summary>
  
**Crashing**
1. Minecraft 1.21 is the first verion to use Java 21. If you experience a crash, make sure you are using Java 21.

**Main Menu is Glitchy/Clipping**
1. Make sure you are using v1.1.3, as this version fixes many clipping issues.
2. Try pressing CTRL + Alt + R to reload the menu.

</details>

## Modlist


<details>
<summary>Modlist</summary>

- [Sodium Extra](https://modrinth.com/mod/PtjYWJkn)
- [Euphoria Patcher](https://modrinth.com/mod/4H6sumDB)
- [Entity View Distance](https://modrinth.com/mod/ihnBJ6on)
- [CreativeCore](https://modrinth.com/mod/OsZiaDHq)
- [Entity Model Features](https://modrinth.com/mod/4I1XuqiY)
- [Tiny Item Animations](https://modrinth.com/mod/wMkevcSR)
- [Fabric API](https://modrinth.com/mod/P7dR8mSH)
- [Nvidium](https://modrinth.com/mod/SfMw2IZN)
- [Serverpack Priority](https://modrinth.com/mod/56FVCPkz)
- [ChatAnimation](https://modrinth.com/mod/DnNYdJsx)
- [ClickThrough](https://modrinth.com/mod/ERHOxvaH)
- [Architectury](https://modrinth.com/mod/lhGA9TYQ)
- [NotEnoughAnimations](https://modrinth.com/mod/MPCX6s5C)
- [MixinTrace](https://modrinth.com/mod/sGmHWmeL)
- [Enhanced Block Entities](https://modrinth.com/mod/OVuFYfre)
- [ModernFix](https://modrinth.com/mod/nmDcB62a)
- [Dynamic Crosshair](https://modrinth.com/mod/ZcR9weSm)
- [YetAnotherConfigLib](https://modrinth.com/mod/1eAoo2KR)
- [Melody](https://modrinth.com/mod/CVT4pFB2)
- [Continuity](https://modrinth.com/mod/1IjD5062)
- [Visuality](https://modrinth.com/mod/rI0hvYcd)
- [MacOS Input Fixes](https://modrinth.com/mod/x9BrsVME)
- [Blur+ (Fabric)](https://modrinth.com/mod/NK39zBp2)
- [ImmediatelyFast](https://modrinth.com/mod/5ZwdcRci)
- [No Resource Pack Warnings](https://modrinth.com/mod/6xKUDQcB)
- [Animatica](https://modrinth.com/mod/PRN43VSY)
- [More Chat History](https://modrinth.com/mod/8qkXwOnk)
- [Dynamic FPS](https://modrinth.com/mod/LQ3K71Q1)
- [Particle Core](https://modrinth.com/mod/RSeLon5O)
- [Krypton](https://modrinth.com/mod/fQEb0iXm)
- [BetterF3](https://modrinth.com/mod/8shC1gFX)
- [Concurrent Chunk Management Engine](https://modrinth.com/mod/VSNURh3q)
- [Mod Menu](https://modrinth.com/mod/mOgUt4GM)
- [Video Tape](https://modrinth.com/mod/LVTZtqlk)
- [Better Beds](https://modrinth.com/mod/kKwy3HU9)
- [Falling Leaves](https://modrinth.com/mod/WhbRG4iK)
- [More Culling](https://modrinth.com/mod/51shyZVL)
- [Wynncraft Dynamic Weather](https://modrinth.com/mod/6z01GnNz)
- [Entity Texture Features](https://modrinth.com/mod/BVzZfTc1)
- [Remove Hud But Not Hand!](https://modrinth.com/mod/MiPOIx6b)
- [Controlling](https://modrinth.com/mod/xv94TkTM)
- [ClientSideNoteblocks](https://modrinth.com/mod/flmhXQgb)
- [FancyMenu](https://modrinth.com/mod/Wq5SjeWM)
- [Fabric Language Kotlin](https://modrinth.com/mod/Ha28R6CL)
- [Particle Rain](https://modrinth.com/mod/nrikgvxm)
- [Debugify](https://modrinth.com/mod/QwxR6Gcd)
- [FerriteCore](https://modrinth.com/mod/uXXizFIs)
- [Smooth Scrolling Refurbished](https://modrinth.com/mod/trr0scVt)
- [AmbientSounds](https://modrinth.com/mod/fM515JnW)
- [Mineblock's Repeated Utilities](https://modrinth.com/mod/SNVQ2c0g)
- [Sounds](https://modrinth.com/mod/ZouiUX7t)
- [WaveyCapes](https://modrinth.com/mod/kYuIpRLv)
- [3d-Skin-Layers](https://modrinth.com/mod/zV5r3pPn)
- [root project 'Prism'](https://modrinth.com/mod/1OE8wbN0)
- [Zoomify](https://modrinth.com/mod/w7ThoJFB)
- [Bobby](https://modrinth.com/mod/M08ruV16)
- [Legendary Tooltips](https://modrinth.com/mod/atHH8NyV)
- [Fzzy Config](https://modrinth.com/mod/hYykXjDp)
- [Indium](https://modrinth.com/mod/Orvt0mRa)
- [Lithium](https://modrinth.com/mod/gvQqBUqZ)
- [Searchables](https://modrinth.com/mod/fuuu3xnx)
- [Physics Mod](https://modrinth.com/mod/Xy8aRQKS)
- [Presence Footsteps](https://modrinth.com/mod/rcTfTZr3)
- [Iris](https://modrinth.com/mod/YL57xq9U)
- [Shoulder Surfing Reloaded](https://modrinth.com/mod/kepjj2sy)
- [Iceberg](https://modrinth.com/mod/5faXoLqX)
- [Reese's Sodium Options](https://modrinth.com/mod/Bh37bMuy)
- [spark](https://modrinth.com/mod/l6YH9Als)
- [Forge Config API Port](https://modrinth.com/mod/ohNO6lps)
- [Cubes Without Borders](https://modrinth.com/mod/ETlrkaYF)
- [Cloth Config v15](https://modrinth.com/mod/9s6osm5g)
- [YOSBR](https://modrinth.com/mod/WwbubTsV)
- [Konkrete](https://modrinth.com/mod/J81TRJWm)
- [fuy.gg](https://modrinth.com/mod/EMQzFaJ1)
- [Cull Leaves](https://modrinth.com/mod/GNxdLCoP)
- [Sound Physics Remastered](https://modrinth.com/mod/qyVF9oeo)
- [EntityCulling](https://modrinth.com/mod/NNAgCjsB)
- [ScalableLux](https://modrinth.com/mod/Ps1zyz6x)
- [Controlify](https://modrinth.com/mod/DOUdJVEm)
- [Custom Splash Screen](https://modrinth.com/mod/BwFQLeCh)
- [Sodium](https://modrinth.com/mod/AANobbMI)
- [YDM's Weapon Master](https://modrinth.com/mod/qi1sj2da)
- [Barriers Don't Block Rain](https://modrinth.com/mod/CXLh6wxz)
- [Chunks Fade In](https://modrinth.com/mod/JaNmzvA8)
- [Wynntils](https://modrinth.com/mod/dU5Gb9Ab)
</details>

## License and Affiliation
This modpack is licensed under the LGPL-3.0 license. This modpack is not affiliated with Wynncraft.
