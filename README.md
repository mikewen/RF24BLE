# nrf_BLE_beacon
RF24BLE is the library that makes an nrf24L01+ chip (1$) into a BLE advertising beacon and can be used for LOW payload
advertising like sensor data etc.

# Pre-Requisites
- this library works on top of the RF24 library by TMRh20 (https://github.com/TMRh20/RF24)
- tested using Arduino v1.6.5(windows) and Arduino v1.0.5 (ubuntu)
- tested with "nrf Master Control Panel" app on google play store on android  LINK: https://play.google.com/store/apps/details?id=no.nordicsemi.android.mcp&hl=en

# Instructions
- Connect the nrf24L01+ to the SPI pins of your specific arduino.
Choose and change the Chip enable (CE) and Chip select (CS) in the code corresponding to your connections

- clone the repo and paste the RF24BLE folder in the folder "libraries" in the sketchbook area. e.g "Arduino/libraries/RF24BLE"


- open the arduino ide and choose an example from the file->examples menu and upload any example


- Download and install the app "nrf Master control" app from the google play store on an android device.

- open the app and click on scan and the advertised packet should be shown in the list in the app

# NOTES
- this is not tested on IPHONE if it works please notify :-)
