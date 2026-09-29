---
title: "Multi-Material Pliers"
order: 2
excerpt: "3D Printed Pliers with a combination of TPU and PLA"
header:
  image: /assets/img/pliers1.jpeg
  teaser: /assets/img/finalpliers.jpeg

---

# Project Design Overview

This project was designed to be a print-in-place model, meaning that the components printed could be assembled and functional immediately after removal from the print bed. The overall objective was to design and print need nose pliers that could pick up a through-hole resistor. Combining multiple materials is useful in including a flexible element as a spring component allows the pliers to move, and stiff components that provide the tool strength. 

In-place printing is a useful design method that has been used in different engineering fields. One example is NASA's 3D printed Rachet Wrench. The International Space Station 3D printed a tool that was a file sent from Earth. This tool, a rachet wrench, was ready to use immediately after printing and useful because it had not been sent up to space. (Information sourced from [nasa.gov](https://www.nasa.gov/missions/station/space-station-3-d-printer-builds-ratchet-wrench-to-complete-first-phase-of-operations/))

Techniques were made throughout the iteration process of this design. TPU was used for the center pivot point of the pliers because its flexure allowed the pliers to move in the desired motion. PLA was used for the plier arms and handle because of its strength and additive manufacturing efficiency. For the TPU base part, several pieces were printed at different infills and then the performance was compared. The fill angle was set to 90 degrees for the correct directional motion to occur. The fill density for the base was 10%, and the infill pattern was grid. Infills of 12% and 15% were also tested, and they did not provide enough flexibility for the plier jaws to move properly. The photo below shows how the increase in filament, even by 2%, changes the structure and stiffness of the TPU base. 

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

To ensure that the dovetails would have a snug fit, different clearances were printed until the fit was secure, yet the pliers were also easily disassembled. The final clearance amount was 0.25mm. Secure dovetails were essential in preserving the spring motion of the TPU. As the plier arms are moved, the TPU moves from a square to a parallelogram, which closes the plier jaws together. If the dovetails slipped, this motion would not occur. 

The photos below depict the iteration stages. The original prototype was smaller than the final product. The Voron 3D printer nozzle of 0.6mm struggled to print the smaller details of first pliers and it didn't provide much jaw strength. Due to both of these reasons, the final product was scaled 150% from the original model. 

| Iteration| Print #1: Base TPU print with different sized dovetail fit.  | Print #2: Simple Pliers were printed | Print #3: Scaled up version of Print #2 with adjusted arms |
|---|---|---|---|
|Photo| <img src="/assets/img/pliers_1.jpeg" width="200"> | <img src="/assets/img/pliers_2.jpeg" width="200"> | <img src="/assets/img/pliers_3.jpeg" width="200"> |
| Details | A clearance of 0mm, 0.1mm, and 0.25mm was printed. 0.25mm allowed manual yet secure assembly. | It assembled well but was not functional due to grid orientation, arm shape, and size.  | Final Product |

The pliers can pick up items up to 10 mm thick, which is the gap distance. The gap length is 75mm. 

## Final Product
### Disassembled Pliers
<img src="/assets/img/pliers_3.jpeg" width="500">

### Assembled Pliers
<img src="/assets/img/finalpliers.jpeg" width="500">

## Video of Pliers Operation
![Pliers GIF](/assets/img/ezgif.com-speed.gif)

## Final Assembly CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811434b0f39557b4d3a?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
