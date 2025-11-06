# ESP32 World Clock and Alarm

This project is a **Digital Logic Design (Sem 3) course project at VJTI**, showcasing the implementation of a world clock and alarm system using an ESP32. 
It utilizes a **4-digit 7-segment display** to show time and demonstrates the use of **combinational circuits** such as BCD to 7-segment decoders. 
The system highlights both hardware design principles and firmware control for a practical embedded application.

## Folder Structure
- **Docs** – Documentation, reports, and design references  
- **PCB** – Circuit schematics, board layout, and related design files  
- **Firmware** – Source code for ESP32 implementation  

```
ESP32_WorldClock_Alarm
    │   PCB.zip
    │   README.md
    │
    ├───Docs
    │       Reference.jpeg
    │
    ├───Firmware
    │   └───Clock
    │       │   CMakeLists.txt
    │       │
    │       └───main
    │               Clock.c
    │               CMakeLists.txt
    │
    └───PCB
        │   CD4026BE.zip
        │   README.md
        │
        └───v1
            │   CD4026BE.kicad_sym
            │   CD4026BE.step
            │   DIP794W45P254L1969H508Q16.kicad_mod
            │   fp-info-cache
            │   freerouting.dsn
            │   temp-freerouting.dsn
            │   v1.csv
            │   v1.kicad_pcb
            │   v1.kicad_prl
            │   v1.kicad_pro
            │   v1.kicad_sch
            │   v1.kicad_sch-bak
            │   v2.dsn
            │   v3.dsn
            │
            └───v1-backups
                    v1-2025-10-22_045640.zip
                    v1-2025-10-26_202308.zip
                    v1-2025-10-28_130222.zip
                    v1-2025-10-28_135910.zip
                    v1-2025-10-28_143325.zip
                    v1-2025-10-28_191431.zip
                    v1-2025-10-30_193222.zip
                    v1-2025-10-30_193947.zip
                    v1-2025-10-30_195150.zip
                    v1-2025-10-30_195731.zip
                    v1-2025-10-31_010139.zip
                    v1-2025-10-31_011447.zip
                    v1-2025-10-31_012544.zip
                    v1-2025-10-31_014305.zip
                    v1-2025-10-31_020036.zip
                    v1-2025-11-03_172902.zip
                    v1-2025-11-03_232243.zip
                    v1-2025-11-03_233844.zip
                    v1-2025-11-03_235613.zip
                    v1-2025-11-04_005950.zip
                    v1-2025-11-04_213110.zip
                    v1-2025-11-04_214232.zip
                    v1-2025-11-04_215051.zip
                    v1-2025-11-04_231246.zip
```