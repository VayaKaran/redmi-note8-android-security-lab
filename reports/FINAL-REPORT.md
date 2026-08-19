# Redmi Note 8 Android System Modification & Mobile Security Learning Lab

**Author:** Karan Bhaveshbhai Vaya  
**Project period:** April–September 2026 (author-stated)  
**Current state documented:** August 2026

## Abstract

This project documents a hands-on Android system modification and Linux-learning project performed on a Redmi Note 8. The device originally ran MIUI 12.5. The project involved bootloader unlocking, ADB/Fastboot use, custom recovery installation, a Pixel 3.6 experiment, recovery from a bootloop, later recovery-loop troubleshooting, and installation of LineageOS 23.2 based on Android 16.

The project also investigated the feasibility of Kali NetHunter. The author concluded that the required support was not available for the device/kernel combination and therefore did not successfully deploy NetHunter. The current device is instead being used for Android system learning and Linux/Termux practice.

## 1. Background

The project was started to understand Android operating-system behavior, custom ROMs, Linux fundamentals, and the relationship between system-level knowledge and cybersecurity.

## 2. Initial objective

The major objectives were:

- understand Android system modification;
- learn bootloader unlocking;
- learn custom recovery and ROM flashing;
- learn ADB/Fastboot;
- explore Linux through Termux;
- investigate Kali NetHunter compatibility;
- prepare a foundation for future cybersecurity learning.

## 3. Device and workstation

### Device

- Redmi Note 8
- Codename: `ginkgo`
- Original OS: MIUI 12.5
- Current OS: LineageOS 23.2
- Current Android: 16
- Current build: `20260812-NIGHTLY-ginkgo`

### Workstation

- HP Notebook
- Windows 8.1
- 4 GB RAM
- Intel Core i3-U series processor

### Tools

- Xiaomi Mi Unlock Tool
- ADB
- Fastboot
- Command Prompt
- OrangeFox Recovery

## 4. Project history

The device was factory-reset and connected to a Xiaomi account before bootloader unlocking.

OrangeFox R10.0 was then used as the early custom recovery.

The author attempted a Pixel 3.6 installation using OrangeFox, a Pixel recovery image, and a Pixel 3.6 ZIP.

The device entered a bootloop. The author spent approximately four days troubleshooting and eventually achieved a successful Pixel 3.6 boot.

During Pixel testing, rapid battery drain was observed. The author considers the age and physical history of the device possible contributors, but the exact cause was not experimentally established.

The author then began learning Linux/Ubuntu-style commands through Termux. The first attempt was unsuccessful; a later attempt was successful.

The device later entered a recovery loop. It repeatedly returned to recovery after power cycling. The author entered Fastboot, flashed OrangeFox R12.0, and later installed LineageOS 23.2 / Android 16.

## 5. Current system

Current screenshots document:

- Android 16
- LineageOS 23.2
- Build `20260812-NIGHTLY-ginkgo`
- August 2026 security update
- 128 GB storage
- current battery information

## 6. Functional testing

The author reports successful testing of:

- Wi-Fi
- Bluetooth
- Camera
- Flashlight
- Speaker
- Microphone
- USB
- Charging
- Touchscreen
- Display
- Sensors
- Battery
- Performance
- Storage
- Termux/Linux commands
- ADB
- Fastboot

GPS, fingerprint, mobile/SIM network, and other unlisted functions were not tested.

## 7. Kali NetHunter investigation

Kali NetHunter was an original target. Device/kernel compatibility research indicated that the required support was not available for the Redmi Note 8 setup used in this project.

NetHunter was therefore not successfully deployed.

This is recorded as a negative compatibility result rather than a failed cybersecurity experiment.

## 8. Cybersecurity relevance

The current project provides foundational knowledge relevant to mobile security:

- Android system layers
- bootloader/recovery concepts
- ADB/Fastboot
- Linux command-line fundamentals
- system troubleshooting
- ROM/device compatibility

However, the project does not claim completed mobile penetration testing or dedicated Android security-tool deployment.

## 9. Evidence limitations

No historical screenshots or personal notes were preserved from the early experiments. Historical stages are therefore based on the author's recollection and the original project report.

Current device-state evidence is directly available through screenshots supplied during documentation.

No backdated evidence has been created.

## 10. Lessons learned

The project demonstrated that system modification is not only about successful installation. Failure recovery, compatibility checking, understanding boot/recovery states, and careful troubleshooting are equally important.

The project also showed the importance of documentation. Because the original experiments were not recorded with systematic screenshots, notes, commands, dates, and hashes, some historical technical details cannot now be verified.

Future experiments will be documented contemporaneously.

## 11. Future work

Potential next steps include:

- deeper Linux fundamentals
- Android internals
- ADB security
- Android permissions
- SELinux concepts
- verified boot
- Android application security
- controlled mobile-security labs
- structured research notes

## 12. Conclusion

The project successfully transformed a Redmi Note 8 from its original MIUI 12.5 environment through multiple Android system experiments and troubleshooting events into a current LineageOS 23.2 / Android 16 learning platform.

The most significant outcome is not the ROM itself. It is the practical experience gained in system modification, recovery, Linux learning, compatibility research, and failure analysis.

**Author:** Karan Bhaveshbhai Vaya
