# MateLightScrewCap
This Repo is based on the idea of [MateLight](http://matelight.rocks/) and improves it by a screw cap which is easy to install and easy to remove from the coasters.

In this Repository you can find the schematics and board layouts created in Eagle. Also, you can find a 3D model of the PCB.

*Fork me and have fun!*


## Power source

An APA102C LED consumes a maximum of 60 mA (red/green/blue each 20 mA). It is recommended to use a new 5 V / 1.4 mA power source for each 20 bottles(higher current delivery dose not matter).

```
  ___  ^ 5V /    LED 1                            LED 19             LED 20             ___  ^ 5V /   LED 21     
   |   | 1.4A  ___________  +5V            +5V   ___________  +5V    ___________ +5V     |   | 1.4A  ___________  +5V  
   |   °------|    ___    |------         ------|    ___    |------|    ___    |--|      |   °------|    ___    |------
   |     GND  |   /   \   | GND            GND  |   /   \   | GND  |   /   \   | GND     |     GND  |   /   \   | GND  
---°----------|  |     |  |------         ------|  |     |  |------|  |     |  |---------°----------|  |     |  |------
         CLK  |  |     |  | CLK     ...    CLK  |  |     |  | CLK  |  |     |  | CLK           CLK  |  |     |  | CLK     ...
------->------|  |     |  |------         ------|  |     |  |------|  |     |  |------------->------|  |     |  |------
         D    |   \___/   | D              D    |   \___/   | D    |   \___/   | D             D    |   \___/   | D    
------->------|___________|------         ------|___________|------|___________|------------->------|___________|------    
```

## 3D View (Fusion360)

Animated 3D STL model: [3d-model/MateLightScrewCap.stl](https://github.com/HansAchterbahn/MateLightScrewCap/blob/Release-36c3/3d-model/MateLightScrewCap.stl)

__Top view__

![3D top view](doku/MateLightScrewCap-3D-TopView.png)

__Bottom view__

![3D bottom view](doku/MateLightScrewCap-3D-BottomView.png)

## Schematic

![Schematic view](doku/MateLightScrewCap-Schematic.png)

## Board

__Top view__

![Board top view](doku/MateLightScrewCap-Board-Top.png)

__Bottom view__

![Board top view](doku/MateLightScrewCap-Board-Bottom.png)
