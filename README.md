# HP ZBook (G1) hackintosh

## Specs
- CPU: Intel Core i7-4800MQ
- IGPU: Intel HD Graphics 4600
- DGPU: Nvidia Quadro K2100M
- RAM: 16KTF1G64HZ-1G6E1
- LCD: B156HAN01.1 (AUO11ED)
- SSD: Samsung 850 PRO
- WLAN: Centrino N 6235
- WWAN: HP lt4112
- Audio: IDT 92HD91BXX
- BIOS: Latest

## Setup configs
- Uncheck "SecureBoot"
- Change Boot Mode to "UEFI Hybrid (With CSM)" (before EDID patching)

## Issues
- Display color is odd because of incompatible EDID.
- Fan noise is louder than Windows.
- Hibernation doesn't work.
- CMOS checksum error occurs sometimes but setting is not lost. (Changing RTC Length may be helpful)

## EDID Patching
[Link](https://github.com/Sniki/Lenovo-Thinkpad-T440) (Patching Display EDID \[WIP\])
