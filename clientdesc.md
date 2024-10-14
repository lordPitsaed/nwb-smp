# Client

## Description
This modpack provides various optimization improvements, as well as graphic enhancements like shaders, distant horizons, and a few useful resource packs. Keybinds and mods are preconfigured, with no further tinkering needed.
Its planned to maintain this modpack as long as possible, so you will always have a nice fresh modpack as soon as possible after Minecraft updates.

## Performance
Used Terralith as world gen mod and Chunky to measure chunk gen performance.

- <b>Time to launch:</b> 31.896s
- <b>Time from main menu to in-game:</b> 22.745342 seconds
- <b>Total time to load game and open world:</b> 54.641342 seconds
- <b>Average Chunky gen rate:</b> 10-15cps (Can be higer with [c2me](https://modrinth.com/mod/c2me-fabric), but I don't want to listen how my friends are struggling and whining about Java 22 requirement)
- <b>Shader/No-shader performance:</b> 65fps/143fps(VSync) (Can be improved with [nvidium](https://modrinth.com/mod/nvidium), will add in 0.0.3)
 <img alt="Shader performance is around 65fps" src="https://github.com/user-attachments/assets/6e079a30-1afb-4fcd-b5a1-27a4d9998e8c" width="400px" style="display: inline-block" />
 <img alt="No shader performance is 143fps" src="https://github.com/user-attachments/assets/08a783e4-021b-415f-8b96-06faec87b2de"  width="400px"  style="display: inline-block" />
<details>
  <summary>On-server performance</summary>
   
  <img alt="Shader performance is around 70fps" src="https://github.com/user-attachments/assets/e1c6083c-a972-4ec6-9ef2-847152bbf261"  width="400px"  style="display: inline-block" />
  <img alt="No shader performance is 150fps" src="https://github.com/user-attachments/assets/3f9864f8-faa7-443d-a9a4-4b7dbcda33e8" width="400px" style="display: inline-block" />
 </details>

<details>
  <summary>Test Rig</summary>

- CPU: Ryzen Z1 Extreme
- GPU: RTX 2060 6Gb
- Allocated RAM: 6144Mb

  <details>
    <summary>Game settings</summary> 
    
  - Shader: Photon
  - Render Distance: 12 chunks
  - Simulation Distance 10 chunks
  - Grapchics: Fancy
  - Clouds: Off
  - Particles: Decreased
  - Distant Horizons Render Distance: 128
  </details>
</details>

##

<details>
  <summary>Mods included</summary>
  
- [AppleSkin](https://modrinth.com/mod/appleskin) by squeek502 - Adds the ability to view food stats and their effects on health and saturation.
- [Architectury](https://modrinth.com/mod/lhGA9TYQ) by shedaniel - Library
- [Auth Me](https://modrinth.com/mod/yjgIrBjZ) by Axieum - Relogin to your account directly from the game.
- [Auto Clicker](https://modrinth.com/mod/r8axuw4u) by ErrorMikey, Advanced XRay team - Does what it says. Configure with the "O" key, toggle with "I".
- [Axiom](https://modrinth.com/mod/axiom) by Moulberry - Minecraft's answer to Blender
- [Bad Optimizations](https://modrinth.com/mod/g96Z4WVZ) by Thosea - Miscellaneous small optimizations.
- [Better Mount HUD](https://modrinth.com/mod/kqJFAPU9) by Lortseam - Hunger bar and mount health displayed at the same time. XP bar replaced only when jumping.
- [Better Ping Display](https://modrinth.com/mod/MS1ZMyR7) by Quintinity - Displays ping in milliseconds in the tab menu.
- [Better F3](https://modrinth.com/mod/8shC1gFX) by cominixo, TreyRuffy - Configurable F3 menu.
- [Blur+](https://modrinth.com/mod/NK39zBp2) by Motschen, tterrag1098, Pyrofab, backryun, byquanton - Adds blur to interface overlays.
- [Chat Heads](https://modrinth.com/mod/Wb5oqrBJ) by dzwdz, Fourmisain - Prepends mini heads to player nicknames in chat and the tab menu.
- [ChatAnimation](https://modrinth.com/mod/DnNYdJsx) by Ezzenix - Adds animation to chat.
- [CIT Resewn](https://modrinth.com/mod/otVJckYQ) by SHsuperCM - OptiFine Custom Item Textures port to Sodium.
- [Click Through Updated](https://modrinth.com/mod/kodT9HQf) by Giselbaer, PinkGoosik - Adds the ability to click through item frames and signs. Press "F9" to toggle.
- [Cloth Config](https://modrinth.com/mod/9s6osm5g) by shedaniel - Library.
- [Collective](https://modrinth.com/mod/e0M1UDsY) by Rick South - Library.
- [Continuity](https://modrinth.com/mod/1IjD5062) by PepperCode1 - OptiFine connected textures port to Sodium.
- [Dark Loading Screen](https://modrinth.com/mod/h3XWIuzM) by Neecko5b84 - Self-descriptive.
- [Distant Horizons](https://modrinth.com/mod/uCdwusMi) - Adds LODs to Minecraft.
- [Dynamic FPS](https://modrinth.com/mod/LQ3K71Q1) by juliand665, LostLuma - Preserves resources of your PC when the game is not in focus by lowering graphics and setting an FPS cap.
- [e4mc](https://modrinth.com/mod/qANg5Jrr) by skyevg - Allows you to open LAN server to anyone
- [Enhanced Block Entities](https://modrinth.com/mod/OVuFYfre) by FoundationGames - Optimizes block entities (e.g., chests, shulkers, etc.).
- [Entity Model Features](https://modrinth.com/mod/4I1XuqiY) by Traben - OptiFine EMF port to Sodium.
- [Entity Texture Features](https://modrinth.com/mod/BVzZfTc1) by Traben - OptiFine ETF port to Sodium.
- [Entity Culling](https://modrinth.com/mod/NNAgCjsB) by tr7zw - Path-traced entity culling to optimize the game.
- [Fabric API](https://modrinth.com/mod/P7dR8mSH) by FabricMC
- [Fabric Language Kotlin](https://modrinth.com/mod/Ha28R6CL) by FabricMC - Library.
- [Fast IP Ping](https://modrinth.com/mod/9mtu0sUO) by Fallen_Breath - Self-explanatory.
- [Ferrite Core](https://modrinth.com/mod/uXXizFIs) by malte0811 - Memory usage optimization.
- [Held Item Info](https://modrinth.com/mod/tEcWzCZz) by Neecko5b84 - Shows info about the held item, similar to Bedrock.
- [Immediately Fast](https://modrinth.com/mod/5ZwdcRci) by RK_01 - Game launch time optimization.
- [Indium](https://modrinth.com/mod/Orvt0mRa) by comp500 - Sodium addon providing support for the Fabric Rendering API, based on Indigo.
- [Iris](https://modrinth.com/mod/YL57xq9U) by coderbot, IMS212, Justsnoopy30, FoundationGames - Shaders mod.
- [Jade](https://modrinth.com/mod/nvQzSEkH) by Snownee - Displays info about what you are looking at.
- [Just Enough Breeding](https://modrinth.com/mod/9Pk89J3g) by Christofmeg - Allows you to see breeding info. Press "U" on the spawner egg.
- [Keep Inventory Sorted, Simple](https://modrinth.com/mod/FbHSPTyF) by Manu - Inventory sorter.
- [Litematica](https://modrinth.com/mod/bEpr0Arc) by masa - Schematica port to Fabric.
- [Lithium](https://modrinth.com/mod/gvQqBUqZ) by JellySquid, 2No2Name - Performance optimization mod.
- M.R.U - Library.
- [MaLiLib](https://modrinth.com/mod/GcWjdA9I) by masa - Library.
- [MidnightLib](https://modrinth.com/mod/codAaoxh) by Motschen, TeamMidnightDust - Library.
- [MiniHUD](https://modrinth.com/mod/UMxybHE8) by masa - Highly configurable HUD with lots of features.
- [Mod Menu](https://modrinth.com/mod/mOgUt4GM) by Prospector, haykam821, TerraformersMC - Adds a mod menu to view and configure mods in-game.
- [Model Gap Fix](https://modrinth.com/mod/QdG47OkI) by MehVahdJukaar - Fixes model gaps, like fishing rods.
- [ModernFix](https://modrinth.com/mod/nmDcB62a) by embeddedt - Performance improvements.
- [More Chat History](https://modrinth.com/mod/8qkXwOnk) by JackFred - Self-explanatory.
- [More Culling](https://modrinth.com/mod/51shyZVL) by PR0CESS, 1Foxy2 - Literally adds more culling options.
- [MouseTweaks](https://modrinth.com/mod/aC3cM3Vq) by Ivan Molodetskikh (YaLTeR) - Inventory mouse interactions enhancer.
- [No Chat Reports](https://modrinth.com/mod/qQyHxfxd) by Aizistral - Strips cryptographic data from chat messages so Microsoft can't spy on you.
- [Noisium](https://modrinth.com/mod/KuNKN7d2) by Steveplays28 - World generation optimization.
- [OptiGUI](https://modrinth.com/mod/JuksLGBQ) by opekope2 - OptiFine Custom GUI feature port to Sodium.
- [Peek](https://modrinth.com/mod/TnOXNf5e) by Max Henkel - Additional information in item tooltips.
- [Placeholder API](https://modrinth.com/mod/eXts2L7r) by Patbox - Library.
- [Presence Footsteps](https://modrinth.com/mod/rcTfTZr3) by Hurricaaane (Ha3), Sollace - Sounds mod.
- [Resourcify](https://modrinth.com/mod/RLzHAoZe) by DeDiamondPro - Adds the ability to download shaders and resource packs from in-game.
- [Roughly Enough Items](https://modrinth.com/mod/nfn13YXA) by shedaniel - Recipe finder and viewer.
- [Roughly Enough Professions](https://modrinth.com/mod/V8XJ8f5f) by Mrbysco, ShyNieke - Adds profession info to REI. Press "U" on emerald or spawn egg.
- [Simple Voice Chat](https://modrinth.com/mod/9eGKb6K1) by Max Henkel - Voice chat. Requires server-side mod to work. Press "V" to configure.
- [Sodium](https://modrinth.com/mod/AANobbMI) by jellysquid3 - Rendering engine.
- [Sodium Extra](https://modrinth.com/mod/PtjYWJkn) by FlashyReese - More options for Sodium.
- [Sodium Shadowy Path Blocks](https://modrinth.com/mod/EIa1eiMm) by Rynnavinx - Adds smooth lighting to path blocks.
- [Status Effect Bars](https://modrinth.com/mod/x02cBj9Y) by Neecko5b84 - Adds small customizable bars to the status effects overlay and in the inventory to show the remaining duration of effects.
- [Thread Tweak](https://modrinth.com/mod/vSEH1ERy) by getchoo, UltimateBoomer, fantahund - Improves CPU scheduling.
- [ViaBackwards](https://modrinth.com/mod/NpvuJQoq) by Matsv, kennytv, Gerrygames, creeper123123321, ForceUpdate1, EnZaXD - Allows you to connect to newer servers.
- [ViaFabricPlus](https://modrinth.com/mod/rIC2XJV4) by FlorianMichael/EnZaXD, RK_01 - Fabric mod to connect to EVERY Minecraft server version (Release, Beta, Alpha, Classic, Snapshots, Bedrock) with QoL fixes to gameplay.
- [ViaVersion](https://modrinth.com/mod/P1OZGk5p) by _MylesC, creeper123123321, Gerrygames, kennytv, Matsv, EnZaXD, RK_01 - Allows you to connect to older servers.
- [WaveyCapes](https://modrinth.com/mod/kYuIpRLv) by tr7zw - Makes capes wave.
- [WI Zoom](https://modrinth.com/mod/o7DitHWP) by Alexander01998 - Zoom. Press "C", MWheel to adjust.
- [WorldEdit](https://enginehub.org/worldedit/) by EngineHub
- [YetAnotherConfigLib](https://modrinth.com/mod/1eAoo2KR) by isXander - Library.
- [Sounds](https://modrinth.com/mod/sound) by IMB11 - Block and item interactions sounds mod. Preconfigured
- [AdaptiveHUD](https://modrinth.com/mod/adaptivehud) by Fy17 - Smaller then miniHUD mod to work independent from miniHUD renderers 
</details>

<details>
  <summary>Resource Packs</summary>
  
  ### Enabled
  
  - [CTM OF-Fabric](https://modrinth.com/resourcepack/ctm-of-fabric) by Aeldit - Connected textures.
  - [BetterBoats](https://modrinth.com/resourcepack/better-boats) by PystoyPlayer
  - [Better Flame Particles](https://modrinth.com/resourcepack/better-flame-particles) by Tschipcraft
  - [Axolotl Bucket Variants](https://modrinth.com/resourcepack/axolotl-bucket-variants) by manyrandomthings
  - [Low On Fire](https://modrinth.com/resourcepack/low-on-fire) by Haikis - Makes fire effect less obstructive.
  - [Small Shield & Totem](https://modrinth.com/resourcepack/small-shield-totem) by blob_ - Makes shield and totem held items less obstructive.
  - [Less Pumpkin Blur](https://modrinth.com/resourcepack/less-pumpkin-blur) by Cyan735 - Makes pumpkin blur more opaque.
  - [Less Rain](https://modrinth.com/resourcepack/less-rain) by Cyan735
  - [Icons Advertisement Removal](https://modrinth.com/resourcepack/icons-advertisement-removal) by vexcenot
  - [Icons](https://modrinth.com/resourcepack/icons) by mr_ch0c0late - Adds icons to UI.
  - [Fancy Crops](https://modrinth.com/resourcepack/fancy-crops) by bebebea_loste
  - [Default Dark Mode](https://modrinth.com/resourcepack/default-dark-mode) by nebulr - Makes all the UI dark.
  - [Better Lights](https://modrinth.com/resourcepack/better-lights) by PystoyPlayer
  - [Detailed Animations](https://modrinth.com/resourcepack/detailed-animations) by Cymock - Player model animation.
  - [Fresh Animations](https://modrinth.com/resourcepack/fresh-animations) by FreshLX - Other mobs' animations.
  - [C4Music](https://modrinth.com/resourcepack/c4music) by MopsTMC and C418 - Removes new soundtrack in favour of C418 ol' days ost
  - Glass Pane Culling Fix - Fixes culling issue with glass panes.
  
  ### Optional
  - [GUI Revision](https://modrinth.com/resourcepack/gui-revision) by Vixel - Another resource pack that changes UI.
  - [Enchant Icons](https://modrinth.com/resourcepack/enchant-icons-colorless-countxd) by CountXD - For those who don’t want Icons RP but want to see enchant icons.
</details>

<details>
  <summary>Shader Packs</summary>

   - [Complimentary Reimagined](https://modrinth.com/shader/complementary-reimagined) by EminGT
   - [Hysteria Shaders](https://modrinth.com/shader/hysteria-shaders) by ElocinDev
   - [Pastel Shaders](https://modrinth.com/shader/pastel-shaders) by ElocinDev
   - [Photon](https://modrinth.com/shader/photon-shader) by sixthsurge
</details>

<details>
 <summary>Versioning</summary>

 Assuming modpack version is x.y.z, where:
 - x: game version change, e.g. Minecracft 1.21 updates to Minecraft 1.21.1
 - y: modlist\resourcepacks\shaderpacks changes, e.g. new mod added, RP removed etc.
 - z: mods\resourcepacks\shaderpacks updates, e.g. DistantHorizons update from 2.2.0a to 2.2.1a
</details>
