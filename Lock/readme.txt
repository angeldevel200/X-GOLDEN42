Code to Reset Pattern:
ADB SHELL RM /DATA/SYSTEM/GESTURE.KEY

Code To Reset PIN Password:
ADB SHELL RM /DATA/SYSTEM/PASSWORD.KEY

adb shell
cd /data/system
rm gesture.key
exit
adb reboot
