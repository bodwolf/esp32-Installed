# esp32 Installed
# Installing ESP32 Add-on in Arduino IDE

starting this installation procedure, make sure you have the latest version of the Arduino IDE installed in your computer. If you don’t, uninstall it and install it again. Otherwise, it may not work.

Having the latest Arduino IDE software installed from arduino.cc/en/Main/Software, continue with this tutorial.
#Installing ESP32 Add-on in Arduino IDE
To install the ESP32 board in your Arduino IDE, follow these next instructions:

1.In your Arduino IDE, go to File> Preferences

![image](https://user-images.githubusercontent.com/107868423/182033190-fd97c84f-3f7c-40ed-9301-12cf7ceda4ce.png)

2.Enter the following into the “Additional Board Manager URLs” field:
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

![image](https://user-images.githubusercontent.com/107868423/182033229-c4a6c9f5-e8d5-494b-a79e-b07a3d4b9b21.png)

3.Open the Boards Manager. Go to Tools > Board > Boards Manager

![image](https://user-images.githubusercontent.com/107868423/182033240-6b90231f-67d8-4472-8144-081b039af3c3.png)

4.Search for ESP32 and press install button for the “ESP32 by Espressif Systems“:


![image](https://user-images.githubusercontent.com/107868423/182033249-974df01a-ee5f-4b66-86c0-aa7f8e00d235.png)

5.That’s it. It should be installed after a few seconds.


![image](https://user-images.githubusercontent.com/107868423/182033262-c1c8c1ed-e581-4dbb-8409-885631b9541c.png)
![image](https://user-images.githubusercontent.com/107868423/182033271-6ab3b60f-2718-486d-b71e-cf0599143acd.png)

![image](https://user-images.githubusercontent.com/107868423/182033275-dd38475f-e5cb-4f35-934f-58de3e34e1da.png)

6. Open the following example under File > Examples > WiFi (ESP32) > WiFiScan

7. A new sketch opens in your Arduino IDE:

![image](https://user-images.githubusercontent.com/107868423/182033305-512a4996-75b5-4a4a-9619-a0692a80d797.png)


8. Press the ESP32 on-board Enable button and you should see the networks available near your ESP32:


![image](https://user-images.githubusercontent.com/107868423/182033347-3637d239-9ee2-45f7-ba41-5e715262bdc7.png)







