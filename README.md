# Woah there!
If you are not familiar with adb or fastboot, I don't recommend you attempt this guide.\
I was a noob once too, and I accidentally hard bricked my first device attempting to run a custom ROM on it.

## Installing HyperOS
1. Boot into TWRP via `fastboot boot (drag in twrp img)`
2. Press the "Wipe" button, then press the "Format Data" button at the bottom of your screen
3. Type "yes" to confirm the format, then go back and press "Advanced Wipe" and wipe Data and Internal Storage
4. Press the home button, press "Advanced > ADB Sideload"
5. Assuming hyperos.zip is in your platform-tools folder, open a cmd window in the platform-tools folder and type `adb sideload <drag in HyperOS zip from file explorer>`. The process will begin.
