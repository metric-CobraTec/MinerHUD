# MinerHUD Version 2.00 #
![MinerHUD](https://raw.githubusercontent.com/metric-CobraTec/MinerHUD/main/screenshots/version2/MinerHUDv2-intro.jpg)

## Introduction ##
Providing an enhancement of the Dual Universe interface and improved gameplay experience.<br>
View information at a glance of an eye without breaking your work flow.

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
- Distance meter maximum linked range
- Distance meter maximum unit range

### Alerts ###
- Alert, Territory Scan completed
- Alert, Territory Scan running
- Alert, Target liters Reached
- Alert, Target Ore Value Indication Reached
- Alert, Target Total Ore Value Reached
- Alert, Maximum Container Weight Reached

### Experimental Hud Module Panel ###
Side panel on your screen displaying:
- Total Ore value based on your settings
- Performance indicator: Liters per second
- Performance indicator: Quantas per second
- Alerts shown within panel

### Other ###
Multiple Color schemes available

## Requirements ##
- Remote controller or programming board. RC recommended because of better maximum range.
- Container hub and/or container

## Installation ##
> It is recommended you deploy your control unit aside the container hub or container for optimal distance meter results.

1. Deploy your Control Unit (remote controller or programming board)
2. Copy MinerHUD content from MinerHUD.txt to your clipboard
3. Right click control unit -> Advanced -> Paste Lua Configuration from Clipboard
4. Link remote controller to container hub or container

Recommended you change MinerHUD settings to your needs.
Preloaded with default settings.

If you're not using a remote controller, set remote controlled to false in settings.

If you are using a remote controller <span style="color:red;font-weight: bold;">Make sure remote controller has been set to "true" in settings.</span><br>
This setting will try to prevent your vessel from being launched into the air when mining underwater.

## Getting Started ##
> TIP: Start with an empty container and get familiar with MinerHUD.

<span style="color:red;font-weight: bold;">Territory Scanner Alert:</span> Scroll down to <span style="font-weight: bold;">Caution</span> for further information

Activate your control unit to enable your MinerHUD.

Use ALT + 1 , shortcut key to activate your territory scanner alert

Use ALT + 2 , toggle MinerHUD experimental Module

Alerts will automatically activate MinerHUD experimental Module


## Change Settings ##

Customize settings to your needs:

- Right click control unit -> Advanced -> Edit Lua Script
- Click on Unit
- Click on Start
- Edit user settings and ore settings
- Click Apply to save changes


### Available Settings/Config ###

- Remote controlled
- Theme
- Triangle colors
- Linked range
- Unit range
- Ore indication value
- Target maximum weight
- Target Maximum liters
- Target ore indication value
- Target actual ore total value
- Tier 1/2/3/4/5 ore values

## Shortcut Keys ##

| Key   | Description                    |
|-------|--------------------------------|
| CTRL + BACKSPACE | Shutdown MinerHUD |
| ALT + 1 | Start territory scanner countdown alert |
| ALT + 2 | Hide or show experimental Hud panel |

Other Shortcut keys are currently reserved.

## Upcoming ##

Upcoming features include but not limited to:

- Change refresh rate
- Required warp cells and costs calculation
- Bar chart to show your recent mining performance
- Code optimization and reduction
- And more...

## Change Log ##

### Version 2.00 ###

#### Added ####
- Experimental MinerHUD module (panel)
- Automated detection and exclusion of non ores on start controller
- Attempt to detect and exclude non ores every 60 seconds 
- Actual total ore value shown in panel and updated every 60 seconds
- Set ore values (Tier 1/2/3/4/5) for accurate calculation 
- Performance indicator liters per second
- Performance indicator quantas per second
- Alerts will activate panel to inform user of changes
- ALT + 2 Shortkey to hide or show panel 
- Alert, set target liters
- Alert, set target ore indication
- Alert, set target actual total ore value
- Boot panel will display current version
- Prices by default set with dual.sh ore prices

#### Changed ####
- Removed: exclude volume (now automated)
- Removed: Display shutdown setting
- Removed: Display Version number setting
- Removed: Parameters
- Removed: Additional screen
- Moved: Alert total maximum weight to panel 
- Moved: Alert Territory scanner completed to panel
- Moved: Alertm Territory scanner running to panel 
- Improvement: Distance ranges easier readable
- Improvement: Code optimization

#### Fixed ####

### Version 1.01 ###
#### Added ####
#### Changed ####
#### Fixed ####
- Incorrect territory scanner duration
- Unwanted lua console output


## Caution ##
> DISCLAIMER: MinerHUD usage PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND.

- Remote controller does not support entering build mode.

- Underwater mining, when activating MinerHUD it will try to disable all your engine types

<div style="color:red;font-weight: bold;">Territory Scanner Alert:</div>

> Currently not recommended using territory scanner on your vessel in combination with remote controller, micro movements can abort your scanner

- Work Around #1: Deploy dynamic construct for territory scanner

- Work Around #2: Deploy seperate dynamic construct with controller + container

- Work Around #3: Use programming board with as disadvantage: reduced range 

## Known Bugs and Issues ##
Currently no bugs or issues reported.

## Support, Report bugs and Feature Requests ##
DU Open Source Initiative Channel - [Visit Discord Server](https://discord.com/channels/760240626942869546/812517764249288745/812520452844945448)Initiative")
or
You can send PM in Discord @ Metric#7020

## External Links ##

Dual Universe - [https://www.dualuniverse.game/](https://www.dualuniverse.game/ "Dual Universe")

Dual.sh - [https://dual.sh/](https://dual.sh/ "Dual.sh")

DU Open Source Initiative Channel - [Visit Discord Server](https://discord.com/channels/760240626942869546/812517764249288745/812520452844945448)


