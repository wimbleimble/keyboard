# keebydeeby

I'm sorry I couldn't think of a better name.

Pretty simple, TKL, ISO keyboard with RGB backlighting. Based around an
ATMega32u4, compatible with QMK (and probably a lot more).

## Repo Structure

```
├──📁 enclosure                - Enclosure CAD files.
├──📁 kicad                    - Schematic/PCB CAD file.
│   ├─📁 Custom.pretty         - Custom KiCAD footprints.
│   ├─📁 media                 - Miscellaneous Media Dependencies for PCB.
│   ├─📄 Custom.kicad_sym      - Custom KiCAD symbols.
│   ├─📄 keyboard.kicad_pro    - KiCAD project file.
│   ├─📄 keyboard.kicad_pcb    - PCB File
│   ├─📄 keyboard.kicad_sch    - Master schematic page.
│   ├─📄 key-matrix.kicad_sch  - Key matrix schematic page.
│   ├─📄 LEDS.kicad_sch        - RBG matrix schematic page.
│   ├─📄 mcu.kicad_sch         - Microcontroller schematic page.
│   ├─📄 fp-info-cache         - KiCAD internal file.
│   ├─📄 fp-lib-table          - KiCAD internal file
│   └─📄 sym-lib-table         - KiCAD internal file.
├─📁 plate                     - Plate CAD files.
│   └─📄 plate.svg             - CAD drawing of plate.
└─📄 README.md                 - You're looking at it.
```
