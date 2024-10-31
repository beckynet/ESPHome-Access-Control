# ESPHome-Access-Control

Project to Use a Wiegand Keypad and RFID 125Khz Reader to control my Alarmo on Home Assistant.

## Introduction

I've been interested in home automation for almost a decade. I've been using OpenHab for a long time.
Then I switched to Home Assistant and discovered a more complete and, above all, much more integrated world.
ESPhome greatly facilitates the development of electronic projects.
For this project, I needed an interface to connect and disconnect Alarmo

## Destination of this project

Project to Use a Wiegand RFID and Keypad to control my Alarmo under Home Assistant.

## Material and knowledge needed

### 1. Material

Wifi Shield : WEMOS D1 Mini (Pro)<BR>
Power Supply : Hi-Link HLK-5M12 AC-DC 220V to 5V Mini Power Supply Module<BR>
Fuse : 0.25 Amp<BR>
Stabilizer : L7805CV<BR>
Condensator : 47µF 25v, 47µF 16v<BR>
Resistor :  220 Ohm<BR>
LED: 5mm
RGB Led: W2812B
Speaker
PCB screw terminal

### 2. Knowledge

ESPHome language [Here](https://esphome.io/)<BR>
Wemos Initialisation and Flashing [Here](https://web.esphome.io/)<BR>
Home Assistant [Here](https://www.home-assistant.io/)<BR> 
ESPhome Integration. [Here](https://www.home-assistant.io/integrations/esphome)<BR>

## Sub Folder Content

ESPhome : Code to flash your Wemos<BR>
Fritzing : Download Fritzing [Here](http://fritzing.org/download/) to view connecting schema.<BR>
Gerber : If you want to make a beautifull PCB. I'm not sponsorized but [this one](https://aisler.net) is cheap.
HomeAssistant : Automation<BR>

## Wiegand Keypad and RFID used

![alt text](https://raw.githubusercontent.com/beckynet/ESPHome-Access-Control/master/Pictures/Wiegand_S20_ID.png)

## PCB View Real Size 110 x 70 mm

![alt text](https://raw.githubusercontent.com/beckynet/ESPHome-Access-Control/master/Pictures/CI-Finish.png)

## Fritzing View

<b style='color:red'>Warning ! Use a HLK-5M12 it is 12V and 5 Watts</b>

