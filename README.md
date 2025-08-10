# Right Shift Operation in Cadence Virtuoso

# Overview
This project implements a 4-bit Right Shift and left shift operation using Cadence Virtuoso, targeting custom VLSI design. The design is verified via schematic simulation

# Tools Used
- Cadence Virtuoso – schematic 
- ADE – simulation  

# Design Details
- Type of Shift*: Right Shift and Left shift 
- Inputs: D[3:0] – 4-bit input  
- Output: Q[3:0] – shifted output  
- Clocked: sequential  

# Features
- Verified using transient simulation* 
- Custom schematicdesigned in Virtuoso  

# Project Structure
/simulation/   → Testbenches & waveforms
/layout/       → Layout files (if done)
/docs/         → Screenshots & reports

#Screenshots
Included waveform and schematic images here:
- waveform.png – simulation proof  
- schematic.png – block-level design
  
#How to Simulate
1. Open *Cadence Virtuoso
2. Load project library
3. Open schematic and launch ADE
4. Run transient simulation  
