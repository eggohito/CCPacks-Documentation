---
title: Home
date: 2021-04-04
---
# Welcome to the Apolis documentation!

This page will hopefully contain all the information you need to make your own data packs for the Apolis mod.

Apolis is a Minecraft mod developed for Fabric. It allows players to choose an Apoli at the beginning of the game, which grants them different benefits and drawbacks.

Visit [CurseForge](https://www.curseforge.com/minecraft/mc-mods/apolis) or [Modrinth](https://modrinth.com/mod/apolis) to download the mod!

## General information

- Most powers are now configurable via data packs. You can also add new powers, as well as new apolis, via data packs. This wiki should help you as a reference for everything important, and will maybe contain a few useful tutorials in the future.
- You are welcome to join the [Apolis Discord server](https://discord.gg/4mTMHu3) if you want to talk about the mod, making data packs or add-ons for the mod, or to discover servers which use the mod which are sometimes advertised there.
- What is considered "meat" is defined via a tag (`apolis/tags/items/meat`), so you can add modded foods in there if you want. Avians can eat all food items that are not in the meat tag. However, if the mod correctly defines the food component as meat in code, it should work out of the box.
- You can add food to the tag `apolis/tags/items/ignore_diet` if you want it to be edible by both vegetarians and carnivores.
- Blocks which are not passable for Phantoms include bedrock, obsidian and crying obsidian. You can change this via a tag as well (`apolis/tags/blocks/unphasable`).
- For the Feline and Shulk, blocks which are considered "natural stone" are also defined via a tag (`apolis/tags/blocks/natural_stone`). By default, it includes stone, diorite, andesite, granite, netherrack, blackstone and basalt.
- There is an "Orb of Apoli" item available in the creative menu. It's a consumable that allows players to change their apoli. If you want this to be obtainable in survival, add a crafting recipe via a data pack.

## Helpful links

* [Example data packs](https://github.com/apace100/apolis-example-packs)
* [Minecraft Wiki: Data Pack](https://minecraft.gamepedia.com/Data_Pack)
* [Minecraft Wiki: Creating a data pack](https://minecraft.gamepedia.com/Tutorials/Creating_a_data_pack)
* [Video Tutorial for creating custom apolis with data packs by CandyCaneCazoo](https://www.youtube.com/watch?v=jId0Fw4w2PQ)
