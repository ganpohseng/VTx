# VTx Lua Script - v1.1

This stripped-down fork of [betaflight-tx-lua-scripts](https://github.com/betaflight/betaflight-tx-lua-scripts) includes only VTx configuration on FrSky transmitters.  VTx lua script was created to save memory on your transmitter so other Lua scripts (for example [Lua Telemetry](https://github.com/iNavFlight/LuaTelemetry)) can run on the same model. This script should work with [Betaflight](https://github.com/betaflight/betaflight) as well as [INAV](https://github.com/iNavFlight/inav).

### Features

* Uses less memory than [betaflight-tx-lua-scripts](https://github.com/betaflight/betaflight-tx-lua-scripts)
* Allows for multiple Lua scripts to be run on the same model (for example [Lua Telemetry](https://github.com/iNavFlight/LuaTelemetry))
* Only allows for VTx control (no PID adjustments)
* Works on Taranis and Horus transmitters running SmartPort or F.Port telemetry
* Works with [INAV](https://github.com/iNavFlight/inav) and probably [Betaflight](https://github.com/betaflight/betaflight) (untested)

### Installation instructions

1. [Download](https://github.com/teckel12/Taranis-VTx/releases/latest) the the latest released `VTx.zip` file
1. Copy `VTx.lua` file and `VTx` folder with contents to transmitter's SD card's `\SCRIPTS\TELEMETRY\` folder
1. Add `VTx` Lua script to desired model display screen
