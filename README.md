<div align="center">
  <img alt="EVA-60 banner" src="assets/banner.svg" width="500"/>
</div>

<h1 align="center">EVA-60</h1>

<p align="center">
  An open hardware keyboard project inspired by Evangelion, built around a compact HHKB-style layout, a custom PCB, and documentation-first development.
  <br/>
  <em>Designed for clarity, repairability, and long-term iteration.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/evan-trr/EVA-60" alt="License"/>
  <img src="https://img.shields.io/badge/status-early%20stage-orange" alt="Status"/>
  <img src="https://img.shields.io/badge/scope-open%20hardware-blue" alt="Scope"/>
  <img src="https://img.shields.io/badge/documentation-active-lightgrey" alt="Documentation"/>
</p>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-progress">Progress</a> •
  <a href="#-features">Features</a> •
  <a href="#-roadmap">Roadmap</a> •
  <a href="#-project-structure">Project structure</a> •
  <a href="#-license">License</a>
</p>

---

## Overview

EVA-60 is an open hardware and open documentation project aimed at building a custom keyboard from the ground up. The project combines a compact HHKB-inspired layout with an Evangelion-inspired visual identity and a documentation structure that covers the full path from concept to manufacturing.

The repository is still in active development, but the direction is already defined: design the keyboard carefully, document the decisions clearly, and keep the project open for iteration.

---

## Progress

<div align="center">
  <img alt="EVA-60 progress" src="assets/progress25.svg" width="600"/>
</div>

The documentation backbone is in place. The remaining work is centered on hardware selection, schematic design, PCB design, case design, and prototype assembly.

---

## Features

- **HHKB-inspired layout** - compact format with a standard space bar.
- **Custom PCB** - designed from scratch with a clear development path.
- **Documentation-first workflow** - overview, goals, hardware, firmware, assembly, manufacturing, and roadmap are documented separately.
- **Firmware-ready direction** - the project is structured with QMK compatibility in mind.
- **Strong visual identity** - Evangelion-inspired palette and typography direction.

---

## Roadmap

- [x] Define the project goals.
- [x] Create the GitHub repository.
- [x] Define the documentation structure.
- [x] Define the layout and design direction.
- [ ] Choose the microcontroller.
- [ ] Select the main components.
- [ ] Design the electrical schematic.
- [ ] Design the PCB.
- [ ] Design the case.
- [ ] Produce and assemble the prototype.

### Near-term milestones

1. Hardware decisions
   - pick the MCU;
   - confirm the key components;
   - lock the electrical direction.

2. Design implementation
   - finalize schematic;
   - route the PCB;
   - validate case constraints.

3. Prototype phase
   - build the first boards;
   - test firmware integration;
   - iterate on the enclosure and layout.

---

## Installation

### Prerequisites

- KiCad or another electronic design environment
- Git
- Basic understanding of PCB and firmware design

### Steps

```bash
git clone https://github.com/evan-trr/EVA-60.git
cd EVA-60
```

---

## Usage

The repository is intended as a working base for open hardware development and documentation. The design notes and technical references live in the docs folder.

---

## Project structure

```text
EVA-60/
├── case/
├── firmware/
├── hardware/
├── docs/
│   ├── 00-Overview.md
│   ├── 01-Goals.md
│   ├── 02-Specifications.md
│   ├── 03-Hardware.md
│   ├── 04-Firmware.md
│   ├── 05-Assembly.md
│   ├── 06-Manufacturing.md
│   └── 07-Roadmap.md
├── LICENSE
└── README.md
```

---

## Design philosophy

1. Simplicity.
2. Reliability.
3. Ease of repair.
4. Open development.
5. Clear visual identity.

---

## Documentation

The full project documentation is available in the [docs](docs) folder.

---

## Acknowledgements

- QMK
- KiCad
- Keyboard Layout Editor (KLE)
- The mechanical keyboard community
- Neon Genesis Evangelion

---

## License

This project is intended to be distributed under an open hardware-friendly license. See [LICENSE](LICENSE) for details.
