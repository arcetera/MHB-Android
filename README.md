# MHB-Android
This is Minimal Hosts Blocker, the popular iOS adblocker, for Android.

# Version
Current version is 0.1 (initial release), based off version 7.0 for iOS.

# Disclaimer
Neither I, nor ReddestDream, are responsible for any failures caused by this. Neither of us are responsible if your internet breaks and you have to reflash your ROM, your phone suddenly dies, your router explodes, you get fired because the alarm app failed, or if this application causes thermonuclear war.

# Prerequisites
You need:
* An Android device (of course), running Android 4.1 or newer. If it is lower, AdAway cannot be installed. Jump to Manual Installation.
* Root, and a ROM that allows writing to /system. If you cannot write to /system, check [here](http://forum.xda-developers.com/showthread.php?t=2327934) or just flash a custom ROM.
* AdAway, preferably installed through F-Droid for instant updates. F-Droid is available [here](http://f-droid.org) and AdAway's APK is available [here](https://f-droid.org/repository/browse/?fdid=org.adaway). Not required for manual installation.
* A working internet connection.
* For my server to be up. My server is literally an old laptop in my boyfriend's room. It could be down occasionally. This will only limit installation; It won't break your connection.

# Installation
First off, install AdAway.
Tap the menu button and tap "Hosts Sources". Deselect every option.
Tap the plus button and add the source http://arcetera.party/hosts.txt
Apply (or reapply, if not already applied) AdAway.
Enjoy.

# Manual Installation
Download http://arcetera.party/hosts.txt and copy it to your device.
Copy and paste the contents into /etc/hosts.
Enjoy.
