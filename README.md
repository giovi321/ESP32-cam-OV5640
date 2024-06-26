ESP32 Cam with driver OV5640 is a pretty good ESP32Cam that can be found online.
However, we struggle to configure it on ESPHome and to find a case designed for it.
In this repository, I have published the ESPHome code to configure it and a design for a 3D printed case that fits like a glove.

![image](https://github.com/giovi321/ESP32-cam-OV5640/assets/6443515/f90ed446-8e4a-454d-bb1e-a4d755ac3189)


# License
The content of this repository is licensed under the [WTFPL](http://www.wtfpl.net/).

```
Copyright © 2023 giovi321
This work is free. You can redistribute it and/or modify it under the
terms of the Do What The Fuck You Want To Public License, Version 2,
as published by Sam Hocevar. See the LICENSE file for more details.
```

# ESPHome code
Find the code in [this file](ESPHome_OV5640.yaml).
The explanation is simple, the variables that change compared to other board drivers are:
- 12Mhz frequency of the camera
- GPIO pinout

# 3D printed case
The case is designed with Sketchup in meters (Sketchup doesn't handle well millimeters).
The case is made of 4 components:
- The shell of the case
- The cover with a hole for the lenses
- The wall-attached ball joint socket
- The ball joint to be attached to the shell of the case

To screw everything in, you'll need:
- 2.0mm autotapping screws to fix the ESP board to the case
- 2.5mmx6x3.5mm threaded inserts to fix the lid to the box
- M2.5 threaded screws to fix the lid to the box

![ESPCam_OV5640_case_v1](https://github.com/giovi321/ESP32-cam-OV5640/assets/6443515/53e716f2-12ed-4c58-8251-7aab297eb73b)

