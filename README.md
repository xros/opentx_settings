OpenTX Settings
===============

[OpenTX](http://www.open-tx.org) is an opensource radio control system.

It provides radio transmitter firmware, and radio transmitter PC software for simulation.


Here I added some templates for OpenTX settings.

My radio is a Fr-sky Taranis X9D Plus. Until now it has been flash with firmware OpenTX 2.1.8 . 

I added a splash templates. 

It looks like this:

![mylogo](mylogoxcf_20160809.png)

Every one can modify this image **mylogoxcf_20160809.xcf** using the opensource image editor [gimp](http://www.gimp.org).


Getting into bootloader
-----------------------

![intobootloader](get_into_bootloader.png)

Use taranis as a USB storage drive and save the firmware and settings on it.

Attention: name of firmware can't not be too long. I used "opentx-en-2.1.8.bin" to replace its original name "opentx-taranisplus-timer3-lua-mixersmon-internalppm-en-2.1.8.bin".

Then restart and get into bootloader interface again. 

Flash firmware
--------------

In bootloader interface,

Choose "Write Firmware".

Optionally choose "Restore EEPROM".

Or we can do all these things in PC software [Companion](http://www.open-tx.org/downloads)

Flash bootloader
----------------

Copy `bootloader/213.bin` to SD card. Hold key **Menu** to get into Setup Menu then change tap **Page** to navigate into File Manager on Taranis. Select the file `213.bin` then flash bootloader.
