___________________________________________________________________________________________________________

                      Linaro GCC 5.2 Toolchain for generic Cortex-A cpu - README
___________________________________________________________________________________________________________


This repo contains latest Linaro GCC 5.2 toolchain built for generic Cortex-A cpu, this is suitable for
Android kernel development and includes also latest Linaro GDB.

The toolchain has been built using latest official crosstool-NG toolchain builder and is configured with
generic ARM settings (inspired by latest Linaro builds) for target architecture and target optimizations:
    CT_ARCH_ARCH="armv7-a"
    CT_ARCH_CPU=""
    CT_ARCH_TUNE="cortex-a9"
    CT_ARCH_FPU="vfpv3-d16"
    CT_ARCH_FLOAT_SOFTFP=y
    CT_ARCH_FLOAT="softfp"
    CT_ARCH_ARM_MODE="thumb"
    CT_ARCH_ARM_MODE_THUMB=y

You can find other toolchain builds on my GitHub and also the zipped versions on my Mediafire, please take
a look at the original thread on XDA Developers forum at this link:
       http://forum.xda-developers.com/showthread.php?t=2098133
