# cardnet
Your Telnet rig for M5Stack Cardputer – a direct link to the net, no jacks required.

## How to Jack In
First, you gotta create a file named `wificred.txt` – slap it on the root of your SD card. This file’s gonna hold your connection deets: network name on the first line, the password on the second, and don't forget that newline between. If you need to change it later, fire up [MicroHydra](https://github.com/echo-lalia/MicroHydra). You can switch between cardnet, MicroHydra, and other firmwares using [M5Launcher](https://github.com/bmorcelli/M5Stick-Launcher/), no PC required. Just slot an SD card with what you need.

## More Info
This project’s a spin-off of [TelnetClient-M5Cardputer by aat440hz](https://github.com/aat440hz/TelnetClient-M5Cardputer/) – not much to change, just added a sweet storage option for your wifi creds on the SD card instead of hardcoding them in the source. Keep it clean, keep it stealthy.
