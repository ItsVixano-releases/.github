# Giovanni Unofficial LineageOS

## Changes from LineageOS sources

- Signature spoofing (For MicroG)
- Mulch WebView support
- DT2S on home screen
- Reworked recent apps page
- Defaults to the high aspect ratio resolution on old apps
- Remove old app target SDK dialog
- Remove Android build number from QS footer
- Misc debugging / tracing disabled
- Misc backend optimizations
- Delete option on screen recorder notification
- Using `HEVC` encoder for screen recording
- Enabled some [Android Go optimisations](https://github.com/ItsVixano/android_vendor_extra/blob/master/config/go.mk) (+ LKMD Optimizations for legacy SOCs)
- Disabled ripple animation on legacy SOCs
- `adb shell` now uses bash shell instead + `neofetch` for flexing you are using Android
- Wireless `adb` port set to `5555` already
- Proper [MiuiCamera](https://github.com/ItsVixano-releases/LineageOS_extra/releases/tag/xiaomi_firmwares) support on `lisa` and `miatoll`, bundled as a Magisk module

## Notes

> Both Unofficial and Official builds for `lisa` and `miatoll` (that are published in this org) are maintained by me

> Something might be missing from older builds

## Credits

- [Android Open Source Project](https://android.googlesource.com/)
- [LineageOS](https://github.com/LineageOS)
- [LMODroid](https://github.com/LMODroid)
- [crDroid Android](https://github.com/crdroidandroid)
- [ProtonAOSP](https://github.com/ProtonAOSP)
- [PixelExperience](https://github.com/PixelExperience)
- [random-aosp-stuff](https://github.com/random-aosp-stuff)
- [Alexander Winkowski](https://github.com/dereference23/)
- A lot of friends who helped me :D
