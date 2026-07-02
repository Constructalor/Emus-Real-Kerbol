# Emu's Real Kerbol
Emu's Real Kerbol is a mod for Kerbal Space Program that aims to revamp the Kerbol system with real-scale and gameplay in mind, as well as reviving cut planets and moons from KSP1 and KSP2.

The stock system and vast majority of planet mods are designed to work at 10% of real scale. When scaled up, the planets become flattened and surface features lose their structure and intensity. ERK is designed to work at 100% real scale, utilizing much higher resolution textures than the standard for planet mods.

ERK will also rebalance the stock parts to work with real scale so you don't have to download extra mods if you don't want to.

ERK is currently very early in development. You can try the mod in its unfinished state by downloading the GitHub repository. Be warned that ERK has some bugs and is missing key features, so play at your own risk.

## Installation Guide

ERK is currently very early in development. You can try the mod in its unfinished state by downloading the GitHub repository. Be warned that ERK has some bugs and is missing key features, so play at your own risk.

### Install Manually

1. Download the mod's dependencies -
   - [Kopernicus](https://github.com/kopernicus/kopernicus/releases)
   - [KSP Community Fixes](https://github.com/KSPModdingLibs/KSPCommunityFixes/releases)
   - [Kopernicus Expansion](https://github.com/VabienArt/KopernicusExpansion-Continueder/releases/)
   - [Niako's Kopernicus Utilities](https://github.com/pkmniako/Kopernicus_VertexMitchellNetravaliHeightMap/releases)
   - [Vertex Color Map Emissive](https://github.com/jamespglaze/VertexColorMapEmissive/releases)
2. Extract each dependency’s `.zip` and place its folders into your `GameData` directory.
3. Download ERK by cloning the repository and merging the `GameData` folder with your `GameData` folder.

ERK should be played on a fresh save.

### Visual Mods

ERK is compatible with any visual mods that do not alter the stock planet textures, however some require extra steps to work with ERK.

#### Parallax Continued
Delete the `Parallax_StockPlanetTextures`, `Parallax_StockScatterTextures` and `Parallax_StockTerrainTextures` folders (and the `Parallax_LifelessEvePatch` folder if installed).

#### EVE Volumetric Clouds
Delete the `StockVolumetricClouds` folder.

#### Scatterer
Delete the `StockScattererConfigs` folder.
