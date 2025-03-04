# cardnet

Your Telnet rig for the M5Stack Cardputer – a direct connection to the net.

## Download
Ready to jack into the grid? Hit the [releases page](https://github.com/evilkbgy9/cardnet/releases) and grab the bin.

## How to Jack In
First step: you gotta spin up a file called `wificred.txt` – slap that sucker right on the root of your SD card. This file's the key to your grid access: network name on the first line, password on the second, and make sure there's a newline between 'em. If you need to change the creds later, fire up [MicroHydra](https://github.com/echo-lalia/MicroHydra). It's got a preem file manager and text editor built in. You can flip between cardnet, MicroHydra, and other firmware with [M5Launcher](https://github.com/bmorcelli/M5Stick-Launcher/), no need for a PC. Just slot an SD card with the firmwares you need.

## More Info
This project’s a spinoff of [TelnetClient-M5Cardputer by aat440hz](https://github.com/aat440hz/TelnetClient-M5Cardputer/) – not much changed, just added a slick new way to store your wifi creds on the SD card instead of hardcoding 'em into the source code.
