# DIY High-Performance Fume Extractor

A professional-grade, portable DIY fume extractor designed for electronics soldering and small-scale 3D printing. This project features a high-static-pressure PC fan, PWM speed control, and a "plug and play" DC power design.

![Fume Extractor Overview](images/IMG_6640.jpg)

## Features

- **High Airflow & Static Pressure**: Utilizes a Noctua 120mm industrial-grade PC fan for efficient smoke capture.
- **Variable Speed Control**: Integrated PWM controller for precise airflow management and noise reduction.
- **Modular Filtering**: Easy-access filter slot for activated carbon sheets.
- **Rugged 3D Printed Housing**: High-precision housing printed on an **Elegoo Centauri Carbon** in PLA.
- **Adjustable Tilt**: Integrated pivot rod for optimal positioning.

## Technical Specifications

| Parameter | Specification |
|-----------|---------------|
| Input Voltage | 12V - 24V DC (Plug & Play) |
| Fan Size | 120mm x 120mm x 25mm |
| Control Type | PWM (Pulse Width Modulation) |
| Max Current Draw | ~1.5A |
| Filter Type | Activated Carbon |

## Component List (BOM)

- **Fan**: [Noctua NF-F12 industrialPPC-24V-3000 IP67 PWM](https://www.amazon.ca/dp/B00KFCRATC). High-performance industrial fan.
- **Control**: [Mini DC Motor PWM Speed Controller](https://www.aliexpress.com/item/1005007648380753.html) (3V-35V 5A).
- **Filter**: [Activated Carbon Filter Sheets](https://www.amazon.ca/dp/B07RNGMXYG) (130x130mm).
- **Hardware**: McMaster-Carr stainless steel screws and nuts (See [BOM](docs/BOM.md)).
- **Housing**: 3D Printed PLA parts.

## Manufacturing & 3D Printing

The housing components are designed for high durability and ease of assembly.

- **Printer**: Centauri Carbon Elegoo
- **Material**: PLA
- **Settings**: Varying per part. See documentation for more details. 

## Repository Structure

- `cad/`: 3D design files 
- `images/`: Project builds, assembly photos, and test parts.
- `docs/`: Technical manuals, [BOM](docs/BOM.md), and [Assembly Guide](docs/Assembly.md).

