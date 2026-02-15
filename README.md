# CNC-Pen-Plotter-Using-Old-printer-parts
🚀 Overview
This is a high-precision, Arduino-based CNC Pen Plotter designed for automated sketching, calligraphy, and technical drawing. Unlike basic DIY kits, this machine is fully calibrated for fine-line art and complex cross-hatching portraits.

Perfect for:

Engineering & Diploma Final Year Projects

Architects & Designers (Floor plans/Blueprints)

Artists (Generative art & Mandalas)

Signature Automation
1. Design & G-Code Generation
Inkscape (Vector Editor): The main software to create your art.

https://inkscape.org/release/inkscape-0.92.5/

4xiDraw Extension (Plotter Control): This is a specialized extension for Inkscape that converts your drawings into plotter-friendly G-code.

https://github.com/bullestock/4xidraw.git

Note: Place the contents into your Inkscape extensions folder.

2. Machine Control (The "Driver")
Universal Gcode Sender (UGS): This software sends the instructions from your computer to the Arduino.

https://winder.github.io/ugs_website/download/

Tip: Use the "Platform" version for a better visual interface.

3. Firmware & Arduino Tools
GRBL Firmware (v1.1): The "brain" that runs on your Arduino Uno.

https://github.com/gnea/grbl

Arduino IDE: Needed if you ever want to re-flash or customize the firmware.

https://www.arduino.cc/en/software/
