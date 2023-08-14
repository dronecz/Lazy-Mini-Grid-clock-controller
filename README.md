# Lazy Mini Grid clock controller
This repository contains firmwares for the Lazy Mini Grid clock. 

Clock sketch v7 folder contains the original firmware from [parallyze](https://www.instructables.com/member/parallyze/). This firmware may not be up to date with what is on Instructables. 

The LazyMiniGrid Clock 17x5 folder contains edited (original) firmware, which adds WiFiManager for easy WiFi connection setup to use the clock with an NTP server. 

## How to use it?

You can use modified firmware with any ESP32 board, but you have to change/use pins which are defined in this firmware. 

If you use a LazyMiniGrid controller board (from a Czech maker), this board is already uploaded with modified firmware and you should just look for **LazyMiniGrid AP**, connect it to it, and go to http://192.168.4.1 address and set up your WiFi credential there.

