# Unofficial-Ubuntu-Touch-For-MI-A1
This is the unofficial port of ubuntu touch for the mi a1 that i made

what works:-
Rotation

Wifi

Video playback

Charging indicator

Audio from external speaker / jack

Bluetooth scanning

Flashlight (amber led only)

Sound recorder (microphone)

Brightness (manual control)



Instructions

Get boot.img,vendor.img and system.img from the releases tab


Get the latest TWRP with Treble Manager for tissot here:
https://forum.xda-developers.com/t/recovery-treble-twrp-3-3-1-0-with-tissot-manager.3976117/


Format Data in Wipe option and factory reset(to remove Stock encryption), then Reboot into Recovery again.
In TWRP, go to Advanced > Treble Manager and repartition the device by following the wizard.


Flash Ubuntu in fastboot mode:

fastboot flash vendor vendor.img

fastboot flash boot boot.img

fastboot flash system system.img

and then reboot to system and enjoy


What doesn't work / Issues

Camera

GPS

Fingerprint
