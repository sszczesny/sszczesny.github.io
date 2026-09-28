---
title: "Multi-Material Pliers"
order: 2
excerpt: "3D Printed Pliers with a combination of TPU and PLA"
header:
  image: /assets/img/pliers1.jpeg
  teaser: /assets/img/pliers1.jpeg

---

# Project Design Overview

This project was designed to be a print-in-place model, meaning that the components printed could be assembled and functional immediately after removal from the print bed. The overall objective was to design and print need nose pliers that could pick up a through-hole resistor. Combining multiple materials is useful in including a flexible element as a spring component allows the pliers to move, and stiff components that provide the tool strength. 


Techniques were made throughout the iteration process of this design. For the TPU base part, several pieces were printed at different infills and then the performance was compared. 
The fill angle was set to 90 degrees for the correct directional motion to occur. The fill density for the base was 10%, and the infill pattern was grid. Infills of 12% and 15% were also tested, and they did not provide enough flexibility. 

![Pliers Infill](/assets/img/infill.png)

To ensure that the dovetails would have a snug fit, different clearances were printed until the fit was secure, yet the pliers were also easily disassembled. The final clearance amount was 0.25mm. 

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



## Video of Pliers Operation
![Pliers GIF](/assets/img/ezgif.com-speed.gif)

## Final Assembly CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811434b0f39557b4d3a?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
