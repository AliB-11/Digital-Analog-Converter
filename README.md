# 3-Bit R-2R Digital-to-Analog Converter (DAC)

## Description
This repository contains the design, simulation, and physical implementation of a 3-bit R-2R ladder DAC. The converter translates 3-bit digital inputs into corresponding analog voltage levels using a precision resistor network and an operational amplifier.

## Circuit Schematic
### 3-Bit R-2R Ladder DAC Schematic
![circuit schematic](https://github.com/user-attachments/assets/f7253ce4-68b3-48f8-a10b-120a5df39ab9)

## Simulated Output
The following waveform shows the ideal simulated output for digital codes `000` through `111`, obtained from LTSpice.  
![simulated Output](https://github.com/user-attachments/assets/c8e2f8c7-f17c-498c-b8c6-289f05dc347e)


## Expected Binary Conversion Chart
Mapping of 3-bit digital codes to ideal analog voltages:
![Expected binary conversion chart](https://github.com/user-attachments/assets/35d78fc9-2362-4eec-a023-8ce1da3e1af7)


## Physical Circuit
Photograph of the assembled DAC circuit on a breadboard, showing the R-2R network and op‑amp connections.  
![Physical Circuit](https://github.com/user-attachments/assets/45f72a51-0d6a-4a2d-a641-571f447daa49)


## Scope Output
Oscilloscope capture of the DAC output on the Analog Discovery 3, demonstrating real-world performance.  
![Scope Output and Measurements](https://github.com/user-attachments/assets/870c7833-9bc1-465f-8efb-2fac0f32c2fa)
