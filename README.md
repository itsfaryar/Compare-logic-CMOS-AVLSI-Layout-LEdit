# Compare-logic-CMOS-AVLSI-Layout-LEdit

# Introduction

In this project, a gate-driven circuit is provided for comparing two 2-bit numbers. The inputs are represented as `A1` and `A0`, where `A1` is the most significant bit and `A0` is the least significant bit of number `A`, and similarly, `B1` and `B0` represent the most and least significant bits of number `B`. 

The outputs are defined as follows:
- `Out0` indicates the result of the comparison `A > B`
- `Out1` indicates the result of the comparison `A = B`
- `Out2` indicates the result of the comparison `A < B`

Additionally, intermediate nodes labeled `X0`, `X1`, `Y0`, `Y1`, `Z0`, and `Z1` are marked in the schematic. 

This report covers:
- The design and construction of the circuit using transistors
- The development of the **stick diagram**
- The final layout of the circuit in **Ledit** software
- The **netlist analysis** of the generated output using simulated waveforms in **Tspice** software

