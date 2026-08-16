07 — Failure Analysis

Failure 1 — Pixel bootloop


Symptom

The phone would begin booting, power off/restart, and attempt to boot again. It could become stuck around the boot logo/boot animation.

Context

The author was relatively new to Android system modification at the time.

Response

The author spent approximately four days checking and troubleshooting the device.

Outcome

Pixel 3.6 eventually booted successfully.

Root cause

Not established.

The final documentation does not assign a technical root cause without evidence.

Failure 2 — Severe battery drain


Symptom

The phone's battery drained very quickly during Pixel testing.

Context

The phone is an older device and has a history of significant physical incidents, including a reported water exposure and a large drop.

Outcome

The device remained operational, but battery performance was poor.

Root cause

Not experimentally established.

Battery age/degradation is a plausible contributing factor based on the author's observation, but it is not presented as a proven cause.

Failure 3 — Recovery loop


Symptom

The phone repeatedly entered recovery after being powered off and switched on.

Response

Entered Fastboot.
Flashed the newer OrangeFox R12.0 recovery.
Later installed LineageOS 23.2 / Android 16.
Outcome

The phone reached the current LineageOS installation.

Root cause

Not established.

Engineering lesson

The most valuable learning outcome from these failures was not simply successful flashing. It was learning to diagnose system state, access recovery/bootloader environments, and recover from failed modifications.
