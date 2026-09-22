# Submodules needed for FaderMonster 

## Cloning 
- Clone this repo to a folder (Arduino IDE `libraries` folder, maybe?)
- `git submodule init` (first time only?)
- `git submodule update` if you think anything upstream might have changed

Need to check if `cores` being in the Arduino libraries causes issues. Shouldn't, no header in its root and no `src` subfolder.

## `cores` preparation 
- copy `cores` to replace your Arduino package's Teensy `cores` (rename the old one, if you like...)

## FreeRTOS preparation

- make sure you've set `#define configTEENSY_ENABLE_HEAP_IN_RAM1 0` in `FreeRTOSConfig.h`


