# xiaomi mi5 kernel for learning linux kernel

[Original repo](https://github.com/LineageOS/android_kernel_xiaomi_msm8996)

Also add kernelsu support

```bash
# Compilation
make ARCH=arm64 vendor/xiaomi/mi8996_defconfig
make -j8 ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- CROSS_COMPILE_ARM32=arm-none-eabi-
# Then use Anykernel3 to pack flashing image
```

After granting permission in kernelsu manager, we can use `adb root` to get root access
