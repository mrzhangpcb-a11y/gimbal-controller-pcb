# Gimbal Controller Board v1.0

A high-performance gimbal controller board based on 
STM32F765VIT6, designed for industrial UAV and 
stabilization applications.

## Key Features

- **MCU**: STM32F765VIT6 (ARM Cortex-M7, 216MHz, LQFP-100)
- **Power**: TPS54531DDAR buck converter + ADM7172 LDO
- **Communications**:
  - RS-485 x4 (MAX3485ESA+T × 3, MAX3490EESA+T × 2)
  - RS-232 (SIT3232EEUE)
  - Isolated RS-485 (ADM2682EBRIZ, 2500V isolation)
  - UART debug port (4-pin 2.0mm header)
- **Storage**: W25Q128JVEIQ 128Mbit SPI Flash
- **Protection**: SMBJ24CA TVS diode, B340A Schottky
- **Clock**: 8MHz main + 32.768KHz RTC crystal
- **Connectors**: MDC1-15SW1, MDC1-25SW1

## BOM Summary

| Category | Count |
|----------|-------|
| Capacitors | 89 |
| Resistors | 103 |
| ICs | 11 |
| Connectors | 3 |
| Inductors | 8 |
| **Total** | **~220** |

## PCB Specifications

- Layers: 4
- Main IC: LQFP-100 (0.5mm pitch)
- Smallest component: 0402
- Mixed SMT + THT assembly

## Manufacturing

Designed and assembled by
**[TJHXPCB](https://tjhxpcb.com)** — professional
PCB manufacturer and turnkey assembly provider
based in Tianjin, China.

- Turnkey PCB Assembly:
  [tjhxpcb.com/pcb-assembly](https://tjhxpcb.com/pcb-assembly/)


## Files

- `/gerbers/` — Gerber production files
- `BOM.xls` — Full bill of materials

## License

CERN Open Hardware Licence Version 2 - Permissive
