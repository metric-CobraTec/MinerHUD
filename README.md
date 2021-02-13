# MinerHUD V1.01 #
![MinerHUD](https://raw.githubusercontent.com/metric-CobraTec/MinerHUD/main/screenshots/minerhud.jpg)
![MinerHUDv1](https://raw.githubusercontent.com/metric-CobraTec/MinerHUD/main/screenshots/MinerHUDv1.jpg)

## Introduction ##
Providing an enhancement of the Dual Universe interface and improved gameplay experience.<br>
View information at a glance of an eye without extra need to open a panel and break your work flow.

Enjoy a more motivating mining experience by watching your ore and quanta balance grow realtime.

## Features ##
### Display Mass and Volume ###
- Display (Kiloton) Kt
- Display (Ton) T
- Display (Kilogram) Kg
- Display (Liter) L

### Display Miscellaneous ###
- Display quanta value
- Display (hh:mm:ss) elapsed time

### Distance Meter ###
- Distance meter to show your current maximum linked container range
- Distance meter to show your current maximum unit range

### Alerts ###
- Alert when defined weight (Kg) has been reached
- Alert when Territory Scan has been completed
- Alert, confirmation when Territory Scan has been started

### Other ###
Multiple Color schemes available

## Requirements ##
- Remote controller or programming board. RC recommended because of better maximum range.
- Screen, any size will do
- Container hub and/or container

## Installation ##
> It is recommended you deploy your control unit aside the container hub or container for optimal distance meter results.

1. Deploy your Control Unit (remote controller or programming board)
2. Link remote controller to screen
3. Link remote controller to container hub or container
4. Copy MinerHUD content from MinerHUD.txt to your clipboard
4. Right click control unit -> Advanced -> Paste Lua Configuration from Clipboard

## Getting Started ##
> TIP: Start with an empty container and get familiar with MinerHUD.

Activate your control unit to enable your MinerHUD.

Change settings to your needs.

Use ALT + 1 shortcut key to activate your Territory Scanner Alert

## Available Settings ##
- unit range
- linked container range
- display default or colored distance meter indicators
- set color scheme
- set maximum kg weight to activate alert
- display version
- display manual shutdown shortcut
- display unit panel
- ore indication price
- exclude volume (your current cargo) from value calculation

### Parameters ###
Right click your control unit -> advanced -> Edit Lua Parameters

|                            | Description                                          | Type    | Checkbox | Example |
|----------------------------|------------------------------------------------------|---------|----------|---------|
| minusLiter                 | exclude volume from HUD and value calculation        | number  | false    | 5000.75 |
| unitRange                  | set your control unit range                          | number  | false    | 1000    |
| linkedRange                | set your maximum linked range                        | number  | false    | 250     |
| showDistanceTriangleColors | display default or colored distance meter indicators | boolean | true     |         |
| MaximumKG                  | set maximum cargo weight in Kg for alert             | number  | false    | 10000   |
| version                    | display version number                               | boolean | true     |         |
| showExit                   | display shortcut for manual shutdown                 | boolean | true     |         |
| enableUnitPanel            | display unit panel                                   | boolean | true     |         |
| orePrice                   | set ore indication/average price for calculation     | number  | false    | 25.01   |
| colorSchemeDefault         | enable color scheme                                  | boolean | true     |         |
| colorSchemeOrange          | enable color scheme                                  | boolean | true     |         |
| colorSchemeRed             | enable color scheme                                  | boolean | true     |         |
| colorSchemeCyan            | enable color scheme                                  | boolean | true     |         |

## Shortcut Keys ##
| Key   | Description                    |
|-------|--------------------------------|
| CTRL + BACKSPACE | Shutdown MinerHUD |
| ALT + 1 | Activate territory scanner alert upon completion |

Other Shortcut keys are currently reserved.

## Upcoming ##
Upcoming features include but not limited to:

- Change refresh rate
- Alert liter/value target
- Average quanta performance p/s
- Average liter performance p/s
- Required warp cells and costs calculation
- Bar chart to show your recent mining performance
- Improved total container ore value
- Code optimization and reduction
- And more...

## Caution ##
> DISCLAIMER: MinerHUD usage PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND.

- While MinerHUD is active you cannot enter build mode.

- Territory Scanner, Make sure your vessel comes to a complete stop before activating to avoid scanner interruption

- Underwater mining, when activating MinerHUD through your control unit it will try to disable your engines and adjusters
