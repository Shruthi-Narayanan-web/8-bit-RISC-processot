# 8-bit-RISC-processot
Design and simulation of an 8-bit RISC processor using Verilog coding and Altera DE10 implementation
This project presents the design, simulation, and FPGA implementation of a simple 8-bit RISC processor using Verilog HDL on the Altera DE10 development board.
The processor demonstrates fundamental CPU concepts such as instruction execution, datapath design, control logic, and hardware verification.

This project is intended for educational and portfolio purposes, focusing on clarity, modular design, and correctness rather than high performance.  

## Objectives:
-Design an 8-bit RISC architecture
-Implement processor components in Verilog HDL
-Simulate and verify the design using ModelSim / QuestaSim
-Deploy the processor on the Altera DE10 FPGA board
-Observe processor operation using on-board LEDs and switches

## Hardware & Tools
### Hardware
- FPGA Board: Altera DE10
- FPGA Device: Intel Cyclone
- Clock: On-board oscillator
- I/O: LEDs, switches, optional seven-segment displays
### Software
- Intel Quartus Prime
- ModelSim / QuestaSim
- Verilog HDL

## Major Components
- Program Counter (PC)
- Instruction Memory (ROM)
- Register File (General-purpose registers)
- Arithmetic Logic Unit (ALU)
- Control Unit
- Data Memory (RAM)
- Multiplexers and Control Logic
