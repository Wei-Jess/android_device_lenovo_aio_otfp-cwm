# android_device_lenovo_aio_otfp-cwm
Build CWM Recovery V6.0.5.1 for Lenovo K50-t5（K3Note）

======================================================

source build/envsetup.sh

make -j4 otatools

lunch cm_aio_otfp-userdebug

make -j4 recoveryimage

======================================================
