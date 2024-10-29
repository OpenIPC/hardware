![OpenIPC logo](https://openipc.org/assets/openipc-logo-black.svg)

## A Radxa Zero 3W stackable double BL-R8812AF1 board

# Note this board has problems!

## The board is often not recognised by the Radxa on boot and needs re-plugging before it is detected by the Radxa. Sometimes it has this problem then powered by a BEC and not when powered from USB. I think this is an issue with this USB hub chip, and this issue has been reproduced by another user. I will update this page if/when a fix is found.

### The board integrates an SL2.1A USB hub chip which splits a single USB interface into 4 interfaces: two are used by the WiFi modules, and two additional ones are broken out for use with anything else (keyboard for configuration, USB stick, more WiFi dongles etc.).

## HOW TO MAKE
### You can order the PCB by sending the gerber files in the .zip to a PCB manufacturer. I have also included the source Kicad project files if you want to make any modifications.
![double wifi](Photos/doubleWifi.jpg)
![pre-assembled PCB](Photos/preAssembledPCB.jpg)
![lsusb](Photos/lsusb.png)

<p align="center">
<a href="https://opencollective.com/openipc/contribute/backer-14335/checkout" target="_blank"><img src="https://opencollective.com/webpack/donate/button@2x.png?color=blue" width="250" alt="Open Collective donate button"></a>
</p>
