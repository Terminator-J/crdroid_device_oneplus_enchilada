# Device Tree for OnePlus 6 (enchilada)

The OnePlus 6 (codenamed _"enchilada"_) is a flagship smartphone from OnePlus.
It was released in May 2018.

| Basic                   | Spec Sheet                                                                                                                     |
| -----------------------:|:------------------------------------------------------------------------------------------------------------------------------ |
| CPU                     | Octa-core (4x2.8 GHz Kryo 385 Gold & 4x1.7 GHz Kryo 385 Silver)                                                                |
| Chipset                 | Qualcomm SDM845 Snapdragon 845                                                                                                 |
| GPU                     | Adreno 630                                                                                                                     |
| Memory                  | 6/8 GB RAM                                                                                                                     |
| Shipped Android Version | 8.1                                                                                                                            |
| Storage                 | 64/128/256 GB                                                                                                                  |
| Battery                 | Non-removable Li-Po 3300 mAh battery                                                                                           |
| Display                 | Optic AMOLED, 1080 x 2280 pixels, 19:9 ratio (~402 ppi density)                                                                |
| Camera (Back)           | Dual: 16 MP (f/1.7, 27mm, 1/2.6", 1.22µm, gyro-EIS, OIS) + 20 MP (16 MP effective, f/1.7, 1/2.8", 1.0µm), PDAF, dual-LED flash |
| Camera (Front)          | 16 MP (f/2.0, 25mm, 1/3", 1.0µm), gyro-EIS, Auto HDR, 1080p                                                                    |

Copyright 2018 - The LineageOS Project.

![OnePlus 6](https://cdn2.gsmarena.com/vv/pics/oneplus/oneplus-6-5.jpg "OnePlus 6")


## Hola amiguitos

This is my attempt to fix up and add a little crDroid customization flavor back into the device tree for OnePlus 6 (enchilada).
Moved a few things to common that don't make sense to be separate, and separated a few things that don't make sense to be commonized.

Rebased on the official lineage-20 branch of the LineageOS device tree as of October 2023.
