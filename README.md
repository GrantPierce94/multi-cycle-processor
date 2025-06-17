# Multi-Cycle and Pipelined MIPS Processor (VHDL)

This project includes both single-cycle and pipelined (multi-cycle) implementations of a MIPS-like processor written in VHDL. Developed as part of an academic course, the design simulates instruction fetch, decode, execute, memory access, and write-back stages, and includes testbenches for verification.

## Architecture Diagram

![Processor Diagram](images/207bf2af155e3c6ab73e2a2b84400812.png)

## Features

- Fully functional control and datapath
- ALU with arithmetic and logic operations
- Register file with read/write capabilities
- Separate single-cycle and pipelined implementations
- Simulated instruction and data memory
- VHDL testbenches covering common instruction types

## Implementations

### Single-Cycle Processor

Executes one complete instruction per clock cycle. This design is simpler and ideal for understanding how datapaths operate without pipeline complexity.

- All stages complete in one cycle
- Basic control logic
- Useful for baseline testing
- Located in `Single-cycle MIPS Processor.zip`

### Pipelined (Multi-Cycle) Processor

Implements a 5-stage pipeline (Instruction Fetch, Decode, Execute, Memory, Write-back), allowing multiple instructions to overlap in execution for better throughput.

- Instruction-level parallelism
- Pipeline hazard detection and resolution
- Improved performance over single-cycle design
- Located in `Multi-Cycle MIPs Processor.zip`

## Repository Structure

├── single-cycle/ # Single-cycle implementation and tests
├── pipelined/ # Pipelined implementation and tests
├── images/ # Block diagrams and architecture visuals
├── LICENSE # MIT License
└── README.md # Project overview

markdown
Copy
Edit

## Tools Used

- VHDL (for hardware description)
- ModelSim (for simulation)
- GitHub (for source control and portfolio presentation)

## License

This project is licensed under the [MIT License](LICENSE).

## Author

Grant Pierce  
B.S. Cybersecurity Engineering  
Iowa State University  
GitHub: [@GrantPierce94](https://github.com/GrantPierce94)
