# Overview
 The purpose of this project is to enable the LENOVO ThinkPad T430 series notebook to use MacOS.
- Note: This series of laptops has a WiFi whitelist and cannot be replaced with any network card.
- [Release](https://github.com/hqnicolas/T430-Thinkpad-OpenCore/releases/tag/T430-Opencore)
# This Commit
What I add to the original Release:
- |Network card | Bcm94360HMB/Bcm943224HMP|
- |Network card | intel Centrino Original 7620 / 6205 / 6210|
- |Bluetooth | Bcm20702A0|
- |External Docking Station Software Support|
- |Dual Boot fix|

# Applicable system
- MacOS Ventura13. x
- MacOS Monterey 12. x
- MacOS Big Sur 11. x
- MacOS Catalina 10.15. x
- MacOS Mojave 10.14. x
- MacOS High Sierra 10.13.6 (17G65)
# Applicable models
- T430/T430s
# What is needed
- Downloaded MacOS image (supports image installation for macOS High Sierra (10.13.6) - macOS MacOS Ventura)
- 16GB USB drive
# BIOS Ensure Settings
- ACHI mode
- CSM Off
- TV-D off
- Upgrade BIOS version (do not operate Xiaobai)
- Enable UEFI mode
- Shield independent graphics card
- Disable secure startup.
# Functionality for normal operation
- UEFI starts through Clover/OC
- Support OTA upgrade to the latest system for any version
- Built in keyboard
- Native USB 3.0/USB 2.0
- AppleHDA native audio, including headphones
- Integrated camera
- Power management
- Battery status
- Backlight control
- Nuclear display driver
- Wired Ethernet card
- Mac App Store Apple ID is running normally
- CPU frequency conversion
- Sleep wake-up (mouse, keyboard, and power button wake-up are all normal)
- Wireless network (replace Bcm943602cdp)
- Bluetooth (replace Bcm943602cdp)
- Touchpad (some gesture support)
- IMessage/FaceTime

# About feeding
The author is still a struggling student on campus, and updates may be slower. However, I try my best and may not be able to meet the needs of many people, but I will try my best to do a good job
##Acknowledgement
Thank you [apple]（ https://www.apple.com）
Thank you [acidanthera]（ https://github.com/acidanthera ）The vast majority of core drivers provided
Thank you [dortania]（ https://github.com/dortania ）Provided patch driver for HD4000
Thank you [daliansky]（ https://github.com/daliansky ）OC title provided
Thank you [OpenCore Part Library]（ https://ocbook.tlhub.cn/?q= ）OpenCore components provided
Thank you（ https://github.com/zhen-zen ）Yoga SMC provided
Thank you [zxystd]（ https://github.com/OpenIntelWireless ）Intel WI-FI driver provided
