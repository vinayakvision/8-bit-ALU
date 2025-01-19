# 8-Bit ALU Using Xilinx Vivado

## Overview
This project demonstrates the design and implementation of an 8-bit Arithmetic Logic Unit (ALU) using Xilinx Vivado. The ALU performs a range of arithmetic and logical operations on 8-bit binary inputs.

---

## Features
- **Arithmetic Operations:** Addition, Subtraction
- **Logical Operations:** AND, OR, XOR, NOT
- **Shift Operations:** Left Shift, Right Shift
- Supports **zero flag**, **carry flag**, and **overflow detection**

---

## Project Structure

---

## How to Use

### Simulation Steps
1. Open Xilinx Vivado and create a new project.
2. Add the `alu.v` file to the project.
3. Add the `alu_tb.v` file as the testbench.
4. Run behavioral simulation to verify the ALU functionality.

### Synthesis and Implementation
1. Open Xilinx Vivado and synthesize the `alu.v` file.
2. Generate the bitstream for implementation.
3. Test the design on hardware (if available).

---

## Inputs and Outputs
### Inputs:
- **A[7:0]:** First 8-bit input operand.
- **B[7:0]:** Second 8-bit input operand.
- **Opcode[3:0]:** Operation selector (e.g., addition, AND, etc.).

### Outputs:
- **Result[7:0]:** 8-bit result of the selected operation.
- **Flags:** Zero flag, Carry flag, Overflow flag.

---

## Operations (Opcode Mapping)
| Opcode | Operation        | Description               |
|--------|------------------|---------------------------|
| 0000   | Addition         | Adds A and B             |
| 0001   | Subtraction      | Subtracts B from A       |
| 0010   | AND              | Bitwise AND of A and B   |
| 0011   | OR               | Bitwise OR of A and B    |
| 0100   | XOR              | Bitwise XOR of A and B   |
| 0101   | NOT              | Bitwise NOT of A         |
| 0110   | Left Shift       | Logical left shift of A  |
| 0111   | Right Shift      | Logical right shift of A |

---

## Files Included
- `alu.v`: Verilog code for the ALU.
- `alu_tb.v`: Testbench for verifying the ALU.
- `block_diagram.png`: Diagram illustrating the ALU architecture.
- `truth_table.pdf`: Documentation of the operation mappings.

---

## Demonstration
1. **Simulation Results:** The ALU design has been verified with test cases in the simulation. The `alu_waveform.vcd` file showcases the waveform results.
2. **Synthesis:** The ALU was successfully synthesized using Xilinx Vivado, confirming the design’s compatibility with FPGA hardware.

---

## Applications
- Fundamental building block for processors.
- Understanding arithmetic and logical operations.
- Learning FPGA-based digital design.

---

## Contribution
Contributions are welcome! Feel free to submit issues or pull requests.




