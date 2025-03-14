# Road_Redemption_VR_bHaptics

<img src="https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/300380/header.jpg">

# Description

Road Redemption VR mod with bHaptics support vest and arms.</br>

Steam page of the game: [https://store.steampowered.com/app/300380/Road_Redemption/](https://store.steampowered.com/app/300380/Road_Redemption/)

Two awesome VR content creators discord links: </br>
Farmertrue: https://discord.gg/G8zZBTGuhP </br>
Dteyn: https://discord.gg/Qt7GT69Pzx </br>

☕ If you wanna show some support you can buy me a coffee : https://www.buymeacoffee.com/astienth4 </br>

# <b>Installation</b></br>

1) Download the zip file from [https://github.com/Astienth/Road_Redemption_VR_bHaptics/releases/download/1.0/RoadRedemptionVR.zip](https://github.com/Astienth/Road_Redemption_VR_bHaptics/releases/download/1.0/RoadRedemptionVR.zip)</br>
2) Extract its content into the game root folder, the folder containing the "RoadRedemption.exe".</br>
3) **YOU MUST install VigemBus drivers** to be able to use VR controllers: launch the install exe that you can find in "GameFolder"/BepInEx/redist/ViGEmBus_1.22.0_x64_x86_arm64.exe
4) Launch the game like you usually launch it via steam or the exe file.
5) Enjoy !

## Features

- Third person view, just like the original game
- First person view with two levels of immersion, basic and full immersive
- VR controllers support

## Controls

VR controllers are mapped EXACTLY as a Xbox controller: buttons labelled with letters are the same, LB = Left grip, LT = Left Trigger. Same for the right side.
VR motion gestures can trigger left and right attacks with weapons like baseball bat, metal pipe, etc. Throw your arm towards your enemy and it will trigger the attack: left arm toward your left side, right arm toward your right side

## Config

```
## Settings file was created by plugin RoadRedemption_VR v1.0.0
## Plugin GUID: RoadRedemption_VR

[General]

## First Person view
# Setting type: String
# Default value: false
# Acceptable values: true, false
firstPersonView = false

## First Person view full immersive, head will follow player's head rotations at all time
# Setting type: String
# Default value: false
# Acceptable values: true, false
firstPersonViewFull = false

## applies vignette when rotating
# Setting type: String
# Default value: false
# Acceptable values: true, false
vignette = false

## Max Vignette value (between 0 and 100)
# Setting type: Single
# Default value: 100
maxVignetteValue = 100

```
This file is created after the first launch of the game with this mod, at **BepInEx/config/RoadRedemption_VR.cfg**</br>
Edit this file and turn "firstPersonView = false" to "firstPersonView = **true**" to activate first person view and VR controls.
You can activate Vignette for motion sickness if you need it and change the intensity value with 100 being the maximum.


