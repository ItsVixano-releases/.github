# Differences between official and unofficial builds

> Both unofficial and official builds for `lisa` are maintained by me 

> Something might be missing from older builds

- Signature spoofing (For MicroG)
- [ih8sn](http://github.com/itsvixano/ih8sn) shipped by default
- DT2S on home screen
- Reworked recents
- Defaults to the high aspect ratio resolution on old apps
- Delete option on screen recorder notification
- Enabled some [Android Go optimisations flags](https://github.com/ItsVixano/android_vendor_extra/blob/master/config/go.mk) (+ LKMD Optimizations for msm8953)
- Disabled ripple animation on msm8953
- `adb shell` now uses bash shell instead + `neofetch` for flexing you are using Android
- Proper [MiuiCamera](https://github.com/ItsVixano-releases/LineageOS_extra/releases/tag/xiaomi_firmwares) support on `lisa`, bundled as a Magisk module
