# vector-pincushion

## Allows CRT swaps between various vector game boards and deflection boards. 

Finding tubes for vector arcade displays is difficult and being able to mix and match deflection boards, TV CRTs and arcade PCBs is becoming a necessity. Some arcade games relied on an exact combination of tube shape, yoke, and game board to correctly display.  There may be analog corrections on either the arcade PCB or the deflection board or even the CRT yoke and neck. The Amplifone deflection boards contain no corrections, so when used with a Wells Gardner game PCB adding a correction board is a necessity to add the missing circuity. Tempest PCBs lacked the adjustments as did Sega vectors, but more advanced games like Major Havoc and Star Wars had them on the game boards rather than the deflection boards.

This board allows correction or decorrection as required depending on what you have combined.

### Linearity adjustment 
applies the function _X = X * k_ and _Y = Y * k_ allowing calibration of straightness in diagonally drawn vectors. When set to expansion mode, the correction will cause lines to be drawn further and further outward from the center. When set to shrink mode, the correction will cause lines to be drawn closer and closer the further they are from the center.

### Pincushion correction 
applies the function _X = X * k * Y_ and _Y = Y * k * X_ allowing for each axis to be drawn further or closer toward the center depending on the *opposite* axis distance from center.

## Features

* Barreling correction mode
* Pincushion correction mode
* Linearity shrinking mode
* Linearity expansion mode
* Performs geometric distortion math in analog circuity
* Single 5V supply
* No unobtanium voltage dependent resistor required
* No unobtanium MC1495 analog multipler required
* All new design around the AD633 analog multipler typically used in very high end audio equipment.
* Supports 2x faster speed than orignal when used with TI-H 5.25MHz bandwidth amplifiers.
  
