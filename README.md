# Gauss Markov KiCad Libraries (converted and updated)

This repository contains the complete conversion of the **Gauss Markov Eagle Libraries** into native **KiCad 8.0/10.0** format and **XML format for Eagle**

These libraries have always been a reference for the DIY pedal community. Unfortunately, they are quite old and on the old binary Eagle format and gauss markov website is today not existing anymore. Moreover, Autodesk has announced Eagle End of Life for June 2026.

That is why I have create this version that modernizes these libraries by converting old binary Eagle `.lbr` files into KiCad footprints (`.pretty` folders) and symbols (`.kicad_sym` files) and `.lbr` file with the modern XML format, that both can be used on KiCad.

---

## Key Features
- **Native KiCad Format**: No "Read-only" warnings. Fully editable and optimized for modern KiCad versions.
- **Pre-Linked Components**: Symbols are already mapped to their correct footprints, no manual linking required.
- **Cleaned Up Graphics**: Removed messy legacy text and documentation overlays for a cleaner schematic view for some components. To be updated in future versions.
- **Full Set**: Includes all classic categories (Pots, Jacks, Caps, Semiconductors, Switches, etc.).

## How to Install

### 1. Add Footprints (PCB)
1. Download or Clone this repository.
2. In KiCad, open the **Footprint Editor**, then go to **Preferences > Manage Footprint Libraries**.
3. Under the **Global Libraries** tab, click the **Folder Icon** (Add existing library).
4. Select all the `.pretty` folders in this repo and click **Open**. Unfortunately you have to do it one by one.

### 2. Add Symbols (Schematic)
1. In KiCad, open the **Symbol Editor**, then go to **Preferences > Manage Symbol Libraries**.
2. Under the **Global Libraries** tab, click the **Folder Icon** (Add existing library).
3. Select all the `.kicad_sym` files in this repo and click **Open**. Again, it has to be done by one.

---

## Included Libraries

- **gm-pots**: 16mm Alpha pots, Dual ganged, and various trimpots styles.
- **gm-caps-ceramic**: Ceramic disc capacitors with multiple lead spacing options.
- **gm-caps-electro-pol**: Polarized electrolytic capacitors in various diameters.
- **gm-caps-film-box**: Box film capacitors (WIMA, KEMET style).
- **gm-caps-film-chicklet**: Standard "Chicklet" style polyester film capacitors (like the old Panasonic ECQ-B).
- **gm-caps-mica**: Silver Mica capacitors.
- **gm-caps-tant**: Tantalum capacitors in case codes A, B, and C.
- **gm-diodes**: Common signal diodes (1N4148), rectifiers (1N4001-7), Schottky (1N5817), and Zener diodes.
- **gm-ics**: Standard pedal ICs including Dual/Quad Op-amps (TL072, LM358), LM386 or CMOS chips (CD4049).
- **gm-jacks**: 1/4" Audio jacks (Mono, Stereo, Switched), DC Power jacks (2.1mm), and Battery clips.
- **gm-inductors**: Specific inductor for wah-wah pedals (**not** Fasel style).
- **gm-switches**: 3PDT/DPDT foot-switches, toggle switches. Small pads and holes, not the best library imo.
- **gm-trans**: Common pedal transistors packages like T092, T018 for several classic models.
- **gm-mics**: Electret condenser microphone footprint and symbol.
- **gm-regulators**: Voltage regulators in TO-92, TO-220, and TO-252 packages (78L05, 7805, etc.).
- **gm-resistors**: Standard 1/4W resistors with multiple lead spacing (horizontal & vertical) and SMD options.
- **gm-supply**: Essential power supply symbols (+9V, -9V, VREF, GND) for clear schematics.
- **gm-voltage**: Reference voltage and battery symbols.
- **gm-xfms**: Audio transformers (e.g., 42TM013) for DI boxes and signal isolation.

---

## Credits & License
- **Original Designs**: All credits to the original creator, **Gauss Markov**.
- **Modernization & Conversion**: Native KiCad conversion and XML cleanup performed by **Coda Effects** ([coda-effects.com](https://www.coda-effects.com)).
- **Legacy Preservation**: This project aims to keep these essential DIY resources alive and compatible with modern EDA tools.

*Note: These libraries are provided "as-is." Always double-check your footprint dimensions against your physical components before ordering PCBs.*
