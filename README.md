# Aerial Workbench APK releases

Signed desktop APK updates for the owner's TCL TV. This repository contains APK distributions, update metadata, checksums, release notes and license notices only. No firmware, Root modules, private signing keys or device data.

Aerial Workbench is based on Aerial TV 1.41 (MIT), by pengchujin / upstream contributors: https://github.com/pengchujin/aerial-tv. It uses the upstream Kotlin / Compose interface and OFL fonts.

Only install an APK matching the installed package and signature. Firmware-specific Root brightness and remote-key features require separate setup; this public APK repository does not perform firmware flashing.

Source fork and modifications: https://github.com/huhao0208/aerial-workbench (workbench branch). The fixed wb.11 firmware-builder source snapshot is tagged source-wb11. The latest source candidate is not automatically promoted to this signed stable APK channel.

Full third-party runtime notices accompany the APK release as AERIAL-THIRD-PARTY-NOTICES.txt. The root MIT notice does not replace font, data, image/icon or library licenses.

Stable channel: **1.41-wb.15 / versionCode 59**. Foreground Root picture connection reuse and resume preparation; opted-in TCL screensavers use SDR to preserve picture settings, including saved Dolby choices. The APKs keep the existing signing identity. Firmware inputs remain separately pinned. See the release notes and SHA256SUMS.
