# RISC-V CPU

An RV64 pipelined CPU in SystemVerilog, simulated with Verilator and verified against Spike.
Long-term goal: boot Linux.

## Toolchain
| Tool | Version |
|---|---|
| Verilator | v5.052 |
| Spike | commit 5a760667 |
| riscv64-unknown-elf-gcc | (13.2.0-11ubuntu1+12) 13.2.0 |
| riscv-tests | commit 3df703c |