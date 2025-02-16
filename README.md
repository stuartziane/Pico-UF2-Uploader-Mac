# Pico-UF2-Uploader-Mac
Easily upload UF2 files to your Raspberry Pi Pico and other RP2040-based boards

## Tested Boards:

* Raspberry Pi Pico
* Raspberry Pi Pico W
* Arduino RP2040 Connect (Must short REC pin to GND whilst connecting to Mac (with reset pin held down))

## Instructions for use:

No installation needed - Just unzip folder (if not automatically unzipped after downloading) and then you can drag the app into your Applications folder.

1. The Pico MUST be in Mass Storage Mode in order to transfer a UF2 file onto it.  To do this, press and hold the BOOTSEL button and then plug the Pico into your Mac. Then release the BOOTSEL button.
2. If you already have the app open, click on the refresh button at the top right corner.  A green dot indicates that the Pico is detected.  If there is a red dot, disconnect the Pico and then try again.
3. To upload a UF2 file to the Pico board, you must first click on the button to locate the UF2 file.
4. Once the UF2 file has been located, you will be able to see the location of the file in the box.  To use a different UF2 file, just repeat the process.
5. To upload the file to the Pico, click on the button.  If the upload was successful, the Pico will be ejected (don't worry about the message!) and the app will show a confirmation box.

To upload another file, follow the process again to put the Pico in Mass Storage Mode and then click on the refresh button to check that the Pico is detected.

## For Arduino RP2040 Connect:

Arduino RP2040 Connect works, but the process is slightly different.

1. Short the REC pin to GND.
2. Press and hold the RESET button whilst plugging in the board to Mac.
3. When the board has been plugged in, wait a couple of seconds then release the RESET button.
4. The board should appear in Finder, or on the Desktop.  When it does...
5. Remove the short between the REC pin and GND.
6. Proceed as per the steps for other boards above.


## Support

The tool is easy to use, but if you have any problems, please feel free to either add an issue to this repo, or send me an email:

[szianepd@gmail.com](mailto:szianepd@gmail.com)

Enjoy!
