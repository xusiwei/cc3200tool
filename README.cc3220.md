## Usage

1. Use Uniflash create a Flash Image for CC3220
2. run the following command under this directroy:
```sh
sudo python cc3200tool/cc.py -p /dev/ttyUSB0 --reset prompt write_flash ~/.SLImageCreator/projects/cc3220sf-launchxl/sl_image/Output/Programming.ucf
```
