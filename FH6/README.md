#Fixes

- DPAD navigation
- Engine revving in upgrade menu
- Map automatically zooming in (zoom in with throttle now)

#Adds

- Map zoom out with brake
- Car Meets

#Original Configs
backups of the original game configs in case you forgot to back them up and something breaks

#If you can't get the game to work with your wheel
- Go to [Gamepad Tester](https://hardwaretester.com/gamepad)
- You'll see a device name, for example: `346e-0004-MOZA R5 Base`
- Compare the beginning 4 numbers to the `VidPid` in the config you downloaded, for example: `VidPid="0x346e0004"`
- The last 4 digits need to match the device that Gamepad Tester shows. If not, Replace All with the correct number.
- Re-merge the zip with the new config, rebind your controls, and it should be properly detected.
