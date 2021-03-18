---
id: firmware-firmware
title: Firmware
custom_edit_url: https://github.com/AirReps/website-content/blob/edit/firmware-firmware.md
---
:::caution
Flashing the incorrect firmware to your device could brick it;
only flash firmware if you're aware of this risk!
:::

## Tutorial
:::note
We recommend you download AirReps official application to flash firmware:
[AirReps156X](https://airreps.info/android)

If the above application does not work, we recommend trying
[this older version](https://airreps.info/androidapk) instead.
:::

Flashing your firmware is not an exact science, therefore your situation may be slightly different than
what you see in the video above.
> [Watch this guide on how to flash your firmware](https://youtu.be/c6hkyg8z89U)

## 2300
| Feature | [2300L](https://airreps.info/files/datasheets/BES2300-L_Datasheet_v0.22.pdf) | [2300H](https://airreps.info/files/datasheets/BES2300-H_Datasheet_v0.22.pdf) | [2300IH](https://airreps.info/files/datasheets/BES2300-IH_Datasheet_v0.25.pdf) | [2300Y](https://airreps.info/files/datasheets/BES2300-Y_Datasheet_v0.14.pdf) | 2300YP | [2300Z](https://airreps.info/files/datasheets/BES2300-Z_Datasheet_v0.15.pdf) |
|---------|-------|-------|--------|-------|--------|-------|
| FF ANC            | No  | Yes | No | Yes | Yes | Yes |
| Hybrid ANC        | No  | Yes | No | Yes | Yes | Yes |
| Flash size        | 1MB | 2MB | 1MB | 4MB | ? | 4MB |
| Bluetooth version | 5.0 | 5.0 | 5.0 | 5.0 | 5.0 | 5.0 |


## AB1562M (V3M)
| Difference | Tigerbuilder | AiTronics (Peppa Pig) |
|------------|--------------|-----------------------|
| Mic Quality | 1:1 | 0.5:1 |
| Battery life | 5-7H | 5-7H |
| Sound Quality | Excellent | Good |
| Hey Siri | No | Yes |
| Firmware Updates | Yes | No |
| About Page | No | Yes |
| Stability | Excellent | Good |

### Tigerbuilder

#### Februray 2021 - V130.1.1.144
> [Download - V130.1.1.144](https://github.com/AirReps/firmware/raw/master/devices/non-pro/AB1562M/TigerBuilder/V130.1.1.144_FOTA.rar)

#### January 2021 - V130.X.X.42
<!-- > [Download - V130.X.X.42](_blank) -->
* Not available

#### January 2021 - V130.1.1.40
> [Download - V130.1.1.40](https://github.com/AirReps/firmware/raw/master/devices/non-pro/AB1562M/TigerBuilder/V130.1.1.40_FOTA.rar)

* More bass
* Better battery life

#### January 2021 - V130.1.2.38   
>[Download - V130.1.2.38](https://github.com/AirReps/firmware/raw/master/devices/non-pro/AB1562M/TigerBuilder/V130.1.2.38_FOTA.zip)  

* No known changes

#### December 2020 - V130.1.2.35
> [Download - V130.1.1.35](https://github.com/AirReps/firmware/raw/master/devices/non-pro/AB1562M/TigerBuilder/V130.1.1.35_FOTA.rar)  

* Improved stability
* Auto connection with device is often slow, but not always. Probably will be fixed in .38

#### November 2020 - V130.1.2.32
> [Download - V130.1.1.32](https://github.com/AirReps/firmware/raw/master/devices/non-pro/AB1562M/TigerBuilder/V130.1.1.32_FOTA.rar)  

* During calls, iOS will auto switch to phone microphone when pods are put in case.
* Added better bass.
* Optimized static sound.
* Fixed common bugs.
* Optimized latency and range.
* Fixed Apple watch compatibility.

#### October 2020 - V130.1.2.24
> [Download - V120.1.1.24](https://github.com/AirReps/firmware/raw/master/devices/non-pro/AB1562M/TigerBuilder/V120.1.1.24_FOTA.rar)  

* Sound quality has been improved with better treble, now matches retail.
* SFX has been improved, with better clarity and more comfortable sound.
* Modified default double-click operation; Left ear play next song, Right ear pause/play.

#### September 2020 - V130.1.2.20 | V130.1.2.17 
> [Download - V120.1.1.20](https://github.com/AirReps/firmware/raw/master/devices/non-pro/AB1562M/TigerBuilder/V120.1.1.20_FOTA.zip)  
> [Download - V120.1.1.17](https://github.com/AirReps/firmware/raw/master/devices/non-pro/AB1562M/TigerBuilder/V120.1.1.17_FOTA.rar)

* Fixed one side of airpods being extra power-hungry.


## Airoha 1562A (V4.5)
### AiTronics / Itronics
You can check if the unit is by AiTronics by doing a soft reset.
AiTronics pods will blink 3 times with blue light after the case has blinked with orange.

#### February 2021
<!-- > [Download - GOES_HERE](_blank) -->

* Not yet available

#### January 2021
> [Download - 1562AJan21Ai](https://github.com/AirReps/firmware/raw/master/devices/pro/AB1562A/AiTronics%20%7C%20iTronics/1562A_JAN_2021.zip)

* Improved ANC background static.
* Improved Transparency mode.

#### November 2020
> [November 2020](https://github.com/AirReps/firmware/raw/master/devices/pro/AB1562A/AiTronics%20%7C%20iTronics/1562A_NOV_2020.zip)

* Added spatial audio.

### Dongguan HR
You can check if the unit is by Dongguan by doing a soft reset.
Dongguan pods **will not** blink with blue light after the case has blinked with orange.

#### November 2020
> [November](https://github.com/AirReps/firmware/raw/master/devices/pro/AB1562A/Dongguan%20HR/dongguan_A3_Plus_V315_2020-11-18%20FOTA.zip)

* Detailed information is not available.