# evDash (old enirodashboard)

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
!!! Use it at your own risk !!!
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

- evDash Discord server: https://discord.gg/rfAvH7xzTr
- Project is maintained by EV owners car community

Supported hardware

1. M5STACK CORE1 IOT Development Kit (best option)
2. LILYGO TTGO T4 v1.3 (!!! limited support, no SDcard/GSM/GPS/CAN module)

Working only with electric vehicles
Kia e-NIRO (EV), Hyundai Kona EV, Hyundai Ioniq EV, Kia Niro Phev 8.9kWh
Vgate iCar Pro Bluetooth 4.0 (BLE4) OBD2 adapter is required or CAN (m5 COMMU module).
See Release notes, quick installation via flash tool bellow.

## Required hardware

Board

- M5STACK CORE1 IOT Development Kit(~EUR 35)
  https://rlx.sk/sk/m5stack/7285-esp32-basic-core-iot-development-kit-m5-k001-m5stack.html
- optional M5 COMMU (CAN) module
- optional M5 GPS NEO-M8N (with external atenna)

or

- older device LILYGO TTGO T4 v1.3 (~USD $30) DEPRECATED device
  https://www.banggood.com/LILYGO-TTGO-T-Watcher-BTC-Ticker-ESP32-For-Bitcoin-Price-Program-4M-SPI-Flash-Psram-LCD-Display-Module-p-1345292.html

OBD2 adapter

- For nonstop use we !strongly! recommend to use direct connection to CAN (2 pins on OBD2 connector).
- It's due to security! Anybody can control your car via OBD2 and BT/BLE adapters are not secured well (unlock doors, ACC off/on, etc).
- Supported is only this model... Vgate iCar Pro Bluetooth 4.0 (BLE4) OBD2 (~USD $30). We can add another BLE adapter if you provide 3x UUID (service/notify,read/write)

## Quick installation with ESP32 flash tool

See INSTALLATION.md

## RELEASE NOTES

see. RELEASENOTES.md file

## Installation from sources

See INSTALLATION.md

## Screens and shortcuts

- Middle button - menu
- Left button - toggle screens

Screen list

- no0. blank screen, lcd off
- no1. automatic mode (summary info / speed kmh / charging graph)
- no2. summary info
- no3. speed kmh + kwh/100km
- no4. battery cells + battery module temperatures
- no5. charging graph
- no6. consumption table. Can be used to measure available battery capacity.

![image](https://github.com/nickn17/evDash/blob/master/screenshots/v2.jpg)
![image](https://github.com/nickn17/evDash/blob/master/screenshots/v2_m5charging2.jpg)
