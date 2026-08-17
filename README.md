# RAM 8x8 SystemVerilog Verification

This project implements and verifies a RAM containing 8 memory locations, with each location storing 8 bits of data.

## Features

- Write data to the RAM.
- Read data from the RAM.
- Reset the output data.
- Directed and random testing.
- Self-checking scoreboard.
- SystemVerilog Assertions.
- Functional coverage.

## Files

- `ram8x8design.sv`: RAM 8x8 RTL design.
- `tb8x8.sv`: SystemVerilog verification environment.

## Tools

- Cadence Xcelium 25.03
- EDA Playground
- EPWave

## How to Run

1. Select `SystemVerilog/Verilog`.
2. Select `Cadence Xcelium`.
3. Paste the RTL code into `ram8x8design.sv`.
4. Paste the testbench code into `tb8x8.sv`.
5. Click `Run`.

## Expected Result

```text
FINAL RESULT        : TEST PASSED
Total errors        : 0
