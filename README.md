USBDM STM32
===========

Personal Port of the USBDM Firmware to run on a Nucleo-144 STM32 development board (specifically the F767ZI).
The code is derived from the Kinetis code the the parent repository, since that is also an ARM platform.

Currently I am using the STM32 HAL functions as opposed to the LL functions. While the LL functions offer better 
better performance, it has less cross-compatability with other STM32 boards. If performance becomes an issue, I will 
switch the necessary portions to LL drivers and update this README. 

Original Readme below
--------------------

BDM firmware for USBDM BDMs

Refer to sourceforge for release files

Release files: http://sourceforge.net/projects/usbdm/files/

Documentation: http://usbdm.sourceforge.net/

The following projects are Codewarrior Eclipse project and should be imported into Codewarrior 10.6.4.

USBDM_JMxx

The project in the following directory is for Codewarrior for HC08 (non-eclipse version).

USBDM_JB16_V4_10

The remaining projects are intended for Eclipse, Kinetis Design Studio or MCUXpresso (all with USBDM plugin)

USBDM_Kinetis etc

