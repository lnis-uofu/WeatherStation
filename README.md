# WeatherStation
This project is a personal Bluetooth weather station utilizing the ESP32 MCU. The ECE Weather Station collects temperature, humidity, and barometric pressure measurements and pushes the data to your smartphone through the custom app. 

<h2> Download The App <img src="img/uofu_ece.jpg" alt="Thumbnail" width="100" height="100" align="middle"></h2>
The ECE Weather Station App is available through both the Apple Store and Google Play Store. 

### iOS
You can find the direct link to the app [by clicking here.](https://itunes.apple.com/us/app/uofu-ece-weather-station/id1400585038?mt=8) Otherwise search `UofU ECE Weather Station` in the Apple App Store to find the app.


### Android
You can find the direct link to the app [by clicking here.](https://play.google.com/store/apps/details?id=com.UofU_ECE_WeatherStation&hl=en) Otherwise search `UofU ECE Weather Station` in the Google Play Store to find the app.

## The ECE Weather Station
The ECE Weather Station is based around an Espressif ESP32 microcontroller, mounted on an [Adafruit HUZZAH32](https://www.adafruit.com/product/3405) development board. Weather measurement peripherals include the [DHT11](https://www.mouser.com/ds/2/758/DHT11-Technical-Data-Sheet-Translated-Version-1143054.pdf) temperature and humidity sensor, and the [BMP280 barometric](https://www.bosch-sensortec.com/bst/products/all_products/bmp280) pressure sensor. A lithium-ion battery can be connected to the device and charged through the micro-USB terminal. The ESP32 can also be completely reprogrammed through the micro-USB terminal. We give additional details below regarding reprogramming the device.

##Reprogramming the ESP32
The easiest way to reprogram the ESP32 is through the [Arduino IDE.](https://www.arduino.cc/en/Main/Software#download) After you install the IDE, you'll need to install the necessary libararies to build your project for the ESP32. [This tutorial](https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/) takes you through the necessary steps. It is for Windows, but the steps are similar for MacOS and Linux. After installing the libraries you can open the `.ino` file in this repository and edit it how you would like. 

For more detailed control of the build process, you can install the [toolchain and ESP-IDF directly.](https://docs.espressif.com/projects/esp-idf/en/latest/get-started/index.html) 

## About Us
The ECE Weather Station was designed by students from the Laboratory for NanoIntegrated Systems (LNIS) at the University of Utah. 

Feel free to contact Trent Taylor at u0872466@utah.edu or Tom Becnel at thomas.becnel@utah.edu with any questions or comments. 
