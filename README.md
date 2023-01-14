# skyrim_vr_3090

My work in progress modlist for my 3090 GPU. Trying to keep the FPS good but also tweak graphics as high as possible.

I also want to be systematic and trying to use to GIT to store all changes and to be able to version this setup.
Also keeping this open so any bugs or requests could be added by anyone.

# Installation

## Todo: Wabbajack part.

## Skyrim Upscaler VR - DLSS FSR2 XeSS

This modlist has already installed Skyrim Upscaler VR - DLSS FSR2 XeSS ( https://www.nexusmods.com/skyrimspecialedition/mods/82179 ) but now you also need to do some manual steps.

1. Download https://www.nexusmods.com/site/mods/502?tab=files and extract to game folder so that the final structure is SkyrimVR\Data\UpscalerBasePlugin\PDPerfPlugin.dll
2. Download the DLSS/DLAA upscaler .dll from https://www.techpowerup.com/download/nvidia-dlss-dll/ More links and other upscalers are here https://www.nexusmods.com/site/mods/502
3. Extract the arhive and move nvngx_dlss.dll into SkyrimVR\Data\UpscalerBasePlugin\ that was created in step 1.
4. In this modlist it's set to DLAA (antialiasing) only because there was no boost with DLSS
5. You can control the settings from game or from ini file if double-click "Skyrim Upscaler VR - DLSS FSR2 XeSS" in the MO2. In the game, multiply key toggle the plugin on and off, end key
   opens the menu but note that you only see on on your PC screen.

## Install ENB

ENB is a graphic mod that enhances post processing effects to make games look better graphically. The acronym stands for Enhanced Natural Beauty, a term coined when people started
modding the general graphics of Elder Scrolls Games trying to make it look more natural, mainly by manipulating the lighting.

Installing ENB can be divided to 2 parts. First downloading the ENB binarys, then choosing preset you like. We'll go with" Scenery ENB VR for Skyrim VR" as it looks great, but 
sadly also the most demanding.

1. Download the latest version here http://enbdev.com/download_mod_tesskyrimvr.html and extract. Inside there's WrapperVersion folder - move the contents of it to root
of your Skyrim VR.
2. Download "Scenery ENB VR for Skyrim VR" Main file https://www.nexusmods.com/skyrimspecialedition/mods/35545?tab=files and extract the contents. Inside there's "Scenery ENB VRX" - also move the contents of it to root
of your Skyrim VR.

## Skyrim Script Extender (SKSE)

The Skyrim Script Extender (SKSE) is a tool used by many Skyrim mods that expands scripting capabilities and adds additional functionality to the game.

1. Go to https://skse.silverlock.org/ and download the **"Current VR build x.x.x"**.
2. Extract and copy the .dll and .exe files to your Skyrim VR directory.
3. Copy the .pex files in Data\Scripts\ into the Data\Scripts\ folder of your installation.
4. Rest of the files are for developers, read sksevr_readme.txt for more info.
5. In your Mod Manager choose SKSE instead of Skyrim VR from the menu left from "Run" and then press "Run" to start the game.
