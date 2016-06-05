# Board definitions for 1286
Board definition files for the 1286 version of the Industruino top board

Industruino comes with 2 different microcontrollers:
* 32u4: a standard Arduino of the 'Leonardo' type so you do not need to install any board definition files; in the Arduino IDE go to Tools > Boards and select 'Arduino Leonardo'
* 1286: a non-standard Arduino microcontroller that requires the installation of specific board definition files into your Arduino IDE 

There are a few differences between these 2 microcontrollers in pin use:
* backlight: for the 32u4 on pin D13, and for the 1286 on pin D26
* membrane panel buttons: for the 32u4 on 1 analog pin A5, and for the 1286 on 3 digital pins D23,24,25
 
Detailed pinout maps can be found [here](https://industruino.com/page/techcentre)
