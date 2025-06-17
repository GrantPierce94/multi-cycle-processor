# Multi-Cycle and Pipelined Processor Implementation

This project includes a VHDL-based simulation of a single-cycle and pipelined MIPS-like processor designed for educational purposes. The design includes instruction fetch, decode, execute, memory access, and writeback stages.

## Architecture Diagram
![Processor Diagram](./images/processor-diagram.png)

## Features
- Fully functional control unit
- ALU with standard operations
- Register file with read/write control
- Separate single-cycle and pipelined implementations
- Instruction + data memory modules
- Testbenches for key instruction types

## Structure
- `single-cycle/`: Single-cycle implementation and testbenches
- `pipelined/`: Pipelined implementation and testbenches
- `images/`: Block diagrams and screenshots
