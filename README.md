# CDCReset
Python script to reset a CDC device.

This script is especially handy when using an Arduino Duo (or similar) device. It will reset the board and start the bootloader, allowing you to upload a new program. 

This may not work for all Cortex M0+ boards; only those that are Arduino Duo compatible.

## Requirements
You'll need pySerial: `sudo python -m pip install pyserial`

## Usage
`python cdc_reset.py <PATH_TO_TTY>`

Replace <PATH_TO_TTY> with the location of your CDC device, such as /dev/ttyACM0.


