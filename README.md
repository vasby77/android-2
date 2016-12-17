CyanogenMod
===========
Getting Started (-jКоличество потоков)
---------------
repo init -u git://github.com/ZIM555/android.git -b cm-11.0
repo sync -j25 
. build/envsetup.sh
lunch
make otapackage -j2
