## TWRP for InFocus Vision 3 (philip)

Minimal device tree for building TWRP for philip

## procedure

(1) repo init --depth=1 -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-7.1

(2) repo sync -j16

(3) git clone https://github.com/00p513-dev/twrp_device_infocus_philip device/infocus/philip

(4) . build/envsetup.sh

(5) lunch omni_philip-eng

(6) make recoveryimage -j8
