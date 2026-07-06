# Vendor blobs for Samsung Galaxy Tab A9+ (gta9p) - common

Common vendor proprietary blobs for the Samsung Galaxy Tab A9+ (SM-X216B)
platform, shared across device variants using the SM6375 (Snapdragon 695 5G)
SoC.

## Blob Source

Extracted from Samsung firmware `X216BXXS9DYJ7` (Android 14 / One UI 6.1).

## Contents

- Camera HAL libraries and tuned data
- GPU firmware (Adreno)
- Audio HAL and effects
- Sensor configurations
- DRM/Widevine libraries
- Bluetooth and WiFi firmware
- VINTF manifests
- Audio calibration data (ACDB)

## Usage

This repo is inherited by `android_vendor_samsung_gta9p` via the device vendor
makefile. It should not be used directly.
