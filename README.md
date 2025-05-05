# Takeoff-Toolhead-Clamps
Is it about time to *takeoff* your current toolhead? Well you're in the right spot!

The **ONLY** fully open source SLM voron toolhead

An SLM toolhead using 3628s and [Chube](https://chubehotend.com), with no X loss. There will be some Y loss (17mm~ from hitting the front door) unless you have a [clicky clacky door](https://github.com/tanaes/whopping_Voron_mods/tree/main/clickyclacky_door), a v2.4 that allows moving the bed back, or a 4040-based frame, such as DoomCube

> [!WARNING]  
> For tridents, you need to cut the front left and rear leadscrew, or use [these](https://www.printables.com/model/486638-voron-trident-z-steppers-spacers) (recommended), to avoid losing travel

> [!WARNING]  
> For those aiming for high belt tensions, a pretension tool is necessary since the mount uses clamping. I recommend using [this one](https://www.printables.com/model/1027579-sovol-sv08-belt-helper-for-x-carriage).

## Luke's Laboratory is [selling kits for takeoff!](https://lukeslabonline.com/products/takeoff-toolhead) I'll be getting a percentage of each sale. If you don't wanna wait/want to support me purchase from them!

## 3Dkatten is [selling kits for takeoff!](https://3dkatten.se/en/products/takeoff-toolhead) I'll be getting a percentage of each sale. If you don't wanna wait/want to support me purchase from them!

##Klipper Setup https://github.com/KalicoCrew/kalico Kalico is the recommendation for MPC

[beacon]
x_offset:-23.48

[fan] #only 2 wires
max_power: 1 #set to .8 for kraken (btt moment)
off_below: 0.13

[verify_heater extruder] #use with mpc
max_error: 120
check_gain_time: 25
hysteresis: 10

[extruder]
control = mpc
heater_power: 120
#ambient_temp_sensor: temperature_fan chamber #if you have a chamber thermistor
cooling_fan: fan
#Recommend 9 minimum FAN_BREAKPOINT for calibration

#Example MPC config from Ericzimmerman
# block_heat_capacity: 26.1100
# sensor_responsiveness: 0.115066
# ambient_transfer: 0.0708064
# fan_ambient_transfer: 0.0708064, 0.147823, 0.179016, 0.19074, 0.206899, 0.22524, 0.21861

Extruders Compatible:

<u>Option A Has mounts for:</u>


LGX Lite Pro

Vz-Hextrudort

Sherpa Mini (No K-face)

Sherpa Micro (With K-face), Mellow CNC Sherpa Micro supported, but no K-face is available

Orbiter 2/Peopoly Lancer Orbiter 2 Version


<u>Option B Has mounts for: </u>

Sherpa Mini (with K-face), Fysetc CNC Sherpa Mini supported 

Peopoly Lancer new/old (rotated COM for both)

DFA/Orbital Ascender (PENDING OA RELEASE)

A3DP FXD 

![Side View Image](Images/Takeoff%20Side%20Shot.png)
![Front View](Images/Takeoff%20Front%20View.png)
![The Purrrfect Toolhead](Images/Purrrfect%20Top%20Plate.png)

![My Beautiful Toolhead installation](Images/Burgos%20install.jpg)

## How does that belt path work?
The belt path relies on you deflecting the belt with itself so that it's straight, the belt must be feed with another piece of belt (or itself) near the XY joints so it's parallel.


![Monolith Belt Install](Images/Monolith%20Belt%20Path.png)
![Voron Belt Install](Images/Voron%20Belt%20Path.png)

<a href='https://ko-fi.com/burgo' target='_blank'><img height='46' style='border:0px;height:46px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a> 

**Want help/ learn more: Join my discord!**

[![Join the Discord](https://discord.com/api/guilds/1192556731952275476/widget.png?style=banner3)](https://discord.gg/6pRs2kgsKK)

### BIG Shoutout to Turtlecrawler for helping me redraw the mainbody, a clean timeline is always fun in the end.
