# Square Inch USB Sound Card #

A compact USB audio interface built around the Texas Instruments PCM2706, with two channels of analog audio and I2S out.
The device supports up to 16-bit 48 kHz audio.
Additional details can be found on the [hackaday.io project page](https://hackaday.io/project/8545-square-inch-usb-sound-card).

## The Schematic ##

The schematic is based heavily off of the PCM2706 reference design.
While the schematic does have the HID buttons designed in, the final board does not implement them.

[Schematic PDF](https://github.com/jcreedon/SIUSBSC/raw/master/pcb/pdf/SIUSBSC.pdf)

## The PCB ##

The PCB is a two layer board that measures 1 inch by 1 inch.
It can be ordered via OSH Park using the link below.

**Front**
![PCB Front](https://raw.githubusercontent.com/jcreedon/SIUSBSC/master/images/SIUSBSC-front.png)

**Back**
![PCB Back](https://raw.githubusercontent.com/jcreedon/SIUSBSC/master/images/SIUSBSC-back.png)

https://oshpark.com/shared_projects/LmhMixU9

## The Bill of Materials ##

The passive components are mainly 0603, with a few aluminum caps, the crystal, the main IC, and the USB connector.
An online BOM can be found on Octopart via the link below.

Designator          | Value         | Size
--------------------|---------------|--------------
U1                  | PCM2706       | TQFP32
Y1                  | 12 MHz        | 3.2mm x 2.5mm
P1                  | USB Micro B   | 
C1, C2              | 18 pF C0G     | 0603
C3, C4, C5, C7, C8  | 1 uF X7R      | 0603
C6                  | 10 uF         | 4 mm
C9, C10             | 100 uF        | 5 mm
C11, C12            | 0.022 uF X7R  | 0603
R1                  | 1M            | 0603
R2, R11             | 1K5           | 0603
R3, R4              | 22R           | 0603
R5, R6              | 16R           | 0603
R7, R8, R9, R10     | 3K3           | 0603


https://octopart.com/bom-lookup/FlH2LCsP

## License ##

This project is licesned under the [CERN Open Hardware License 1.2](http://www.ohwr.org/licenses/cern-ohl/v1.2).
