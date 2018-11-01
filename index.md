---
layout: page
title: RISC-V BOOM 
subtitle: The Berkeley Out-of-Order RISC-V Processor 
use-site-title: true
---

The Berkeley Out-of-Order Machine (BOOM) is a synthesizable and parameterizable open source RV64G RISC-V core written in the 
[Chisel](https://chisel.eecs.berkeley.edu/) hardware construction language. It can run on an FPGA (50 MHz on a zc706), but 
optimizing it to be an FPGA soft-core is a non-goal. Created at the University of California,
Berkeley in the [Berkeley Architecture Research](https://bar.eecs.berkeley.edu/) group, its focus is to create a high 
performance, synthesizable, and parameterizable core for architecture research. 

## Features 

Feature | BOOM
--- | ---
ISA | RISC-V (RV64G)
Synthesizable |√
FPGA |√
Parameterized |√
Floating Point (IEEE 754-2008) |√
Atomic Memory Op Support |√
Caches |√
Viritual Memory |√
Boots Linux |√
Privileged Arch v1.11 |√
External Debug |√

## Getting Started

To get started with RISC-V BOOM, you can find our microarchitectural documentation [here](https://ccelio.github.io/riscv-boom-doc/) and the GitHub repository [here](https://github.com/ucb-bar/riscv-boom).
