# SHMod24
(Smart Home Module NRF24)

WORK IN PROGRESS.

This PCB is a universal microcontroller board with many optionally placable components. It aims to be an universal base-board for many projects especially around home automation.

## Features
- Choice of ATMega328 (Arduino Pro Mini) or ESP8266 (ESP12-F) as the µC
- NRF24L01+ SMD with power filtering
- 6-30V input
- Lithium battery support with charging and protection circuit

## Project installation
- Make sure to run `git clone` with `--recurse-submodules` to include the necessary libraries too.
- To use the 3D Models, set the following environment variables:
  - **ESPLIB** : `${KIPRJMOD}\lib_includes\kicad-ESP8266`
  - **MYSLOCAL** : `${KIPRJMOD}\lib_includes`
  - Note: Sometimes you need to manually replace `${KIPRJMOD}` with the absolute path to the project