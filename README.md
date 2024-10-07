# Dolby Atmos ZTE A2019 Pro Magisk Module

## DISCLAIMER
- Dolby apps and blobs are owned by Dolby™.
- The MIT license specified here is for the Magisk Module only, not for Dolby apps and blobs.

## Descriptions
- Equalizer sound effect ported from ZTE A2019 Pro (P845A02) and integrated as a Magisk Module for all supported and rooted devices with Magisk
- Global type sound effect
- Conflicted with `vendor.dolby.hardware.dms@2.0-service`

## Sources
- https://dumps.tadiphone.dev/dumps/zte/p845a02 sdm845-user-9-PKQ1.181105.001-559-release-keys
- Dolby Atmos RC4 & RC1 debug 2.2b Magisk Module by @guitardedhero
- system_32: https://dumps.tadiphone.dev/dumps/lenovo/7305i full_mt8321_GO-user-9-PPR1.180610.011-18-release-keys
- system_support: CrDroid ROM Android 13
- libmagiskpolicy.so: Kitsune Mask R65C33E4F

## Screenshots
- https://t.me/androidryukimodsdiscussions/66074

## Requirements
- ARM64 or ARM architecture
- Android 9 (SDK 28) and up
- Magisk or KernelSU installed (Recommended to use Magisk Delta/Kitsune Mask for systemless early init mount manifest.xml if your ROM is Read-Only https://t.me/androidryukimodsdiscussions/100091)

## WARNING!!!
- Possibility of bootloop or even softbrick or a service failure on Read-Only ROM if you don't use Magisk Delta/Kitsune Mask.

## Installation Guide & Download Link
- Recommended to use Magisk Delta/Kitsune Mask https://t.me/androidryukimodsdiscussions/100091
- Remove any other else Dolby Magisk module with different name (no need to remove if it's the same name)
- Reboot
- If you have Dolby in-built in your ROM, then you need to activate data.cleanup=1 at the first time install (READ Optionals bellow!)
- Install this module https://www.pling.com/p/1531390/ via Magisk app or KernelSU app or Recovery if Magisk installed
- Install AML Magisk Module https://t.me/androidryukimodsdiscussions/29836 only if using any other else audio mod module
- If you are using KernelSU, you need to disable Unmount Modules by Default in KernelSU app settings
- Reboot
- If you are using KernelSU, you need to allow superuser list manually all package name listed in package.txt (and your home launcher app also) (enable show system apps) and reboot afterwards
- If you are using SUList, you need to allow list manually your home launcher app (enable show system apps) and reboot afterwards
- If you have sensors issue (fingerprint, proximity, gyroscope, etc), then READ Optionals bellow!

## Optionals
- https://t.me/ryukinotes/8
- Global: https://t.me/androidryukimodsdiscussions/60861
- Stream: https://t.me/androidryukimodsdiscussions/26764

## Troubleshootings
- https://t.me/ryukinotes/10
- https://t.me/ryukinotes/11
- Global: https://t.me/androidryukimodsdiscussions/29836

## Support & Bug Report
- https://t.me/androidryukimodsdiscussions/2618

## Credits and Contributors
- Lennon
- @HuskyDG
- https://t.me/viperatmos
- https://t.me/androidryukimodsdiscussions
- @HELLBOY017
- You can contribute ideas about this Magisk Module here: https://t.me/androidappsportdevelopment

## Sponsors
- https://t.me/ryukinotes/25


