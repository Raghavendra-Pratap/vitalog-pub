# How Vitalog is put together

Vitalog is an on-device record. The phone and desktop apps are the same product. There is no Vitalog account and no server that receives lab values, visit notes, or files.

## On the device

The health record stays in an encrypted database on that device. Report photos and PDFs stay in an encrypted store on that device. The app lock is a PIN on the device. Biometrics, when you turn them on, are handled by the operating system.

Settings can wipe the record on that device. An encrypted backup is a file you keep. Restore reads that file back onto a device. Vitalog cannot erase a copy you saved in your own files or cloud drive.

## What may use the network

| Use | What leaves the device |
|-----|------------------------|
| Catalogue and medicine-name lists | A request for the published reference list on vitalog.cc. Not your results. |
| Help message | The message you choose to send to BSOC. |
| Desktop update check | A request for the latest public release. Not your results. |
| Optional phone health connection | Readings move between Vitalog and Health Connect or Apple Health on that phone. Vitalog does not run a health cloud. |
| Same-Wi-Fi pairing | Devices you pair can exchange the record on that network. There is no always-on Vitalog relay. |

## Desktop delivery

Each desktop version is published as three unsigned installers: a Mac disk image, a Windows setup program, and a Debian package. The installed app looks up the latest release. If the published version is newer, it opens that system’s installer. Signing comes later. Until then, macOS and Windows ask before an unsigned installer runs.

## Public and private

This repository is the public description of Vitalog. The application source, internal design notes, and any sample reports stay in a separate private repository.
