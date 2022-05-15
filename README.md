# Blinking-LED-using-Rpi4
Using python code to blink an OLED connected to Raspberry pi4.

## Task number: 09

## Task name: Control LED with Raspberry pi using python.

## Reference 
https://www.circuitbasics.com/how-to-control-led-using-raspberry-pi-and-python/

To set up: https://www.circuitbasics.com/how-to-install-the-raspberry-pi-operating-system/

## Components used
MicroSD card, Raspberry pi board, HDMI cable, USB keyboard, mouse, power supply for board.

## Connections
Insert a microSD card to the Raspberry pi board, connect it to monitor using HDMI cable. Also connect the mouse and keyboard.
Connect the cathode(shorter leg) of LED to GPIO pin 14 of board through a current limiting resistor. Connect the anode(longer leg) of the LED to pin below that. 
Next, once open the raspberry pi terminal and type nano led.py to create a python file. This creates and opens the file in nano text editor, write the python code on the file. Once done, save and close the file.
Open Raspberry pi terminal, to run the program type sudo python led.py, and press enter.

## Theory
To write python code to control an LED with Raspberry pi, first import RPI.GPIO library to manage GPIO pins. And also import time module to manage delay using sleep function.
To avoid all the warnings, set it to false, set pin 14 as output. Once code enters the while loop, first LED is set to high, it prints LED id ON on the terminal, after delay of 1 second, it is set to low, again delay of 1 second. This while loop continues till we stop it with a command or disconnect the circuit.

## Code
https://github.com/meghana-23-7/Blinking-LED-using-Rpi4/blob/main/blinkLed.py

##  Problems faced

Firstly, there were errors due to indentation and syntax. Next there was no response in the LED, as it was connected wrongly. 
Some ways to avoid problems:
Indentation: we all know python works only with proper indentation, while writing code on nano file, proper indentation should be provided.
Make sure to provide proper power supply.
Make sure to check that all the connections are proper.

## Output

LED blinks with a delay of 1 second. 




