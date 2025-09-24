# REF1266-Datel-N64-Cheat-Development-System
Everything necessary to produce the Datel N64 Cheat Development System

This device is explained in some detail [here](https://www.nesworld.com/n64-dateltrainercart.php).

Brought back from the edge of extinction, this is the predecessor to the N64 Gameshark Pro's Code Generator. This device is used to hack codes for the N64 in concert with the [Datel PC Comms ISA Card](https://github.com/RWeick/REF1190-Datel-PC-Comms-Link-ISA-Card). The firmwares listed show the compatible games it can hack codes for. I have not yet tested if they are compatible with other games as well. The firmware can be flashed to the device by writing it directly to the eeproms prior to soldering them down or via the Sanni Cartridge Reader's Flash Gameshark function. Once a firmware is written, the firmwares can be swapped using the Sharklink software in the PC Comms Link repository.

As I have not ever seen one of these myself in person, the dimensions of the PCB may be slighly off from the original. However, the schematic and pcb trace connections are 100% the same as the original as verified by testing the device. This was possible due to the extensive reverse engineering I've already done on the N64 Gameshark. All necessary parts can be harvested from any N64 Gameshark or Gameshark Pro, with the exception of the parallel port which is a horizontal mounted male port. Happy making.

PCB Thickness: 1.2 mm

![image](https://github.com/RWeick/REF1266-Datel-N64-Cheat-Development-System/blob/main/REF1266.png)
