# Pipelined RISC-V Processor (Logisim)

A complete, cycle-accurate implementation of a pipelined RISC-V processor designed entirely from scratch using Logisim. This project was developed as part of the Computer Organization and Architecture (COA) coursework at IIT Delhi.

## Architecture Highlights
- **Architecture**: RISC-V 32-bit (RV32I Base Integer Instruction Set)
- **Pipeline Stages**: Standard 5-stage pipeline (Instruction Fetch, Instruction Decode, Execute, Memory Access, Write-Back)
- **Design Tool**: Built visually and structurally using Logisim
- **Components Implemented**:
  - Full Arithmetic Logic Unit (ALU)
  - Register File
  - Instruction Memory & Data Memory modules
  - Control Unit and Hazard Detection/Forwarding logic

## Repository Contents
- **`Logisim_Dhruv_Final`**: Contains the visual `.circ` (Logisim circuit) files representing the datapath and individual processor components.

## How to Run
1. Download [Logisim](http://www.cburch.com/logisim/) (or an actively maintained fork like [Logisim-Evolution](https://github.com/logisim-evolution/logisim-evolution)).
2. Open the main `.circ` file present in the `Logisim_Dhruv_Final` folder.
3. You can step through the clock cycles to observe the propagation of signals across the datapath.

## About the Author
Developed by Dhruv during his First Semester at IIT Delhi (2024)
