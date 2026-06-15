# Fault Detection in Combinational Circuits

## Overview

This project presents an FSM-based fault detection mechanism for combinational logic circuits. The objective is to identify single stuck-at faults (SA0 and SA1) while reducing the number of test vectors required for testing.

## Circuits Implemented

* Half Adder
* Full Adder
* Half Subtractor
* Full Subtractor
* Decoder

## Fault Models

* Stuck-at-0 (SA0)
* Stuck-at-1 (SA1)

## Methodology

1. Generate fault-free truth tables.
2. Introduce faults into the circuit.
3. Compare faulty and fault-free outputs.
4. Generate optimized test vectors.
5. Design FSMs to apply test vectors automatically.
6. Detect faults through output mismatches.

## Components Used

* IC7408 (AND Gate)
* IC7432 (OR Gate)
* IC7486 (XOR Gate)
* IC7404 (NOT Gate)
* D Flip-Flops
* Breadboard
* LEDs
* Regulated Power Supply

## Key Features

* Reduced number of test vectors
* Detection of single stuck-at faults
* FSM-based test pattern generation
* Analysis of adders, subtractors, and decoders

## Applications

* VLSI Testing
* Embedded Systems
* Digital Circuit Verification
* Aerospace and Medical Electronics

## Project Report

The complete project report is available in this repository.

## Future Scope
- FPGA implementation
- Built-In Self-Test (BIST)
- Real-time fault monitoring
- AI-assisted fault prediction

