# Coddy.Tech Verilog Journey

This repository is my learning log for Verilog syntax using Coddy.tech. I am going back to basics to rebuild my hardware foundations from scratch.

Coddy.Tech is an interactive, hands-on path consisting of 128 lessons, 112 coding challenges, and 5 practical projects using an in-browser `iverilog` sandbox.

[Coddy Verilog Page](https://coddy.tech/landing/verilog).

## Section 1: Fundamentals
* **Hardware vs. Software Concept:** Transitioning from sequential programming to concurrent hardware execution.
* **Basic Syntax & Structure:** Module declarations, inputs, outputs, named vs positional instantiation, and port mappings.
* **Data Types & Digital States:** Working with `wire` and `reg`, declaring multi-bit vectors, array slicing, and compile-time `parameter` definitions.
* **The 4 Fundamental Logic States:** Managing and debugging `0`, `1`, `X` (unknown state), and `Z` (high impedance).
* **Operators & Expressions:** Implementation of bitwise, logical, arithmetic, vector reduction, and bus concatenation (`{}`) operators.
* **Continuous Assignment:** Driving combinational nets using the `assign` statement.
* **Procedural Blocks:** Designing inside `always` and `initial` blocks, including behavioral decision making (`if-else`, `case`).
* **Behavioral Loops:** Utilising loops within procedural blocks for structural and iterative configurations.
* **Simulation & Behavioral Testing:** Printing debugging outputs using `$display` and `$monitor` system tasks alongside basic testbenches.
* **Foundational Projects:** Practical builds including a `Half Adder`, a `Multiplexer`, a `Traffic Light Controller`, and a basic `UART Module`.

## Section 2: RTL (Register-Transfer Level) Design
* **Combinational RTL:** Designing multi-bit arithmetic structures, multiplexer trees, and Arithmetic Logic Units (ALUs).
* **Signed Arithmetic:** Rules and handling of 2's complement, signed signals, and sign extension in hardware.
* **Sequential Logic & Synchronisation:** Mastering clock edges (`posedge`/`negedge`), non-blocking assignments (`<=`), registers, and counters.
* **Finite State Machines (FSMs):** Architecting Mealy and Moore state machines with separate state registers, next-state logic, and output logic.
* **Memory Blocks:** Declaring and implementing ROM (Read-Only Memory) and RAM (Random-Access Memory) structures.
* **Advanced Verification:** Writing automated, self-checking testbenches and robust test monitors to track complex hardware variations.
