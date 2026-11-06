# Duet

A small, fast launcher for **Minecraft: Java Edition** on Windows, made by Kadir (Hydrate) for myself and the friends on our SMP.

## What it does

- **Instances** – imports existing Modrinth App profiles and creates new Fabric or vanilla instances
- **Official game files** – downloads Minecraft, libraries and assets from Mojang's servers, Fabric from FabricMC, and Java (Eclipse Temurin) when needed
- **Mods from Modrinth** – search and install mods, resource packs and shader packs, with their required dependencies
- **Tuned Java settings** – launch profiles (generational ZGC for smooth frame times, tuned G1 for max FPS, or low memory), RAM control, high-performance GPU preference and higher CPU priority
- **Themes & backgrounds** – color themes, plus screenshots, images, GIFs or looping videos as backgrounds (videos pause while you play)
- **Light** – a few MB installer, ~35 MB of RAM, and it hides itself while you play

## Microsoft sign-in

Players sign in with their Microsoft account through Microsoft's own sign-in page (OAuth device code flow → Xbox Live → XSTS → Minecraft Services). The launcher:

- requires sign-in and checks game ownership before the game can be started
- never sees or stores passwords
- keeps tokens only on the player's own PC

## Status

Personal project, Windows only. Built with Rust and [Tauri](https://tauri.app).
