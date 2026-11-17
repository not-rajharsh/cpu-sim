# CPU Sim Lab — Computer System Architecture

Name: Harsh Raj
Roll No: 26570024
Course: B.Sc. (Hons.) Computer Science, Semester 1
College: Ramanujan College, University of Delhi
Paper: Computer System Architecture

Simulation of Mano's Basic Computer using CPU Sim 4.0.11 (Java 8 with JavaFX). Each practical has its own folder containing numbered screenshots of the machine setup and the output of that practical.

## Repository structure

CPU_Sim/
├── README.md
├── BasicComputer.cpu        <- machine used by all practicals
├── PRACTICAL_01/            <- Create Machine
├── PRACTICAL_02/            <- Fetch Routine
├── PRACTICAL_03/            <- ADD
├── PRACTICAL_04/            <- SUBTRACT
├── PRACTICAL_05/            <- Logical Operations
├── PRACTICAL_06/            <- Memory Reference
├── PRACTICAL_07/            <- CLA, CMA, CME, HLT
├── PRACTICAL_08/            <- INC, SPA, SNA, SZE
├── PRACTICAL_09/            <- CIR, CIL
├── PRACTICAL_10/            <- Sum Until Negative
└── PRACTICAL_11/            <- Sum Until Zero

Inside each `PRACTICAL_NN` folder the screenshots are named `1.jpeg`, `2.jpeg`, `3.jpeg`, … in the order they were captured.

## How to run

1. Install Java 8 with JavaFX (for example Azul Zulu JDK FX 8) and download CPU Sim 4.0.11.
2. Start CPU Sim (Cpusim4.bat).
3. File → Open machine… and choose `BasicComputer.cpu`.
4. File → Open text… and open the program for the practical (if you have the `.a` source).
5. Press Ctrl+2 to assemble and load.
6. Press Ctrl+R to run, or Ctrl+D to debug with Step by Instr / Step by Micro.
7. For programs that read input, type a number in the yellow console and press Enter.
8. Example (Practical 3): for the ADD program, press Ctrl+2, then Ctrl+R, and enter 25 and 17.

## Notes

1. Practical 2 uses the same machine file as Practical 1; its screenshots show the fetch routine executed one microinstruction at a time.
2. Register values in the debug traces are shown in Unsigned Dec; the RAM pane is shown in Hex.
