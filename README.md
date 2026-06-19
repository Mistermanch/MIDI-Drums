# Arduino MIDI Drums

A DIY Arduino-based drum controller that transmits MIDI signals. Build your own tactile drum pads using affordable materials and an Arduino Nano microcontroller.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Bill of Materials](#bill-of-materials)
- [Assembly Instructions](#assembly-instructions)
- [Getting Started](#getting-started)

## Overview

This project guides you through building 8 MIDI-enabled drum pads using:
- Arduino Nano microcontroller
- Piezo sensors for strike detection
- Custom 3D-printed and wood-based construction
- Minimal soldering required

Perfect for music production, live performance, or learning about hardware-software integration.

## Features

- ✓ Up to 8 independent drum pads (limited by Arduino Nano's analog pins)
- ✓ MIDI output compatible with DAWs and music software
- ✓ Affordable materials sourced from common suppliers
- ✓ Customizable pad sensitivity and response
- ✓ Modular design—build as many pads as needed

## Bill of Materials

### Pad Construction

| Item | Quantity | Notes |
|------|----------|-------|
| Foam yoga mat | 1 | [Decathlon](https://www.decathlon.es/es/p/aislante-esterilla-de-espuma-180-50-cm-forclaz-m100/13259/c210m5591048) |
| Plywood base (60×30×1 cm) | 1 | Cut into 12×12 cm squares |
| Piezo sensor (27mm) | 8+ | [Amazon](https://amzn.eu/d/06fRtvy3) |
| EVA rubber sheets | 1 set | [Amazon](https://amzn.eu/d/05HnhJ7I) |

### Electronics

| Item | Quantity | Notes |
|------|----------|-------|
| Arduino Nano | 1 | [Amazon](https://amzn.eu/d/0cT62Rpz) |
| HiFi cable (0.75mm²) | ~10m | Extra for safety |
| Heat shrink tubing | 1 pack | Various sizes |
| 1M Ohm resistors | 8+ | One per pad |
| Dupont cables | 1 pack | For breadboard prototyping |

### Tools & Miscellaneous

| Tool | Purpose |
|------|---------|
| Soldering iron + solder | Electronics assembly |
| Flux | Soldering (recommended) |
| Flush cutter | Wire trimming |
| 3D printer | Minimum A1 mini size |
| Exacto knife / cutter | Precision cutting |
| Wood saw | Electric saw recommended |
| Hot glue gun | Foam adhesion |
| Cutting mat | Recommended for protection |

## Assembly Instructions

### Step 1: Prepare Materials
Cut both wood and foam into **12×12 cm squares** (adjust size as desired).

### Step 2: Attach Piezo Sensor
1. Position the piezo sensor using double-sided tape
2. Route the cable to a fixed position on the board
3. Secure the cable with additional tape

![Piezo sensor placement](https://github.com/user-attachments/assets/5970243e-c4dd-4d94-8cbc-5444509ebe87)

### Step 3: Bond Foam to Wood
Use hot silicone glue to attach the foam to the wood with the **shiny side facing down**.

### Step 4: Solder Connections
1. Solder piezo terminals to HiFi cable
2. Protect all joints with heat shrink tubing
3. Keep leads organized and labeled

### Step 5: Test the Pad
Test your pad using either:
- **Arduino with test code** - For full functionality
- **Multimeter** - To verify sensor continuity and output

### Step 6: Repeat
Build additional pads as needed (maximum 8 pads per Arduino Nano due to analog pin limitations).

![Completed pad assembly](https://github.com/user-attachments/assets/6be19474-3faf-4dd4-8c8f-9c854f91c93d)

### Step 7: Create Housing & Assembly
*Assembly and housing construction details coming soon.*

## Getting Started

1. Gather all materials from the Bill of Materials
2. Follow the Assembly Instructions step-by-step
3. Upload Arduino sketch to your Nano
4. Configure MIDI mapping in your DAW
5. Start drumming!

## License

This project is licensed under the Apache 2.0 license - see the LICENSE file for details.

## Contact

Questions or improvements? Feel free to open an issue or submit a pull request.

---

*Last updated: June 2026*
