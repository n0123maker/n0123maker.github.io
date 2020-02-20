# FPGA Programming

Time to dust off my old Terasic DE2-70 board. It features the Altera Cyclone II EP2C70F896C6N FPGA.

![DE2-70](https://github.com/n0123maker/n0123maker.github.io/blob/master/images/de2-70.png)

# Installation

## Quartus II
The latest version of Quartus II which supports the Cyclone II seems to be v13.0.1.232 which can be downloaded from [Download Center for FPGAs](https://fpgasoftware.intel.com/13.0sp1/).

After installation it's time to install the USB-Blaster driver. Use the USB cable to connect the leftmost USB
connector on the DE2-70 board to a USB port on the computer. The correct driver can be found at location ```C:\altera\13.0sp1\quartus\drivers\usb-blaster```

## Nios II EDS
It seems version v13.0 of Quartus II already includes the Nios II Embedded Design Suite (EDS). So no additional installation is needed.

## University Program Installer
The University Program Installer contains the Monitor Program and computer systems examples. The Monitor Program can be used to compile, assemble, download and debug programs for Altera's Nios II processsor. 

The University Program Installer can be downloaded from [Free Academic Software - University Program Installer](https://www.intel.com/content/www/us/en/programmable/support/training/university/materials-software.html).

Make sure to match the corresponding version of your Quartus II installation, in our case this would be v13.0. You can then click on the EXE item in the displayed table, which links to an installation program called ```altera_upds_setup.exe```

The default installation path will be: ```C:\altera\13.0sp1\University_Program```

# Tutorials
Intel provides some nice additional [Tutorials](https://software.intel.com/en-us/fpga-academic/learn/tutorials). At the bottom of the page you can download Archived Versions, in our case this would be v13.1.

# Altera Monitor Program Tutorial
After installation of the University Program Installer this tutorial can be found locally at ```C:\altera\13.0sp1\University_Program\Monitor_Program\tutorial\Altera_Monitor_Program.pdf```

After following the steps outlined in this tutorial, I arrive at section 3.2 Compiling and Loading the Program. When selecting Actions - Compile from the menu I see the following error displayed in the Info & Errors window:
```
      1 [main] bash 13584 find_fast_cwd: WARNING: Couldn't compute FAST_CWD pointer.  Please report this problem to
the public mailing list cygwin@cygwin.com
Compilation stopped.
```
I seems this involves an error due to an older version of Cygwin installed by the toolchain, described here: https://cygwin.com/faq.html#faq.using.fixing-find_fast_cwd-warnings.

So let's download a recent [Cygwin Installer](https://cygwin.com/setup-x86_64.exe). I just go with all default settings while installing.

# Resources
* [FPGA designs with Verilog](https://verilogguide.readthedocs.io/en/latest)
* [NandLand](https://www.nandland.com)
* [NandLand YouTube](https://www.youtube.com/nandland)
* [Time To Explore](https://timetoexplore.net)
