# UART Protocol Design and Verification

A complete implementation and verification of the **UART (Universal Asynchronous Receiver Transmitter)** protocol using Verilog and SystemVerilog. The design consists of a Baud Rate Generator, UART Transmitter, UART Receiver and a top module integrating all components for asynchronous serial communication.

---

## Overview

UART is one of the most widely used peripheral serial communication protocols in embedded systems and digital electronics.

This project implements:-

- Baud Rate Generator
- UART Transmitter
- UART Receiver
- UART top module

The design follows the standard UART frame format:

```
| Start Bit | 8 Data Bits (LSB First) | Parity Bit | Stop Bit |
```

---

## Features

✅ Baud rate generation from system clock  
✅ 8-bit parallel to serial conversion  
✅ Serial to parallel conversion     
✅ Receiver oversampling for reliable reception  
✅ Functional Coverage using SV

---

## Applications

- Serial communication interfaces
- Embedded systems
- FPGA-based communication systems
- Sensor interfacing
- Debugging and terminal interfaces

---

## Future Improvements

- Configurable baud rates
- FIFO buffers
- Variable data lengths (5–9 bits)
- Add Assertion-Based Verification techniques

---

## Author

**Sumanta Kumar Dutta**
