---
title: "Syringe Pump Project"
excerpt: "3D Printed Motorized Pump with Syringe Compatability"
header:
  image: /assets/img/LF3DP-Banner-2.jpg
  teaser: /assets/img/Large-Format-3D-Printer-Thumbnail.png
gallery:
  - image_path: assets/img/Slide-3.png
  - image_path: assets/img/Slide-2.png
  - image_path: assets/img/Slide-4.png
   
---

# Project Design Overview

The syringe pump is a small tool used to steadily deliver specified volumes of liquid. Syringe pumps have applications in both healthcare and scientific research because they can deliver liquid volumes to a degree of accuracy beyond human capabilities.

Our syringe pump operates by converting rotational motion into linear motion. An electrically powered stepper motor rotates a lead screw, causing the carriage to move forward and apply pressure to the plunger of the syringe. This pushes the plunger forward and causes liquid to eject from the tip of the syringe at a specified flow rate.

The syringe pump was designed to be compatible with syringes of different diameters and volumes. Custom supports were designed in Fusion 360 to securely hold the syringe while also allowing different syringe sizes to be quickly switched in and out of the apparatus.

The pump includes one button to start and pause its motion and an RGB LED to inform the user of its current state. The LED is green while the pump is running, yellow while it is paused, and red when the syringe is out of liquid. A limit switch is positioned on the carriage so that when the syringe has been emptied, the switch collides with the end support and stops the motion of the motor.

The syringe pump was programmed using Arduino with the AccelStepper library to control the speed of the stepper motor. Calculations were used to convert a desired flow rate in mL/min into the steps per second required from the motor. The flow rate and internal diameter of the syringe can be changed in the program, allowing the pump to operate with different syringe sizes and desired flow rates.

View the [Arduino Code](https://gist.github.com/sszczesny/63c3be88db641657d14363d45011b2e1)

![Syringe Final Assembly Photo](/assets/img/syringe_image.png)

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811b926df60c2b08dca?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="Large Format 3D Printer Gallery" %}
