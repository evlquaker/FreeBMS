"# FreeBMS" 


FreeBMS was inspired by diyBMS v4 by Stuart Pittaway and the diyBMS v4 Leaf circuit board by George Boudreau. This is still in VERY EARLY DEVELOPMENT and is completely UNTESTED. I highly recommend no one attempt to build this unless they have the skills and knowledge to do so safely. 
I am posting this here in the hopes of finding other interested people, especially ones that may be able to help with the project.
I am building this project because I could not find another BMS that is both affordable and supports 96 cells in series. This BMS will have a limit of 256 cells (if it is powered separately). Like the diyBMS by Stuart Pittaway this BMS will be decentralized and have optically isolated modules on each cell connected via serial. 
I will be using George Boudreau’s Leaf boards and designing my own controller. This should also be hardware compatible with the diyBMS v4 boards. I will also be writing my own serial protocol as the diyBMS v4 protocol has a limit of (I believe) 48 cells. The software will not be compatible with the diyBMS boards and all boards will need to be programed especially for this.


The FreeBMS will have the following features:
*Open Source
*ESP32-PICO-D4 Microcontroller
*2 optically isolated serial channels + a third serial channel for programming
*Programming port for USB UART programmer. MUST HAVE DTR and RTS pins available. Has transistors for auto programming.
*CAN bus (not currently isolated, but I have plans to make it be)
*100V to 500VDC input supply (could be increased as the regulator supports 1000v, but the other components currently don’t)
*4 relays, 3 that output 12VDC from the onboard regulator and 1 that is SPDT general purpose


I am having JLCpcb assemble all of the surface mount components and I am hand soldering the through hole ones. It is very inexpensive to have them do this. I am sure there are other good board shops too.
The board was made in EasyEDA and I have posted the EasyEDA files. I will likely post other files in the future. Please let me know if you are interested in this project or would like to contribute. Suggestions on the board design and software development would be greatly appreciated.
