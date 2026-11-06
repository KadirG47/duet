<p align="center">
  <img src="docs/banner.jpg" alt="Duet — the fast, good-looking Minecraft launcher" width="100%">
</p>

<p align="center">
  <a href="https://github.com/KadirG47/duet/releases/latest"><img src="https://img.shields.io/github/v/release/KadirG47/duet?style=for-the-badge&color=7c3aed&label=latest" alt="Latest release"></a>
  <a href="https://github.com/KadirG47/duet/releases"><img src="https://img.shields.io/github/downloads/KadirG47/duet/total?style=for-the-badge&color=a855f7" alt="Downloads"></a>
  <img src="https://img.shields.io/badge/Windows%20%7C%20Linux-1f1530?style=for-the-badge" alt="Windows and Linux">
</p>

<p align="center">
  <b>Duet</b> is a Minecraft: Java Edition launcher built for speed and good looks.<br>
  Instances, mods and modpacks like Modrinth, tuned Java, built-in speed mods and a launcher you'll actually enjoy opening.
</p>

<p align="center">
  <a href="https://github.com/KadirG47/duet/releases/latest"><b>⬇ Download</b></a> &nbsp;·&nbsp;
  <a href="#features">Features</a> &nbsp;·&nbsp;
  <a href="#faq">FAQ</a>
</p>

<br>

<p align="center">
  <img src="docs/home.jpg" alt="Duet home screen" width="88%">
</p>

## Download

| System | File | Updates |
| --- | --- | --- |
| **Windows 10 / 11** | `Duet_x.y.z_x64-setup.exe` | Automatic |
| **Linux** (any distro) | `Duet_x.y.z_amd64.AppImage` | Automatic |
| **Ubuntu / Debian / Mint** | `Duet_x.y.z_amd64.deb` | Download new versions from the releases page |

Get them from the **[latest release](https://github.com/KadirG47/duet/releases/latest)**. Once installed, Duet updates itself: a button appears when a new version is out, and one click installs it.

## Features

### Play anything
- **Every mod loader**: Fabric, Quilt, Forge and NeoForge, from the newest Minecraft to classics like 1.12.2. Duet installs the loader and the right Java for you.
- **Modpacks in one click**: browse Modrinth's modpacks or drop in an `.mrpack` file. Minecraft, the loader, every mod and its configs are set up automatically.
- **Mods, resource packs and shaders**: search Modrinth, install with dependencies, and update everything with one button.
- **Bring your instances**: imports your Modrinth App profiles without moving any files.

### Built for FPS
- **Tuned Java profiles**: Smooth (generational ZGC for frame times without spikes), Max FPS (tuned G1) or Low RAM.
- **Built-in speed mods**: Sodium, Lithium, FerriteCore, ImmediatelyFast, EntityCulling, MoreCulling, Dynamic FPS and Iris load automatically on Fabric and Quilt. Your mods folder stays untouched.
- **Far view**: 50+ chunk render distance with Voxy or Distant Horizons, one toggle.
- **No FPS cap**: new instances start with uncapped FPS and VSync off. Duet also prefers your fast GPU and sleeps while you play.

<p align="center">
  <img src="docs/performance.jpg" alt="Performance settings" width="88%">
</p>

### Duet Mods
A built-in PvP and HUD mod set for Fabric 1.21.11: hit sounds, reach and combo display, CPS, W-tap trainer, custom crosshair with cooldown ring, shield timer, enemy actions, damage numbers, loot glow, totem pops, kill banners, armor and inventory HUD, and more. It's fair play: no ESP, no macros, and no showing other players' health or items.

### Make it yours
- **Themes**: seven colour themes, plus seasonal ones that switch on by themselves for Halloween, Christmas, New Year, Valentine's, Easter and Miku's birthday.
- **Backgrounds**: your newest screenshot, any image, GIF or looping video, with optional sound or your own music.
- **Skin changer**: a 3D preview, a skin library, copying any player's skin and switching capes.

<p align="center">
  <img src="docs/halloween.jpg" alt="Seasonal Halloween theme" width="44%">
  &nbsp;
  <img src="docs/themes.jpg" alt="Themes" width="44%">
</p>

### Also included
Crash help that explains common crashes in plain words · offline singleplayer for signed-in owners · join a server straight from the launcher · window size and fullscreen options · duplicating instances, with mods linked so they use no extra space · safe deleting to the Recycle Bin · Linux support with fallbacks for WebKitGTK.

## Your account is safe

Signing in uses **Microsoft's own sign-in page**. Duet never sees your password. Your sign-in tokens stay on your own PC and are only sent to Microsoft and Mojang. Duet checks that the account owns Minecraft before the game can start, as Mojang requires.

> **Status:** Microsoft sign-in is waiting for Mojang's approval for third-party launchers. Until then you can set everything up (instances, mods, modpacks, skins); playing unlocks once the approval comes through.

## FAQ

<details>
<summary><b>Windows says "Windows protected your PC"</b></summary>
<br>
Duet isn't code-signed yet, so Windows SmartScreen warns about it. Click <b>More info → Run anyway</b>. Official downloads are only published on this page.
</details>

<details>
<summary><b>A video background doesn't play on Linux</b></summary>
<br>
Linux plays videos through GStreamer. Use a <code>.webm</code> video, or install the codecs: <code>sudo apt install gstreamer1.0-libav gstreamer1.0-plugins-good</code> (Ubuntu and Debian) or <code>gst-libav</code> (Arch). The <code>.deb</code> installs them automatically.
</details>

<details>
<summary><b>Where does Duet keep its files?</b></summary>
<br>
Windows: <code>%APPDATA%\Duet</code> · Linux: <code>~/.local/share/Duet</code>. Imported Modrinth App profiles stay where they are, and both launchers share them.
</details>

<details>
<summary><b>Does Duet change my mods folder?</b></summary>
<br>
No. Duet Mods and the speed mods are loaded straight from the launcher. If you already have one of them in your mods folder, yours is used instead.
</details>

## Built with

[Tauri](https://tauri.app) and Rust · React · [Modrinth API](https://docs.modrinth.com) · [FabricMC](https://fabricmc.net), [Quilt](https://quiltmc.org), [Forge](https://minecraftforge.net), [NeoForge](https://neoforged.net) · [Eclipse Temurin](https://adoptium.net) · [skinview3d](https://github.com/bs-community/skinview3d)

Speed mods are downloaded from Modrinth and belong to their authors.

---

<p align="center">
  <img src="docs/emblem.svg" width="56" alt=""><br>
  <sub>© 2026 Hydrate (KadirG47). All rights reserved.</sub><br>
  <sub>NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT.</sub>
</p>
