# Vitalog

Vitalog keeps a family’s lab results, visits, medicines, and reminders on the device. It compares a result with the range printed on that lab report. It does not diagnose a condition or recommend treatment.

Website: [vitalog.cc](https://vitalog.cc/)  
Privacy: [vitalog.cc/privacy](https://vitalog.cc/privacy)  
Questions: [outreach@bsoc.space](mailto:outreach@bsoc.space)

## This repository

This is the public showcase. Vitalog is not open source.

| What you get | What you do not get |
|--------------|---------------------|
| [What Vitalog does](pub/README.md) | The application source |
| [How it is put together](pub/ARCHITECTURE.md) | Internal design notes, schemas, or sample reports |

The application source is a private repository.

## Desktop

Unsigned installers — a Mac disk image, a Windows setup program, and a Debian package — are published as [releases of this repository](https://github.com/Raghavendra-Pratap/vitalog-pub/releases) when a desktop version is posted here. macOS will say the developer cannot be verified. Windows SmartScreen will ask before the setup runs.

An installed desktop copy checks this repository for a newer release and opens the installer for that computer. The check does not send lab results.
