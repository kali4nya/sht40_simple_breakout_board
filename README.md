# SHT40 Simple Breakout Board

A simple breakout board for the **Sensirion SHT40** temperature and humidity sensor, designed in [KiCad](https://www.kicad.org/).

This repository contains two PCB variants:

- **1 Board Version** – A single standalone SHT40 breakout board.
- **4 Board Version** – Four breakout boards panelized together, connected by breakaway tabs for easy separation after manufacturing.

Both versions include the complete KiCad design files and manufacturing outputs generated using the Fabrication Toolkit plugin for KiCad.

---

## PCB Versions

### 1. Single Board Version

A standalone SHT40 breakout board, designed for individual use.

**PCB Renders**

![PCB Front](<1 board version/pictures/pcb_front.png>)

![PCB Design](<1 board version/pictures/pcb_design.png>)

**Included Files**
- KiCad project (`.kicad_pro`)
- Schematic (`.kicad_sch`)
- PCB layout (`.kicad_pcb`)
- Production files (BOM, designators, IPC netlist and component positions)
- Gerber and drill files (ZIP archive)

---

### 2. Four Board Version

A panelized version containing four identical SHT40 breakout boards connected together using breakaway tabs.

The boards can be separated after manufacturing, allowing four individual breakout boards to be obtained from a single PCB panel.

**PCB Renders**

![PCB Front](<4 board version/pictures/pcb_front.png>)

![PCB Design](<4 board version/pictures/pcb_design.png>)

**Included Files**
- KiCad project (`.kicad_pro`)
- Schematic (`.kicad_sch`)
- PCB layout (`.kicad_pcb`)
- Production files (BOM, designators, IPC netlist and component positions)
- Gerber and drill files (ZIP archive)

---

## Schematic

Both PCB versions share the same electrical schematic.

![SHT40 Schematic](<1 board version/pictures/schematic.png>)

---

## Repository Structure

```text
sht40_simple_breakout_board/
│
├── 1 board version/
│   ├── *.kicad_pro
│   ├── *.kicad_sch
│   ├── *.kicad_pcb
│   │
│   ├── production/
│   │   ├── bom.csv
│   │   ├── designators.csv
│   │   ├── netlist.ipc
│   │   ├── positions.csv
│   │   └── Gerber files.zip
│   │
│   └── pictures/
│       ├── pcb_front.png
│       ├── pcb_design.png
│       └── schematic.png
│
├── 4 board version/
│   ├── *.kicad_pro
│   ├── *.kicad_sch
│   ├── *.kicad_pcb
│   │
│   ├── production/
│   │   ├── bom.csv
│   │   ├── designators.csv
│   │   ├── netlist.ipc
│   │   ├── positions.csv
│   │   └── Gerber files.zip
│   │
│   └── pictures/
│       ├── pcb_front.png
│       └── pcb_design.png
│
├── README.md
└── LICENSE
```

---

## Manufacturing

Manufacturing files for both PCB variants are provided in their respective `production` directories.

The files were generated using the JLC **Fabrication Toolkit** plugin for KiCad and include:

| File | Description |
|---|---|
| `bom.csv` | Bill of Materials |
| `designators.csv` | Component designator information |
| `netlist.ipc` | IPC netlist |
| `positions.csv` | Component placement coordinates |
| Gerber ZIP | PCB fabrication layers and drill files |

These files are provided to make PCB manufacturing and assembly easier.

---

## Design Software

- **EDA:** KiCad 10.0
- **Manufacturing file generation:** Fabrication Toolkit for KiCad

---

## License

See the [LICENSE](LICENSE) file for the terms governing the use, modification and distribution of this project.
