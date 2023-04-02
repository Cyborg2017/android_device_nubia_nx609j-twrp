# android_device_nubia_nx609j
Tree for building TWRP for Nubia Red Magic (Decryption works on Android 11/12.x/13.x ROMs)

## Kernel Sources

https://github.com/nubia-development/android_kernel_nubia_msm8998/tree/lineage-20

## To compile

export ALLOW_MISSING_DEPENDENCIES=true

. build/envsetup.sh && lunch omni_nx609j-eng

mka adbd recoveryimage

## Device specifications

ZTE Nubia Red Magic (codenamed "nx609j") is a high-range smartphone from Nubia.
It was released in April, 2018.

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Quad-core 2.45 GHz Kryo 280 & Quad-core 1.9 GHz Kryo 280
Chipset | Qualcomm MSM8998 Snapdragon 835
GPU     | Adreno 540
Memory  | 6/8 GB RAM
Storage | 64/128 GB
Battery | Li-Po 3800mAh battery
Display | 1080 x 1920 pixels, 6.0 inches
Back camera  | 24 MP, f/1.7, LED flash, HDR, panorama
Front camera |	8 MP, f/2.0
Android Version | 8.1.0

## Device picture

![ZTE Nubia Red Magic](https://fdn2.gsmarena.com/vv/pics/zte/zte-nubia-red-magic-5.jpg "ZTE Nubia Red Magic")
