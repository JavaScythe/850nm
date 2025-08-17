---
Title: "850nm"
Author: "JavaScythe"
Description: "850nm area illuminator with adjustable brightness and optional MCU control"
Created On: "8/15/2025"
---
# 8/15/2025 into 8/16/2025

Started the design. Searched "850nm" on JLC parts and looked for high amperage. Found C2833562. Moving forward with that package (SMD3535).

Cost analyis yields 36 per board x2

Initially I tried narrow beam and wide beam setup + schematic, but too expensive and complex.

I layed out the schematic to include manual tune and automatic and mcu, but switched. Used like 6x potentiometer for BOM opt, clunky.

Looked for control methods, considered automatic with IR phototransistor but it will be used with MCU that can do this logic easily

Schematic includes one current limiting resistor, npn, potentiometer, header psuedoswitch, screw terminal for power

<img width="1458" height="880" alt="image" src="https://github.com/user-attachments/assets/bb3e3c6c-3687-437f-8c4b-12c747e9acac" />

Layed out in two layer circle, 20 -> 16, power plane and ground plane. (this sucks, the references and stuff created by circular array is weird, but I learned now)

Added auxiliary edge.cut piece for control electronics mounting, squished all together.

Realized I should use one small resistor instead of one big one for all, swapped and added those in circular pattern (again difficult trying to get them to line up in circular array)

Added some mounting holes

<img width="1112" height="1122" alt="image" src="https://github.com/user-attachments/assets/fb5f6e31-5e16-4c69-aaae-a36c049d4edf" />

### Ordering

Put in JLC for cost estimation, PCB is the standard 2$ but PCBA is too expensive. TLDR, switched to lscs parts and self soldering with stencil.

LSCS shipping can be combined, but shipping remains expensive from China to US. It will be very close if not over 30$ for PCB+shipping, components are 19.

<img width="1483" height="649" alt="image" src="https://github.com/user-attachments/assets/aac969c4-9193-48f1-b3ef-65c340f786f5" />


Long sprint finished, now to add images

<img width="943" height="806" alt="image" src="https://github.com/user-attachments/assets/07e34d84-2fe8-42d9-9cf9-8bc702e1de74" />

**Total time spent: 6h**
