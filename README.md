# Redmi Note 8 Android System Modification & Mobile Security Learning Lab

**Author:** Karan Bhaveshbhai Vaya  
**Device:** Xiaomi Redmi Note 8 (`ginkgo`)  
**Current OS:** LineageOS 23.2 / Android 16  
**Current build:** `20260812-NIGHTLY-ginkgo`  
**Project period:** April–September 2026 (user-stated; current state documented in August 2026)  
**Status:** Project work completed; repository documentation is being formalized.

## Overview

This project documents a personal, hands-on study of Android system modification using a Redmi Note 8.

The project began with the original MIUI 12.5 installation and progressed through bootloader unlocking, custom recovery work, a Pixel 3.6 experiment, troubleshooting of a bootloop and later a recovery loop, and finally installation of LineageOS 23.2 based on Android 16.

The project also became a Linux learning platform through Termux. The original goal included investigating whether Kali NetHunter could be deployed on the device. Research indicated that the required support was not available for this device/kernel combination, so the project shifted toward Android system learning, Linux fundamentals, and future mobile-security study.

> **Important:** This repository distinguishes firsthand observations from verified technical facts. Unknown historical details are marked as unknown instead of being guessed.

## Project progression

```text
MIUI 12.5
    │
    ▼
Bootloader Unlock
    │
    ▼
OrangeFox R10.0
    │
    ▼
Pixel 3.6 experiment
    │
    ├──► Bootloop
    │      │
    │      ▼
    │   Troubleshooting
    │      │
    │      ▼
    │   Successful boot
    │
    ▼
Pixel testing
    │
    ├──► Severe battery drain observed
    │
    ▼
Termux / Linux learning
    │
    ▼
Recovery loop
    │
    ▼
Fastboot
    │
    ▼
OrangeFox R12.0
    │
    ▼
LineageOS 23.2
Android 16
    │
    ▼
Current learning platform
```

## Objectives

- Understand Android operating-system modification at a practical level.
- Learn bootloader unlocking, ADB, Fastboot, and custom recovery workflows.
- Learn about custom ROM installation and recovery from system failures.
- Explore Linux fundamentals through Termux.
- Investigate Kali NetHunter compatibility.
- Build a documented foundation for future Android/mobile-security research.

## Current status

The current phone is running LineageOS 23.2 / Android 16. Current screenshots show the device, Android version, LineageOS version/build, storage, security-update information, battery information, and system status.

Major functions tested and reported working include Wi-Fi, Bluetooth, camera, flashlight, speaker, microphone, USB, charging, touchscreen, display, sensors, performance, storage, Termux/Linux commands, ADB, and Fastboot.

GPS, fingerprint, mobile/SIM network, and other unlisted functions were not tested as part of this project record.

## Cybersecurity scope

This is **not presented as a penetration-testing project**.

The current cybersecurity relevance comes from learning:

- Android system architecture and modification
- Bootloader/recovery/firmware concepts
- Linux fundamentals
- ADB/Fastboot
- Device and ROM compatibility
- System recovery and troubleshooting
- Future mobile-security research

Dedicated cybersecurity tooling was not installed during the documented project phase.

## Evidence policy

Historical screenshots and personal notes from the original experiments are not available. The historical timeline is therefore documented from:

1. the author's recollection,
2. the original project report,
3. current device screenshots,
4. and external technical documentation where applicable.

No backdated screenshots or fabricated historical notes are used.

## Repository map

- `docs/` — technical and project documentation
- `evidence/` — evidence inventory and sanitized evidence
- `research/` — learning/research notes
- `reports/` — formal project reports
- `CHANGELOG.md` — project/documentation history
- `CITATION.cff` — citation metadata
- `SECURITY.md` — security/reporting scope
- `LICENSE` — repository licensing terms

## Safety and ethics

All device modification described here was performed on the author's own device. Do not modify or test devices without authorization. Android flashing can cause data loss, boot failure, or device damage.

## Author

**Karan Bhaveshbhai Vaya**

This repository is a personal educational project documenting hands-on Android and Linux learning.
