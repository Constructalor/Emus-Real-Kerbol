# Emu's Real Kerbol
Emu's Real Kerbol is a mod for Kerbal Space Program that aims to revamp the Kerbol system with real-scale and gameplay in mind, as well as reviving cut planets and moons from KSP1 and KSP2.

The stock system and vast majority of planet mods are designed to work at 10% of real scale. When scaled up, the planets become flattened and surface features lose their structure and intensity. ERK is designed to work at 100% real scale, utilizing much higher resolution textures than the standard for planet mods.

ERK will also rebalance the stock parts to work with real scale so you don't have to download extra mods if you don't want to.

ERK is currently very early in development. You can try the mod in its unfinished state by downloading the GitHub repository. Be warned that ERK has some bugs and is missing key features, so play at your own risk.

## Contributors

Emu (Mod author)

Gabo (Part reconfig)

## Installation Guide

ERK is currently in early access. Features are being added incrementally with updates.

### Install Manually

1. Download the mod's dependencies -
   - [Kopernicus](https://github.com/kopernicus/kopernicus/releases)
   - [KSP Community Fixes](https://github.com/KSPModdingLibs/KSPCommunityFixes/releases)
   - [Kopernicus Expansion](https://github.com/VabienArt/KopernicusExpansion-Continueder/releases/)
   - [Niako's Kopernicus Utilities](https://github.com/pkmniako/Kopernicus_VertexMitchellNetravaliHeightMap/releases)
   - [Vertex Color Map Emissive](https://github.com/jamespglaze/VertexColorMapEmissive/releases)
   - [SMURFF](https://github.com/Kerbas-ad-astra/SMURFF)
   - [Rational Resources](https://github.com/JadeOfMaar/RationalResources)
2. Extract each dependency’s `.zip` and place its folders into your `GameData` directory.
3. [Download the latest release]([https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository?tool=desktop&platform=windows](https://github.com/Constructalor/Emus-Real-Kerbol/releases))
4. Extract ERK’s `.zip` and place its folders into your `GameData` directory.

ERK should be played on a fresh save.

### Visual Mods

ERK is compatible with any visual mods that do not alter the stock planet textures, however some require extra steps to work with ERK.

#### Parallax Continued
Delete the `Parallax_StockPlanetTextures`, `Parallax_StockScatterTextures` and `Parallax_StockTerrainTextures` folders (and the `Parallax_LifelessEvePatch` folder if installed).

#### EVE Volumetric Clouds
Delete the `StockVolumetricClouds` folder.

#### Scatterer
Delete the `StockScattererConfigs` folder.

### Soundtrack

ERK has its own custom soundtrack that works with Soundtrack Editor Forked.
1. Download [Soundtrack Editor Forked](https://forum.kerbalspaceprogram.com/topic/191467-112x-soundtrack-editor-forked/) and its dependencies
2. Follow the installation instructions on the forum page
3. Remove the `Music` and `Playlists` folders
4. Place the ERK `Music` and `Playlists` folders into your KSP directory

### Compatibility

ERK is compatible with TiltEm Continued.

ERK compatibility with other planet mods has not been tested yet.


### BDB Compatibility
if you are using BDB please do the following for adequate Smurff compat
1) go in the bdb game data
2) Gamedata/Bluedog_DB/Compatibility/Rescale
3) you should see a file called blueSmurff
4) in that file modify the line highlighted to false <img width="1314" height="706" alt="image" src="https://github.com/user-attachments/assets/d41f3ad1-b5c6-4c03-a2a0-6336d8542074" />

