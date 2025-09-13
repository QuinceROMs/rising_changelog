RisingOS Revived - device tree changelog
========================================

2025.09.13
----------
- improved visual smoothness by adjusting frame timing, reducing stuttering in games
- enabled composition caching for better UI performance and lower power consumption
- enabled smooth motion for smoother display
- improved frame update responsiveness and display performance
- optimized the dext2oat application compilation process during system configuration
- improved Bluetooth connectivity for multiple simultaneous BLE devices
- Dolby: reverted switched layout to Material Expressive
- minor sepolicy fixes.


2025.09.09
----------
- fixes in sensor support
- imported sensor configuration from OOS 12.1 H.41
- fixes in the sepolicy rules
- fixes in LiveDisplay
- changes to the Oplus charger interface (AIDL)
- fixed the Vendor ID list to work correctly with QPST on Windows
- Dolby: fixed QS tile support and switched layout to Material Expressive
- imported Polish carrier configurations from Xiaomi 15 Ultra HyperOS 2.0.204.0.VOAEUXM
- few other minor changes.


2025.08.28
----------
- fix alarm & notification sound not playing while using BT earphones
- enable ADPF CPU hints for improved UI performance and responsiveness
- make adaptive brightness more stable in dim environment
- improve vibration and haptics
- import alert slider support from YAAP's hardware/oplus
- kernel defconfig: add conservative and ondemand governors
- switch to reference fastboot AIDL service
- add oplus performance HAL service
- add many new rules and sepolicy fixes
- few other minor changes.


2025.08.22
----------
- dolby: Imported Simplified Chinese translation
- vintf: Update oplus charging service.


2025.08.21
----------
+ UDFPS:
  - Enabled additional icons and animations
  - oplus: udfps: Use qti_kernel_headers
  - overlay: Enabled config_supportScreenOffUdfps
- sepolicy: qti: Label /dev/oplus_chg & update rules for charger AIDL
- oplus: Reverted the usage of vendor_sysfs_soc_sensitive.


2025.08.20
----------
- Migrated to AIDL LiveDisplay HAL
- livedisplay: Added IAdaptiveBacklight support
- overlay: qssi: Removed deprecated telephony overlays
- sepolicy: qti: Given rw perms to /proc/qcom_flash for camera hal
- kernel-headers: Added PANEL_IOCTL_{GET,SET}_CABC_STATUS.


2025.08.15
----------
- Added ColumbusService (Quick Tap)
- Set Ortus Launcher as default
- Adjust status bar paddings
- vintf: Bump oplus charging service
- Switched Adreno driver to v786
- sepolicy: qti: Address more rules.
