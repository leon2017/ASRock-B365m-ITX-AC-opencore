# Hackintosh for Asrock B365 itx/ac via OpenCore

Asrock B365M-ITX-AC Hackintosh OpenCore EFI

![ScreenShot](/screenshot.png)

## Version

| Type     | Version |
| :------- | :------ |
| OpenCore | 0.7.6   |
| MacOS    | 12.2 Monterey   |

## Hardware

| Type            | Item                         |
| :-------------- |:-----------------------------|
| **CPU**         | Intel Core i7-8700           |
| **Motherboard** | ASRock B365M-ITX/ac Mini ITX |
| **Wifi card**   | Broadcom Bcm943602cs         |

## Functionality

### Works

- Ethernet
- Onboard Audio (including digital audio)
- APFS
- Sleep/Wake
- All USB ports at 3.x speed
- iMessage
- App Store
- Facetime
- APFS
- Handoff
- Bluetooth & Wi-Fi
- Airdrop
- AirPlay
- Continuity
- Power Nap
- NVRAM

## Instructions

[OpenCore Desktop Guide](https://dortania.github.io/OpenCore-Desktop-Guide/).

When you have troubles, take look at my kexts, drivers, ACPI and config.list for help.

## SSDT

| SSDT             | Usage |
| :--------------- |:------|
| SSDT-SBUS-MCHC.aml |       |
| SSDT-PLUG.aml    |       |
| SSDT-PMC.aml     |       |
| SSDT-USBX.aml    | EC    |
| SSDT-AWAC.aml    |       |


## Notic 
- SystemSerialNumber
- SystemUUID
- MLB
- Use [USBToolBox](https://github.com/USBToolBox/kext/) making USB Port Map
