# Space Performance V2 Controller
<img width="100%" alt="d3f8fa78-5b3f-4a2f-8f40-94e7eeca5fef" src="https://github.com/user-attachments/assets/39a82a05-bd86-43b4-8f9d-0500b84cd88f" />  

With the Teensy 4.0 Microcontroller from PJRC and the Arduino XInput library  from dMadison, you can build your own DIY Xbox-like controller.

# Setup
**Important Links:**  
**Teensy 4.0:** https://www.pjrc.com/store/teensy40.html  
**Arduino XInput Libary:** https://github.com/dmadison/ArduinoXInput

<img width="100%" alt="Unbenannt" src="https://github.com/user-attachments/assets/21f91fc9-73f8-4137-860e-9ca5250b0e0b" />

## Control Surface 
- all 15 Digital Buttons
- 2 Analog Joysticks (16 bit) (12 bit max for Teensy, 10 bit for less noise)
- 2 Analog Triggers (8 bit)
- 1 Four-Way Directional Pad (D-Pad)

# My own Build: Space Performance V2 Controller
<img width="100%" alt="Unbenannnt" src="https://github.com/user-attachments/assets/93487109-df3d-498a-9c28-86d92a7d6322" />
<img width="100%" alt="Unbenannnnt" src="https://github.com/user-attachments/assets/5d2e0f59-174f-4c4c-9f29-892c46cf2381" />

## Specs of the Controller
<img width="100%" alt="a74fb86b-df5e-4b0c-8d26-d2b549598043" src="https://github.com/user-attachments/assets/3a738f25-3d84-4597-af37-9f7ba224b58c" />
 
**Specs:**  
- **Powerd by Teensy 4.0 with XInput**
- full 3D printable case
- own 3D printable analogsticks with ball bearing mounting (Gulikit Xbox TMR Sensors), under 1% deadzone in-game possible
- all digital Buttons (optional - analog Trigger)
- 6 paddles
- no vibration motors
- only wired USB-C
- 8000 Hz polling-rate (real end-to-end latency of 1ms)  

<img width="100%" alt="Unbenannnnnnt" src="https://github.com/user-attachments/assets/61ef6b60-dc72-403e-b005-97eac1d032b9" />

# Polling Rate and Latency
**My own beta Tester:**  
<img width="100%" alt="Screenshot 2026-08-07 113543" src="https://github.com/user-attachments/assets/4ccb43f7-62e5-4ea0-b10d-5e1030467231" />
<img width="100%" alt="test" src="https://github.com/user-attachments/assets/baefde91-5076-4a6c-8c6c-a6bc849ca3ad" />
Link: https://github.com/SylvesterFPS/Button-Latency-Tester-for-XInput-Gamepads

**Note:** GIP stands for the "new" XInput-Protocol the Controllers are using. But that doesent mean it interface on PC with GIP (GIP-Driver on Windows is limited to 1000Hz) - more it has the functions of the new GameInputProtocol. So the Space Performance Controller on XInput(GIP) work like an GIP controller with alle functions of a modern Xbox Series X/S controller, but uses a diffrent driver on PC which allows, to work with XInput-API and GIP-API on 8000Hz on PC. --> I will explain later how it works. 
 
**Gamepadla:**   
<img width="100%" alt="Screenshot 2026-05-26 162045" src="https://github.com/user-attachments/assets/7a1e3f6d-f4e5-4783-887c-abee92d7d1c4" />
Link: https://gamepadla.com/teensy-4-0-xinput-controller.html  

**Deeppoll:**   
<img width="50%" alt="Screenshot 2026-06-20 125325" src="https://github.com/user-attachments/assets/51064c89-1029-4679-b5e9-c25a79505b50" />  
Link: https://tools.mariusheier.com/deeppoll.html  


# SLA-3D-Printer-Parts
Raw printed parts (Front and Back).
The STL files are not yet available due to stability testing. There may be a public version in the future. You can download the current version if you want to try it on this site: https://grabcad.com/library/space-performance-v2-controller-1/details?folder_id=14229136
. However, please note that there is currently no assembly tutorial available for these parts.

<img width="100%" alt="Unbenannt" src="https://github.com/user-attachments/assets/df5b5ce7-e4e0-482b-b082-9d55db1be5f0" />  

# Test Ingame

https://github.com/user-attachments/assets/8df616dd-1650-4056-8ab0-c3171b6e6a49

![20260321_111201](https://github.com/user-attachments/assets/0483f678-2e1d-4108-a938-a7fbf1814e2d)

# Currently working on:
- **Firmware Processing Latency**
- **App for calibration**
<img width="50%" alt="Screenshot 2026-06-11 134910" src="https://github.com/user-attachments/assets/74884c35-0de8-4b1d-b167-2e7bd65dbcbe" />

[![Download EXE](https://img.shields.io/badge/Download-Space_Calibration_Beta_Software%20(.exe)-blue?style=for-the-badge)](https://github.com/SylvesterFPS/Space-Performance-V2-aka-Teensy-4.0-XInput-Controller/releases/download/Software/Space_Controller.exe)

- **new Shell "Space Performance V3"**
- with LED, Keyboard-Button-Mapping and Scroll-Wheel

- **The firmware source code will later also be released as open source for the XInput-USB-Mode!**

























