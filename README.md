# TWRP Device configuration for Motorola Moto Z3

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core (4x2.45 GHz Kryo & 4x1.9 GHz Kryo)
CHIPSET | Qualcomm MSM8998 Snapdragon 835
GPU     | Adreno 540
Memory  | 4, 6GB
Shipped Android Version | 8.1 (Oreo)
Storage | 64, 128GB
Battery | 3000 mAh
Dimensions | 156.5 x 76.5 x 6.75 mm
Display | 1080 x 2160 pixels, 6.01" Super AMOLED
Rear Camera  | 12 MP (f/2.0) + 12 MP (f/2.0), (PDAF, dual pixel)
Front Camera | 8 MP (f/2.0)

![Device Picture](https://i-cdn.phonearena.com//images/phones/72766-xlarge/Motorola-Moto-Z3-0.jpg)

### Kernel Source
Check here: https://github.com/ixmoe/android_kernel_motorola_sdm660

### How to compile

```sh
. build/envsetup.sh
lunch omni_messi-eng
make -j4 recoveryimage
```
### Copyright
 ```
  /*
  *  Copyright (C) 2013-17 The OmniROM Project
  *
  * This program is free software: you can redistribute it and/or modify
  * it under the terms of the GNU General Public License as published by
  * the Free Software Foundation, either version 3 of the License, or
  * (at your option) any later version.
  *
  * This program is distributed in the hope that it will be useful,
  * but WITHOUT ANY WARRANTY; without even the implied warranty of
  * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  * GNU General Public License for more details.
  *
  * You should have received a copy of the GNU General Public License
  * along with this program.  If not, see <http://www.gnu.org/licenses/>.
  *
  */
  ```
