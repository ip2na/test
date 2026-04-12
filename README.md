# Anya Kernel

Custom kernel for Android GKI 5.10.x devices with KernelSU support.

## Features

- KernelSU integrated
- SUSFS integrated
- Built with Greenforce Clang, LLVM Slim, Google AOSP Clang, and Zyc Clang
- AnyKernel3 flashable zip

## Requirements

- Device running GKI kernel `5.10.x`
- Unlocked bootloader
- Custom recovery (TWRP / OrangeFox)

## Installation

1. Download the latest zip from [Releases](../../releases)
2. Boot into recovery
3. Flash the zip
4. Reboot

## Source

- Kernel base: `android12-5.10-lts` (AOSP/Common Kernel)
- This repository contains patches and modifications only

## Notes

Flashing a custom kernel may void your warranty. Backup your data before proceeding.

## Credits

- [KernelSU-Next](https://github.com/pershoot/KernelSU-Next) by pershoot
- [SUSFS4KSU](https://gitlab.com/simonpunk/susfs4ksu/-/tree/gki-android12-5.10-dev) by simonpunk
- [AnyKernel3](https://github.com/osm0sis/AnyKernel3) by osm0sis
- [Greenforce Clang](https://github.com/greenforce-project/clang-llvm) by greenforce-project
- [Zyc Clang](https://github.com/ZyCromerZ/Clang) by ZyCromerZ
- [LLVM Slim](https://github.com/llvm/llvm-project) by LLVM
- [Google AOSP Clang](https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86/) by Google

## Disclaimer

This project is provided as-is without any warranty.
Flashing custom kernels may void your warranty.
You are responsible for any damage to your device.
