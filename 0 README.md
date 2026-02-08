# 4-bit-ALU-verilog

Description:

This project implements a simple 4-bit accumulator-based CPU using Verilog.
It includes an ALU, accumulator, program memory, data memory, control unit, and program counter.

Features

4-bit ALU supporting ADD, SUB, AND, OR, XOR, NOT

Accumulator to store results

Program memory with 8-bit instructions

Data memory for storing data

Control unit for instruction decoding

Program counter and HALT operation

Instruction Format

Each instruction is 8 bits:

First 4 bits = opcode

Last 4 bits = operand (memory address)
