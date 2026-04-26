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

| Name                                | Description                     | Quantity |
| :---------------------------------- | :------------------------------ | :------- |
| 15180 aluminum profile 200x180mm    | the bed                         | 1        |
| GT2 pulley 16T Bore 5mm height 10mm | the belt will rotate along it   | 4        |
| Timing Belt Tensioner Spring        | Tensioner the Timing Belt       | 2        |
| Bearings lm6uu                      | move along chrome palte         | 4        |
| Chrome Plated Rods 6x100mm, 6x180mm | guide the axes                  | 1        |
| Threaded Rods M3x100mm              | direct the axes                 | 1        |
| Mechanical endstop                  | home the head                   | 3        |
| ESC Skywalker 40A V2 UBEC 3-4S      | brushless motor driver          | 1        |
| jumpers                             | connect pins                    | 10       |
| some het shrink                     | keep the wires safe             | 10       |
| zip ties                            | organize wiers                  | 1        |
| 12V brushless 40x40x10mm fan        | cool down the system            | 1        |
| power supply                        | power                           | 1        |
| Cable Drag Chain                    | hold caples toggizer            | 1        |
| brushless motor                     | move the bits to engrave copper | 1        |
| NEMA 11 Stepper Motor               | motors for x and y              | 2        |
| MGN9H Linear Bearing Block          | move things                     | 2        |
| GT2 Timing Belt                     | motion system                   | 3        |
| T-slot nut                          | hold everything                 | 50       |
| 2020 aluminum extrusion - 75mm      | body                            | 4        |
| 2020 aluminum extrusion - 220mm     | body                           | 4        |
