# FPS-CS2-Optimization-Guide
> [!IMPORTANT]
> Update your Drivers to the latest version! GPU, Chipset, Network and Audio.


## NVIDIA Settings
  Manage 3d settings, select programm CS2.exe
  - Shader cache -> 10 GB
  - Vertical Sync -> off
  - Powermanagement mode -> maximum performance
  - Low latency mode -> ultra
  - Refresh rate -> highest available


## BIOS Settings
> [!NOTE]
> Consider updating your BIOS when not done in a long time

- Enable EXPO (AMD) or XMP (Intel) RAM profile. (RAM is running on stock clocks, when you buy RAM its probably able to run way higher than on stock clocks!)
- Enable XMP/(EXPO High Bandwith Support
- Enable Low Latency Support
- Enable Above 4G Decoding (for high end system)
- Enable Re-Size BAR Support (for high end system)


## Windows Settings
- Enable "Game Mode"
- Power Plan Options:
  - enable "Ultimate Performance" Power Plan. (This plan is hidden and needs to be activated through two possible ways. See christitus Windows Tool below or use the following command in powershell: powercfg -duplicatescheme e9a42b02-d5df-448d-aa00-03f14749eb61)


## Further Optimization
### Tools
- [Christitus - Debloat and Optimization Software](https://christitus.com/windows-tool/).
  - This Tools gives more PC efficency in general, when disabling Windows features like Co-Pilot, etc. Additionally adds some privacy when disabling Tracking and Telemetry and gives the option to update your applications with one click.
  -   Check out YouTube for a Guide, for example JayzTwoCents
- [Latencymon - Measure Input Latency](https://resplendence.com/latencymon)
  - This Tool can be used to check where latency issues on the computer might happen, for example bad drivers, etc. 


## Other CS2 Optimization
- CS2 Audio Profile is pretty weak, if you want the best experience to hear footsteps, use an Equalizer for example Sonar from SteelSeries
- CS2 has issues with Shaders and Shader Cache from CS2 itself, NVIDIA and DirectX. It is recommended to clean Shaders after GPU Driver Updates or bigger CS2 updates. See my other Guide and one-click Files here: https://github.com/devfo/shader-clearing
  
### Optimal CS2 ingame Video Settings 
- Check out my Video Settings: https://github.com/devfo/CS2-Video-Settings/tree/main
