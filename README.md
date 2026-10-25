# MIDI-keypad
## An electronic instrument based around a Waveshare ESP32-S3-Zero.

Chosen in the Half life project because I personally always wanted an instrument but never had the chance to get one when I was younger so making my own is even better! 

<img width="1330" height="770" alt="Screenshot From 2026-10-25 22-47-37" src="https://github.com/user-attachments/assets/189e2c62-a638-47f6-8133-866388097a65" />

Its intentionally simplistic because I wanted something that anyone can understand at a first glance and also because of budget and time constraints as well.

## Features

- a Waveshare ESP32-S3-Zero, the thing that actually makes everything work
- three buttons typical of a mechanical keyboard
- a rotary encoder
- and two potentiometers
  
## Bill of materials
[bom.md](https://github.com/user-attachments/files/33940341/bom.md)

| Id | Designator | Footprint | Quantity | Designation | Supplier and ref |
|----|------------|-----------|----------|-------------|------------------|
| 1 | D1, D2 | LED_SK6812MINI-E_3.2x2.8mm_P1.5mm_ReverseMount | 2 | SK6812MINI-E | keeb.io (25-pack) |
| 2 | RV1, RV2 | Potentiometer_Bourns_PTA1543_Single_Slide | 2 | R_Potentiometer_MountingPin | Mouser |
| 3 | SW1, SW2, SW3 | Kailh Choc Low-Profile Switches | 3 | SW_Push | Kailh |
| 4 | SW4 | RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm | 1 | RotaryEncoder_Switch_MP | Adafruit |
| 5 | U1 | Waveshare ESP32-S3-Zero | 1 | Waveshare ESP32-S3-ZERO | Waveshare |

## Its schematic and PCB

<img width="1920" height="1048" alt="Screenshot From 2026-10-26 00-36-43" src="https://github.com/user-attachments/assets/89c9dcaf-cd8e-453c-b6b4-618de21d2119" />


<img width="1920" height="1048" alt="Screenshot From 2026-10-25 22-18-07" src="https://github.com/user-attachments/assets/2b053c49-d9bf-4de4-befb-1fb29495c143" />

