# CNC-P

![License](https://img.shields.io/github/license/Travis8795/CNC-P?style=flat-square)
![Status](https://img.shields.io/badge/Status-Prototype-orange?style=flat-square)
![Motion](https://img.shields.io/badge/Motion-CoreXY-blueviolet?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Arduino-00979D?style=flat-square&logo=arduino)
![Open Hardware](https://img.shields.io/badge/Open-Hardware-brightgreen?style=flat-square)

---
This is a compact CoreXY CNC machine for PCB making at home, capable of engraving copper and specifically taking FR4 PCBs.

## The why
Ordering PCB in Egypt is like pulling teeth, you have to wait till ur lil brother grows, and after it comes, you have to pay the customs with ur cidney, so **no** I'M MAKING MY OWN PCBs.

## What I have learned 

I knew it was a hard project, but damn, I didn't know I'd learn this far. This project helped me learn more about rigidity, motion control, mechanical fundamentals, and much more that I can't count.

### some pics

![image alt](https://raw.githubusercontent.com/Travis8795/CNC-P/main/assets/render.png)

| bem | bom | bam |
|-|-| - |
| ![image alt](https://raw.github.com/Travis8795/CNC-P/main/assets/bem.png) | ![image alt](https://raw.github.com/Travis8795/CNC-P/main/assets/bom.png) | ![image alt](https://raw.github.com/Travis8795/CNC-P/main/assets/bam.png) |

![image alt](https://raw.github.com/Travis8795/CNC-P/main/assets/diagram.jpg)

### BOM table
| Category | Item Name | Purpose | Quantity | Total Cost (USD) |
| :--- | :--- | :--- | :---: | :---: |
| **Assembly Tools** | 90° Machinist Square | For framing corners perfectly square | - | $1.00 |
| **Assembly Tools** | Digital Calipers | Ensure dimensions and measurements are accurate | - | $4.00 |
| **Assembly Tools** | Screwdriver Set: Phillips & Flat | Assembly tools | - | $3.00 |
| **Assembly Tools** | Metric Hex / Allen Key Set | Assembly tools for hex bolts/screws | - | $4.00 |
| **Assembly Tools** | Needle-Nose Pliers | Handling small nuts and components | - | $1.50 |
| **Assembly Tools** | Wire Stripper | Wiring and electronics prep tool | - | $3.00 |
| **Assembly Tools** | Flush Wire Cutters | Trimming wires and cable ties clean | - | $3.00 |
| **Assembly Tools** | Heat Gun | Shrinking heat shrink tubing over wire splices | - | $6.00 |
| **Electronics & Power** | BIGTREETECH SKR PRO V1.2 | Main control board (future upgradeable to 3D printer + CNC) | 1 | $74.00 |
| **Electronics & Power** | Power Supply | Core system power delivery | 1 | $12.00 |
| **Electronics & Power** | ESC Skywalker 40A V2 UBEC 3-4S | Brushless spindle motor driver speed controller | 1 | $15.76 |
| **Electronics & Power** | Mechanical Endstop | Homing the axes limits | 3 | $1.40 |
| **Electronics & Power** | 12V Brushless 40x40x10mm Fan | Cool down the control electronics/system | 1 | $2.00 |
| **Electronics & Power** | Jumper Wires | Connecting pins on control boards | 10 | $1.00 |
| **Electronics & Power** | Heat Shrink Tubing | Wire insulation and safety protection | 10 | $1.00 |
| **Electronics & Power** | Zip Ties | Wire organization and cable management | 1 | $2.50 |
| **Electronics & Power** | Cable Drag Chain | Holds moving cables together cleanly without binding | 1 | $15.00 |
| **Motion & Actuation** | Brushless Motor | Spindle motor to spin bits and engrave copper | 1 | $16.17 |
| **Motion & Actuation** | NEMA 11 Stepper Motor | Driving linear motion for X and Y axes | 2 | $41.85 |
| **Motion & Actuation** | MGN9H Linear Bearing Block | High precision linear rail carriage block | 2 | $19.20 
| **Motion & Actuation** | GT2 Timing Belt | Linear motion transmission system | 3 | $3.71 |
| **Motion & Actuation** | GT2 Pulley 16T (Bore 5mm, H 10mm) | Drive gear for the timing belts to rotate along | 4 | $1.00 |
| **Motion & Actuation** | Timing Belt Tensioner Spring | Keeps ideal tension on the GT2 timing belts | 2 | $0.30 |
| **Motion & Actuation** | Bearings LM6UU | Linear motion along the chrome plates | 4 | $2.00 |
| **Motion & Actuation** | Chrome Plated Rods (6x100mm, 6x180mm) | Guide rails for structural movement | 1 | $3.00 |
| **Motion & Actuation** | Threaded Rods M3x100mm | Direct lead screw drive for fine axis positioning | 1 | $2.00 |
| **Frame & Structure** | 15180 Aluminum Profile (200x180mm) | The heavy flat bed surface for material placement | 1 | $4.00 |
| **Frame & Structure** | 2020 Aluminum Extrusion (220mm) | Machine frame body rails | 4 | $4.76 |
| **Frame & Structure** | 2020 Aluminum Extrusion (75mm) | Machine frame body vertical pillars/supports | 4 | $4.00 |
| **Frame & Structure** | T-Slot Nut | Captive nuts used to fasten hardware to extrusions | 50 | $4.76 |
