# Magisk Module: "ActionLauncher as System app"

*This is a module for the Magisk framework. If you don't know what Magisk is or does, please stop now and head over to the Magisk thread(s) on XDA:*

- [Magisk Forum on XDA developers](http://forum.xda-developers.com/apps/magisk)

### Description

This module is very simple: it does nothing else than placing the apk file of the launcher [Action Launcher 3](https://play.google.com/store/apps/details?id=com.actionlauncher.playstore) under `/system/app/ActionLauncher/ActionLauncher.apk`

The apk file contained in this repo is the one downloaded from PlayStore (currently in version 3.11.4)

### Future Updates
Even if Action Launcher brings out future updates, you should be able to update it normally via Play Store as any other pre-installed system app which is on Play Store.


### Why Action Launcher as system app?
The reason why somebody wants to have Action Launcher 3 installed as a sytem app is the "**Google Now Integration**" feature of Action Launcher. This allows seamless integration of the Google Now screen (when you swipe in from the left on the first screen).

But this only works when the launcher is installed as a system app.

### Why Magisk?
While it's perfectly ok to simply move the Action Launcher 3 APK file to the `/system` partition via recovery or using a root file-explorer, this will modify the `/system` partition. This may have impacts on future system updates of your phone or other negative effects.

However, [Magisk](http://forum.xda-developers.com/apps/magisk) is a framework that allows developers to make all system modifications *system-less* (without any physical modification of the `/system` partition) and makes them more hassle-free. Read up the Magisk threads on XDA-Developers for more information about Magisk.

