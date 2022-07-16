# Ender-3-Max 
Marlin 2.1 configuration for Ender 3 Max with CR Touch/BL Touch.

The **Configuration** folder contains the files needed to compile the firmware. The bin folder contains a pre-compiled binary that can be applied to the printer.

The configuration is compiled with the board name `BOARD_CREALITY_V4` targeted for verion 4.2.2 of the controller board. Use `STM32F103RE_creality` in ***platform.ini***.

In this version I defined the printable volume as 310 (x) by 310 (y) by 360 (z). The OEM firmware defines it as 300 x 300 x 340. This helps the bed leveling process to be centered on the bed resulting in slightly better accuracy.

This will not work on the 4.2.7 board without modification to the `Configuration.h` file.

## Viewing Changes
If you would like to view the changes I made from the OEM Ender 3 Max configuration, you can view the differences in your favorite tool by comparing these files to the files found at [https://github.com/MarlinFirmware/Configurations/tree/release-2.1/config/examples/Creality/Ender-3%20Max](https://github.com/MarlinFirmware/Configurations/tree/release-2.1/config/examples/Creality/Ender-3%20Max).

### Using GitHub Desktop
1. Download and install GitHub desktop from [https://desktop.github.com](https://desktop.github.com)
2. Open GitHub desktop and clone the Marlin Configurations repository using the URL **https://github.com/MarlinFirmware/Configurations.git**
3. Copy the `Configuration.h` and `Configuration_adv.h` files from this repository into the Marlin Configuration folder `Configurations/config/examples/Creality/Ender-3 Max`
4. Select one of the files in GitHub Desktop and it will show the changes I have made to the original files.
5. Optionally, click the **Gear** icon on the right and select **Split** to view the changes in split view mode as shown below.

![](https://github.com/3DP-Tech/Ender-3-Max/raw/Marlin-2.1/Images/Diff.png)