# SailfishOS 3.x for Redmi 4X (santoni)

<a name="no-apk"></a>**THIS IS NOT ANDROID.** If you're looking for Android ROMs, this ROM is **NOT** for you.
(oh and forgot to mention that by not Android, it means no APK support.)

## What is SailfishOS?
> SailfishOS is a general purpose Linux distribution used commonly as a mobile operating system combining the Linux kernel for a particular hardware platform, the open-source Mer core stack of middleware, a proprietary UI contributed by Jolla or an open source UI, and other third-party components.

## Disclaimer:
```
/*
 * Your warranty is now void.
 *
 * I am not responsible for bricked devices, dead SD cards,
 * thermonuclear war, or you getting fired because the alarm app failed. Please
 * do some research if you have any concerns about features included in this ROM
 * before flashing it! YOU are choosing to make these modifications, and if
 * you point the finger at me for messing up your device, I will laugh at you.
 */
 ```
 
 ## What's not working?
 - Fingerprint (until SailfishOS 3.1)
 - [Android APK](#no-apk)
 - VoLTE (my sim card isn't registered to use VoLTE)
 - Missing codecs, meaning that videos won't play, except videos from the browser.
 - It's possible that there are other stuffs I've missed out.
 
 ## What's working?
 - Everything else.
 
 ## Why is the Jolla Store empty?
 - Since our device is not registered by Jolla yet, use [Storeman](#storeman) to get apps.
 
 ## Installation
1. Download [LOS 14.1](https://download.lineageos.org/santoni)
2. Download [SailfishOS](https://github.com/sailfish-santoni/projectmanagement/releases)
3. **Use [official TWRP image](https://dl.twrp.me/santoni). Other recoveries such as OrangeFox has reported to have OOM enabled, which will kill the unpacking process on low memory.**
4. Reboot to TWRP
5. Make sure /data and /cache are in **ext4** format. **(anything that is not ext4 will not be supported.)**
6. Wipe Dalvik, Data, Cache, System, Vendor
7. Copy both files to your phone
8. Flash LOS 14.1
9. Flash SailfishOS
10. Reboot!
 
 ## <a name="storeman"></a>Installing Storeman:
- [Download Storeman](https://openrepos.net/sites/default/files/packages/6416/harbour-storeman-0.1.5-1.armv7hl.rpm)
- Enable Untrusted Software in Settings.
- Navigate to your file (via Settings > Storage), open and install it.
- Download Apps!

## Reporting Bugs

If you faced a **bug** or something is not working at all, please open an [issue here](https://github.com/sailfish-santoni/projectmanagement/issues). Follow the instructions provided there.
**Give as much detail as possible.**

## Source code
SailfishOS UI and system apps are proprietary.

As for device tree, kernel, droid configurations, check [here](https://github.com/sailfish-santoni)

## Special thanks
- [bitrvmpd](https://github.com/bitrvmpd) - For the old Sailfish 2.x port which is no longer maintained.
- [mal](https://github.com/mlehtima) - For helping me most parts (modem, bluetooth, wifi,..)
- [Asriel](https://github.com/asriel-danctnix) - For getting lipstick (UI) to show up.
- [deathmist](https://github.com/JamiKettunen) - For such a hacky script for calls.
