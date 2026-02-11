# FPS-CS2-Optimization-Guide

NVIDIA Settings
  Manage 3d settings, select CS2
    shader cache -> 10 GB
    Vertical Sync -> off
    powermanagement mode -> maximum performance
    low latency mode -> ultra
    refresh rate -> highest available

BIOS Settings
consider to update your BIOS when not done for a long time.
Enable EXPO (AMD) or XMP (Intel) RAM profile. (RAM is running on stock clocks, when you buy RAM its probably able to run way higher than on stock clocks!)
Enable XMP/(EXPO High Bandwith Support
Enable Low Latency Support
Enable Above 4G Decoding (for high end system)
Enable Re-Size BAR Support (for high end system)
SMT Mode -> Enable less than 8 COREs. Disable 8 or more.


Windows Settings
enable "Game Mode"
Power Plan Options: enable "Ultimate Performance" Power Plan. 
  This plan is hidden and needs to be activated through two ways. See christitus Windows Tool below or use the following command in powershell: powercfg -duplicatescheme e9a42b02-d5df-448d-aa00-03f14749eb61

Registry Changes (at your own risk) 
-

General Note
Update your drivers like GPU (NVIDIA / AMD), Chipset and Network.

This is not specifically related to FPS and CS2 Optimization, but is giving your PC more efficency on games when disabling Windows features like Co-Pilot, etc. Additionally adds some privacy when disabling Tracking and Telemetry and gives the option to update your applications with one click. Check it out here:
https://christitus.com/windows-tool/



