---
title: "Multi-Material Pliers"
order: 2
excerpt: "3D Printed Pliers with a combination of TPU and PLA"
header:
  image: /assets/img/syringe_image.png
  teaser: /assets/img/syringe_image.png

---

# Project Design Overview

This project was designed to be a print-in-place model, meaning that the components printed could be assembled and functional immediately after removal from the print bed. 

The overall objective was to design and print need nose pliers that could pick up a through-hole resistor. Combining multiple materials is useful in including a flexible element as a spring component allows the pliers to move, and stiff components that provide the tool strength. 

The fill angle was set to 90 degrees for the correct directional motion to occur. The fill density for the base was 10%, and the infill pattern was grid. Infills of 12% and 15% were also tested, and they did not provide enough flexibility. 

## Operating the Syringe Pump

1) Upload the Arduino code and load the syringe with the required quantity of liquid.
2) Place the syringe in the holder with the tip resting on the front support.
3) Adjust the carriage until it rests against the syringe plunger.
4) Enter the desired flow rate and internal diameter of the syringe.
5) Start the pump using the control button. The pump will stop once the limit switch is reached.

## Parts Required

### Off-the-Shelf Parts

| Part | Quantity |
| --- | --- |
| Stepper Motor | 1 |
| Lead Screw | 1 |
| Linear Rod | 1 |
| Motor Coupler | 1 |
| Arduino | 1 |
| Limit Switch | 1 |
| RGB LED | 1 |
| Start/Pause Button | 1 |
| Syringe | 1 |

### 3D-Printed Parts

| Part | Material |
| --- | --- |
| Motor Mounting Plate | ABS |
| Carriage | PLA |
| Custom End Support | PLA |
| End Support for Syringe Tip | PLA |
| End Support | PLA |

## 3D Rendering of Assembly
![Syringe Final Rendering](/assets/img/pliers_gif)

## Final Assembly
![Syringe Final Assembly Photo](/assets/img/syringe_image.png)

## CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811434b0f39557b4d3a?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
