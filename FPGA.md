# FPGA Programming

Time to dust off my old Terasic DE2-70 board. It features the Altera Cyclone II EP2C70F896C6N FPGA.

![DE2-70](https://github.com/n0123maker/n0123maker.github.io/blob/master/images/de2-70.png)

# Installation

## Quartus II
The latest version of Quartus II which supports the Cyclone II seems to be v13.0.1.232 which can be downloaded from [Download Center for FPGAs](https://fpgasoftware.intel.com/13.0sp1/).

After installation it's time to install the USB-Blaster driver. Use the USB cable to connect the leftmost USB
connector on the DE2-70 board to a USB port on the computer. The correct driver can be found at location ```C:\altera\13.0sp1\quartus\drivers\usb-blaster```.

## Nios II EDS
It seems version v13.0 of Quartus II already includes the Nios II Embedded Design Suite (EDS). So no additional installation is needed.

## University Program Installer
The University Program Installer contains the Monitor Program and computer systems examples. The Monitor Program can be used to compile, assemble, download and debug programs for Altera's Nios II processsor. 

The University Program Installer can be downloaded from [Free Academic Software - University Program Installer](https://www.intel.com/content/www/us/en/programmable/support/training/university/materials-software.html).

Make sure to match the corresponding version of your Quartus II installation, in our case this would be v13.0. You can then click on the EXE item in the displayed table, which links to an installation program called ```altera_upds_setup.exe```.

# Tutorials
Intel provides some nice additional [Tutorials](https://software.intel.com/en-us/fpga-academic/learn/tutorials). At the bottom of the page you can download Archived Versions, in our case this would be v13.1.

# Resources
* [FPGA designs with Verilog](https://verilogguide.readthedocs.io/en/latest)
* [NandLand](https://www.nandland.com)
* [NandLand YouTube](https://www.youtube.com/nandland)
* [Time To Explore](https://timetoexplore.net)
