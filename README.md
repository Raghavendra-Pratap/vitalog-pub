# Vitalog

Vitalog is a private record for a family’s lab results, visits, medicines, and reminders. It lives on the phone or computer you install it on. There is no Vitalog account, and the health record is not uploaded to a Vitalog server.

A lab value is compared with the low and high figures printed on that report. The flag says high, low, or in range. That flag is a label for your own tracking. It is not a diagnosis, a risk score, or treatment advice, and it does not replace a clinician.

Published by BSOC.  
Website: [vitalog.cc](https://vitalog.cc/)  
Privacy: [vitalog.cc/privacy](https://vitalog.cc/privacy)  
Questions: [outreach@bsoc.space](mailto:outreach@bsoc.space)

## Who it is for

An adult keeping records for themselves, or for people in the family they look after. It is for someone who wants the history in one place and does not want that history stored on a company server.

A profile can be a child only when the adult has the authority local law requires.

## What you keep

Each person has a profile. You switch between people without mixing their results.

For labs, you open a panel — a lipid panel, a blood count, thyroid, or another panel the report uses — and enter each value with the range printed on that sheet. Later results for the same test sit against that range, so a change over months is visible without re-reading old paper.

You can also save visits, the doctors you see, a medicine list, and reminders. A report photo or PDF stays with the person it belongs to.

## Reading a report

You can type a panel in, or start from a photo or a PDF. Vitalog reads the text on the device and proposes matches. Nothing from that file is stored until you save. Check the values and the ranges first. A wrong range makes a wrong flag.

The catalogue of common tests, and the list of medicine names, can be refreshed from vitalog.cc. Those are published reference lists. They are not this person’s results.

## Lock, backup, and a device you are leaving

Settings can require a PIN before the record opens. Leaving the app locks it. Biometrics are optional, and only after a PIN exists. The PIN remains the way back in if biometrics fail. The biometric template stays with the operating system.

An encrypted backup is a file you save and keep. Keep the recovery key with that file. Vitalog cannot reconstruct the key later. Restore reads the file you choose back onto a device.

Wipe removes the record on this device. It does not delete a backup you copied to another disk, a USB drive, or a cloud folder of your own. Delete that copy yourself. Uninstalling the app removes the local data, subject to the operating system, and still leaves any copy you saved elsewhere.

You can also export a readable copy for your own files. Sharing that file with another app is your choice. Vitalog does not send it.

## What may leave the device

The health record stays put. These are the exceptions, and each one is something you start:

| You do this | What happens |
|-------------|--------------|
| Refresh the test catalogue or medicine names | The app downloads a published list from vitalog.cc. Not your results. |
| Send a help message | The message goes to BSOC at outreach@bsoc.space. Send only what you are willing to have read. Do not attach a lab report unless you mean to. |
| Check for a desktop update | The app asks GitHub whether this repository has a newer release. Not your results. |
| Connect Apple Health or Health Connect | Weight, glucose, and blood pressure can move between Vitalog and the health store already on that phone. Vitalog does not run a health cloud. |
| Pair another Vitalog device on the same Wi-Fi | The devices you pair can exchange the record on that network. There is no always-on Vitalog relay. |

Vitalog does not show ads, and it does not sell health data. It does not upload lab contents through an analytics or crash service.

## Download 0.2.8

The current public download is the desktop app. Phone builds are in closed testing. Microsoft Store submission is in certification.

| Computer | Installer |
|----------|-----------|
| macOS | [Vitalog-0.2.8.dmg](https://github.com/Raghavendra-Pratap/vitalog-pub/releases/download/v0.2.8/Vitalog-0.2.8.dmg) (notarized Developer ID) |
| Windows | [Vitalog-0.2.8-setup.exe](https://github.com/Raghavendra-Pratap/vitalog-pub/releases/download/v0.2.8/Vitalog-0.2.8-setup.exe) (SmartScreen may warn until Store is live) |
| Debian and Ubuntu | [Vitalog-0.2.8.deb](https://github.com/Raghavendra-Pratap/vitalog-pub/releases/download/v0.2.8/Vitalog-0.2.8.deb) |

All three are also on the [0.2.8 release](https://github.com/Raghavendra-Pratap/vitalog-pub/releases/tag/v0.2.8). Same files are served from [vitalog.cc/download](https://vitalog.cc/).

On a Mac, open the disk image and move Vitalog into Applications. On Windows, run the setup program. On Debian or Ubuntu, install the package with your package manager.

An installed desktop copy checks this repository for a newer release and opens the installer for that computer. The same version is not offered again. The check does not install silently, and it does not send lab results.

## This repository

This is the public description of Vitalog. The application source is private.

| Read next | What it covers |
|-----------|----------------|
| [What you can do](pub/README.md) | The record, in short |
| [How it is put together](pub/ARCHITECTURE.md) | On-device storage, and the network uses above |

You will not find the application source, internal design notes, database schemas, or sample reports here.
