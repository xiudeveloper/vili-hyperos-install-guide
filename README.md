# Woah there!
If you are not familiar with adb or fastboot, I don't recommend you attempt this guide.\
I was a noob once too, and I accidentally hard bricked my first device attempting to run a custom ROM on it.

## Installing HyperOS
1. Boot into TWRP via `fastboot boot (drag in twrp img)`
2. Press the "Wipe" button, then press the "Format Data" button at the bottom of your screen
3. Type "yes" to confirm the format
4. Press the home button, connect your phone to your computer with a USB cable, then press "Mount" > "Mount USB Storage"
5. Transfer the ROM file into your internal storage
6. Once done, press the "Unmount" button and then press the home button once again. At this point, it is safe to disconnect the USB cable.
7. Press "Install", find the ROM file, select it, then swipe the slider at the bottom screen. Installation will begin.\

**By the way, if you want TWRP to function as the recovery permanently on the device, go to Advanced and scroll down, then use "Flash Current TWRP"**
