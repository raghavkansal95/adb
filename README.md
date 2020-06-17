# adb
use of adb  command in android world

## show only third party apps
adb shell pm list packages -3

## show only third party apps
adb shell pm list packages -3

##Grant all permissions listed in the app manifest
adb install -g test.apk

##record mobile screen via adb
adb shell screenrecord /sdcard/video.mp4 

## Screenshot of mobile save to desktop/laptop via adb
adb exec-out screencap -p > screen.png
