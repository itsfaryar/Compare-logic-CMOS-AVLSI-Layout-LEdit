# Compare-logic-CMOS-AVLSI-Layout-LEdit

## Introduction

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

## Compare Circuit Gate Logic

![Gate Level Design](Images/logic_gate_design.png)

## Transistor Circuit Design and Stick Diagram

For this task, the circuit is divided into three different sections, each responsible for generating one of the outputs: `Out0`, `Out1`, and `Out2`.

At this stage, the designed circuit diagrams are as follows. In the next section, they are integrated into a single cell where their corresponding ports are interconnected.

### Out0 Stick Diagram

![Out0 Stick Diagram](Images/out0_stick_diagram.png)

### Out1 Stick Diagram

![Out1 Stick Diagram](Images/out1_stick_diagram.png)

### Out2 Stick Diagram

![Out2 Stick Diagram](Images/out2_stick_diagram.png)
