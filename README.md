# Opencore Configuration for HP 14s-FQ1004AU

NOTE : This configuration is still Work In Progress (WIP), tested on macOS Sonoma Public Beta 14.0

## Specification

| Name | Description |
| --- | --- |
| Processor | AMD Ryzen 5 5500U |
| RAM | 2 x 4GB DDR4-3200 |
| Audio | Realtek ALC236 |
| iGPU | AMD Radeon Vega 7 |
| Wireless Adapter | Realtek 8821CE 802.11ac |

## What's Working ?
- Power Management
- Graphics Acceleration, Using [NootedRed](https://github.com/ChefKissInc/NootedRed)
- Onboard Audio
- Microphone
- Backlight Control
- Keyboard Hotkey
- Display Output through HDMI
- Battery Readout

## Known Issue / Not Working & Workaround
- Sleep/Wake (Went on instantly, unable to enter deeper sleep state)
- High Idle CPU Temperature
- HDMI Audio
- System Lockup in Application that heavily uses IGP
- Hardware Acceleration in Chromium-Based apps (simply disable any hardware/graphic acceleration and you're good to go)
- Battery Life is somehow worse
- Onboard Wi-Fi (Replace with Intel AX210 if you want to)





