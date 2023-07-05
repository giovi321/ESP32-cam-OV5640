ESP32 Cam with driver OV5640 is a pretty good ESP32Cam that can be found online.
However, we struggle to configure it on ESPHome and to find a case designed for it.
In this repository, I have published the ESPHome code to configure it and a design for a 3D printed case that fits like a glove.

# License
The content of this repository is licensed under the [WTFPL](http://www.wtfpl.net/).

```
Copyright © 2023 giovi321
This work is free. You can redistribute it and/or modify it under the
terms of the Do What The Fuck You Want To Public License, Version 2,
as published by Sam Hocevar. See the LICENSE file for more details.
```

# ESPHome code
Find the code in the file ESPHome_OV5640.yaml.
The explanation is simple, the variables that change compared to other board drivers are:
- 12Mhz frequency of the camera
- GPIO pinout

# 3D printed case
The case is designed with Sketchup in meters (Sketchup doesn't handle well millimeters).
The case is made of 4 components:
- The shell of the case
- The cover with a hole for the lenses
- The wall-attached ball joint
- The ball joint to be attached to the shell of the case
To screw everything in, you'll need 2.6mm autotapping screws such as [these](https://www.aliexpress.com/item/1005003330377202.html).