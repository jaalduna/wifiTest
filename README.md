Welcome to wifiTest repository!

wifiTest is source code for mcu esp32 to configure it as a signal strengh (RSSI) observer of nearby WiFi AP at 2.4 GHz.

This code was designed in Visual Studio code using the package PlatformIO. 

# Usage instructions
Program your esp32 with this code. Then, within vscode or using your favorite
serial monitor app (termite, coolTerm, screen, etc), read the outputs from the esp32 at 115200 bps.
The code scan for nearby WiFi Signals, gets the RSSI for each one of them and then print results over the serial interface. This process repeats every 1 sec aprox.
