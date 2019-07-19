# Binaries

Firmware for the 3rd Wave Labs Controllino controller comes in the form of a .hex binary file.

## Using This repository
If you are familiar with Github, clone this repository as you regularly would and pull when updates are pushed to this repository to keep everything up to date.

If you are unfamiliar with Github simply click the green "clone or download" at the top right of the file list and download as a zip file.

Extract the zip to a location of your choosing. This folder and its contents will need to be manually removed and replaced upon every firmware update so old files wont be used by mistake.

## Uploading the binary HEX file

Included within this repository is Xloader which is a third party program that is is used to upload binary HEX files to the controller. XLoader can also be downloaded from its source [HERE](http://xloader.russemotto.com/)

Below are the steps to using Xloader:

## Using XLoader
Xloader has 4 main input fields: Hex file, Device, COM port, and Baud rate

![](http://www.hobbytronics.co.uk/image/data/tutorial/arduino_xloader/xloader.jpg)

Plug in the controller to the computer using the usb port on the controller.

Open the *XLoader.exe* within the XLoader folder

1. Set the *Hex file* feild to the location of the provided **.hex** binary
2. Set the *Device* to: **Mega(ATMEGA2560)**
3. Set the *COM port* to the appropriate device. Should be listed in the drop down menu as COM followed by a number. 
4. Set the *Baud Rate* field to: **115200**
5. Click upload
