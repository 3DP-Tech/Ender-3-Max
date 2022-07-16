# Ender-3-Max 
Marlin 2.1 configuration for Ender 3 Max with CR Touch/BL Touch.

The **Configuration** folder contains the files needed to compile the firmware. The bin folder contains a pre-compiled binary that can be applied to the printer.

The configuration is compiled with the board name `BOARD_CREALITY_V4` targeted for verion 4.2.2 of the controller board. Use `STM32F103RE_creality` in ***platform.ini***.

In this version I defined the printable volume as 310 (x) by 310 (y) by 360 (z). The OEM firmware defines it as 300 x 300 x 340. This helps the bed leveling process to be centered on the bed resulting in slightly better accuracy.

This will not work on the 4.2.7 board without modification to the `Configuration.h` file.
