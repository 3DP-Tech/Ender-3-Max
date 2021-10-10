# Ender-3-Max
Marlin 2.0.9.2 configuration for Ender 3 Max with CR Touch mounted with the OEM mount. If you are using the BL Touch with a different mount you may need to adjust the probe offset values. Search for `NOZZLE_TO_PROBE_OFFSET` in **Configuration.h**.

Copy **Configuration.h** and **Configuration_adv.h** into the Marlin folder overwriting the existing files.

To compile, change the value of `default_envs` to `STM32F103RET6_creality` in **platformio.ini**.

Guide to build firmware: [Teaching Tech - Updated Marlin firmware setup guide - VS Code and Auto Build Marlin](https://www.youtube.com/watch?v=eq_ygvHF29I)

This firmeware configuration files are provided as-is and you agree to assume all risk when you download them and apply them to your printer.
