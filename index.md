---
layout: page
title: RISC-V BOOM 
subtitle: The Berkeley Out-of-Order RISC-V Processor 
use-site-title: true
---

The Berkeley Out-of-Order Machine (BOOM) is a synthesizable and parameterizable open
source RV64GC RISC-V core written in the [Chisel](https://chisel.eecs.berkeley.edu/)
hardware construction language. While BOOM is primarily ASIC optimized, it is also
usable on FPGAs. We support the FireSim flow to run BOOM at 90+ MHz on FPGAs on
Amazon EC2 F1. Created at the University of California, Berkeley in the
[Berkeley Architecture Research](https://bar.eecs.berkeley.edu/) group, its focus is
to create a high performance, synthesizable, and parameterizable core for
architecture research.

## Features 

Feature | BOOM
--- | ---
ISA | RISC-V (RV64GC)
Synthesizable |√
FPGA |√
Parameterized |√
Floating Point (IEEE 754-2008) |√
Atomic Memory Op Support |√
Caches |√
Virtual Memory |√
Boots Linux |√
Privileged Arch v1.11 |√
External Debug |√

## Getting Started

To get started with RISC-V BOOM, you can find our microarchitectural documentation
[here](https://docs.boom-core.org/), the GitHub organization
[here](https://github.com/riscv-boom), and the mailing list
[here](https://groups.google.com/forum/#!forum/riscv-boom).
