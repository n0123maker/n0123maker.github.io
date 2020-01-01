# Visual Studio Code for Arduino

First install:
* Visual Studio Code: https://code.visualstudio.com/
* The Arduino IDE: https://www.arduino.cc/en/main/software

Install the Arduino Extension:  
In Visual Studio Code go to Manage - Extensions (shortcut: Ctrl+Shift+X) and install the Arduino Extension from Microsoft.

Select Programmer, Board and Serial Port then click the Upload button.

I use the following settings for my boards but it depends on the manufacturer which settings you will need to use.

## Arduino Uno
Board: Arduino/Genuino Uno

Programmer: AVR ISP

## Arduino Pro Mini
Connected via FTDI Programmer board  
Board: Arduino Pro or Pro Mini (Arduino AVR Boards)  
Processor: ATmega328P (5V, 16MHz)  

Programmer: AVR ISP

## Arduino Nano
Seems this one is broken.

## WeMos Lolin32 OLED
Board: WEMOS LOLIN32 (esp32)  
Flash Frequency: 80MHz  
Partition Scheme: Default  
Upload Speed: 921600  

Programmer: AVR ISP
