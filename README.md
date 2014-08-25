AndroidWinXPBootAnimation
=========

Windows XP boot animation on Android

Version
----
1.0
>Support resolution
> * 480 x 800

>Tested on device
> * GT-I9100 (7-AUG-2012)


Installation (ADB, Require root)
--------------

```sh
1. Copy bootanimation.zip into Android
    > adb push /your_system_path/bootanimation.zip /system/media/bootanimation.zip.new
2. Go /system/media/
    > adb shell
    > su
    > cd /system/media
3. Backup bootanimation.zip
    > mv bootanimation.zip bootanimation.zip.bak
4. Rename new bootanimation.zip.new to bootanimation.zip
    > mv bootanimation.zip.new bootanimation.zip
5. make sure the bootanimation.zip have proper permission (-rw-r--r--)
    > chmod 644 bootanimation.zip
6. Reboot your devices

```