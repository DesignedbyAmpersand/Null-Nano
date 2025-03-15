Wrigley is an ESP32 powered gaming handheld that uses retro-go from ducalex.
It measures 100x35x15mm and has roughly 3 hours of battery life.

This is not a beginner project.

These files are provided for free and with no guarantees.
These files are provided for personal use and not for resale purposes.

You will need the SD card skeleton files from here: https://1drv.ms/u/c/66cb300826c22fa3/Efv0uc86yZ5Hv4n83UHvBrcBqe-35vOahgP56gvEnUvf-g?e=ifL2Ww
You will also need the ESP32 flash download tool: https://1drv.ms/u/c/66cb300826c22fa3/EbNSYC88lTlOn8YUjpB1ucgBnk_qerDjQeKToj3xAFp3lw?e=woOXxG

Do not use a USB C to USB C cable to charge Wrigley, it does not have anything connected to CC1 or CC2.

Do not use Wrigley whilst charging, it does not have the necessary components to make this safe.

Use Kapton tape, do not use regular tape or masking tape.

You will need the latest version of the ESP flash tool to flash Wrigley. Make sure you have installed the necessary drivers for your USB to UART adapter. The "options" button acts as a Boot button, so hold down options when you turn it on/provide power to enter bootloader mode for flashing.

The R3 resistor determines the charge rate. 1000/X = Y
e.g. for a 5.6K resistor the equation is 1000/5.6 = 179mA
If you use a different battery, you will need to change this resistor value.

The green LED goes on the right and the red LED on the left.

Trim the plastic pins off the bottom of the micro SD card socket with a scalpel or flush cutters (the holes needed would've interfered with the DPad).

The PCB needs to be 1.6mm thick. I order through JLCPCB and have "JLCJLCJLCJLC" written on the board so that the production number can be hidden below the ESP32.

The screws used are 8mm M2 self-tapping cap head



Resources used:

Odroid GO schematic
https://github.com/hardkernel/ODROID-GO/blob/master/Documents/ODROID-GO_REV0.1_20180518.pdf

Screen config file from this project
https://circuitdigest.com/microcontroller-projects/esp32-based-retro-game-console

Amp circuit based on Adafruit Class D amplifier
https://learn.adafruit.com/adafruit-pam8302-mono-2-5w-class-d-audio-amplifier

Charge circuit based on Adafruit MicroLiPo
https://learn.adafruit.com/adafruit-microlipo-and-minilipo-battery-chargers

Retro-go software
https://github.com/ducalex/retro-go

All graphics designed by me


Let me know if you make one, have fun!
Ampersand
