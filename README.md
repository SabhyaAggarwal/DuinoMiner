# DuinoMiner
This is a PCB made by me that is used for mining DuinoCoin, a type of cryptocurrency with not too much value. You can mine it with normal small consumer-available chips as well...

## Hardware
### Schematic

<img width="826" height="467" alt="Screenshot 2026-07-07 at 3 27 21 PM" src="https://github.com/user-attachments/assets/efb17c9e-23a0-4325-9e06-c6591e83ecdd" />

### PCB Design

<img width="561" height="593" alt="Screenshot 2026-07-07 at 3 27 56 PM" src="https://github.com/user-attachments/assets/4ebd80c9-bc98-47b7-a267-053e589fd3b7" />

### 3D render

<img width="1064" height="616" alt="image (12)" src="https://github.com/user-attachments/assets/84e80e1d-eeee-4860-8396-c5d12656a7f1" />


## BOM
|Name                  |Description                                                                                         |Quantity|Total Cost|Link                                                                                                         |Distributor     |
|----------------------|----------------------------------------------------------------------------------------------------|--------|----------|-------------------------------------------------------------------------------------------------------------|----------------|
|PCB                   |Main PCB(cost includes payment fees)                                                                |1       |$1.36     |https://aivon.com/                                                                                           |AIVON           |
|Wemos D1 Mini         |Main chip for Network connection(cost includes tax)                                                 |1       |$2.17     |https://quartzcomponents.com/products/wemos-d1-mini-esp8266-nodemcu-mini-d1-module?variant=39261072392376    |quartz component|
|Pi Pico               |The 3 Picos which actually mine(tax inclusive and shipping grouped with wemos)                      |3       |$12.23    |https://quartzcomponents.com/products/raspberry-pi-pico?variant=37945289801912                               |quartz component|
|0.96 inch oled display|OLED display                                                                                        |1       |$1.71     |https://quartzcomponents.com/collections/all/products/oled-display-0-96-inch-i2c-interface-4-pin-blue-ssd1306|quartz component|
|40 pin male header    |Header pins for the pi picos as they are not included(tax inclusive and shipping grouped with wemos)|3       |$0.26     |https://quartzcomponents.com/products/40-pin-break-away-headers-straight-male-headers?variant=31898065633415 |quartz component|


## Notes

For setup there is a great onboarding setup shown on the OLED screen and you can manage it using the web UI and all. The firmware is taken from https://github.com/JK-Rolling/DuinoI2C_ESP
