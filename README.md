# ender5-klipped
Klipper configuration for an Ender 5 Pro, with modifications listed below. 

I have uploaded this information to help others, as the documentation on getting a working configuration is somewhat lacking. To install the Manta E3EZ board, you will need to expand the cutout on the side of the Ender 5's power supply/control box to allow access to the ethernet port, USB jacks, and HDMI display.  I am using the stock 24V power supply, but needed to move it over slightly for the Manta E3EZ board to fit.  After installation, you will need to follow the instructions in the Manta E3EZ manual to create the sd card image, compile klipper, and install klipper on the MCUs.  After that is done, copy the printer.cfg configuration file over. 

Documentation for configuring the Manta E3EZ is at https://github.com/bigtreetech/Manta-E3EZ.  Firmware for the CB1 can be downloaded from https://github.com/bigtreetech/CB1/releases.  After installation, update all software, but DO NOT force an update of the Linux kernel, which causes the device to no longer connect to the network.

This page contains affiliate links. As an Amazon Associate, I earn from qualifying purchases. This means I may receive a commission if you click on a link and make a purchase, at no extra cost to you.

This Ender 5 was upgraded with the following components:
* BIGTREETECH Manta E3EZ V1.0 for Ender 3 https://amzn.to/43G87Zd
* CB1 RPI equivalent https://amzn.to/4qxLqjE 
* CB1 Heatsink https://amzn.to/4qxLqjE 
* TMC5160 Motor Controllers https://amzn.to/4qxLqjE
* BIQU H2 V2S extruder w/Generic V6 hotend https://amzn.to/47FE2dI
* 60W heater cartridge https://amzn.to/4hAXNaz
* Creality CR Touch Auto Bed Level https://amzn.to/4qBlWSE
* BIGTREETECH EZ31865 https://amzn.to/47gMT6t
* PT1000 probe for extruder https://amzn.to/47gvACB
* Small HDMI/USB touch screen for local status and control https://amzn.to/4oIPIDd 
* 24V 5015 Part Cooling fan https://amzn.to/4hyyNRz
* BIGTREETECH SFS V2.0 Smart Filament Runout Sensor https://amzn.to/49pvOIT
* 3D Printed BIQU H2 Mount for the Ender 5 https://www.thingiverse.com/thing:4889163
* 3D Printed Part Cooling Fan Duct https://www.thingiverse.com/thing:5101234

You will need these items to complete process:
* Crimping Tool Connector Kit with Ribbon Wire https://amzn.to/49sYIb6

I plan on adding these parts, but have not yet: 
* BIGTREETECH UPS 24V V1.0 Resume Printing While Power Off Module Sensor https://amzn.to/3X0iUd0 

Consumables and replacement parts that fit the BIQU H2 V2S, if needed:
* Nozzles https://amzn.to/4ogOBLj 
* Bimetal Heatbreak https://amzn.to/4ojwaWe
* Copper Heater Block https://amzn.to/4ogOBLj


