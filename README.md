# GPU Dataset

This dataset provides information about various GPUs (Graphics Processing Units) and is collected from [TechPowerUp](https://www.techpowerup.com/). The dataset includes the following columns:

- **Product Name**: The name of the GPU product.
- **GPU Chip**: The chip or architecture used in the GPU.
- **Released**: The release date of the GPU.
- **Bus**: The type and speed of the bus interface.
- **Memory**: The amount of memory and its type.
- **GPU clock**: The clock speed of the GPU core.
- **Memory clock**: The clock speed of the GPU memory.
- **Shaders / TMUs / ROPs**: The number of shaders, texture mapping units, and render output units.
- **URL**: A URL pointing to detailed specifications for the GPU on [TechPowerUp](https://www.techpowerup.com/).

## Example

Here is an example of one row in this dataset:

| Product Name      | GPU Chip | Released       | Bus         | Memory              | GPU clock | Memory clock | Shaders / TMUs / ROPs | URL                                      |
|-------------------|----------|----------------|-------------|---------------------|-----------|--------------|-----------------------|------------------------------------------|
| Quadro 4000       | GF100    | Nov 2nd, 2010  | PCIe 2.0 x16 | 2 GB GDDR5, 256-bit | 475 MHz   | 702 MHz      | 256 / 32 / 32         | [/gpu-specs/quadro-4000.c898](https://www.techpowerup.com/gpu-specs/quadro-4000.c898) |
| Radeon R7 240     | Oland    | Oct 8th, 2013  | PCIe 3.0 x8 | 2 GB, GDDR5, 128 bit | 650 MHz   | 1150 MHz     | 320 / 20 / 8          | [/gpu-specs/radeon-r7-240.c3130](https://www.techpowerup.com/gpu-specs/radeon-r7-240.c3130) |
| Radeon R7 240     | Oland    | Oct 8th, 2013  | PCIe 3.0 x8 | 2 GB, DDR3, 128 bit  | 730 MHz   | 900 MHz      | 320 / 20 / 8          | [/gpu-specs/radeon-r7-240.c2463](https://www.techpowerup.com/gpu-specs/radeon-r7-240.c2463) |
| Radeon R7 240 OEM | Oland    | Nov 1st, 2013  | PCIe 3.0 x8 | 2 GB, DDR3, 128 bit  | 730 MHz   | 900 MHz      | 320 / 20 / 8          | [/gpu-specs/radeon-r7-240-oem.c2542](https://www.techpowerup.com/gpu-specs/radeon-r7-240-oem.c2542) |



## Dataset Usage

You can use this dataset for various purposes, such as analyzing the historical development of GPUs, comparing their specifications, or conducting research in the field of graphics hardware.

## Data Source

The data in this dataset is collected from [TechPowerUp](https://www.techpowerup.com/) and is for informational and educational purposes. Please refer to TechPowerUp for the most up-to-date and accurate GPU specifications.

If you have any questions or would like to contribute to this dataset, please feel free to contact us.
