# Enhanced ESP32-S3 USB to BLE Keyboard Bridge

## How-To-Setup

1. Install VS Code
2. Install PlatformIO extension
3. Press `Ctrl+Shift+P` and type `PlatformIO CLI` and press enter
4. Type inside the terminal as follow
   1. `git clone https://github.com/AirulFmy/ESP32S3-USB-Keyboard-To-BLE-Plus.git`
   2. `cd ESP32S3-USB-Keyboard-To-BLE-Plus`
   3. It will take quite sometime for the necessary dependencies required by PlatformIO, just wait till everything finish

## PlatformIO Command
* Compile code : `pio run`
* Erase program from ESP32 : `pio run -t erase`
* Upload program to ESP32 : `pio run -t upload`
* To perform fresh install package and dependencies : `pio pkg uninstall`
* To perform package/dependencies update : `pio pkg update`
* Help : `pio --help`

## Changes

Additional Features implemented so far

✅ Caps Lock LED synchronization
✅ Num Lock LED synchronization
✅ Scroll Lock LED synchronization
✅ Fixed NVS compatibility issue
✅ Fixed ESP32-S3 runtime crash
✅ Tested on ESP32-S3-N16R8

## Disclaimer

This repository is originally forked from https://github.com/KoStard/ESP32S3-USB-Keyboard-To-BLE

The changes in this repository is to cater on some issue I encountered myself when I tried to compile and push to ESP32-S3 DevKit
