# MarlinFirmwares

This Repo contains various configurations and compiled bin for Creality Printers.

## Folder Structure
* PrinterModel
    * Marlin Version
        * Board Version
            * ABL
                * Config Files
                * Compiled Bin
            * Stock
                * Config Files
                * Compiled Bin


## Features
Over the baseline Marlin Project following Features are enabled.
* Enabled BLTouch (optional bin)
* Enabled Babystepping, set steps to 0.05mm on Z axis
* Enabled Bed Tramming, including Level Center 

## How to compile Marlin 2?
Follow this [video](https://youtu.be/qPDBNBgdW6o?t=680) on walk through on how to compile Marlin 2.

## How to Update Firmware?
* Prepare SD Card by formatting the SD Card with Filesystem = FAT32 and Allocation Size = "4096 bytes".
* Copy the copiled/downloaded bin file in SD Card.
* Turn Off the Printer
* Put SD Card in Printer
* Turn the Printer on, it will take a minute or 2 to update
* When the printer re-starts, it may ask to reset the EEPROM settings. Remove the sd card and select reset. The printer may restart and ask again, select reset again.
* If on re-start, the printer does not ask to reset EEPROM, go to Configuration > Advance Setting and select Initialize EEPROM. This will reset the configurations.
