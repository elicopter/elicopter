![Elicopter](logo.png)
=========

Glue between all Elicopter components.

## Frame

![Elicopter](elicopter_v2-1.jpg)

> Note: STL files are available on [Thingiverse](http://www.thingiverse.com/thing:2277533).

| Part                          | Quantity   |
| ----------------------------- |:----------:|
tube_inner_fix_2_v3.stl               | 4
imu_bumper_v4.stl                     | 1
propeller_guard_spacer_light_v3.stl   | 8
motor_support_tube_fix_v3.stl.        | 4
pcb_support_v10.stl                   | 1
tube_fix_bottom_v3.stl                | 4
raspberry_model_b_v4.stl              | 1
tube_inner_fix_1_v3.stl               | 4 (with stop at layer 58 for M3 nut see: [CONTRIBUTING.md](parts/tube_inner_fix_1_v3_layer_58.png))
propeller_guard_bottom_v4.stl         | 4
stand_v1.stl                          | 2
motor_spacer_v13.stl                  | 4
led_fix_v4.stl                        | 1
tube_t_fix_v8.stl                     | 8
propeller_guard_guide_v14.stl         | 4
tube_fix_top_v3.stl                   | 2
propellers_guard_top_v4.stl           | 4
battery_fix_v2.stl                    | 2
motor_base_support_v13.stl            | 4 (with stop at layer for 4xM3 nuts see: [CONTRIBUTING.md](parts/motor_base_support_v13_layer_58.png))

## Software

[Core](https://github.com/elicopter/core) repository:
```
git clone https://github.com/elicopter/core.git
```

[Ground Station](https://github.com/elicopter/ground_station) repository:
```
git clone https://github.com/elicopter/ground-station.git
```

[Elicopter System RPI3](https://github.com/elicopter/elicopter_system_rpi3) repository (fork of nerves_system_rpi3):
```
git clone https://github.com/elicopter/elicopter_system_rpi3
```

### Run

* To run `core`, check the project documentation [here](https://github.com/elicopter/core).
* To run `ground-station`, check the project documentation [here](https://github.com/elicopter/ground_station).

## Bill of Material

*This list contains parts which were used for the development, up to you to use other parts if you want.*

| Part                          | Quantity   | Link  |
| ----------------------------- |:----------:| ---------------:|
| Raspberry Pi 3 | 1 | [Adafruit](https://www.adafruit.com/products/3055) |
| Adafruit 10-DOF IMU Breakout - L3GD20H + LSM303 + BMP180 | 1 | [Adafruit](https://www.adafruit.com/products/1604) |
| Emax RS2205S 2300KV | 4 | [Banggood](https://www.banggood.com/4x-Emax-RS2205S-2300KV-Racing-Edition-Brushess-Motor-CW-CCW-for-FPV-Racing-p-1106170.html?rmmds=myaccout-bottom-latestwishlist__1&cur_warehouse=CN)
| ESC Littlebee 30A | 4 | [Banggood](https://www.banggood.com/4X-FVT-LittleBee-30A-ESC-2-6S-BLHeli-Supports-OneShot125-For-RC-Multirotors-p-1031943.html?rmmds=search&cur_warehouse=CN)
| PDB 5v 12v | 1 | [Banggood](https://www.banggood.com/Matek-Mini-Power-Hub-Power-Distribution-Board-With-BEC-5V-And-12V-For-FPV-Multicopter-p-1005549.html?rmmds=search&cur_warehouse=CN)
| Carbon Tube 8mm | 2x 30cm |  [Hobbyking](https://hobbyking.com/fr_fr/carbon-fiber-tube-hollow-8x750mm.html)
| Carbon Tube 16mm | 2x 30cm | [Hobbyking](https://hobbyking.com/fr_fr/carbon-fiber-round-tube-330x16x14mm.html)
| LED | 1 | [Adafruit](https://www.adafruit.com/product/1426)
| 16-Channel 12-bit PWM/Servo Driver - I2C interface | 1 | [Adafruit](https://www.adafruit.com/product/815)
| USB to TTL Serial Cable | 1 | [Adafruit](https://www.adafruit.com/product/954)
| Level Shifter| 1 | [Adafruit](https://www.adafruit.com/product/1875)
| M2 -> M5 screws, nuts | * |
| Radio Receiver | 1 |


## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

