manifest
========
Before Compile use patches in Device Tree

    patch -p1 < device/sony/device_name/patches/framework_av.patch
    patch -p1 < device/sony/device_name/patches/framework_native.patch
    patch -p1 < device/sony/device_name/patches/framework_base.patch
    patch -p1 < device/sony/device_name/patches/hardware_libhardware.patch
    patch -p1 < device/sony/device_name/patches/hardware_libhardware_legacy.patch
    patch -p1 < device/sony/device_name/patches/system_core.patch
    patch -p1 < device/sony/device_name/patches/bionic.patch
    patch -p1 < device/sony/device_name/patches/external_bluetooth_bluedroid.patch
