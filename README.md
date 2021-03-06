rpi_kit
=======

Resources for the IET/ExploreSTEM roving Raspberry Pi kits.

You can always get the latest version of these resources from:
https://github.com/explorestem/rpi_kit

(over on the right, click on Download ZIP)

If you are using one of our pre-loaded SD cards, please follow these
steps to update your SD card to the latest resources:

open an LXTerminal window

cd rpi_kit

./update

This will download any updates to the resource packs, which
includes PDFs of workbooks, code, and all other required files.

If you need to completely reconstruct the card, please note all cards are
currently loaded with this image from the Raspberry Pi Foundation:

2016-02-09-raspbian-jessie.img

You can get downloads and install instructions from here:

https://www.raspberrypi.org/downloads/raspbian/

Archived versions of the raspian images are here:

http://downloads.raspberrypi.org/raspbian/images/

So, the one we currently have installed on all cards is this one:

http://downloads.raspberrypi.org/raspbian/images/raspbian-2016-02-09/

Once you have downloaded that, follow the setup guide on the downloads page
to install it. Then boot the Pi connected to the internet.

Open an LXTerminal window and type:

git clone https://github.com/ExploreSTEM/rpi_kit

When it has downloaded...

```
cd rpi_kit
./update
sudo cp config/cmdline.txt /boot/cmdline.txt
sudo cp config/config.txt /boot/config.txt
sudo reboot
```

Then go into MENU/PREFERENCES/RASPBERRY PI CONFIG

Press EXPAND FILE SYSTEM
Follow the messages to reboot.

When you have finished, shut down the pi with the shutdown button.

ExploreSTEM
June 2016


