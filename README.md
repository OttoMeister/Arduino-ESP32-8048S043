# ESP32-8048S043C

ESP32-S3 HMI 8M PSRAM 16M Flash 4.3" 800x480 Display with Capacitive touch screen <br>

[Aliexpress 1](https://www.aliexpress.com/item/1005004788147691.html),
[Aliexpress 2](https://www.aliexpress.com/item/1005004788147691.html)


## More infos
[Info 1](https://esp3d.io/esp3d-tft/v1.x/hardware/sunton-43-8048/index.html), 
[Info 2](https://homeding.github.io/boards/esp32s3/panel-8048S043.htm), 
[Info 3](https://wiki.makerfabs.com/Sunton_ESP32_S3_4.3_inch_800x400_IPS_with_Touch.html),
[Info 4](https://github.com/rzeldent/esp32-smartdisplay)



## How to install ARDUINO IDE nightly with on Linux
erase all old traces, then download, install and start it
```
rm -rf ~/Schreibtisch/arduino-ide* ~/.arduinoIDE ~/.arduino15 ~/.config/arduino* ~/.config/Arduino* ~/Arduino* /tmp/.arduino* /tmp/arduino* ~/.cache/arduino-ide-updater
wget https://downloads.arduino.cc/arduino-ide/nightly/arduino-ide_nightly-latest_Linux_64bit.AppImage
mv arduino-ide_nightly-latest_Linux_64bit.AppImage ~/Schreibtisch
chmod u+x ~/Schreibtisch/arduino-ide_nightly-latest_Linux_64bit.AppImage 
~/Schreibtisch/arduino-ide_nightly-latest_Linux_64bit.AppImage & disown
```

## Install Arduino IDE 2.3.0 on Windows 
Download from here:

[https://downloads.arduino.cc/arduino-ide/arduino-ide_2.3.0_Windows_64bit.exe](https://downloads.arduino.cc/arduino-ide/arduino-ide_2.3.2_Windows_64bit.exe)

Start the installer, klick yes to everything.

## Settings in Arduino IDE:<br>
Menü -> File -> Preferences -> Language -> English <br>
Menü -> File -> Preferences -> Show verbose output during compile und upload -> check <br>
Menü -> File -> Preferences -> Compiler warnings -> Default <br>
Menü -> File -> Preferences -> OK <br>
Libary Manager -> TFT_eSPI -> search and install: LovyanGFX by lovyan03 ver 1.1.12 <br>
Libary Manager -> TFT_eSPI -> search and install: NTPClient by F.Weinberg ver 3.2.1 <br>
Libary Manager -> TFT_eSPI -> search and install: HTTPClient by A.McEwen ver 2.2.0 <br>
Libary Manager -> TFT_eSPI -> search and install: ArduinoJson.h by B.Blanchon ver 7.0.4 <br>
Bords Manager -> ESP32 search and install esp32 by Espressif Sytems  <br>
Select Board and Port -> ESP323S Dev Module
-CPU Frequency : “240MHz (WiFi/BT)” <br>
-Core Degug Level : “Verbose” <br>
-Flash Frequency : “80MHz” <br>
-Flash Mode : “QIO” or “DIO” <br>
-Flash Size : “4MB (32Mb)” <br>
-Partition Scheme : “Default 4MB with spiffs (1.2MB APP/1.5MB SPIFFS)” <br>
-PSRAM : “Disabled” <br>
-Upload Speed: “921600”  <br>

## config library:<br>

xxxxxxx <br>
