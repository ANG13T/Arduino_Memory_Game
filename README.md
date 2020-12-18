# Arduino Memory Game

A Simon-like memory game made usng the Arduino. 

## Materials

- Breadboard
- Arduino Uno
- Around 20 - 25 jumper wires
- 8 220ohm resistors
- 4 pushbuttons
- 4 LEDs
- One LCD with I2C module

## Schematic

![design image](https://github.com/angelina-tsuboi/Arduino_Memory_Game/blob/main/images/schematic.png)

## How It Works

The circuit for this project is straightforward. The digital pins control the LED functions which indicates each step of the game. When the button is clicked, the current is sent through the anode of the LED making it light up. Furthermore the digital pins detect the button input, and runs the corresponding game logic. I also used an I2C LCD with this project. It lists basic game messages in order to make the game more immersive. The main circuits (LED and pushbuttons) are powered by the 3.3V power source from the Arduino, and the LCD is powered by the 5V powersource.

## Prototype

![prototype photo](https://github.com/angelina-tsuboi/Arduino_Memory_Game/blob/main/images/stage1_image.JPG)

## Completed Project

![project photo](https://github.com/angelina-tsuboi/Arduino_Memory_Game/blob/main/images/final.JPG)

## Sources

[Makerguides tutorial](https://www.makerguides.com/character-i2c-lcd-arduino-tutorial/)

