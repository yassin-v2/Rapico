<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/26227bd9-6ad5-4ce1-84e2-db5a73c75b01">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/26227bd9-6ad5-4ce1-84e2-db5a73c75b01">
  <img alligns = "center" width="1333" height="140" alt="Rapico logo" src="https://github.com/user-attachments/assets/26227bd9-6ad5-4ce1-84e2-db5a73c75b01">
</picture>

### A RP2040-based development board with a nRF wireless chip, designed in the Raspberry Pi Pico form factor.

----

<img alligns = "center" width="1723" height="892" alt="PCB Render" src="https://github.com/user-attachments/assets/febcfec6-1957-425e-b399-b49c3192dc0b" />

---

## Features
- **[RP2040](https://pip-assets.raspberrypi.com/categories/814-rp2040/documents/RP-008371-DS-1-rp2040-datasheet.pdf) MCU** - 32bit dual core ARM Cortex M0+ from Raspberry Pi.
- **[nRF24L01P](https://cdn.sparkfun.com/assets/3/d/8/5/1/nRF24L01P_Product_Specification_1_0.pdf) chip** -  2.4GHz radio transceiver, with a PCB trace antenna.
- **USB C** - for programming and power.
- **Raspberry Pi Pico formfactor** - but less pins; 2x18
- **W25Q128JVPIQ flash storage chip** - 16MB high speed flash storage, intergrated with the RP2040 over quad SPI.
- **I2C and SPI** - on many pins.
- **5V and 3.3V power pins**
- Power indicator LED and another addressable LED


## Pinout

<img alligns = "center" width="1723" height="892" alt="PCB Render" src="https://github.com/yassin-v2/Rapico/blob/main/Assets/Board%20Pinout.png" />

## PCB Design
*Find the PCB files [here](https://github.com/yassin-v2/Rapico/tree/main/PCB)*

The PCB is a 2 layer PCB with dimentions 51mm x 21mm.

| ![](https://github.com/yassin-v2/Rapico/blob/main/Assets/FCu.jpg) | ![](https://github.com/yassin-v2/Rapico/blob/main/Assets/BCu.jpg) |
|:---:|:---:|

## Schematic Design
*Find the schematic files [here](https://github.com/yassin-v2/Rapico/tree/main/PCB)*

  <img src="https://github.com/yassin-v2/Rapico/blob/main/Assets/Schematic%20Full.png">

### nRF chip schematic:
  <img src="https://github.com/yassin-v2/Rapico/blob/main/Assets/Schematic%20nRF.png">

### Power input schematic:
  <img src="https://github.com/yassin-v2/Rapico/blob/main/Assets/Schematic%20Power.png">

----
| ![](https://github.com/yassin-v2/Rapico/blob/main/Assets/Render%20Top.jpg) | ![](https://github.com/yassin-v2/Rapico/blob/main/Assets/Render%20Bottum.jpg) |
|:---:|:---:|


<p align="center"><strong><em>Made with KiCad 9, as part of <a href="https://stasis.hackclub.com">Stasis</a> from <a href="https://hackclub.com/">Hackclub</a></em></strong></p>
