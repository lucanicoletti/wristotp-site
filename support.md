---
title: WristOTP Support
---

# WristOTP Support

Email me at [luca.nicolett@gmail.com](mailto:luca.nicolett@gmail.com). Tell me your phone model and your watch model. You can also [open an issue on GitHub](https://github.com/lucanicoletti/wristotp/issues).

## Common questions

**The phone app says no watch is connected.**

Open Garmin Connect and check your watch is connected there. On iPhone, tap Choose in the watch card and pick your watch. On Android, the phone app uses the watch paired in Garmin Connect.

**The phone app says WristOTP is missing on the watch.**

Build the watch app and copy it into `GARMIN/APPS` ([how](https://github.com/lucanicoletti/wristotp#watch)), then open it once on your watch.

**How many accounts fit on the watch?**

Up to 50.

**Which accounts are sent?**

The ones at the top of the list. (Drag them to change the order, or tap A–Z.) Names longer than 64 characters are shortened. The glance shows the first one too. (While the PIN is on, it shows the issuer name but hides the code.)

**The watch rejected the sync: "open WristOTP on the watch and enter the PIN first".**

With a PIN set, turning the PIN off or sending fewer accounts needs a recent unlock. Open WristOTP on your watch, enter the PIN, then send again within 2 minutes.

**Some accounts are "not supported".**

WristOTP supports time-based codes (TOTP) with SHA-1 and SHA-256. SHA-512, MD5 and counter-based (HOTP) accounts can't be shown on your watch.

**I forgot my watch PIN.**

From the 5th wrong attempt your watch makes you wait (30 s, doubling each time, up to 8 min). After 10 wrong attempts it wipes all accounts. Send them again from the phone app and choose a new PIN.

