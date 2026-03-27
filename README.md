# Gauss Markov KiCad Libraries (Converted & Updated)

This repository contains the complete conversion of the **Gauss Markov Eagle Libraries** into native **KiCad 8.0/10.0** format and **XML format for Eagle**

These libraries have been a staple for the DIY guitar pedal community for years. This version modernizes them by converting old Eagle `.lbr` files into KiCad footprints (`.pretty` folders) and symbols (`.kicad_sym` files) following Eagle EoL.

---

## 🛠 Key Features
- **Native KiCad Format**: No "Read-Only" warnings. Fully editable and optimized for modern KiCad versions.
- **Pre-Linked Components**: Symbols are already mapped to their correct footprints—no manual linking required.
- **Cleaned Up Graphics**: Removed messy legacy text and documentation overlays for a cleaner schematic view.
- **Full Set**: Includes all classic categories (Pots, Jacks, Caps, Semiconductors, Switches, etc.).

## 🚀 How to Install

### 1. Add Footprints (PCB)
1. Download or Clone this repository.
2. In KiCad, go to **Preferences > Manage Footprint Libraries**.
3. Under the **Global Libraries** tab, click the **Folder Icon** (Add existing library).
4. Select all the `.pretty` folders in this repo and click **Open**.

### 2. Add Symbols (Schematic)
1. In KiCad, go to **Preferences > Manage Symbol Libraries**.
2. Under the **Global Libraries** tab, click the **Folder Icon** (Add existing library).
3. Select all the `.kicad_sym` files in this repo and click **Open**.

---

## 📁 Included Libraries

- **gm-pots**: 16mm Alpha pots (PCB mount & solder lugs), Dual ganged, and various trimmer styles.
- **gm-caps-ceramic**: Ceramic disc capacitors with multiple lead spacing options (e.g., 5mm, 2.5mm).
- **gm-caps-electro-pol**: Polarized electrolytic capacitors in various diameters and heights.
- **gm-caps-film-box**: High-quality Box film capacitors (WIMA, KEMET style) for audio circuits.
- **gm-caps-film-chicklet**: Standard "Chicklet" style polyester film capacitors (Panasonic ECQ-B).
- **gm-caps-mica**: Silver Mica capacitors, essential for vintage tone stacks and high-frequency stability.
- **gm-caps-tant**: Tantalum capacitors in case codes A, B, and C.
- **gm-diodes**: Common signal diodes (1N4148), rectifiers (1N4001-7), Schottky (1N5817), and Zener diodes.
- **gm-ics**: Standard pedal ICs including Dual/Quad Op-amps (TL072, LM358), LM386, and CMOS chips (CD4049).
- **gm-jacks**: 1/4" Audio jacks (Mono, Stereo, Switched), DC Power jacks (2.1mm), and Battery clips.
- **gm-inductors**: Specific inductors for wah-wah pedals (Fasel style) and noise filtering.
- **gm-switches**: 3PDT/DPDT foot-switches, Toggle switches (Sub-mini & Mini), and DIP switches.
- **gm-trans**: Common pedal transistors (BJT, JFET, MOSFET) like 2N3904, 2N5457, BS170, and more.
- **gm-mics**: Electret condenser microphone footprints and symbols.
- **gm-regulators**: Voltage regulators in TO-92, TO-220, and TO-252 packages (78L05, 7805, etc.).
- **gm-resistors**: Standard 1/4W resistors with multiple lead spacing (horizontal & vertical) and SMD options.
- **gm-supply**: Essential power supply symbols (+9V, -9V, VREF, GND) for clear schematics.
- **gm-voltage**: Reference voltage and battery symbols.
- **gm-xfms**: Audio transformers (e.g., 42TM013) for DI boxes and signal isolation.

---

## ⚖️ Credits & License
- **Original Designs**: All credits to the original creator, **Gauss Markov**.
- **Modernization & Conversion**: Native KiCad conversion and XML cleanup performed by **Coda Effects** ([coda-effects.com](https://www.coda-effects.com)).
- **Legacy Preservation**: This project aims to keep these essential DIY resources alive and compatible with modern EDA tools.

*Note: These libraries are provided "as-is." Always double-check your footprint dimensions against your physical components before ordering PCBs.*