# MiNi Microphone Module

An ultra-compact digital MEMS microphone module based on **MP34DT05TR-A**, with PDM output. Designed for voice capture with MCUs like ESP32-S3.

[**中文文档**](README_CN.md)

## Preview

| Front | Back |
|-------|------|
| ![Front](./docs/img.png) | ![Back](./docs/back.png) |

## Features

- **Chip**: MP34DT05TR-A (ST)
- **Output**: PDM (Pulse Density Modulation)
- **SNR**: 64 dB
- **Sensitivity**: -26 dBFS
- **Supply Voltage**: 1.6V – 3.6V
- **Size**: Ultra-compact PCB design

## File Structure

```
MiNi-Microphone/
├── hardware/
│   ├── MicroPhone.eprj    # LCEDA (EasyEDA) project file
│   ├── Gerber.zip          # Gerber manufacturing files (ready for PCB fab)
│   └── BOM.xlsx            # Bill of Materials
├── docs/
│   ├── img.png             # PCB front
│   └── back.png            # PCB back
├── LICENSE
└── README.md
```

## Usage

1. Order PCB fabrication using `hardware/Gerber.zip`
2. Source components per `hardware/BOM.xlsx` and solder
3. Connect to your MCU's I2S/PDM interface to capture audio

## License

MIT License
