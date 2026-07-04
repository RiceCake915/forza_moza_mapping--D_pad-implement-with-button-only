# Forza - Moza Mapping Config Files

# IMPORTANT! You have to remap your controls in game after replacing the config file! Otherwise it will not work!

Only edited Moza R5 config for D_pad *InputType* from switch to button, as I cannot get the original to work with switch InputType to have the d_pad icon on Anna and Link function.

## Forza Horizon 6

### Fixes

- DPad navigation
- Engine revving in upgrade menu
- Map automatically zooming in (zoom in with throttle now)
- Binds for Eliminator (upgrade selection)

### Adds

- Map zoom out with brake
- Car Meets bind

## Installation

To use this config file for your Moza Steering Wheel, download the file and copy it to:

Drive:\SteamLibrary\steamapps\common\ForzaHorizon6\media\inputmappingprofiles.zip (only open, don't extract)

- Open archive in 7zip
- Drag downloaded config onto 7zip window, confirm changes
- Close 7zip, restart Forza, and **rebind your controls**

![example](https://github.com/goodluckNito/forza_moza_mapping/blob/main/FH6/example.gif)

Here is a short video of how to install and remap the controls:

https://youtu.be/HveJplZZjtQ?si=DOeNxcCIr_7cYOFw

## Original Configs
backups of the original game configs in case you forgot to back them up and something breaks

## If you can't get the game to work with your wheel
- Go to [Gamepad Tester](https://hardwaretester.com/gamepad)
- You'll see a device name, for example: `346e-0004-MOZA R5 Base`
- Compare the beginning 4 numbers to the `VidPid` in the config you downloaded, for example: `VidPid="0x346e0004"`
- The last 4 digits need to match the device that Gamepad Tester shows. If not, Replace All with the correct number.
- Re-merge the zip with the new config, rebind your controls, and it should be properly detected.

