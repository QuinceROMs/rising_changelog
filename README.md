RisingOS Revived - device tree changelog
========================================

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
