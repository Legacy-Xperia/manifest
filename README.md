manifest
========
Before Compile use patches in Device Tree

patch -p1 < device/sony/device/patches/framework_av.patch
patch -p1 < device/sony/device/patches/framework_native.patch
patch -p1 < device/sony/device/patches/framework_base.patch
patch -p1 < device/sony/device/patches/hardware_libhardware.patch
patch -p1 < device/sony/device/patches/hardware_libhardware_legacy.patch
patch -p1 < device/sony/device/patches/system_core.patch
patch -p1 < device/sony/device/patches/bionic.patch
patch -p1 < device/sony/device/patches/external_bluetooth_bluedroid.patch
