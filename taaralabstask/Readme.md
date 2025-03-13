Support for TaaraLabs RS-485+CAN bus+DCDC Converter
===================================================
This folder adds [TaaraLabs RS-485+CAN bus+DCDC Converter for Wemos D1 Mini32](https://taaralabs.eu/cw1) board definitions to [ESP32-NMEA2000](https://github.com/wellenvogel/esp32-nmea2000) project.
To compile the image put this folder under the "lib" directory. The name of this folder should correspond to the header file inside it so it is best not to rename them.

There are also board definitions for Lolin C3 Mini (ESP32C3) board, however
the pinout for serial rx/tx connections does not match. One way to use this
board with Lolin C3 Mini is to omit RX/TX pins and use bodge wires to route
them to defalt RX/TX pins. Also with this configuration USB port could not be used neither for debugging or NMEA data.
