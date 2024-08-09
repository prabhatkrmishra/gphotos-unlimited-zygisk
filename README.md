# Google Photos unlimited backup module
Adds Photos features and unlimited original backup

Current version : **1.1-stable**


### [Переключиться на русский язык](https://gitlab.com/cuynu/gphotos-unlimited-zygisk/-/wikis/RU)

### [Chuyển ngôn ngữ Tiếng Việt](https://gitlab.com/cuynu/gphotos-unlimited-zygisk/-/wikis/VI)

# Introduction 
Based from Pixelify GitHub. This module will spoof your device info to Pixel XL on Google apps and Google Photos to get unlimited backup storage at original quality !

# Warning !
Module will only works with Zygisk, it will not works with Riru, Shamiko, etc !!

Some modules could break and prevent this module from running, if module does not work, try disable some modules and see.

# Usage 
Download module from [release page](https://gitlab.com/cuynu/gphotos-unlimited-zygisk/-/releases), enable Zygisk then install with Magisk v24.3+ and reboot. 

For KernelSU/APatch users, **DON'T use ZygiskNext 1.0.0+** !. instead, use ReZygisk : [GH Actions](https://github.com/PerformanC/ReZygisk/actions) (select most recent workflows, scroll down and press download button, you might need GitHub account to make Download button appears.)
- Tested with : `Magisk v25.2+` `Magisk Delta` `KernelSU` `APatch`

# Known issues 
- **Some Xiaomi devices with MIUI 14 when this module is active, its will cause Bootloop with SystemUI crash exception**
- When use with `Magisk-GApps` module, it will conflict and cause lose the ability to backup unlimited at original quality (Still able to backup unlimited at storage saver quality)

# Tested devices
- Sony Xperia XZ2/XZ2 Compact/XZ2 Premium (Stock/AOSP)
- Sony Xperia XZ3 (Stock/AOSP)
- Realme C3/C11/C55 (Stock/AOSP)
- Xiaomi Redmi Note 11/Redmi K20 Pro/Redmi Note 7/Redmi Note 4X (AOSP)
- Google Pixel 2/3/4XL/6A (Stock)
- Nothing Phone (1) with Nothing OS 2.5.1 CBT
- Masstel_X9 (Stock/AOSP)
- LG G7 ThinQ (Stock/AOSP)
- LG G8, G8x ThinQ (Stock/AOSP)
- LG V40, V50, V50s ThinQ (Stock/AOSP)
- Lenovo Legion Y70 (AOSP)
- Tecno Pova 2 (AOSP)
- Xiaomi Qin F21 Pro (AOSP)

# Build zygisk binary
`git clone https://gitlab.com/cuynu/gphotos-unlimited-zygisk.git`

Import folder zygisk_build to Android Studio or Gradle and build then copy compiled zygisk library to zygisk folder (not zygisk_build)
