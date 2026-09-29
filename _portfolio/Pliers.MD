---
title: "Multi-Material Pliers"
order: 2
excerpt: "3D Printed Pliers with a combination of TPU and PLA"
header:
  image: /assets/img/pliers1.jpeg
  teaser: /assets/img/pliers1.jpeg
---

# Project Design Overview

This project was designed to be a print-in-place model, meaning that the components printed could be assembled and functional immediately after removal from the print bed. The overall objective was to design and print needle nose pliers that could pick up a through-hole resistor. Combining multiple materials is useful because including a flexible element as a spring component allows the pliers to move, while stiff components provide the tool with strength.

In-place printing is a useful design method that has been used in different engineering fields. One example is NASA's 3D-printed Ratchet Wrench. The International Space Station 3D printed this tool using a file sent from Earth. The ratchet wrench was ready to use immediately after printing and was useful because the physical tool did not have to be sent up to space. (Information sourced from [nasa.gov](https://www.nasa.gov/missions/station/space-station-3-d-printer-builds-ratchet-wrench-to-complete-first-phase-of-operations/)). Some consumer products also use in-place printing, such as for plastic water bottles that have hinged caps. These techniques can reduce manufacturing cost and time. Combinations of materials that work well for print-in-place depend on the application. For flexible joints, TPU & PETG or TPU & PLA are popular combinations because they mechanically bond well. Learn more about material combinations [here](https://support.mosaicmfg.com/Wiki/Palette_Multi-Material_Printing_Guide). 

Changes were made throughout the iteration process of this design. TPU was used for the center pivot point of the pliers because its flexibility allowed the pliers to move in the desired motion. PLA was used for the plier arms and handles because of its strength and additive manufacturing efficiency. For the TPU base part, several pieces were printed at different infills, and then their performance was compared. The fill angle was set to 90 degrees for the correct directional motion to occur. The fill density for the base was 10%, and the infill pattern was grid. Infills of 12% and 15% were also tested, but they did not provide enough flexibility for the plier jaws to move properly. The photo below shows how the increase in filament, even by 2%, changes the structure and stiffness of the TPU base.

![Pliers Infill](/assets/img/infill.png)

### Print Settings

| Setting | Base Part | Arm/Handle Part |
|---|---|---|
| Material | TPU | PLA |
| Infill | 10% | 25% |
| Infill Pattern | Grid | Gyroid |
| Fill Angle | 90° | 45° |
| Bottom Solid Layers | 0 | 3 |
| Top Solid Layers | 0 | 4 |
| Perimeter Count | 0 | 2 |

To ensure that the dovetails would have a snug fit, different clearances were printed until the fit was secure, yet the pliers could still be easily disassembled. The final clearance was 0.25 mm. Secure dovetails were essential in preserving the spring motion of the TPU. As the plier arms are moved, the TPU moves from a square to a parallelogram, which closes the plier jaws together. If the dovetails slipped, this motion would not occur. The PLA provides the force that deforms the TPU. The flexible TPU moves into the required shape and when released goes back to its initial state. This is what makes PLA and TPU work so well together for multi-material prints. 

The photos below depict the iteration stages. The original prototype was smaller than the final product. These changes were made from Print #2 to Print #3. The Voron 3D printer's 0.6 mm nozzle struggled to print the smaller details of the first pliers, particularly the dovetails, and the smaller design did not provide much jaw strength. Due to these reasons, the final product was scaled to 150% of the original model. Improved dovetail precision made the pliers much easier to assemble and disassemble. Another improvement from Print #2 to #3 was decreasing the gap between the jaws so that they could pick up the resistor. 

| Iteration | Print #1: Base TPU print with different-sized dovetail fits | Print #2: Simple pliers were printed | Print #3: Scaled-up version of Print #2 with adjusted arms |
|---|---|---|---|
| Photo | <img src="/assets/img/pliers_1.jpeg" width="200"> | <img src="/assets/img/pliers_2.jpeg" width="200"> | <img src="/assets/img/pliers_3.jpeg" width="200"> |
| Details | Clearances of 0 mm, 0.1 mm, and 0.25 mm were printed. The 0.25 mm clearance allowed for manual yet secure assembly. | It assembled well but was not functional due to grid orientation, arm shape, and size. | Final product |

The pliers can pick up items up to 10 mm thick, which is the maximum gap distance. The jaw length is 75 mm. The resting position is open. 

Multi-material pliers were designed, iterated upon, and tested for a final result that can successfully pick up a resistor. Understanding and improvement of print-in-place methods are useful for engineering applications, but also every day 3D printing accessibility. 

## Final Product

### Disassembled Pliers

<img src="/assets/img/pliers_3.jpeg" width="500">

### Assembled Pliers

<img src="/assets/img/finalpliers.jpeg" width="500">

## Video of Pliers Operation

![Pliers GIF](/assets/img/ezgif.com-speed.gif)

## Final Assembly CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811434b0f39557b4d3a?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"></iframe>
